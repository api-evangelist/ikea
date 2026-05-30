# IKEA (ikea)

A Swedish multinational furniture and home goods retailer known for its affordable, ready-to-assemble products. Operates hundreds of stores worldwide and is the world's largest furniture retailer with a distinctive showroom-based shopping experience. IKEA does not publish an official public developer API or developer portal; the surfaces profiled here are community reverse-engineered specs of the IKEA storefront (Product Catalog, Search, Sales Item availability, After Purchase Ordering / spare parts) plus the local-network API of the DIRIGERA smart home hub. All artifacts are community-built and unofficial — they may change at any time and are not affiliated with, endorsed by, or supported by IKEA.

**URL:** [https://raw.githubusercontent.com/api-evangelist/ikea/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/ikea/refs/heads/main/apis.yml)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=ikea-api-evangelist&utm_content=repo)

## Tags:

 - Retail, Home Furnishings, Consumer Products, Opensource, Community, Unofficial API, Smart Home

## Timestamps

- **Created:** 2026-05-05
- **Modified:** 2026-05-30

## APIs

### IKEA Product Catalog API (Unofficial)
Unofficial reverse-engineered specification for IKEA's public storefront product catalog. Exposes store metadata, the global category and navigation tree and per-product detail endpoints under `www.ikea.com/{country}/{language}`. Authored and maintained by `idelsink/ikea-openapi` based on observed network traffic. This is not an official IKEA developer API.

**Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)

**Base URL:** `https://www.ikea.com/{country}/{language}`

#### Tags:

 - Product Catalog, Categories, Stores, Products, Unofficial API, Opensource

#### Properties

- [OpenAPI](openapi/ikea-product-catalog-openapi.yml)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/product-catalog/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/product-catalog)

### IKEA Search API (Unofficial)
Unofficial reverse-engineered specification for IKEA's product search service hosted at `sik.search.blue.cdtapps.com`. Supports paginated product list pages and filtered search across IKEA's storefront catalogue. This is the only one of the four idelsink specs that the IKEA-hosted endpoint exposes with permissive CORS, so it is the easiest to exercise from a browser.

**Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)

**Base URL:** `https://sik.search.blue.cdtapps.com/{country}/{language}`

#### Tags:

 - Search, Products, Unofficial API, Opensource

#### Properties

- [OpenAPI](openapi/ikea-search-openapi.yml)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/search/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/search)

### IKEA Sales Item API (Unofficial)
Unofficial reverse-engineered specification for IKEA's real-time availability service hosted at `api.salesitem.ingka.com`. Returns per-store and per-class-unit availability and packaging information for IKEA articles. Used by community projects like `ikea-availability-checker` and `ikeaStockChecker`.

**Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)

**Base URL:** `https://api.salesitem.ingka.com`

#### Tags:

 - Availability, Stock, Stores, Sales Items, Unofficial API, Opensource

#### Properties

- [OpenAPI](openapi/ikea-sales-item-openapi.yml)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/sales-item/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/sales-item)

### IKEA After Purchase Ordering API (Unofficial)
Unofficial reverse-engineered specification for IKEA's spare-parts and After Purchase Ordering (APO) service. Lets shoppers look up replacement parts by partial or full part ID and browse the catalogue of orderable spare parts attached to IKEA products.

**Human URL:** [https://github.com/idelsink/ikea-openapi](https://github.com/idelsink/ikea-openapi)

#### Tags:

 - After Purchase, Spare Parts, Aftermarket, Unofficial API, Opensource

#### Properties

- [OpenAPI](openapi/ikea-after-purchase-ordering-openapi.yml)
- [Documentation](https://ingmar.dels.ink/ikea-openapi/after-purchase-ordering/)
- [Source Code](https://github.com/idelsink/ikea-openapi/tree/main/openapi/after-purchase-ordering)

### IKEA DIRIGERA Smart Home Hub API (Unofficial, Local)
The DIRIGERA hub is IKEA's next-generation smart home gateway (replacing TRADFRI). It exposes a private, locally-served REST API on the LAN with bearer-token authentication (token obtained by pressing the action button on the hub). There is no public OpenAPI from IKEA; the community has produced several SDKs that document and consume the surface.

**Human URL:** [https://github.com/Leggin/dirigera](https://github.com/Leggin/dirigera)

#### Tags:

 - Smart Home, DIRIGERA, IoT, Local API, Unofficial API, Opensource

#### Properties

- [Python Client (Leggin/dirigera)](https://github.com/Leggin/dirigera)
- [TypeScript Client (lpgera/dirigera)](https://github.com/lpgera/dirigera)
- [Java Client (dvdgeisler/DirigeraClient)](https://github.com/dvdgeisler/DirigeraClient)
- [Rust Client (bombsimon/dirigera-rs)](https://github.com/bombsimon/dirigera-rs)
- [Home Assistant Integration (sanjoyg/dirigera_platform)](https://github.com/sanjoyg/dirigera_platform)
- [Homebridge Plugin (uboness/homebridge-dirigera)](https://github.com/uboness/homebridge-dirigera)
- [Web UI (lpgera/dirigera-web)](https://github.com/lpgera/dirigera-web)

## Common Properties

- [GitHub Organization](https://github.com/IKEA)
- [LinkedIn](https://www.linkedin.com/company/ikea)
- [Website](https://www.ikea.com/)
- [Corporate Site](https://www.inter.ikea.com/)
- [Python ikea_api (vrslev/ikea-api-client, archived)](https://pypi.org/project/ikea_api/)
- [Community OpenAPI Specs (idelsink/ikea-openapi)](https://github.com/idelsink/ikea-openapi)
- [IKEA 3D Assembly Dataset](https://github.com/IKEA/IKEA3DAssemblyDataset)
- [ikea-availability-checker (Ephigenia)](https://github.com/Ephigenia/ikea-availability-checker)
- [ikeaStockChecker (DavisChappins)](https://github.com/DavisChappins/ikeaStockChecker)
- [ikeaScraper (Mirzaei81)](https://github.com/Mirzaei81/ikeaScraper)

## Features

| Name | Description |
|------|-------------|
| Community Reverse-Engineered Specs | Four OpenAPI 3.1 specifications (Product Catalog, Search, Sales Item, After Purchase Ordering) maintained by idelsink/ikea-openapi with daily contract tests against IKEA endpoints. |
| Real-Time Stock Availability | The Sales Item API surfaces per-store class-unit availability and packaging data used by stock-checker and price-tracker projects. |
| Spare Parts Lookup | The After Purchase Ordering API exposes IKEA's spare-parts catalogue, letting shoppers search by partial part ID and pull part metadata. |
| Local Smart Home Control | The DIRIGERA hub exposes a LAN-only REST API with token-based auth, allowing local-first automation of IKEA Home Smart devices without cloud round-trips. |
| Multi-Language SDK Ecosystem | Community SDKs exist for Python, TypeScript, Java and Rust covering the DIRIGERA hub plus a Python client (archived) covering the storefront cart, order capture, search and stock APIs. |

## Use Cases

| Name | Description |
|------|-------------|
| Stock and Price Monitoring | Track availability and price changes for specific IKEA products across stores and notify when restocks happen, using the Sales Item and Search APIs. |
| Spare Parts Self-Service | Build assistants that look up replacement parts by part ID and link shoppers to IKEA's order flow without scraping HTML. |
| Product Catalog Indexing | Mirror IKEA's category tree and store directory into search indexes, RAG pipelines or shopping aggregators using the Product Catalog API. |
| Local Smart Home Automation | Drive IKEA DIRIGERA-paired lights, outlets, blinds and air purifiers from Home Assistant, Homebridge or custom scripts entirely on the LAN. |
| Furniture Assembly Research | Use the IKEA 3D Assembly Dataset for academic work on instruction understanding, step segmentation, robotic assembly and computer vision. |

## Integrations

| Name | Description |
|------|-------------|
| Home Assistant | The `dirigera_platform` custom component integrates DIRIGERA-paired devices into Home Assistant as native entities. |
| Homebridge | The `homebridge-dirigera` plugin exposes DIRIGERA devices to Apple HomeKit via Homebridge. |
| GNOME Shell | The `vchlum/smart-home` GNOME Shell extension can drive DIRIGERA devices alongside Hue, Nanoleaf and Shelly. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [IKEA Product Catalog API](openapi/ikea-product-catalog-openapi.yml)
- [IKEA Search API](openapi/ikea-search-openapi.yml)
- [IKEA Sales Item API](openapi/ikea-sales-item-openapi.yml)
- [IKEA After Purchase Ordering API](openapi/ikea-after-purchase-ordering-openapi.yml)

### JSON Schema

21 standalone JSON Schema files extracted from the four OpenAPI specs (Product Catalog, Search, Sales Item, After Purchase Ordering). See [`json-schema/`](json-schema/).

### JSON Structure

21 JSON Structure (json-structure.org) representations converted from the JSON Schemas above. See [`json-structure/`](json-structure/).

### JSON-LD

- [Product Catalog Context](json-ld/ikea-product-catalog-context.jsonld)
- [Search Context](json-ld/ikea-search-context.jsonld)
- [Sales Item Context](json-ld/ikea-sales-item-context.jsonld)
- [After Purchase Ordering Context](json-ld/ikea-after-purchase-ordering-context.jsonld)

### Examples

9 per-operation example payloads in [`examples/`](examples/) (one default 2xx response per operation, Microcks-compatible).

### Capabilities

Six self-contained Naftiko capability files in [`capabilities/`](capabilities/) — one per OpenAPI tag across the four storefront APIs:

- [After Purchase Ordering — Parts](capabilities/after-purchase-ordering-parts.yaml)
- [Product Catalog — Categories](capabilities/product-catalog-categories.yaml)
- [Product Catalog — Products](capabilities/product-catalog-products.yaml)
- [Product Catalog — Stores](capabilities/product-catalog-stores.yaml)
- [Sales Item — Availability](capabilities/sales-item-availability.yaml)
- [Search — Products](capabilities/search-products.yaml)

### Spectral Rules

- [IKEA Community Spec Ruleset](rules/ikea-rules.yml) — opinionated Spectral rules derived from the patterns observed across the four community IKEA OpenAPI specs.

### Vocabulary

- [IKEA Vocabulary](vocabulary/ikea-vocabulary.yml) — operational and capability vocabulary mapping resources, actions, schemas, parameters, enums, workflows, personas and domains.

## Notes on Authenticity

IKEA does not publish an official public developer API or developer portal. Every API documented in this repo is:

1. **Unofficial** — reverse-engineered from observed network requests by community contributors, or
2. **Local-only** — the DIRIGERA hub API runs on the LAN with a bearer token paired via the hub's physical button.

Endpoints, schemas and behaviour may change at any time. The artifacts here track community efforts to keep up; treat them as best-effort approximations of IKEA's actual surfaces, not contracts.
