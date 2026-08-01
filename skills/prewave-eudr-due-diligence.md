---
name: File EUDR due-diligence statements
description: Register products, request commodity origins from suppliers, and submit EUDR Due Diligence Statements.
api: openapi/prewave-openapi-original.json
operations: [addOutboundProduct, requestOrigins, findCustomerOriginRequests, addCustomerDDS, submitCustomerDDS, findCustomerDDS]
---

# File EUDR due-diligence statements

Complete EU Deforestation Regulation (EUDR) due diligence with the Public Prewave API.
Authenticate with the `X-Auth-Token` header.

## Steps
1. **Register the outbound product** — `POST /public/v2/eudr/customers/products/outbound`
   (`addOutboundProduct`). Look up HS codes, countries, and commodities from the EUDR - Shared
   endpoints (`findHSCodes`, `findCountries`, `findCommodities`).
2. **Request origins from suppliers** — `POST /public/v2/eudr/customers/origin-requests`
   (`requestOrigins`); track them with `GET /public/v2/eudr/customers/products/{productId}/origin-requests`
   (`findCustomerOriginRequests`). An unsupported product returns `422`
   (`OriginRequestProductUnsupportedErrorDTO`).
3. **Attach a Due Diligence Statement** — `POST /public/v2/eudr/customers/products/{productId}/customer-dds`
   (`addCustomerDDS`); list existing ones with `findCustomerDDS`.
4. **Submit the DDS** — `PUT /public/v2/eudr/customers/customer-dds/{ddsId}/submission`
   (`submitCustomerDDS`).

## Rules
- Errors use the `ErrorDTO` envelope; validate HS codes/commodities against the Shared endpoints first.
- Handle `429` rate limits with backoff. Page lists with `page`/`size`.
- See `data-model/prewave-data-model.yml` for the Product -> Origin Request -> DDS relationships.
