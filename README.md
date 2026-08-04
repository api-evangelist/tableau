# Tableau (tableau)

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

Tableau is a visual analytics platform transforming the way we use data to solve problems—empowering people and organizations to make the most of their data.

**APIs.json:** [https://www.tableau.com](https://www.tableau.com)

## Tags

- Analytics
- Business Intelligence
- Dashboards
- Data Visualization

## Timestamps

- **Created:** 2024
- **Modified:** 2026-05-19

## APIs

### Tableau REST API

The Tableau REST API allows you to manage and change Tableau Server, Tableau Cloud site, and Tableau Prep Conductor resources programmatically, using HTTP.

- **Human URL:** [https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- **Base URL:** `https://[server]/api/[api-version]`

#### Tags

- Data Sources
- REST
- Server Management
- Sites
- Workbooks

#### Properties

- [Documentation](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api.htm)
- [OpenAPI](openapi/tableau-rest-api-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [JSON Schema](json-schema/tableau-workbook-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON-LD](json-ld/tableau-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Authentication](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_auth.htm)
- [Versioning](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_concepts_versions.htm)
- [Changelog](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_whats_new.htm)
- [Getting Started](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_get_started_tutorial_part_1.htm)
- [API Reference](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref.htm)
- [Code Examples](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_samples.htm)
- [SDK](https://tableau.github.io/server-client-python/)
- [GitHub Repository](https://github.com/tableau/rest-api-samples)

### Tableau Metadata API

GraphQL-based API for querying metadata about Tableau content, data sources, and lineage information.

- **Human URL:** [https://help.tableau.com/current/api/metadata_api/en-us/index.html](https://help.tableau.com/current/api/metadata_api/en-us/index.html)
- **Base URL:** `https://[server]/api/metadata/graphql`

#### Tags

- Data Catalog
- GraphQL
- Lineage
- Metadata

#### Properties

- [Documentation](https://help.tableau.com/current/api/metadata_api/en-us/index.html)
- [API Reference](https://help.tableau.com/current/api/metadata_api/en-us/reference/index.html)
- [Code Examples](https://help.tableau.com/current/api/metadata_api/en-us/docs/use-cases.html)
- [Getting Started](https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_start.html)
- [Authentication](https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_auth.html)
- [Changelog](https://help.tableau.com/current/api/metadata_api/en-us/docs/meta_api_release_notes.html)
- [GitHub Repository](https://github.com/tableau/metadata-api-samples)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Hyper API

API for creating, reading, and updating Hyper files, which are the data files that power Tableau extracts.

- **Human URL:** [https://help.tableau.com/current/api/hyper_api/en-us/index.html](https://help.tableau.com/current/api/hyper_api/en-us/index.html)
- **Base URL:** `https://github.com/tableau/hyper-api-samples`

#### Tags

- Data Files
- ETL
- Extracts
- Hyper

#### Properties

- [Documentation](https://help.tableau.com/current/api/hyper_api/en-us/index.html)
- [GitHub Repository](https://github.com/tableau/hyper-api-samples)
- [Getting Started](https://www.tableau.com/developer/learning/tableau-hyper-api)
- [Changelog](https://tableau.github.io/hyper-db/docs/releases/)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Embedding API

JavaScript API for embedding Tableau visualizations in web applications with advanced interaction capabilities.

- **Human URL:** [https://help.tableau.com/current/api/embedding_api/en-us/index.html](https://help.tableau.com/current/api/embedding_api/en-us/index.html)
- **Base URL:** `https://[server]`

#### Tags

- Embedding
- JavaScript
- Visualization
- Web Components

#### Properties

- [Documentation](https://help.tableau.com/current/api/embedding_api/en-us/index.html)
- [Tutorials](https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_get_started.html)
- [API Reference](https://help.tableau.com/current/api/embedding_api/en-us/reference/index.html)
- [Authentication](https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_auth.html)
- [Changelog](https://help.tableau.com/current/api/embedding_api/en-us/docs/embedding_api_release_notes.html)
- [GitHub Repository](https://github.com/tableau/embedding-api-v3-samples)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Document API

Python library for programmatically updating Tableau workbook and data source files.

- **Human URL:** [https://tableau.github.io/document-api-python/](https://tableau.github.io/document-api-python/)
- **Base URL:** `https://github.com/tableau/document-api-python`

#### Tags

- Automation
- Data Sources
- Python
- Workbooks

#### Properties

- [Documentation](https://tableau.github.io/document-api-python/)
- [GitHub Repository](https://github.com/tableau/document-api-python)
- [Getting Started](https://tableau.github.io/document-api-python/docs/)
- [API Reference](https://tableau.github.io/document-api-python/docs/api-ref)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Server Client (Python)

Python library that wraps the Tableau REST API for easier programmatic access.

- **Human URL:** [https://tableau.github.io/server-client-python/](https://tableau.github.io/server-client-python/)
- **Base URL:** `https://github.com/tableau/server-client-python`

#### Tags

- Python
- REST
- SDK
- Wrapper

#### Properties

- [Documentation](https://tableau.github.io/server-client-python/)
- [GitHub Repository](https://github.com/tableau/server-client-python)
- [Code Examples](https://tableau.github.io/server-client-python/docs/samples)
- [API Reference](https://tableau.github.io/server-client-python/docs/api-ref)
- [Getting Started](https://tableau.github.io/server-client-python/docs/)
- [Changelog](https://github.com/tableau/server-client-python/blob/master/CHANGELOG.md)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Extensions API

The Tableau Extensions API allows developers to create dashboard extensions and viz extensions that users can interact with directly in Tableau, enabling integration with other applications and custom visualization types.

- **Human URL:** [https://tableau.github.io/extensions-api/docs/](https://tableau.github.io/extensions-api/docs/)
- **Base URL:** `https://[server]`

#### Tags

- Dashboard Extensions
- Extensibility
- JavaScript
- Viz Extensions
- Web Components

#### Properties

- [Documentation](https://tableau.github.io/extensions-api/docs/)
- [GitHub Repository](https://github.com/tableau/extensions-api)
- [Getting Started](https://tableau.github.io/extensions-api/docs/dashext/trex_getstarted/)
- [API Reference](https://tableau.github.io/extensions-api/docs/trex_tableau_viz_ref/)
- [Changelog](https://tableau.github.io/extensions-api/docs/trex_release-notes/)
- [Code Examples](https://tableau.github.io/extensions-api/docs/dashext/trex_examples/)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Web Data Connector

The Tableau Web Data Connector (WDC) provides an SDK for building connectors to any data accessible over HTTP, allowing users to bring external data into Tableau for analysis and visualization.

- **Human URL:** [https://help.tableau.com/current/api/webdataconnector/en-us/index.html](https://help.tableau.com/current/api/webdataconnector/en-us/index.html)
- **Base URL:** `https://[server]`

#### Tags

- Connectors
- Data Integration
- HTTP
- JavaScript

#### Properties

- [Documentation](https://help.tableau.com/current/api/webdataconnector/en-us/index.html)
- [API Reference](https://tableau.github.io/webdataconnector/docs/api_ref.html)
- [GitHub Repository](https://github.com/tableau/webdataconnector)
- [Changelog](https://help.tableau.com/current/api/webdataconnector/en-us/docs/wdc_whats_new.html)
- [Tutorials](https://tableau.github.io/webdataconnector/docs/wdc_tutorial.html)
- [Code Examples](https://tableau.github.io/webdataconnector/docs/wdc_samples.html)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Connector SDK

SDK for developing custom Tableau connectors using ODBC or JDBC drivers, including documentation, example files, a test harness, and a packaging tool for distribution.

- **Human URL:** [https://tableau.github.io/connector-plugin-sdk/](https://tableau.github.io/connector-plugin-sdk/)
- **Base URL:** `https://github.com/tableau/connector-plugin-sdk`

#### Tags

- Connectors
- Custom Connectors
- JDBC
- ODBC
- SDK

#### Properties

- [Documentation](https://tableau.github.io/connector-plugin-sdk/docs/)
- [GitHub Repository](https://github.com/tableau/connector-plugin-sdk)
- [API Reference](https://tableau.github.io/connector-plugin-sdk/docs/api-reference)
- [Code Examples](https://tableau.github.io/connector-plugin-sdk/docs/example)
- [Getting Started](https://tableau.github.io/connector-plugin-sdk/docs/)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Analytics Extensions API

The Analytics Extensions API allows integration of external analytics engines such as Python, R, MATLAB, and data science platforms with Tableau calculations for advanced analytics.

- **Human URL:** [https://tableau.github.io/analytics-extensions-api/docs/ae_intro.html](https://tableau.github.io/analytics-extensions-api/docs/ae_intro.html)
- **Base URL:** `https://[server]`

#### Tags

- Analytics
- Data Science
- Machine Learning
- Python
- R

#### Properties

- [Documentation](https://tableau.github.io/analytics-extensions-api/docs/ae_intro.html)
- [Code Examples](https://tableau.github.io/analytics-extensions-api/docs/ae_example_tabpy.html)
- [Getting Started](https://tableau.github.io/analytics-extensions-api/docs/ae_connect_desktop.html)
- [API Reference](https://tableau.github.io/analytics-extensions-api/docs/ae_summary.html)
- [GitHub Repository](https://github.com/tableau/TabPy)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Webhooks

Tableau Webhooks enable event-driven automation by sending HTTP POST notifications to specified URLs when events occur on Tableau Server or Tableau Cloud.

- **Human URL:** [https://help.tableau.com/current/developer/webhooks/en-us/](https://help.tableau.com/current/developer/webhooks/en-us/)
- **Base URL:** `https://[server]/api/[api-version]`

#### Tags

- Automation
- Events
- Notifications
- Webhooks

#### Properties

- [Documentation](https://help.tableau.com/current/developer/webhooks/en-us/)
- [GitHub Repository](https://github.com/tableau/webhooks-docs)
- [Getting Started](https://help.tableau.com/current/developer/webhooks/en-us/docs/webhooks-get-started.html)
- [API Reference](https://help.tableau.com/current/developer/webhooks/en-us/docs/webhooks-events-payload.html)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau VizQL Data Service

The VizQL Data Service provides a programmatic HTTP interface to query published data sources outside of Tableau visualizations, enabling headless data access from any application.

- **Human URL:** [https://help.tableau.com/current/api/vizql-data-service/en-us/index.html](https://help.tableau.com/current/api/vizql-data-service/en-us/index.html)
- **Base URL:** `https://[server]/api/v1`

#### Tags

- Data Access
- Headless
- Query
- REST

#### Properties

- [Documentation](https://help.tableau.com/current/api/vizql-data-service/en-us/index.html)
- [API Reference](https://help.tableau.com/current/api/vizql-data-service/en-us/reference/index.html)
- [Changelog](https://help.tableau.com/current/api/vizql-data-service/en-us/docs/vds_whats_new.html)
- [GitHub Repository](https://github.com/tableau/VizQL-Data-Service)
- [Getting Started](https://help.tableau.com/current/api/vizql-data-service/en-us/docs/vds_create_queries.html)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Tableau Pulse API

The Tableau Pulse API enables programmatic creation, management, and querying of Tableau Pulse metrics and subscriptions, as well as embedding Pulse insights into web applications.

- **Human URL:** [https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref_pulse.htm](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref_pulse.htm)
- **Base URL:** `https://[server]/api/[api-version]`

#### Tags

- Analytics
- Insights
- Metrics
- Pulse

#### Properties

- [Documentation](https://help.tableau.com/current/api/rest_api/en-us/REST/rest_api_ref_pulse.htm)
- [API Reference](https://help.tableau.com/current/api/embedding_api/en-us/reference/interfaces/pulse.html)
- [GitHub Repository](https://github.com/tableau/pulse-api-utilities)
- [Postman Collection](collections/tableau-rest-api.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/tableau-rest-api.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [LinkedIn](https://www.linkedin.com/company/tableau-software)
- [Developer Portal](https://www.tableau.com/developer)
- [Blog](https://www.tableau.com/blog/developers)
- [Support](https://www.tableau.com/support)
- [GitHub Organization](https://github.com/tableau)
- [Status Page](https://trust.tableau.com/)
- [Release Notes](https://help.tableau.com/current/tableau/en-us/whatsnew_all.htm)
- [Terms of Service](https://www.tableau.com/legal)
- [Privacy Policy](https://www.tableau.com/privacy)
- [Sign Up](https://www.tableau.com/products/trial)
- [Login](https://www.tableau.com/tableau-login-hub)
- [Documentation](https://help.tableau.com/)
- [Stack Overflow](https://stackoverflow.com/questions/tagged/tableau)
- [YouTube](https://www.youtube.com/@Tableau)
- [Training](https://www.tableau.com/developer/learning)
- [Spectral Rules](rules/tableau-spectral-rules.yml)
- [Features](undefined)
- [Use Cases](undefined)
- [Integrations](undefined)
- [M C P Server](https://github.com/tableau/tableau-mcp)

## Maintainers

**Email:** developers@tableau.com
**URL:** https://www.tableau.com
**Email:** kin@apievangelist.com
**URL:** https://apievangelist.com
