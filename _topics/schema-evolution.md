---
layout: topic
slug: schema-evolution
name: Schema Evolution
kind: topic
description: Schema Evolution is the practice of managing changes to data schemas over time while preserving compatibility between producers and consumers. It covers backward compatibility, forward compatibility, full compatibility, breaking change detection, schema migration strategies, and versioning patterns for REST APIs, event streaming (Kafka/Avro), GraphQL, database schemas, and Protocol Buffers. Effective schema evolution is critical for maintaining API contracts and enabling independent deployment of distributed system components.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/schema-evolution.png
tags:
- Schema Evolution
- Backward Compatibility
- Forward Compatibility
- API Versioning
- Breaking Changes
- Schema Registry
- Data Migration
- Kafka
repo: https://github.com/api-evangelist/schema-evolution
api_count: 9
apis:
- name: AWS Glue Schema Registry API
  description: AWS Glue Schema Registry is a feature that enables you to centrally discover, control, and evolve data stream schemas. The AWS Glue Schema Registry API supports creating, deleting, listing, updating, and fetching schemas, and it supports c…
  url: https://docs.aws.amazon.com/glue/latest/dg/schema-registry.html
- name: Apicurio Schema Registry API
  description: Apicurio Registry is a datastore for standard event schemas and API designs. Apicurio Registry enables you to add, update, and remove artifacts from the registry using a REST API interface. It supports Apache Avro, JSON Schema, Protobuf, G…
  url: https://www.apicur.io/registry/
- name: Schema Evolution Compatibility API
  description: The Compatibility API from Schema Evolution — 2 operation(s) for compatibility.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- name: Schema Evolution Config API
  description: The Config API from Schema Evolution — 2 operation(s) for config.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- name: Schema Evolution Contexts API
  description: The Contexts API from Schema Evolution — 1 operation(s) for contexts.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- name: Schema Evolution Exporters API
  description: The Exporters API from Schema Evolution — 1 operation(s) for exporters.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- name: Schema Evolution Mode API
  description: The Mode API from Schema Evolution — 1 operation(s) for mode.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- name: Schema Evolution Schemas API
  description: The Schemas API from Schema Evolution — 2 operation(s) for schemas.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
- name: Schema Evolution Subjects API
  description: The Subjects API from Schema Evolution — 4 operation(s) for subjects.
  url: https://docs.confluent.io/platform/current/schema-registry/develop/api.html
links:
- type: IssueTracker
  url: https://github.com/Apicurio/apicurio-registry/issues
- type: Releases
  url: https://github.com/Apicurio/apicurio-registry/releases
- type: SecurityPolicy
  url: https://github.com/Apicurio/apicurio-registry/blob/main/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/Apicurio/apicurio-registry/blob/main/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/Apicurio/apicurio-registry/blob/main/CONTRIBUTING.md
- type: License
  url: https://github.com/Apicurio/apicurio-registry/blob/main/LICENSE
- type: AgenticAccess
  url: https://github.com/api-evangelist/schema-evolution/blob/main/agentic-access/schema-evolution-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/schema-evolution/blob/main/security/schema-evolution-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/schema-evolution/blob/main/security/schema-evolution-domain-security.yml
- type: Website
  url: https://docs.confluent.io/platform/current/schema-registry/fundamentals/schema-evolution.html
- type: JSONSchema
  url: https://github.com/api-evangelist/schema-evolution/blob/main/json-schema/schema-evolution-change-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/schema-evolution/blob/main/json-structure/schema-evolution-compatibility-structure.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/schema-evolution/blob/main/json-ld/schema-evolution-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/schema-evolution/blob/main/vocabulary/schema-evolution-vocabulary.yml
provider_count: 2
providers:
- slug: buf
  name: Buf
  description: 'Buf Technologies builds the modern toolchain for Protocol Buffers and gRPC: the buf CLI, the Buf Schema Registry (BSR), Protovalidate, Protobuf-ES and Protobuf-Py, and the Connect protocol, which is now a CNCF project. It replaces protoc-b…'
  api_count: 2
  score_band: strong
  score_composite: 61.4
  shared: 2
- slug: confluent-schema-registry
  name: Confluent Schema Registry
  description: Confluent Schema Registry is the open-source serving layer for schema metadata used in Apache Kafka data pipelines. It exposes a RESTful interface for storing and retrieving Avro, JSON Schema, and Protobuf schemas, manages schema evolution…
  api_count: 1
  score_band: thin
  score_composite: 34.7
  shared: 2
---
