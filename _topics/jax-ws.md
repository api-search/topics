---
layout: topic
slug: jax-ws
name: JAX-WS
kind: topic
description: JAX-WS (Java API for XML Web Services) is a Java standard for building and consuming SOAP-based XML web services. Originally specified as JSR 224 under the Java Community Process, JAX-WS is now part of Jakarta EE as Jakarta XML Web Services. It defines annotations and runtime APIs that allow developers to expose Java methods as SOAP web service operations and to generate Java client stubs from WSDL documents. Reference implementations include the Eclipse Metro project and Apache CXF.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/jax-ws.png
tags:
- Jakarta EE
- Java
- JAX-WS
- SOAP
- Standards
- Web Services
- XML
repo: https://github.com/api-evangelist/jax-ws
api_count: 3
apis:
- name: Jakarta XML Web Services (JAX-WS)
  description: The Jakarta EE specification for XML web services, formerly JSR 224 JAX-WS. Defines annotations such as @WebService, @WebMethod, and @WebParam, as well as runtime APIs for SOAP-based web service providers and clients.
  url: https://jakarta.ee/specifications/xml-web-services/
- name: Eclipse Metro
  description: Eclipse Metro is the reference implementation of Jakarta XML Web Services (JAX-WS), providing a high-performance, extensible SOAP web services stack for Java applications.
  url: https://projects.eclipse.org/projects/ee4j.metro
- name: Apache CXF
  description: Apache CXF is an open source services framework that supports JAX-WS and JAX-RS, providing tooling and runtime support for SOAP, REST, and other web service protocols.
  url: https://cxf.apache.org/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/jax-ws/blob/main/security/jax-ws-domain-security.yml
- type: Website
  url: https://jakarta.ee/specifications/xml-web-services/
- type: Documentation
  url: https://jakarta.ee/specifications/xml-web-services/
- type: GitHubOrganization
  url: https://github.com/jakartaee
provider_count: 19
providers:
- slug: apache-cxf
  name: Apache CXF
  description: Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first…
  api_count: 1
  score_band: thin
  score_composite: 34.9
  shared: 4
- slug: soap
  name: SOAP
  description: SOAP (Simple Object Access Protocol) is an XML-based messaging protocol for exchanging structured information in web services, standardized by W3C as SOAP 1.2 (2003). It provides a platform-independent, language-neutral framework for web s…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
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
- slug: acord
  name: ACORD
  description: ACORD is the global standards-setting body for the insurance industry, publishing the data standards that insurers, reinsurers, brokers, MGAs and software vendors use to exchange policy, claims, party, underwriting, accounting and settleme…
  api_count: 6
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: opentravel-alliance
  name: OpenTravel Alliance
  description: The OpenTravel Alliance is a volunteer, non-profit travel technology standards body headquartered in Melbourne, Florida, United States. Since 1999 it has published the OpenTravel Specification — the OTA 1.0 XML message suite (releases 2001…
  api_count: 8
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: open-liberty
  name: Open Liberty
  description: Open Liberty is a lightweight, open source Java application server from IBM for building cloud-native microservices and applications with full support for Jakarta EE and MicroProfile.
  api_count: 1
  score_band: thin
  score_composite: 28.6
  shared: 2
- slug: dropwizard
  name: Dropwizard
  description: Dropwizard is a Java framework for developing ops-friendly, high-performance RESTful web services, pulling together stable, mature libraries from the Java ecosystem into a simple, lightweight package.
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: apache-ant
  name: Apache Ant
  description: Apache Ant is a Java-based build tool and library developed by the Apache Software Foundation, used to automate software build processes. It uses XML-based build files to define targets and tasks for compiling, testing, packaging, and depl…
  api_count: 2
  score_band: emerging
  score_composite: 23.9
  shared: 2
- slug: bean-validation
  name: Bean Validation
  description: Jakarta Bean Validation (formerly Java Bean Validation / JSR 380) is a Java specification providing a standardized constraint model and API for validating Java beans using annotations. It defines built-in constraints (@NotNull, @Size, @Min…
  api_count: 3
  score_band: emerging
  score_composite: 22.2
  shared: 2
- slug: soa
  name: SOA
  description: Service-Oriented Architecture (SOA) is an architectural style for building software applications as a collection of loosely coupled, interoperable services. Each service encapsulates a specific business capability and communicates with oth…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
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
- slug: mismo
  name: MISMO
  description: MISMO — the Mortgage Industry Standards Maintenance Organization — is the standards development body for US real estate finance, founded in 1999 and a not-for-profit wholly owned subsidiary of the Mortgage Bankers Association since 2004. I…
  api_count: 0
  score_band: minimal
  score_composite: 6.7
  shared: 2
- slug: resware
  name: ResWare
  description: ResWare is customizable title and escrow production software for real estate closings, originally built by Adeptive Software Corporation and acquired by Qualia Labs in December 2020 (now shipping as ResWare 10 within the Qualia ecosystem).…
  api_count: 7
  score_band: minimal
  score_composite: 6.7
  shared: 2
- slug: java-ee
  name: Java EE
  description: Java EE (Java Platform, Enterprise Edition) was a set of specifications extending the Java SE platform with enterprise features such as distributed computing and web services. In 2017 Oracle transferred Java EE to the Eclipse Foundation, w…
  api_count: 0
  score_band: minimal
  score_composite: 4.1
  shared: 2
---
