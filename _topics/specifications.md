---
layout: topic
slug: specifications
name: API Specifications
kind: topic
description: Meta-index of the specification languages used to describe APIs, events, schemas, and service interfaces across the modern API landscape. This repo is the META layer above the topical repos that profile each individual specification — it catalogs every major HTTP, event-driven, schema, and service interface specification along with its current version, governing body, license, and tooling ecosystem.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/specifications.png
tags:
- API Specification
- Specification Languages
- API Design
- Contracts
- Schema
- Interface Definitions
- Standards
repo: https://github.com/api-evangelist/specifications
api_count: 13
apis:
- name: OpenAPI Specification (OAS)
  description: The OpenAPI Specification (formerly Swagger) is the dominant industry standard for describing HTTP-based RESTful APIs. OAS describes endpoints, operations, parameters, request/response schemas, authentication, and examples in a machine- an…
  url: https://www.openapis.org/
- name: AsyncAPI Specification
  description: AsyncAPI is the open standard for describing event-driven and message-driven APIs across protocols such as Kafka, AMQP, MQTT, WebSocket, NATS, and SNS/SQS. AsyncAPI 3.0 (December 2023) decoupled operations from channels, enabling clearer m…
  url: https://www.asyncapi.com/
- name: JSON Schema
  description: JSON Schema is a declarative language for annotating and validating JSON documents. It is the foundational schema language for most modern API specifications (OpenAPI 3.1, AsyncAPI 3, and others embed it directly). The current stable diale…
  url: https://json-schema.org/
- name: JSON Structure
  description: JSON Structure is an emerging open specification that extends and complements JSON Schema with a clearer, more code-generation-friendly type system designed for data contracts and modeling. It introduces structural primitives intended for…
  url: https://json-structure.org/
- name: GraphQL SDL
  description: GraphQL is a query language and runtime for APIs, defined by the GraphQL Specification. The GraphQL Schema Definition Language (SDL) is the declarative format used to define types, queries, mutations, and subscriptions on a GraphQL server.…
  url: https://graphql.org/
- name: gRPC and Protocol Buffers
  description: gRPC is a high-performance RPC framework using HTTP/2 and Protocol Buffers (Protobuf) as its IDL and wire format. Service definitions are written in .proto files. gRPC is a CNCF graduated project; Protocol Buffers (proto2/proto3, with prot…
  url: https://grpc.io/
- name: Smithy
  description: Smithy is an open-source IDL and code-generation framework for defining services and SDKs, created and maintained by AWS. It is protocol-agnostic (HTTP REST, AWS JSON, MQTT, RPC), supports traits-based modeling, and is used to generate AWS…
  url: https://smithy.io/
- name: TypeSpec
  description: TypeSpec (formerly Cadl) is a language for describing API shapes developed by Microsoft. TypeSpec definitions emit OpenAPI 3.x, JSON Schema, Protobuf, and other artifacts, and serve as the upstream source for Azure SDK generation. TypeSpec…
  url: https://typespec.io/
- name: RAML (RESTful API Modeling Language)
  description: RAML is a YAML-based modelling language for RESTful APIs, originally created by Mulesoft. RAML 1.0 (2016) is the current stable specification. RAML governance has effectively converged with Mulesoft / Salesforce, and the broader industry h…
  url: https://raml.org/
- name: API Blueprint
  description: API Blueprint is a Markdown-based specification language for describing web APIs, originally created by Apiary (acquired by Oracle). The spec is MIT licensed but development effectively stalled after Oracle's acquisition of Apiary; it is d…
  url: https://apiblueprint.org/
- name: WSDL / SOAP
  description: The Web Services Description Language (WSDL) is the historical XML-based interface definition language for SOAP web services. WSDL 1.1 (2001) is the most widely deployed version; WSDL 2.0 is a W3C Recommendation (2007). SOAP and WSDL are g…
  url: https://www.w3.org/TR/wsdl/
- name: JSON-RPC 2.0
  description: JSON-RPC 2.0 is a stateless, light-weight remote procedure call (RPC) protocol encoded in JSON. It is widely used in blockchain/Web3 APIs (Ethereum, Bitcoin), IDE language servers (LSP), and developer tooling. The 2.0 specification (2010)…
  url: https://www.jsonrpc.org/
- name: Tinybird API Spec
  description: The Tinybird API specification is a vendor-defined, declarative format for describing analytics endpoints (pipes), data sources, and parameters backed by ClickHouse. It is documented here as a representative example of vendor-specific spec…
  url: https://www.tinybird.co/docs
links:
- type: IssueTracker
  url: https://github.com/OAI/OpenAPI-Specification/issues
- type: Releases
  url: https://github.com/OAI/OpenAPI-Specification/releases
- type: CodeOfConduct
  url: https://github.com/OAI/.github/blob/main/.github/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/OAI/OpenAPI-Specification/blob/main/CONTRIBUTING.md
- type: DomainSecurity
  url: https://github.com/api-evangelist/specifications/blob/main/security/specifications-domain-security.yml
- type: Website
  url: https://github.com/api-evangelist/specifications
- type: GitHubRepository
  url: https://github.com/api-evangelist/specifications
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/specifications/refs/heads/main/json-schema/specification-record-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/specifications/refs/heads/main/json-structure/specification-record-structure.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/specifications/refs/heads/main/json-ld/specifications-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/specifications/refs/heads/main/vocabulary/specifications-vocabulary.yml
- type: GitHubOrganization
  url: https://github.com/OAI
- type: GitHubOrganization
  url: https://github.com/asyncapi
- type: GitHubOrganization
  url: https://github.com/json-schema-org
- type: GitHubOrganization
  url: https://github.com/json-structure
- type: GitHubOrganization
  url: https://github.com/graphql
- type: GitHubOrganization
  url: https://github.com/grpc
- type: GitHubOrganization
  url: https://github.com/protocolbuffers
- type: GitHubOrganization
  url: https://github.com/smithy-lang
- type: GitHubOrganization
  url: https://github.com/microsoft
- type: GitHubOrganization
  url: https://github.com/raml-org
provider_count: 1
providers:
- slug: apigovernance-dev
  name: APIGovernance.Dev
  description: APIGovernance.Dev is an AI-powered API governance platform that enforces API best practices through automated reviews trained on 10,000 public APIs. It provides the API Governance Top-10 list of best practices, automated CI/CD integration,…
  api_count: 1
  score_band: emerging
  score_composite: 25.7
  shared: 2
---
