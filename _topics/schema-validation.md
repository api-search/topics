---
layout: topic
slug: schema-validation
name: Schema Validation
kind: topic
description: Schema validation is the practice of verifying that data structures conform to a defined schema, contract, or specification. In API development, schema validation ensures API requests and responses match declared OpenAPI, JSON Schema, AsyncAPI, or GraphQL specifications, enabling contract testing, governance, and runtime integrity. Key tools include AJV, Hyperjump JSON Schema, Spectral, and Schemathesis, each addressing different validation contexts from CLI pipelines to runtime API testing.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/schema-validation.png
tags:
- API Governance
- Contract Testing
- JSON-Schema
- OpenAPI
- Schema Validation
repo: https://github.com/api-evangelist/schema-validation
api_count: 6
apis:
- name: AJV JSON Schema Validator
  description: AJV (Another JSON Validator) is the fastest JSON Schema validator for JavaScript and Node.js. It supports JSON Schema drafts 04/06/07/2019-09/ 2020-12 and JSON Type Definition (RFC 8927). AJV compiles schemas to highly optimized JavaScript…
  url: https://ajv.js.org/
- name: Hyperjump JSON Schema
  description: Hyperjump is a JSON Schema validation, annotation, and bundling library for JavaScript. It supports JSON Schema drafts 04, 06, 07, 2019-09, 2020-12, OpenAPI 3.0, and OpenAPI 3.1 vocabularies. It also provides an OAS Schema Validator for Op…
  url: https://json-schema.hyperjump.io/
- name: Spectral
  description: Spectral is an open-source JSON/YAML linter and schema validator from Stoplight. It provides customizable rulesets for validating OpenAPI, AsyncAPI, JSON Schema, and any custom schema format, enabling API governance at the CLI, IDE, and CI…
  url: https://stoplight.io/open-source/spectral
- name: OpenAPI Schema Validator
  description: A Node.js library for validating OpenAPI schemas against the OpenAPI specification for versions 2.0 (Swagger), 3.0.x, and 3.1.x. Available as both a library and CLI tool.
  url: https://github.com/seriousme/openapi-schema-validator
- name: Blaze JSON Schema Validator
  description: An ultra high-performance JSON Schema validator for C++ with support for JSON Schema Draft 4, Draft 6, Draft 7, 2019-09, and 2020-12. Suitable for high-throughput server-side validation scenarios.
  url: https://github.com/sourcemeta/blaze
- name: AlterSchema
  description: A tooling library for upgrading JSON Schema documents from previous versions (Draft 4, 6, 7, 2019-09) to the latest draft 2020-12, enabling schema modernization pipelines.
  url: https://github.com/sourcemeta/alterschema
links:
- type: IssueTracker
  url: https://github.com/ajv-validator/ajv/issues
- type: Releases
  url: https://github.com/ajv-validator/ajv/releases
- type: CodeOfConduct
  url: https://github.com/ajv-validator/ajv/blob/master/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/ajv-validator/ajv/blob/master/CONTRIBUTING.md
- type: License
  url: https://github.com/ajv-validator/ajv/blob/master/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/schema-validation/blob/main/security/schema-validation-domain-security.yml
- type: Website
  url: https://json-schema.org/
- type: Documentation
  url: https://json-schema.org/learn
- type: Blog
  url: https://json-schema.org/blog
- type: GitHubOrganization
  url: https://github.com/json-schema-org
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-schema/schema-validation-config-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-structure/schema-validation-config-structure.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/json-ld/schema-validation-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/vocabulary/schema-validation-vocabulary.yml
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/schema-validation/refs/heads/main/examples/schema-validation-ajv-example.json
provider_count: 19
providers:
- slug: optic
  name: Optic
  description: Optic is an MIT-licensed command-line tool for OpenAPI linting, diffing and testing. It compares two versions of an OpenAPI document with behaviour-aware diffing to catch breaking changes before they ship, enforces style-guide rulesets (br…
  api_count: 1
  score_band: emerging
  score_composite: 21.1
  shared: 3
- slug: dredd
  name: Dredd
  description: Dredd is a language-agnostic, MIT-licensed open source command-line tool that validates a running HTTP API against its own API description document. It compiles every request/response pair documented in an API Blueprint, OpenAPI 2.0 or (ex…
  api_count: 1
  score_band: emerging
  score_composite: 20.2
  shared: 3
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 20.0
  shared: 3
- slug: apis-io
  name: APIs.io
  description: APIs.io is an open-source API search engine and federated discovery network built on the APIs.json specification. It indexes API providers and their individual APIs across the public internet along with the machine-readable artifacts they…
  api_count: 20
  score_band: exemplar
  score_composite: 88.8
  shared: 2
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 72.4
  shared: 2
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: strong
  score_composite: 65.1
  shared: 2
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: elva
  name: Elva
  description: 'API management platform for the agentic era: reads repos to build an API catalog, enforces per-audience contracts, generates tests, and turns APIs into governed, hosted MCP servers for AI agents. Built by Theneo. Exposes a public no-auth O…'
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 2
- slug: btc-war-live-market-data-api
  name: BTC War Live Market Data API
  description: Public, keyless, read-only real-time crypto market-data API from btcwar.net, exposing live Binance Spot snapshots and single-market observations for nine USDT pairs as JSON and Schema.org JSON-LD. Every response carries provenance, a sourc…
  api_count: 3
  score_band: developing
  score_composite: 47.9
  shared: 2
- slug: kiota
  name: Kiota
  description: 'Kiota is Microsoft''s open source (MIT) API client generator: a command line tool that turns any OpenAPI-described API into a strongly-typed, lightweight client in C#, Dart, Go, Java, PHP, Python, Ruby or TypeScript. It exists to remove the…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 2
- slug: schemathesis
  name: Schemathesis
  description: Schemathesis is a property-based API testing tool that automatically generates test cases from OpenAPI and GraphQL schemas to find bugs and specification violations. It uses the Hypothesis property-based testing framework to generate diver…
  api_count: 1
  score_band: thin
  score_composite: 33.0
  shared: 2
- slug: orval
  name: Orval
  description: Orval is an MIT-licensed open source code generator that turns any valid OpenAPI v3 or Swagger v2 specification into type-safe TypeScript. From one spec it emits HTTP request functions (Fetch by default, Axios optional), TanStack Query hoo…
  api_count: 1
  score_band: thin
  score_composite: 31.6
  shared: 2
- slug: nswag
  name: NSwag
  description: 'NSwag is the Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript, written in C# and maintained by Rico Suter under an MIT licence. It runs the contract in both directions: generating Swagger 2.0 and OpenAPI 3.0 documents from A…'
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: spectral
  name: Spectral
  description: Spectral is an open-source API style guide enforcer and linter from Stoplight, providing a flexible JSON/YAML linting engine with built-in support for OpenAPI (v3.1, v3.0, v2.0), Arazzo v1.0, and AsyncAPI v2.x. Teams use Spectral to define…
  api_count: 1
  score_band: emerging
  score_composite: 23.4
  shared: 2
- slug: style-guides
  name: API Style Guides
  description: A landscape index of public API style guides published by leading technology companies and standards bodies. API style guides codify conventions for resource modeling, URI design, HTTP method use, status codes, error formats, pagination, v…
  api_count: 11
  score_band: emerging
  score_composite: 21.4
  shared: 2
- slug: speclynx
  name: SpecLynx
  description: SpecLynx provides enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx products prioritize securi…
  api_count: 6
  score_band: emerging
  score_composite: 16.2
  shared: 2
- slug: portman
  name: Portman
  description: Portman is an open source CLI tool that auto-generates Postman collections with contract and variation tests from OpenAPI specifications, supporting OpenAPI 3.0 and 3.1, fuzzing, request customization, pre-request scripts, and direct uploa…
  api_count: 1
  score_band: emerging
  score_composite: 14.9
  shared: 2
- slug: jargon
  name: Jargon
  description: Jargon is a platform for Domain Driven Design for APIs and Enterprise Data Modelling. It provides text-based modelling, template-based API design, real-time validation, version control with breaking change detection, and generation of arti…
  api_count: 1
  score_band: emerging
  score_composite: 12.8
  shared: 2
---
