---
layout: topic
slug: event-sourcing
name: Event Sourcing
kind: topic
description: Event sourcing is an architectural pattern where state changes are stored as a sequence of immutable events rather than just the current state. Instead of storing only the current state of data, event sourcing stores all changes as a log of events, enabling complete audit trails, temporal queries, and event-driven projections.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/event-sourcing.png
tags:
- Architecture
- CQRS
- Distributed Systems
- Event Sourcing
repo: https://github.com/api-evangelist/event-sourcing
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/event-sourcing/blob/main/security/event-sourcing-domain-security.yml
- type: Website
  url: https://martinfowler.com/eaaDev/EventSourcing.html
provider_count: 9
providers:
- slug: kurrent
  name: Kurrent
  description: Kurrent — formerly Event Store Ltd — builds KurrentDB, an event-native database purpose-built to store, process and deliver application state changes as an immutable, append-only log of events. Where a traditional CRUD database overwrites…
  api_count: 1
  score_band: developing
  score_composite: 46.7
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 2
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: emerging
  score_composite: 21.3
  shared: 2
- slug: event-driven-architecture
  name: Event-Driven Architecture
  description: Event-driven architecture (EDA) is a software architecture pattern promoting the production, detection, consumption of, and reaction to events. In this pattern, systems are designed to respond to state changes asynchronously through event…
  api_count: 0
  score_band: minimal
  score_composite: 3.9
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
- slug: pub-sub
  name: Pub/Sub
  description: A messaging pattern where publishers send messages to topics without knowledge of subscribers, and subscribers receive messages from topics they're interested in, enabling asynchronous and decoupled communication between services. Modern d…
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
