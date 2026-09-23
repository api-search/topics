---
layout: topic
slug: cqrs
name: CQRS
kind: topic
description: Command Query Responsibility Segregation (CQRS) is an architectural pattern that separates read and write operations for a data store into distinct models. Commands mutate state and produce events; queries return data optimized for the read side. CQRS is frequently combined with Event Sourcing, Domain-Driven Design (DDD), and message-based integration to scale complex domains. The pattern is most associated with Greg Young, building on Bertrand Meyer's Command-Query Separation principle, and is widely covered in writings by Martin Fowler and the Microsoft Patterns and Practices team.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cqrs.png
tags:
- Architecture
- Command Query Responsibility Segregation
- Commands
- CQRS
- Domain-Driven Design
- Event Sourcing
- Event
- Patterns
- Query
- Read Models
repo: https://github.com/api-evangelist/cqrs
api_count: 0
apis: []
links:
- type: MartinFowlerOnCQRS
  url: https://martinfowler.com/bliki/CQRS.html
- type: GregYoungOnCQRS
  url: https://gregyoung.com/blog/
- type: CQRSDocumentsByGregYoung
  url: https://cqrs.files.wordpress.com/2010/11/cqrs_documents.pdf
- type: MicrosoftCQRSPattern
  url: https://learn.microsoft.com/en-us/azure/architecture/patterns/cqrs
- type: AWSCQRSPattern
  url: https://docs.aws.amazon.com/prescriptive-guidance/latest/modernization-data-persistence/cqrs-pattern.html
- type: CommandQuerySeparation
  url: https://martinfowler.com/bliki/CommandQuerySeparation.html
- type: EventSourcingPattern
  url: https://microservices.io/patterns/data/event-sourcing.html
- type: DDDCommunity
  url: https://www.dddcommunity.org/
- type: AxonFramework
  url: https://www.axoniq.io/products/axon-framework
- type: EventStoreDB
  url: https://www.eventstore.com/
- type: NServiceBus
  url: https://particular.net/nservicebus
- type: MediatRGitHub
  url: https://github.com/jbogard/MediatR
- type: WikipediaCQRS
  url: https://en.wikipedia.org/wiki/Command%E2%80%93query_separation
provider_count: 4
providers:
- slug: kurrent
  name: Kurrent
  description: Kurrent — formerly Event Store Ltd — builds KurrentDB, an event-native database purpose-built to store, process and deliver application state changes as an immutable, append-only log of events. Where a traditional CRUD database overwrites…
  api_count: 1
  score_band: developing
  score_composite: 44.3
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: serverless-patterns
  name: Serverless Patterns
  description: A collection of serverless architectures and patterns for building applications on AWS, featuring ready-to-use templates and best practices for Lambda, API Gateway, EventBridge, and other serverless services. Cloud adoption of this technol…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
---
