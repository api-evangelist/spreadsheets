# Spreadsheets

Spreadsheets covers the APIs, tools, and services for programmatic access to spreadsheet data across major platforms. The Google Sheets API v4 provides RESTful access to read, write, format, and manage Google Spreadsheets. The Microsoft Graph Excel API enables reading and writing Excel workbooks stored in OneDrive for Business and SharePoint. Third-party services like SheetDB, Sheety, and Sheet Best convert spreadsheets into REST APIs for use as lightweight backends.

## APIs

### Google Sheets API

The Google Sheets API v4 is a RESTful interface for reading and modifying Google Spreadsheet data programmatically.

- **Base URL:** https://sheets.googleapis.com/v4
- **Authentication:** Google OAuth 2.0 (Authorization Code flow)
- **Documentation:** https://developers.google.com/workspace/sheets/api
- **Scopes:** spreadsheets, spreadsheets.readonly

**Key Capabilities:**
- Create and retrieve spreadsheets
- Read/write cell values by range using A1 notation
- Batch get/update multiple ranges in a single call
- Append rows to existing tables
- Manage sheet structure, formatting, and charts
- Developer metadata for app-level storage

### Microsoft Graph Excel API

The Microsoft Graph Excel API enables reading and writing .xlsx workbooks stored in OneDrive for Business and SharePoint via Microsoft Graph.

- **Base URL:** https://graph.microsoft.com/v1.0
- **Authentication:** Microsoft identity platform (OAuth 2.0)
- **Documentation:** https://learn.microsoft.com/en-us/graph/api/resources/excel
- **Scopes:** Files.Read, Files.ReadWrite

**Key Capabilities:**
- Persistent and non-persistent session management
- Worksheet management (create, rename, delete)
- Range read/write and cell formatting
- Table management (create, rows, columns, sort, filter)
- Chart creation and image export
- 300+ Excel worksheet functions via API

### Third-Party Spreadsheet APIs

| Service | Description |
|---|---|
| [SheetDB](https://sheetdb.io/) | Google Sheets to REST API, full CRUD |
| [Sheety](https://sheety.co/) | Google Sheets to RESTful JSON API |
| [Sheet Best](https://sheetbest.com/) | Secure REST endpoints for Sheets data |
| [Sheet2API](https://sheet2api.com/) | Hosted REST endpoints with caching |
| [Sheetlabs](https://sheetlabs.com/) | Scalable APIs from spreadsheets |
| [API Spreadsheets](https://apispreadsheets.com/) | AI workflow integration |

## Artifacts

### OpenAPI Specifications

| Spec | Description |
|---|---|
| [google-sheets-openapi.yml](openapi/google-sheets-openapi.yml) | Google Sheets API v4 — spreadsheets, values, sheets, and metadata operations |

### JSON Schema

| Schema | Description |
|---|---|
| [spreadsheet-range-schema.json](json-schema/spreadsheet-range-schema.json) | ValueRange object schema for reading and writing cell data |
| [spreadsheet-value-schema.json](json-schema/spreadsheet-value-schema.json) | Spreadsheet object schema with sheets and properties |

### JSON Structure

| Structure | Description |
|---|---|
| [spreadsheet-range-structure.json](json-structure/spreadsheet-range-structure.json) | Hierarchical field map for the ValueRange object with usage notes |

### JSON-LD Context

| Context | Description |
|---|---|
| [spreadsheets-context.jsonld](json-ld/spreadsheets-context.jsonld) | Linked data context for Google Sheets and Excel API vocabulary |

### Examples

| Example | Description |
|---|---|
| [google-sheets-read-values-example.json](examples/google-sheets-read-values-example.json) | Read a table of employee data from a Google Sheet |
| [google-sheets-append-values-example.json](examples/google-sheets-append-values-example.json) | Append new rows to an existing table |

### Spectral Rules

| Ruleset | Description |
|---|---|
| [spreadsheets-rules.yml](rules/spreadsheets-rules.yml) | Spectral ruleset for spreadsheet API conventions |

### Capabilities

| Capability | Description |
|---|---|
| [spreadsheet-automation.yaml](capabilities/spreadsheet-automation.yaml) | Spreadsheet automation: read, write, append, batch operations (6 MCP tools) |
| [shared/google-sheets.yaml](capabilities/shared/google-sheets.yaml) | Shared Google Sheets API definition |

### Vocabulary

| Vocabulary | Description |
|---|---|
| [spreadsheets-vocabulary.yml](vocabulary/spreadsheets-vocabulary.yml) | Domain vocabulary for spreadsheet APIs: ranges, operations, formatting, providers |

## Common Use Cases

- **Data Pipeline:** Import/export between databases and spreadsheets
- **Automated Reporting:** Generate reports directly in Google Sheets or Excel
- **Form Collection:** Write form submissions as spreadsheet rows (lightweight backend)
- **Financial Modeling:** Update financial models with live data
- **Content Management:** Use sheets as a CMS for websites and apps
- **AI Workflows:** Enable LLMs to read and update spreadsheet data via MCP

## Maintainers

**FN:** Kin Lane
**Email:** kin@apievangelist.com
