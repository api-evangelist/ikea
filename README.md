# IKEA (ikea)

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

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/ikea/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ikea/refs/heads/main/apis.yml)

## Scope

- **Type:** Index

## Tags

- Retail
- Home Furnishings
- Consumer Products
- Opensource
- Community
- Unofficial API
- Smart Home

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-30

## APIs

### IKEA Product Catalog API (Unofficial)

Unofficial reverse-engineered specification for IKEA's public storefront product catalog. Exposes store metadata (informera/stores-detailed.json), the global category and navigation tree (catalog-products-slim.json) and per-product detail endpoints under www.ikea.com/{country}/{language}. Authored and maintained by idelsink/ikea-openapi based on observed network traffic. This is not an official IKEA developer API.

- **Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)
- **Base URL:** `https://www.ikea.com/{country}/{language}`

#### Tags

- Product Catalog
- Categories
- Stores
- Products
- Unofficial API
- Opensource

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ikea/main/openapi/ikea-product-catalog-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/product-catalog/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/product-catalog)
- [Postman Collection](collections/ikea-after-purchase-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-after-purchase-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-product-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-product-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-sales-item.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-sales-item.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IKEA Search API (Unofficial)

Unofficial reverse-engineered specification for IKEA's product search service hosted at sik.search.blue.cdtapps.com. Supports paginated product list pages and filtered search across IKEA's storefront catalogue. This is the only one of the four idelsink specs that the IKEA-hosted endpoint exposes with permissive CORS, so it is the easiest to exercise from a browser. Authored and maintained by idelsink/ikea-openapi. Not an official IKEA developer API.

- **Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)
- **Base URL:** `https://sik.search.blue.cdtapps.com/{country}/{language}`

#### Tags

- Search
- Products
- Unofficial API
- Opensource

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ikea/main/openapi/ikea-search-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/search/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/search)
- [Postman Collection](collections/ikea-after-purchase-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-after-purchase-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-product-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-product-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-sales-item.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-sales-item.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IKEA Sales Item API (Unofficial)

Unofficial reverse-engineered specification for IKEA's real-time availability service hosted at api.salesitem.ingka.com. Returns per-store and per-class-unit availability and packaging information for IKEA articles. Used by community projects like ikea-availability-checker and ikeaStockChecker. Authored and maintained by idelsink/ikea-openapi. Not an official IKEA developer API.

- **Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)
- **Base URL:** `https://api.salesitem.ingka.com`

#### Tags

- Availability
- Stock
- Stores
- Sales Items
- Unofficial API
- Opensource

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ikea/main/openapi/ikea-sales-item-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/sales-item/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/sales-item)
- [Postman Collection](collections/ikea-after-purchase-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-after-purchase-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-product-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-product-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-sales-item.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-sales-item.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IKEA After Purchase Ordering API (Unofficial)

Unofficial reverse-engineered specification for IKEA's spare-parts and After Purchase Ordering (APO) service. Lets shoppers look up replacement parts by partial or full part ID and browse the catalogue of orderable spare parts attached to IKEA products. Authored and maintained by idelsink/ikea-openapi. Not an official IKEA developer API.

- **Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)

#### Tags

- After Purchase
- Spare Parts
- Aftermarket
- Unofficial API
- Opensource

#### Properties

- [OpenAPI](https://raw.githubusercontent.com/api-evangelist/ikea/main/openapi/ikea-after-purchase-ordering-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/after-purchase-ordering/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/after-purchase-ordering)
- [Postman Collection](collections/ikea-after-purchase-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-after-purchase-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-product-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-product-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-sales-item.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-sales-item.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### IKEA DIRIGERA Smart Home Hub API (Unofficial, Local)

The DIRIGERA hub is IKEA's next-generation smart home gateway (replacing TRADFRI). It exposes a private, locally-served REST API on the LAN with bearer-token authentication (token obtained by pressing the action button on the hub). There is no public OpenAPI from IKEA; the community has produced several SDKs that document and consume the surface — Leggin/dirigera (Python), lpgera/dirigera (TypeScript), dvdgeisler/DirigeraClient (Java), bombsimon/dirigera-rs (Rust). Resources include lights, outlets, blinds, air purifiers, environment sensors, motion sensors, open/close sensors, scenes, rooms and an event listener websocket. Not an official IKEA developer API.

- **Human URL:** [https://github.com/Leggin/dirigera](https://github.com/Leggin/dirigera)

#### Tags

- Smart Home
- DIRIGERA
- IoT
- Local API
- Unofficial API
- Opensource

#### Properties

- [SDK](https://github.com/Leggin/dirigera)
- [SDK](https://github.com/lpgera/dirigera)
- [SDK](https://github.com/dvdgeisler/DirigeraClient)
- [SDK](https://github.com/bombsimon/dirigera-rs)
- [Integrations](https://github.com/sanjoyg/dirigera_platform)
- [Integrations](https://github.com/uboness/homebridge-dirigera)
- [Tools](https://github.com/lpgera/dirigera-web)
- [Postman Collection](collections/ikea-after-purchase-ordering.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-after-purchase-ordering.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-product-catalog.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-product-catalog.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-sales-item.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-sales-item.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Postman Collection](collections/ikea-search.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/ikea-search.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [GitHub Organization](https://github.com/IKEA)
- [LinkedIn](https://www.linkedin.com/company/ikea)
- [Website](https://www.ikea.com/)
- [Corporate Site](https://www.inter.ikea.com/)
- [SDK](https://pypi.org/project/ikea_api/)
- [Source Code](https://github.com/idelsink/ikea-openapi)
- [Source Code](https://github.com/IKEA/IKEA3DAssemblyDataset)
- [Code Examples](https://github.com/Ephigenia/ikea-availability-checker)
- [Code Examples](https://github.com/DavisChappins/ikeaStockChecker)
- [Code Examples](https://github.com/Mirzaei81/ikeaScraper)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
