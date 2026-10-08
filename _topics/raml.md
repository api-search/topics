---
layout: topic
slug: raml
name: RAML
kind: topic
description: RAML (RESTful API Modeling Language) is a YAML-based specification language for describing RESTful APIs with first-class support for reusable patterns, traits, resource types, data type annotations, libraries, overlays, and extensions. Developed by MuleSoft and Salesforce, RAML 1.0 is the current stable version. The raml-org GitHub organization maintains the canonical specification and related tooling, all of which are archived and read-only as of February 2024.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/raml.png
tags:
- API Design
- Specification Language
- Standards
- YAML
- REST
- API Modeling
- Developer Tools
repo: https://github.com/api-evangelist/raml
api_count: 1
apis:
- name: RAML Specification
  description: The RAML (RESTful API Modeling Language) specification defines a YAML 1.2-based language for describing HTTP-based APIs. RAML 1.0 introduces a unified type system, annotations, libraries, overlays, extensions, and improved OAuth support ov…
  url: https://raml.org
links:
- type: IssueTracker
  url: https://github.com/raml-org/raml-spec/issues
- type: Releases
  url: https://github.com/raml-org/raml-spec/releases
- type: DomainSecurity
  url: https://github.com/api-evangelist/raml/blob/main/security/raml-domain-security.yml
- type: Website
  url: https://raml.org
- type: Documentation
  url: https://raml.org/developers/raml-100-tutorial
- type: Specification
  url: https://github.com/raml-org/raml-spec
- type: GitHubOrganization
  url: https://github.com/raml-org
- type: Forums
  url: https://forum.raml.org
- type: Parser JavaScript
  url: https://github.com/raml-org/raml-js-parser-2
- type: Parser PHP
  url: https://github.com/raml-org/raml-php-parser
- type: TCK
  url: https://github.com/raml-org/raml-tck
- type: JSONSchemaConverter
  url: https://github.com/raml-org/ramldt2jsonschema
- type: WebapiParser
  url: https://github.com/raml-org/webapi-parser
- type: JSONLD
  url: https://github.com/api-evangelist/raml/blob/main/json-ld/raml-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/raml/blob/main/vocabulary/raml-vocabulary.yml
provider_count: 43
providers:
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 3
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 3
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 31.1
  shared: 3
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration,…
  api_count: 1
  score_band: emerging
  score_composite: 25.7
  shared: 3
- slug: rest
  name: REST
  description: REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DEL…
  api_count: 4
  score_band: emerging
  score_composite: 17.8
  shared: 3
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 2
- slug: aws-api-gateway
  name: Amazon API Gateway
  description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, a…
  api_count: 13
  score_band: exemplar
  score_composite: 70.0
  shared: 2
- slug: eclipse
  name: Eclipse Foundation
  description: The Eclipse Foundation is a non-profit (Belgian AISBL) that provides a global community of individuals and organizations with a mature, scalable and business-friendly environment for open source software collaboration and innovation. It is…
  api_count: 19
  score_band: strong
  score_composite: 63.6
  shared: 2
- slug: apiverve
  name: APIVerve
  description: An agent-native API marketplace exposing 300+ (367+ enumerated) ready-made REST APIs behind a single API key with a uniform JSON envelope. Offers REST, an alpha GraphQL gateway, OpenAPI + Postman contracts, a self-hosted apis.json, an llms…
  api_count: 1
  score_band: strong
  score_composite: 60.8
  shared: 2
- slug: smartbear
  name: SmartBear
  description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI fo…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: insomnia
  name: Insomnia
  description: Insomnia is an open-source, cross-platform API development platform by Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for CI/CD integration, cloud-ho…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: mediacaption-api
  name: MediaCaption API
  description: A credit-billed REST API for retrieving public YouTube transcripts, with single and bulk transcript jobs, job-level webhooks, and AI transcription/translation capabilities. Backed by a public OpenAPI 3.1 contract with bearer/X-API-Key auth…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: plandex
  name: Plandex
  description: Plandex is an open-source, terminal-based AI coding agent designed to take on large, multi-step software development tasks across many files in real world codebases. Written in Go and released under the MIT license, Plandex builds and exec…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 2
- slug: rapidapi
  name: RapidAPI
  description: RapidAPI operates the world's largest API marketplace, connecting developers to thousands of APIs through a single platform. Their developer platform provides tools for API discovery, testing, management, design, and gateway configuration,…
  api_count: 6
  score_band: developing
  score_composite: 41.7
  shared: 2
- slug: snapapi
  name: SnapAPI
  description: REST API for website screenshots, metadata extraction, text extraction, and PDF generation. Powered by headless Chromium. Free tier with 50 requests/month, no credit card required. API key issued via self-service signup.
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 2
- slug: crowdin
  name: Crowdin
  description: Crowdin is a localization management platform for software, mobile, games, and documentation. It offers a REST API v2 covering projects, files, strings, translations, screenshots, glossaries, MT engines, and webhooks, plus a single GraphQL…
  api_count: 1
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: platzi
  name: Platzi
  description: Platzi is the leading online learning platform in Latin America, offering thousands of technology, business, and marketing courses. For developers, Platzi (via PlatziLabs) publishes the free, public "Platzi Fake Store API" — a fully functi…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 2
- slug: the-guild-dev
  name: The Guild
  description: The Guild is an open-source software group building much of the GraphQL ecosystem's tooling, published together at the-guild.dev. Its portfolio spans GraphQL Hive (schema registry, usage observability and breaking-change detection), GraphQ…
  api_count: 10
  score_band: thin
  score_composite: 36.7
  shared: 2
- slug: tonic-ai
  name: Tonic.ai
  description: Tonic.ai builds developer-data products for de-identifying, subsetting, and synthesizing data for AI and software teams. The portfolio includes Tonic Structural (structured/semi-structured data), Tonic Textual (unstructured free-text and f…
  api_count: 1
  score_band: thin
  score_composite: 34.0
  shared: 2
- slug: lokalise
  name: Lokalise
  description: Lokalise is a translation management system (TMS) for software, mobile, web, games, and documentation. It pairs collaborative localization workflows with AI machine translation and a full-coverage REST API (APIv2) that exposes projects, ke…
  api_count: 1
  score_band: thin
  score_composite: 33.2
  shared: 2
- slug: playground
  name: Playground API — Free Stateful Mock REST & GraphQL Service
  description: A free, zero-configuration, stateful mock REST and GraphQL API sandbox by Nilesh Kumar / Niles Labs. Unlike static mock APIs, it provides stateful per-session virtual mutation overlays where POST/PUT/PATCH/DELETE mutations persist across G…
  api_count: 1
  score_band: thin
  score_composite: 31.5
  shared: 2
- slug: apiops-cycles-canvas
  name: APIOps Cycles Canvas
  description: APIOps Cycles Canvases are structured workshop tools for API strategy, design, and business modeling. The collection includes 10 canvas types covering API business models, value propositions, capacity planning, customer journeys, domain de…
  api_count: 1
  score_band: thin
  score_composite: 31.3
  shared: 2
- slug: voiden
  name: Voiden
  description: Voiden is an offline-first, Git-native API workspace that unifies API design, testing, and documentation in plain Markdown .void files stored alongside your codebase. It uses composable, reusable blocks (endpoints, auth, headers, params, b…
  api_count: 1
  score_band: thin
  score_composite: 31.2
  shared: 2
- slug: api-fiddle
  name: API-Fiddle
  description: API-Fiddle is an interactive, collaborative API design platform for creating professional APIs based on OpenAPI. It provides first-class support for OpenAPI 3.x, data transfer objects, API versioning, suggested response codes, parameter se…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 2
- slug: snapapi-pics
  name: SnapAPI
  description: SnapAPI is a REST API for turning any URL into visual captures or structured data with a single call - screenshots (PNG, JPEG, WebP, AVIF), full-page PDFs, scroll videos (MP4, WebM, GIF), markdown/text/metadata extraction tuned for AI pipe…
  api_count: 1
  score_band: thin
  score_composite: 29.1
  shared: 2
- slug: apiwiz
  name: APIwiz
  description: APIwiz is a federated API management platform that streamlines the complete API lifecycle from design through monetization. The low-code platform provides centralized control for organizations managing APIs across multiple cloud environmen…
  api_count: 1
  score_band: emerging
  score_composite: 26.1
  shared: 2
---
