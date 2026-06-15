# Spreadsheets (spreadsheets)

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
