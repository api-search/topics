---
layout: topic
slug: templates
name: Templates
kind: topic
description: A cross-industry subject-matter collection covering API design templates, code templates, documentation templates, API specification templates, and templating engines used in API development and integration workflows. Covers OpenAPI templates, AsyncAPI templates, JSON Schema templates, Postman collection templates, and SDK code generation templates.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/templates.png
tags:
- Templates
- API Design
- Code Generation
- Documentation
- OpenAPI
- AsyncAPI
- Developer Tools
repo: https://github.com/api-evangelist/templates
api_count: 6
apis:
- name: Mustache Templates
  description: Mustache is a logic-less template syntax available for HTML, config files, source code, and more. Used widely for API client SDK generation, documentation generation, and configuration templating.
  url: https://mustache.github.io/
- name: Handlebars.js
  description: Handlebars provides the power necessary to let you build semantic templates effectively with no frustration. Widely used in API documentation generation, email templates, and API portal theming.
  url: https://handlebarsjs.com/
- name: Jinja2
  description: Jinja is a fast, expressive, and extensible templating engine for Python. Used in API code generation (Cookiecutter templates), OpenAPI spec generation, Ansible playbooks, and infrastructure-as-code templates.
  url: https://jinja.palletsprojects.com/
- name: OpenAPI Generator
  description: OpenAPI Generator allows generation of API client libraries (SDK generation), server stubs, documentation and configuration automatically given an OpenAPI Spec. Supports 50+ languages and frameworks via configurable templates.
  url: https://openapi-generator.tech/
- name: Cookiecutter
  description: A command-line utility that creates projects from project templates. Widely used for API project bootstrapping including FastAPI, Flask, Django REST, and microservice templates with standardized structure.
  url: https://cookiecutter.readthedocs.io/
- name: Yeoman
  description: Yeoman is a scaffolding tool for modern webapps and APIs. Generators provide templates for REST APIs, Express apps, OpenAPI-first projects, and full-stack applications following community best practices.
  url: https://yeoman.io/
links:
- type: IssueTracker
  url: https://github.com/mustache/mustache/issues
- type: Releases
  url: https://github.com/mustache/mustache/releases
- type: ContributionGuide
  url: https://github.com/mustache/mustache/blob/master/CONTRIBUTING.md
- type: License
  url: https://github.com/mustache/mustache/blob/master/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/templates/blob/main/security/templates-domain-security.yml
- type: Website
  url: https://mustache.github.io/
- type: GitHubRepository
  url: https://github.com/mustache/mustache
- type: JSONLD
  url: https://github.com/api-evangelist/templates/blob/main/json-ld/templates-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/templates/blob/main/json-schema/templates-template-schema.json
- type: Vocabulary
  url: https://github.com/api-evangelist/templates/blob/main/vocabulary/templates-vocabulary.yml
provider_count: 108
providers:
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: strong
  score_composite: 65.1
  shared: 4
- slug: swaggerhub
  name: SwaggerHub
  description: SwaggerHub is SmartBear's enterprise collaborative API design and documentation platform built around the OpenAPI specification. It provides tools for designing, building, documenting, and consuming RESTful APIs with support for OpenAPI 2.…
  api_count: 2
  score_band: developing
  score_composite: 50.8
  shared: 4
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 43.9
  shared: 4
- slug: openapi-generator
  name: OpenAPI Generator
  description: OpenAPI Generator is a community-governed, Apache-2.0 open-source project that generates client libraries (SDKs), server stubs, API documentation and configuration automatically from an OpenAPI Specification (v2 and v3). Forked from Swagge…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 4
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 4
- slug: api-fiddle
  name: API-Fiddle
  description: API-Fiddle is an interactive, collaborative API design platform for creating professional APIs based on OpenAPI. It provides first-class support for OpenAPI 3.x, data transfer objects, API versioning, suggested response codes, parameter se…
  api_count: 1
  score_band: thin
  score_composite: 32.4
  shared: 4
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 32.2
  shared: 4
- slug: vacuum
  name: Vacuum
  description: Vacuum is the world's fastest and most versatile OpenAPI linter and toolkit, built in Go for validating and linting API specifications at scale. It is 100% compatible with Spectral rulesets and supports OpenAPI 3.0, 3.1, and 3.2.
  api_count: 1
  score_band: emerging
  score_composite: 23.6
  shared: 4
- slug: style-guides
  name: API Style Guides
  description: A landscape index of public API style guides published by leading technology companies and standards bodies. API style guides codify conventions for resource modeling, URI design, HTTP method use, status codes, error formats, pagination, v…
  api_count: 11
  score_band: emerging
  score_composite: 21.4
  shared: 4
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 20.0
  shared: 4
- slug: speclynx
  name: SpecLynx
  description: SpecLynx provides enterprise-ready API tooling for authors and maintainers of OpenAPI, AsyncAPI, and Arazzo specifications. Built by veterans with 15+ years of Swagger and OpenAPI development experience, SpecLynx products prioritize securi…
  api_count: 6
  score_band: emerging
  score_composite: 16.2
  shared: 4
- slug: apimatic
  name: APIMatic
  description: APIMatic is a developer experience platform for APIs that specializes in automated SDK generation, API documentation portal creation, specification validation and linting, and API format transformation. It supports 15+ API specification fo…
  api_count: 1
  score_band: exemplar
  score_composite: 70.0
  shared: 3
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 62.1
  shared: 3
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 52.5
  shared: 3
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: developing
  score_composite: 50.0
  shared: 3
- slug: scalar
  name: Scalar
  description: Scalar is an open-source API platform built around the OpenAPI standard. It provides API documentation (API References), an offline-first API client, a centralized API registry for managing OpenAPI documents, JSON schemas and Spectral rule…
  api_count: 1
  score_band: developing
  score_composite: 48.8
  shared: 3
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 40.5
  shared: 3
- slug: kiota
  name: Kiota
  description: 'Kiota is Microsoft''s open source (MIT) API client generator: a command line tool that turns any OpenAPI-described API into a strongly-typed, lightweight client in C#, Dart, Go, Java, PHP, Python, Ruby or TypeScript. It exists to remove the…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 3
- slug: apicurio
  name: Apicurio
  description: Apicurio is an open source API and schema tooling platform maintained by Red Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance schema and API design registry), Apicurio Studio (a visual API designer for Op…
  api_count: 1
  score_band: thin
  score_composite: 32.9
  shared: 3
- slug: orval
  name: Orval
  description: Orval is an MIT-licensed open source code generator that turns any valid OpenAPI v3 or Swagger v2 specification into type-safe TypeScript. From one spec it emits HTTP request functions (Fetch by default, Axios optional), TanStack Query hoo…
  api_count: 1
  score_band: thin
  score_composite: 31.6
  shared: 3
- slug: oapi-codegen
  name: Oapi-Codegen
  description: oapi-codegen is an open source Go code generator that produces client and server boilerplate from OpenAPI 3.0 and 3.1 specifications with support for Echo, Chi, Gin, Gorilla/Mux, Iris, Fiber, and the standard library net/http router.
  api_count: 1
  score_band: thin
  score_composite: 31.2
  shared: 3
- slug: swagger
  name: Swagger
  description: Swagger is an open-source framework by SmartBear for designing, building, documenting, and consuming RESTful APIs using the OpenAPI Specification. Originally created by Wordnik in 2011, Swagger became the OpenAPI Specification (OAS) in 201…
  api_count: 5
  score_band: thin
  score_composite: 30.1
  shared: 3
- slug: autorest
  name: AutoRest
  description: AutoRest is an open source tool from Microsoft (MIT License) that generates client libraries for accessing RESTful APIs from OpenAPI specifications. It powers generation of Azure SDKs across C#, Python, Java, TypeScript, Go, PowerShell, an…
  api_count: 6
  score_band: thin
  score_composite: 29.0
  shared: 3
- slug: elements
  name: Stoplight Elements
  description: Stoplight Elements is an open-source API documentation component library for rendering OpenAPI specifications interactively. It provides embeddable React and Web Components that produce beautiful, interactive API reference documentation fr…
  api_count: 1
  score_band: thin
  score_composite: 28.9
  shared: 3
- slug: liblab
  name: Liblab
  description: liblab generates and publishes type-safe, idiomatic SDKs in TypeScript, Python, Java, .NET, Go, PHP, and Terraform from OpenAPI/Swagger/Postman specs, plus MCP servers that expose those APIs to AI agents. The platform ships a CLI, hosted p…
  api_count: 4
  score_band: thin
  score_composite: 28.8
  shared: 3
- slug: redoc
  name: ReDoc
  description: ReDoc is an open-source API documentation renderer for OpenAPI specifications by Redocly. It generates a responsive three-panel documentation layout from OpenAPI 3.1, 3.0, and Swagger 2.0 definitions. The left panel provides a search bar a…
  api_count: 1
  score_band: thin
  score_composite: 28.1
  shared: 3
- slug: apigit
  name: APIGit
  description: APIGit is a Git-native platform for full lifecycle API development that combines version control, API design, documentation generation, governance, testing, and dynamic mock servers in a single integrated environment. Teams can build, publ…
  api_count: 4
  score_band: emerging
  score_composite: 26.1
  shared: 3
- slug: openapi-typescript-codegen
  name: OpenAPI TypeScript Codegen
  description: OpenAPI TypeScript Codegen is an MIT-licensed Node.js library and CLI by Ferdi Koomen that reads an OpenAPI 2.0 or 3.0 specification — JSON or YAML, from a path, URL, or string — and generates a lightweight, fully typed TypeScript client.…
  api_count: 1
  score_band: emerging
  score_composite: 24.7
  shared: 3
- slug: nswag
  name: NSwag
  description: 'NSwag is the Swagger/OpenAPI toolchain for .NET, ASP.NET Core and TypeScript, written in C# and maintained by Rico Suter under an MIT licence. It runs the contract in both directions: generating Swagger 2.0 and OpenAPI 3.0 documents from A…'
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 3
- slug: spectral
  name: Spectral
  description: Spectral is an open-source API style guide enforcer and linter from Stoplight, providing a flexible JSON/YAML linting engine with built-in support for OpenAPI (v3.1, v3.0, v2.0), Arazzo v1.0, and AsyncAPI v2.x. Teams use Spectral to define…
  api_count: 1
  score_band: emerging
  score_composite: 23.4
  shared: 3
---
