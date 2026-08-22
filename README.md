# Aladdin Studio (aladdin-studio)

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

Aladdin Studio is BlackRock's developer platform enabling institutional investors, asset managers, and wealth managers to build custom solutions on top of the Aladdin investment operating system. APIs provide access to portfolio data, risk analytics, trading, investment research, and the Aladdin Data Cloud, supporting approximately $25 trillion in assets managed on the platform.

**URL:** [https://www.blackrock.com/aladdin/products/apis](https://www.blackrock.com/aladdin/products/apis)

**Run:** [Capabilities Using Naftiko](https://github.com/naftiko/fleet?utm_source=api-evangelist&utm_medium=readme&utm_campaign=company-api-evangelist&utm_content=repo)

## Tags:

 - Financial, Investment Management, Portfolio Analytics, Risk Management, Asset Management, BlackRock, Data Cloud

## Timestamps

- **Created:** 2024-03-05
- **Modified:** 2026-04-19

## APIs

### Aladdin Graph API
The Aladdin Graph API provides RESTful access to portfolio data, securities, positions, risk analytics, and other Aladdin platform capabilities. Powers the AladdinSDK Python client with OAuth and Basic Auth authentication.

**Human URL:** [https://www.blackrock.com/aladdin/products/apis](https://www.blackrock.com/aladdin/products/apis)

#### Tags:

 - Portfolio Data, Investment Management, REST

#### Properties

- [Documentation](https://www.blackrock.com/aladdin/products/apis)
- [APIReference](https://www.blackrock.com/aladdin/products/apis)
- [OpenAPI](openapi/aladdin-studio-graph-openapi.yaml)
- [JSONSchema - Portfolio](json-schema/aladdin-studio-graph-portfolio-schema.json)
- [JSONSchema - Position](json-schema/aladdin-studio-graph-position-schema.json)
- [JSONSchema - Portfolio Risk](json-schema/aladdin-studio-graph-portfolio-risk-schema.json)
- [JSONSchema - Security](json-schema/aladdin-studio-graph-security-schema.json)

### Aladdin Data Cloud API
The Aladdin Data Cloud API provides access to Snowflake-based analytics data warehousing with OAuth and JWT authentication. Enables large-scale portfolio analytics and data science workflows using Snowflake connectors and Snowpark.

**Human URL:** [https://www.blackrock.com/aladdin/products/apis](https://www.blackrock.com/aladdin/products/apis)

#### Tags:

 - Data Cloud, Snowflake, Analytics

#### Properties

- [Documentation](https://www.blackrock.com/aladdin/products/apis)
- [OpenAPI](openapi/aladdin-studio-data-cloud-openapi.yaml)
- [JSONSchema - Connection](json-schema/aladdin-studio-data-cloud-connection-schema.json)
- [JSONSchema - Query Request](json-schema/aladdin-studio-data-cloud-query-request-schema.json)
- [JSONSchema - Query Result](json-schema/aladdin-studio-data-cloud-query-result-schema.json)
- [JSONSchema - Dataset](json-schema/aladdin-studio-data-cloud-dataset-schema.json)

### Aladdin Trading API
The Aladdin Trading API enables order management and trading workflow integration. Available as the asdk_plugin_trading Python package built on the AladdinSDK framework.

**Human URL:** [https://www.blackrock.com/aladdin/products/apis](https://www.blackrock.com/aladdin/products/apis)

#### Tags:

 - Trading, Order Management, Financial

#### Properties

- [Documentation](https://www.blackrock.com/aladdin/products/apis)
- [OpenAPI](openapi/aladdin-studio-trading-openapi.yaml)
- [SDK - Python Trading Plugin](https://pypi.org/project/asdk-plugin-trading/)
- [JSONSchema - Order](json-schema/aladdin-studio-trading-order-schema.json)

### Aladdin Investment Research API
The Aladdin Investment Research API provides access to research data, analyst insights, and quantitative analytics built on Aladdin's data infrastructure. Available as the asdk_plugin_investment_research Python package.

**Human URL:** [https://www.blackrock.com/aladdin/products/apis](https://www.blackrock.com/aladdin/products/apis)

#### Tags:

 - Investment Research, Analytics, Portfolio

#### Properties

- [Documentation](https://www.blackrock.com/aladdin/products/apis)
- [OpenAPI](openapi/aladdin-studio-investment-research-openapi.yaml)
- [SDK - Python Investment Research Plugin](https://pypi.org/project/asdk-plugin-investment-research/)
- [JSONSchema - Security Research](json-schema/aladdin-studio-investment-research-security-research-schema.json)
- [JSONSchema - Portfolio Analytics](json-schema/aladdin-studio-investment-research-portfolio-analytics-schema.json)

## Common Properties

- [Portal](https://www.blackrock.com/aladdin/products/apis)
- [Documentation](https://www.blackrock.com/aladdin/products/aladdin-studio)
- [GitHubOrganization](https://github.com/blackrock)
- [SDK - Python SDK (AladdinSDK)](https://github.com/blackrock/aladdinsdk)
- [SDK - Python SDK (PyPI)](https://pypi.org/project/aladdinsdk/)
- [SDK - Plugin Builder](https://github.com/blackrock/aladdinsdk-plugin-builder)

## Features

| Name | Description |
|------|-------------|
| Portfolio Data Access | Retrieve comprehensive portfolio data including positions, holdings, securities, and performance metrics across asset classes. |
| Risk Analytics | Access Aladdin's institutional-grade risk analytics including factor exposures, VaR, scenario analysis, and stress testing across public and private markets. |
| Aladdin Data Cloud | Snowflake-based data warehousing providing access to large-scale portfolio analytics with OAuth and JWT authentication supporting both Snowflake connectors and Snowpark. |
| Trading Integration | Order management and trading workflow APIs enabling integration with Aladdin's trading platform for order creation, tracking, and execution. |
| Investment Research Access | APIs for accessing investment research data, analyst insights, and quantitative analytics built on Aladdin's data infrastructure. |
| Long-Running Operations | Support for long-running operation (LRO) patterns with configurable polling, enabling asynchronous processing of computationally intensive analytics requests. |
| Batch Processing | Batch API support with sequential and parallel execution capabilities for processing large volumes of portfolio data operations efficiently. |
| Multi-Auth Support | Flexible authentication supporting Basic Auth with API tokens, OAuth client credentials flow, OAuth refresh token flow, and Snowflake JWT for Data Cloud access. |
| Plugin Architecture | Extensible SDK plugin architecture enabling domain-specific packages (trading, investment research) built on top of the core AladdinSDK. |
| Jupyter Notebook Integration | Downloadable Python Jupyter Notebooks and code samples in multiple languages for rapid solution development and prototyping. |

## Use Cases

| Name | Description |
|------|-------------|
| Custom Portfolio Analytics | Build bespoke portfolio analysis tools using Aladdin's risk and performance data to generate custom insights for investment teams. |
| Automated Risk Reporting | Automate generation of risk reports, factor exposure summaries, and stress test results using Aladdin's risk analytics APIs. |
| Trading Workflow Automation | Integrate Aladdin trading data into proprietary order management systems and automate trading workflow processes. |
| Investment Research Integration | Connect internal research platforms to Aladdin's investment research data for unified analyst workflow tooling. |
| Data Science and Quantitative Research | Access Aladdin Data Cloud from Snowflake-based data science environments for quantitative model development and backtesting. |
| Client Reporting Automation | Build automated client reporting solutions pulling portfolio performance, risk, and holdings data from Aladdin APIs. |
| Multi-Asset Class Analytics | Analyze portfolios across public equities, fixed income, alternatives, and private markets using Aladdin's unified data platform. |

## Integrations

| Name | Description |
|------|-------------|
| Snowflake | Native Aladdin Data Cloud integration with Snowflake for large-scale analytics, supporting both standard connectors and Snowpark for Python-based data science workflows. |
| Amazon Web Services | Aladdin available on AWS infrastructure (general availability expected second half of 2026) complementing existing Azure deployment. |
| Microsoft Azure | Primary cloud infrastructure for Aladdin platform, supporting enterprise deployments across institutional clients. |
| Preqin | Private markets data integrated into Aladdin ecosystem following BlackRock's acquisition for alternatives and private market analytics. |
| Python Ecosystem | First-class Python support via AladdinSDK on PyPI, with Jupyter Notebook examples and plugin architecture for domain extensions. |
| RepRisk | ESG risk data integrated into Aladdin portfolio management for reputational and environmental risk analysis. |

## Artifacts

Machine-readable API specifications organized by format.

### OpenAPI

- [Aladdin Graph API](openapi/aladdin-studio-graph-openapi.yaml)
- [Aladdin Data Cloud API](openapi/aladdin-studio-data-cloud-openapi.yaml)
- [Aladdin Trading API](openapi/aladdin-studio-trading-openapi.yaml)
- [Aladdin Investment Research API](openapi/aladdin-studio-investment-research-openapi.yaml)

### JSON Schema

- [aladdin-studio-graph-portfolio-schema.json](json-schema/aladdin-studio-graph-portfolio-schema.json)
- [aladdin-studio-graph-portfolio-list-schema.json](json-schema/aladdin-studio-graph-portfolio-list-schema.json)
- [aladdin-studio-graph-position-schema.json](json-schema/aladdin-studio-graph-position-schema.json)
- [aladdin-studio-graph-position-list-schema.json](json-schema/aladdin-studio-graph-position-list-schema.json)
- [aladdin-studio-graph-factor-exposure-schema.json](json-schema/aladdin-studio-graph-factor-exposure-schema.json)
- [aladdin-studio-graph-portfolio-risk-schema.json](json-schema/aladdin-studio-graph-portfolio-risk-schema.json)
- [aladdin-studio-graph-security-schema.json](json-schema/aladdin-studio-graph-security-schema.json)
- [aladdin-studio-data-cloud-connection-schema.json](json-schema/aladdin-studio-data-cloud-connection-schema.json)
- [aladdin-studio-data-cloud-connection-list-schema.json](json-schema/aladdin-studio-data-cloud-connection-list-schema.json)
- [aladdin-studio-data-cloud-query-request-schema.json](json-schema/aladdin-studio-data-cloud-query-request-schema.json)
- [aladdin-studio-data-cloud-query-result-schema.json](json-schema/aladdin-studio-data-cloud-query-result-schema.json)
- [aladdin-studio-data-cloud-dataset-schema.json](json-schema/aladdin-studio-data-cloud-dataset-schema.json)
- [aladdin-studio-data-cloud-dataset-list-schema.json](json-schema/aladdin-studio-data-cloud-dataset-list-schema.json)
- [aladdin-studio-trading-order-schema.json](json-schema/aladdin-studio-trading-order-schema.json)
- [aladdin-studio-trading-order-list-schema.json](json-schema/aladdin-studio-trading-order-list-schema.json)
- [aladdin-studio-trading-order-request-schema.json](json-schema/aladdin-studio-trading-order-request-schema.json)
- [aladdin-studio-investment-research-security-research-schema.json](json-schema/aladdin-studio-investment-research-security-research-schema.json)
- [aladdin-studio-investment-research-portfolio-analytics-schema.json](json-schema/aladdin-studio-investment-research-portfolio-analytics-schema.json)

### JSON Structure

- [aladdin-studio-graph-portfolio-structure.json](json-structure/aladdin-studio-graph-portfolio-structure.json)
- [aladdin-studio-graph-position-structure.json](json-structure/aladdin-studio-graph-position-structure.json)
- [aladdin-studio-graph-portfolio-risk-structure.json](json-structure/aladdin-studio-graph-portfolio-risk-structure.json)
- [aladdin-studio-graph-security-structure.json](json-structure/aladdin-studio-graph-security-structure.json)
- [aladdin-studio-data-cloud-connection-structure.json](json-structure/aladdin-studio-data-cloud-connection-structure.json)
- [aladdin-studio-data-cloud-query-result-structure.json](json-structure/aladdin-studio-data-cloud-query-result-structure.json)
- [aladdin-studio-trading-order-structure.json](json-structure/aladdin-studio-trading-order-structure.json)
- [aladdin-studio-investment-research-security-research-structure.json](json-structure/aladdin-studio-investment-research-security-research-structure.json)
- [aladdin-studio-investment-research-portfolio-analytics-structure.json](json-structure/aladdin-studio-investment-research-portfolio-analytics-structure.json)

### JSON-LD

- [aladdin-studio-context.jsonld](json-ld/aladdin-studio-context.jsonld)

### Examples

- [aladdin-studio-graph-portfolio-example.json](examples/aladdin-studio-graph-portfolio-example.json)
- [aladdin-studio-graph-position-example.json](examples/aladdin-studio-graph-position-example.json)
- [aladdin-studio-graph-portfolio-risk-example.json](examples/aladdin-studio-graph-portfolio-risk-example.json)
- [aladdin-studio-graph-security-example.json](examples/aladdin-studio-graph-security-example.json)
- [aladdin-studio-data-cloud-connection-example.json](examples/aladdin-studio-data-cloud-connection-example.json)
- [aladdin-studio-data-cloud-query-result-example.json](examples/aladdin-studio-data-cloud-query-result-example.json)
- [aladdin-studio-trading-order-example.json](examples/aladdin-studio-trading-order-example.json)
- [aladdin-studio-investment-research-security-research-example.json](examples/aladdin-studio-investment-research-security-research-example.json)
- [aladdin-studio-investment-research-portfolio-analytics-example.json](examples/aladdin-studio-investment-research-portfolio-analytics-example.json)

## Capabilities

Naftiko capabilities organized as shared per-API definitions composed into customer-facing workflows.

### Shared Per-API Definitions

- [Aladdin Graph API](capabilities/shared/graph-api.yaml) — 5 operations for portfolio, position, risk, and security data
- [Aladdin Data Cloud API](capabilities/shared/data-cloud-api.yaml) — 3 operations for Snowflake analytics

### Workflow Capabilities

| Workflow | APIs Combined | Tools | Persona |
|----------|--------------|-------|---------|
| [Portfolio Analytics](capabilities/portfolio-analytics.yaml) | aladdin-graph, aladdin-data-cloud | 7 | Portfolio Manager, Risk Analyst, Quantitative Researcher |

## Vocabulary

- [Aladdin Studio Vocabulary](vocabulary/aladdin-studio-vocabulary.yaml) — Unified taxonomy mapping 10 resources, 4 actions, 1 workflow, and 3 personas across operational (OpenAPI) and capability (Naftiko) dimensions

## Rules

- [Aladdin Studio Spectral Rules](rules/aladdin-studio-spectral-rules.yml) — 33 rules across 11 categories enforcing Aladdin Studio API conventions

## Maintainers

**FN:** Kin Lane

**Email:** kin@apievangelist.com
