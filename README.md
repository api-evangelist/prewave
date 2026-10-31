# Prewave

<!-- API-EVANGELIST-PROVENANCE:BEGIN -->
> ### About this repository
>
> **This is not our API.** This repository is an independent, third-party profile of a company's
> **publicly available** API surface, maintained by [API Evangelist](https://apievangelist.com).
> API Evangelist does not operate, host, resell, or support this company's APIs, and is not
> affiliated with or endorsed by the company unless stated on the profile.
>
> **Where the information came from.** Everything here is assembled from material a member of the
> public can reach with a browser and no credentials — the company's own website, developer portal
> and documentation, the specifications it publishes for public use (OpenAPI, AsyncAPI, JSON Schema,
> `apis.json`, `llms.txt` and similar), its public repositories, and its public status, pricing and
> changelog pages. **Nothing here is obtained by breaching a system, defeating an access control, or
> using credentials of any kind.**
>
> **The rating is an independent assessment.** The Kin Score and Agent Readiness rating are
> independently calculated scores of a company's *public* API artifacts, produced by API Evangelist
> against a published rubric. They are not certifications, endorsements, security assessments, or
> audits, and they score published artifacts — not the quality, safety, or security of the software.
>
> **Corrections, re-scores, and removal are free.** No partnership, contract, or purchase is
> required, and you do not need to justify the request.
>
> - **Something wrong?** Open an issue on this repository, or email
>   [info@apievangelist.com](mailto:info@apievangelist.com).
> - **Published something new?** Ask for a re-score and we will re-run the rating.
> - **Want the listing taken down?** Say so and we will honor it. The profile is reduced to your
>   company name, a factual description, and a link to your own site, and the company is recorded as
>   **unrated** — never scored zero for having asked.
>
> **Response times.** Acknowledgement within **one business day**; removal or restriction within
> **two business days**; corrections and re-scores within **five business days**.
>
> **Not from the company, and here with a question?** You are welcome here — we would rather be the
> front line and point you the right way than have a good report go nowhere. What this repository
> can answer is narrow, though, so it is worth knowing who you are actually looking for:
>
> - **A question about how the API works, an account, billing, or a bug in the service** — that is
>   the company's own support, not us. We profile this API; we do not operate it and cannot see
>   your account.
> - **A bug in an open-source project we only catalog** — file it on that project's own repository.
>   This has happened with a real and correct bug report that reached us instead of the people who
>   could fix it, which helped nobody.
> - **Anything about this listing itself** — the description, the tags, the rating, a missing or
>   wrong artifact — is ours. Open an issue here.
> - **Not sure, or something general about API Evangelist or APIs.io** — open an issue on the
>   [APIs.io Inbox](https://github.com/api-search/inbox) and we will route it.
>
> **This repository contains no software, and we will never ask you to download anything.** There is
> no build, release, installer, or binary here — only text and machine-readable API descriptions, so
> there is nothing here that can be "corrupt" or need "repairing". Any issue, comment, or email
> claiming otherwise and offering a download link is not from us and is hostile. Do not follow the
> link; it is a lure. Report it to GitHub and, if you like, tell us at
> [info@apievangelist.com](mailto:info@apievangelist.com) so we can take it down.
>
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

Prewave is a Vienna-based AI-powered supply-chain risk intelligence platform that monitors millions of risk events across languages and networks to give enterprises proactive resilience, multi-tier supplier transparency, and sustainability-compliance automation (EU Deforestation Regulation, LkSG, and CSDDD). The Public Prewave API is a REST API at api.prewave.com covering suppliers and sites, collections and the Tier-N supplier graph, alerts and the risk feed, disruptions, risk scores (target, external, and enterprise export), exposure graphs, EUDR products / origin requests / Due Diligence Statements, actions, and user and role management. It authenticates with an X-Auth-Token API key.

**Areas:** Company · Software-as-a-Service · Supply Chain · Risk Intelligence · Sustainability · Compliance · EUDR · Supplier Management

## Prewave on APIs.io

Everything profiled for Prewave is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/prewave/](https://apis.io/providers/prewave/)** — or go straight to one of the APIs or properties below.

### APIs (25)

- [Prewave Actions API](https://apis.io/apis/prewave/prewave-actions-api/) — 🆕 NEW - Retrieve actions (tasks/work items), action types, and action statuses for supplier relationships, compliance reviews, and operational activities.…
- [Prewave Alerts API](https://apis.io/apis/prewave/prewave-alerts-api/) — Endpoints for retrieving alert information from user feeds, disruption maps, and specific targets. Supports filtering by collections, dates, priorities,…
- [Prewave Collections - Management API](https://apis.io/apis/prewave/prewave-collections-management-api/) — Public API for managing collections in Prewave's supply chain network. Collections are used to organize and group suppliers (targets) in your supply chain.
- [Prewave Collections - Network API](https://apis.io/apis/prewave/prewave-collections-network-api/) — Allows you to retrieve network information. Like tree-graph and commodity-graph.
- [Prewave Collections - Targets API](https://apis.io/apis/prewave/prewave-collections-targets-api/) — Public API for managing targets within collections in Prewave's supply chain network.
- [Prewave Collections - Tier-N API](https://apis.io/apis/prewave/prewave-collections-tier-n-api/) — Public API for retrieving supplier relationship graphs from tier-n enabled collections.
- [Prewave Disruptions API](https://apis.io/apis/prewave/prewave-disruptions-api/) — Endpoints for retrieving alerts from the disruption map. Supports filtering by geographic region, collections, countries, and other criteria.
- [Prewave EUDR - Customers - DDS API](https://apis.io/apis/prewave/prewave-eudr-customers-dds-api/) — 🆕 NEW - Allows you to manage customer Due Diligence Statements (DDS), including creating, updating, submitting, withdrawing customer DDS, and viewing…
- [Prewave EUDR - Customers - Origin Requests API](https://apis.io/apis/prewave/prewave-eudr-customers-origin-requests-api/) — Allows you to manage customer origin requests for products, including creating, updating, closing requests, and viewing requests per product.
- [Prewave EUDR - Customers - Products API](https://apis.io/apis/prewave/prewave-eudr-customers-products-api/) — Allows you to manage customer products, including creating, updating, linking/unlinking products, and deactivating products.
- [Prewave EUDR - Customers - Suppliers API](https://apis.io/apis/prewave/prewave-eudr-customers-suppliers-api/) — Allows you to search for suppliers, find suppliers by IDs or references, and manage supplier connection contacts.
- [Prewave EUDR - Shared API](https://apis.io/apis/prewave/prewave-eudr-shared-api/) — Shared reference data for EUDR, including countries, HS codes, and commodities. Available to both customers and suppliers.
- [Prewave EUDR - Suppliers API](https://apis.io/apis/prewave/prewave-eudr-suppliers-api/) — Allows suppliers to manage their origin requests, view their customers, and answer origin requests with supplier DDS.
- [Prewave Exposure API](https://apis.io/apis/prewave/prewave-exposure-api/) — Get exposure analysis graph and targets
- [Prewave Infotags API](https://apis.io/apis/prewave/prewave-infotags-api/) — Allows you to retrieve information about infotags and groups.
- [Prewave Scores - Enterprise Export API](https://apis.io/apis/prewave/prewave-scores-enterprise-export-api/) — Public API for managing enterprise export configurations and retrieving score data in Prewave's supply chain network.
- [Prewave Scores - Externals API](https://apis.io/apis/prewave/prewave-scores-externals-api/) — Upload and read custom supplier scores from your systems (e.g. SAP). Bulk upload, list event types, and view history per supplier. Available from June 2026.
- [Prewave Scores - Target API](https://apis.io/apis/prewave/prewave-scores-target-api/) — ⚠️ **DEPRECATED** - Target score endpoints. These endpoints are deprecated and will be removed at the end of December 2026. Use…
- [Prewave Suppliers - Connection Contacts API](https://apis.io/apis/prewave/prewave-suppliers-connection-contacts-api/) — 🆕 NEW - Supplier connection contact management endpoints. Available from February 2026.
- [Prewave Suppliers - Management API](https://apis.io/apis/prewave/prewave-suppliers-management-api/) — Supplier management endpoints for listing, retrieving, updating supplier data, and bulk operations.
- [Prewave Suppliers - Sites API](https://apis.io/apis/prewave/prewave-suppliers-sites-api/) — 🆕 NEW - Supplier and site management endpoints. Available from January 2026.
- [Prewave Suppliers - Sites Upsert API](https://apis.io/apis/prewave/prewave-suppliers-sites-upsert-api/) — Allows you to create or update sites.
- [Prewave Suppliers - Supplier Graph API](https://apis.io/apis/prewave/prewave-suppliers-supplier-graph-api/) — ⚠️ **DEPRECATED** - This API is deprecated and will be removed at the end of December 2026.
- [Prewave Users API](https://apis.io/apis/prewave/prewave-users-api/) — 🆕 NEW - API to manage users in the public network. Available from February 2026.
- [Prewave Users - Roles API](https://apis.io/apis/prewave/prewave-users-roles-api/) — 🆕 NEW - API to manage user roles in the public network. Available from February 2026.

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Arazzo workflows (2)

Multi-step workflows that chain operations into a business task.

- [Submit an EUDR Due Diligence Statement](https://apis.io/arazzos/prewave/prewave-eudr-dds-submission/)
- [Onboard and monitor a supplier](https://apis.io/arazzos/prewave/prewave-onboard-and-monitor-supplier/)

#### MCP servers (1)

Model Context Protocol servers that expose the API to agents.

- [prewave](https://apis.io/servers/prewave/prewave/)

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Prewave Agentic Access](https://apis.io/agentic-access/prewave/prewave-agentic-access/)

#### Collections (25)

Postman and Open Collection request collections.

- [Public Prewave Actions API](https://apis.io/collections/prewave/open-prewave-actions-api/)
- [Public Prewave Actions Alerts API](https://apis.io/collections/prewave/open-prewave-alerts-api/)
- [Public Prewave Actions Collections - Management API](https://apis.io/collections/prewave/open-prewave-collections-management-api/)
- [Public Prewave Actions Collections - Network API](https://apis.io/collections/prewave/open-prewave-collections-network-api/)
- [Public Prewave Actions Collections - Targets API](https://apis.io/collections/prewave/open-prewave-collections-targets-api/)
- [Public Prewave Actions Collections - Tier-N API](https://apis.io/collections/prewave/open-prewave-collections-tier-n-api/)
- [Public Prewave Actions Disruptions API](https://apis.io/collections/prewave/open-prewave-disruptions-api/)
- [Public Prewave Actions EUDR - Customers - DDS API](https://apis.io/collections/prewave/open-prewave-eudr-customers-dds-api/)
- [Public Prewave Actions EUDR - Customers - Origin Requests API](https://apis.io/collections/prewave/open-prewave-eudr-customers-origin-requests-api/)
- [Public Prewave Actions EUDR - Customers - Products API](https://apis.io/collections/prewave/open-prewave-eudr-customers-products-api/)
- [Public Prewave Actions EUDR - Customers - Suppliers API](https://apis.io/collections/prewave/open-prewave-eudr-customers-suppliers-api/)
- [Public Prewave Actions EUDR - Shared API](https://apis.io/collections/prewave/open-prewave-eudr-shared-api/)
- [Public Prewave Actions EUDR - Suppliers API](https://apis.io/collections/prewave/open-prewave-eudr-suppliers-api/)
- [Public Prewave Actions Exposure API](https://apis.io/collections/prewave/open-prewave-exposure-api/)
- [Public Prewave Actions Infotags API](https://apis.io/collections/prewave/open-prewave-infotags-api/)
- [Public Prewave Actions Scores - Enterprise Export API](https://apis.io/collections/prewave/open-prewave-scores-enterprise-export-api/)
- [Public Prewave Actions Scores - Externals API](https://apis.io/collections/prewave/open-prewave-scores-externals-api/)
- [Public Prewave Actions Scores - Target API](https://apis.io/collections/prewave/open-prewave-scores-target-api/)
- [Public Prewave Actions Suppliers - Connection Contacts API](https://apis.io/collections/prewave/open-prewave-suppliers-connection-contacts-api/)
- [Public Prewave Actions Suppliers - Management API](https://apis.io/collections/prewave/open-prewave-suppliers-management-api/)
- [Public Prewave Actions Suppliers - Sites API](https://apis.io/collections/prewave/open-prewave-suppliers-sites-api/)
- [Public Prewave Actions Suppliers - Sites Upsert API](https://apis.io/collections/prewave/open-prewave-suppliers-sites-upsert-api/)
- [Public Prewave Actions Suppliers - Supplier Graph API](https://apis.io/collections/prewave/open-prewave-suppliers-supplier-graph-api/)
- [Public Prewave Actions Users API](https://apis.io/collections/prewave/open-prewave-users-api/)
- [Public Prewave Actions Users - Roles API](https://apis.io/collections/prewave/open-prewave-users-roles-api/)

#### Overlays (1)

OpenAPI overlays, including conversational phrasing for each operation.

- [Prewave Openapi Overlay](https://apis.io/overlays/prewave/prewave-openapi-overlay/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Prewave Authentication](https://apis.io/security/prewave/prewave-authentication/)
- [Prewave Domain Security](https://apis.io/security/prewave/prewave-domain-security/)
- [Prewave Trust Center](https://apis.io/security/prewave/prewave-trust-center/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.prewave.com/)
- [Documentation](https://docs.prewave.com/)
- [API reference](https://dev.prewave.com)
- [Blog](https://www.prewave.com/resources/blog/)
- [Trust centre](https://trust.prewave.com/)
- [Terms of service](https://www.prewave.com/terms-of-service)
- [Privacy policy](https://www.prewave.com/privacy-policy)
- [GitHub](https://github.com/prewave)
- [Status](https://status.prewave.com/)

## API Evangelist rating

**Kin Score 44.5** — developing · rubric 0.25.0 · scored 2026-10-23

| Facet | Score |
|---|---|
| Discoverability | 73.2 |
| Contract quality | 52.7 |
| Contract governance | 4.5 |
| Operational transparency | 34.2 |
| Developer ergonomics | 42.3 |
| Access clarity | 28.9 |

**Agent readiness 31.1** — agent-ready

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | — |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | — |
| Error Semantics | verified |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | derived (partial credit) |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | yes |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |
| Pagination Ratio | — |
| Operation Distinctiveness | mostly |

**Regulatory alignment 29.4** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/prewave/](https://apis.io/providers/prewave/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for Prewave: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/prewave/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
