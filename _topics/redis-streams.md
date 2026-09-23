---
layout: topic
slug: redis-streams
name: Redis Streams
kind: topic
description: Redis Streams is a data structure in Redis that models an append-only log for managing streams of data, providing consumer groups, message acknowledgment, and the ability to process data in real time with high throughput and low latency.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/redis-streams.png
tags:
- Consumer Groups
- Event-Driven
- In-Memory
- Messaging
- Redis
- Streaming
repo: https://github.com/api-evangelist/redis-streams
api_count: 1
apis:
- name: Redis Streams
  description: Redis Streams is a Redis data structure that acts as an append-only log, supporting consumer groups, range queries, and message acknowledgment for building event-driven architectures and real-time data processing pipelines.
  url: https://redis.io/docs/latest/develop/data-types/streams/
links:
- type: TrustCenter
  url: https://github.com/api-evangelist/redis-streams/blob/main/security/redis-streams-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/redis-streams/blob/main/security/redis-streams-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/redis-streams/blob/main/security/redis-streams-domain-security.yml
- type: Website
  url: https://redis.io/
- type: Documentation
  url: https://redis.io/docs/latest/develop/data-types/streams/
- type: GettingStarted
  url: https://redis.io/docs/latest/get-started/
- type: GitHub
  url: https://github.com/redis/redis
- type: Blog
  url: https://redis.io/blog/
- type: Community
  url: https://redis.io/community/
- type: Commands Reference
  url: https://redis.io/docs/latest/commands/?group=stream
- type: Tutorial
  url: https://redis.io/docs/latest/develop/data-types/streams-tutorial/
- type: Integrations
  url: https://redis.io/partners/
- type: LlmsText
  url: https://redis.io/llms.txt
provider_count: 29
providers:
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 80.4
  shared: 3
- slug: google-pub-sub
  name: Google Pub/Sub
  description: Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications, providing reliable, many-to-many, asynchronous messaging for event ingestion, streaming ana…
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 3
- slug: kafka
  name: Apache Kafka
  description: Apache Kafka is a distributed event streaming platform for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides high-throughput, fault-tolerant, publish-subscribe messaging.
  api_count: 5
  score_band: thin
  score_composite: 29.3
  shared: 3
- slug: event-driven-architecture
  name: Event-Driven Architecture
  description: Event-driven architecture (EDA) is a software architecture pattern promoting the production, detection, consumption of, and reaction to events. In this pattern, systems are designed to respond to state changes asynchronously through event…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 3
- slug: hookdeck
  name: Hookdeck
  description: Hookdeck is a Toronto-based webhook and event-infrastructure platform. The Hookdeck Event Gateway sits between webhook senders and your services to receive, verify, queue, retry, transform, filter, route, and observe events reliably at sca…
  api_count: 1
  score_band: strong
  score_composite: 61.5
  shared: 2
- slug: amazon-eventbridge-pipes
  name: Amazon EventBridge Pipes
  description: Amazon EventBridge Pipes helps you create point-to-point integrations between event producers and consumers with optional transform, filter, and enrich steps. It reduces the amount of integration code you need to write and maintain when bu…
  api_count: 1
  score_band: strong
  score_composite: 60.9
  shared: 2
- slug: amazon-elasticache
  name: Amazon ElastiCache
  description: Amazon ElastiCache is a fully managed in-memory caching service supporting Redis and Memcached. ElastiCache makes it easy to deploy, operate, and scale popular open-source compatible in-memory data stores, improving the performance of web…
  api_count: 1
  score_band: strong
  score_composite: 58.1
  shared: 2
- slug: cloudflare-queues
  name: Cloudflare Queues
  description: Cloudflare Queues is a flexible, scalable message queue service built into the Cloudflare Workers ecosystem. It provides guaranteed message delivery with a REST API for creating and managing queues, sending individual or batched messages,…
  api_count: 1
  score_band: strong
  score_composite: 56.2
  shared: 2
- slug: microsoft-azure-integration-services
  name: Microsoft Azure Integration Services
  description: Microsoft Azure Integration Services is a collection of cloud-based integration capabilities that connect applications, data, and processes across cloud and on-premises environments. It includes API Management, Logic Apps, Service Bus, Eve…
  api_count: 6
  score_band: developing
  score_composite: 48.7
  shared: 2
- slug: asyncapi
  name: AsyncAPI
  description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, valid…
  api_count: 1
  score_band: developing
  score_composite: 44.8
  shared: 2
- slug: google-cloud-eventarc
  name: Google Cloud Eventarc
  description: Google Cloud Eventarc is a fully managed eventing service that allows you to build event-driven architectures by routing events from Google Cloud services, SaaS applications, and custom sources to target destinations. Eventarc supports bot…
  api_count: 1
  score_band: developing
  score_composite: 43.9
  shared: 2
- slug: google-cloud-memorystore
  name: Google Cloud Memorystore
  description: Google Cloud Memorystore is a fully managed in-memory data store service for Redis and Memcached. It provides a scalable, secure, and highly available caching layer that helps accelerate application performance. Memorystore automates compl…
  api_count: 1
  score_band: developing
  score_composite: 43.6
  shared: 2
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, w…
  api_count: 2
  score_band: developing
  score_composite: 43.1
  shared: 2
- slug: redis
  name: Redis
  description: Redis is an open source, in-memory data structure store used as a database, cache, message broker, and streaming engine. It supports strings, hashes, lists, sets, sorted sets, streams, JSON, and more. Redis is used by millions of developer…
  api_count: 4
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: azure-event-grid
  name: Azure Event Grid
  description: Azure Event Grid is a fully managed event routing service from Microsoft Azure that enables event-driven, reactive programming by ingesting events from Azure services, SaaS providers, and custom sources and delivering them to subscribers s…
  api_count: 1
  score_band: thin
  score_composite: 38.9
  shared: 2
- slug: upstash
  name: Upstash
  description: Upstash provides serverless data platforms including managed Redis, Kafka, QStash messaging, and Vector databases optimized for serverless and edge applications with per-request pricing. The platform offers low-latency global replication,…
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: google-cloud-pubsub
  name: Google Cloud Pub/Sub
  description: Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications. It provides reliable, many-to-many, asynchronous messaging that decouples senders and recei…
  api_count: 1
  score_band: thin
  score_composite: 37.9
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: spring-integration
  name: Spring Integration
  description: Spring Integration extends the Spring programming model to support enterprise integration patterns (EIP), providing lightweight messaging within Spring-based applications and integration with external systems via declarative adapters. It s…
  api_count: 2
  score_band: thin
  score_composite: 34.4
  shared: 2
- slug: apache-event-mesh
  name: Apache EventMesh
  description: Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents…
  api_count: 1
  score_band: thin
  score_composite: 33.7
  shared: 2
- slug: apache-pulsar
  name: Apache Pulsar
  description: Apache Pulsar is a cloud-native, distributed messaging and streaming platform that provides server-to-server messaging with multi-tenancy, high performance, and geo-replication. It combines messaging and stream processing in a single platf…
  api_count: 1
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: strimzi
  name: Strimzi
  description: Strimzi is a CNCF project providing a Kubernetes-native operator for running Apache Kafka on Kubernetes and OpenShift. It simplifies the deployment, management, scaling, and configuration of Kafka clusters using Kubernetes Custom Resource…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 2
- slug: spring-cloud-stream
  name: Spring Cloud Stream
  description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persi…
  api_count: 3
  score_band: thin
  score_composite: 30.7
  shared: 2
- slug: apache-rocketmq
  name: Apache RocketMQ
  description: Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance, and reliability. It provides trillion-level message capacity with rich message types including normal, transactional, delayed, and ordere…
  api_count: 1
  score_band: thin
  score_composite: 28.3
  shared: 2
- slug: events
  name: Events
  description: Event-driven APIs catalog. Documents the landscape of brokers, streaming platforms, schema registries, and the specifications that standardize how events are described, transported, and stored. "Events" is the broader category that contain…
  api_count: 18
  score_band: thin
  score_composite: 27.3
  shared: 2
- slug: masstransit
  name: MassTransit
  description: MassTransit is a free, open source distributed application framework for .NET that makes it easy to create applications and services that leverage message-based, loosely-coupled asynchronous communication for higher availability, reliabili…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 2
- slug: dragonfly
  name: Dragonfly
  description: Dragonfly is a modern in-memory datastore built for performance and scalability, designed as a drop-in replacement for Redis and Memcached with improved efficiency and throughput. Dragonfly uses a multi-threaded, shared-nothing architectur…
  api_count: 0
  score_band: emerging
  score_composite: 17.4
  shared: 2
- slug: algox2
  name: AlgoX2
  description: AlgoX2 is a data streaming operating system that unifies ingestion, ordering, fan-out, transformation, and durable storage into a single fault-tolerant engine, positioned as an alternative to assembling Kafka, Flink, and Redis. Built by ve…
  api_count: 0
  score_band: minimal
  score_composite: 7.4
  shared: 2
- slug: appnet
  name: App.net
  description: 'App.net (ADN) was a paid, ad-free real-time social networking and microblogging platform launched in 2012 by Dalton Caldwell''s Mixed Media Labs after a public crowdfunding campaign. It was explicitly developer-first: the App.net Stream API…'
  api_count: 1
  score_band: null
  score_composite: 0
  shared: 2
---
