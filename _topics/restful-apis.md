---
layout: topic
slug: restful-apis
name: RESTful APIs
kind: topic
description: Representational State Transfer (REST) is an architectural style for designing networked applications. RESTful APIs use HTTP methods to perform CRUD operations and communicate between client and server using stateless, cacheable requests with standard conventions. This collection covers RESTful API design principles, best practices, standards, tools, and the OpenAPI Specification ecosystem.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/restful-apis.png
tags:
- Architecture
- HTTP
- REST
- Web Services
- OpenAPI
- Standards
- Design
repo: https://github.com/api-evangelist/restful-apis
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/restful-apis/blob/main/security/restful-apis-domain-security.yml
- type: Website
  url: https://restfulapi.net/
- type: OpenAPI Specification
  url: https://spec.openapis.org/oas/latest.html
- type: RFC 7231 HTTP Semantics
  url: https://datatracker.ietf.org/doc/html/rfc7231
- type: Roy Fielding REST Dissertation
  url: https://www.ics.uci.edu/~fielding/pubs/dissertation/rest_arch_style.htm
- type: Richardson Maturity Model
  url: https://martinfowler.com/articles/richardsonMaturityModel.html
- type: OWASP API Security Top 10
  url: https://owasp.org/www-project-api-security/
- type: JSON API Specification
  url: https://jsonapi.org/
- type: HAL Specification
  url: https://stateless.group/hal_specification.html
- type: Swagger Tools
  url: https://swagger.io/tools/
- type: Postman REST Client
  url: https://www.postman.com/
provider_count: 35
providers:
- slug: rest
  name: REST
  description: REST (Representational State Transfer) is an architectural style for designing networked applications, defined by Roy Fielding in his 2000 doctoral dissertation. REST uses stateless communication, standard HTTP methods (GET, POST, PUT, DEL…
  api_count: 4
  score_band: emerging
  score_composite: 17.8
  shared: 4
- slug: restful-services
  name: RESTful Services
  description: Representational State Transfer (REST) services are web services built using the REST architectural style, which uses stateless HTTP communication and standard HTTP methods (GET, POST, PUT, DELETE, PATCH) to expose resources. RESTful servi…
  api_count: 5
  score_band: emerging
  score_composite: 16.9
  shared: 4
- slug: restful
  name: RESTful
  description: 'Representational State Transfer (REST) is an architectural style for designing networked applications using stateless HTTP communication and uniform interfaces. RESTful describes systems and APIs that conform to the REST constraints: clien…'
  api_count: 5
  score_band: emerging
  score_composite: 14.6
  shared: 3
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 2
- slug: cvent-event-cloud
  name: Cvent Event Cloud
  description: 'Cvent Event Cloud is the event management product line of the Cvent Platform. It supports the full event lifecycle: event creation, registration, marketing, agenda and session management, mobile event apps, onsite check-in, virtual and hyb…'
  api_count: 2
  score_band: exemplar
  score_composite: 71.9
  shared: 2
- slug: 0xarchive
  name: 0xArchive
  description: 0xArchive is a replayable market-data archive for two decentralised perpetuals venues, Hyperliquid and Lighter, delivered as one REST API, one WebSocket API that carries both live subscriptions and historical replay on a single connection,…
  api_count: 2
  score_band: exemplar
  score_composite: 71.6
  shared: 2
- slug: aws-api-gateway
  name: Amazon API Gateway
  description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, a…
  api_count: 13
  score_band: exemplar
  score_composite: 70.0
  shared: 2
- slug: stayingapi
  name: StayingAPI
  description: Unified accommodation-data API returning live search, availability, price, cross-OTA price comparison, and normalized reviews across Airbnb, Booking.com, Vrbo, and Google Hotels via a single normalized JSON schema, so one integration cover…
  api_count: 1
  score_band: strong
  score_composite: 64.8
  shared: 2
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 2
- slug: apiverve
  name: APIVerve
  description: An agent-native API marketplace exposing 300+ (367+ enumerated) ready-made REST APIs behind a single API key with a uniform JSON envelope. Offers REST, an alpha GraphQL gateway, OpenAPI + Postman contracts, a self-hosted apis.json, an llms…
  api_count: 1
  score_band: strong
  score_composite: 60.8
  shared: 2
- slug: autodesk
  name: Autodesk
  description: Autodesk is a global leader in design, engineering, and entertainment software, providing cloud-connected platform APIs through Autodesk Platform Services (APS). APS APIs enable developers to build applications that access design data, aut…
  api_count: 12
  score_band: strong
  score_composite: 59.9
  shared: 2
- slug: odds-api
  name: Odds API
  description: OpenAPI-first sports betting odds API (odds-api.net) providing bookmaker odds, odds comparison, arbitrage, positive EV, line movement, and racing/sports coverage via REST plus SSE and WebSocket streaming. Agent-native with an MCP server, l…
  api_count: 1
  score_band: strong
  score_composite: 58.8
  shared: 2
- slug: reefapi
  name: ReefAPI
  description: ReefAPI is a unified web-data gateway that fronts 183 production data engines - Amazon, Zillow, Reddit, Trustpilot, LinkedIn Jobs, Indeed, Google Maps, Booking.com, StockX, YouTube and more - behind ONE JSON contract, ONE API key and ONE s…
  api_count: 1
  score_band: strong
  score_composite: 57.7
  shared: 2
- slug: netcracker
  name: Netcracker
  description: Netcracker Technology is a Waltham, Massachusetts-based BSS/OSS and digital business software vendor and a wholly owned subsidiary of NEC Corporation. It sells cloud BSS, digital commerce and monetization, convergent charging, service and…
  api_count: 4
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: mediacaption-api
  name: MediaCaption API
  description: A credit-billed REST API for retrieving public YouTube transcripts, with single and bulk transcript jobs, job-level webhooks, and AI transcription/translation capabilities. Backed by a public OpenAPI 3.1 contract with bearer/X-API-Key auth…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: blng
  name: Blng
  description: BLNG is an AI-driven creative suite for the jewelry industry, giving jewelers, designers, brands, and retailers tools to explore, refine, and present designs fast and without compromise. Its Design product turns sketches, doodles, photos,…
  api_count: 4
  score_band: developing
  score_composite: 50.7
  shared: 2
- slug: etsi
  name: ETSI
  description: ETSI, the European Telecommunications Standards Institute, is a not-for-profit standards development organisation headquartered in Sophia Antipolis, France, and one of only three bodies officially recognised by the European Union as a Euro…
  api_count: 24
  score_band: developing
  score_composite: 50.2
  shared: 2
- slug: autocad
  name: AutoCAD
  description: APIs for Autodesk AutoCAD, providing programmatic access to CAD design, drawing, and automation capabilities through Autodesk Platform Services (APS, formerly Forge) and desktop development environments including AutoLISP, ObjectARX, .NET,…
  api_count: 6
  score_band: developing
  score_composite: 47.8
  shared: 2
- slug: 3gpp
  name: 3GPP
  description: 3GPP (the 3rd Generation Partnership Project) is the global standards partnership that writes the technical specifications for mobile networks — GSM, UMTS, LTE, 5G and the ongoing 6G work — through seven regional Organizational Partners (A…
  api_count: 116
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: vehicles-dev-api
  name: Vehicles.dev
  description: Automotive vehicle data platform offering a live REST API for VIN decoding, specifications, recalls, market valuation, depreciation, ownership costs, listings, price history, and photos, backed by federal sources (NHTSA vPIC, NHTSA recalls…
  api_count: 1
  score_band: developing
  score_composite: 42.7
  shared: 2
- slug: adsmom-inc
  name: Adsmom
  description: Adsmom (SIA Adsmom) is a Latvia-based AI-powered ad intelligence platform that indexes 200M+ ads from Meta, TikTok and Google, decodes them with AI, and gives brands, agencies and research teams a clear read on what competitors are running…
  api_count: 1
  score_band: developing
  score_composite: 41.6
  shared: 2
- slug: ruby
  name: Ruby Programming Language and Popular API Gems
  description: 'A profile of the Ruby programming language ecosystem from an API perspective: the language and its standard library HTTP surface (Net::HTTP), the rubygems.org package registry and its public v1/v2 REST API, Bundler, RBS type signatures, po…'
  api_count: 1
  score_band: developing
  score_composite: 40.8
  shared: 2
- slug: acelab
  name: Acelab
  description: Acelab is a Brooklyn, New York software company building Material Hub, an AI-assisted material intelligence platform for the architecture, engineering, construction and owner (AECO) market. Founded in 2019 by architecture graduates from Ha…
  api_count: 2
  score_band: thin
  score_composite: 38.2
  shared: 2
- slug: apache-cxf
  name: Apache CXF
  description: Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first…
  api_count: 1
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: snaptrude
  name: Snaptrude
  description: Snaptrude is a cloud-native design platform for architecture and interior design that unifies sketching, real-time collaboration, AI-assisted programming, and BIM into a single browser-based tool. Snaptrude 3.0 offers four integrated modes…
  api_count: 1
  score_band: thin
  score_composite: 28.0
  shared: 2
- slug: camara-project
  name: CAMARA Project
  description: CAMARA is the Telco Global API Alliance — an open-source project hosted by the Linux Foundation that defines, builds, and tests a unified set of network APIs across the world's mobile operators. Working alongside the GSMA Open Gateway comm…
  api_count: 24
  score_band: emerging
  score_composite: 24.5
  shared: 2
- slug: dropwizard
  name: Dropwizard
  description: Dropwizard is a Java framework for developing ops-friendly, high-performance RESTful web services, pulling together stable, mature libraries from the Java ecosystem into a simple, lightweight package.
  api_count: 1
  score_band: emerging
  score_composite: 24.2
  shared: 2
- slug: rayon
  name: Rayon
  description: Rayon is an AI-powered CAD (computer-aided design) platform built for interior designers and architects, positioned as a modern, browser-based alternative to legacy tools like AutoCAD and SketchUp. It provides professional 2D drafting and…
  api_count: 0
  score_band: emerging
  score_composite: 21.7
  shared: 2
- slug: curl
  name: cURL
  description: cURL is a command-line tool and library for transferring data with URLs. Originally released in 1997 by Daniel Stenberg, cURL is the de facto standard tool used by developers for testing, automating, and scripting interactions with HTTP, H…
  api_count: 2
  score_band: emerging
  score_composite: 20.8
  shared: 2
- slug: nmfta
  name: NMFTA
  description: The National Motor Freight Traffic Association (NMFTA) is the nonprofit membership body that has set the standards for North American freight since 1956, and through its Digital Standards Development Council (DSDC) it publishes that indust…
  api_count: 6
  score_band: emerging
  score_composite: 18.4
  shared: 2
---
