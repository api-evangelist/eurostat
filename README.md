# Eurostat (eurostat)

Eurostat is the statistical office of the European Union, providing free and open REST APIs for programmatic access to European statistical data covering demographics, economy, trade, agriculture, transport, environment, and dozens of other indicators across EU member states and regions.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/eurostat/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/eurostat/refs/heads/main/apis.yml)

## Tags

- Statistics
- European Union
- Open Data
- Demographics
- Economy
- Trade
- Agriculture
- Transport
- Environment
- SDMX

## Timestamps

- **Created:** 2026-06-13
- **Modified:** 2026-06-13

## APIs

### Eurostat Statistics API

The primary REST API for accessing Eurostat datasets in JSON-stat 2.0 format. Supports filtering by geography, time period, and any dataset dimension. Returns synchronous or asynchronous responses depending on query size.

- **Human URL:** [https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- **Base URL:** `https://ec.europa.eu/eurostat/api/dissemination/statistics/1.0/`

#### Tags

- Statistics
- JSON-stat
- European Union

#### Properties

- [Documentation](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- [Getting Started](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-getting-started/api)
- [Detailed Guidelines](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/api-statistics)

### Eurostat SDMX 2.1 API

SDMX 2.1-compliant web service providing access to Eurostat datasets and structural metadata in SDMX-ML (XML), SDMX-CSV, and TSV formats.

- **Human URL:** [https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- **Base URL:** `https://ec.europa.eu/eurostat/api/dissemination/sdmx/2.1/`

#### Tags

- SDMX
- XML
- Statistics
- European Union

#### Properties

- [Documentation](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- [OpenAPI](openapi/eurostat-sdmx-rest-openapi.yaml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)

### Eurostat SDMX 3.0 API

SDMX 3.0-compliant web service providing access to Eurostat datasets, dataflows, data structure definitions, and codelists. Supports SDMX-ML 3.0 and 2.1, SDMX-CSV 2.0 and 1.0, TSV, and JSON-stat formats.

- **Human URL:** [https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-getting-started/sdmx3.0](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-getting-started/sdmx3.0)
- **Base URL:** `https://ec.europa.eu/eurostat/api/dissemination/sdmx/3.0/`

#### Tags

- SDMX
- XML
- CSV
- Statistics
- European Union

#### Properties

- [Documentation](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-getting-started/sdmx3.0)
- [Detailed Guidelines](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/sdmx3-0/data-query)

### Eurostat Asynchronous API

Asynchronous dissemination API for large dataset extractions between 500,000 and 5,000,000 cells. Clients submit a request, receive a unique key, poll for status, and download results when available.

- **Human URL:** [https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/asynchronous-api](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/asynchronous-api)
- **Base URL:** `https://ec.europa.eu/eurostat/api/dissemination/1.0/async/`

#### Tags

- Asynchronous
- Large Datasets
- Statistics
- European Union

#### Properties

- [Documentation](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-detailed-guidelines/asynchronous-api)

### Eurostat Catalogue API

API for discovering all publicly available Eurostat datasets, browsing the navigation tree, and retrieving dataset metadata before querying.

- **Human URL:** [https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- **Base URL:** `https://ec.europa.eu/eurostat/api/dissemination/catalogue/`

#### Tags

- Catalogue
- Metadata
- Discovery
- European Union

#### Properties

- [Documentation](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)

## Common Properties

- [Website](https://ec.europa.eu/eurostat)
- [Documentation](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- [Git Hub Org](https://github.com/eurostat)
- [LinkedIn](https://www.linkedin.com/company/eurostat/)
- [Blog](https://ec.europa.eu/eurostat/news/news-articles)
- [Pricing](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-introduction)
- [Status Page](https://ec.europa.eu/eurostat/help/maintenance-information)
- [X (Twitter)](https://x.com/EU_Eurostat)
- [Plans](plans/eurostat-plans-pricing.yml)
- [Rate Limits](rate-limits/eurostat-rate-limits.yml)
- [Fin Ops](finops/eurostat-finops.yml)
- [F A Q](https://ec.europa.eu/eurostat/web/user-guides/data-browser/api-data-access/api-faq)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
