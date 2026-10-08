---
layout: topic
slug: style-guides
name: API Style Guides
kind: topic
description: A landscape index of public API style guides published by leading technology companies and standards bodies. API style guides codify conventions for resource modeling, URI design, HTTP method use, status codes, error formats, pagination, versioning, deprecation, idempotency, hypermedia, and security so that APIs across an organization (or an industry) behave consistently. This topic repo catalogs the canonical industry style guides, compares the pillars each one chooses to mandate, and provides a shared vocabulary and JSON Schema for describing individual style guide rules.
image: https://kinlane-images.s3.amazonaws.com/shared/api-evangelist-logos/api-evangelist-logo-butterfly.png
tags:
- API Style Guides
- API Design
- API Governance
- REST
- OpenAPI
- Conventions
- Standards
- Documentation
- Developer Tools
repo: https://github.com/api-evangelist/style-guides
api_count: 11
apis:
- name: Microsoft REST API Guidelines
  description: Microsoft's organization-wide REST API design guidelines, originally published in 2016 and now maintained as separate Azure and Microsoft Graph guideline documents under the umbrella Guidelines.md. Licensed CC BY 4.0 to encourage adoption…
  url: https://github.com/microsoft/api-guidelines
- name: Google API Improvement Proposals (AIPs)
  description: Google's design review system, modeled on Python PEPs and Rust RFCs. AIPs are numbered, individually reviewable design documents covering resource-oriented design, standard methods, errors, pagination, naming conventions, and long-running…
  url: https://google.aip.dev/
- name: Zalando RESTful API and Event Guidelines
  description: The canonical open community style guide. Maintained by Zalando's API Guild and widely cited as the reference implementation for an API-First, OpenAPI-based REST and event-driven API program. Roughly 150+ numbered MUST/SHOULD/MAY rules cov…
  url: https://opensource.zalando.com/restful-api-guidelines/
- name: PayPal API Design Guidelines
  description: PayPal's API style guide covering service design principles, HTTP methods, hypermedia, naming, URI structure, JSON schema and types, error handling, versioning, and deprecation. The original repository at github.com/paypal/api-standards wa…
  url: https://github.com/paypal/api-standards
- name: adidas API Guidelines
  description: adidas group's API guidelines covering general principles, REST conventions, and asynchronous (Kafka / AsyncAPI) event design. Ships with a Spectral ruleset that validates both OpenAPI and AsyncAPI specifications against the guideline. MIT…
  url: https://github.com/adidas/api-guidelines
- name: Cisco REST API Design Guide
  description: Guidelines for Designing REST APIs at Cisco, developed across Cisco DevNet, Collaboration, and the Application Platform Group. Emphasizes "API-only" communication, aesthetic and behavioral consistency, OAuth2 / HTTPS security, and avoidanc…
  url: https://github.com/CiscoDevNet/api-design-guide
- name: Atlassian REST API Design Guidelines
  description: Atlassian's REST API design guidelines, applied across Jira, Confluence, Crowd, and plugin REST modules. Defines URI conventions (singular resources, versioned paths, expand/start-index/max-results query parameters), HTTP method semantics,…
  url: https://developer.atlassian.com/server/framework/atlassian-sdk/atlassian-rest-api-design-guidelines-version-1/
- name: Heroku Platform API Design Conventions
  description: Heroku's design conventions for the Platform API, documented in the Platform API Reference and the API Compatibility Policy. Notable for versioned media types (application/vnd.heroku+json; version=3), JSON Schema discovery via /schema, Ran…
  url: https://devcenter.heroku.com/articles/platform-api-reference
- name: GitLab API Style Guide
  description: GitLab's developer-facing API style guide for the REST API (v4) and GraphQL API. Mandates Grape DSL parameter validation, Entity-based response payloads, Title Case summary verbs aligned to HTTP method, deprecation markers with migration g…
  url: https://docs.gitlab.com/ee/development/api_styleguide.html
- name: Kubernetes API Conventions
  description: The Kubernetes API conventions document, maintained by SIG Architecture. Defines the "kind / apiVersion" object envelope, spec/status separation, resourceVersion-based optimistic concurrency, list semantics, label and selector validation,…
  url: https://github.com/kubernetes/community/blob/master/contributors/devel/sig-architecture/api-conventions.md
- name: IETF HTTPAPI Working Group Drafts and RFCs
  description: The IETF httpapi Working Group is producing the cross-vendor vocabulary that style guides increasingly cite normatively. Includes RFC 9457 Problem Details for HTTP APIs, RFC 9652 Link-Template, RFC 9745 Deprecation header, RFC 9727 api-cat…
  url: https://datatracker.ietf.org/wg/httpapi/documents/
links:
- type: IssueTracker
  url: https://github.com/microsoft/api-guidelines/issues
- type: SecurityPolicy
  url: https://github.com/microsoft/api-guidelines/blob/vNext/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/microsoft/.github/blob/main/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/microsoft/api-guidelines/blob/vNext/CONTRIBUTING.md
- type: DomainSecurity
  url: https://github.com/api-evangelist/style-guides/blob/main/security/style-guides-domain-security.yml
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/style-guides/main/json-schema/style-guide-rule-schema.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/style-guides/main/json-ld/style-guides-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/style-guides/main/vocabulary/style-guides-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/style-guides/tree/main/examples
- type: DeveloperPortal
  url: https://developer.apievangelist.com/
- type: Network
  url: https://developer.apievangelist.com/network/
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: RelatedTopic
  url: https://github.com/api-evangelist/design-standards
- type: RelatedTopic
  url: https://github.com/api-evangelist/rules
- type: RelatedTopic
  url: https://github.com/api-evangelist/policies
provider_count: 116
providers:
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 4
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 4
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 4
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 4
- slug: api-fiddle
  name: API-Fiddle
  description: API-Fiddle is an interactive, collaborative API design platform for creating professional APIs based on OpenAPI. It provides first-class support for OpenAPI 3.x, data transfer objects, API versioning, suggested response codes, parameter se…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 4
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration,…
  api_count: 1
  score_band: emerging
  score_composite: 25.7
  shared: 4
- slug: vacuum
  name: Vacuum
  description: Vacuum is the world's fastest and most versatile OpenAPI linter and toolkit, built in Go for validating and linting API specifications at scale. It is 100% compatible with Spectral rulesets and supports OpenAPI 3.0, 3.1, and 3.2.
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 4
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 18.4
  shared: 4
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: archbee
  name: Archbee
  description: Archbee is a documentation and knowledge-portal platform for software teams. It creates, manages and publishes technical documentation, API references and internal wikis, with collaborative editing, revision history, branching and review,…
  api_count: 11
  score_band: exemplar
  score_composite: 70.9
  shared: 3
- slug: apimatic
  name: APIMatic
  description: APIMatic is a developer experience platform for APIs that specializes in automated SDK generation, API documentation portal creation, specification validation and linting, and API format transformation. It supports 15+ API specification fo…
  api_count: 5
  score_band: strong
  score_composite: 63.1
  shared: 3
- slug: apiverve
  name: APIVerve
  description: An agent-native API marketplace exposing 300+ (367+ enumerated) ready-made REST APIs behind a single API key with a uniform JSON envelope. Offers REST, an alpha GraphQL gateway, OpenAPI + Postman contracts, a self-hosted apis.json, an llms…
  api_count: 1
  score_band: strong
  score_composite: 60.8
  shared: 3
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 3
- slug: insomnia
  name: Insomnia
  description: Insomnia is an open-source, cross-platform API development platform by Kong for designing, debugging, and testing HTTP, REST, GraphQL, gRPC, SOAP, WebSockets, SSE, and Socket.IO APIs. It includes an Inso CLI for CI/CD integration, cloud-ho…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 3
- slug: mediacaption-api
  name: MediaCaption API
  description: A credit-billed REST API for retrieving public YouTube transcripts, with single and bulk transcript jobs, job-level webhooks, and AI transcription/translation capabilities. Backed by a public OpenAPI 3.1 contract with bearer/X-API-Key auth…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 3
- slug: elva
  name: Elva
  description: 'API management platform for the agentic era: reads repos to build an API catalog, enforces per-audience contracts, generates tests, and turns APIs into governed, hosted MCP servers for AI agents. Built by Theneo. Exposes a public no-auth O…'
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 3
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 3
- slug: openapi-generator
  name: OpenAPI Generator
  description: OpenAPI Generator is a community-governed, Apache-2.0 open-source project that generates client libraries (SDKs), server stubs, API documentation and configuration automatically from an OpenAPI Specification (v2 and v3). Forked from Swagge…
  api_count: 1
  score_band: developing
  score_composite: 41.9
  shared: 3
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 3
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 3
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 31.1
  shared: 3
- slug: redoc
  name: ReDoc
  description: ReDoc is an open-source API documentation renderer for OpenAPI specifications by Redocly. It generates a responsive three-panel documentation layout from OpenAPI 3.1, 3.0, and Swagger 2.0 definitions. The left panel provides a search bar a…
  api_count: 1
  score_band: thin
  score_composite: 26.8
  shared: 3
- slug: elements
  name: Stoplight Elements
  description: Stoplight Elements is an open-source API documentation component library for rendering OpenAPI specifications interactively. It provides embeddable React and Web Components that produce beautiful, interactive API reference documentation fr…
  api_count: 1
  score_band: thin
  score_composite: 26.7
  shared: 3
- slug: fern-api
  name: Fern
  description: Fern is a developer-tools platform that turns a single API specification into idiomatic client SDKs, beautiful API documentation, and MCP servers. Given OpenAPI, AsyncAPI, gRPC/Protobuf, or Fern's own Fern Definition as input, Fern generat…
  api_count: 1
  score_band: thin
  score_composite: 26.6
  shared: 3
- slug: apiwiz
  name: APIwiz
  description: APIwiz is a federated API management platform that streamlines the complete API lifecycle from design through monetization. The low-code platform provides centralized control for organizations managing APIs across multiple cloud environmen…
  api_count: 1
  score_band: emerging
  score_composite: 26.1
  shared: 3
- slug: apigit
  name: APIGit
  description: APIGit is a Git-native platform for full lifecycle API development that combines version control, API design, documentation generation, governance, testing, and dynamic mock servers in a single integrated environment. Teams can build, publ…
  api_count: 4
  score_band: emerging
  score_composite: 25.9
  shared: 3
- slug: apinotes
  name: ApiNotes
  description: ApiNotes is an interactive API documentation tool that generates developer portals with live endpoint testing, code examples in multiple languages, and shareable documentation from OpenAPI and Swagger specifications.
  api_count: 1
  score_band: emerging
  score_composite: 19.6
  shared: 3
- slug: rest
  name: REST
  description: REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DEL…
  api_count: 4
  score_band: emerging
  score_composite: 17.8
  shared: 3
- slug: dapperdox
  name: DapperDox
  description: DapperDox is an open-source API documentation generator that creates beautiful, customizable reference documentation from OpenAPI specifications. It supports theming, overlays, and cross-referencing across multiple API specifications, maki…
  api_count: 1
  score_band: emerging
  score_composite: 16.2
  shared: 3
- slug: speclynx
  name: SpecLynx
  description: SpecLynx provides enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx products prioritize securi…
  api_count: 6
  score_band: emerging
  score_composite: 15.2
  shared: 3
---
