---
layout: topic
slug: circuit-breaker
name: Circuit Breaker
kind: topic
description: The Circuit Breaker is a stability pattern for distributed systems and API architectures that prevents cascading failure when a downstream service degrades. A breaker wraps a remote call and tracks failures against a threshold; when the threshold is exceeded the breaker "opens" and short-circuits subsequent calls (typically returning an error or fallback) without contacting the downstream service. After a cooldown the breaker enters a "half-open" probe state and either resets to "closed" on success or re-opens on failure. The pattern was popularized by Michael Nygard in *Release It!* and is now standard in resilient microservice and API gateway design.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/circuit-breaker.png
tags:
- Circuit Breaker
- Distributed Systems
- Fault Tolerance
- Microservices
- Patterns
- Resilience
- Stability
repo: https://github.com/api-evangelist/circuit-breaker
api_count: 0
apis: []
links:
- type: Reference
  url: https://martinfowler.com/bliki/CircuitBreaker.html
- type: Reference
  url: https://docs.microsoft.com/azure/architecture/patterns/circuit-breaker
- type: Reference
  url: https://learn.microsoft.com/azure/architecture/patterns/retry
- type: Book
  url: https://pragprog.com/titles/mnee2/release-it-second-edition/
- type: JSONLD
  url: https://github.com/api-evangelist/circuit-breaker/blob/main/json-ld/circuit-breaker-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/circuit-breaker/blob/main/json-schema/circuit-breaker-state-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/circuit-breaker/blob/main/json-schema/circuit-breaker-config-schema.json
provider_count: 23
providers:
- slug: resilience4j
  name: Resilience4j
  description: Resilience4j is a lightweight fault tolerance library designed for Java 17+ and functional programming, providing higher-order functions to enhance functional interfaces with Circuit Breaker, Rate Limiter, Retry, Bulkhead, TimeLimiter, and…
  api_count: 1
  score_band: emerging
  score_composite: 22.2
  shared: 4
- slug: netflix-hystrix
  name: Netflix Hystrix
  description: Netflix Hystrix is a latency and fault tolerance library designed to isolate points of access to remote systems, services, and third-party libraries, stop cascading failure, and enable resilience in complex distributed systems where failur…
  api_count: 1
  score_band: emerging
  score_composite: 17.5
  shared: 4
- slug: polly
  name: Polly
  description: Polly is a .NET resilience and transient-fault-handling library that allows developers to express resilience strategies such as Retry, Circuit Breaker, Hedging, Timeout, Rate Limiter, and Fallback in a fluent and thread-safe manner. A .NET…
  api_count: 1
  score_band: emerging
  score_composite: 16.0
  shared: 4
- slug: alibaba-sentinel
  name: Alibaba Sentinel
  description: Alibaba Sentinel is a powerful open source flow control component enabling reliability, resilience, and monitoring for microservices. Originally developed by Alibaba and used in production at Alibaba for over 10 years, Sentinel provides fl…
  api_count: 1
  score_band: emerging
  score_composite: 23.3
  shared: 3
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 58.7
  shared: 2
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 2
- slug: apollo-config
  name: Apollo Config
  description: Apollo is a reliable, open-source configuration management system suitable for microservice configuration management scenarios, providing centralized configuration management, real-time updates, versioning, and multi-environment support. O…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 2
  score_band: developing
  score_composite: 44.2
  shared: 2
- slug: dapr
  name: Dapr
  description: Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state…
  api_count: 13
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: spring-cloud-config
  name: Spring Cloud Config
  description: Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN,…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 2
- slug: restate
  name: Restate
  description: Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices…
  api_count: 1
  score_band: thin
  score_composite: 37.9
  shared: 2
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
  api_count: 1
  score_band: thin
  score_composite: 35.5
  shared: 2
- slug: spring-cloud-gateway
  name: Spring Cloud Gateway
  description: Spring Cloud Gateway provides an intelligent, programmable router built on Spring WebFlux that serves as the entry point to microservice architectures. It offers routing, predicate evaluation, filter chaining, load balancing, circuit break…
  api_count: 1
  score_band: thin
  score_composite: 35.5
  shared: 2
- slug: diagrid
  name: Diagrid
  description: Diagrid is the execution layer for production AI, built by the creators of the open source Dapr and KEDA projects. Its managed platform, Diagrid Catalyst, gives AI agents, workflows, and MCP servers durable execution (applications resume f…
  api_count: 0
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of librari…
  api_count: 1
  score_band: thin
  score_composite: 32.9
  shared: 2
- slug: moleculer
  name: Moleculer
  description: Moleculer is a fast, modern, and powerful microservices framework for Node.js. It provides built-in service discovery, load balancing, fault tolerance with circuit breaker, request retries, distributed event handling, and support for multi…
  api_count: 1
  score_band: thin
  score_composite: 30.6
  shared: 2
- slug: go-kit
  name: Go Kit
  description: Go Kit is a programming toolkit for building microservices in Go, emphasizing domain-driven design, transport-agnostic service definitions, and best practices for distributed systems.
  api_count: 1
  score_band: emerging
  score_composite: 15.1
  shared: 2
- slug: go-micro
  name: Go Micro
  description: Go Micro is a distributed systems framework for building microservices in Go, providing service discovery, load balancing, message encoding, RPC, and async messaging out of the box.
  api_count: 1
  score_band: emerging
  score_composite: 12.5
  shared: 2
- slug: microservice-architecture-patterns
  name: Micro-Service Architecture Patterns
  description: Design patterns and best practices for building distributed systems using microservices architecture, including service decomposition, communication patterns, data management, and deployment strategies.
  api_count: 0
  score_band: minimal
  score_composite: 3.9
  shared: 2
- slug: microservice-architecture
  name: Microservice Architecture
  description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services organized around business capabilities. Widely used by developers to build, maintain, and scale software applicatio…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 2
- slug: microservice-design
  name: Microservice Design
  description: Architectural approach for building applications as a collection of loosely coupled, independently deployable services that are organized around business capabilities. Covers principles, patterns, and best practices for designing effective…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 2
- slug: microservices-architecture
  name: Microservices Architecture
  description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services, each running in its own process and communicating through lightweight mechanisms like HTTP/REST APIs. Widely used…
  api_count: 0
  score_band: minimal
  score_composite: 1.6
  shared: 2
- slug: microservices-design-patterns
  name: Microservices Design Patterns
  description: Architectural patterns and best practices for designing, building, and maintaining microservices-based applications, including patterns for communication, data management, deployment, and resilience.
  api_count: 0
  score_band: minimal
  score_composite: 1.6
  shared: 2
---
