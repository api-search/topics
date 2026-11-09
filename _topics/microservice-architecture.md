---
layout: topic
slug: microservice-architecture
name: Microservice Architecture
kind: concept
description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services organized around business capabilities. Widely used by developers to build, maintain, and scale software applications efficiently.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/microservice-architecture.png
tags:
- Architecture
- Cloud-Native
- Distributed Systems
- Microservices
- Software Design
area: microservices
repo: https://github.com/api-evangelist/microservice-architecture
api_count: 0
apis: []
links:
- type: Website
  url: https://github.com/api-evangelist/microservice-architecture
- type: Wikipedia
  url: https://en.wikipedia.org/wiki/Microservices
provider_count: 34
providers:
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 53.2
  shared: 3
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
  api_count: 1
  score_band: thin
  score_composite: 35.4
  shared: 3
- slug: diagrid
  name: Diagrid
  description: Diagrid is the execution layer for production AI, built by the creators of the open source Dapr and KEDA projects. Its managed platform, Diagrid Catalyst, gives AI agents, workflows, and MCP servers durable execution (applications resume f…
  api_count: 0
  score_band: thin
  score_composite: 35.0
  shared: 3
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 4
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: websphere
  name: IBM WebSphere
  description: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.
  api_count: 7
  score_band: strong
  score_composite: 59.9
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: etcd
  name: Etcd
  description: etcd is a CNCF graduated distributed, reliable key-value store used as the backing store for all Kubernetes cluster data. It provides strong consistency guarantees using the Raft consensus algorithm, supporting watch operations, lease-base…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: apollo-config
  name: Apollo Config
  description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. O…
  api_count: 1
  score_band: developing
  score_composite: 44.4
  shared: 2
- slug: wasmcloud
  name: wasmCloud
  description: wasmCloud is a CNCF incubating platform for building, managing, and scaling distributed applications using WebAssembly components. It provides a runtime that manages the lifecycle of WebAssembly actors and capability providers, enabling de…
  api_count: 5
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: spring
  name: Spring Framework
  description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, mes…
  api_count: 3
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: nats
  name: NATS
  description: A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.
  api_count: 2
  score_band: developing
  score_composite: 39.9
  shared: 2
- slug: dapr
  name: Dapr
  description: Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state…
  api_count: 13
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: spring-cloud-config
  name: Spring Cloud Config
  description: Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN,…
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: restate
  name: Restate
  description: Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: vitess
  name: Vitess
  description: Vitess is a CNCF graduated database clustering system for horizontal scaling of MySQL through generalized sharding. It provides MySQL protocol compatibility, automated resharding, query routing, and connection pooling, making it suitable f…
  api_count: 4
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing,…
  api_count: 3
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of librari…
  api_count: 1
  score_band: thin
  score_composite: 31.4
  shared: 2
- slug: nacos
  name: Nacos
  description: Nacos is an easy-to-use dynamic service discovery, configuration, and service management platform from Alibaba for building cloud-native applications, supporting Dubbo, gRPC, Spring Cloud RESTful, and Kubernetes services.
  api_count: 1
  score_band: thin
  score_composite: 30.0
  shared: 2
- slug: spin
  name: Spin
  description: Spin is an open source framework by Fermyon for building and running fast, secure, and composable cloud microservices with WebAssembly. Spin provides a developer experience for creating event-driven serverless applications that compile to…
  api_count: 5
  score_band: thin
  score_composite: 28.7
  shared: 2
- slug: vineyard
  name: Vineyard
  description: Vineyard (v6d) is an in-memory immutable data manager developed under CNCF TAG-Storage. It provides efficient zero-copy data sharing across distributed systems for big data analytics, machine learning, and data-intensive workflows. Vineyar…
  api_count: 1
  score_band: thin
  score_composite: 28.2
  shared: 2
- slug: kratos
  name: Kratos
  description: Kratos is a Go framework for building cloud-native microservices, originally created at Bilibili. It provides built-in support for HTTP and gRPC transports, service discovery, configuration management, logging, metrics, and tracing, follow…
  api_count: 1
  score_band: thin
  score_composite: 27.9
  shared: 2
- slug: quarkus
  name: Quarkus
  description: Quarkus is a Kubernetes-native Java framework tailored for GraalVM and OpenJDK HotSpot, designed to build cloud-native microservices and serverless applications with fast startup times and low memory footprint.
  api_count: 1
  score_band: thin
  score_composite: 27.3
  shared: 2
- slug: open-liberty
  name: Open Liberty
  description: Open Liberty is a lightweight, open source Java application server from IBM for building cloud-native microservices and applications with full support for Jakarta EE and MicroProfile.
  api_count: 1
  score_band: thin
  score_composite: 27.1
  shared: 2
- slug: jboss
  name: JBoss
  description: JBoss is a division of Red Hat providing open source middleware and application server technologies for enterprise Java workloads. The JBoss product portfolio includes JBoss EAP (Enterprise Application Platform), the WildFly community appl…
  api_count: 5
  score_band: emerging
  score_composite: 26.0
  shared: 2
- slug: alibaba-sentinel
  name: Alibaba Sentinel
  description: Alibaba Sentinel is a powerful open source flow control component enabling reliability, resilience, and monitoring for microservices. Originally developed by Alibaba and used in production at Alibaba for over 10 years, Sentinel provides fl…
  api_count: 1
  score_band: emerging
  score_composite: 23.4
  shared: 2
- slug: helidon
  name: Helidon
  description: Helidon is a collection of Java libraries from Oracle for writing microservices that run on a fast web core powered by Netty, supporting MicroProfile and reactive programming models.
  api_count: 1
  score_band: emerging
  score_composite: 22.9
  shared: 2
- slug: netflix-eureka
  name: Netflix Eureka
  description: Netflix Eureka is a RESTful service registry used for service discovery, load balancing, and failover of middle-tier servers in microservice and cloud-native architectures, originally built for the AWS cloud.
  api_count: 1
  score_band: emerging
  score_composite: 22.3
  shared: 2
- slug: micronaut
  name: Micronaut
  description: Micronaut is a modern JVM-based framework for building modular, easily testable microservice and serverless applications with ahead-of-time compilation and minimal memory consumption.
  api_count: 1
  score_band: emerging
  score_composite: 22.0
  shared: 2
- slug: open-service-mesh
  name: Open Service Mesh
  description: Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh built on Envoy and the Service Mesh Interface (SMI) specification. OSM provides traffic shifting, mutual TLS, access control, observability, and automatic side…
  api_count: 1
  score_band: emerging
  score_composite: 21.5
  shared: 2
- slug: go-kit
  name: Go Kit
  description: Go Kit is a programming toolkit for building microservices in Go, emphasizing domain-driven design, transport-agnostic service definitions, and best practices for distributed systems.
  api_count: 1
  score_band: emerging
  score_composite: 13.6
  shared: 2
---
