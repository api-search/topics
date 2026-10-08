---
layout: topic
slug: lakehouse-architecture
name: Lakehouse Architecture
kind: topic
description: Lakehouse Architecture is a data architecture paradigm that combines the best features of data lakes and data warehouses, providing ACID transactions, schema enforcement, and governance on low-cost storage with support for both business intelligence and machine learning workloads.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/lakehouse-architecture.png
tags:
- Analytics
- Big Data
- Data Architecture
- Data Lake
- Data Warehouse
repo: https://github.com/api-evangelist/lakehouse-architecture
api_count: 1
apis:
- name: Lakehouse Architecture
  description: Resources and reference implementations for the Lakehouse Architecture data platform paradigm.
  url: https://www.databricks.com/glossary/data-lakehouse
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/lakehouse-architecture/blob/main/security/lakehouse-architecture-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/lakehouse-architecture/blob/main/security/lakehouse-architecture-domain-security.yml
- type: Website
  url: https://www.databricks.com/glossary/data-lakehouse
- type: Integrations
  url: https://www.databricks.com/partners
provider_count: 65
providers:
- slug: amazon-redshift
  name: Amazon Redshift
  description: Amazon Redshift is a fast, fully managed cloud data warehouse that makes it simple and cost-effective to analyze all your data using standard SQL and your existing Business Intelligence (BI) tools.
  api_count: 2
  score_band: strong
  score_composite: 58.8
  shared: 4
- slug: treasure-data
  name: Treasure Data
  description: Treasure Data — rebranded Treasure AI in April 2026 — is an enterprise customer data platform that unifies first-party customer data and activates it across marketing, service and AI agent workloads. It publishes eight OpenAPI descriptions…
  api_count: 7
  score_band: exemplar
  score_composite: 76.2
  shared: 3
- slug: microsoft-azure-synapse-analytics
  name: Azure Synapse Analytics
  description: Azure Synapse Analytics is an enterprise analytics service that accelerates time to insight across data warehouses and big data systems. It brings together the best of SQL technologies used in enterprise data warehousing, Spark technologie…
  api_count: 30
  score_band: strong
  score_composite: 59.2
  shared: 3
- slug: ocient
  name: Ocient
  description: Ocient is a Chicago-based data platform company founded in 2016 that builds OcientAIQ, a unified data platform for petabyte-scale analytics and production AI. Its Compute-Adjacent Storage Architecture (CASA) colocates NVMe storage with com…
  api_count: 1
  score_band: developing
  score_composite: 48.7
  shared: 3
- slug: google-bigquery
  name: Google BigQuery
  description: Google BigQuery is a fully managed, serverless data warehouse that enables scalable analysis over petabytes of data using SQL.
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 3
- slug: qubole
  name: Qubole
  description: Qubole is a cloud-native data lake platform (now part of Idera) that lets teams run multiple open-source data-processing engines - Apache Spark, Presto, Hive, Hadoop, and Airflow - together in a single, cost-optimized, self-managing enviro…
  api_count: 1
  score_band: thin
  score_composite: 38.4
  shared: 3
- slug: microsoft-azure-data-lake
  name: Azure Data Lake Storage
  description: Azure Data Lake Storage Gen2 REST API provides a file system interface for big data analytics workloads on Azure Blob Storage. It supports creating file systems, managing directories and files with hierarchical namespace, setting ACLs, and…
  api_count: 1
  score_band: thin
  score_composite: 34.8
  shared: 3
- slug: etleap
  name: Etleap
  description: Etleap is a managed ETL and data-integration platform that streamlines data ingestion, transformation, and observability so data teams can build cloud data warehouses and lakes with minimal engineering effort. Originally built as an "autop…
  api_count: 1
  score_band: thin
  score_composite: 29.2
  shared: 3
- slug: sqream-technologies
  name: SQream Technologies
  description: SQream Technologies is an Israeli data and analytics company, founded in 2010 in Tel Aviv, that builds SQreamDB — a GPU-accelerated, SQL-compliant analytics database for petabyte-scale workloads on NVIDIA hardware — alongside AISQream for…
  api_count: 0
  score_band: thin
  score_composite: 28.7
  shared: 3
- slug: netezza
  name: Netezza
  description: IBM Netezza Performance Server is a cloud-native data warehouse and analytics appliance for running large-scale SQL analytics and in-database machine learning on structured data. Originally a standalone data-warehouse appliance vendor acqu…
  api_count: 0
  score_band: emerging
  score_composite: 17.7
  shared: 3
- slug: amiato
  name: Amiato
  description: Amiato was a Palo Alto, California big-data startup founded in 2011 by Nathan Binkert and Mehul A. Shah, originally incubated at Y Combinator in 2012 under the name Nou Data. Amiato built a real-time analytics pipeline around its Schema-li…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 3
- slug: bityota
  name: BitYota
  description: BitYota was a Data-Warehouse-as-a-Service (DWaaS) startup founded around 2011 in Santa Clara, California, offering a SaaS analytics data warehouse that ran on top of Amazon Web Services and Rackspace infrastructure and natively queried sem…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 3
- slug: cazena
  name: Cazena
  description: Cazena was a Waltham, Massachusetts-based enterprise software company, founded in 2014, that delivered a fully-managed SaaS data platform — a "Big Data as a Service" cloud data lake that let enterprises run analytics, machine learning, and…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: snowflake
  name: Snowflake
  description: Snowflake is a cloud-based data platform delivering data warehousing, data lakes, data engineering, data science and data application development as a single managed service across AWS, Azure and Google Cloud. Its developer surface is a 47…
  api_count: 84
  score_band: exemplar
  score_composite: 82.7
  shared: 2
- slug: sigma-computing
  name: Sigma Computing
  description: Sigma Computing is a warehouse-first analytics and business-application platform. Instead of extracting data into its own store, Sigma queries the customer's cloud data warehouse live — Snowflake, Databricks, BigQuery, Redshift, Amazon Ath…
  api_count: 3
  score_band: exemplar
  score_composite: 71.9
  shared: 2
- slug: cloudera
  name: Cloudera
  description: Cloudera is a hybrid data platform company offering the Cloudera Data Platform (CDP) for data engineering, data warehousing, machine learning, streaming, and operational data. The platform exposes multiple REST APIs including the CDP Publi…
  api_count: 38
  score_band: exemplar
  score_composite: 70.3
  shared: 2
- slug: textql
  name: TextQL
  description: TextQL is an enterprise AI data platform built around Ana, an AI data scientist that connects to a company's warehouses, databases, BI tools and SaaS APIs and answers questions in plain language. Ana writes SQL, runs Python in a managed gV…
  api_count: 15
  score_band: exemplar
  score_composite: 69.5
  shared: 2
- slug: monte-carlo
  name: Monte Carlo
  description: Monte Carlo is a data and AI observability platform that monitors data warehouses, lakes, and pipelines for freshness, volume, schema, and quality anomalies, helping data teams detect, resolve, and prevent data downtime across Snowflake, D…
  api_count: 1
  score_band: exemplar
  score_composite: 67.4
  shared: 2
- slug: databricks
  name: Databricks
  description: Databricks provides a unified Data + AI Platform that runs analytical and operational workloads on a single open, governed foundation. The platform enables enterprises to build business intelligence and AI applications, stream and analyze…
  api_count: 1
  score_band: strong
  score_composite: 65.3
  shared: 2
- slug: microsoft-azure-databricks
  name: Azure Databricks
  description: Azure Databricks is an Apache Spark-based analytics platform optimized for Microsoft Azure. It provides a collaborative workspace for data engineers, data scientists, and analysts to work together on big data and machine learning workloads.
  api_count: 1
  score_band: strong
  score_composite: 63.1
  shared: 2
- slug: amazon-lake-formation
  name: Amazon Lake Formation
  description: AWS Lake Formation is a service that makes it easy to set up a secure data lake in days, providing centralized governance and security for data stored in Amazon S3 and other AWS data stores with fine-grained access control.
  api_count: 1
  score_band: strong
  score_composite: 60.4
  shared: 2
- slug: funnel
  name: Funnel
  description: Funnel (funnel.io) is a marketing intelligence and marketing data hub that helps agencies and brands become more data-driven. It connects to hundreds of advertising, analytics, CRM, and social data platforms, then automatically collects, n…
  api_count: 3
  score_band: strong
  score_composite: 58.5
  shared: 2
- slug: supermetrics
  name: Supermetrics
  description: Supermetrics is a marketing intelligence platform that automates the pipeline of marketing and advertising data from 100+ sources (Google Ads, Facebook/Meta Ads, TikTok, Google Analytics, LinkedIn Ads, and more) into spreadsheets, BI tools…
  api_count: 1
  score_band: strong
  score_composite: 57.2
  shared: 2
- slug: amazon-emr
  name: Amazon EMR
  description: Amazon EMR is a cloud big data platform for running large-scale distributed data processing jobs, interactive SQL queries, and machine learning applications using open-source analytics frameworks such as Apache Spark, Apache Hive, Apache H…
  api_count: 1
  score_band: strong
  score_composite: 55.0
  shared: 2
- slug: beaconstac
  name: Beaconstac
  description: Beaconstac (now Uniqode) is a B2B SaaS platform for creating, customizing, and tracking dynamic QR Codes and Digital Business Cards at scale, connecting physical touchpoints to measurable digital experiences for 50,000+ brands. Its REST AP…
  api_count: 1
  score_band: strong
  score_composite: 54.9
  shared: 2
- slug: definite
  name: Definite
  description: Definite is an all-in-one, AI-native data platform that consolidates data integration, warehouse storage, a semantic layer, BI dashboards, and AI agents into a single product. It ships 500+ managed data connectors, a DuckDB / DuckLake lake…
  api_count: 1
  score_band: developing
  score_composite: 52.8
  shared: 2
- slug: kinesis
  name: AWS Kinesis
  description: Amazon Kinesis is a family of fully managed AWS services for collecting, processing, and analyzing real-time streaming data. The family includes Kinesis Data Streams for scalable record ingestion, Amazon Data Firehose (formerly Kinesis Dat…
  api_count: 4
  score_band: developing
  score_composite: 48.7
  shared: 2
- slug: apache-iceberg
  name: Apache Iceberg
  description: Apache Iceberg is an open table format for large analytic datasets that provides ACID transactions, schema evolution, hidden partitioning, and time travel. It works with Spark, Flink, Hive, Presto, Trino, DuckDB, ClickHouse, and many more…
  api_count: 1
  score_band: developing
  score_composite: 46.8
  shared: 2
- slug: ryft
  name: Ryft
  description: Ryft is the intelligent Apache Iceberg management platform - a data lakehouse optimization layer that continuously monitors, manages, and optimizes Iceberg tables across query engines and clouds. It provides automated table compaction, sna…
  api_count: 1
  score_band: developing
  score_composite: 42.5
  shared: 2
- slug: altinity
  name: Altinity
  description: Altinity is the enterprise provider for open-source ClickHouse, the real-time analytical database. It builds and operates Altinity.Cloud, a fully managed ClickHouse service available on AWS, GCP, Azure and Hetzner, plus a bring-your-own-cl…
  api_count: 1
  score_band: developing
  score_composite: 40.8
  shared: 2
---
