---
layout: topic
slug: jdbc
name: JDBC
kind: topic
description: JDBC (Java Database Connectivity) is a Java API that defines how a client may access a database. It provides methods for querying and updating data in a database and is oriented towards relational databases. JDBC is part of the Java Standard Edition platform via the java.sql module (with enterprise extensions in javax.sql), and every JDBC driver implements the Driver interface to enable database connectivity in Java applications.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/jdbc.png
tags:
- Database
- Java
- JDBC
- SQL
- Standards
- java.sql
repo: https://github.com/api-evangelist/jdbc
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/jdbc/blob/main/security/jdbc-domain-security.yml
- type: Website
  url: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/module-summary.html
- type: Documentation
  url: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/java/sql/package-summary.html
- type: EnterpriseExtension
  url: https://docs.oracle.com/en/java/javase/21/docs/api/java.sql/javax/sql/package-summary.html
provider_count: 48
providers:
- slug: apache-derby
  name: Apache Derby
  description: Apache Derby is an open-source relational database implemented entirely in Java, formerly governed by the Apache Software Foundation (retired October 2025). It provides a small-footprint (~3.5MB) database engine with full SQL support, JDBC…
  api_count: 1
  score_band: thin
  score_composite: 28.4
  shared: 4
- slug: cdata
  name: CData
  description: CData Software is a leading provider of data access and connectivity solutions. Our standards-based connectors streamline data access and insulate customers from the complexities of integrating with on-premise or cloud databases, SaaS, API…
  api_count: 9
  score_band: exemplar
  score_composite: 84.4
  shared: 2
- slug: clickhouse
  name: ClickHouse
  description: ClickHouse is a fast open-source column-oriented database management system that enables real-time analytical reporting using SQL. ClickHouse exposes multiple interfaces - an HTTP interface for SQL queries, native TCP, MySQL and PostgreSQL…
  api_count: 2
  score_band: exemplar
  score_composite: 73.5
  shared: 2
- slug: cockroach-labs
  name: Cockroach Labs
  description: Cockroach Labs is the New York-based software company that builds CockroachDB, a cloud-native, distributed, PostgreSQL-compatible SQL database. CockroachDB is offered as Cockroach Labs' fully managed cloud service (Basic, Standard, and Adv…
  api_count: 3
  score_band: exemplar
  score_composite: 72.0
  shared: 2
- slug: eclipse
  name: Eclipse Foundation
  description: The Eclipse Foundation is a non-profit (Belgian AISBL) that provides a global community of individuals and organizations with a mature, scalable and business-friendly environment for open source software collaboration and innovation. It is…
  api_count: 19
  score_band: strong
  score_composite: 63.6
  shared: 2
- slug: microsoft-sql-server
  name: Microsoft SQL Server
  description: A relational database management system developed by Microsoft for enterprise-scale data management and business intelligence solutions.
  api_count: 30
  score_band: strong
  score_composite: 62.7
  shared: 2
- slug: singlestore
  name: SingleStore
  description: SingleStore is a cloud-native distributed SQL database designed for real-time analytics and mixed workloads. It offers a management API for provisioning and managing cloud workspaces, and a data API for executing SQL statements over HTTP w…
  api_count: 2
  score_band: strong
  score_composite: 59.8
  shared: 2
- slug: teradata
  name: Teradata
  description: Teradata provides enterprise analytics and data management solutions. The Teradata VantageCloud platform delivers connected multi-cloud data analytics with capabilities for data warehousing, advanced analytics, and machine learning at scal…
  api_count: 1
  score_band: strong
  score_composite: 59.4
  shared: 2
- slug: yugabyte
  name: Yugabyte
  description: Yugabyte is the company behind YugabyteDB, an open source (Apache 2.0), PostgreSQL-compatible distributed SQL database built for cloud-native and mission-critical applications. It pairs PostgreSQL wire-compatibility (the YSQL API) and a Ca…
  api_count: 73
  score_band: strong
  score_composite: 59.1
  shared: 2
- slug: amuncore
  name: AmunCore
  description: AmunCore turns a database into a secure REST API without writing a backend. You connect a database, pick tables, and endpoints go live with routing, authentication, validation, pagination, joins, errors, logs and docs already handled — the…
  api_count: 2
  score_band: strong
  score_composite: 54.8
  shared: 2
- slug: vividcortex
  name: VividCortex
  description: VividCortex is a SaaS database performance monitoring platform, now part of SolarWinds and marketed as SolarWinds Database Performance Monitor (DPM). It uses lightweight per-host agents to capture and analyze every query executed against M…
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 2
- slug: ehrbase
  name: EHRbase
  description: EHRbase is an open source openEHR Clinical Data Repository (CDR) - a standards-based backend for storing, versioning and querying structured clinical data. It implements the official openEHR REST API (ITS-REST 1.0.2) against openEHR Refere…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: oracle-database
  name: Oracle Database
  description: APIs and interfaces for Oracle Database management, querying, and administration.
  api_count: 3
  score_band: developing
  score_composite: 50.8
  shared: 2
- slug: ocient
  name: Ocient
  description: Ocient is a Chicago-based data platform company founded in 2016 that builds OcientAIQ, a unified data platform for petabyte-scale analytics and production AI. Its Compute-Adjacent Storage Architecture (CASA) colocates NVMe storage with com…
  api_count: 1
  score_band: developing
  score_composite: 48.7
  shared: 2
- slug: google-cloud-sql
  name: Google Cloud SQL
  description: Google Cloud SQL is a fully managed relational database service that supports MySQL, PostgreSQL, and SQL Server. It handles routine database tasks such as provisioning, replication, backups, and failover, allowing developers to focus on ap…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 2
- slug: google-cloud-spanner
  name: Google Cloud Spanner
  description: Google Cloud Spanner is a fully managed, mission-critical relational database service that offers transactional consistency at global scale, automatic synchronous replication, and schemas with SQL support. It combines the benefits of relat…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 2
- slug: cloudflare-d1
  name: Cloudflare D1
  description: Cloudflare D1 is a managed, serverless SQLite database service with a REST API for querying D1 databases, executing SQL statements, listing databases, and managing database instances at the edge. D1 offers SQLite semantics, built-in Time T…
  api_count: 1
  score_band: developing
  score_composite: 44.8
  shared: 2
- slug: cockroachdb
  name: CockroachDB
  description: CockroachDB is a distributed SQL database with strong consistency, PostgreSQL compatibility, and a managed cloud offering. The Cloud API manages cluster lifecycle; the Cluster API exposes per-node operational state for monitoring and troub…
  api_count: 2
  score_band: developing
  score_composite: 44.4
  shared: 2
- slug: microsoft-azure-sql-database
  name: Azure SQL Database
  description: Azure SQL Database is a fully managed relational database service built on the SQL Server engine with built-in intelligence, high availability, and elastic scaling.
  api_count: 5
  score_band: developing
  score_composite: 42.5
  shared: 2
- slug: sybase
  name: Sybase
  description: A collection of APIs and resources for Sybase database systems.
  api_count: 1
  score_band: developing
  score_composite: 42.4
  shared: 2
- slug: kinetica
  name: Kinetica
  description: Kinetica is a GPU-accelerated, real-time analytical database that unifies relational (SQL), vector, graph, geospatial, time-series and OLAP workloads in a single query engine, aimed at applications needing millisecond-latency analytics ove…
  api_count: 3
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: apache-doris
  name: Apache Doris
  description: Apache Doris is a high-performance, real-time analytical database based on MPP (Massively Parallel Processing) architecture, governed by the Apache Software Foundation. It provides MySQL-protocol-compatible SQL queries, sub-second query la…
  api_count: 1
  score_band: developing
  score_composite: 41.0
  shared: 2
- slug: crate-io
  name: Crate Io
  description: Crate.io is the company behind CrateDB, a distributed SQL database engineered for real-time analytics on large volumes of operational data. CrateDB unifies time-series, JSON/document, full-text search, vector, geospatial, and relational da…
  api_count: 2
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: risingwave
  name: RisingWave
  description: RisingWave is a distributed SQL streaming platform that continuously ingests event streams from Kafka, Kinesis, and other sources, transforms them using PostgreSQL-compatible SQL, and serves low-latency results through incrementally mainta…
  api_count: 6
  score_band: developing
  score_composite: 39.5
  shared: 2
- slug: apache-druid
  name: Apache Druid
  description: Apache Druid is a high-performance, real-time analytics database governed by the Apache Software Foundation, designed for fast slice-and-dice OLAP queries on event-time data. It features a distributed, column-oriented storage engine with a…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 2
- slug: smartmind
  name: SmartMind
  description: SmartMind AI Inc. is a South Korean AI company (Techstars 2020, Seoul) building ontology-based enterprise AI. Its current products are Qurify — a natural-language data analysis platform that answers questions without SQL by combining struc…
  api_count: 1
  score_band: thin
  score_composite: 36.5
  shared: 2
- slug: dolthub
  name: DoltHub
  description: DoltHub is the hosting platform for Dolt, the version-controlled SQL database - "Git for data". DoltHub hosts public and private Dolt databases and exposes an HTTP API (the DoltHub SQL API) for running read and write SQL queries against an…
  api_count: 1
  score_band: thin
  score_composite: 33.4
  shared: 2
- slug: questdb
  name: QuestDB
  description: QuestDB is a high-performance open-source time-series database. It exposes three programmatic surfaces — an HTTP REST API for SQL queries and CSV import/export, the InfluxDB Line Protocol (ILP) over TCP and HTTP for high-throughput ingesti…
  api_count: 1
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: yunqi
  name: Yunqi (ClickZetta / Singdata Lakehouse)
  description: Yunqi (云器科技, English brands ClickZetta and Singdata) is a cloud-native AI Lakehouse company that unifies structured, semi-structured, and unstructured data on Apache Iceberg behind a single vectorized SQL engine. Its proprietary Generic In…
  api_count: 0
  score_band: thin
  score_composite: 31.9
  shared: 2
- slug: mysql
  name: MySQL
  description: MySQL is the world's most popular open-source relational database management system. This index covers the developer-facing APIs and interfaces for MySQL, including the MySQL REST Service, X DevAPI, and native connectors.
  api_count: 1
  score_band: thin
  score_composite: 31.7
  shared: 2
---
