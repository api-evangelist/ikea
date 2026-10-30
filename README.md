# IKEA

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

A Swedish multinational furniture and home goods retailer known for its affordable, ready-to-assemble products. Operates hundreds of stores worldwide and is the world's largest furniture retailer with a distinctive showroom-based shopping experience. IKEA does not publish an official public developer API or developer portal; the surfaces profiled here are community reverse-engineered specs of the IKEA storefront (Product Catalog, Search, Sales Item availability, After Purchase Ordering / spare parts) plus the local-network API of the DIRIGERA smart home hub. All artifacts are community-built and unofficial — they may change at any time and are not affiliated with, endorsed by, or supported by IKEA.

**Areas:** Retail · Home Furnishings · Consumer Products · Open Source · Community · Unofficial API · Smart Home

## IKEA on APIs.io

Everything profiled for IKEA is published on APIs.io rather than in this repository. Start at the provider page — **[apis.io/providers/ikea/](https://apis.io/providers/ikea/)** — or go straight to one of the APIs or properties below.

### APIs (6)

- [IKEA DIRIGERA Smart Home Hub API (Unofficial, Local)](https://apis.io/apis/ikea/dirigera-hub/) — The DIRIGERA hub is IKEA's next-generation smart home gateway (replacing TRADFRI). It exposes a private, locally-served REST API on the LAN with…
- [IKEA Availability API](https://apis.io/apis/ikea/ikea-availability-api/) — Everything about Availability
- [IKEA Categories API](https://apis.io/apis/ikea/ikea-categories-api/) — Everything about Categories
- [IKEA Parts API](https://apis.io/apis/ikea/ikea-parts-api/) — Everything about Parts
- [IKEA Products API](https://apis.io/apis/ikea/ikea-products-api/) — Everything about Products
- [IKEA Stores API](https://apis.io/apis/ikea/ikea-stores-api/) — Everything about Stores

### Published properties

Each property below is a page on APIs.io carrying the machine-readable artifact and what it says.

#### Agentic access (1)

Which operations an agent can call, which act, and which need a human in the loop.

- [Ikea Agentic Access](https://apis.io/agentic-access/ikea/ikea-agentic-access/)

#### JSON Schema (21)

The data models the API reads and writes.

- [Part](https://apis.io/schemas/ikea/ikea-after-purchase-ordering-part/)
- [ProductParts](https://apis.io/schemas/ikea/ikea-after-purchase-ordering-product-parts/)
- [SearchPart](https://apis.io/schemas/ikea/ikea-after-purchase-ordering-search-part/)
- [status](https://apis.io/schemas/ikea/ikea-after-purchase-ordering-status/)
- [Category](https://apis.io/schemas/ikea/ikea-product-catalog-category/)
- [ProductDetails](https://apis.io/schemas/ikea/ikea-product-catalog-product-details/)
- [Store](https://apis.io/schemas/ikea/ikea-product-catalog-store/)
- [Availability](https://apis.io/schemas/ikea/ikea-sales-item-availability/)
- [AvailabilityEnvelope](https://apis.io/schemas/ikea/ikea-sales-item-availability-envelope/)
- [AvailabilityError](https://apis.io/schemas/ikea/ikea-sales-item-availability-error/)
- [ClassUnitKey](https://apis.io/schemas/ikea/ikea-sales-item-class-unit-key/)
- [expandOption](https://apis.io/schemas/ikea/ikea-sales-item-expand-option/)
- [ItemKey](https://apis.io/schemas/ikea/ikea-sales-item-item-key/)
- [itemType](https://apis.io/schemas/ikea/ikea-sales-item-item-type/)
- [SalesLocation](https://apis.io/schemas/ikea/ikea-sales-item-sales-location/)
- [Category](https://apis.io/schemas/ikea/ikea-search-category/)
- [CommonProperties](https://apis.io/schemas/ikea/ikea-search-common-properties/)
- [itemType](https://apis.io/schemas/ikea/ikea-search-item-type/)
- [MoreProductsEnvelope](https://apis.io/schemas/ikea/ikea-search-more-products-envelope/)
- [Product](https://apis.io/schemas/ikea/ikea-search-product/)
- [ProductListPageEnvelope](https://apis.io/schemas/ikea/ikea-search-product-list-page-envelope/)

#### JSON Structure (21)

Data models expressed in JSON Structure.

- [Ikea After Purchase Ordering Part Structure](https://apis.io/json-structure/ikea/ikea-after-purchase-ordering-part-structure/)
- [Ikea After Purchase Ordering Product Parts Structure](https://apis.io/json-structure/ikea/ikea-after-purchase-ordering-product-parts-structure/)
- [Ikea After Purchase Ordering Search Part Structure](https://apis.io/json-structure/ikea/ikea-after-purchase-ordering-search-part-structure/)
- [Ikea After Purchase Ordering Status Structure](https://apis.io/json-structure/ikea/ikea-after-purchase-ordering-status-structure/)
- [Ikea Product Catalog Category Structure](https://apis.io/json-structure/ikea/ikea-product-catalog-category-structure/)
- [Ikea Product Catalog Product Details Structure](https://apis.io/json-structure/ikea/ikea-product-catalog-product-details-structure/)
- [Ikea Product Catalog Store Structure](https://apis.io/json-structure/ikea/ikea-product-catalog-store-structure/)
- [Ikea Sales Item Availability Envelope Structure](https://apis.io/json-structure/ikea/ikea-sales-item-availability-envelope-structure/)
- [Ikea Sales Item Availability Error Structure](https://apis.io/json-structure/ikea/ikea-sales-item-availability-error-structure/)
- [Ikea Sales Item Availability Structure](https://apis.io/json-structure/ikea/ikea-sales-item-availability-structure/)
- [Ikea Sales Item Class Unit Key Structure](https://apis.io/json-structure/ikea/ikea-sales-item-class-unit-key-structure/)
- [Ikea Sales Item Expand Option Structure](https://apis.io/json-structure/ikea/ikea-sales-item-expand-option-structure/)
- [Ikea Sales Item Item Key Structure](https://apis.io/json-structure/ikea/ikea-sales-item-item-key-structure/)
- [Ikea Sales Item Item Type Structure](https://apis.io/json-structure/ikea/ikea-sales-item-item-type-structure/)
- [Ikea Sales Item Sales Location Structure](https://apis.io/json-structure/ikea/ikea-sales-item-sales-location-structure/)
- [Ikea Search Category Structure](https://apis.io/json-structure/ikea/ikea-search-category-structure/)
- [Ikea Search Common Properties Structure](https://apis.io/json-structure/ikea/ikea-search-common-properties-structure/)
- [Ikea Search Item Type Structure](https://apis.io/json-structure/ikea/ikea-search-item-type-structure/)
- [Ikea Search More Products Envelope Structure](https://apis.io/json-structure/ikea/ikea-search-more-products-envelope-structure/)
- [Ikea Search Product List Page Envelope Structure](https://apis.io/json-structure/ikea/ikea-search-product-list-page-envelope-structure/)
- [Ikea Search Product Structure](https://apis.io/json-structure/ikea/ikea-search-product-structure/)

#### JSON-LD (4)

Linked-data contexts for the provider's vocabulary.

- [Ikea After Purchase Ordering Context](https://apis.io/jsonld/ikea/ikea-after-purchase-ordering-context/)
- [Ikea Product Catalog Context](https://apis.io/jsonld/ikea/ikea-product-catalog-context/)
- [Ikea Sales Item Context](https://apis.io/jsonld/ikea/ikea-sales-item-context/)
- [Ikea Search Context](https://apis.io/jsonld/ikea/ikea-search-context/)

#### Vocabulary (1)

The provider's domain terms, defined.

- [Ikea Vocabulary](https://apis.io/vocabularies/ikea/ikea-vocabulary/)

#### Examples (5)

Example requests and responses.

- [Ikea After Purchase Ordering Get Part By Id Example](https://apis.io/examples/ikea/ikea-after-purchase-ordering-get-part-by-id-example/)
- [Ikea Product Catalog Get Product By Id Example](https://apis.io/examples/ikea/ikea-product-catalog-get-product-by-id-example/)
- [Ikea Sales Item Get Product Availability Example](https://apis.io/examples/ikea/ikea-sales-item-get-product-availability-example/)
- [Ikea Search Find Products Example](https://apis.io/examples/ikea/ikea-search-find-products-example/)
- [Ikea Search Find Products Paginated Example](https://apis.io/examples/ikea/ikea-search-find-products-paginated-example/)

#### Collections (9)

Postman and Open Collection request collections.

- [IKEA After Purchase Ordering API](https://apis.io/collections/ikea/open-ikea-after-purchase-ordering/)
- [IKEA After Purchase Ordering Availability API](https://apis.io/collections/ikea/open-ikea-availability-api/)
- [IKEA After Purchase Ordering Availability Categories API](https://apis.io/collections/ikea/open-ikea-categories-api/)
- [IKEA After Purchase Ordering Availability Parts API](https://apis.io/collections/ikea/open-ikea-parts-api/)
- [IKEA Product Catalog API](https://apis.io/collections/ikea/open-ikea-product-catalog/)
- [IKEA After Purchase Ordering Availability Products API](https://apis.io/collections/ikea/open-ikea-products-api/)
- [IKEA Sales Item API](https://apis.io/collections/ikea/open-ikea-sales-item/)
- [IKEA Search API](https://apis.io/collections/ikea/open-ikea-search/)
- [IKEA After Purchase Ordering Availability Stores API](https://apis.io/collections/ikea/open-ikea-stores-api/)

#### Governance rules (2)

Spectral rulesets for the provider's contracts.

- [IKEA — jsonschema rules](https://apis.io/rules/ikea/ikea-jsonschema-spectral-rules/)
- [IKEA API Rules](https://apis.io/rules/ikea/ikea-rules/)

#### Security (3)

Authentication, trust centre, and vulnerability disclosure.

- [Ikea Authentication](https://apis.io/security/ikea/ikea-authentication/)
- [Ikea Domain Security](https://apis.io/security/ikea/ikea-domain-security/)
- [Ikea Vulnerability Disclosure](https://apis.io/security/ikea/ikea-vulnerability-disclosure/)

## Where to find this API

Links to the company's own pages. This repository publishes no copy of their specifications — the canonical document is theirs and lives at the URLs below.

- [Website](https://www.ikea.com/)
- [Blog](https://www.ikea.com/global/en/newsroom/)
- [GitHub](https://github.com/IKEA)

## API Evangelist rating

**Kin Score 32.8** — thin · rubric 0.24.0 · scored 2026-10-17

| Facet | Score |
|---|---|
| Discoverability | 62.5 |
| Contract quality | 61.3 |
| Contract governance | 13.6 |
| Operational transparency | 2.6 |
| Developer ergonomics | 40.5 |
| Access clarity | 0.0 |

**Agent readiness 25.8** — agent-aware

| Agent-readiness dimension | Result |
|---|---|
| Spec Presence | yes |
| Agentic Access | derived (partial credit) |
| Reversibility Documented | na |
| MCP Server | — |
| Auth Clarity | bearer (partial credit) |
| Idempotency | na |
| Error Semantics | — |
| OpenAPI Examples | verified |
| Rate Limit Signal | — |
| Event Surface Described | — |
| Agent Skills | — |
| Well Known Catalog | — |
| Consent Identity | — |
| Agent Card | — |
| Dry Run Mode | na |
| Delegated Identity | — |
| Protected Resource Metadata | — |
| Dynamic Client Registration | — |
| Agentic Commerce | — |

**Regulatory alignment 22.5** — Horizontal (data, software, accessibility, platform)

The rubric is published at [github.com/api-evangelist/kin-score](https://github.com/api-evangelist/kin-score). The per-check breakdown behind these numbers — which checks were earned, partial or missed — along with score history and how this provider compares to its peers, is available at [apis.io/providers/ikea/](https://apis.io/providers/ikea/).

## How this profile is made

API Evangelist profiles a company's public API surface the way a developer would find it: the website, developer portal and documentation, the specifications it publishes, its public repositories, and its pricing, status and changelog pages. From that it derives the properties above — contracts split per API, workflows, schemas, collections, governance rules, plans and rate limits — and scores them against the published [Kin Score rubric](https://github.com/api-evangelist/kin-score).

The artifacts are published on [APIs.io](https://apis.io), not in this repository. This repository is the public record for IKEA: the place to say something is wrong, missing or out of date, and to ask for a re-score or a removal.

## Open an issue

- **Something about this listing** — a wrong description, a missing API, a stale artifact or a question about the rating: [open an issue on this repository](https://github.com/api-evangelist/ikea/issues/new).
- **A new API, or one that is not in the catalog yet** — [submit it on APIs.io](https://apis.io/add/).
- **Anything else** — [the APIs.io inbox](https://github.com/api-search/inbox/issues/new) or [info@apievangelist.com](mailto:info@apievangelist.com).
