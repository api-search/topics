---
layout: topic
slug: microservice-architecture-patterns
name: Micro-Service Architecture Patterns
kind: concept
description: Design patterns and best practices for building distributed systems using microservices architecture, including service decomposition, communication patterns, data management, and deployment strategies.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/microservice-architecture-patterns.png
tags:
- Architecture
- Design Patterns
- Distributed Systems
- Microservices
- Software Engineering
area: microservices
repo: https://github.com/api-evangelist/microservice-architecture-patterns
api_count: 0
apis: []
links:
- type: BlogRSS
  url: https://microservices.io/feed.xml
- type: Website
  url: https://microservices.io/
- type: Reference
  url: https://microservices.io/patterns/index.html
- type: Microservices.io
  url: https://microservices.io/
- type: Pattern Language
  url: https://microservices.io/patterns/microservices.html
provider_count: 15
providers:
- slug: services-patterns
  name: Services Patterns
  description: Design patterns and architectural approaches for building microservices and service-oriented applications. Modern distributed architectures rely on it to coordinate workloads across multiple nodes and regions.
  api_count: 0
  score_band: minimal
  score_composite: 2.3
  shared: 3
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 4
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 53.2
  shared: 2
- slug: apollo-config
  name: Apollo Config
  description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. O…
  api_count: 1
  score_band: developing
  score_composite: 44.4
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
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
  api_count: 1
  score_band: thin
  score_composite: 35.4
  shared: 2
- slug: diagrid
  name: Diagrid
  description: Diagrid is the execution layer for production AI, built by the creators of the open source Dapr and KEDA projects. Its managed platform, Diagrid Catalyst, gives AI agents, workflows, and MCP servers durable execution (applications resume f…
  api_count: 0
  score_band: thin
  score_composite: 35.0
  shared: 2
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of librari…
  api_count: 1
  score_band: thin
  score_composite: 31.4
  shared: 2
- slug: arketo-ai
  name: Arketo
  description: Arketo is a web‑based developer application that connects AI assistants such as Claude, Code, Cursor, and others to automatically draw your app’s architecture live, flag potential breakages, and generate detailed reports. It helps prompt‑b…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 2
- slug: go-kit
  name: Go Kit
  description: Go Kit is a programming toolkit for building microservices in Go, emphasizing domain-driven design, transport-agnostic service definitions, and best practices for distributed systems.
  api_count: 1
  score_band: emerging
  score_composite: 13.6
  shared: 2
- slug: go-micro
  name: Go Micro
  description: Go Micro is a distributed systems framework for building microservices in Go, providing service discovery, load balancing, message encoding, RPC, and async messaging out of the box.
  api_count: 1
  score_band: emerging
  score_composite: 11.0
  shared: 2
- slug: restful-services
  name: RESTful Services
  description: Representational State Transfer (REST) services are web services built using the REST architectural style, which uses stateless HTTP communication and standard HTTP methods (GET, POST, PUT, DELETE, PATCH) to expose resources. RESTful servi…
  api_count: 5
  score_band: null
  score_composite: 0
  shared: 2
---
