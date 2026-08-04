# Spreadsheets (spreadsheets)

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

Spreadsheets covers the APIs, tools, and services for programmatic access to spreadsheet data across major platforms including Google Sheets and Microsoft Excel. The Google Sheets API v4 provides RESTful access to read, write, format, and manage Google Spreadsheets. The Microsoft Graph Excel API enables reading and writing Excel workbooks stored in OneDrive for Business and SharePoint. Third-party services like SheetDB, Sheety, Sheet Best, and Sheet2API convert spreadsheets into REST APIs for use as lightweight backends. Spreadsheet APIs are widely used for data import/export, automated reporting, form submissions, lightweight CMS, and business process automation.

**APIs.json:** [https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/apis.yml](https://raw.githubusercontent.com/api-evangelist/spreadsheets/refs/heads/main/apis.yml)

## Scope

- **Type:** Index
- **Position:** Consumer
- **Access:** 3rd-Party

## Tags

- Spreadsheets
- Data
- Google Sheets
- Excel
- Productivity
- Automation

## Timestamps

- **Created:** 2026-03-16
- **Modified:** 2026-05-19

## APIs

### Google Sheets API

The Google Sheets API v4 is a RESTful interface that lets developers read and modify Google Spreadsheet data programmatically. The API supports creating spreadsheets, reading and writing cell values by range (A1 notation), batch operations for efficiency, managing sheet structure and formatting, and accessing developer metadata. Authentication uses Google OAuth 2.0. The API is widely used for data pipelines, automated reporting, form data collection, and spreadsheet-powered applications.

- **Human URL:** [https://developers.google.com/workspace/sheets/api](https://developers.google.com/workspace/sheets/api)
- **Base URL:** `https://sheets.googleapis.com/v4`

#### Tags

- Google Sheets
- Spreadsheets
- Data
- Productivity
- Google Workspace

#### Properties

- [Documentation](https://developers.google.com/workspace/sheets/api/guides/concepts)
- [Reference](https://developers.google.com/workspace/sheets/api/reference/rest)
- [OpenAPI](openapi/google-sheets-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [Postman Collection](collections/google-sheets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-sheets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)
- [Getting Started](https://developers.google.com/workspace/sheets/api/quickstart/python)
- [Discovery](https://sheets.googleapis.com/$discovery/rest?version=v4)

### Microsoft Graph Excel API

The Microsoft Graph Excel API enables reading and writing Excel workbooks (.xlsx format) stored in OneDrive for Business, SharePoint, or Group drives via the Microsoft Graph REST API. Supports worksheets, ranges, tables, charts, named items, and Excel worksheet functions. Uses session-based access for efficient multi-step operations. Authentication requires Microsoft identity platform (OAuth 2.0) with Files.Read or Files.ReadWrite scopes.

- **Human URL:** [https://learn.microsoft.com/en-us/graph/api/resources/excel](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- **Base URL:** `https://graph.microsoft.com/v1.0`

#### Tags

- Excel
- Microsoft Graph
- Microsoft 365
- Spreadsheets
- OneDrive

#### Properties

- [Documentation](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- [Reference](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- [Getting Started](https://learn.microsoft.com/en-us/graph/excel-use-functions)
- [Postman Collection](collections/google-sheets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-sheets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### SheetDB

SheetDB is a service that turns any Google Sheet into a JSON REST API. Provides GET, POST, PUT, PATCH, and DELETE endpoints against spreadsheet data, supporting full CRUD operations without code. Used for prototyping, simple backends, and content management.

- **Human URL:** [https://sheetdb.io/](https://sheetdb.io/)
- **Base URL:** `https://sheetdb.io/api/v1`

#### Tags

- Spreadsheets
- No Code
- REST API
- Google Sheets

#### Properties

- [Documentation](https://docs.sheetdb.io/)
- [Website](https://sheetdb.io/)
- [Postman Collection](collections/google-sheets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-sheets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

### Sheety

Sheety converts Google Spreadsheets into RESTful JSON APIs, providing simple HTTP endpoints for reading and writing spreadsheet data. Supports GET, POST, PUT, PATCH, and DELETE operations with optional API key authentication.

- **Human URL:** [https://sheety.co/](https://sheety.co/)
- **Base URL:** `https://api.sheety.co`

#### Tags

- Spreadsheets
- No Code
- REST API
- Google Sheets

#### Properties

- [Documentation](https://sheety.co/docs)
- [Website](https://sheety.co/)
- [Postman Collection](collections/google-sheets.postman_collection.json) — [Postman Collection 2.1](https://schema.getpostman.com/json/collection/v2.1.0/collection.json)
- [Open Collection](collections/google-sheets.opencollection.json) — [Open Collection 1.0](https://schema.opencollection.com/opencollection/v1.0.0.json)

## Common Properties

- [Website](https://developers.google.com/workspace/sheets/api)
- [Reference](https://learn.microsoft.com/en-us/graph/api/resources/excel)
- [OpenAPI](openapi/google-sheets-openapi.yml) — [OpenAPI Specification](https://spec.openapis.org/oas/latest.html)
- [JSON Schema](json-schema/spreadsheet-range-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Schema](json-schema/spreadsheet-value-schema.json) — [JSON Schema](https://json-schema.org/specification)
- [JSON Structure](json-structure/spreadsheet-range-structure.json)
- [JSON-LD](json-ld/spreadsheets-context.jsonld) — [JSON-LD](https://www.w3.org/TR/json-ld11/)
- [Spectral Rules](rules/spreadsheets-rules.yml)
- [Capabilities](capabilities/spreadsheet-automation.yaml)
- [Vocabulary](vocabulary/spreadsheets-vocabulary.yml)

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
