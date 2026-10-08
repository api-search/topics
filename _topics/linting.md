---
layout: topic
slug: linting
name: API Linting
kind: topic
description: API Linting is a topic index for the tools, rulesets, vocabularies, and practices that automate API style guide enforcement across OpenAPI, AsyncAPI, JSON Schema, and adjacent contract formats. The collection catalogs the major open-source and commercial linters in use across the industry — Spectral, Vacuum, Redocly CLI, Optic, Apicurio, sweater-comb, Speakeasy, and Postman API governance — alongside shared schemas, JSON-LD context, and a working vocabulary so linting concepts can be reasoned about consistently across tools.
image: https://kinlane-images.s3.amazonaws.com/shared/api-evangelist-logos/api-evangelist-logo-butterfly.png
tags:
- API Design
- API Governance
- API Linting
- API Style Guide
- AsyncAPI
- JSON Schema
- Linting
- OpenAPI
- Quality Assurance
- Topic
repo: https://github.com/api-evangelist/linting
api_count: 10
apis:
- name: Spectral
  description: Stoplight's flexible JSON/YAML linter for creating automated style guides, with baked-in support for OpenAPI v3.1, v3.0, v2.0, Arazzo v1.0, and AsyncAPI v2.x. Spectral is the de facto reference linter for API style guides — every other too…
  url: https://stoplight.io/open-source/spectral
- name: Vacuum
  description: A Go-based, ultra-fast OpenAPI linter inspired by Spectral and fully compatible with existing Spectral rulesets. Vacuum tears through API specs at light speed, ships interactive HTML reports and a dashboard TUI, and embeds as a Go SDK for…
  url: https://quobix.com/vacuum/
- name: Redocly CLI
  description: Redocly's `lint` command identifies and reports problems in OpenAPI, AsyncAPI, Arazzo, or Open-RPC descriptions, helping teams "avoid bugs and make API or Arazzo descriptions more consistent." Rules and assertions are configured through `r…
  url: https://redocly.com/docs/cli/
- name: Optic
  description: Optic catches breaking changes and applies lint rules to OpenAPI specs, generating OpenAPI from real traffic and keeping it accurate with automatic schema testing and patches. The project was archived in January 2026 after Optic Labs was a…
  url: https://www.useoptic.com/
- name: Apicurio Registry
  description: Red Hat's open-source API/schema registry that stores and validates OpenAPI, AsyncAPI, JSON Schema, Avro, Protobuf, and GraphQL artifacts. While not a pure linter, Apicurio Registry performs content-rule validation on artifact upload and i…
  url: https://www.apicur.io/registry/
- name: Sweater Comb
  description: Snyk's TypeScript ruleset built on Optic CI that enforces consistency standards across OpenAPI specifications. Sweater Comb codifies the Snyk API Program's design rules so a growing federation of teams ship "cohesive, consistent and unsurp…
  url: https://github.com/snyk/sweater-comb
- name: Speakeasy Linter
  description: Speakeasy's OpenAPI validator with 90+ built-in rules across six categories — SDK generation, spec correctness, best practices, security, schema validation, and Speakeasy-specific checks. The `speakeasy-generation` ruleset is always applie…
  url: https://www.speakeasy.com/docs/prep-openapi/linting
- name: Postman API Governance
  description: Postman Spec Hub's governance engine applies linting rules to OpenAPI 2.0, 3.0, and 3.1 specifications, surfacing violations directly in the Issues tab below the spec editor. Enterprise teams can customize the rules Postman applies and enf…
  url: https://learning.postman.com/docs/api-governance/api-definition/api-definition-warnings/
- name: Stoplight Studio
  description: Stoplight's API design IDE embeds Spectral natively, surfacing ruleset violations as real-time editor feedback as designers author OpenAPI and JSON Schema. Studio is the canonical reference for IDE-grade linting feedback in the API design…
  url: https://stoplight.io/api-design
- name: APIMetrics
  description: APIMetrics provides live-traffic API monitoring with a rule engine that evaluates JSON Schema and response-shape compliance on every production call. Unlike static linters, APIMetrics enforces contract conformance at runtime as a complemen…
  url: https://apimetrics.io/
links:
- type: IssueTracker
  url: https://github.com/stoplightio/spectral/issues
- type: Releases
  url: https://github.com/stoplightio/spectral/releases
- type: CodeOfConduct
  url: https://github.com/stoplightio/spectral/blob/develop/.github/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/stoplightio/spectral/blob/develop/CONTRIBUTING.md
- type: DomainSecurity
  url: https://github.com/api-evangelist/linting/blob/main/security/linting-domain-security.yml
- type: Repository
  url: https://github.com/api-evangelist/linting
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: Network
  url: https://github.com/api-evangelist/api-evangelist-network
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/linting/refs/heads/main/json-schema/linting-rule-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/linting/refs/heads/main/json-structure/linting-rule-structure.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/linting/refs/heads/main/json-ld/linting-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/linting/refs/heads/main/vocabulary/linting-vocabulary.yml
- type: RelatedRepository
  url: https://github.com/api-evangelist/spotlight-rules
- type: RelatedRepository
  url: https://github.com/api-evangelist/spectral
- type: RelatedRepository
  url: https://github.com/api-evangelist/vacuum
- type: RelatedRepository
  url: https://github.com/api-evangelist/redocly
- type: RelatedRepository
  url: https://github.com/api-evangelist/optic
- type: RelatedRepository
  url: https://github.com/api-evangelist/stoplight
provider_count: 32
providers:
- slug: spectral
  name: Spectral
  description: Spectral is an open-source API style guide enforcer and linter from Stoplight, providing a flexible JSON/YAML linting engine with built-in support for OpenAPI (v3.1, v3.0, v2.0), Arazzo v1.0, and AsyncAPI v2.x. Teams use Spectral to define…
  api_count: 1
  score_band: emerging
  score_composite: 22.0
  shared: 7
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 18.4
  shared: 6
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 5
- slug: speclynx
  name: SpecLynx
  description: SpecLynx provides enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx products prioritize securi…
  api_count: 6
  score_band: emerging
  score_composite: 15.2
  shared: 4
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 3
- slug: zally
  name: Zally
  description: Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs aga…
  api_count: 1
  score_band: developing
  score_composite: 41.0
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
- slug: vacuum
  name: Vacuum
  description: Vacuum is the world's fastest and most versatile OpenAPI linter and toolkit, built in Go for validating and linting API specifications at scale. It is 100% compatible with Spectral rulesets and supports OpenAPI 3.0, 3.1, and 3.2.
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: optic
  name: Optic
  description: Optic is an MIT-licensed command-line tool for OpenAPI linting, diffing and testing. It compares two versions of an OpenAPI document with behaviour-aware diffing to catch breaking changes before they ship, enforces style-guide rulesets (br…
  api_count: 1
  score_band: emerging
  score_composite: 21.0
  shared: 3
- slug: jargon
  name: Jargon
  description: Jargon is a platform for Domain Driven Design for APIs and Enterprise Data Modelling. It provides text-based modelling, template-based API design, real-time validation, version control with breaking change detection, and generation of arti…
  api_count: 1
  score_band: emerging
  score_composite: 11.5
  shared: 3
- slug: apis-io
  name: APIs.io
  description: APIs.io is an open-source API search engine and federated discovery network built on the APIs.json specification. It indexes API providers and their individual APIs across the public internet along with the machine-readable artifacts they…
  api_count: 20
  score_band: exemplar
  score_composite: 90.1
  shared: 2
- slug: redocly
  name: Redocly
  description: Redocly is a company that specializes in API documentation and governance tooling. Their platform helps organizations create, manage, and publish API documentation through Realm (the integrated lifecycle platform that unifies Redoc, Revel,…
  api_count: 4
  score_band: exemplar
  score_composite: 82.6
  shared: 2
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 2
- slug: observeai
  name: Observe.AI
  description: Observe.AI is an agentic AI platform for the contact center, providing purpose-built AI agents that handle customer support end-to-end across voice and chat, real-time AI Copilot guidance that assists frontline agents during live interacti…
  api_count: 1
  score_band: strong
  score_composite: 54.9
  shared: 2
- slug: insomnia
  name: Insomnia
  description: Insomnia is an open-source, cross-platform API development platform by Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for CI/CD integration, cloud-ho…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: elva
  name: Elva
  description: 'API management platform for the agentic era: reads repos to build an API catalog, enforces per-audience contracts, generates tests, and turns APIs into governed, hosted MCP servers for AI agents. Built by Theneo. Exposes a public no-auth O…'
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: kiota
  name: Kiota
  description: 'Kiota is Microsoft''s open source (MIT) API client generator: a command line tool that turns any OpenAPI-described API into a strongly-typed, lightweight client in C#, Dart, Go, Java, PHP, Python, Ruby or TypeScript. It exists to remove the…'
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 2
- slug: btc-war-live-market-data-api
  name: BTC War Live Market Data API
  description: Public, keyless, read-only real-time crypto market-data API from btcwar.net, exposing live Binance Spot snapshots and single-market observations for nine USDT pairs as JSON and Schema.org JSON-LD. Every response carries provenance, a sourc…
  api_count: 3
  score_band: developing
  score_composite: 44.1
  shared: 2
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 2
- slug: naftiko
  name: Naftiko
  description: Naftiko builds spec-driven integration software for AI agents. Its two Apache 2.0 Java engines — Ikanos, a capability engine, and Polychro, a polyglot spec linter — let a team declare a slice of its business in a single YAML capability fil…
  api_count: 0
  score_band: developing
  score_composite: 40.1
  shared: 2
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 31.1
  shared: 2
- slug: api-fiddle
  name: API-Fiddle
  description: API-Fiddle is an interactive, collaborative API design platform for creating professional APIs based on OpenAPI. It provides first-class support for OpenAPI 3.x, data transfer objects, API versioning, suggested response codes, parameter se…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 2
- slug: events
  name: Events
  description: Event-driven APIs catalog. Documents the landscape of brokers, streaming platforms, schema registries, and the specifications that standardize how events are described, transported, and stored. "Events" is the broader category that contain…
  api_count: 18
  score_band: thin
  score_composite: 28.8
  shared: 2
- slug: apiwiz
  name: APIwiz
  description: APIwiz is a federated API management platform that streamlines the complete API lifecycle from design through monetization. The low-code platform provides centralized control for organizations managing APIs across multiple cloud environmen…
  api_count: 1
  score_band: emerging
  score_composite: 26.1
  shared: 2
- slug: nswag
  name: NSwag
  description: 'NSwag is the Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript, written in C# and maintained by Rico Suter under an MIT licence. It runs the contract in both directions: generating Swagger 2.0 and OpenAPI 3.0 documents from A…'
  api_count: 1
  score_band: emerging
  score_composite: 25.9
  shared: 2
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration,…
  api_count: 1
  score_band: emerging
  score_composite: 25.7
  shared: 2
- slug: dredd
  name: Dredd
  description: Dredd is a language-agnostic, MIT-licensed open source command-line tool that validates a running HTTP API against its own API description document. It compiles every request/response pair documented in an API Blueprint, OpenAPI 2.0 or (ex…
  api_count: 1
  score_band: emerging
  score_composite: 19.2
  shared: 2
---
