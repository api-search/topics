---
layout: topic
slug: software-design-architectural-patterns
name: Software Design Architectural Patterns
kind: topic
description: Software architectural patterns are reusable solutions and best practices for organizing software system architecture. Key patterns include MVC (Model-View-Controller), Microservices, Layered Architecture, Event-Driven Architecture, CQRS (Command Query Responsibility Segregation), Hexagonal Architecture, and Service-Oriented Architecture. These patterns are documented by Microsoft Azure Architecture Center, AWS Well-Architected Framework, and the broader software engineering community.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/software-design-architectural-patterns.png
tags:
- Best Practices
- Design Patterns
- Software Architecture
- System Design
- Microservices
- MVC
- CQRS
- Event-Driven
repo: https://github.com/api-evangelist/software-design-architectural-patterns
api_count: 2
apis:
- name: Azure Architecture Center
  description: Microsoft Azure Architecture Center provides guidance, patterns, and best practices for building cloud-native architectures. It documents architectural patterns including CQRS, Event Sourcing, Strangler Fig, Circuit Breaker, Bulkhead, and…
  url: https://learn.microsoft.com/en-us/azure/architecture/patterns/
- name: Microservices.io Patterns Catalog
  description: Microservices.io is a pattern language for microservices architectures, documenting patterns for decomposition, data management, communication, deployment, and cross-cutting concerns. It covers API Gateway, Saga, Event Sourcing, CQRS, and…
  url: https://microservices.io/patterns/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/software-design-architectural-patterns/blob/main/security/software-design-architectural-patterns-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/software-design-architectural-patterns/blob/main/security/software-design-architectural-patterns-domain-security.yml
- type: Reference
  url: https://en.wikipedia.org/wiki/Architectural_pattern
- type: Reference
  url: https://learn.microsoft.com/en-us/azure/architecture/patterns/
- type: Reference
  url: https://microservices.io/patterns/
- type: Reference
  url: https://refactoring.guru/design-patterns
- type: Reference
  url: https://martinfowler.com/architecture/
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/software-design-architectural-patterns/refs/heads/main/json-ld/software-design-architectural-patterns-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/software-design-architectural-patterns/refs/heads/main/vocabulary/software-design-architectural-patterns-vocabulary.yml
provider_count: 17
providers:
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 3
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: emerging
  score_composite: 21.3
  shared: 3
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
- slug: conductor-oss
  name: Conductor OSS
  description: Conductor OSS is the Netflix-founded, Orkes-stewarded open source workflow and agentic AI orchestration platform. It provides a durable, event-driven workflow engine for coordinating microservices, long-running tasks, human approvals, and…
  api_count: 1
  score_band: thin
  score_composite: 32.6
  shared: 2
- slug: vert-x
  name: Vert.x
  description: Eclipse Vert.x is a toolkit for building reactive applications on the JVM, providing support for multiple languages including Java, JavaScript, Groovy, Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the Eclipse F…
  api_count: 7
  score_band: thin
  score_composite: 32.0
  shared: 2
- slug: spring-cloud-stream
  name: Spring Cloud Stream
  description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persi…
  api_count: 3
  score_band: thin
  score_composite: 30.2
  shared: 2
- slug: netflix-conductor
  name: Netflix Conductor
  description: Conductor is a microservices orchestration platform originally created by Netflix, providing a workflow engine for coordinating and managing complex distributed processes across multiple services with built-in retries, error handling, and…
  api_count: 1
  score_band: emerging
  score_composite: 21.4
  shared: 2
- slug: dependency-injection
  name: Dependency Injection
  description: A design pattern in which objects receive their dependencies from external sources rather than creating them internally, promoting loose coupling, easier testing, and clear composition roots. Effective use of this practice reduces bugs in…
  api_count: 1
  score_band: emerging
  score_composite: 12.5
  shared: 2
- slug: design-patterns
  name: Design Patterns
  description: Reusable solutions to commonly occurring problems in software design, including the Gang of Four catalog (creational, structural, behavioral) and core API design patterns such as HATEOAS, idempotency keys, webhooks, and sagas.
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
- slug: microservices-design-patterns
  name: Microservices Design Patterns
  description: Architectural patterns and best practices for designing, building, and maintaining microservices-based applications, including patterns for communication, data management, deployment, and resilience.
  api_count: 0
  score_band: minimal
  score_composite: 1.6
  shared: 2
- slug: monolithic-architecture
  name: Monolithic Architecture
  description: Monolithic Architecture is a software design approach in which an application is built as a single, unified unit where all components, business logic, data access, and user interface are tightly coupled and deployed together. It contrasts…
  api_count: 0
  score_band: minimal
  score_composite: 1.6
  shared: 2
---
