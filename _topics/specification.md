---
layout: topic
slug: specification
name: Specification
kind: topic
description: A subject-matter collection covering API specifications, specification formats, specification-driven development, and the broader specification landscape. This includes OpenAPI, AsyncAPI, JSON Schema, GraphQL SDL, Arazzo, gRPC Protocol Buffers, RAML, API Blueprint, and other machine-readable API description formats. Specification-first development treats the API contract as the source of truth for code generation, documentation, testing, and governance.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/specification.png
tags:
- API Design
- API Governance
- AsyncAPI
- Contract Testing
- JSON Schema
- OpenAPI
- Specification
- Standards
repo: https://github.com/api-evangelist/specification
api_count: 4
apis:
- name: OpenAPI Specification
  description: The OpenAPI Specification (OAS) is the industry-standard format for describing REST/HTTP APIs. Maintained by the OpenAPI Initiative under the Linux Foundation, it enables code generation, interactive documentation, mock servers, contract t…
  url: https://www.openapis.org/
- name: AsyncAPI Specification
  description: AsyncAPI is the standard for defining event-driven and message-based APIs. Modeled on the OpenAPI Specification but extended for asynchronous protocols including Kafka, AMQP, MQTT, WebSocket, and SNS/SQS. Used for generating documentation,…
  url: https://www.asyncapi.com/
- name: JSON Schema
  description: JSON Schema is a vocabulary for annotating and validating JSON documents. It is the foundation of OpenAPI 3.1 schema definitions and used across the API ecosystem for request/response validation, code generation, and data contract enforcem…
  url: https://json-schema.org/
- name: Arazzo Specification
  description: The Arazzo Specification (formerly OpenAPI Workflows) describes multi-step API sequences, enabling documentation and automated testing of complex API interactions that span multiple operations. Used for contract testing and API workflow do…
  url: https://spec.openapis.org/arazzo/latest.html
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/specification/blob/main/security/specification-domain-security.yml
- type: Organization
  url: https://www.openapis.org/
- type: Organization
  url: https://www.asyncapi.com/
- type: Organization
  url: https://json-schema.org/
- type: Tools
  url: https://openapi.tools/
- type: Specification
  url: https://spec.openapis.org/oas/latest.html
provider_count: 49
providers:
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 18.4
  shared: 6
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 4
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 4
- slug: spectral
  name: Spectral
  description: Spectral is an open-source API style guide enforcer and linter from Stoplight, providing a flexible JSON/YAML linting engine with built-in support for OpenAPI (v3.1, v3.0, v2.0), Arazzo v1.0, and AsyncAPI v2.x. Teams use Spectral to define…
  api_count: 1
  score_band: emerging
  score_composite: 22.0
  shared: 4
- slug: speclynx
  name: SpecLynx
  description: SpecLynx provides enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx products prioritize securi…
  api_count: 6
  score_band: emerging
  score_composite: 15.2
  shared: 4
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 3
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 42.8
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
- slug: apis-json
  name: APIs.json
  description: APIs.json is an open, machine-readable specification that API providers can use to describe their API operations, similar to how websites use sitemap.xml. The format provides a lightweight means for individuals and organizations to documen…
  api_count: 1
  score_band: thin
  score_composite: 28.2
  shared: 3
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration,…
  api_count: 1
  score_band: emerging
  score_composite: 25.7
  shared: 3
- slug: optic
  name: Optic
  description: Optic is an MIT-licensed command-line tool for OpenAPI linting, diffing and testing. It compares two versions of an OpenAPI document with behaviour-aware diffing to catch breaking changes before they ship, enforces style-guide rulesets (br…
  api_count: 1
  score_band: emerging
  score_composite: 21.0
  shared: 3
- slug: dredd
  name: Dredd
  description: Dredd is a language-agnostic, MIT-licensed open source command-line tool that validates a running HTTP API against its own API description document. It compiles every request/response pair documented in an API Blueprint, OpenAPI 2.0 or (ex…
  api_count: 1
  score_band: emerging
  score_composite: 19.2
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
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 2
- slug: netcracker
  name: Netcracker
  description: Netcracker Technology is a Waltham, Massachusetts-based BSS/OSS and digital business software vendor and a wholly owned subsidiary of NEC Corporation. It sells cloud BSS, digital commerce and monetization, convergent charging, service and…
  api_count: 4
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: smartbear
  name: SmartBear
  description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI fo…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: insomnia
  name: Insomnia
  description: Insomnia is an open-source, cross-platform API development platform by Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for CI/CD integration, cloud-ho…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: gsma
  name: GSMA
  description: The GSMA (GSM Association) is the London-headquartered global trade body for the mobile industry, representing roughly 750 mobile network operators and around 400 companies in the wider mobile ecosystem, and the organiser of MWC Barcelona.…
  api_count: 37
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: elva
  name: Elva
  description: 'API management platform for the agentic era: reads repos to build an API catalog, enforces per-audience contracts, generates tests, and turns APIs into governed, hosted MCP servers for AI agents. Built by Theneo. Exposes a public no-auth O…'
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: etsi
  name: ETSI
  description: ETSI, the European Telecommunications Standards Institute, is a not-for-profit standards development organisation headquartered in Sophia Antipolis, France, and one of only three bodies officially recognised by the European Union as a Euro…
  api_count: 24
  score_band: developing
  score_composite: 50.2
  shared: 2
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: agntcy
  name: AGNTCY
  description: AGNTCY is the open collective for agent interoperability, initiated by Outshift — Cisco's incubation group — and governed under the Linux Foundation (LF Projects, LLC), developed in the open across 52 public repositories. It publishes spec…
  api_count: 4
  score_band: developing
  score_composite: 48.4
  shared: 2
- slug: kiota
  name: Kiota
  description: 'Kiota is Microsoft''s open source (MIT) API client generator: a command line tool that turns any OpenAPI-described API into a strongly-typed, lightweight client in C#, Dart, Go, Java, PHP, Python, Ruby or TypeScript. It exists to remove the…'
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 2
- slug: 3gpp
  name: 3GPP
  description: 3GPP (the 3rd Generation Partnership Project) is the global standards partnership that writes the technical specifications for mobile networks — GSM, UMTS, LTE, 5G and the ongoing 6G work — through seven regional Organizational Partners (A…
  api_count: 116
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: asyncapi
  name: AsyncAPI
  description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, valid…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: opentravel-alliance
  name: OpenTravel Alliance
  description: The OpenTravel Alliance is a volunteer, non-profit travel technology standards body headquartered in Melbourne, Florida, United States. Since 1999 it has published the OpenTravel Specification — the OTA 1.0 XML message suite (releases 2001…
  api_count: 8
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: btc-war-live-market-data-api
  name: BTC War Live Market Data API
  description: Public, keyless, read-only real-time crypto market-data API from btcwar.net, exposing live Binance Spot snapshots and single-market observations for nine USDT pairs as JSON and Schema.org JSON-LD. Every response carries provenance, a sourc…
  api_count: 3
  score_band: developing
  score_composite: 44.1
  shared: 2
- slug: zally
  name: Zally
  description: Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs aga…
  api_count: 1
  score_band: developing
  score_composite: 41.0
  shared: 2
---
