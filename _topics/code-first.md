---
layout: topic
slug: code-first
name: Code First
kind: topic
description: Code-first is an API design and software development approach where the application's source code is the primary source of truth and the API contract (OpenAPI document, GraphQL schema, gRPC proto, type definitions) is generated from that code via decorators, annotations, type inference, or runtime introspection. It contrasts with the design-first (or contract-first) approach in which a hand-authored OpenAPI/GraphQL/Proto contract is written first and code is scaffolded from it. Code-first approaches are widely used in TypeScript, Python, Java, Go, and C# ecosystems where strong type systems make schema generation reliable.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/code-first.png
tags:
- API Design
- Code Generation
- Code-First
- Decorators
- Development Methodology
- Software Architecture
- Type Safety
repo: https://github.com/api-evangelist/code-first
api_count: 0
apis: []
links:
- type: Reference
  url: https://en.wikipedia.org/wiki/Code_first
- type: Article
  url: https://blog.postman.com/api-first-vs-code-first/
- type: Article
  url: https://blog.stoplight.io/api-design-first-vs-code-first
- type: Article
  url: https://swagger.io/blog/code-first-vs-design-first-api/
- type: Specification
  url: https://spec.openapis.org/
provider_count: 6
providers:
- slug: hey-api
  name: Hey API
  description: Hey API builds open-source OpenAPI code generators and a hosted specification registry. @hey-api/openapi-ts turns an OpenAPI document into production-grade TypeScript — SDKs, types, Zod/Valibot/TypeBox validators, TanStack Query and SWR ho…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 2
- slug: ogen
  name: Ogen
  description: 'Ogen is an Apache-2.0 OpenAPI v3 code generator for Go, maintained by the ogen-go organization. It reads an OpenAPI v3 document at build time and emits a statically typed Go client and server: code-generated JSON encoding with no reflectio…'
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: the-guild-dev
  name: The Guild
  description: The Guild is an open-source software group building much of the GraphQL ecosystem's tooling, published together at the-guild.dev. Its portfolio spans GraphQL Hive (schema registry, usage observability and breaking-change detection), GraphQ…
  api_count: 10
  score_band: thin
  score_composite: 36.7
  shared: 2
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 31.1
  shared: 2
- slug: smithy
  name: Smithy
  description: Smithy is an open source, protocol-agnostic interface definition language (IDL) and toolchain developed at AWS for defining, validating, and generating API clients, servers, and documentation for any programming language. It powers the AWS…
  api_count: 2
  score_band: thin
  score_composite: 26.5
  shared: 2
- slug: design-patterns
  name: Design Patterns
  description: Reusable solutions to commonly occurring problems in software design, including the Gang of Four catalog (creational, structural, behavioral) and core API design patterns such as HATEOAS, idempotency keys, webhooks, and sagas.
  api_count: 1
  score_band: emerging
  score_composite: 12.5
  shared: 2
---
