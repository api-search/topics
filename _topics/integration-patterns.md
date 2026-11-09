---
layout: topic
slug: integration-patterns
name: Integration Patterns
kind: concept
description: Integration Patterns are design patterns and best practices for integrating different software systems and applications, including messaging, data transformation, and service orchestration approaches. Enterprise Integration Patterns (EIP), as cataloged by Gregor Hohpe and Bobby Woolf, provide a technology-independent vocabulary and visual notation harvested from proven solutions to recurring integration problems, organized into Messaging Channels, Message Construction, Message Routing, Message Transformation, Messaging Endpoints, and System Management.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/integration-patterns.png
tags:
- Asynchronous Messaging
- Choreography
- Design Patterns
- EAI
- EIP
- Enterprise Architecture
- Enterprise Integration Patterns
- Event-Driven Architecture
- Messaging
- Message Routing
- Microservices
- Orchestration
- Software Architecture
- System Integration
area: microservices
repo: https://github.com/api-evangelist/integration-patterns
api_count: 0
apis: []
links:
- type: Website
  url: https://www.enterpriseintegrationpatterns.com/
- type: Reference
  url: https://www.enterpriseintegrationpatterns.com/
- type: Reference
  url: https://www.enterpriseintegrationpatterns.com/patterns/messaging/
- type: Book
  url: https://www.enterpriseintegrationpatterns.com/eaipatterns.html
- type: Author
  url: https://www.enterpriseintegrationpatterns.com/gregor.html
- type: Reference
  url: https://en.wikipedia.org/wiki/Enterprise_Integration_Patterns
- type: Rules
  url: https://github.com/api-evangelist/integration-patterns/blob/main/rules/integration-patterns-rules.yml
provider_count: 9
providers:
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: polyapi
  name: PolyAPI
  description: Poly, built using cutting-edge AI and Kubernetes-native technology, accelerates development and simplifies the operation of integrations, orchestrations, and microservices with TypeScript, Python, Java, and C.
  api_count: 1
  score_band: developing
  score_composite: 45.9
  shared: 2
- slug: fyno
  name: Fyno
  description: Fyno is a notification routing and orchestration platform that provides a single unified REST API for sending and managing notifications across 10+ communication channels including email, SMS, push, WhatsApp, in-app, RCS, voice, and iMessa…
  api_count: 1
  score_band: developing
  score_composite: 41.4
  shared: 2
- slug: restate
  name: Restate
  description: Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: conductor-oss
  name: Conductor OSS
  description: Conductor OSS is the Netflix-founded, Orkes-stewarded open source workflow and agentic AI orchestration platform. It provides a durable, event-driven workflow engine for coordinating microservices, long-running tasks, human approvals, and…
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 33.1
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
- slug: services-patterns
  name: Services Patterns
  description: Design patterns and architectural approaches for building microservices and service-oriented applications. Modern distributed architectures rely on it to coordinate workloads across multiple nodes and regions.
  api_count: 0
  score_band: minimal
  score_composite: 2.3
  shared: 2
---
