---
layout: topic
slug: data-warehouse-schemas
name: Data Warehouse Schemas
kind: topic
description: Data Warehouse Schemas is the landscape of analytical schema patterns used to organize fact and dimension data for business intelligence and reporting. It spans star, snowflake, and galaxy schemas, the Kimball dimensional modeling methodology, the Inmon Corporate Information Factory, Data Vault 2.0, and modern lakehouse table formats like Delta Lake, Apache Iceberg, and Apache Hudi.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/data-warehouse-schemas.png
tags:
- Analytics
- Business Intelligence
- Data Warehouse Schemas
- Data Warehousing
- Database Design
- Dimensional Modeling
repo: https://github.com/api-evangelist/data-warehouse-schemas
api_count: 0
apis: []
links:
- type: Reference
  url: https://en.wikipedia.org/wiki/Data_warehouse#Schemas
- type: Reference
  url: https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/
- type: Reference
  url: https://en.wikipedia.org/wiki/Star_schema
- type: Reference
  url: https://en.wikipedia.org/wiki/Snowflake_schema
- type: Reference
  url: https://en.wikipedia.org/wiki/Fact_constellation
- type: Reference
  url: https://datavaultalliance.com/
- type: Reference
  url: https://www.amazon.com/dp/0470174420
- type: Tools
  url: https://delta.io/
- type: Tools
  url: https://iceberg.apache.org/
- type: Tools
  url: https://hudi.apache.org/
- type: Tools
  url: https://docs.getdbt.com/
- type: Platform
  url: https://www.snowflake.com/
- type: Platform
  url: https://cloud.google.com/bigquery
- type: Platform
  url: https://www.databricks.com/
- type: Vocabulary
  url: https://github.com/api-evangelist/data-warehouse-schemas/blob/main/vocabulary/data-warehouse-schemas-vocabulary.yml
provider_count: 109
providers:
- slug: power-bi
  name: Power BI
  description: Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end users to cr…
  api_count: 1
  score_band: exemplar
  score_composite: 72.7
  shared: 2
- slug: qliksense
  name: Qlik Sense
  description: 'Qlik Sense and Qlik Cloud from Qlik Parent, Inc. — a business intelligence, data integration and AI analytics platform. Qlik publishes one of the broadest machine-readable API surfaces in the analytics market: 78 OpenAPI 3.0.0 documents co…'
  api_count: 78
  score_band: exemplar
  score_composite: 69.7
  shared: 2
- slug: sigma-computing
  name: Sigma Computing
  description: Sigma Computing is a warehouse-first analytics and business-application platform. Instead of extracting data into its own store, Sigma queries the customer's cloud data warehouse live — Snowflake, Databricks, BigQuery, Redshift, Amazon Ath…
  api_count: 3
  score_band: exemplar
  score_composite: 68.8
  shared: 2
- slug: textql
  name: TextQL
  description: TextQL is an enterprise AI data platform built around Ana, an AI data scientist that connects to a company's warehouses, databases, BI tools and SaaS APIs and answers questions in plain language. Ana writes SQL, runs Python in a managed gV…
  api_count: 15
  score_band: exemplar
  score_composite: 67.2
  shared: 2
- slug: adobe-analytics
  name: Adobe Analytics
  description: Adobe Analytics provides real-time analytics and detailed segmentation capabilities across all marketing channels, enabling organizations to discover high-value audiences and power customer intelligence.
  api_count: 11
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: visier
  name: Visier
  description: Visier is a workforce and people analytics platform that consolidates HR, talent, compensation, and operational data into a purpose-built people data model, then exposes that model for analysis, planning, and AI-assisted question answering…
  api_count: 9
  score_band: strong
  score_composite: 61.3
  shared: 2
- slug: bloomberg
  name: Bloomberg
  description: Bloomberg delivers business and markets news, data, analysis, and video to the world, featuring stories from Businessweek and Bloomberg News. Bloomberg provides a suite of developer APIs including BLPAPI, Server API, and the Hypermedia API…
  api_count: 1
  score_band: strong
  score_composite: 61.1
  shared: 2
- slug: aifordatabase
  name: AI for Database
  description: AI for Database is a natural-language data layer for operational databases, built by Wavicle.tech. It connects read-only to PostgreSQL, MySQL, MariaDB, SQL Server, MongoDB, SQLite and Google Sheets, translates plain-English questions into…
  api_count: 2
  score_band: strong
  score_composite: 60.3
  shared: 2
- slug: omni
  name: Omni
  description: Omni is an AI-powered business intelligence and embedded analytics platform that turns a governed semantic model into a trusted source of truth for people and AI agents. It connects to warehouses like Snowflake, BigQuery, Databricks and Po…
  api_count: 1
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: thoughtspot
  name: ThoughtSpot
  description: ThoughtSpot is an agentic analytics and business intelligence platform that turns data into decisions using AI agents (Spotter), Search, automated insights, and embedded analytics. The ThoughtSpot Public REST API v2.0 exposes 191 operation…
  api_count: 1
  score_band: strong
  score_composite: 58.1
  shared: 2
- slug: amazon-quicksight
  name: Amazon QuickSight
  description: Amazon QuickSight is a scalable, serverless, embeddable, machine learning-powered business intelligence service built for the cloud that enables you to create and publish interactive dashboards.
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: google-looker-studio
  name: Google Looker Studio
  description: Google Looker Studio — which Google's own documentation now renders again as Data Studio — is Google's self-service business intelligence and data visualization platform, free to build and view reports in, with a paid Pro tier sold per use…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: funnel
  name: Funnel
  description: Funnel (funnel.io) is a marketing intelligence and marketing data hub that helps agencies and brands become more data-driven. It connects to hundreds of advertising, analytics, CRM, and social data platforms, then automatically collects, n…
  api_count: 3
  score_band: strong
  score_composite: 55.8
  shared: 2
- slug: hex
  name: Hex
  description: Hex is an AI-powered analytics platform that combines agentic notebooks, interactive data apps, and conversational self-serve analytics so teams can go from ad-hoc exploration to published, governed data apps. The Hex External API (bearer-…
  api_count: 1
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: looker-studio
  name: Looker Studio
  description: Looker Studio (formerly Google Data Studio) is a free tool that turns your data into informative, easy to read, easy to share, and fully customizable dashboards and reports. The API allows developers to programmatically manage assets, buil…
  api_count: 5
  score_band: developing
  score_composite: 53.1
  shared: 2
- slug: supermetrics
  name: Supermetrics
  description: Supermetrics is a marketing intelligence platform that automates the pipeline of marketing and advertising data from 100+ sources (Google Ads, Facebook/Meta Ads, TikTok, Google Analytics, LinkedIn Ads, and more) into spreadsheets, BI tools…
  api_count: 1
  score_band: developing
  score_composite: 53.1
  shared: 2
- slug: tableau
  name: Tableau
  description: Tableau is a visual analytics platform transforming the way we use data to solve problems—empowering people and organizations to make the most of their data.
  api_count: 1
  score_band: developing
  score_composite: 51.5
  shared: 2
- slug: looker
  name: Looker
  description: Looker is a business intelligence and data analytics platform that enables organizations to explore, analyze, and share real-time business analytics.
  api_count: 1
  score_band: developing
  score_composite: 50.7
  shared: 2
- slug: definite
  name: Definite
  description: Definite is an all-in-one, AI-native data platform that consolidates data integration, warehouse storage, a semantic layer, BI dashboards, and AI agents into a single product. It ships 500+ managed data connectors, a DuckDB / DuckLake lake…
  api_count: 1
  score_band: developing
  score_composite: 50.4
  shared: 2
- slug: sap-bi-tools
  name: SAP BI Tools
  description: Collection of SAP Business Intelligence tools and APIs for analytics, reporting, and data visualization.
  api_count: 4
  score_band: developing
  score_composite: 50.3
  shared: 2
- slug: lightdash
  name: Lightdash
  description: Lightdash is an open-source business intelligence platform built on top of dbt that connects directly to the semantic layer defined in dbt projects. It provides a REST API covering core data operations including catalog management, chart a…
  api_count: 1
  score_band: developing
  score_composite: 49.9
  shared: 2
- slug: oracle-essbase
  name: Oracle Essbase
  description: Oracle Essbase is a multi-dimensional database management system that provides a multidimensional analytical platform for business intelligence applications, financial consolidation, planning, budgeting, and forecasting.
  api_count: 1
  score_band: developing
  score_composite: 49.4
  shared: 2
- slug: tellius
  name: Tellius
  description: Tellius is an agentic analytics platform that deploys AI agents ("Kaiya") on governed enterprise data to automate root cause analysis, variance decomposition and insight delivery across structured and unstructured sources. It sits above th…
  api_count: 2
  score_band: developing
  score_composite: 49.1
  shared: 2
- slug: datorama
  name: Datorama
  description: Datorama was a cloud-based marketing intelligence and analytics platform founded in 2012 in Tel Aviv and New York. It unified marketing, advertising, and sales data from thousands of disparate sources into a single AI-powered reporting and…
  api_count: 2
  score_band: developing
  score_composite: 47.8
  shared: 2
- slug: equals
  name: Equals
  description: Equals is an AI analytics platform that builds trusted spreadsheets and dashboards for revenue operations and go-to-market teams. It connects directly to databases and SaaS tools — PostgreSQL, MySQL, BigQuery, Snowflake, Redshift, Azure SQ…
  api_count: 1
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: google-data-studio
  name: Google Data Studio
  description: Google Data Studio, now rebranded as Looker Studio, is a free data visualization and business intelligence tool from Google that transforms data into customizable, shareable dashboards and reports. It connects to a wide range of data sourc…
  api_count: 2
  score_band: developing
  score_composite: 47.2
  shared: 2
- slug: pyramid-analytics
  name: Pyramid Analytics
  description: Pyramid Analytics is a decision intelligence software company whose platform unifies data preparation, business analytics and AI-assisted insight generation in a single environment, deployed either onto the customer's own infrastructure ("…
  api_count: 2
  score_band: developing
  score_composite: 46.4
  shared: 2
- slug: minubo
  name: Minubo
  description: Minubo is a German business-intelligence platform for e-commerce and retail that integrates, models, and contextualizes commerce data — orders, products, customers, and suppliers — into AI Insights, Profit Management, reporting, and a supp…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 2
- slug: google-looker
  name: Google Looker
  description: A collection of APIs for Google Looker, a modern business intelligence and analytics platform.
  api_count: 1
  score_band: developing
  score_composite: 44.9
  shared: 2
- slug: rill-data
  name: Rill Data
  description: Rill Data builds Rill, an operational business-intelligence tool for fast, exploratory dashboards on large event and time-series data. Developers connect data sources, model last-mile transformations in SQL/YAML, define a governed metrics…
  api_count: 1
  score_band: developing
  score_composite: 44.8
  shared: 2
---
