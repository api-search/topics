---
layout: topic
slug: async-apis
name: AsyncAPI
kind: topic
description: 'Topic index for the AsyncAPI ecosystem — the open specification, tooling, and adopter community for describing event-driven and message-driven APIs. AsyncAPI is to asynchronous APIs what OpenAPI is to synchronous REST: a machine-readable contract describing channels, operations, messages, servers, and protocol bindings (Kafka, MQTT, AMQP, WebSocket, NATS, SNS, SQS, JMS, Pulsar, IBM MQ, ROS 2, and more). This repo catalogs the specification versions, the canonical tooling (Studio, Parser, Modelina, Generator, CLI), validators (Spectral, Microcks, Apicurio Registry), code-first frameworks (Springwolf, FastStream, nestjs-asyncapi, AsyncAPI.NET), and real-world adopters (Adeo, HDI Global, TransferGo, Walmart, LEGO, eBay, Salesforce).'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/async-apis.png
tags:
- AsyncAPI
- Event-Driven Architecture
- Asynchronous APIs
- Message Brokers
- API Specification
- Kafka
- MQTT
- AMQP
- WebSocket
- Linux Foundation
repo: https://github.com/api-evangelist/async-apis
api_count: 19
apis:
- name: AsyncAPI Specification
  description: The AsyncAPI Specification is an open-source machine-readable format for describing asynchronous APIs. It defines channels (the addressable message endpoints), operations (send/receive actions an application performs), messages (the payloa…
  url: https://www.asyncapi.com/
- name: AsyncAPI Studio
  description: AsyncAPI Studio is the official browser-based editor for visually designing AsyncAPI documents and event-driven architectures. It provides a real-time preview rendered by the AsyncAPI React component, validation via the AsyncAPI Parser, an…
  url: https://studio.asyncapi.com/
- name: AsyncAPI Parser
  description: The AsyncAPI Parser parses, validates, and provides a programmatic API over AsyncAPI documents. It is the reference implementation used by Studio, the CLI, and the Generator. Available in JavaScript and Go; a shared parser-api defines the…
  url: https://github.com/asyncapi/parser-js
- name: AsyncAPI Modelina
  description: Modelina is the AsyncAPI library for generating typed payload models from AsyncAPI, OpenAPI, JSON Schema, and Avro documents. Supports Java, TypeScript, JavaScript, Go, C#, Rust, Python, Kotlin, Dart, PHP, and C++ output with high customiz…
  url: https://modelina.org/
- name: AsyncAPI Generator
  description: The AsyncAPI Generator takes an AsyncAPI document plus a template and generates anything — markdown docs, HTML, Node.js code, Python code, Java code, AMQP/MQTT/Kafka clients. Template registry includes html-template, markdown-template, nod…
  url: https://github.com/asyncapi/generator
- name: AsyncAPI CLI
  description: The AsyncAPI CLI is the unified command-line interface for the AsyncAPI ecosystem. Commands include `validate`, `generate`, `optimize`, `convert` (2.x to 3.x), `new` (scaffold a spec), `bundle`, and `start studio`.
  url: https://github.com/asyncapi/cli
- name: AsyncAPI React Component
  description: The AsyncAPI React component renders interactive HTML documentation from an AsyncAPI document. Used by Studio, html-template, and the asyncapi-react Storybook playground. Also available as a Web Component.
  url: https://github.com/asyncapi/asyncapi-react
- name: Microcks
  description: Microcks is a Kubernetes-native open-source platform for API mocking and contract testing. First-class support for AsyncAPI — it consumes AsyncAPI documents and stands up mock Kafka, MQTT, AMQP, WebSocket, NATS, SNS, SQS, Google PubSub, an…
  url: https://microcks.io/
- name: Apicurio Registry
  description: Apicurio Registry is an open-source schema and API registry from Red Hat that stores AsyncAPI, OpenAPI, JSON Schema, Avro, Protobuf, GraphQL, and XML Schema artifacts. Integrates with Kafka, Kafka Connect, and Kafka Streams via SerDes libr…
  url: https://www.apicur.io/registry/
- name: Springwolf
  description: Springwolf is the code-first AsyncAPI generator for Spring Boot applications. It auto-detects @KafkaListener, @RabbitListener, @JmsListener, @SqsListener, @SnsListener, and Cloud Stream bindings and produces an AsyncAPI document plus an in…
  url: https://www.springwolf.dev/
- name: FastStream
  description: FastStream is a Python framework that auto-generates AsyncAPI documentation from typed message handlers for Kafka, RabbitMQ, NATS, Redis Pub/Sub, and Confluent Kafka. Created by airtai and donated to the AsyncAPI community.
  url: https://faststream.airt.ai/
- name: Glee
  description: Glee is the AsyncAPI-native application framework. It takes an AsyncAPI document as input and scaffolds a working server (Node.js) that handles the channels, validates messages against the schema, and routes them to user-supplied handler f…
  url: https://github.com/asyncapi/glee
- name: AsyncAPI Bundle API
  description: The Bundle API from AsyncAPI — 1 operation(s) for bundle.
  url: https://www.asyncapi.com/
- name: AsyncAPI Convert API
  description: The Convert API from AsyncAPI — 1 operation(s) for convert.
  url: https://www.asyncapi.com/
- name: AsyncAPI Diff API
  description: The Diff API from AsyncAPI — 1 operation(s) for diff.
  url: https://www.asyncapi.com/
- name: AsyncAPI Generate API
  description: The Generate API from AsyncAPI — 1 operation(s) for generate.
  url: https://www.asyncapi.com/
- name: AsyncAPI Help API
  description: The Help API from AsyncAPI — 1 operation(s) for help.
  url: https://www.asyncapi.com/
- name: AsyncAPI Parse API
  description: The Parse API from AsyncAPI — 1 operation(s) for parse.
  url: https://www.asyncapi.com/
- name: AsyncAPI Validate API
  description: The Validate API from AsyncAPI — 1 operation(s) for validate.
  url: https://www.asyncapi.com/
links:
- type: Website
  url: https://asyncapi.com
- type: AgenticAccess
  url: https://github.com/api-evangelist/async-apis/blob/main/agentic-access/async-apis-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/async-apis/blob/main/security/async-apis-domain-security.yml
- type: TopicIndex
  url: https://github.com/api-evangelist/async-apis
- type: JSONSchema
  url: https://github.com/api-evangelist/async-apis/blob/main/json-schema/asyncapi-document-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/async-apis/blob/main/json-schema/asyncapi-channel-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/async-apis/blob/main/json-schema/asyncapi-operation-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/async-apis/blob/main/json-schema/asyncapi-message-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/async-apis/blob/main/json-schema/asyncapi-server-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/async-apis/blob/main/json-ld/async-apis-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/async-apis/blob/main/vocabulary/async-apis-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/async-apis/blob/main/examples/asyncapi-kafka-example.yml
- type: Examples
  url: https://github.com/api-evangelist/async-apis/blob/main/examples/asyncapi-mqtt-example.yml
- type: Examples
  url: https://github.com/api-evangelist/async-apis/blob/main/examples/asyncapi-websocket-example.yml
- type: Specification
  url: https://www.asyncapi.com/docs/reference/specification/latest
- type: SpecificationRepo
  url: https://github.com/asyncapi/spec
- type: GitHubOrganization
  url: https://github.com/asyncapi
- type: Governance
  url: https://github.com/asyncapi/community
- type: LinuxFoundationProject
  url: https://www.linuxfoundation.org/projects
provider_count: 4
providers:
- slug: gravitee
  name: Gravitee
  description: Gravitee.io is an open-source API management platform from GraviteeSource, combining a high-performance API Gateway, full-lifecycle API Management, Access Management (IAM), Cockpit (multi-environment control plane), an Alert Engine, a Kube…
  api_count: 2
  score_band: strong
  score_composite: 61.5
  shared: 2
- slug: hivemq
  name: HiveMQ
  description: HiveMQ is an enterprise MQTT broker and IoT connectivity platform that provides reliable, scalable bidirectional messaging between connected devices and back-end systems using the MQTT protocol. It supports MQTT 3, MQTT 5, MQTT over WebSoc…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 2
- slug: apache-activemq
  name: Apache ActiveMQ
  description: Apache ActiveMQ is an open-source, high-performance message broker written in Java, developed by the Apache Software Foundation. It implements the Jakarta Messaging (JMS) API and supports multiple messaging protocols including AMQP, STOMP,…
  api_count: 4
  score_band: thin
  score_composite: 35.5
  shared: 2
- slug: messaging-protocol
  name: Messaging Protocol
  description: Messaging Protocol is a networking technology or protocol that facilitates communication, data transfer, or traffic management between systems and devices. Examples include AMQP, MQTT, STOMP, and other protocols that enable reliable, effic…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
---
