---
layout: topic
slug: analytics
name: Analytics
kind: topic
description: A curated index of analytics platforms, SDKs, and open source solutions spanning the full analytics spectrum — from web and product analytics (Google Analytics, Mixpanel, Amplitude, PostHog, Plausible, Matomo, Heap) to customer data platforms (Segment, mParticle, RudderStack), mobile analytics (Firebase Analytics, Adjust, AppsFlyer, Braze), business intelligence (Looker, Tableau, Metabase, Redash), event streaming (Kafka, Kinesis), and real-time analytics infrastructure (ClickHouse, Druid, Pinot). Covers both SaaS and self-hosted, open source and commercial offerings.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/analytics.png
tags:
- Analytics
- Business Intelligence
- Customer Data Platform
- Data Pipeline
- Event Tracking
- Mobile Analytics
- Observability
- Product Analytics
- Real-Time Analytics
- Web Analytics
repo: https://github.com/api-evangelist/analytics
api_count: 0
apis: []
links:
- type: Website
  url: https://apievangelist.com
- type: JSONSchema
  url: https://github.com/api-evangelist/analytics/blob/main/json-schema/analytics-platform-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/analytics/blob/main/json-ld/analytics-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/analytics/blob/main/vocabulary/analytics-vocabulary.yaml
- type: Rules
  url: https://github.com/api-evangelist/analytics/blob/main/rules/analytics-jsonschema-spectral-rules.yml
- type: LLMsTxt
  url: https://github.com/api-evangelist/analytics/blob/main/llms/analytics-llms.txt
- type: GitHubOrganization
  url: https://github.com/api-evangelist
provider_count: 229
providers:
- slug: google-analytics-4
  name: Google Analytics 4
  description: 'Google Analytics 4 (GA4) is Google''s event-based web and app analytics platform and the successor to Universal Analytics. Its developer surface has three distinct parts: the Analytics Data API (analyticsdata.googleapis.com) for running cor…'
  api_count: 8
  score_band: strong
  score_composite: 65.3
  shared: 4
- slug: rakam
  name: rakam
  description: Rakam is a warehouse-native product analytics platform that lets business and data teams build analytics interfaces without coding, operating directly on the data warehouse (Snowflake, BigQuery, Redshift, Postgres, ClickHouse) without movi…
  api_count: 0
  score_band: emerging
  score_composite: 24.5
  shared: 4
- slug: rudderstack
  name: RudderStack
  description: RudderStack is a warehouse-native customer data platform (CDP) for developers, with open-source data plane SDKs (rudder-server) and a managed control plane. The platform exposes an HTTP Tracking (Event Stream) API for ingest, a Config Back…
  api_count: 1
  score_band: exemplar
  score_composite: 76.2
  shared: 3
- slug: swetrix
  name: Swetrix
  description: Swetrix is an open source, privacy-focused web analytics platform that provides cookieless tracking, real-time dashboards, and GDPR-compliant analytics without collecting personal data. It offers a fully-featured REST API for tracking even…
  api_count: 2
  score_band: exemplar
  score_composite: 75.9
  shared: 3
- slug: adobe-analytics
  name: Adobe Analytics
  description: Adobe Analytics provides real-time analytics and detailed segmentation capabilities across all marketing channels, enabling organizations to discover high-value audiences and power customer intelligence.
  api_count: 11
  score_band: strong
  score_composite: 65.9
  shared: 3
- slug: rybbit
  name: Rybbit
  description: Rybbit is an open-source, privacy-friendly web and product analytics platform positioned as a cookieless alternative to Google Analytics and Plausible. It ingests pageviews, custom events, autocaptured interactions, performance samples and…
  api_count: 1
  score_band: strong
  score_composite: 65.2
  shared: 3
- slug: umami
  name: Umami
  description: Umami is an open source, privacy-first web analytics platform that provides website traffic insights without cookies or personal data collection, serving as a simple and fast alternative to Google Analytics. The Umami API provides full pro…
  api_count: 7
  score_band: strong
  score_composite: 61.9
  shared: 3
- slug: plausible
  name: Plausible
  description: Plausible is an open source, privacy-friendly web analytics platform designed as a lightweight alternative to Google Analytics. It provides essential website traffic metrics without using cookies or collecting personal data, making it comp…
  api_count: 3
  score_band: strong
  score_composite: 61.8
  shared: 3
- slug: microsoft-clarity
  name: Microsoft Clarity
  description: Microsoft Clarity is a free behavioral analytics service from Microsoft that captures heatmaps, session recordings and frustration signals — rage clicks, dead clicks, excessive scroll, quickback clicks and script errors — for websites and…
  api_count: 1
  score_band: strong
  score_composite: 60.1
  shared: 3
- slug: mparticle
  name: mParticle
  description: mParticle is a customer data platform (CDP) that helps brands collect, unify, and activate customer data across mobile, web, OTT, and server sources, then forward it in real time to hundreds of analytics, marketing, and warehouse destinati…
  api_count: 3
  score_band: strong
  score_composite: 55.6
  shared: 3
- slug: freshpaint
  name: Freshpaint
  description: Freshpaint is a healthcare privacy platform and customer-data platform that collects first-party event data and governs it for HIPAA compliance before fanning it out to 100+ marketing, analytics, and data destinations. Its server-side HTTP…
  api_count: 1
  score_band: strong
  score_composite: 55.1
  shared: 3
- slug: mixpanel
  name: Mixpanel
  description: Mixpanel is a business analytics service company that tracks user interactions with web and mobile applications and provides tools for targeted communication with them.
  api_count: 10
  score_band: strong
  score_composite: 55.0
  shared: 3
- slug: kissmetrics
  name: Kissmetrics
  description: Kissmetrics is a product and behavioral analytics platform that tracks individual people across web and mobile rather than sessions, resolving every event to a persistent identity and surfacing funnels, cohorts, retention, paths, revenue a…
  api_count: 17
  score_band: developing
  score_composite: 52.0
  shared: 3
- slug: segment
  name: Twilio Segment
  description: Twilio Segment is a customer data platform that collects, cleans, and routes customer data to hundreds of downstream tools for analytics, marketing, and data warehousing. Its surface spans event collection (the HTTP Tracking API with ident…
  api_count: 4
  score_band: developing
  score_composite: 44.3
  shared: 3
- slug: june
  name: June
  description: June is a product analytics platform purpose-built for B2B SaaS companies, providing company-level and user-level analytics focused on key SaaS metrics such as activation, retention, and feature adoption. The platform offers a REST-based T…
  api_count: 1
  score_band: developing
  score_composite: 43.7
  shared: 3
- slug: chartbeat
  name: Chartbeat
  description: Chartbeat is a real-time content analytics and audience-engagement platform built for digital publishers, media brands, and editorial teams. It measures how audiences read, watch, and engage with content the moment it is published, reporti…
  api_count: 5
  score_band: developing
  score_composite: 43.4
  shared: 3
- slug: sensors-data
  name: Sensors Data
  description: Sensors Data (神策数据) is a customer data analytics and CDP (Customer Data Platform) company. Its platform unifies customer data across channels into real-time customer profiles and provides product analytics, user profiling, marketing and ad…
  api_count: 58
  score_band: developing
  score_composite: 43.1
  shared: 3
- slug: millimetric
  name: Millimetric
  description: Millimetric is API-first, privacy-respecting web and product analytics for developers, indie startups ("vibe coders"), and AI agents. It captures events over a simple REST API (/v1/track, /v1/batch, /v1/identify, /v1/query, /v1/stats, /v1/…
  api_count: 1
  score_band: developing
  score_composite: 42.4
  shared: 3
- slug: elementl
  name: Elementl
  description: Elementl, Inc. is the company behind Dagster, rebranded as Dagster Labs in August 2023. Founded in 2018 by Nick Schrock (creator of GraphQL) and led by CEO Pete Hunt, the San Francisco company builds Dagster, an open-source, Apache-2.0 lic…
  api_count: 0
  score_band: thin
  score_composite: 29.9
  shared: 3
- slug: openpanel
  name: OpenPanel
  description: OpenPanel is an open source product analytics platform that provides event tracking, user journey analysis, real-time dashboards, and funnel analysis, offering a privacy-friendly alternative to tools like Mixpanel and Amplitude.
  api_count: 1
  score_band: thin
  score_composite: 27.6
  shared: 3
- slug: armature
  name: Armature
  description: Armature is a Y Combinator (Spring 2026) startup building product analytics for AI agent sessions. Instead of tracking clicks in a human UI, Armature captures how users interact with a product through Claude, ChatGPT, Claude Code, Cursor a…
  api_count: 1
  score_band: emerging
  score_composite: 26.0
  shared: 3
- slug: scuba
  name: Scuba
  description: Scuba (Scuba Analytics, formerly Interana) is a real-time behavioral and customer analytics platform for self-service exploration of large-scale event data, backed by Battery Ventures and DCVC. The company is rebranding to Behavure AI and…
  api_count: 0
  score_band: emerging
  score_composite: 12.6
  shared: 3
- slug: quantum-metric
  name: Quantum Metric
  description: Quantum Metric is a continuous product design and digital experience intelligence platform that captures and quantifies every user session across web and mobile, replaying interactions and surfacing friction, errors, and conversion opportu…
  api_count: 0
  score_band: minimal
  score_composite: 10.2
  shared: 3
- slug: rjmetrics
  name: RJMetrics
  description: RJMetrics was a Philadelphia-based business intelligence and analytics company (founded 2008, backed by Trinity Ventures, SoftTech VC and others) that helped online businesses centralize, model and visualize data from databases and SaaS to…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: customer-io
  name: Customer.io
  description: Customer.io is a customer engagement platform that combines a customer data platform, marketing automation, and messaging delivery to send behavior-triggered email, push, SMS, and in-app messages. Its API surface includes the Track API for…
  api_count: 4
  score_band: exemplar
  score_composite: 89.3
  shared: 2
- slug: dynatrace
  name: Dynatrace
  description: Dynatrace is a software intelligence platform that provides application performance monitoring, artificial intelligence for operations, cloud infrastructure monitoring, and digital experience management.
  api_count: 6
  score_band: exemplar
  score_composite: 84.4
  shared: 2
- slug: elk-stack
  name: Elastic Stack (ELK Stack)
  description: The Elastic Stack (formerly known as the ELK Stack) is the collection of open-source products from Elastic — Elasticsearch, Logstash, Kibana, and Beats/Elastic Agent — designed for taking data from any source, in any format, and searching,…
  api_count: 3
  score_band: exemplar
  score_composite: 76.7
  shared: 2
- slug: treasure-data
  name: Treasure Data
  description: Treasure Data — rebranded Treasure AI in April 2026 — is an enterprise customer data platform that unifies first-party customer data and activates it across marketing, service and AI agent workloads. It publishes eight OpenAPI descriptions…
  api_count: 7
  score_band: exemplar
  score_composite: 74.6
  shared: 2
- slug: moengage
  name: MoEngage
  description: MoEngage is an insights-led customer engagement and cross-channel marketing automation platform used by consumer brands to unify customer data, segment audiences, and orchestrate personalized messaging across push notifications, email, SMS…
  api_count: 30
  score_band: exemplar
  score_composite: 73.6
  shared: 2
- slug: power-bi
  name: Power BI
  description: Microsoft Power BI is a business analytics service that delivers insights to enable fast, informed decisions. It provides interactive visualizations and business intelligence capabilities with an interface simple enough for end users to cr…
  api_count: 1
  score_band: exemplar
  score_composite: 72.7
  shared: 2
---
