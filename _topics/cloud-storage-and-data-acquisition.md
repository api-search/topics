---
layout: topic
slug: cloud-storage-and-data-acquisition
name: Cloud Storage and Data Acquisition
kind: topic
description: Cloud Storage and Data Acquisition is a topic profile in the API Evangelist Network covering APIs and tooling for ingesting, moving, and persisting bulk and streaming data into cloud-resident storage. It groups object storage services, data-lake foundations, managed ingestion pipelines, change-data-capture connectors, transfer appliances, and data-broker APIs that provide source material for cloud-storage workloads. The topic is intended as an entry point for developers and architects evaluating how data lands in cloud storage from on-premises systems, SaaS APIs, IoT devices, public data sources, and partner exchanges.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cloud-storage-and-data-acquisition.png
tags:
- Bulk Transfer
- Change Data Capture
- Cloud Storage
- Data Acquisition
- Data Ingestion
- Data Lake
- ETL
- Object Storage
- Pipelines
- Streaming
repo: https://github.com/api-evangelist/cloud-storage-and-data-acquisition
api_count: 6
apis:
- name: Object Storage Surface
  description: The object-storage surface includes Amazon S3, Google Cloud Storage, and Azure Blob Storage REST APIs. These APIs provide the canonical landing zone for cloud data acquisition and are the most common targets for ingestion pipelines.
  url: https://aws.amazon.com/s3/
- name: Streaming Ingest Surface
  description: The streaming-ingest surface covers Amazon Kinesis Data Streams, Google Cloud Pub/Sub, and Azure Event Hubs. These services ingest high-volume event streams and make them durable for downstream landing into object storage and analytics sys…
  url: https://aws.amazon.com/kinesis/data-streams/
- name: Managed Ingestion Pipelines
  description: Managed ingestion pipelines such as AWS Glue, Google Cloud Dataflow, and Azure Data Factory expose REST APIs for orchestrating extract-transform-load and extract-load-transform jobs that land source data in cloud storage.
  url: https://aws.amazon.com/glue/
- name: Change Data Capture Connectors
  description: Change Data Capture connectors (Debezium, AWS DMS, Fivetran, Striim) replicate row-level changes from operational databases to cloud storage and warehouses, providing a low-latency feed for analytics and data-lake hydration.
  url: https://debezium.io/
- name: Bulk Transfer Services
  description: Bulk transfer services (AWS DataSync and Snow family, Google Storage Transfer Service, Azure Data Box) move large datasets from on-premises and edge locations into cloud storage over network or via offline appliances.
  url: https://aws.amazon.com/datasync/
- name: Data Marketplaces
  description: Data marketplaces and open-data registries expose third-party datasets through REST APIs, subscription delivery, and shared buckets. They are an increasingly common acquisition channel for cloud-storage data lakes.
  url: https://aws.amazon.com/data-exchange/
links:
- type: TrustCenter
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition/blob/main/security/cloud-storage-and-data-acquisition-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition/blob/main/security/cloud-storage-and-data-acquisition-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition/blob/main/security/cloud-storage-and-data-acquisition-domain-security.yml
- type: Topic
  url: https://apievangelist.com/topics/cloud-storage-and-data-acquisition/
- type: API Evangelist
  url: https://apievangelist.com/
- type: Network
  url: https://network.apievangelist.com/
- type: GitHub
  url: https://github.com/api-evangelist
- type: JSONLD
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition/blob/main/json-ld/cloud-storage-and-data-acquisition-context.jsonld
- type: Spectral
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition/blob/main/rules/cloud-storage-and-data-acquisition-rules.yml
provider_count: 48
providers:
- slug: nexla
  name: Nexla
  description: Nexla is an enterprise data integration and AI-data platform, founded in 2016 and headquartered in San Mateo, California. Its core abstraction is the Nexset — a logical, schema-aware, bi-directionally usable data product that Nexla generat…
  api_count: 4
  score_band: strong
  score_composite: 64.1
  shared: 3
- slug: artie
  name: Artie
  description: Artie is a real-time data replication platform that streams database changes to cloud data warehouses and lakehouses with sub-minute latency and exactly-once delivery. It captures change data (CDC) from sources such as PostgreSQL, MySQL, M…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 3
- slug: popsink
  name: Popsink
  description: Popsink is a real-time data replication and change data capture (CDC) platform that continuously moves data out of mission-critical and legacy systems into cloud data platforms with low latency and minimal production impact. It offers a br…
  api_count: 2
  score_band: developing
  score_composite: 41.2
  shared: 3
- slug: estuary-flow
  name: Estuary Flow
  description: Estuary Flow is a real-time data movement and transformation platform combining streaming infrastructure, a runtime, and an open-source ecosystem of connectors. It supports change data capture (CDC), SaaS integration, database replication,…
  api_count: 4
  score_band: thin
  score_composite: 36.1
  shared: 3
- slug: streamkap
  name: Streamkap
  description: Streamkap is a real-time streaming ETL and change data capture (CDC) platform built on Apache Kafka and Apache Flink. It streams data from operational databases (PostgreSQL, MySQL, MongoDB, SQL Server, Oracle) to cloud warehouses, lakes, a…
  api_count: 1
  score_band: thin
  score_composite: 26.5
  shared: 3
- slug: amazon-s3
  name: Amazon S3
  description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.
  api_count: 2
  score_band: exemplar
  score_composite: 69.1
  shared: 2
- slug: gcp-cloud-storage
  name: Google Cloud Storage
  description: Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.
  api_count: 1
  score_band: strong
  score_composite: 63.2
  shared: 2
- slug: microsoft-azure-data-factory
  name: Azure Data Factory
  description: Azure Data Factory is Microsoft's cloud-based data integration service, orchestrating and automating the movement and transformation of data across ETL and ELT workloads that span cloud and on-premises stores. Its public interface is the M…
  api_count: 1
  score_band: strong
  score_composite: 62.0
  shared: 2
- slug: microsoft-azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 1
  score_band: strong
  score_composite: 59.1
  shared: 2
- slug: feldera
  name: Feldera
  description: Feldera is an incremental compute engine for running complex SQL data pipelines in real time. Rather than reprocessing entire datasets, it updates materialized views proportionally to the changes in the input data, delivering low-latency,…
  api_count: 1
  score_band: strong
  score_composite: 57.8
  shared: 2
- slug: lucidlink
  name: LucidLink
  description: LucidLink Corp. is a cloud file-streaming company whose product is a "filespace" — a shared, cloud-native filesystem that mounts on macOS, Windows, Linux, iOS and Android and streams only the bytes an application actually asks for, so dist…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: amazon-redshift
  name: Amazon Redshift
  description: Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.
  api_count: 1
  score_band: strong
  score_composite: 56.0
  shared: 2
- slug: archil
  name: Archil
  description: Archil is the cloud filesystem for AI. It turns an existing object-storage bucket (Amazon S3, Google Cloud Storage, Cloudflare R2, Azure Blob, MinIO, Wasabi, Backblaze B2, DigitalOcean Spaces) into an unlimited, POSIX-compatible local disk…
  api_count: 1
  score_band: strong
  score_composite: 55.6
  shared: 2
- slug: pure-storage
  name: Pure Storage
  description: Pure Storage is an American publicly traded technology company specializing in all-flash data storage hardware and software products. The company provides enterprise data storage platforms including FlashArray, FlashBlade, and Pure1 fleet…
  api_count: 3
  score_band: developing
  score_composite: 54.1
  shared: 2
- slug: delta-lake
  name: Delta Lake
  description: Delta Lake is a graduated project of the Linux Foundation AI & Data Foundation providing an open source storage framework for building Lakehouse architectures. Originally contributed by Databricks, it adds reliability, quality, and perform…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 2
- slug: warpstream
  name: WarpStream
  description: WarpStream is a diskless, Apache Kafka-compatible data streaming platform built directly on top of cloud object storage such as S3, GCP, and Azure. It eliminates the need for local disks, brokers to rebalance, and ZooKeeper, delivering Kaf…
  api_count: 1
  score_band: developing
  score_composite: 48.0
  shared: 2
- slug: google-cloud-datastream
  name: Google Cloud Datastream
  description: Google Cloud Datastream is a serverless change data capture (CDC) and replication service that allows you to synchronize data across heterogeneous databases, storage systems, and applications reliably and with minimal latency.
  api_count: 1
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: backblaze
  name: Backblaze
  description: Backblaze is a cloud storage and data backup provider offering B2 Cloud Storage - a low-cost, S3-compatible object storage service. Backblaze provides both a native B2 API and an S3-compatible API, enabling developers to build applications…
  api_count: 7
  score_band: developing
  score_composite: 47.0
  shared: 2
- slug: striim
  name: Striim
  description: Unified data integration and streaming platform offering change data capture (CDC), real-time streaming analytics, and data validation. Exposes a token-authenticated REST API (WActionStore queries, system health, Application Management) co…
  api_count: 6
  score_band: developing
  score_composite: 47.0
  shared: 2
- slug: flatfile
  name: Flatfile
  description: Flatfile is a data exchange platform that helps teams import, transform, validate, and collaborate on file-based data. The Flatfile API provides programmatic access to spaces, workbooks, sheets, records, files, documents, jobs, events, age…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: weld
  name: Weld
  description: Weld is a programmable data-infrastructure platform for moving and transforming data. It runs near real-time ELT/ETL pipelines from 300+ prebuilt connectors, log-based Change Data Capture (CDC), SQL-based data transformations with lineage…
  api_count: 1
  score_band: developing
  score_composite: 44.7
  shared: 2
- slug: cloudflare-r2
  name: Cloudflare R2
  description: Cloudflare R2 is S3-compatible object storage with zero egress fees. It provides both an S3-compatible REST API and a Cloudflare API for managing buckets, objects, and storage policies at global scale. R2 offers a generous free tier includ…
  api_count: 2
  score_band: developing
  score_composite: 43.9
  shared: 2
- slug: unstructured
  name: Unstructured
  description: Unstructured is a document parsing and pre-processing platform that provides a REST API for ingesting PDFs, HTML, DOCX, images, and more than 50 other file formats, transforming them into clean structured JSON chunks ready for RAG pipeline…
  api_count: 2
  score_band: developing
  score_composite: 43.8
  shared: 2
- slug: eon
  name: Eon
  description: Eon is a next-generation cloud backup and data-protection platform that turns cloud backups into live, searchable, strategic assets across AWS, Google Cloud, and Azure. It provides agentless backup, cloud backup posture management, ransomw…
  api_count: 1
  score_band: developing
  score_composite: 43.7
  shared: 2
- slug: talend
  name: Talend
  description: Talend (now part of Qlik) provides data integration, quality, and API management capabilities through cloud-native APIs for ETL, data pipelines, and application integration. The Qlik Talend Cloud platform exposes REST APIs for orchestratin…
  api_count: 2
  score_band: developing
  score_composite: 42.8
  shared: 2
- slug: filebase
  name: Filebase
  description: Filebase is an S3-compatible object storage and IPFS pinning platform that combines familiar cloud storage APIs with decentralized, blockchain-backed infrastructure. Developers can store, manage, and pin files to IPFS using standard S3 too…
  api_count: 4
  score_band: developing
  score_composite: 40.4
  shared: 2
- slug: apache-nifi
  name: Apache NiFi
  description: Apache NiFi is a dataflow management system designed to automate the flow of data between systems. It provides a web-based user interface for designing, controlling, and monitoring data flows with real-time operational control, data proven…
  api_count: 1
  score_band: developing
  score_composite: 40.3
  shared: 2
- slug: sequin-io
  name: Sequin
  description: Sequin is an open-source Postgres change data capture (CDC) engine that streams Postgres rows and changes to streams, queues, and search indexes - Kafka, SQS, SNS, Kinesis, Redis, NATS, RabbitMQ, Elasticsearch, Typesense, GCP Pub/Sub, Azur…
  api_count: 1
  score_band: thin
  score_composite: 38.1
  shared: 2
- slug: bytark
  name: ByteArk
  description: ByteArk is a Thailand-based video streaming and content delivery platform founded in 2012 and headquartered in Bangkok. It provides video-on-demand (ByteArk Stream), live streaming (Fleet / Teatro), an S3-compatible object storage service,…
  api_count: 1
  score_band: thin
  score_composite: 37.7
  shared: 2
- slug: infoworks
  name: Infoworks
  description: Infoworks is an Enterprise Data Operations and Orchestration (EDO2) platform that automates data onboarding, preparation and operationalization onto Databricks, Snowflake, BigQuery, Synapse and Apache Spark. Unlike a multi-tenant SaaS, Inf…
  api_count: 1
  score_band: thin
  score_composite: 37.7
  shared: 2
---
