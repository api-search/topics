---
layout: topic
slug: test-rate-limit-check
name: Test Rate Limit Check
kind: topic
description: Testing and validation of API rate limiting implementations to ensure that APIs correctly enforce request quotas, return appropriate error responses, and recover gracefully when limits are exceeded. Rate limit testing verifies throttling behavior, retry-after headers, burst allowances, and quota reset mechanisms across different API consumers and usage tiers.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-rate-limit-check.png
tags:
- API Governance
- API Management
- API Testing
- Developer Tools
- Performance Testing
- Rate Limiting
- Testing
repo: https://github.com/api-evangelist/test-rate-limit-check
api_count: 9
apis:
- name: AWS API Gateway API
  description: AWS REST API for managing API Gateway usage plans, API keys, throttling limits, and quota enforcement across API deployments.
  url: https://docs.aws.amazon.com/apigateway/latest/developerguide/api-ref.html
- name: Apigee API
  description: REST API for Google Apigee API management platform supporting rate limit policy configuration, quota management, spike arrest, and traffic shaping for API testing.
  url: https://cloud.google.com/apigee/docs/reference/apis/apigee/rest
- name: Azure API Management API
  description: REST API for Azure API Management service supporting subscription quotas, rate limit policies, and throttling configuration for testing rate limit implementations.
  url: https://learn.microsoft.com/en-us/rest/api/apimanagement/
- name: Test Rate Limit Check Consumers API
  description: The Consumers API from Test Rate Limit Check — 1 operation(s) for consumers.
  url: https://docs.konghq.com/gateway/latest/admin-api/
- name: Test Rate Limit Check Plugins API
  description: The Plugins API from Test Rate Limit Check — 1 operation(s) for plugins.
  url: https://docs.konghq.com/gateway/latest/admin-api/
- name: Test Rate Limit Check Routes API
  description: The Routes API from Test Rate Limit Check — 1 operation(s) for routes.
  url: https://docs.konghq.com/gateway/latest/admin-api/
- name: Test Rate Limit Check Schemas API
  description: The Schemas API from Test Rate Limit Check — 1 operation(s) for schemas.
  url: https://docs.konghq.com/gateway/latest/admin-api/
- name: Test Rate Limit Check Services API
  description: The Services API from Test Rate Limit Check — 1 operation(s) for services.
  url: https://docs.konghq.com/gateway/latest/admin-api/
- name: Test Rate Limit Check Status API
  description: The Status API from Test Rate Limit Check — 1 operation(s) for status.
  url: https://docs.konghq.com/gateway/latest/admin-api/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/agentic-access/test-rate-limit-check-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/security/test-rate-limit-check-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/authentication/test-rate-limit-check-authentication.yml
- type: Documentation
  url: https://en.wikipedia.org/wiki/Rate_limiting
- type: Documentation
  url: https://www.rfc-editor.org/rfc/rfc6585#section-4
- type: JSONSchema
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/json-schema/test-rate-limit-check-rate-limit-config-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/json-schema/test-rate-limit-check-rate-limit-response-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/json-schema/test-rate-limit-check-quota-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/json-ld/test-rate-limit-check-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/test-rate-limit-check/blob/main/vocabulary/test-rate-limit-check-vocabulary.yml
provider_count: 105
providers:
- slug: elva
  name: Elva
  description: 'API management platform for the agentic era: reads repos to build an API catalog, enforces per-audience contracts, generates tests, and turns APIs into governed, hosted MCP servers for AI agents. Built by Theneo. Exposes a public no-auth O…'
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 4
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: zuplo
  name: Zuplo
  description: Zuplo is the API management platform for developers. Build, deploy, and scale APIs faster with Zuplo.
  api_count: 1
  score_band: strong
  score_composite: 62.3
  shared: 3
- slug: smartbear
  name: SmartBear
  description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI fo…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 3
- slug: keploy
  name: Keploy
  description: Open-source, AI-native testing platform that captures real production API traffic with eBPF and replays it in CI as deterministic tests, auto-generated mocks, and production-like sandboxes with zero code changes. Publishes a first-party Op…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 3
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 3
- slug: bruno-api
  name: Bruno
  description: Bruno is an open-source (MIT), git-native API client - a lightweight, offline-first alternative to Postman and Insomnia for exploring and testing APIs. It is a developer TOOL, not a hosted HTTP API provider. Collections are stored on the l…
  api_count: 6
  score_band: developing
  score_composite: 51.9
  shared: 3
- slug: lunar
  name: Lunar
  description: Lunar is an enterprise-grade API management and AI control plane platform that provides a unified gateway for managing API traffic policies, rate limiting, quota enforcement, and API monetization across gateways. The platform combines an A…
  api_count: 3
  score_band: developing
  score_composite: 50.7
  shared: 3
- slug: assertible
  name: Assertible
  description: Assertible provides a reliable first line of defense against web service failures by providing simple and powerful assertions to test and monitor APIs. It enables automated API testing with assertions on response status, headers, body cont…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 3
- slug: apitoolkit
  name: APIToolkit (Monoscope)
  description: APIToolkit (now Monoscope) is an open-source-friendly API observability and monitoring platform that helps teams find and fix production issues before customers notice. It unifies logs, traces, metrics, errors, monitors, and session replay…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 3
- slug: rapidapi
  name: RapidAPI
  description: RapidAPI operates the world's largest API marketplace, connecting developers to thousands of APIs through a single platform. Their developer platform provides tools for API discovery, testing, management, design, and gateway configuration,…
  api_count: 6
  score_band: developing
  score_composite: 41.7
  shared: 3
- slug: reqkey
  name: ReqKey
  description: 'ReqKey is out-of-band API key authentication, usage credits, rate limiting and request analytics as a service for teams that sell or expose an API. It never sits in front of customer traffic: your own middleware makes one call to POST /key…'
  api_count: 1
  score_band: developing
  score_composite: 40.7
  shared: 3
- slug: testim-io
  name: Testim
  description: Testim is an AI-powered functional test automation platform for web and mobile applications, using machine learning to author, run, and self-heal UI tests. Acquired by Tricentis in 2022, Testim is offered as part of the Tricentis quality-e…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 3
- slug: speedscale
  name: Speedscale
  description: Speedscale is an API traffic replay and performance testing platform that captures production API traffic and replays it in test environments for load testing, regression testing, and validation of AI-generated code. It enables teams to si…
  api_count: 1
  score_band: thin
  score_composite: 32.1
  shared: 3
- slug: scalability-testing
  name: Scalability Testing
  description: A collection of tools, frameworks, APIs, and datasets for performing scalability and load testing of web services, APIs, and distributed systems. Scalability testing evaluates how a system performs as load increases, identifying bottleneck…
  api_count: 1
  score_band: thin
  score_composite: 31.2
  shared: 3
- slug: rest-assured
  name: REST Assured
  description: REST Assured is a Java library for simplifying the testing and validation of RESTful APIs. It provides a fluent domain-specific language (DSL) built on the given-when-then BDD pattern, making it easy to write readable and maintainable API…
  api_count: 1
  score_band: thin
  score_composite: 28.9
  shared: 3
- slug: apiwiz
  name: APIwiz
  description: APIwiz is a federated API management platform that streamlines the complete API lifecycle from design through monetization. The low-code platform provides centralized control for organizations managing APIs across multiple cloud environmen…
  api_count: 1
  score_band: emerging
  score_composite: 26.1
  shared: 3
- slug: stellate
  name: Stellate
  description: Stellate is a GraphQL edge caching and API management platform that caches GraphQL query results at 60 data centers worldwide, reducing origin traffic by up to 95% and delivering responses in milliseconds. The platform provides edge cachin…
  api_count: 1
  score_band: emerging
  score_composite: 23.0
  shared: 3
- slug: api-stack
  name: API Stack
  description: API Stack is a free, public directory and discovery platform for third-party API tooling, built and operated by Apideck B.V. as a tenant of its own Apideck Ecosystem marketplace platform. It catalogs 213 API tools and services across 46 pu…
  api_count: 1
  score_band: emerging
  score_composite: 14.1
  shared: 3
- slug: muuktest
  name: Muuktest
  description: MuukTest (MuukLabs) is an AI-powered test automation and managed QA services company founded in 2019 that helps software teams reach high end-to-end test coverage in weeks rather than months. It blends an AI-driven automation platform with…
  api_count: 0
  score_band: emerging
  score_composite: 12.1
  shared: 3
- slug: readyapi
  name: ReadyAPI
  description: ReadyAPI is SmartBear's enterprise-grade automated API testing platform. It unifies functional, security, performance, and virtualization testing for REST, SOAP, GraphQL, Kafka, JDBC, and JMS APIs. ReadyAPI is delivered as a desktop and CI…
  api_count: 0
  score_band: emerging
  score_composite: 11.9
  shared: 3
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 2
- slug: apigee
  name: Apigee
  description: Apigee is Google Cloud's native API management platform for building, managing, and securing APIs across any use case, environment, or scale. It provides API proxies, security, rate limiting, quotas, analytics, monetization, and developer…
  api_count: 5
  score_band: exemplar
  score_composite: 70.8
  shared: 2
- slug: tricentis
  name: Tricentis
  description: Tricentis is an enterprise continuous testing and quality engineering company, founded in Austria in 2007 and headquartered in Vienna with US operations in Austin, Texas. Its platform spans model-based UI and API test automation (Tosca, To…
  api_count: 8
  score_band: exemplar
  score_composite: 68.0
  shared: 2
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 2
- slug: tempmailgrab
  name: TempMailGrab API
  description: Privacy-first disposable/temporary email service with private 24-hour inboxes, real-time WebSocket delivery, automatic OTP and verification-link extraction, attachments, webhooks, custom domains, and a versioned REST API for QA, test autom…
  api_count: 2
  score_band: strong
  score_composite: 62.4
  shared: 2
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: artillery
  name: Artillery
  description: Artillery is an open source load testing and performance testing platform for APIs, microservices, and web applications. Built with Node.js and available as an npm package, Artillery supports HTTP/1, HTTP/2, WebSocket, Socket.IO, gRPC, and…
  api_count: 1
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: gradle
  name: Gradle
  description: Gradle Inc. (Gradle Technologies) is the company behind the open-source Gradle Build Tool, downloaded more than 25 million times a month across the Java, JVM, Android, Kotlin, C/C++, and native ecosystems, and Develocity (formerly Gradle E…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: signadot
  name: Signadot
  description: 'Signadot is a Kubernetes-native platform for validating microservices and AI-generated code changes against real dependencies before merge. Its core is environment virtualization: large numbers of lightweight ephemeral "sandboxes" spin up…'
  api_count: 1
  score_band: strong
  score_composite: 55.6
  shared: 2
---
