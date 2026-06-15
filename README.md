# IKEA (ikea)

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
