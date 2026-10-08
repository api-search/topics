---
layout: topic
slug: swagger
name: Swagger
kind: topic
description: Swagger is an open-source framework by SmartBear for designing, building, documenting, and consuming RESTful APIs using the OpenAPI Specification. Originally created by Wordnik in 2011, Swagger became the OpenAPI Specification (OAS) in 2016 under the OpenAPI Initiative. The Swagger toolset includes Swagger UI for interactive documentation, Swagger Editor for writing OpenAPI specs, and Swagger Codegen for generating client SDKs and server stubs. The latest OpenAPI standard version is 3.2.0 (released September 2025).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/swagger.png
tags:
- API Design
- Documentation
- Open Source
- OpenAPI
- REST
- Standards
- Swagger
repo: https://github.com/api-evangelist/swagger
api_count: 5
apis:
- name: Swagger UI
  description: Swagger UI renders OpenAPI specifications as interactive API documentation, allowing developers to explore and test API endpoints directly in the browser. It generates a rich HTML interface with try-it-out functionality from any OpenAPI 2.…
  url: https://swagger.io/tools/swagger-ui/
- name: Swagger Editor
  description: Swagger Editor is a browser-based editor for writing and validating OpenAPI and AsyncAPI specifications with real-time preview and validation. Available as a standalone web application and as Swagger Editor Next (v5).
  url: https://swagger.io/tools/swagger-editor/
- name: Swagger Codegen
  description: Swagger Codegen generates server stubs, client SDKs, and API documentation from OpenAPI specifications in over 40 languages including Python, Java, JavaScript, Go, Ruby, C#, Swift, and TypeScript.
  url: https://swagger.io/tools/swagger-codegen/
- name: Swagger Parser
  description: Swagger Parser (swagger-parser) is a JavaScript library for parsing, validating, and dereferencing OpenAPI 2.0 and 3.x specifications. Available as an npm package.
  url: https://github.com/swagger-api/swagger-parser
- name: OpenAPI Specification
  description: The OpenAPI Specification (formerly Swagger Specification) is a language-agnostic standard for describing HTTP APIs. The current versions are OAS 3.1.1 (stable) and OAS 3.2.0 (latest). Governed by the OpenAPI Initiative (OAI) under the Lin…
  url: https://swagger.io/specification/
links:
- type: VendorFacets
  url: https://github.com/api-evangelist/swagger/blob/main/vendor-facets/swagger-vendor-facets.yml
- type: IssueTracker
  url: https://github.com/swagger-api/swagger-ui/issues
- type: Releases
  url: https://github.com/swagger-api/swagger-ui/releases
- type: SecurityPolicy
  url: https://github.com/swagger-api/swagger-ui/blob/main/SECURITY.md
- type: ContributionGuide
  url: https://github.com/swagger-api/.github/blob/master/CONTRIBUTING.md
- type: License
  url: https://github.com/swagger-api/swagger-ui/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/swagger/blob/main/security/swagger-domain-security.yml
- type: LinkedIn
  url: https://www.linkedin.com/company/swagger
- type: Website
  url: https://swagger.io
- type: Documentation
  url: https://swagger.io/docs/
- type: GitHubOrganization
  url: https://github.com/swagger-api
- type: Blog
  url: https://swagger.io/blog/
- type: Tools
  url: https://swagger.io/tools/
- type: OpenAPI Specification
  url: https://swagger.io/specification/
- type: OpenAPI Initiative
  url: https://www.openapis.org/
- type: Community
  url: https://community.smartbear.com/
- type: Twitter
  url: https://twitter.com/SwaggerApi
provider_count: 117
providers:
- slug: openapi-generator
  name: OpenAPI Generator
  description: OpenAPI Generator is a community-governed, Apache-2.0 open-source project that generates client libraries (SDKs), server stubs, API documentation and configuration automatically from an OpenAPI Specification (v2 and v3). Forked from Swagge…
  api_count: 1
  score_band: developing
  score_composite: 41.9
  shared: 4
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 3
- slug: netcracker
  name: Netcracker
  description: Netcracker Technology is a Waltham, Massachusetts-based BSS/OSS and digital business software vendor and a wholly owned subsidiary of NEC Corporation. It sells cloud BSS, digital commerce and monetization, convergent charging, service and…
  api_count: 4
  score_band: strong
  score_composite: 57.4
  shared: 3
- slug: etsi
  name: ETSI
  description: ETSI, the European Telecommunications Standards Institute, is a not-for-profit standards development organisation headquartered in Sophia Antipolis, France, and one of only three bodies officially recognised by the European Union as a Euro…
  api_count: 24
  score_band: developing
  score_composite: 50.2
  shared: 3
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 3
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 3
- slug: zally
  name: Zally
  description: Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs aga…
  api_count: 1
  score_band: developing
  score_composite: 41.0
  shared: 3
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 3
- slug: orval
  name: Orval
  description: Orval is an MIT-licensed open source code generator that turns any valid OpenAPI v3 or Swagger v2 specification into type-safe TypeScript. From one spec it emits HTTP request functions (Fetch by default, Axios optional), TanStack Query hoo…
  api_count: 1
  score_band: thin
  score_composite: 38.4
  shared: 3
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 3
- slug: apicurio
  name: Apicurio
  description: Apicurio is an open source API and schema tooling platform maintained by Red Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance schema and API design registry), Apicurio Studio (a visual API designer for Op…
  api_count: 1
  score_band: thin
  score_composite: 32.3
  shared: 3
- slug: api-fiddle
  name: API-Fiddle
  description: API-Fiddle is an interactive, collaborative API design platform for creating professional APIs based on OpenAPI. It provides first-class support for OpenAPI 3.x, data transfer objects, API versioning, suggested response codes, parameter se…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 3
- slug: openapi-typescript-codegen
  name: OpenAPI TypeScript Codegen
  description: OpenAPI TypeScript Codegen is an MIT-licensed Node.js library and CLI by Ferdi Koomen that reads an OpenAPI 2.0 or 3.0 specification — JSON or YAML, from a path, URL, or string — and generates a lightweight, fully typed TypeScript client.…
  api_count: 1
  score_band: thin
  score_composite: 26.9
  shared: 3
- slug: fern-api
  name: Fern
  description: Fern is a developer-tools platform that turns a single API specification into idiomatic client SDKs, beautiful API documentation, and MCP servers. Given OpenAPI, AsyncAPI, gRPC/Protobuf, or Fern's own Fern Definition as input, Fern generat…
  api_count: 1
  score_band: thin
  score_composite: 26.6
  shared: 3
- slug: nswag
  name: NSwag
  description: 'NSwag is the Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript, written in C# and maintained by Rico Suter under an MIT licence. It runs the contract in both directions: generating Swagger 2.0 and OpenAPI 3.0 documents from A…'
  api_count: 1
  score_band: emerging
  score_composite: 25.9
  shared: 3
- slug: camara-project
  name: CAMARA Project
  description: CAMARA is the Telco Global API Alliance — an open-source project hosted by the Linux Foundation that defines, builds, and tests a unified set of network APIs across the world's mobile operators. Working alongside the GSMA Open Gateway comm…
  api_count: 24
  score_band: emerging
  score_composite: 24.5
  shared: 3
- slug: vacuum
  name: Vacuum
  description: Vacuum is the world's fastest and most versatile OpenAPI linter and toolkit, built in Go for validating and linting API specifications at scale. It is 100% compatible with Spectral rulesets and supports OpenAPI 3.0, 3.1, and 3.2.
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 18.4
  shared: 3
- slug: fastapi
  name: FastAPI
  description: FastAPI is a modern, fast (high-performance), web framework for building APIs with Python 3.7+ based on standard Python type hints.
  api_count: 1
  score_band: emerging
  score_composite: 18.2
  shared: 3
- slug: dapperdox
  name: DapperDox
  description: DapperDox is an open-source API documentation generator that creates beautiful, customizable reference documentation from OpenAPI specifications. It supports theming, overlays, and cross-referencing across multiple API specifications, maki…
  api_count: 1
  score_band: emerging
  score_composite: 16.2
  shared: 3
- slug: acknowledgments-md
  name: ACKNOWLEDGMENTS.md
  description: ACKNOWLEDGMENTS.md is a standardized file convention used in open source repositories to credit third-party software, libraries, inspirations, and other works that a project builds upon or is indebted to. It is a common practice for docume…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: wso2
  name: WSO2
  description: WSO2 API Manager is an open-source API management platform supporting REST, SOAP, and GraphQL with flexible hybrid deployment. It provides a unified control plane for managing APIs, AI models, and agents across on-premises, hybrid, and clo…
  api_count: 7
  score_band: exemplar
  score_composite: 79.9
  shared: 2
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 2
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 76.7
  shared: 2
- slug: cvent-event-cloud
  name: Cvent Event Cloud
  description: 'Cvent Event Cloud is the event management product line of the Cvent Platform. It supports the full event lifecycle: event creation, registration, marketing, agenda and session management, mobile event apps, onsite check-in, virtual and hyb…'
  api_count: 2
  score_band: exemplar
  score_composite: 71.9
  shared: 2
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 2
- slug: scalar
  name: Scalar
  description: Scalar is an open-source API platform built around the OpenAPI standard. It provides API documentation (API References), an offline-first API client, a centralized API registry for managing OpenAPI documents, JSON schemas and Spectral rule…
  api_count: 2
  score_band: exemplar
  score_composite: 71.7
  shared: 2
- slug: 0xarchive
  name: 0xArchive
  description: 0xArchive is a replayable market-data archive for two decentralised perpetuals venues, Hyperliquid and Lighter, delivered as one REST API, one WebSocket API that carries both live subscriptions and historical replay on a single connection,…
  api_count: 2
  score_band: exemplar
  score_composite: 71.6
  shared: 2
- slug: archbee
  name: Archbee
  description: Archbee is a documentation and knowledge-portal platform for software teams. It creates, manages and publishes technical documentation, API references and internal wikis, with collaborative editing, revision history, branching and review,…
  api_count: 11
  score_band: exemplar
  score_composite: 70.9
  shared: 2
- slug: canvas
  name: Canvas
  description: Canvas is Instructure's open-source learning management system (LMS) used by K-12, higher education, and corporate training organizations to deliver courses, assessments, and learner communication. Canvas exposes a comprehensive REST API a…
  api_count: 146
  score_band: exemplar
  score_composite: 68.2
  shared: 2
---
