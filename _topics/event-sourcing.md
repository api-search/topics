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
provider_count: 3
providers:
- slug: kurrent
  name: Kurrent
  description: Kurrent — formerly Event Store Ltd — builds KurrentDB, an event-native database purpose-built to store, process and deliver application state changes as an immutable, append-only log of events. Where a traditional CRUD database overwrites…
  api_count: 1
  score_band: strong
  score_composite: 56.3
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 2
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: emerging
  score_composite: 21.5
  shared: 2
---
