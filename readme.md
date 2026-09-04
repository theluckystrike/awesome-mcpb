# Awesome MCPB [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> Self-contained MCP server packages that run with a single command.

[MCPB](https://github.com/modelcontextprotocol/mcpb) (MCP Bundle), also known as Claude Desktop Extensions (DXT), is the packaging format for distributing [Model Context Protocol](https://modelcontextprotocol.io) servers as ready-to-run bundles. No cloning repos, no installing runtimes, no debugging dependencies.

Bundles are distributed as `.mcpb` files. Install from a registry or download from GitHub Releases:

```bash
# From mpak registry
mpak run @scope/name

# From a local .mcpb file
mpak run ./server.mcpb
```

## Contents

- [Developer Tools](#developer-tools)
- [Databases](#databases)
- [Search and Documentation](#search-and-documentation)
- [Productivity](#productivity)
- [Communication and Media](#communication-and-media)
- [Science](#science)
- [Infrastructure and Observability](#infrastructure-and-observability)
- [Utilities](#utilities)
- [Build Tools](#build-tools)

## Developer Tools

- [Desktop Commander](https://github.com/wonderwhy-er/DesktopCommanderMCP) - Terminal control, file operations, and diff-based code editing.
- [dbt](https://github.com/dbt-labs/dbt-mcp) - Data build tool for analytics engineering workflows.
- [GitHub](https://github.com/modelcontextprotocol/servers/tree/main/src/github) - Repository management, pull requests, issues, and code search.
- [liblab](https://github.com/liblaber/mcp-server-liblab) - SDK generation and API documentation from specs.
- [Postman](https://github.com/postmanlabs/postman-mcp-server) - API testing, collection management, and development workflows.

## Databases

- [ClickHouse](https://github.com/ClickHouse/mcp-clickhouse) - Analytics database queries and schema exploration.
- [Neo4j](https://github.com/neo4j/mcp) - Graph database queries and knowledge graph operations.
- [PostgreSQL](https://github.com/modelcontextprotocol/servers/tree/main/src/postgres) - SQL queries with configurable read/write permissions.

## Search and Documentation

- [Context7](https://github.com/upstash/context7) - Up-to-date library documentation and code examples.
- [Docling](https://github.com/docling-project/docling-mcp) - Document AI processing and format conversion.
- [Exa](https://github.com/exa-labs/exa-mcp-server) - AI-native semantic web search.
- [Ref Tools](https://github.com/nicobailon/ref-tools-mcp) - Token-efficient documentation search and retrieval.
- [Tavily](https://github.com/tavily-ai/tavily-mcp) - Real-time web search, extraction, and crawling.

## Productivity

- [Anki](https://github.com/tbroadley/ankiconnect-mcpb) - Flashcard operations via AnkiConnect.
- [Bank Statement](https://github.com/theluckystrike/mcp-servers/tree/main/servers/bank-statement) - Import a bank CSV export, categorize it, summarize it per currency, and reconcile it against an expense ledger. (mcp.zovo.one)
- [Bear](https://github.com/jkawamoto/mcp-bear) - Notes app integration for macOS.
- [Calendar](https://github.com/theluckystrike/mcp-servers/tree/main/servers/calendar) - Read .ics calendar exports: availability, double-booking checks, and turning meetings into billable time. (mcp.zovo.one)
- [Clauses](https://github.com/theluckystrike/mcp-servers/tree/main/servers/clauses) - Reusable contract and proposal clause library with variables, search, and assembly into a Word document. (mcp.zovo.one)
- [Docx](https://github.com/theluckystrike/mcp-servers/tree/main/servers/docx) - Generate and fill Word documents (proposals, quotes, contracts, statements of work) from a chat. (mcp.zovo.one)
- [Expense Tracker](https://github.com/theluckystrike/mcp-servers/tree/main/servers/expense-tracker) - Local expense, receipt, and mileage ledger with VAT splitting and CSV/xlsx export. (mcp.zovo.one)
- [Invoice](https://github.com/theluckystrike/mcp-servers/tree/main/servers/invoice) - Create sendable PDF invoices with numbering, VAT lines, discounts, and overdue reports. (mcp.zovo.one)
- [Kanban](https://github.com/theluckystrike/mcp-servers/tree/main/servers/kanban) - Local task board per project: columns, due dates, estimates, priorities. (mcp.zovo.one)
- [Office Suite](https://github.com/theluckystrike/mcp-servers/tree/main/servers/office-suite) - Bundle proxying time tracking, price watching, spreadsheets, and PDF invoicing behind one MCP server. (mcp.zovo.one)
- [Productboard](https://github.com/benmillerat/productboard-mcpb) - Product management and roadmap workflows.
- [Quotes](https://github.com/theluckystrike/mcp-servers/tree/main/servers/quotes) - Send client quotes with line items and VAT as PDF; accepted quotes convert to invoices. (mcp.zovo.one)
- [Recurring](https://github.com/theluckystrike/mcp-servers/tree/main/servers/recurring) - Generate recurring invoices on a schedule with an audit log and revenue forecast. (mcp.zovo.one)
- [Resume](https://github.com/theluckystrike/mcp-servers/tree/main/servers/resume) - Turn CV facts into a tailored Word resume and cover letter with keyword matching. (mcp.zovo.one)
- [Spreadsheet](https://github.com/theluckystrike/mcp-servers/tree/main/servers/spreadsheet) - Open, inspect, query, edit, and convert xlsx and csv files locally. (mcp.zovo.one)
- [Things](https://github.com/mbmccormick/things-mcpb) - Task management via Things app for macOS.
- [Time Tracker](https://github.com/theluckystrike/mcp-servers/tree/main/servers/time-tracker) - Track billable time with timers, entries, reports, and CSV export. (mcp.zovo.one)
- [Timezone](https://github.com/theluckystrike/mcp-servers/tree/main/servers/timezone) - Time zone conversion, meeting-slot finding, DST checks, and .ics generation. (mcp.zovo.one)
- [YNAB](https://github.com/dizzlkheinz/ynab-mcpb) - Budget management with You Need A Budget.

## Communication and Media

- [Mailtrap](https://github.com/mailtrap/mailtrap-mcp) - Email testing, delivery, and inbox management.
- [Spotify](https://github.com/fabioc-aloha/spotify-mcpb) - Music playback control and library management.
- [WebSSH](https://github.com/webssh-software/webssh-mcpb-dxt-extension) - SSH terminal access via the browser.

## Science

- [Scientific Skills](https://github.com/silverstein/claude-scientific-skills-desktop) - Scientific computation reference corpus.
- [SmileyMCPB](https://github.com/lukasmki/SmileyMCPB) - SMILES string toolkit for chemistry and molecular data.

## Infrastructure and Observability

- [Blockscout](https://github.com/blockscout/mcp-server) - Blockchain data exploration and analytics.
- [Kintone](https://github.com/kintone/mcp-server) - Business application platform for custom workflows.
- [macOS](https://github.com/macuse-app/macuse-mcp) - Native system functionality bridge for Apple desktops.
- [SigNoz](https://github.com/SigNoz/signoz-mcp-server) - Observability, monitoring, and distributed tracing.
- [WordPress](https://github.com/Automattic/wpcom-mcp-bundle) - Site and content management for WP.com.

## Utilities

- [Abstract](https://github.com/NimbleBrainInc/mcp-abstract) - Email validation, IP geolocation, and VAT verification.
- [Barcode](https://github.com/theluckystrike/mcp-servers/tree/main/servers/barcode) - Generate QR codes and barcodes (SEPA payment QR, Code 128, EAN-13) as SVG or PNG, offline. (mcp.zovo.one)
- [Currency](https://github.com/theluckystrike/mcp-servers/tree/main/servers/currency) - Live and historical exchange rates from the European Central Bank, cached locally. (mcp.zovo.one)
- [DeepL](https://github.com/NimbleBrainInc/mcp-deepl) - Professional neural machine translation for 30+ languages.
- [Echo](https://github.com/NimbleBrainInc/mcp-echo) - MCP protocol testing and debugging tool.
- [Finnhub](https://github.com/NimbleBrainInc/mcp-finnhub) - Real-time stock quotes, financials, and company news.
- [Image](https://github.com/theluckystrike/mcp-servers/tree/main/servers/image) - Resize, convert, compress, crop, thumbnail, and watermark images locally. (mcp.zovo.one)
- [IPInfo](https://github.com/NimbleBrainInc/mcp-ipinfo) - IP geolocation, ASN lookups, and network intelligence.
- [National Parks](https://github.com/NimbleBrainInc/mcp-nationalparks) - US national park information, alerts, and campgrounds.
- [OpenWeatherMap](https://github.com/NimbleBrainInc/mcp-openweathermap) - Weather forecasts, air quality, and UV index data.
- [PDF](https://github.com/theluckystrike/mcp-servers/tree/main/servers/pdf) - Merge, split, extract, rotate, reorder, and stamp PDF files. (mcp.zovo.one)
- [PDF.co](https://github.com/NimbleBrainInc/mcp-pdfco) - PDF manipulation, conversion, OCR, and text extraction.
- [PolyNeural](https://github.com/PolyNeural-ai/mcpb) - Persistent AI memory via knowledge graphs.
- [Price Tracker](https://github.com/theluckystrike/mcp-servers/tree/main/servers/price-tracker) - Track prices and get notified when a target price is hit. (mcp.zovo.one)
- [Zip](https://github.com/theluckystrike/mcp-servers/tree/main/servers/zip) - Create, inspect, and extract zip archives with a zip-bomb and path-traversal check. (mcp.zovo.one)

## Build Tools

- [mcpb](https://www.npmjs.com/package/@anthropic-ai/mcpb) - Official CLI for packing and validating MCPB bundles.
- [mcpb-pack](https://github.com/NimbleBrainInc/mcpb-pack) - GitHub Action for building MCPB bundles in CI/CD pipelines.
- [mpak](https://github.com/NimbleBrainInc/mpak) - Registry and CLI for discovering and running MCPB bundles.

## Contributing

See [contributing.md](contributing.md) for how to add a bundle to this list.

Looking for a server to package? Check the [wanted list](docs/wanted.md).
