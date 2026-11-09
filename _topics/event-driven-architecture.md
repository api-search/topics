---
layout: topic
slug: event-driven-architecture
name: Event-Driven Architecture
kind: concept
description: Event-driven architecture (EDA) is a software architecture pattern promoting the production, detection, consumption of, and reaction to events. In this pattern, systems are designed to respond to state changes asynchronously through event messages. EDA enables loose coupling between services and is widely used in microservices, real-time data processing, and distributed systems. Foundational specifications include AsyncAPI for describing event-driven APIs and CNCF CloudEvents for a common event format.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/event-driven-architecture.png
tags:
- Architecture
- AsyncAPI
- Asynchronous
- CloudEvents
- Distributed Systems
- Event-Driven
- Messaging
- Streaming
area: microservices
repo: https://github.com/api-evangelist/event-driven-architecture
api_count: 0
apis: []
links:
- type: Reference
  url: https://en.wikipedia.org/wiki/Event-driven_architecture
- type: Specification
  url: https://www.asyncapi.com/
- type: Specification
  url: https://cloudevents.io/
- type: Project
  url: https://www.cncf.io/projects/cloudevents/
- type: Project
  url: https://www.cncf.io/projects/knative/
- type: Project
  url: https://www.cncf.io/projects/dapr/
- type: Article
  url: https://martinfowler.com/articles/201701-event-driven.html
provider_count: 35
providers:
- slug: events
  name: Events
  description: Event-driven APIs catalog. Documents the landscape of brokers, streaming platforms, schema registries, and the specifications that standardize how events are described, transported, and stored. "Events" is the broader category that contain…
  api_count: 18
  score_band: thin
  score_composite: 29.3
  shared: 4
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 74.5
  shared: 3
- slug: azure-event-grid
  name: Azure Event Grid
  description: Azure Event Grid is a fully managed event routing service from Microsoft Azure that enables event-driven, reactive programming by ingesting events from Azure services, SaaS providers, and custom sources and delivering them to subscribers s…
  api_count: 1
  score_band: developing
  score_composite: 47.6
  shared: 3
- slug: google-pub-sub
  name: Google Pub/Sub
  description: Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications, providing reliable, many-to-many, asynchronous messaging for event ingestion, streaming ana…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 3
- slug: apache-event-mesh
  name: Apache EventMesh
  description: Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents…
  api_count: 1
  score_band: thin
  score_composite: 32.5
  shared: 3
- slug: spring-cloud-stream
  name: Spring Cloud Stream
  description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persi…
  api_count: 3
  score_band: thin
  score_composite: 30.0
  shared: 3
- slug: synadia-communications
  name: Synadia Communications
  description: Synadia Communications, Inc. is the creator and primary maintainer of NATS.io, the CNCF connectivity and messaging system, and sells the commercial platform built on it. Its products are Synadia Cloud (fully managed, globally distributed N…
  api_count: 2
  score_band: exemplar
  score_composite: 72.1
  shared: 2
- slug: virto-commerce
  name: Virto Commerce
  description: Virto Commerce is an open-source, API-first B2B e-commerce platform built on .NET Core. It provides REST and GraphQL APIs for catalog management, pricing, inventory, order management, customer organizations, marketing, payments, shipping,…
  api_count: 14
  score_band: exemplar
  score_composite: 71.0
  shared: 2
- slug: amazon-eventbridge-pipes
  name: Amazon EventBridge Pipes
  description: Amazon EventBridge Pipes helps you create point-to-point integrations between event producers and consumers with optional transform, filter, and enrich steps. It reduces the amount of integration code you need to write and maintain when bu…
  api_count: 1
  score_band: exemplar
  score_composite: 66.5
  shared: 2
- slug: fastly
  name: Fastly
  description: Fastly is an edge cloud platform that helps customers create great digital experiences quickly, securely, and reliably by processing, serving, and securing their applications closer to their users. The platform spans CDN, Edge Compute (Web…
  api_count: 22
  score_band: strong
  score_composite: 65.3
  shared: 2
- slug: hookdeck
  name: Hookdeck
  description: Hookdeck is a Toronto-based webhook and event-infrastructure platform. The Hookdeck Event Gateway sits between webhook senders and your services to receive, verify, queue, retry, transform, filter, route, and observe events reliably at sca…
  api_count: 1
  score_band: strong
  score_composite: 63.7
  shared: 2
- slug: microsoft-azure-integration-services
  name: Microsoft Azure Integration Services
  description: Microsoft Azure Integration Services is a collection of cloud-based integration capabilities that connect applications, data, and processes across cloud and on-premises environments. It includes API Management, Logic Apps, Service Bus, Eve…
  api_count: 4
  score_band: strong
  score_composite: 63.3
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: cloudflare-queues
  name: Cloudflare Queues
  description: Cloudflare Queues is a flexible, scalable message queue service built into the Cloudflare Workers ecosystem. It provides guaranteed message delivery with a REST API for creating and managing queues, sending individual or batched messages,…
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 2
- slug: apache-kafka
  name: Apache Kafka
  description: Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides a REST Proxy API,…
  api_count: 2
  score_band: developing
  score_composite: 51.3
  shared: 2
- slug: aklivity
  name: Aklivity
  description: Aklivity builds Zilla, a stateless, source-available multi-protocol gateway for event-driven applications and AI agents. Zilla translates HTTP, SSE, WebSocket, MQTT, gRPC and MCP Streamable HTTP to and from Apache Kafka and other backends,…
  api_count: 4
  score_band: developing
  score_composite: 50.2
  shared: 2
- slug: google-cloud-eventarc
  name: Google Cloud Eventarc
  description: Google Cloud Eventarc is a fully managed eventing service that allows you to build event-driven architectures by routing events from Google Cloud services, SaaS applications, and custom sources to target destinations. Eventarc supports bot…
  api_count: 1
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, w…
  api_count: 2
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: google-cloud-tasks
  name: Google Cloud Tasks
  description: Google Cloud Tasks enables you to manage the execution of large numbers of distributed tasks. Cloud Tasks lets you create and dispatch tasks to worker services running on App Engine or any arbitrary HTTP endpoint, with automatic rate limit…
  api_count: 1
  score_band: developing
  score_composite: 48.3
  shared: 2
- slug: asyncapi
  name: AsyncAPI
  description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, valid…
  api_count: 1
  score_band: developing
  score_composite: 46.4
  shared: 2
- slug: google-cloud-pubsub
  name: Google Cloud Pub/Sub
  description: Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications. It provides reliable, many-to-many, asynchronous messaging that decouples senders and recei…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 2
- slug: celery
  name: Celery
  description: Celery is an open-source distributed task queue for Python. It allows you to run tasks asynchronously in the background, enabling scalable distributed systems with support for multiple message brokers (RabbitMQ, Redis, Amazon SQS) and resu…
  api_count: 8
  score_band: thin
  score_composite: 37.6
  shared: 2
- slug: cloudevents
  name: CloudEvents
  description: CloudEvents is a CNCF graduated specification for describing event data in a common way. It provides a consistent format for event metadata across services, platforms, and systems, enabling interoperability between event producers and cons…
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 2
- slug: spring-integration
  name: Spring Integration
  description: Spring Integration extends the Spring programming model to support enterprise integration patterns (EIP), providing lightweight messaging within Spring-based applications and integration with external systems via declarative adapters. It s…
  api_count: 2
  score_band: thin
  score_composite: 33.3
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 2
- slug: apache-bookkeeper
  name: Apache BookKeeper
  description: Apache BookKeeper is a scalable, fault-tolerant, and low-latency storage service optimized for real-time workloads developed by the Apache Software Foundation. It provides a simple log-oriented storage abstraction called ledgers for reliab…
  api_count: 6
  score_band: thin
  score_composite: 32.0
  shared: 2
- slug: apache-pulsar
  name: Apache Pulsar
  description: Apache Pulsar is a cloud-native, distributed messaging and streaming platform that provides server-to-server messaging with multi-tenancy, high performance, and geo-replication. It combines messaging and stream processing in a single platf…
  api_count: 1
  score_band: thin
  score_composite: 30.9
  shared: 2
- slug: rabbitmq
  name: RabbitMQ
  description: RabbitMQ is a widely deployed open source message broker. It supports multiple messaging protocols and can be deployed in distributed and federated configurations to meet high-scale, high-availability requirements.
  api_count: 1
  score_band: thin
  score_composite: 29.8
  shared: 2
- slug: strimzi
  name: Strimzi
  description: Strimzi is a CNCF project providing a Kubernetes-native operator for running Apache Kafka on Kubernetes and OpenShift. It simplifies the deployment, management, scaling, and configuration of Kafka clusters using Kubernetes Custom Resource…
  api_count: 1
  score_band: thin
  score_composite: 27.1
  shared: 2
- slug: apache-rocketmq
  name: Apache RocketMQ
  description: Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance, and reliability. It provides trillion-level message capacity with rich message types including normal, transactional, delayed, and ordere…
  api_count: 1
  score_band: thin
  score_composite: 26.8
  shared: 2
---
