---
layout: topic
slug: streaming
name: Streaming
kind: topic
description: 'Streaming is a topic catalog of the protocols, platforms, and processing engines used to move and transform real-time, high-volume, often bidirectional data over the network. It indexes the canonical log-structured and broker systems (Apache Kafka, Apache Pulsar, Redpanda, NATS JetStream, AWS Kinesis, GCP Pub/Sub + Dataflow, Azure Event Hubs, Confluent Cloud, StreamNative), the over-the-wire streaming protocols exposed to API consumers (Server-Sent Events, WebSocket, gRPC streaming, GraphQL subscriptions), the change-data capture and connector frameworks that feed them (Kafka Connect, Debezium), and the stream-processing engines that consume them (Apache Flink, Spark Structured Streaming, Materialize, Tinybird, Bytewax, Apache Beam). This topic is distinguished from `events` and `async-apis`: streaming emphasizes real-time, high-throughput, partitioned, and often bidirectional pipes, rather than discrete event envelopes or static contract documents.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/streaming.png
tags:
- Streaming
- Real-Time
- Event Streaming
- Change Data Capture
- Stream Processing
- Server-Sent Events
- WebSocket
- gRPC
- GraphQL Subscriptions
- Kafka
- Pulsar
- Kinesis
- Flink
repo: https://github.com/api-evangelist/streaming
api_count: 21
apis:
- name: Apache Kafka
  description: Distributed, partitioned, replicated log. The reference open-source streaming platform; durable, ordered topics with consumer groups, exactly -once semantics, and the de facto wire protocol for the streaming ecosystem. Native Kafka clients…
  url: https://kafka.apache.org
- name: Apache Pulsar
  description: Cloud-native, multi-tenant pub/sub and streaming platform with a tiered storage architecture (BookKeeper) that separates compute from storage, native geo-replication, and built-in Functions for lightweight stream processing.
  url: https://pulsar.apache.org
- name: Redpanda
  description: Kafka-API-compatible streaming platform implemented in C++ with no ZooKeeper/JVM dependency. Single binary, thread-per-core architecture, Raft consensus; positioned as a drop-in for Kafka workloads.
  url: https://redpanda.com
- name: NATS JetStream
  description: Persistence layer for the NATS messaging system providing at-least-once and exactly-once streaming, key/value and object stores, and durable consumers — designed for edge, IoT, and microservice topologies.
  url: https://nats.io/
- name: Amazon Kinesis
  description: 'AWS managed family for real-time streaming: Kinesis Data Streams (shards, partition keys, 24h–365d retention), Kinesis Data Firehose (delivery to S3/Redshift/OpenSearch), and Kinesis Video Streams for media. HTTP/2 SubscribeToShard for low…'
  url: https://aws.amazon.com/kinesis/
- name: Google Cloud Pub/Sub and Dataflow
  description: GCP's managed messaging (Pub/Sub) and stream-processing (Dataflow, built on Apache Beam) stack. Pub/Sub provides at-least-once and exactly-once delivery with push/pull subscribers; Dataflow runs windowed, watermark-aware Beam pipelines.
  url: https://cloud.google.com/pubsub
- name: Azure Event Hubs
  description: Microsoft's managed big-data streaming platform; Kafka-protocol compatible, partitioned, with Capture (delivery to ADLS/Blob) and tight integration with Azure Stream Analytics and Functions.
  url: https://azure.microsoft.com/en-us/products/event-hubs/
- name: Confluent Cloud
  description: Managed Kafka by the original Kafka authors. Cluster, topic, connector, KSQL, Schema Registry, Stream Governance, and Flink offerings exposed via a Confluent Cloud REST API and Terraform provider.
  url: https://www.confluent.io/confluent-cloud/
- name: StreamNative
  description: Managed Apache Pulsar as a service from Pulsar's original contributors, with multi-cloud clusters, Functions, sources/sinks, and a control-plane REST API.
  url: https://streamnative.io
- name: Server-Sent Events (SSE)
  description: One-directional HTTP-based streaming from server to client using the `text/event-stream` media type. Defined by the HTML Living Standard EventSource API; widely used for LLM token streams, dashboards, and live feeds where bidirectionality…
  url: https://html.spec.whatwg.org/multipage/server-sent-events.html
- name: WebSocket
  description: Full-duplex, bidirectional streaming protocol over a single TCP connection, upgraded from HTTP. RFC 6455. Foundation for chat, collaborative apps, market data, and real-time control planes.
  url: https://datatracker.ietf.org/doc/html/rfc6455
- name: gRPC Streaming
  description: 'gRPC defines four RPC styles, three of which are streaming: server streaming, client streaming, and bidirectional streaming, all multiplexed over HTTP/2. The default streaming surface for service-to-service systems and Kubernetes-native AP…'
  url: https://grpc.io
- name: GraphQL Subscriptions
  description: The GraphQL operation type for receiving a stream of updates over a long-lived transport (typically WebSocket via the graphql-ws or graphql-transport-ws sub-protocols, or SSE). Used to push schema- defined deltas to clients.
  url: https://spec.graphql.org/draft/#sec-Subscription
- name: Kafka Connect
  description: Framework and runtime for source/sink connectors that move data into and out of Kafka. Distributed mode runs a REST-controlled cluster of workers managing connector and task lifecycle.
  url: https://kafka.apache.org/documentation/#connect
- name: Debezium
  description: Change-data-capture (CDC) platform that streams row-level database changes (Postgres, MySQL, MongoDB, SQL Server, Oracle, Cassandra) as Kafka records using each database's native replication log.
  url: https://debezium.io
- name: Apache Flink
  description: Distributed, stateful stream-processing engine with event-time semantics, windowing, watermarks, and exactly-once state. SQL, DataStream, and Table APIs; reference engine for sub-second latency analytics on streams.
  url: https://flink.apache.org
- name: Spark Structured Streaming
  description: Stream-processing API built on Spark SQL using a micro-batch (and experimental continuous) execution model. Treats a stream as an unbounded table.
  url: https://spark.apache.org/streaming/
- name: Materialize
  description: Operational data warehouse and streaming SQL database built on Differential Dataflow. Maintains incrementally updated materialized views over streaming sources with millisecond freshness.
  url: https://materialize.com
- name: Tinybird
  description: Real-time analytics platform built on ClickHouse; ingests streams via HTTP, Kafka, or CDC, exposes SQL pipes as parameterized HTTP API endpoints with auth tokens.
  url: https://www.tinybird.co
- name: Bytewax
  description: Open-source Python-native stream-processing framework built on Timely Dataflow; targets data scientists and Python teams building real-time ML and data pipelines.
  url: https://bytewax.io
- name: Apache Beam
  description: Unified batch and streaming programming model. Beam pipelines run on multiple runners (Dataflow, Flink, Spark, Samza), defining the canonical event-time / watermark / window / trigger semantics for stream processing.
  url: https://beam.apache.org
links:
- type: IssueTracker
  url: https://github.com/apache/kafka/issues
- type: SecurityPolicy
  url: https://github.com/apache/kafka/blob/trunk/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/apache/.github/blob/main/.github/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/apache/kafka/blob/trunk/CONTRIBUTING.md
- type: License
  url: https://github.com/apache/kafka/blob/trunk/LICENSE
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/streaming/blob/main/security/streaming-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/streaming/blob/main/security/streaming-domain-security.yml
- type: JSONSchema
  url: https://github.com/api-evangelist/streaming/blob/main/json-schema/streaming-stream-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/streaming/blob/main/json-schema/streaming-stream-record-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/streaming/blob/main/json-schema/streaming-stream-platform-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/streaming/blob/main/json-ld/streaming-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/streaming/blob/main/vocabulary/streaming-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/streaming/blob/main/examples/streaming-stream-example.json
- type: Examples
  url: https://github.com/api-evangelist/streaming/blob/main/examples/streaming-stream-record-example.json
- type: Examples
  url: https://github.com/api-evangelist/streaming/blob/main/examples/streaming-stream-platform-example.json
provider_count: 95
providers:
- slug: redpanda
  name: Redpanda
  description: Redpanda is a Kafka API-compatible streaming data platform written in C++ with no JVM and no ZooKeeper, optimized for low latency and operational simplicity. The core broker (redpanda) is open source and available under the Business Source…
  api_count: 10
  score_band: thin
  score_composite: 33.8
  shared: 5
- slug: streamkap
  name: Streamkap
  description: Streamkap is a real-time streaming ETL and change data capture (CDC) platform built on Apache Kafka and Apache Flink. It streams data from operational databases (PostgreSQL, MySQL, MongoDB, SQL Server, Oracle) to cloud warehouses, lakes, a…
  api_count: 1
  score_band: thin
  score_composite: 26.5
  shared: 5
- slug: nstream
  name: Nstream
  description: Nstream is the company behind SwimOS, an open-source platform for building streaming data applications. Instead of polling databases, Nstream keeps application state continuously in memory as stateful "web agents" that ingest events from a…
  api_count: 0
  score_band: emerging
  score_composite: 21.4
  shared: 4
- slug: heroiclabs
  name: Heroic Labs
  description: Heroic Labs is the company behind Nakama, a leading open-source game backend server providing a comprehensive REST, WebSocket, and gRPC API for building scalable multiplayer and social games. The platform delivers essential backend service…
  api_count: 4
  score_band: exemplar
  score_composite: 67.5
  shared: 3
- slug: buf
  name: Buf
  description: 'Buf Technologies builds the modern toolchain for Protocol Buffers and gRPC: the buf CLI, the Buf Schema Registry (BSR), Protovalidate, Protobuf-ES and Protobuf-Py, and the Connect protocol, which is now a CNCF project. It replaces protoc-b…'
  api_count: 2
  score_band: strong
  score_composite: 61.4
  shared: 3
- slug: s2-dev
  name: S2 Dev
  description: S2 ("Stream Store") is the API for unlimited, durable, real-time streams. Where object storage deals with blobs, S2 provides append-able, ordered record streams that can be tailed in real time and replayed from any retained point. Core dat…
  api_count: 1
  score_band: strong
  score_composite: 59.4
  shared: 3
- slug: laserdata
  name: LaserData
  description: LaserData is a hyper-efficient data streaming platform built in Rust for AI-native, real-time, and latency-sensitive workloads. Founded by the creators of Apache Iggy, LaserData packages the Iggy message-streaming engine — io_uring, thread…
  api_count: 3
  score_band: strong
  score_composite: 57.6
  shared: 3
- slug: warpstream
  name: WarpStream
  description: WarpStream is a diskless, Apache Kafka-compatible data streaming platform built directly on top of cloud object storage such as S3, GCP, and Azure. It eliminates the need for local disks, brokers to rebalance, and ZooKeeper, delivering Kaf…
  api_count: 1
  score_band: developing
  score_composite: 48.0
  shared: 3
- slug: macrometa
  name: Macrometa
  description: Macrometa is a global data network and edge computing platform. Its Global Data Network (GDN) provides a geo-distributed, serverless NoSQL database, pub/sub streams, complex event processing, and edge functions through a unified REST API p…
  api_count: 8
  score_band: developing
  score_composite: 47.5
  shared: 3
- slug: striim
  name: Striim
  description: Unified data integration and streaming platform offering change data capture (CDC), real-time streaming analytics, and data validation. Exposes a token-authenticated REST API (WActionStore queries, system health, Application Management) co…
  api_count: 6
  score_band: developing
  score_composite: 47.0
  shared: 3
- slug: neuphonic
  name: Neuphonic
  description: Neuphonic is an ultra-low-latency voice AI platform specializing in real-time text-to-speech synthesis with sub-25ms latency, making it suitable for conversational AI and live applications. The platform provides both a cloud-hosted API wit…
  api_count: 1
  score_band: developing
  score_composite: 46.6
  shared: 3
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, w…
  api_count: 2
  score_band: developing
  score_composite: 43.1
  shared: 3
- slug: risingwave
  name: RisingWave
  description: RisingWave is a distributed SQL streaming platform that continuously ingests event streams from Kafka, Kinesis, and other sources, transforms them using PostgreSQL-compatible SQL, and serves low-latency results through incrementally mainta…
  api_count: 6
  score_band: developing
  score_composite: 43.0
  shared: 3
- slug: quix
  name: Quix
  description: Quix is a Python-native stream-processing platform for real-time data and ML. It pairs Quix Streams - an open source (Apache 2.0) Python library for building containerized stream-processing applications on Apache Kafka - with Quix Cloud, a…
  api_count: 1
  score_band: developing
  score_composite: 40.7
  shared: 3
- slug: estuary-flow
  name: Estuary Flow
  description: Estuary Flow is a real-time data movement and transformation platform combining streaming infrastructure, a runtime, and an open-source ecosystem of connectors. It supports change data capture (CDC), SaaS integration, database replication,…
  api_count: 4
  score_band: thin
  score_composite: 36.1
  shared: 3
- slug: bytewax
  name: Bytewax
  description: Bytewax is a Python-native distributed stream processing framework built on a Rust runtime. Developers define dataflows using the bytewax.dataflow API, composing operators (map, filter, reduce, joins, windowing) over connectors for Kafka,…
  api_count: 3
  score_band: thin
  score_composite: 33.4
  shared: 3
- slug: pulsoid
  name: Pulsoid
  description: Pulsoid enables real-time heart rate data transmission from peripherals (BLE heart rate monitors, smartwatches, etc.) to clients. The Pulsoid API allows reading and writing real-time heart rate data, accessing statistics, and managing widg…
  api_count: 1
  score_band: thin
  score_composite: 29.7
  shared: 3
- slug: apache-samza
  name: Apache Samza
  description: Apache Samza is a distributed stream processing framework that provides a simple API for building stateful stream processing applications. It integrates with Apache Kafka for messaging and supports both stream and batch processing.
  api_count: 1
  score_band: thin
  score_composite: 28.7
  shared: 3
- slug: concord-systems
  name: Concord Systems
  description: Concord Systems was a Brooklyn, New York stream-processing company founded in December 2014 by Alexander Gallego and Emilio Del Tesoro, and backed by Bloomberg Beta. It built a high-performance distributed stream processing framework writt…
  api_count: 0
  score_band: minimal
  score_composite: 9.3
  shared: 3
- slug: confluent
  name: Confluent
  description: Stream, connect, process, and govern your data with an all-in-one, real-time platform from the pioneer in data streaming. Build faster, scale smarter, and turn data chaos into instantly accessible and usable data products with the market l…
  api_count: 3
  score_band: exemplar
  score_composite: 79.1
  shared: 2
- slug: 0xarchive
  name: 0xArchive
  description: 0xArchive is a replayable market-data archive for two decentralised perpetuals venues, Hyperliquid and Lighter, delivered as one REST API, one WebSocket API that carries both live subscriptions and historical replay on a single connection,…
  api_count: 2
  score_band: exemplar
  score_composite: 76.4
  shared: 2
- slug: confluent-the-data-streaming-platform
  name: Confluent | the Data Streaming Platform
  description: Confluent is a fully managed data streaming platform built by the original creators of Apache Kafka. It lets organizations stream, connect, process, and govern data in motion through a cloud-native service (Confluent Cloud) and the on-prem…
  api_count: 2
  score_band: exemplar
  score_composite: 74.3
  shared: 2
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 72.4
  shared: 2
- slug: x
  name: X
  description: X (formerly Twitter) operates the X Developer Platform, the programmable interface to the public conversation on X. The X API v2 is a 190-operation REST surface covering Posts, Users, Direct Messages, the encrypted Chat API, Lists, Spaces,…
  api_count: 2
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: polygon
  name: Massive (formerly Polygon.io)
  description: Polygon (Polygon.io, rebranded as Massive in early 2026) provides real-time and historical market data APIs across US stocks, options, indices, forex, cryptocurrencies, and futures. Coverage is delivered through REST endpoints and WebSocke…
  api_count: 7
  score_band: exemplar
  score_composite: 67.2
  shared: 2
- slug: dolby
  name: Dolby
  description: Dolby Laboratories is an audio and video technology company whose developer platform, Dolby OptiView, is the merged surface of the original dolby.io platform, THEO Technologies (THEOplayer, THEOlive, THEOads) and Millicast. It ships public…
  api_count: 13
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: twitter-x
  name: Twitter/X
  description: X (formerly Twitter) operates the X Developer Platform, giving developers programmatic access to the public conversation through the X API v2 — Posts, Users, Direct Messages, Lists, Spaces, Communities, Community Notes, Trends, News, Media…
  api_count: 1
  score_band: strong
  score_composite: 65.4
  shared: 2
- slug: nexla
  name: Nexla
  description: Nexla is an enterprise data integration and AI-data platform, founded in 2016 and headquartered in San Mateo, California. Its core abstraction is the Nexset — a logical, schema-aware, bi-directionally usable data product that Nexla generat…
  api_count: 4
  score_band: strong
  score_composite: 64.1
  shared: 2
- slug: siftingio
  name: SiftingIO
  description: Cross-asset market data APIs covering US equities, forex, cryptocurrency, DeFi/on-chain, commodities, and SEC/EDGAR fundamentals, aggregated across venues and normalized into one JSON schema so every asset class shares the same fields, aut…
  api_count: 1
  score_band: strong
  score_composite: 63.9
  shared: 2
- slug: red5
  name: Red5
  description: Red5 provides real-time streaming infrastructure for live video and audio delivery at scale. The Red5 Pro platform includes a media server, Stream Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite stream productio…
  api_count: 3
  score_band: strong
  score_composite: 62.5
  shared: 2
---
