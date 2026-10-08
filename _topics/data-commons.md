---
layout: topic
slug: data-commons
name: Data Commons
kind: topic
description: Data Commons is an open knowledge graph initiative led by Google that aggregates and harmonizes the world's public data into a single graph, making global statistical data simple to explore, query, and integrate through REST, Python, BigQuery, web component, and MCP interfaces.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/data-commons.png
tags:
- Data Commons
- Knowledge Graph
- Open Data
- Public Data
- Statistics
repo: https://github.com/api-evangelist/data-commons
api_count: 8
apis:
- name: Data Commons Python Client
  description: Official Python client library that wraps the Data Commons REST API with native Pandas DataFrame support for analytical workflows and notebook integration.
  url: https://docs.datacommons.org/api/python/v2/
- name: Data Commons Google Sheets
  description: Custom Google Sheets functions that pull Data Commons statistical data directly into spreadsheets without requiring an API key.
  url: https://docs.datacommons.org/api/sheets/
- name: Data Commons Web Components
  description: Drop-in JavaScript/HTML web components for embedding Data Commons charts, maps, rankings, and visualizations in any website.
  url: https://docs.datacommons.org/api/web_components/
- name: Data Commons BigQuery
  description: SQL access to Data Commons through Google BigQuery enabling complex analytical queries and joins with private datasets.
  url: https://docs.datacommons.org/api/bigquery.html
- name: Data Commons MCP Server
  description: Model Context Protocol server that lets AI agents query Data Commons conversationally, surfacing variables, places, and observations through natural language tools.
  url: https://docs.datacommons.org/api/mcp/
- name: Data Commons Node API
  description: The Node API from Data Commons — 1 operation(s) for node.
  url: https://docs.datacommons.org/api/rest/v2/
- name: Data Commons Observation API
  description: The Observation API from Data Commons — 1 operation(s) for observation.
  url: https://docs.datacommons.org/api/rest/v2/
- name: Data Commons Resolve API
  description: The Resolve API from Data Commons — 1 operation(s) for resolve.
  url: https://docs.datacommons.org/api/rest/v2/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/data-commons/blob/main/agentic-access/data-commons-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/data-commons/blob/main/security/data-commons-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/data-commons/blob/main/authentication/data-commons-authentication.yml
- type: Website
  url: https://datacommons.org/
- type: Documentation
  url: https://docs.datacommons.org/
- type: API Documentation
  url: https://docs.datacommons.org/api/
- type: API Keys
  url: https://apikeys.datacommons.org
- type: GitHubOrganization
  url: https://github.com/datacommonsorg
- type: Blog
  url: https://blog.datacommons.org/
- type: Vocabulary
  url: https://github.com/api-evangelist/data-commons/blob/main/vocabulary/data-commons-vocabulary.yml
- type: JSONLD
  url: https://github.com/api-evangelist/data-commons/blob/main/json-ld/data-commons-context.jsonld
- type: MCPServer
  url: https://blog.datacommons.org/2025/10/02/announcing-the-data-commons-model-context-protocol-server/
provider_count: 19
providers:
- slug: wikidata
  name: Wikidata
  description: Wikidata is a free, collaborative, multilingual knowledge graph hosted by the Wikimedia Foundation. It provides structured linked data for Wikipedia and other Wikimedia projects, as well as a public platform for anyone to read and edit. Wi…
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 2
- slug: us-census-bureau
  name: US Census Bureau
  description: The U.S. Census Bureau is the federal statistical agency responsible for producing data about the American people and economy. Established in 1902 and part of the U.S. Department of Commerce, the Bureau conducts the constitutionally mandat…
  api_count: 7
  score_band: developing
  score_composite: 51.8
  shared: 2
- slug: us-dot
  name: U.S. Department of Transportation
  description: The U.S. Department of Transportation (DOT) is the federal transportation regulator for the United States, the deepest travel market in the world. In aviation DOT is not a participant in the distribution chain — it is the counterweight to…
  api_count: 12
  score_band: developing
  score_composite: 49.0
  shared: 2
- slug: bargo-congress-trades-api
  name: Bargo Congress Trades API
  description: A free JSON REST API and hosted MCP server from Bargo that normalizes U.S. House and Senate STOCK Act securities transaction disclosures into a queryable dataset — currently 42,000+ disclosed trades across 415 members and 4,100+ tickers. S…
  api_count: 2
  score_band: developing
  score_composite: 48.2
  shared: 2
- slug: department-of-justice
  name: Department of Justice
  description: The U.S. Department of Justice (DOJ) is the federal executive department responsible for enforcing the law and defending the interests of the United States. DOJ exposes a portfolio of public APIs and data feeds including the DOJ News API f…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 2
- slug: wikipedia
  name: Wikipedia / MediaWiki
  description: 'Wikipedia is the free, multilingual online encyclopedia operated by the non-profit Wikimedia Foundation. The platform exposes its content and structured data through several public APIs: the original MediaWiki Action API (action=query|edit…'
  api_count: 2
  score_band: developing
  score_composite: 46.6
  shared: 2
- slug: opendatasoft
  name: Opendatasoft
  description: Open data platform with REST APIs for accessing public datasets from 1,000+ cities and organizations, providing standard OData and JSON query interfaces. Now operating as Huwise, the platform powers 3,000+ data marketplaces and provides ca…
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 2
- slug: economic-research-service
  name: Economic Research Service
  description: The Economic Research Service (ERS) is a division of the United States Department of Agriculture (USDA) that conducts economic research and analysis related to agriculture, food, and rural development. ERS provides policymakers, stakeholde…
  api_count: 2
  score_band: developing
  score_composite: 42.6
  shared: 2
- slug: bureau-of-transportation-statistics
  name: Bureau of Transportation Statistics
  description: The Bureau of Transportation Statistics (BTS), part of the Department of Transportation (DOT) is the preeminent source of statistics on commercial aviation, multimodal freight activity, and transportation economics, and provides context to…
  api_count: 2
  score_band: developing
  score_composite: 42.0
  shared: 2
- slug: the-bureau-of-economic-analysis
  name: The Bureau of Economic Analysis
  description: The Bureau of Economic Analysis (BEA) is an agency within the U.S. Department of Commerce that provides economic data to policymakers, businesses, and the general public. The BEA collects and analyzes a wide range of economic indicators, i…
  api_count: 1
  score_band: thin
  score_composite: 36.6
  shared: 2
- slug: agricultural-statistics-service
  name: Agricultural Statistics Service
  description: The National Agricultural Statistics Service (NASS) is an agency of the United States Department of Agriculture (USDA) whose mission is to support the United States, its agricultural sector, and rural communities by providing accurate, obj…
  api_count: 5
  score_band: thin
  score_composite: 36.2
  shared: 2
- slug: eurostat
  name: Eurostat
  description: Eurostat is the statistical office of the European Union, providing free and open REST APIs for programmatic access to European statistical data covering demographics, economy, trade, agriculture, transport, environment, and dozens of othe…
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 2
- slug: unicef-data
  name: UNICEF Data
  description: UNICEF Data is the official open data platform of the United Nations Children's Fund, providing programmatic access to global child welfare statistics, health and nutrition indicators, education data, child protection metrics, MICS (Multip…
  api_count: 2
  score_band: thin
  score_composite: 34.2
  shared: 2
- slug: conceptnet
  name: ConceptNet
  description: ConceptNet is a freely available multilingual knowledge graph that gives computers access to common-sense knowledge. It represents over 13 million links between concepts across 100+ languages, drawing from crowd-sourced resources (Open Min…
  api_count: 1
  score_band: thin
  score_composite: 34.1
  shared: 2
- slug: united-states-census-bureau
  name: United States Census Bureau
  description: The U.S. Census Bureau is the nation's leading provider of quality data about its people and economy. The Census Bureau has been rolling out datasets via APIs, providing programmatic access to demographic, economic, housing, and social sta…
  api_count: 1
  score_band: thin
  score_composite: 32.5
  shared: 2
- slug: dbnomics
  name: DBnomics
  description: DBnomics is the world's economic database - a free, open-source aggregator run by Cepremap that harvests macroeconomic time series from more than 90 national and international providers (IMF, ECB, Eurostat, World Bank, OECD, BLS, BEA, Banq…
  api_count: 1
  score_band: thin
  score_composite: 29.8
  shared: 2
- slug: unfao
  name: FAO FAOSTAT
  description: The Food and Agriculture Organization (FAO) of the United Nations operates FAOSTAT, the world's largest freely accessible database for food and agriculture statistics. FAOSTAT provides REST APIs for programmatic access to agricultural prod…
  api_count: 2
  score_band: thin
  score_composite: 29.0
  shared: 2
- slug: dol
  name: Department of Labor
  description: The U.S. Department of Labor provides REST APIs exposing over 200 datasets covering employment statistics, H-1B and foreign labor visa data, OSHA inspections and enforcement, wage and hour violations, job openings, union reports, workforce…
  api_count: 13
  score_band: emerging
  score_composite: 25.2
  shared: 2
- slug: dbpedia
  name: DBpedia
  description: DBpedia is a community project that extracts structured data from Wikipedia and publishes it as Linked Open Data on the Web. It provides a SPARQL endpoint, a Lookup Service for entity resolution, a Spotlight API for text annotation, a Live…
  api_count: 6
  score_band: emerging
  score_composite: 20.2
  shared: 2
---
