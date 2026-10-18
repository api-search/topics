---
layout: topic
slug: spreadsheets
name: Spreadsheets
kind: topic
description: Spreadsheets covers the APIs, tools, and services for programmatic access to spreadsheet data across major platforms including Google Sheets and Microsoft Excel. The Google Sheets API v4 provides RESTful access to read, write, format, and manage Google Spreadsheets. The Microsoft Graph Excel API enables reading and writing Excel workbooks stored in OneDrive for Business and SharePoint. Third-party services like SheetDB, Sheety, Sheet Best, and Sheet2API convert spreadsheets into REST APIs for use as lightweight backends. Spreadsheet APIs are widely used for data import/export, automated reporting, form submissions, lightweight CMS, and business process automation.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/spreadsheets.png
tags:
- Spreadsheets
- Data
- Google Sheets
- Excel
- Productivity
- Automation
repo: https://github.com/api-evangelist/spreadsheets
api_count: 7
apis:
- name: Microsoft Graph Excel API
  description: The Microsoft Graph Excel API enables reading and writing Excel workbooks (.xlsx format) stored in OneDrive for Business, SharePoint, or Group drives via the Microsoft Graph REST API. Supports worksheets, ranges, tables, charts, named item…
  url: https://learn.microsoft.com/en-us/graph/api/resources/excel
- name: SheetDB
  description: SheetDB is a service that turns any Google Sheet into a JSON REST API. Provides GET, POST, PUT, PATCH, and DELETE endpoints against spreadsheet data, supporting full CRUD operations without code. Used for prototyping, simple backends, and…
  url: https://sheetdb.io/
- name: Sheety
  description: Sheety converts Google Spreadsheets into RESTful JSON APIs, providing simple HTTP endpoints for reading and writing spreadsheet data. Supports GET, POST, PUT, PATCH, and DELETE operations with optional API key authentication.
  url: https://sheety.co/
- name: Spreadsheets Developer Metadata API
  description: Manage developer metadata attached to spreadsheets
  url: https://developers.google.com/workspace/sheets/api
- name: Spreadsheets Sheets API
  description: Sheet-level operations
  url: https://developers.google.com/workspace/sheets/api
- name: Spreadsheets API
  description: Spreadsheet-level operations
  url: https://developers.google.com/workspace/sheets/api
- name: Spreadsheets Values API
  description: Read and write cell values
  url: https://developers.google.com/workspace/sheets/api
links:
- type: Plans
  url: https://github.com/api-evangelist/spreadsheets/blob/main/plans/spreadsheets-plans-pricing.yml
- type: RateLimits
  url: https://github.com/api-evangelist/spreadsheets/blob/main/rate-limits/spreadsheets-rate-limits.yml
- type: FinOps
  url: https://github.com/api-evangelist/spreadsheets/blob/main/finops/spreadsheets-finops.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/spreadsheets/blob/main/agentic-access/spreadsheets-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/spreadsheets/blob/main/security/spreadsheets-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/spreadsheets/blob/main/security/spreadsheets-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/spreadsheets/blob/main/authentication/spreadsheets-authentication.yml
- type: OAuthScopes
  url: https://github.com/api-evangelist/spreadsheets/blob/main/scopes/spreadsheets-scopes.yml
- type: Website
  url: https://developers.google.com/workspace/sheets/api
- type: Reference
  url: https://learn.microsoft.com/en-us/graph/api/resources/excel
- type: OpenAPI
  url: https://github.com/api-evangelist/spreadsheets/blob/main/openapi/_original/google-sheets-openapi.yml
- type: JSONSchema
  url: https://github.com/api-evangelist/spreadsheets/blob/main/json-schema/spreadsheet-range-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/spreadsheets/blob/main/json-schema/spreadsheet-value-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/spreadsheets/blob/main/json-structure/spreadsheet-range-structure.json
- type: JSONLD
  url: https://github.com/api-evangelist/spreadsheets/blob/main/json-ld/spreadsheets-context.jsonld
- type: SpectralRules
  url: https://github.com/api-evangelist/spreadsheets/blob/main/rules/spreadsheets-rules.yml
- type: Vocabulary
  url: https://github.com/api-evangelist/spreadsheets/blob/main/vocabulary/spreadsheets-vocabulary.yml
provider_count: 51
providers:
- slug: fundamental-research-labs
  name: Fundamental Research Labs
  description: Fundamental Research Labs (formerly Altera) is an applied AI research company building autonomous, collaborative AI agents, founded by researchers from MIT EECS, the Stanford NLP Group, Google X, and Citadel and backed by Andreessen Horowi…
  api_count: 2
  score_band: strong
  score_composite: 60.6
  shared: 4
- slug: rows
  name: Rows
  description: Rows is an AI-powered spreadsheet that connects to live data from dozens of business tools and lets teams build reports, dashboards and lightweight data apps without leaving a familiar grid. Beyond the app, Rows ships a public REST API (ba…
  api_count: 1
  score_band: developing
  score_composite: 40.8
  shared: 4
- slug: airtable
  name: Airtable
  description: Airtable is a cloud-based collaboration service that combines the simplicity of a spreadsheet with the complexity of a database. It provides APIs for managing bases, tables, records, and more.
  api_count: 3
  score_band: strong
  score_composite: 61.5
  shared: 3
- slug: quadratic
  name: Quadratic
  description: Quadratic is an AI-native infinite spreadsheet that combines Python, SQL, JavaScript, formulas, and AI agents on a single canvas, with live connections to databases like PostgreSQL, MySQL, BigQuery, and Snowflake. Its token-authenticated D…
  api_count: 2
  score_band: strong
  score_composite: 54.3
  shared: 3
- slug: zoho-sheet
  name: Zoho Sheet
  description: Online spreadsheet application with a REST API for reading, writing, and manipulating spreadsheet data, cells, formulas, and exporting to various formats. The Zoho Sheet Data API v2 supports workbook management, worksheet operations, cell…
  api_count: 1
  score_band: thin
  score_composite: 33.5
  shared: 3
- slug: microsoft-excel-macros
  name: Microsoft Excel Macros
  description: A collection of APIs and resources for working with Microsoft Excel Macros, VBA automation, and Excel extensibility including the Office JavaScript API and COM automation.
  api_count: 3
  score_band: emerging
  score_composite: 26.1
  shared: 3
- slug: crunched
  name: Crunched
  description: Crunched is an AI Excel analyst for power users in management consulting, investment banking, private equity, and corporate finance. Working as a native Microsoft Excel add-in (Mac and PC) and a companion PowerPoint deck reviewer, it build…
  api_count: 0
  score_band: minimal
  score_composite: 8.7
  shared: 3
- slug: coda-project
  name: Coda Project
  description: Coda Project, Inc. is the maker of Coda (now branded Superhuman Docs), an all-in-one collaborative workspace that blends the flexibility of a document, the structure of a spreadsheet, the power of applications, and the intelligence of AI i…
  api_count: 2
  score_band: exemplar
  score_composite: 71.6
  shared: 2
- slug: lucid
  name: Lucid
  description: Lucid Software Inc. is the visual collaboration company behind the Lucid Suite — Lucidchart (intelligent diagramming), Lucidspark (virtual whiteboarding) and Lucidscale (cloud visualization) — plus the Lucid Cloud, Process and Enterprise S…
  api_count: 6
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: microsoft-graph
  name: Microsoft Graph
  description: Microsoft Graph is the gateway to data and intelligence in Microsoft 365. It provides a unified programmability model that you can use to access data in Microsoft 365, Windows 10, and Enterprise Mobility + Security.
  api_count: 71
  score_band: strong
  score_composite: 62.6
  shared: 2
- slug: celonis
  name: Celonis
  description: Celonis is the process intelligence and process mining company. Its cloud platform ingests event data from enterprise systems, builds Knowledge Models of how business processes actually run, and surfaces KPIs, bottlenecks and automation op…
  api_count: 7
  score_band: strong
  score_composite: 62.5
  shared: 2
- slug: aito-technologies
  name: Aito Technologies
  description: Aito Technologies (Aito.ai, legal entity Episto Oy of Vantaa, Finland) builds a predictive database that delivers instant, calibrated machine-learning predictions from live business data with no model training. Its REST Query API exposes a…
  api_count: 1
  score_band: strong
  score_composite: 56.3
  shared: 2
- slug: avoma
  name: Avoma
  description: Avoma is an AI-powered meeting assistant platform that automates note‑taking, scheduling, and coaching for sales and revenue teams. It records and transcribes meetings in real time, generates structured summaries, pushes data to CRMs, and…
  api_count: 2
  score_band: strong
  score_composite: 56.0
  shared: 2
- slug: google-sheets
  name: Google Sheets
  description: API for reading, writing, and formatting data in Google Sheets.
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 2
- slug: microsoft-excel
  name: Microsoft Excel
  description: APIs for automating, integrating, and extending Microsoft Excel functionality including workbook management, data manipulation, charting, and formula execution through Microsoft Graph REST APIs.
  api_count: 11
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: equals
  name: Equals
  description: Equals is an AI analytics platform that builds trusted spreadsheets and dashboards for revenue operations and go-to-market teams. It connects directly to databases and SaaS tools — PostgreSQL, MySQL, BigQuery, Snowflake, Redshift, Azure SQ…
  api_count: 1
  score_band: developing
  score_composite: 49.3
  shared: 2
- slug: paidhandshake
  name: PaidHandshake Exchange
  description: PaidHandshake Exchange is a live AI‑enabled marketplace that connects autonomous agents, human workers, and data sources to fulfill commercial intelligence, procurement, and research requests. The platform offers a searchable catalog of ve…
  api_count: 1
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: coefficient-works
  name: Coefficient Works
  description: Coefficient Works, Inc. (operating as Coefficient) is a San Mateo, California no-code data platform that connects live business data to Google Sheets and Microsoft Excel. Founded in 2019 by Navneet Loiwal and Tommy Tsai, the company provid…
  api_count: 0
  score_band: developing
  score_composite: 45.4
  shared: 2
- slug: codewords
  name: Agemo
  description: Agemo, operating under the brand CodeWords, provides AI‑driven workflow automation that lets users describe processes in natural language and instantly generate live WhatsApp and other tool integrations. The platform offers a visual UI, te…
  api_count: 1
  score_band: developing
  score_composite: 44.3
  shared: 2
- slug: memory
  name: Memory
  description: Memory AS (operating as Timely, timely.com) is an Oslo, Norway based software company behind Timely, an AI-powered automatic time tracking and timesheet platform for consultancies, agencies, professional-services firms and SaaS teams. Its…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: stilla
  name: Stilla
  description: Stilla is an AI teammate for the whole company — an AI agent that connects to a team's tools (Slack, Microsoft Teams, GitHub, Linear, Notion, Google Workspace and 3,000+ more) and turns chats, meetings, and conversations into finished work…
  api_count: 1
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: microsoft-excel-advanced
  name: Microsoft Excel (Advanced)
  description: Advanced automation and integration APIs for Microsoft Excel, enabling programmatic access to spreadsheet data, formulas, charts, and automation capabilities through Microsoft Graph, Office Scripts, JavaScript add-ins, custom functions, On…
  api_count: 1
  score_band: developing
  score_composite: 39.4
  shared: 2
- slug: smartsheet
  name: Smartsheet
  description: Smartsheet is a SaaS work management and collaboration platform that combines spreadsheet-style sheets, project plans, Gantt charts, dashboards, forms, and workflow automation for teams and enterprises. The Smartsheet REST API provides pro…
  api_count: 1
  score_band: thin
  score_composite: 38.6
  shared: 2
- slug: the-interaction-company-of-california
  name: The Interaction Company Of California
  description: The Interaction Company of California (d/b/a Poke) builds Poke, a proactive AI assistant that lives in Apple Messages, WhatsApp, Telegram, and SMS. Poke texts like a human, knows the user, and integrates with their email, calendar, reminde…
  api_count: 1
  score_band: thin
  score_composite: 37.9
  shared: 2
- slug: teammates
  name: Teammates
  description: Teammates ("AI that works") is Super Duper Labs' end-to-end platform for designing and managing a virtual AI workforce. Companies create AI teammates that autonomously execute natural-language assignments across the SaaS tools their human…
  api_count: 1
  score_band: thin
  score_composite: 36.0
  shared: 2
- slug: agentkey
  name: AgentKey (Data API Layer)
  description: AgentKey (Data API Layer) provides a unified gateway that connects AI agents to a wide range of digital services, including social media, crypto, finance, e‑commerce, and more. It offers a single API key to discover, describe, and execute…
  api_count: 2
  score_band: thin
  score_composite: 28.8
  shared: 2
- slug: viktor
  name: Viktor
  description: 'Viktor is an autonomous AI employee that lives inside Slack and Microsoft Teams, connects to 3,200+ business tools, and completes real work rather than just answering questions: pulling and reconciling data, generating reports and dashboar…'
  api_count: 0
  score_band: thin
  score_composite: 27.0
  shared: 2
- slug: sintra
  name: Sintra
  description: Sintra is a no-code AI-employees platform that gives small businesses a team of role-based digital workers. It ships 12 specialized AI helpers — such as Soshie (social media), Cassie (customer support), Seomi (SEO), Buddy, and Vizzy (meeti…
  api_count: 0
  score_band: emerging
  score_composite: 25.9
  shared: 2
- slug: openblock-labs
  name: OpenBlock Labs
  description: OpenBlock Labs builds OB-1, a self-improving autonomous coding agent that automates the software development lifecycle from PM to PR. OB-1 runs as a native terminal CLI and inside VS Code and JetBrains IDEs, consumes MCP (Model Context Pro…
  api_count: 1
  score_band: emerging
  score_composite: 23.7
  shared: 2
- slug: excel-macros
  name: Excel Macros
  description: Excel Macros refer to automated sequences of actions in Microsoft Excel, primarily written using VBA (Visual Basic for Applications). Excel also supports Office Scripts (TypeScript) for cloud-based automation and the Excel JavaScript API f…
  api_count: 3
  score_band: emerging
  score_composite: 22.4
  shared: 2
---
