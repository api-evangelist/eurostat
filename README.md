# Eurostat (eurostat)

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
> **On a security or compliance team?** Email
> [info@apievangelist.com](mailto:info@apievangelist.com) with *security* in the subject line and
> you will get a person, not a form. We will tell you exactly which public URLs this profile was
> built from so your team can see the same surface we did, and we will take the listing down on
> request while you work through it.
>
> Full detail: **[Where this data comes from](https://apievangelist.com/about/where-our-data-comes-from)**
<!-- API-EVANGELIST-PROVENANCE:END -->

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
