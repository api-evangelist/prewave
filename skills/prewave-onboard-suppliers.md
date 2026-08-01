---
name: Onboard and screen suppliers
description: Create supplier sites in Prewave, then run validation and screening to complete onboarding.
api: openapi/prewave-openapi-original.json
operations: [createSupplier, getValidationStatus, requestValidation, requestScreening, getScreeningStatus, findSuppliers]
---

# Onboard and screen suppliers

Use the Public Prewave API (base `https://api.prewave.com`) to add supplier sites and complete
onboarding checks. Authenticate every request with the `X-Auth-Token` header (token from
https://www.prewave.com/management/api).

## Steps
1. **Create the supplier site** — `POST /public/v2/suppliers/sites` (`createSupplier`). Supply the
   supplier identifiers and site details. Batch writes may return `202 Accepted` with a `Location`
   header pointing at the request-status resource.
2. **Check for an existing match first** — `GET /public/v2/suppliers/sites/find-by-identifier`
   (`findSuppliers`) to avoid duplicate sites (a duplicate identifier returns `409 Conflict`).
3. **Request validation** — `POST /public/v2/suppliers/sites/validation` (`requestValidation`),
   then poll `GET /public/v2/suppliers/sites/validation` (`getValidationStatus`).
4. **Request screening** — `POST /public/v2/suppliers/sites/screening` (`requestScreening`), then
   poll `GET /public/v2/suppliers/sites/screening` (`getScreeningStatus`).

## Rules
- Errors use the `ErrorDTO` envelope (`code`, `message`, `solution`) — see `errors/prewave-error-codes.yml`.
- Handle `429` (`ApiRateLimitResponse`) by backing off; inspect `requestLimit`/`requestCount`.
- Paginate list calls with `page` and `size`. No idempotency key is supported, so de-dupe with
  `findSuppliers` before creating.
