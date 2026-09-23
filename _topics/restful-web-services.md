---
layout: topic
slug: restful-web-services
name: RESTful Web Services
kind: topic
description: RESTful web services are web services built using the Representational State Transfer (REST) architectural style, using HTTP as the transport protocol with standard methods to perform CRUD operations on resources. This index covers RESTful web service design patterns, frameworks for building REST services, developer tooling, API testing tools, and best practice guidelines from across the ecosystem.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/restful-web-services.png
tags:
- Architecture
- HTTP
- REST
- Web Services
repo: https://github.com/api-evangelist/restful-web-services
api_count: 5
apis:
- name: Postman API Platform
  description: Industry-leading API development platform for building, testing, documenting, and collaborating on RESTful APIs. Includes API client, collections, environments, mock servers, and automated testing.
  url: https://www.postman.com/
- name: Swagger / OpenAPI
  description: The OpenAPI Specification (formerly Swagger) is the most widely-used standard for describing RESTful APIs. Provides tooling for API design, documentation generation, code generation, and validation.
  url: https://swagger.io/
- name: Spring Boot REST
  description: Java framework from the Spring ecosystem for building production-ready RESTful web services with embedded servers, auto-configuration, and a rich ecosystem of integrations.
  url: https://spring.io/guides/gs/rest-service/
- name: FastAPI
  description: Modern, high-performance Python web framework for building RESTful APIs based on Python type hints. Automatically generates OpenAPI documentation and supports async operations natively.
  url: https://fastapi.tiangolo.com/
- name: Express.js
  description: Minimal and flexible Node.js web application framework widely used for building RESTful APIs and web services in JavaScript and TypeScript.
  url: https://expressjs.com/
links:
- type: TrustCenter
  url: https://github.com/api-evangelist/restful-web-services/blob/main/security/restful-web-services-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/restful-web-services/blob/main/security/restful-web-services-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/restful-web-services/blob/main/security/restful-web-services-domain-security.yml
- type: Roy Fielding Dissertation
  url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm
- type: OpenAPI Specification
  url: https://spec.openapis.org/oas/latest.html
- type: RFC 7231 HTTP Semantics
  url: https://datatracker.ietf.org/doc/html/rfc7231
- type: RFC 7807 Problem Details
  url: https://datatracker.ietf.org/doc/html/rfc7807
provider_count: 9
providers:
- slug: rest
  name: REST
  description: REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DEL…
  api_count: 4
  score_band: emerging
  score_composite: 18.9
  shared: 4
- slug: restful-services
  name: RESTful Services
  description: Representational State Transfer (REST) services are web services built using the REST architectural style, which uses stateless HTTP communication and standard HTTP methods (GET, POST, PUT, DELETE, PATCH) to expose resources. RESTful servi…
  api_count: 5
  score_band: emerging
  score_composite: 17.9
  shared: 4
- slug: restful
  name: RESTful
  description: 'Representational State Transfer (REST) is an architectural style for designing networked applications using stateless HTTP communication and uniform interfaces. RESTful describes systems and APIs that conform to the REST constraints: clien…'
  api_count: 5
  score_band: emerging
  score_composite: 15.5
  shared: 3
- slug: aws-api-gateway
  name: Amazon API Gateway
  description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, a…
  api_count: 13
  score_band: exemplar
  score_composite: 68.9
  shared: 2
- slug: ruby
  name: Ruby Programming Language and Popular API Gems
  description: 'A profile of the Ruby programming language ecosystem from an API perspective: the language and its standard library HTTP surface (Net::HTTP), the rubygems.org package registry and its public v1/v2 REST API, Bundler, RBS type signatures, po…'
  api_count: 1
  score_band: developing
  score_composite: 43.1
  shared: 2
- slug: apache-cxf
  name: Apache CXF
  description: Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first…
  api_count: 1
  score_band: thin
  score_composite: 35.3
  shared: 2
- slug: dropwizard
  name: Dropwizard
  description: Dropwizard is a Java framework for developing ops-friendly, high-performance RESTful web services, pulling together stable, mature libraries from the Java ecosystem into a simple, lightweight package.
  api_count: 1
  score_band: thin
  score_composite: 27.0
  shared: 2
- slug: curl
  name: cURL
  description: cURL is a command-line tool and library for transferring data with URLs. Originally released in 1997 by Daniel Stenberg, cURL is the de facto standard tool used by developers for testing, automating, and scripting interactions with HTTP, H…
  api_count: 2
  score_band: emerging
  score_composite: 21.3
  shared: 2
- slug: restful-microservices
  name: RESTful Microservices
  description: An architectural style that structures an application as a collection of loosely coupled, independently deployable services that communicate via REST APIs using HTTP methods and standard web protocols. This collection covers RESTful micros…
  api_count: 0
  score_band: minimal
  score_composite: 8.9
  shared: 2
---
