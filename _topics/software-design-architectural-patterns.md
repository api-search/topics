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
- type: Plans
  url: https://github.com/api-evangelist/software-design-architectural-patterns/blob/main/plans/software-design-architectural-patterns-plans-pricing.yml
- type: RateLimits
  url: https://github.com/api-evangelist/software-design-architectural-patterns/blob/main/rate-limits/software-design-architectural-patterns-rate-limits.yml
- type: FinOps
  url: https://github.com/api-evangelist/software-design-architectural-patterns/blob/main/finops/software-design-architectural-patterns-finops.yml
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
provider_count: 8
providers:
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 3
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: emerging
  score_composite: 21.5
  shared: 3
- slug: conductor-oss
  name: Conductor OSS
  description: Conductor OSS is the Netflix-founded, Orkes-stewarded open source workflow and agentic AI orchestration platform. It provides a durable, event-driven workflow engine for coordinating microservices, long-running tasks, human approvals, and…
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 2
- slug: vert-x
  name: Vert.x
  description: Eclipse Vert.x is a toolkit for building reactive applications on the JVM, providing support for multiple languages including Java, JavaScript, Groovy, Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the Eclipse F…
  api_count: 7
  score_band: thin
  score_composite: 31.9
  shared: 2
- slug: spring-cloud-stream
  name: Spring Cloud Stream
  description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persi…
  api_count: 3
  score_band: thin
  score_composite: 30.0
  shared: 2
- slug: netflix-conductor
  name: Netflix Conductor
  description: Conductor is a microservices orchestration platform originally created by Netflix, providing a workflow engine for coordinating and managing complex distributed processes across multiple services with built-in retries, error handling, and…
  api_count: 1
  score_band: emerging
  score_composite: 21.5
  shared: 2
- slug: design-patterns
  name: Design Patterns
  description: Reusable solutions to commonly occurring problems in software design, including the Gang of Four catalog (creational, structural, behavioral) and core API design patterns such as HATEOAS, idempotency keys, webhooks, and sagas.
  api_count: 1
  score_band: emerging
  score_composite: 11.0
  shared: 2
- slug: services-patterns
  name: Services Patterns
  description: Design patterns and architectural approaches for building microservices and service-oriented applications. Modern distributed architectures rely on it to coordinate workloads across multiple nodes and regions.
  api_count: 0
  score_band: minimal
  score_composite: 2.3
  shared: 2
---
