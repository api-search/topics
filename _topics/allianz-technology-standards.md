---
layout: topic
slug: allianz-technology-standards
name: Allianz Technology Standards
kind: topic
description: A collection of technology standards and guidelines maintained by Allianz for software development, API design, architecture, and engineering practices. Allianz follows API-first development using OpenAPI specifications, Backend for Frontends (BFF) architecture, and standardized patterns for pagination, sorting, webhooks, and asynchronous processing.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/allianz-technology-standards.png
tags:
- Best Practices
- Enterprise Architecture
- Guidelines
- Software Development
- Technology Standards
- API Design
- OpenAPI
repo: https://github.com/api-evangelist/allianz-technology-standards
api_count: 5
apis:
- name: Allianz Trade API Design Standards
  description: Allianz Trade API design guidelines covering REST API conventions, pagination standards (pageSize, page, totalRequired), sorting conventions, asynchronous processing with JobID management, webhook notification patterns, and security requir…
  url: https://developers.allianz-trade.com/docs/api-design-guidelines
- name: Allianz Backend Development Standards
  description: Allianz Global Digital Factory backend development standards. Uses Java and Kotlin with Spring Boot for microservices, API-first approach with OpenAPI specifications, Backend for Frontends (BFF) architecture, and comprehensive automated te…
  url: https://globaldigitalfactory.allianz.com/blog/finally-talking-about-backend-.html
- name: Allianz Technology Standards Compliance API
  description: API compliance checking against Allianz standards
  url: https://developers.allianz-trade.com/docs/api-design-guidelines
- name: Allianz Technology Standards Guidelines API
  description: Specific guideline rules for API design areas
  url: https://developers.allianz-trade.com/docs/api-design-guidelines
- name: Allianz Technology Standards API
  description: Technology standard definitions and retrieval
  url: https://developers.allianz-trade.com/docs/api-design-guidelines
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/agentic-access/allianz-technology-standards-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/security/allianz-technology-standards-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/security/allianz-technology-standards-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/authentication/allianz-technology-standards-authentication.yml
- type: OAuthScopes
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/scopes/allianz-technology-standards-scopes.yml
- type: GitHubOrganization
  url: https://github.com/Allianz
- type: Website
  url: https://www.allianz.com/
- type: Blog
  url: https://globaldigitalfactory.allianz.com/
- type: SpectralRules
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/rules/allianz-technology-standards-spectral-rules.yml
- type: Vocabulary
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/vocabulary/allianz-technology-standards-vocabulary.yaml
- type: Packages
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/packages/allianz-technology-standards-packages.yml
- type: WellKnown
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/well-known/allianz-technology-standards-well-known.yml
- type: MCPServer
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/mcp/allianz-technology-standards-mcp.yml
- type: LLMsTxt
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/llms/allianz-technology-standards-llms.txt
- type: Conformance
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/conformance/allianz-technology-standards-conformance.yml
- type: ErrorCatalog
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/errors/allianz-technology-standards-problem-types.yml
- type: Lifecycle
  url: https://github.com/api-evangelist/allianz-technology-standards/blob/main/lifecycle/allianz-technology-standards-lifecycle.yml
provider_count: 24
providers:
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration,…
  api_count: 1
  score_band: thin
  score_composite: 27.2
  shared: 3
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
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 62.1
  shared: 2
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.8
  shared: 2
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 43.9
  shared: 2
- slug: zally
  name: Zally
  description: Zally is an open source API linter from Zalando that validates OpenAPI 2 and 3 specifications against configurable rule sets for API design consistency. It exposes a REST API, command-line interface, and web UI for checking API designs aga…
  api_count: 1
  score_band: developing
  score_composite: 43.4
  shared: 2
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 2
- slug: apicurio
  name: Apicurio
  description: Apicurio is an open source API and schema tooling platform maintained by Red Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance schema and API design registry), Apicurio Studio (a visual API designer for Op…
  api_count: 1
  score_band: thin
  score_composite: 32.9
  shared: 2
- slug: api-fiddle
  name: API-Fiddle
  description: API-Fiddle is an interactive, collaborative API design platform for creating professional APIs based on OpenAPI. It provides first-class support for OpenAPI 3.x, data transfer objects, API versioning, suggested response codes, parameter se…
  api_count: 1
  score_band: thin
  score_composite: 32.4
  shared: 2
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: swagger
  name: Swagger
  description: Swagger is an open-source framework by SmartBear for designing, building, documenting, and consuming RESTful APIs using the OpenAPI Specification. Originally created by Wordnik in 2011, Swagger became the OpenAPI Specification (OAS) in 201…
  api_count: 5
  score_band: thin
  score_composite: 30.1
  shared: 2
- slug: vacuum
  name: Vacuum
  description: Vacuum is the world's fastest and most versatile OpenAPI linter and toolkit, built in Go for validating and linting API specifications at scale. It is 100% compatible with Spectral rulesets and supports OpenAPI 3.0, 3.1, and 3.2.
  api_count: 1
  score_band: emerging
  score_composite: 23.6
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
- slug: versioning-protocols
  name: Versioning Protocols
  description: Standards and methodologies for managing changes and updates to APIs, software interfaces, and data formats while maintaining backward compatibility and clear communication of breaking changes. Covers Semantic Versioning (SemVer), Calendar…
  api_count: 5
  score_band: emerging
  score_composite: 20.2
  shared: 2
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 20.0
  shared: 2
- slug: connexion
  name: Connexion
  description: Connexion is an open source Python framework that automatically handles HTTP requests based on OpenAPI specifications. Connexion 3 provides AsyncApp, FlaskApp, and ConnexionMiddleware as primary entry points, with built-in routing, request…
  api_count: 2
  score_band: emerging
  score_composite: 17.2
  shared: 2
- slug: speclynx
  name: SpecLynx
  description: SpecLynx provides enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx products prioritize securi…
  api_count: 6
  score_band: emerging
  score_composite: 16.2
  shared: 2
- slug: design-patterns
  name: Design Patterns
  description: Reusable solutions to commonly occurring problems in software design, including the Gang of Four catalog (creational, structural, behavioral) and core API design patterns such as HATEOAS, idempotency keys, webhooks, and sagas.
  api_count: 1
  score_band: emerging
  score_composite: 14.4
  shared: 2
- slug: api-insights
  name: API Insights
  description: API Insights is a free online tool powered by Treblle that provides advanced API analysis and monitoring by evaluating OpenAPI specifications across multiple dimensions including AI readiness, design quality, performance, and security. It…
  api_count: 1
  score_band: emerging
  score_composite: 13.0
  shared: 2
- slug: jargon
  name: Jargon
  description: Jargon is a platform for Domain Driven Design for APIs and Enterprise Data Modelling. It provides text-based modelling, template-based API design, real-time validation, version control with breaking change detection, and generation of arti…
  api_count: 1
  score_band: emerging
  score_composite: 12.8
  shared: 2
- slug: secure-by-design
  name: Secure-By-Design
  description: A software development approach that prioritizes security from the initial design phase through implementation, ensuring security considerations are built into the foundation of systems rather than added as an afterthought. It is widely ad…
  api_count: 0
  score_band: minimal
  score_composite: 5.5
  shared: 2
- slug: security-by-design
  name: Security by Design
  description: A software development approach that integrates security considerations and practices from the initial design phase through the entire development lifecycle, rather than adding security as an afterthought. It plays a critical role in prote…
  api_count: 0
  score_band: minimal
  score_composite: 4.3
  shared: 2
---
