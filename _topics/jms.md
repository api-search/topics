---
layout: topic
slug: jms
name: JMS
kind: topic
description: Java Message Service (JMS), now known as Jakarta Messaging, is a Java API that allows applications to create, send, receive, and read messages. It defines a common enterprise messaging API for loosely coupled, reliable, and asynchronous communication between distributed application components. Current release is Jakarta Messaging 3.1 (Jakarta EE 10).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/jms.png
tags:
- Enterprise Integration
- Jakarta EE
- Java
- JMS
- Messaging
- Standards
repo: https://github.com/api-evangelist/jms
api_count: 1
apis:
- name: Jakarta Messaging
  description: The Jakarta Messaging (formerly Java Message Service) specification for enterprise messaging and asynchronous communication between distributed components. Defines point-to-point queues and publish/subscribe topics with guaranteed delivery…
  url: https://jakarta.ee/specifications/messaging/
links:
- type: CodeOfConduct
  url: https://github.com/jakartaee/.github/blob/master/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/jakartaee/messaging/blob/master/CONTRIBUTING.md
- type: DomainSecurity
  url: https://github.com/api-evangelist/jms/blob/main/security/jms-domain-security.yml
- type: Website
  url: https://jakarta.ee/specifications/messaging/
- type: Documentation
  url: https://jakarta.ee/specifications/messaging/3.1/
- type: GitHubOrganization
  url: https://github.com/jakartaee
- type: Issues
  url: https://github.com/jakartaee/messaging/issues
provider_count: 21
providers:
- slug: apache-activemq
  name: Apache ActiveMQ
  description: Apache ActiveMQ is an open-source, high-performance message broker written in Java, developed by the Apache Software Foundation. It implements the Jakarta Messaging (JMS) API and supports multiple messaging protocols including AMQP, STOMP,…
  api_count: 4
  score_band: thin
  score_composite: 36.7
  shared: 3
- slug: spring-integration
  name: Spring Integration
  description: Spring Integration extends the Spring programming model to support enterprise integration patterns (EIP), providing lightweight messaging within Spring-based applications and integration with external systems via declarative adapters. It s…
  api_count: 2
  score_band: thin
  score_composite: 33.4
  shared: 3
- slug: jakarta-ee
  name: Jakarta EE
  description: Jakarta EE is the open source successor to Java EE, providing a set of specifications for enterprise Java development. Jakarta EE is developed under the Eclipse Foundation and includes specifications for web services, messaging, persistenc…
  api_count: 6
  score_band: emerging
  score_composite: 13.4
  shared: 3
- slug: eclipse
  name: Eclipse Foundation
  description: The Eclipse Foundation is a non-profit (Belgian AISBL) that provides a global community of individuals and organizations with a mature, scalable and business-friendly environment for open source software collaboration and innovation. It is…
  api_count: 19
  score_band: strong
  score_composite: 63.6
  shared: 2
- slug: reliance-jio
  name: Reliance Jio
  description: Reliance Jio Infocomm, the telecom arm of Jio Platforms Limited and Reliance Industries, is India's largest mobile network operator, serving roughly half a billion subscribers on an all-IP 4G/5G network from its home market of India, along…
  api_count: 6
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: totogi
  name: Totogi
  description: Totogi LLC is an Austin, Texas based vertical AI and BSS software vendor that builds telecom operator software natively on the public cloud (AWS). Its two products are the Totogi Ontology (formerly BSS Magic), a machine-readable semantic l…
  api_count: 2
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: telia
  name: Telia Company
  description: Telia Company is the Nordic and Baltic telecommunications group headquartered in Solna, Sweden, operating mobile and fixed networks in Sweden, Finland, Norway, Denmark, Lithuania, Latvia and Estonia, plus a global carrier and IoT business.…
  api_count: 1
  score_band: developing
  score_composite: 46.8
  shared: 2
- slug: asyncapi
  name: AsyncAPI
  description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, valid…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: mavenir
  name: Mavenir
  description: Mavenir is a US-headquartered (Richardson, Texas) cloud-native telecom network software vendor that builds the software operators run rather than a network or a developer platform of its own. Its portfolio spans Open RAN and vRAN (MAVair),…
  api_count: 2
  score_band: thin
  score_composite: 36.5
  shared: 2
- slug: axon-framework
  name: Axon Framework
  description: Axon Framework is a Java framework for building event-driven microservices using CQRS (Command Query Responsibility Segregation) and event sourcing patterns, providing the building blocks to implement scalable and maintainable distributed…
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 2
- slug: apache-camel
  name: Apache Camel
  description: Apache Camel is an open-source integration framework developed by the Apache Software Foundation that implements Enterprise Integration Patterns (EIPs) for connecting systems, services, and data. It provides a domain-specific language (DSL…
  api_count: 4
  score_band: thin
  score_composite: 32.1
  shared: 2
- slug: spring-cloud-stream
  name: Spring Cloud Stream
  description: Spring Cloud Stream is a framework for building event-driven microservices connected with shared messaging systems. It provides a flexible programming model built on established Spring idioms and best practices, including support for persi…
  api_count: 3
  score_band: thin
  score_composite: 30.2
  shared: 2
- slug: open-liberty
  name: Open Liberty
  description: Open Liberty is a lightweight, open source Java application server from IBM for building cloud-native microservices and applications with full support for Jakarta EE and MicroProfile.
  api_count: 1
  score_band: thin
  score_composite: 28.6
  shared: 2
- slug: apache-servicemix
  name: Apache ServiceMix
  description: Apache ServiceMix is a flexible, open-source integration container that unifies the features and functionality of Apache ActiveMQ, Camel, CXF, and Karaf into a powerful runtime for building enterprise integration solutions.
  api_count: 1
  score_band: thin
  score_composite: 26.8
  shared: 2
- slug: bean-validation
  name: Bean Validation
  description: Jakarta Bean Validation (formerly Java Bean Validation / JSR 380) is a Java specification providing a standardized constraint model and API for validating Java beans using annotations. It defines built-in constraints (@NotNull, @Size, @Min…
  api_count: 3
  score_band: emerging
  score_composite: 22.2
  shared: 2
- slug: json-processing
  name: JSON Processing
  description: JSON Processing (JSON-P) is a Java API for parsing, generating, transforming, and querying JSON messages. Standardized as Jakarta JSON Processing, it provides both an object model API and a streaming API for working with JSON data in Java…
  api_count: 1
  score_band: emerging
  score_composite: 12.2
  shared: 2
- slug: jsr-303
  name: JSR-303
  description: JSR-303 (Bean Validation) is a Java specification that defines a metadata model and API for JavaBean validation. It provides a standard way to define validation constraints on Java objects using annotations, enabling developers to enforce…
  api_count: 1
  score_band: emerging
  score_composite: 12.2
  shared: 2
- slug: jpa
  name: JPA
  description: Jakarta Persistence (formerly Java Persistence API / JPA) defines a Java specification and binding layer for the management of persistence and object-relational mapping in Java environments. It provides a standardized ORM framework that en…
  api_count: 1
  score_band: minimal
  score_composite: 10.7
  shared: 2
- slug: jsf
  name: JSF
  description: Jakarta Faces (formerly JavaServer Faces / JSF) is an MVC framework for building component-based user interfaces for Java web applications. It simplifies the development of web UIs through a component-driven approach with managed beans, an…
  api_count: 1
  score_band: minimal
  score_composite: 10.7
  shared: 2
- slug: json-binding
  name: JSON Binding
  description: Jakarta JSON Binding (JSON-B) defines a standard binding layer for converting Java objects to and from JSON documents. It specifies a default mapping algorithm for serializing and deserializing existing Java classes to and from JSON, while…
  api_count: 1
  score_band: minimal
  score_composite: 10.7
  shared: 2
- slug: java-ee
  name: Java EE
  description: Java EE (Java Platform, Enterprise Edition) was a set of specifications extending the Java SE platform with enterprise features such as distributed computing and web services. In 2017 Oracle transferred Java EE to the Eclipse Foundation, w…
  api_count: 0
  score_band: minimal
  score_composite: 4.1
  shared: 2
---
