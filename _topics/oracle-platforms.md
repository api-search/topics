---
layout: topic
slug: oracle-platforms
name: Oracle Platforms
kind: topic
description: 'Oracle Platforms is the API Evangelist index of Oracle''s cloud and enterprise platform APIs: the Oracle Cloud Infrastructure (OCI) control plane for compute, storage, networking and databases, plus the PaaS and SaaS services layered on it — Autonomous Database, Integration Cloud, Content Management, Fusion Cloud ERP, Analytics Cloud, Data Science and APEX. Oracle publishes a machine-readable index of every OCI service specification at docs.oracle.com/en-us/iaas/api/specs/index.json, and six of those contracts — 1,154 operations across Core Services, Database, Data Science, Analytics, Integration and Content Management — are harvested verbatim into this repo. Authentication is RSA request signing rather than a bearer token, idempotency is the opc-retry-token header, and Oracle ships both managed remote MCP servers and 32 open-source reference MCP servers.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/oracle-platforms.png
tags:
- Analytics
- Cloud Computing
- Database
- Enterprise Software
- Infrastructure-as-a-Service
- Integration
- Machine-Learning
- Platform-as-a-Service
- Software-as-a-Service
repo: https://github.com/api-evangelist/oracle-platforms
api_count: 11
apis:
- name: Oracle Fusion Cloud ERP API
  description: REST API for Oracle Fusion Cloud ERP providing access to financial management, procurement, and project management capabilities.
  url: https://docs.oracle.com/en/cloud/saas/financials/
- name: Oracle APEX REST APIs
  description: RESTful services for Oracle Application Express enabling low-code application development.
  url: https://apex.oracle.com/api
- name: Oracle Platforms Analytics API
  description: The analytics API from Oracle Platforms — 19 operation(s) for analytics.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Blockstorage API
  description: The blockstorage API from Oracle Platforms — 33 operation(s) for blockstorage.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Compute API
  description: The compute API from Oracle Platforms — 82 operation(s) for compute.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Compute Management API
  description: The computeManagement API from Oracle Platforms — 23 operation(s) for computemanagement.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Database API
  description: The database API from Oracle Platforms — 319 operation(s) for database.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Data Science API
  description: The dataScience API from Oracle Platforms — 99 operation(s) for datascience.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Integration Instance API
  description: The integrationInstance API from Oracle Platforms — 19 operation(s) for integrationinstance.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Oce Instance API
  description: The oceInstance API from Oracle Platforms — 7 operation(s) for oceinstance.
  url: https://docs.oracle.com/en-us/iaas/api/
- name: Oracle Platforms Virtual Network API
  description: The virtualNetwork API from Oracle Platforms — 176 operation(s) for virtualnetwork.
  url: https://docs.oracle.com/en-us/iaas/api/
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/capabilities/oracle-platforms-capability-edges.yml
- type: Overlay
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/overlays/oracle-platforms-core-overlay.yaml
- type: Overlay
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/overlays/oracle-platforms-database-overlay.yaml
- type: Overlay
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/overlays/oracle-platforms-integration-overlay.yaml
- type: Overlay
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/overlays/oracle-platforms-content-management-overlay.yaml
- type: Overlay
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/overlays/oracle-platforms-analytics-overlay.yaml
- type: Overlay
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/overlays/oracle-platforms-data-science-overlay.yaml
- type: DomainSecurity
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/security/oracle-platforms-domain-security.yml
- type: Packages
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/packages/oracle-platforms-packages.yml
- type: SDKs
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/packages/oracle-platforms-packages.yml
- type: MCPServer
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/mcp/oracle-platforms-mcp.yml
- type: ToolCrosswalk
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/mcp/oracle-platforms-tool-crosswalk.yml
- type: LLMsTxt
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/llms/oracle-platforms-llms.txt
- type: Conformance
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/conformance/oracle-platforms-conformance.yml
- type: Compliance
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/security/oracle-platforms-trust-center.yml
- type: ErrorCatalog
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/errors/oracle-platforms-problem-types.yml
- type: Lifecycle
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/lifecycle/oracle-platforms-lifecycle.yml
- type: StatusPage
  url: https://ocistatus.oraclecloud.com/
- type: Deprecation
  url: https://docs.oracle.com/en-us/iaas/Content/servicechanges.htm
- type: Authentication
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/authentication/oracle-platforms-authentication.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/security/oracle-platforms-vulnerability-disclosure.yml
- type: Security
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/security/oracle-platforms-vulnerability-disclosure.yml
- type: TrustCenter
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/security/oracle-platforms-trust-center.yml
- type: Sandbox
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/sandbox/oracle-platforms-sandbox.yml
- type: Conventions
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/conventions/oracle-platforms-conventions.yml
- type: Idempotency
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/conventions/oracle-platforms-conventions.yml
- type: ChangeLog
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/changelog/oracle-platforms-changelog.yml
- type: CLI
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/cli/oracle-platforms-cli.yml
- type: DataModel
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/data-model/oracle-platforms-data-model.yml
- type: Webhooks
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/asyncapi/oracle-platforms-events.yml
- type: AgentSkill
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/skills/_index.yml
- type: RateLimits
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/rate-limits/oracle-platforms-rate-limits.yml
- type: Plans
  url: https://github.com/api-evangelist/oracle-platforms/blob/main/plans/oracle-platforms-plans-pricing.yml
- type: DeveloperPortal
  url: https://developer.oracle.com/
- type: Documentation
  url: https://docs.oracle.com/en-us/iaas/Content/API/Concepts/usingapi.htm
- type: APIReference
  url: https://docs.oracle.com/en-us/iaas/api/
- type: GettingStarted
  url: https://docs.oracle.com/en-us/iaas/Content/API/SDKDocs/cliinstall.htm
- type: Support
  url: https://developer.oracle.com/community/
- type: GitHubOrganization
  url: https://github.com/oracle
- type: Pricing
  url: https://www.oracle.com/cloud/price-list.html
provider_count: 294
providers:
- slug: oracle-cloud
  name: Oracle Cloud Infrastructure
  description: Oracle Cloud Infrastructure (OCI) is Oracle's public cloud, exposed as a REST control plane of 159 service APIs covering compute, virtual cloud networking, block and object storage, identity and access management, Autonomous Database, Kube…
  api_count: 9
  score_band: exemplar
  score_composite: 70.9
  shared: 4
- slug: microsoft-azure
  name: Microsoft Azure
  description: Microsoft Azure is a cloud computing platform and infrastructure for building, deploying, and managing applications and services through Microsoft-managed data centers.
  api_count: 697
  score_band: exemplar
  score_composite: 72.6
  shared: 3
- slug: ibm
  name: IBM
  description: A collection of IBM's public APIs and developer resources.
  api_count: 1
  score_band: strong
  score_composite: 62.6
  shared: 3
- slug: crusoe
  name: Crusoe
  description: Crusoe is a vertically integrated "AI factory" company that designs, builds, and operates energy-first AI infrastructure, and sells it as Crusoe Cloud — a GPU cloud for training, fine-tuning, and inference. The public developer surface is…
  api_count: 2
  score_band: strong
  score_composite: 60.0
  shared: 3
- slug: workday
  name: Workday
  description: Collection of Workday REST and SOAP APIs for human capital management, financial management, enterprise planning, analytics, and platform extensibility.
  api_count: 16
  score_band: strong
  score_composite: 57.4
  shared: 3
- slug: databricks
  name: Databricks
  description: Collection of Databricks REST APIs for managing workspaces, clusters, jobs, and data operations.
  api_count: 1
  score_band: strong
  score_composite: 56.7
  shared: 3
- slug: tiledb
  name: TileDB
  description: TileDB, Inc. builds a multimodal database around a single universal data model — the multi-dimensional array — that stores tables, genomics (VCF), single-cell (SOMA), biomedical imaging, vector embeddings, point clouds, files and ML models…
  api_count: 4
  score_band: strong
  score_composite: 55.9
  shared: 3
- slug: ocient
  name: Ocient
  description: Ocient is a Chicago-based data platform company founded in 2016 that builds OcientAIQ, a unified data platform for petabyte-scale analytics and production AI. Its Compute-Adjacent Storage Architecture (CASA) colocates NVMe storage with com…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 3
- slug: tibco
  name: TIBCO
  description: APIs and services provided by TIBCO Software Inc., a global leader in integration, API management, and analytics software.
  api_count: 4
  score_band: developing
  score_composite: 44.0
  shared: 3
- slug: aws
  name: Amazon Web Services (AWS)
  description: Amazon Web Services is a comprehensive collection of cloud computing services and APIs provided by Amazon, offering infrastructure as a service, platform as a service, and software as a service solutions globally.
  api_count: 12
  score_band: developing
  score_composite: 43.1
  shared: 3
- slug: teradata
  name: Teradata
  description: Teradata provides enterprise analytics and data management solutions. The Teradata VantageCloud platform delivers connected multi-cloud data analytics with capabilities for data warehousing, advanced analytics, and machine learning at scal…
  api_count: 11
  score_band: developing
  score_composite: 41.6
  shared: 3
- slug: smartmind
  name: SmartMind
  description: SmartMind AI Inc. is a South Korean AI company (Techstars 2020, Seoul) building ontology-based enterprise AI. Its current products are Qurify — a natural-language data analysis platform that answers questions without SQL by combining struc…
  api_count: 1
  score_band: thin
  score_composite: 36.9
  shared: 3
- slug: aible
  name: Aible
  description: Aible is an enterprise AI company founded in 2018 and headquartered in Pleasanton, California, that lets business users build and run AI agents, AutoML models and generative-AI analytics against data that stays inside the customer's own AW…
  api_count: 1
  score_band: thin
  score_composite: 28.6
  shared: 3
- slug: sqream-technologies
  name: SQream Technologies
  description: SQream Technologies is an Israeli data and analytics company, founded in 2010 in Tel Aviv, that builds SQreamDB — a GPU-accelerated, SQL-compliant analytics database for petabyte-scale workloads on NVIDIA hardware — alongside AISQream for…
  api_count: 0
  score_band: thin
  score_composite: 27.5
  shared: 3
- slug: decisionnext
  name: DecisionNext
  description: DecisionNext is a San Francisco-founded (2015) AI and machine-learning software company whose prescriptive analytics platform helps commodity-driven businesses decide what to buy and sell, when, at what price, and on what formula. The plat…
  api_count: 0
  score_band: emerging
  score_composite: 19.3
  shared: 3
- slug: netezza
  name: Netezza
  description: IBM Netezza Performance Server is a cloud-native data warehouse and analytics appliance for running large-scale SQL analytics and in-database machine learning on structured data. Originally a standalone data-warehouse appliance vendor acqu…
  api_count: 0
  score_band: emerging
  score_composite: 18.6
  shared: 3
- slug: tresata
  name: Tresata
  description: Tresata is a Charlotte, North Carolina enterprise software company building what it describes as the foundational data layer for agentic AI. Its platform is marketed under the product names AB (Asset Builder), AU (Unreal Data Engine) and A…
  api_count: 0
  score_band: emerging
  score_composite: 18.6
  shared: 3
- slug: vespucci
  name: Vespucci
  description: Vespucci (Vespucci Analytics) is a product-analytics platform that helps teams understand why their users engage with a product. Rather than replacing existing analytics, it connects to the event data companies already collect in Amplitude…
  api_count: 0
  score_band: minimal
  score_composite: 10.1
  shared: 3
- slug: aaktelescienceinc
  name: AAK Tele-Science, Inc.
  description: AAK Tele-Science, Inc. (aakscience.com) is a Davis, California software company founded in 2020 that operates a cloud-based collaborative platform for the global scientific research community. The AAK platform connects researchers, institu…
  api_count: 1
  score_band: minimal
  score_composite: 8.5
  shared: 3
- slug: akashx
  name: AkashX
  description: AkashX is a Techstars-backed data and AI company building an Online Cognitive Processing (OLCP) Database and a declarative "Cognitive SQL" engine for reasoning over structured and unstructured data at scale. Its platform runs small languag…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 3
- slug: cazena
  name: Cazena
  description: Cazena was a Waltham, Massachusetts-based enterprise software company, founded in 2014, that delivered a fully-managed SaaS data platform — a "Big Data as a Service" cloud data lake that let enterprises run analytics, machine learning, and…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: recommind
  name: Recommind
  description: Recommind was an enterprise information analytics and eDiscovery software company founded in 2000, best known for its CORE predictive-analytics platform and its Axcelerate eDiscovery and information-governance products used by legal and en…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: canopy-labs
  name: Canopy Labs
  description: Canopy Labs was a customer analytics and predictive marketing SaaS company founded in 2012 in the Toronto, Ontario area (Thornhill) by Wojciech Gryc and Jorge Escobedo, with an additional office in San Francisco. A Y Combinator alumnus, it…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 80.4
  shared: 2
- slug: elk-stack
  name: Elastic Stack (ELK Stack)
  description: The Elastic Stack (formerly known as the ELK Stack) is the collection of open-source products from Elastic — Elasticsearch, Logstash, Kibana, and Beats/Elastic Agent — designed for taking data from any source, in any format, and searching,…
  api_count: 3
  score_band: exemplar
  score_composite: 76.7
  shared: 2
- slug: clickhouse
  name: ClickHouse
  description: ClickHouse is a fast open-source column-oriented database management system that enables real-time analytical reporting using SQL. ClickHouse exposes multiple interfaces - an HTTP interface for SQL queries, native TCP, MySQL and PostgreSQL…
  api_count: 2
  score_band: exemplar
  score_composite: 70.5
  shared: 2
- slug: qliksense
  name: Qlik Sense
  description: 'Qlik Sense and Qlik Cloud from Qlik Parent, Inc. — a business intelligence, data integration and AI analytics platform. Qlik publishes one of the broadest machine-readable API surfaces in the analytics market: 78 OpenAPI 3.0.0 documents co…'
  api_count: 78
  score_band: exemplar
  score_composite: 69.7
  shared: 2
- slug: google-analytics
  name: Google Analytics
  description: Google Analytics provides data and insights about website and app usage, enabling businesses to understand their audience and optimize their digital properties through customer-centric measurement, machine learning insights, and cross-plat…
  api_count: 6
  score_band: exemplar
  score_composite: 69.6
  shared: 2
- slug: buttondown
  name: Buttondown
  description: Buttondown is an independent, bootstrapped email newsletter platform for writers, creators and developers, offering a Markdown and rich-text editor, subscriber management with tags, segments and metadata, automations, RSS-to-email, surveys…
  api_count: 1
  score_band: exemplar
  score_composite: 67.2
  shared: 2
- slug: oracle
  name: Oracle
  description: Collection of Oracle's APIs and developer resources across cloud infrastructure, databases, AI services, SaaS applications, and platform services.
  api_count: 161
  score_band: exemplar
  score_composite: 66.8
  shared: 2
---
