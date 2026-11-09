---
layout: topic
slug: pub-sub
name: Pub/Sub
kind: concept
description: A messaging pattern where publishers send messages to topics without knowledge of subscribers, and subscribers receive messages from topics they're interested in, enabling asynchronous and decoupled communication between services. Modern distributed architectures rely on it to coordinate workloads across multiple nodes and regions.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/pub-sub.png
tags:
- Architecture
- Asynchronous
- Distributed Systems
- Messaging
- Pub/Sub
area: microservices
repo: https://github.com/api-evangelist/pub-sub
api_count: 0
apis: []
links: []
provider_count: 24
providers:
- slug: apache-kafka
  name: Apache Kafka
  description: Apache Kafka is an open-source distributed event streaming platform used by thousands of companies for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides a REST Proxy API,…
  api_count: 2
  score_band: developing
  score_composite: 51.3
  shared: 3
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 74.5
  shared: 2
- slug: synadia-communications
  name: Synadia Communications
  description: Synadia Communications, Inc. is the creator and primary maintainer of NATS.io, the CNCF connectivity and messaging system, and sells the commercial platform built on it. Its products are Synadia Cloud (fully managed, globally distributed N…
  api_count: 2
  score_band: exemplar
  score_composite: 72.1
  shared: 2
- slug: azure-service-bus
  name: Azure Service Bus
  description: Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics, providing reliable message delivery for decoupling applications and services in cloud and hybrid environments.
  api_count: 1
  score_band: exemplar
  score_composite: 68.0
  shared: 2
- slug: microsoft-azure-web-pubsub
  name: Azure Web PubSub
  description: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to speci…
  api_count: 3
  score_band: exemplar
  score_composite: 66.6
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: hivemq
  name: HiveMQ
  description: HiveMQ is an enterprise MQTT broker and IoT connectivity platform that provides reliable, scalable bidirectional messaging between connected devices and back-end systems using the MQTT protocol. It supports MQTT 3, MQTT 5, MQTT over WebSoc…
  api_count: 1
  score_band: strong
  score_composite: 57.2
  shared: 2
- slug: amazon-sns
  name: Amazon SNS
  description: Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It enables pub/sub, SMS, email, and mobile push notifications.
  api_count: 1
  score_band: strong
  score_composite: 55.5
  shared: 2
- slug: momento
  name: Momento
  description: Momento is a serverless data platform that provides low-latency, pay-as-you-go infrastructure without servers to provision, tune, or scale. Its core services are Momento Cache (an ephemeral serverless cache and drop-in Redis replacement),…
  api_count: 1
  score_band: developing
  score_composite: 48.8
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
- slug: azure-event-grid
  name: Azure Event Grid
  description: Azure Event Grid is a fully managed event routing service from Microsoft Azure that enables event-driven, reactive programming by ingesting events from Azure services, SaaS providers, and custom sources and delivering them to subscribers s…
  api_count: 1
  score_band: developing
  score_composite: 47.6
  shared: 2
- slug: dapr
  name: Dapr
  description: Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state…
  api_count: 13
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: google-cloud-pubsub
  name: Google Cloud Pub/Sub
  description: Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications. It provides reliable, many-to-many, asynchronous messaging that decouples senders and recei…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 2
- slug: pusher
  name: Pusher
  description: Pusher is a realtime communication platform owned by MessageBird/Bird. Its primary product Channels provides pub/sub messaging over WebSocket and HTTP; Beams provides device push notifications. Authentication uses an app key + secret per P…
  api_count: 1
  score_band: thin
  score_composite: 38.6
  shared: 2
- slug: google-pub-sub
  name: Google Pub/Sub
  description: Google Cloud Pub/Sub is a fully managed, real-time messaging service that allows you to send and receive messages between independent applications, providing reliable, many-to-many, asynchronous messaging for event ingestion, streaming ana…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 2
- slug: celery
  name: Celery
  description: Celery is an open-source distributed task queue for Python. It allows you to run tasks asynchronously in the background, enabling scalable distributed systems with support for multiple message brokers (RabbitMQ, Redis, Amazon SQS) and resu…
  api_count: 8
  score_band: thin
  score_composite: 37.6
  shared: 2
- slug: apache-event-mesh
  name: Apache EventMesh
  description: Apache EventMesh is a dynamic event-driven application runtime used to decouple the application and backend middleware layer, providing a serverless platform for building distributed event-driven architectures with support for CloudEvents…
  api_count: 1
  score_band: thin
  score_composite: 32.5
  shared: 2
- slug: pubnub
  name: PubNub
  description: PubNub is a realtime communication platform supporting pub/sub, presence, chat, App Context (object metadata), Functions (server-less compute on the edge), Push Notifications, and IoT messaging across 1B+ devices. The PubNub REST API runs…
  api_count: 2
  score_band: thin
  score_composite: 31.1
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
- slug: events
  name: Events
  description: Event-driven APIs catalog. Documents the landscape of brokers, streaming platforms, schema registries, and the specifications that standardize how events are described, transported, and stored. "Events" is the broader category that contain…
  api_count: 18
  score_band: thin
  score_composite: 29.3
  shared: 2
- slug: apache-rocketmq
  name: Apache RocketMQ
  description: Apache RocketMQ is a distributed messaging and streaming platform with low latency, high performance, and reliability. It provides trillion-level message capacity with rich message types including normal, transactional, delayed, and ordere…
  api_count: 1
  score_band: thin
  score_composite: 26.8
  shared: 2
- slug: amqp
  name: AMQP
  description: AMQP (Advanced Message Queuing Protocol) is an open standard for message-oriented middleware governed by OASIS and standardized as ISO/IEC 19464. AMQP 1.0 enables interoperable, asynchronous communication between applications across differ…
  api_count: 1
  score_band: null
  score_composite: 0
  shared: 2
---
