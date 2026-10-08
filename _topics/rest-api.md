---
layout: topic
slug: rest-api
name: REST API
kind: topic
description: Representational State Transfer (REST) is an architectural style for designing networked applications using standard HTTP methods and stateless communication between client and server. REST APIs define how client and server applications communicate over the web using GET, POST, PUT, DELETE, and PATCH methods against resource-oriented URLs. REST is the dominant API paradigm, used by 89% of organisations as their primary API format. This index covers the REST API landscape including specifications, tools, frameworks, best practices, and educational resources.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/rest-api.png
tags:
- Architecture
- HTTP
- Web Services
- REST
- API Design
- Developer Tools
repo: https://github.com/api-evangelist/rest-api
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/rest-api/blob/main/security/rest-api-domain-security.yml
- type: Website
  url: https://restfulapi.net
- type: Reference
  url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm
- type: Guide
  url: https://www.freecodecamp.org/news/build-consume-and-document-a-rest-api/
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rest-api/refs/heads/main/vocabulary/rest-api-vocabulary.yml
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/rest-api/refs/heads/main/json-ld/rest-api-context.jsonld
provider_count: 56
providers:
- slug: rest
  name: REST
  description: REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DEL…
  api_count: 4
  score_band: emerging
  score_composite: 17.8
  shared: 6
- slug: restful-services
  name: RESTful Services
  description: Representational State Transfer (REST) services are web services built using the REST architectural style, which uses stateless HTTP communication and standard HTTP methods (GET, POST, PUT, DELETE, PATCH) to expose resources. RESTful servi…
  api_count: 5
  score_band: emerging
  score_composite: 16.9
  shared: 4
- slug: aws-api-gateway
  name: Amazon API Gateway
  description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, a…
  api_count: 13
  score_band: exemplar
  score_composite: 70.0
  shared: 3
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 3
- slug: soa
  name: SOA
  description: Service-Oriented Architecture (SOA) is an architectural style for building software applications as a collection of loosely coupled, interoperable services. Each service encapsulates a specific business capability and communicates with oth…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 3
- slug: restful
  name: RESTful
  description: 'Representational State Transfer (REST) is an architectural style for designing networked applications using stateless HTTP communication and uniform interfaces. RESTful describes systems and APIs that conform to the REST constraints: clien…'
  api_count: 5
  score_band: emerging
  score_composite: 14.6
  shared: 3
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 2
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
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
- slug: eraser
  name: Eraser
  description: Eraser is an AI-powered diagramming and technical documentation platform designed for engineering teams. It provides a REST API for generating diagrams from natural language prompts or structured DSL, managing files and workspaces, and emb…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 2
- slug: ruby
  name: Ruby Programming Language and Popular API Gems
  description: 'A profile of the Ruby programming language ecosystem from an API perspective: the language and its standard library HTTP surface (Net::HTTP), the rubygems.org package registry and its public v1/v2 REST API, Bundler, RBS type signatures, po…'
  api_count: 1
  score_band: developing
  score_composite: 40.8
  shared: 2
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 39.6
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
- slug: http-toolkit
  name: HTTP Toolkit
  description: HTTP Toolkit is a beautiful, cross-platform, and open-source tool for debugging, testing, and building with HTTP(S) on Windows, Linux, and Mac. It provides a REST API for intercepting HTTP/HTTPS traffic, inspecting requests and responses,…
  api_count: 4
  score_band: thin
  score_composite: 36.1
  shared: 2
- slug: apache-cxf
  name: Apache CXF
  description: Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first…
  api_count: 1
  score_band: thin
  score_composite: 34.9
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
- slug: httpie
  name: HTTPie
  description: HTTPie is a user-friendly command-line and web-based HTTP client designed for testing, debugging, and interacting with APIs and HTTP services. It provides expressive syntax that mirrors actual HTTP requests, formatted and syntax-highlighte…
  api_count: 1
  score_band: thin
  score_composite: 31.5
  shared: 2
---
