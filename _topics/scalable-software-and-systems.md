---
layout: topic
slug: scalable-software-and-systems
name: Scalable Software and Systems
kind: topic
description: A topic collection exploring the APIs, design patterns, frameworks, and platforms that enable scalable software and systems engineering. Covers architectural patterns such as CQRS, event sourcing, saga, MACH architecture, API-first design, and modular monoliths, as well as the tooling ecosystems that support building maintainable, high-scale software. Relevant to software architects, platform teams, and senior engineers building enterprise-grade distributed systems.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scalable-software-and-systems.png
tags:
- API-First
- Architecture Patterns
- CQRS
- Distributed Systems
- Enterprise
- Event-Driven
- Microservices
- Scalable Architecture
- Software Engineering
- Systems Design
repo: https://github.com/api-evangelist/scalable-software-and-systems
api_count: 9
apis:
- name: Backstage Software Catalog API
  description: Backstage by Spotify provides a software catalog API and developer portal platform for managing all software components, services, websites, and infrastructure at scale. Its catalog API enables registering, tracking, and discovering softwa…
  url: https://backstage.io/docs/features/software-catalog/software-catalog-api
- name: CloudEvents API
  description: CloudEvents is a CNCF specification for describing event data in a common way. It defines a core data model and HTTP, AMQP, MQTT, and Kafka bindings enabling interoperable event-driven system design across cloud providers and middleware.
  url: https://cloudevents.io/
- name: Apache Kafka Admin API
  description: Apache Kafka's Admin REST API enables creating and managing topics, partitions, consumer groups, and cluster configurations for high-throughput event streaming pipelines used in scalable, event-driven architectures.
  url: https://kafka.apache.org/documentation/
- name: NATS Management API
  description: NATS is a lightweight, high-performance messaging system for distributed applications. Its management API provides monitoring, subject inspection, and JetStream (persistent streams) management for building scalable event-driven systems.
  url: https://docs.nats.io/
- name: Dapr API
  description: Dapr (Distributed Application Runtime) provides building block APIs for service invocation, pub/sub messaging, state management, bindings, actors, and distributed tracing. Abstracts away infrastructure complexity for portable, scalable sof…
  url: https://docs.dapr.io/reference/api/
- name: OpenTelemetry API
  description: OpenTelemetry provides vendor-neutral APIs, SDKs, and instrumentation for generating traces, metrics, and logs. Essential for observability in scalable distributed software systems, enabling performance analysis and root cause diagnosis.
  url: https://opentelemetry.io/docs/
- name: Argo CD API
  description: Argo CD provides a declarative GitOps continuous delivery API for Kubernetes applications. Enables teams to manage application deployments at scale using Git as the source of truth for system state.
  url: https://argo-cd.readthedocs.io/en/stable/developer-guide/api-docs/
- name: Scalable Software and Systems Entities API
  description: The Entities API from Scalable Software and Systems — 6 operation(s) for entities.
  url: https://backstage.io/docs/features/software-catalog/software-catalog-api
- name: Scalable Software and Systems Locations API
  description: The Locations API from Scalable Software and Systems — 2 operation(s) for locations.
  url: https://backstage.io/docs/features/software-catalog/software-catalog-api
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/agentic-access/scalable-software-and-systems-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/security/scalable-software-and-systems-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/authentication/scalable-software-and-systems-authentication.yml
- type: Guide
  url: https://microservices.io/patterns/data/cqrs.html
- type: Guide
  url: https://microservices.io/patterns/data/event-sourcing.html
- type: Guide
  url: https://microservices.io/patterns/data/saga.html
- type: Guide
  url: https://www.cncf.io/projects/
- type: Guide
  url: https://12factor.net/
- type: JSONSchema
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-schema/scalable-software-and-systems-event-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-structure/scalable-software-and-systems-event-structure.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/json-ld/scalable-software-and-systems-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/vocabulary/scalable-software-and-systems-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-order-placed-event-example.json
- type: Examples
  url: https://github.com/api-evangelist/scalable-software-and-systems/blob/main/examples/scalable-software-and-systems-temporal-workflow-example.json
provider_count: 34
providers:
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 3
- slug: eventuate
  name: Eventuate
  description: Eventuate is a platform for developing transactional microservices using event sourcing and CQRS patterns, providing frameworks for managing distributed data consistency across services without two-phase commit.
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 3
- slug: microservice-architecture-patterns
  name: Micro-Service Architecture Patterns
  description: Design patterns and best practices for building distributed systems using microservices architecture, including service decomposition, communication patterns, data management, and deployment strategies.
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 3
- slug: microservices-design-patterns
  name: Microservices Design Patterns
  description: Architectural patterns and best practices for designing, building, and maintaining microservices-based applications, including patterns for communication, data management, deployment, and resilience.
  api_count: 0
  score_band: minimal
  score_composite: 4.1
  shared: 3
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 80.4
  shared: 2
- slug: apigee
  name: Apigee
  description: Apigee is Google Cloud's native API management platform for building, managing, and securing APIs across any use case, environment, or scale. It provides API proxies, security, rate limiting, quotas, analytics, monetization, and developer…
  api_count: 5
  score_band: strong
  score_composite: 65.8
  shared: 2
- slug: amazon-sqs
  name: Amazon SQS
  description: Amazon Simple Queue Service (SQS) is a fully managed message queuing service that enables you to decouple and scale microservices, distributed systems, and serverless applications.
  api_count: 1
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: microsoft-azure-integration-services
  name: Microsoft Azure Integration Services
  description: Microsoft Azure Integration Services is a collection of cloud-based integration capabilities that connect applications, data, and processes across cloud and on-premises environments. It includes API Management, Logic Apps, Service Bus, Eve…
  api_count: 6
  score_band: developing
  score_composite: 48.7
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
  score_composite: 47.2
  shared: 2
- slug: spring
  name: Spring Framework
  description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, mes…
  api_count: 3
  score_band: developing
  score_composite: 46.2
  shared: 2
- slug: microsoft-azure-service-fabric
  name: Azure Service Fabric
  description: Azure Service Fabric REST API provides management of microservices clusters, applications, and services. It supports creating and scaling clusters, deploying applications, managing partitions and replicas, and monitoring cluster health for…
  api_count: 2
  score_band: developing
  score_composite: 43.6
  shared: 2
- slug: dapr
  name: Dapr
  description: Dapr (Distributed Application Runtime) is a portable, event-driven runtime that makes it easy for developers to build resilient, stateless, and stateful applications that run on the cloud and edge. It provides building block APIs for state…
  api_count: 13
  score_band: developing
  score_composite: 42.5
  shared: 2
- slug: restate
  name: Restate
  description: Restate is a low-latency durable execution engine for building resilient applications that tolerate all infrastructure faults. It provides durable execution for workflows, event-driven handlers, and stateful orchestration of microservices…
  api_count: 1
  score_band: developing
  score_composite: 39.5
  shared: 2
- slug: spring-cloud-config
  name: Spring Cloud Config
  description: Spring Cloud Config provides server-side and client-side support for externalized configuration in a distributed system. It offers a central place to manage external properties for applications across all environments, backed by Git, SVN,…
  api_count: 1
  score_band: thin
  score_composite: 38.8
  shared: 2
- slug: service-fabric
  name: Service Fabric
  description: Azure Service Fabric is an open-source distributed systems platform for packaging, deploying, and managing scalable and reliable microservices and containers. Service Fabric powers many Microsoft Azure core services, and thousands of servi…
  api_count: 1
  score_band: thin
  score_composite: 37.1
  shared: 2
- slug: poolside-ai
  name: Poolside
  description: Poolside is an AI foundation model lab (founded 2023 by former GitHub CTO Jason Warner and Eiso Kant) building open-weight foundation models - the Laguna family - purpose-built for agentic software engineering. Poolside does not run a shar…
  api_count: 1
  score_band: thin
  score_composite: 36.5
  shared: 2
- slug: spring-boot-3
  name: Spring Boot 3
  description: Spring Boot 3 is the major release of the opinionated Spring application framework, now built on Spring Framework 6, requiring Java 17 baseline and Jakarta EE 10. It delivers native image support via GraalVM, improved observability with Mi…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: conductor-oss
  name: Conductor OSS
  description: Conductor OSS is the Netflix-founded, Orkes-stewarded open source workflow and agentic AI orchestration platform. It provides a durable, event-driven workflow engine for coordinating microservices, long-running tasks, human approvals, and…
  api_count: 1
  score_band: thin
  score_composite: 34.6
  shared: 2
- slug: akka
  name: Akka
  description: Akka is a toolkit and runtime for building highly concurrent, distributed, and resilient message-driven applications on the JVM using the actor model for Java and Scala. Maintained by Lightbend, Akka provides a comprehensive set of librari…
  api_count: 1
  score_band: thin
  score_composite: 34.4
  shared: 2
- slug: diagrid
  name: Diagrid
  description: Diagrid is the execution layer for production AI, built by the creators of the open source Dapr and KEDA projects. Its managed platform, Diagrid Catalyst, gives AI agents, workflows, and MCP servers durable execution (applications resume f…
  api_count: 0
  score_band: thin
  score_composite: 33.0
  shared: 2
- slug: vert-x
  name: Vert.x
  description: Eclipse Vert.x is a toolkit for building reactive applications on the JVM, providing support for multiple languages including Java, JavaScript, Groovy, Ruby, and Kotlin with an event-driven, non-blocking architecture. Part of the Eclipse F…
  api_count: 7
  score_band: thin
  score_composite: 31.4
  shared: 2
- slug: spring-cloud-stream
  name: Spring Cloud Stream
  description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persi…
  api_count: 3
  score_band: thin
  score_composite: 30.7
  shared: 2
- slug: kafka
  name: Apache Kafka
  description: Apache Kafka is a distributed event streaming platform for high-performance data pipelines, streaming analytics, data integration, and mission-critical applications. It provides high-throughput, fault-tolerant, publish-subscribe messaging.
  api_count: 5
  score_band: thin
  score_composite: 29.3
  shared: 2
- slug: architecture-pattern
  name: Architecture Pattern
  description: Architecture Patterns provide reusable solutions to commonly occurring software and system design problems. They offer proven templates for organizing code, components, and interactions across distributed systems, microservices, cloud-nati…
  api_count: 1
  score_band: thin
  score_composite: 28.5
  shared: 2
- slug: jboss
  name: JBoss
  description: JBoss is a division of Red Hat providing open source middleware and application server technologies for enterprise Java workloads. The JBoss product portfolio includes JBoss EAP (Enterprise Application Platform), the WildFly community appl…
  api_count: 5
  score_band: thin
  score_composite: 26.7
  shared: 2
- slug: netflix-conductor
  name: Netflix Conductor
  description: Conductor is a microservices orchestration platform originally created by Netflix, providing a workflow engine for coordinating and managing complex distributed processes across multiple services with built-in retries, error handling, and…
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: go-kit
  name: Go Kit
  description: Go Kit is a programming toolkit for building microservices in Go, emphasizing domain-driven design, transport-agnostic service definitions, and best practices for distributed systems.
  api_count: 1
  score_band: emerging
  score_composite: 17.0
  shared: 2
- slug: go-micro
  name: Go Micro
  description: Go Micro is a distributed systems framework for building microservices in Go, providing service discovery, load balancing, message encoding, RPC, and async messaging out of the box.
  api_count: 1
  score_band: emerging
  score_composite: 14.5
  shared: 2
- slug: restful-microservices
  name: RESTful Microservices
  description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services that communicate via REST APIs using HTTP methods and standard web protocols. This collection covers RESTful micros…
  api_count: 0
  score_band: minimal
  score_composite: 8.9
  shared: 2
---
