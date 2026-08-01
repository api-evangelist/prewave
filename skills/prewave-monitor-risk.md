---
name: Monitor supplier risk alerts and scores
description: Poll the Prewave alert feed and read target risk scores to monitor supply-chain risk.
api: openapi/prewave-openapi-original.json
operations: [alertFeed, targetAlerts, getScoreResults, getExternalScoresForTargetByIdentifier, getAllCollections]
---

# Monitor supplier risk alerts and scores

Track risk against your supplier portfolio using the Public Prewave API. Authenticate with the
`X-Auth-Token` header.

## Steps
1. **Enumerate your collections** — `GET /public/v1/collections` (`getAllCollections`) to find the
   supplier groupings to monitor.
2. **Pull the alert feed** — `GET /public/v2/feed` (`alertFeed`) for new risk/disruption events;
   page with `page`/`size`.
3. **Read alerts for one target** — `GET /public/v1/target/{systemId}/{targetId}/alerts`
   (`targetAlerts`) to drill into a specific supplier.
4. **Read risk scores** — `GET /public/v1/enterprise-export/scores` (`getScoreResults`) for the
   enterprise export, or `GET /public/v1/scores/externals` (`getExternalScoresForTargetByIdentifier`)
   for identifier-based external scores.

## Rules
- Prefer the v2 feed (`alertFeed`); the v1 feed (`alertFeed_1`) and the legacy
  `score`/`score-history` target endpoints are deprecated (RFC 8594 Sunset; migrate by 2027-05-31).
- Errors use `ErrorDTO`; rate limits return `429` (`ApiRateLimitResponse`).
- See `conventions/prewave-conventions.yml` for pagination and rate-limit signaling.
