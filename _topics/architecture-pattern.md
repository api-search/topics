---
layout: topic
slug: architecture-pattern
name: Architecture Pattern
kind: topic
description: Architecture Patterns provide reusable solutions to commonly occurring software and system design problems. They offer proven templates for organizing code, components, and interactions across distributed systems, microservices, cloud-native applications, and enterprise software.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/architecture-pattern.png
tags:
- Architecture Patterns
- Software Architecture
- Design Patterns
- System Design
- Microservices
- Cloud-Native
repo: https://github.com/api-evangelist/architecture-pattern
api_count: 3
apis:
- name: Architecture Pattern Domains API
  description: The Domains API from Architecture Pattern — 1 operation(s) for domains.
  url: https://microservices.io/patterns/
- name: Architecture Pattern Patterns API
  description: The Patterns API from Architecture Pattern — 3 operation(s) for patterns.
  url: https://microservices.io/patterns/
- name: Architecture Pattern Trade-offs API
  description: The Trade-offs API from Architecture Pattern — 1 operation(s) for trade-offs.
  url: https://microservices.io/patterns/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/architecture-pattern/blob/main/agentic-access/architecture-pattern-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/architecture-pattern/blob/main/security/architecture-pattern-domain-security.yml
- type: Portal
  url: https://microservices.io/patterns/
- type: Documentation
  url: https://microservices.io/patterns/
- type: Blog
  url: https://microservices.io/feed.xml
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: SpectralRules
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/rules/architecture-pattern-spectral-rules.yml
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/vocabulary/architecture-pattern-vocabulary.yaml
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/architecture-pattern/refs/heads/main/json-ld/architecture-pattern-api-context.jsonld
provider_count: 31
providers:
- slug: integration-patterns
  name: Integration Patterns
  description: Integration Patterns are design patterns and best practices for integrating different software systems and applications, including messaging, data transformation, and service orchestration approaches. Enterprise Integration Patterns (EIP),…
  api_count: 0
  score_band: minimal
  score_composite: 3.9
  shared: 3
- slug: microservice-design
  name: Microservice Design
  description: Architectural approach for building applications as a collection of loosely coupled, independently deployable services that are organized around business capabilities. Covers principles, patterns, and best practices for designing effective…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 3
- slug: websphere
  name: IBM WebSphere
  description: IBM WebSphere is a family of enterprise software products that provide middleware and application server capabilities for building, deploying, and managing enterprise applications.
  api_count: 7
  score_band: strong
  score_composite: 58.0
  shared: 2
- slug: zeebe
  name: Zeebe
  description: Zeebe is the cloud-native workflow engine that powers Camunda 8, providing scalable, resilient workflow automation and microservices orchestration without relying on a central database, enabling high throughput with horizontal scaling. It…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 2
- slug: spring
  name: Spring Framework
  description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, mes…
  api_count: 3
  score_band: developing
  score_composite: 44.4
  shared: 2
- slug: nats
  name: NATS
  description: A high-performance, cloud-native messaging system for microservices, IoT, and edge computing. Provides pub-sub, request-reply, and queue-based messaging patterns with at-most-once and at-least-once delivery guarantees.
  api_count: 2
  score_band: developing
  score_composite: 40.3
  shared: 2
- slug: istio
  name: Istio
  description: Istio is an open-source service mesh platform that provides a comprehensive solution for managing, securing, and monitoring microservices in a distributed system. It acts as a middle layer between services, handling communication, routing,…
  api_count: 3
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
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
- slug: spin
  name: Spin
  description: Spin is an open source framework by Fermyon for building and running fast, secure, and composable cloud microservices with WebAssembly. Spin provides a developer experience for creating event-driven serverless applications that compile to…
  api_count: 5
  score_band: thin
  score_composite: 30.0
  shared: 2
- slug: nacos
  name: Nacos
  description: Nacos is an easy-to-use dynamic service discovery, configuration, and service management platform from Alibaba for building cloud-native applications, supporting Dubbo, gRPC, Spring Cloud RESTful, and Kubernetes services.
  api_count: 1
  score_band: thin
  score_composite: 29.9
  shared: 2
- slug: kratos
  name: Kratos
  description: Kratos is a Go framework for building cloud-native microservices, originally created at Bilibili. It provides built-in support for HTTP and gRPC transports, service discovery, configuration management, logging, metrics, and tracing, follow…
  api_count: 1
  score_band: thin
  score_composite: 29.3
  shared: 2
- slug: open-liberty
  name: Open Liberty
  description: Open Liberty is a lightweight, open source Java application server from IBM for building cloud-native microservices and applications with full support for Jakarta EE and MicroProfile.
  api_count: 1
  score_band: thin
  score_composite: 28.6
  shared: 2
- slug: jboss
  name: JBoss
  description: JBoss is a division of Red Hat providing open source middleware and application server technologies for enterprise Java workloads. The JBoss product portfolio includes JBoss EAP (Enterprise Application Platform), the WildFly community appl…
  api_count: 5
  score_band: emerging
  score_composite: 26.1
  shared: 2
- slug: quarkus
  name: Quarkus
  description: Quarkus is a Kubernetes-native Java framework tailored for GraalVM and OpenJDK HotSpot, designed to build cloud-native microservices and serverless applications with fast startup times and low memory footprint.
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: micronaut
  name: Micronaut
  description: Micronaut is a modern JVM-based framework for building modular, easily testable microservice and serverless applications with ahead-of-time compilation and minimal memory consumption.
  api_count: 1
  score_band: emerging
  score_composite: 23.5
  shared: 2
- slug: alibaba-sentinel
  name: Alibaba Sentinel
  description: Alibaba Sentinel is a powerful open source flow control component enabling reliability, resilience, and monitoring for microservices. Originally developed by Alibaba and used in production at Alibaba for over 10 years, Sentinel provides fl…
  api_count: 1
  score_band: emerging
  score_composite: 23.3
  shared: 2
- slug: open-service-mesh
  name: Open Service Mesh
  description: Open Service Mesh (OSM) is a lightweight, extensible, cloud native service mesh built on Envoy and the Service Mesh Interface (SMI) specification. OSM provides traffic shifting, mutual TLS, access control, observability, and automatic side…
  api_count: 1
  score_band: emerging
  score_composite: 22.9
  shared: 2
- slug: netflix-eureka
  name: Netflix Eureka
  description: Netflix Eureka is a RESTful service registry used for service discovery, load balancing, and failover of middle-tier servers in microservice and cloud-native architectures, originally built for the AWS cloud.
  api_count: 1
  score_band: emerging
  score_composite: 22.2
  shared: 2
- slug: helidon
  name: Helidon
  description: Helidon is a collection of Java libraries from Oracle for writing microservices that run on a fast web core powered by Netty, supporting MicroProfile and reactive programming models.
  api_count: 1
  score_band: emerging
  score_composite: 21.2
  shared: 2
- slug: dependency-injection
  name: Dependency Injection
  description: A design pattern in which objects receive their dependencies from external sources rather than creating them internally, promoting loose coupling, easier testing, and clear composition roots. Effective use of this practice reduces bugs in…
  api_count: 1
  score_band: emerging
  score_composite: 12.5
  shared: 2
- slug: mia-platform
  name: Mia-Platform
  description: Mia-Platform is an Internal Developer Platform (IDP) that harmonizes infrastructure, applications, and data for intelligent engineering at scale. It provides an API-first platform for building and managing microservices and cloud-native ap…
  api_count: 1
  score_band: minimal
  score_composite: 9.4
  shared: 2
- slug: microservice-architecture-patterns
  name: Micro-Service Architecture Patterns
  description: Design patterns and best practices for building distributed systems using microservices architecture, including service decomposition, communication patterns, data management, and deployment strategies.
  api_count: 0
  score_band: minimal
  score_composite: 3.9
  shared: 2
- slug: domain-driven-design
  name: Domain-Driven Design
  description: A software development approach that focuses on modeling software to match a domain according to input from domain experts, emphasizing collaboration between technical and domain experts to create a shared understanding through ubiquitous…
  api_count: 0
  score_band: minimal
  score_composite: 3.2
  shared: 2
- slug: modular-monolith
  name: Modular Monolith
  description: An architectural pattern that structures a monolithic application into loosely coupled, well-defined modules with clear boundaries and dependencies, combining the operational simplicity of a monolith with the organizational benefits of mod…
  api_count: 0
  score_band: minimal
  score_composite: 3.0
  shared: 2
- slug: microservice-architecture
  name: Microservice Architecture
  description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services organized around business capabilities. Widely used by developers to build, maintain, and scale software applicatio…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 2
- slug: services-patterns
  name: Services Patterns
  description: Design patterns and architectural approaches for building microservices and service-oriented applications. Modern distributed architectures rely on it to coordinate workloads across multiple nodes and regions.
  api_count: 0
  score_band: minimal
  score_composite: 2.3
  shared: 2
- slug: inversion-of-control
  name: Inversion of Control
  description: Inversion of Control (IoC) is a software design principle where the control flow of a program is inverted compared to traditional programming. Instead of application code calling frameworks, frameworks call application code. Common impleme…
  api_count: 0
  score_band: minimal
  score_composite: 1.6
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
