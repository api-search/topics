---
layout: topic
slug: graph-query-language-gql
name: Graph Query Language (GQL)
kind: topic
description: GQL is an international standard query language for property graph databases, developed by ISO/IEC JTC1 SC32 WG3 to provide a declarative way to query and manipulate graph data structures. Published as ISO/IEC 39075:2024 on April 17, 2024, the standard complements SQL for graph workloads and builds on prior art including openCypher, PGQL, GSQL, and G-CORE. Effective implementation supports data-driven strategies and helps maintain data integrity and portability across graph database systems.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/graph-query-language-gql.png
tags:
- Database
- Graph Database
- ISO Standard
- Query Language
- Standards
- Property Graph
repo: https://github.com/api-evangelist/graph-query-language-gql
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/graph-query-language-gql/blob/main/security/graph-query-language-gql-domain-security.yml
- type: Portal
  url: https://www.gqlstandards.org/
- type: Documentation
  url: https://www.gqlstandards.org/
- type: Standards
  url: https://www.iso.org/standard/76120.html
- type: StandardsBody
  url: https://www.iso.org/committee/45342.html
- type: Rules
  url: https://github.com/api-evangelist/graph-query-language-gql/blob/main/graph-query-language-gql-rules.yml
provider_count: 9
providers:
- slug: amazon-neptune
  name: Amazon Neptune
  description: Amazon Neptune is a fast, reliable, fully managed graph database service that makes it easy to build and run applications that work with highly connected datasets. It supports property graph and RDF models, with multiple query languages in…
  api_count: 9
  score_band: exemplar
  score_composite: 67.8
  shared: 3
- slug: sql
  name: SQL
  description: SQL (Structured Query Language) is the ANSI/ISO standard language for managing and querying relational databases. SQL defines the interface for creating, reading, updating, and deleting data in relational database management systems (RDBMS…
  api_count: 2
  score_band: emerging
  score_composite: 15.0
  shared: 3
- slug: neo4j
  name: Neo4j
  description: Neo4j is the leading graph database platform, enabling developers to build applications powered by connected data. Their developer platform provides HTTP, Query, and Aura cloud APIs alongside official drivers for Python, Java, and JavaScri…
  api_count: 2
  score_band: strong
  score_composite: 61.3
  shared: 2
- slug: ehrbase
  name: EHRbase
  description: EHRbase is an open source openEHR Clinical Data Repository (CDR) - a standards-based backend for storing, versioning and querying structured clinical data. It implements the official openEHR REST API (ITS-REST 1.0.2) against openEHR Refere…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: arangodb
  name: ArangoDB
  description: ArangoDB (now operating as Arango) is the company behind the open-source, graph-native multi-model database of the same name, which unifies graph, document, key/value, vector and full-text search in a single core with one declarative query…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 2
- slug: edgedb
  name: EdgeDB
  description: EdgeDB (rebranded as Gel in 2025) is an open-source object-relational database built on top of PostgreSQL that combines a modern graph-relational data model with a powerful query language called EdgeQL. It provides an HTTP-based EdgeQL que…
  api_count: 3
  score_band: thin
  score_composite: 33.9
  shared: 2
- slug: gel-data
  name: Gel Data
  description: Gel Data (formerly EdgeDB Inc.) builds Gel, an open-source graph-relational database that supercharges PostgreSQL with a modern object-oriented data model, the EdgeQL query language (with full SQL and GraphQL support), a built-in migration…
  api_count: 0
  score_band: thin
  score_composite: 32.8
  shared: 2
- slug: surrealdb
  name: SurrealDB
  description: SurrealDB is a multi-model database that unifies documents, graphs, vectors, time-series, full-text search, and relational data within a single ACID transaction framework. It exposes a native HTTP REST API and supports SurrealQL, a powerfu…
  api_count: 2
  score_band: thin
  score_composite: 30.8
  shared: 2
- slug: opencypher
  name: openCypher
  description: openCypher is an open-source project that provides a standardized graph query language originally developed by Neo4j for querying property graphs. It enables developers to write expressive pattern-matching queries against graph databases,…
  api_count: 0
  score_band: minimal
  score_composite: 2.8
  shared: 2
---
