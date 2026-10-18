---
layout: topic
slug: knowledge
name: API Knowledge
kind: topic
description: API knowledge is the layer of indexes, descriptions, contexts, and signals that lets humans and agents reason about which APIs exist, what they do, who operates them, what they cost, how to call them, and how trustworthy they are. This topic repo catalogs the formats and platforms that publish API knowledge — APIs.json as a sitemap for an API project, APIs.guru as the community OpenAPI directory, RapidAPI Hub and the Postman Public API Network as commercial discovery surfaces, the OpenAPI Initiative as the spec authority, Jentic and Composio as agent-facing knowledge layers, llms.txt as a site-level guide for LLMs, schema.org/WebAPI as the structured-data vocabulary. Together they form a multi-source view of the API knowledge an AI agent needs to do real work against the API economy.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/knowledge.png
tags:
- API Knowledge
- Knowledge Graph
- API Discovery
- API Search
- Catalog
- Index
- Registries
- RAG
- Semantic Web
- JSON-LD
- LLM
- AI Agents
- Topic
repo: https://github.com/api-evangelist/knowledge
api_count: 9
apis:
- name: APIs.json
  description: APIs.json is an open-source machine-readable format for indexing the surface area of an API project — its operations, OpenAPI files, JSON Schema, JSON-LD contexts, documentation, pricing, status page, and maintainer contacts. It functions…
  url: https://apisjson.org
- name: APIs.guru OpenAPI Directory
  description: APIs.guru is the community-driven directory of OpenAPI 2.0 and 3.x definitions for publicly available APIs. As reported on the api.apis.guru metrics endpoint, the directory currently indexes 2,529 APIs across 677 providers, with 3,992 spec…
  url: https://apis.guru
- name: RapidAPI Hub
  description: RapidAPI Hub is a commercial API marketplace and developer portal that acts as a discovery, onboarding, and metering layer over thousands of third-party APIs. RapidAPI Hub fronts a single key, single billing relationship, and a normalized…
  url: https://rapidapi.com/hub
- name: Postman Public API Network
  description: The Postman Public API Network is Postman's public-facing index of API workspaces, collections, and environments. Postman's "Explore" surface organizes the network by category (App Security, Artificial Intelligence, Payments, etc.) and is…
  url: https://www.postman.com/explore
- name: OpenAPI Initiative
  description: The OpenAPI Initiative (OAI) is the Linux Foundation working group that stewards the OpenAPI Specification — the de-facto contract format for HTTP APIs and the substrate underneath most API knowledge tooling. OpenAPI 3.2.0 was released on…
  url: https://www.openapis.org
- name: Jentic
  description: Jentic is a governed execution layer that lets AI agents call enterprise APIs safely. It describes API workflows using the Arazzo open standard on top of OpenAPI, validates agent behavior in a sandbox, and converts successful interactions…
  url: https://jentic.com
- name: Composio
  description: Composio is an agent integration platform that exposes 1,000+ third-party applications as agent-ready tools. Composio publishes a tool registry accessed through session.tools() and ships both an OpenAPI-based native tool representation and…
  url: https://composio.dev
- name: llms.txt
  description: llms.txt is a community specification for a markdown file placed at the root path /llms.txt that gives LLMs a curated, link-rich entry point to a site's most important content. The spec is the lightest-weight form of API knowledge — it doe…
  url: https://llmstxt.org
- name: schema.org WebAPI
  description: schema.org/WebAPI is the structured-data vocabulary for describing an "application programming interface accessible over Web/Internet technologies." It inherits from schema.org/Service and contributes properties like documentation, provide…
  url: https://schema.org/WebAPI
links:
- type: Blog
  url: https://apisjson.org/blog/
- type: DomainSecurity
  url: https://github.com/api-evangelist/knowledge/blob/main/security/knowledge-domain-security.yml
- type: Portal
  url: https://github.com/api-evangelist/knowledge
- type: GitHubRepository
  url: https://github.com/api-evangelist/knowledge
- type: Vocabulary
  url: https://github.com/api-evangelist/knowledge/blob/main/vocabulary/knowledge-vocabulary.yml
- type: JSONLD
  url: https://github.com/api-evangelist/knowledge/blob/main/json-ld/knowledge-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/knowledge/blob/main/json-schema/knowledge-record-schema.json
provider_count: 117
providers:
- slug: webcrawlerapi-com
  name: WebCrawlerAPI
  description: WebCrawlerAPI is a web crawling and scraping API from 103 Labs (Netherlands) that turns websites into clean, LLM-ready markdown, cleaned text, HTML or link lists for AI agents, support bots and RAG pipelines. It offers asynchronous multi-p…
  api_count: 3
  score_band: strong
  score_composite: 64.6
  shared: 3
- slug: h2o-ai
  name: H2O.ai
  description: H2O.ai is an open-source artificial-intelligence and machine-learning company whose platform spans H2O-3 (a distributed, in-memory ML engine), H2O Driverless AI (automatic machine learning), H2O MLOps (model deployment, scoring and monitor…
  api_count: 2
  score_band: strong
  score_composite: 56.5
  shared: 3
- slug: cognee
  name: Cognee
  description: Cognee is an open-source AI memory and knowledge graph platform that enables developers to build persistent, structured memory for AI agents and LLM applications. The platform provides a REST API and Python/TypeScript SDKs for ingesting do…
  api_count: 1
  score_band: developing
  score_composite: 42.8
  shared: 3
- slug: docling
  name: Docling
  description: Docling is an open-source toolkit for parsing diverse document formats — PDF, DOCX, PPTX, XLSX, HTML, images, audio, LaTeX, plain text — into a unified, lossless DoclingDocument representation that downstream generative AI and RAG systems…
  api_count: 2
  score_band: thin
  score_composite: 38.0
  shared: 3
- slug: zep
  name: Zep
  description: Zep is a context engineering and agent memory platform that assembles relevant context from chat history, business data, and user interactions for AI agents. It builds a temporal knowledge graph per user that evolves as new facts arrive, a…
  api_count: 1
  score_band: thin
  score_composite: 37.1
  shared: 3
- slug: julep
  name: Julep
  description: Julep is an open-source platform for building stateful AI agents that remember past interactions and execute long-running, multi-step tasks. Its cloud API and self-hostable server expose agents, sessions, tasks, executions, documents (RAG)…
  api_count: 1
  score_band: thin
  score_composite: 37.0
  shared: 3
- slug: eder-labs
  name: Eder Labs
  description: Eder Labs builds infrastructure for using personal data in safer, more human ways. Its current focus is Persona, an open-source (MIT) user-memory system for AI agents that turns a person's digital footprint into a Graph-Vector hybrid perso…
  api_count: 1
  score_band: thin
  score_composite: 29.4
  shared: 3
- slug: miriel
  name: Miriel
  description: 'Miriel is the context engine and platform for AI-native development. It gives AI apps and agents the context they need in real time through a simple API: developers connect a data source with the learn operation and retrieve relevant conte…'
  api_count: 7
  score_band: emerging
  score_composite: 24.9
  shared: 3
- slug: superduperdb
  name: Superduper
  description: Superduper (formerly SuperDuperDB) is an open-source Python framework for building database-integrated AI agents and applications directly on top of existing databases - MongoDB, SQL databases, Snowflake, and Redis - without separate vecto…
  api_count: 6
  score_band: emerging
  score_composite: 17.3
  shared: 3
- slug: naboo
  name: Naboo
  description: Naboo is Reasoning Layer infrastructure for enterprise AI agents, built on a Decision Graph that models how a company actually decides, ships, and unblocks - who decided what, what triggered each decision, what blocks it, and what depends…
  api_count: 0
  score_band: emerging
  score_composite: 15.0
  shared: 3
- slug: rdf
  name: RDF
  description: The Resource Description Framework (RDF) is a W3C standard for representing information about resources on the web. RDF is the foundation for linked data and the semantic web, providing a graph-based data model where statements are express…
  api_count: 0
  score_band: emerging
  score_composite: 13.0
  shared: 3
- slug: apis-io
  name: APIs.io
  description: APIs.io is an open-source API search engine and federated discovery network built on the APIs.json specification. It indexes API providers and their individual APIs across the public internet along with the machine-readable artifacts they…
  api_count: 20
  score_band: exemplar
  score_composite: 93.6
  shared: 2
- slug: alphaai
  name: AlphaAI
  description: A REST API and agent-native platform for relevance-scored, ticker-linked financial news, built for trading bots, agent backends, and dashboards. Every article is enriched at ingest with a 1-10 relevance score, one of fourteen categories, v…
  api_count: 1
  score_band: exemplar
  score_composite: 66.7
  shared: 2
- slug: dust-tt
  name: Dust
  description: Dust is a Paris-based enterprise AI platform for building, deploying, and operating teams of AI agents that have shared context across a company's knowledge and tools. Dust positions itself as the platform for "AI Operators" — the people w…
  api_count: 9
  score_band: strong
  score_composite: 66.1
  shared: 2
- slug: airia
  name: Airia
  description: 'Airia (Airia LLC, Atlanta) is an enterprise AI orchestration, security and governance platform: a no-code/low-code/pro-code agent builder, a model routing and cost gateway, an MCP Gateway that fronts 1,000+ app connectors and turns hosted…'
  api_count: 1
  score_band: strong
  score_composite: 64.0
  shared: 2
- slug: seekr
  name: Seekr
  description: Seekr Technologies builds explainable, auditable, sovereign AI for regulated industries and high-stakes government missions. Its platform, SeekrFlow, is an end-to-end AI operating system that covers document ingestion and AI-ready data pre…
  api_count: 8
  score_band: strong
  score_composite: 63.4
  shared: 2
- slug: machinelibrary-ai
  name: Space Frontiers
  description: Space Frontiers is a Wyoming corporation whose search and AI product, Machine Library (formerly Space Frontiers search, moved to machinelibrary.ai on 2026-09-12), is a full-text retrieval API and hosted MCP server over a corpus the provide…
  api_count: 4
  score_band: strong
  score_composite: 62.8
  shared: 2
- slug: gumloop
  name: Gumloop
  description: Gumloop is an AI-agent automation platform for building, deploying, and governing agents that automate real work — data analysis, customer support, CRM management, and back-office tasks — across tools like Slack, Microsoft Teams, and Gmail…
  api_count: 1
  score_band: strong
  score_composite: 62.1
  shared: 2
- slug: compresr
  name: Compresr
  description: Compresr is an LLM context-compression API. You send the long context you would otherwise pass to a model plus the query you want answered, and Compresr returns a shorter context that keeps the answer-bearing spans and drops the rest — few…
  api_count: 1
  score_band: strong
  score_composite: 59.5
  shared: 2
- slug: arcade-dev
  name: Arcade.dev
  description: Arcade.dev (formerly Arcade AI) is the MCP runtime for production AI agents — a platform that lets agents safely take real-world actions across SaaS apps with per-user authorization, governed tool execution, and audit logging. The Arcade E…
  api_count: 9
  score_band: strong
  score_composite: 58.7
  shared: 2
- slug: 558686-xyz
  name: gpt55-token-gateway
  description: gpt55-token-gateway is the self-chosen service name of an unnamed operator running two OpenAI-compatible AI API gateways on the 558686.xyz domain. GPT55 Model Gateway (gpt55.558686.xyz) sells single GPT-5.6 Luna, GPT-5.5 and GPT-5.3-codex…
  api_count: 3
  score_band: strong
  score_composite: 57.7
  shared: 2
- slug: coval
  name: Coval
  description: Coval is the deployment-readiness platform for voice and chat AI agents. Teams simulate thousands of realistic conversation scenarios before launch, monitor real production calls, and improve reliability with metrics and human review. Cova…
  api_count: 20
  score_band: strong
  score_composite: 57.5
  shared: 2
- slug: google-gemini
  name: Google Gemini
  description: Google's multimodal AI model APIs for text, image, audio, and video understanding.
  api_count: 1
  score_band: developing
  score_composite: 53.5
  shared: 2
- slug: llamaparse
  name: LlamaParse
  description: LlamaParse is an enterprise document parsing and AI pipeline platform from LlamaIndex that converts complex PDFs, Office files, and 130+ document formats into LLM-ready structured outputs. The platform offers six composable products under…
  api_count: 1
  score_band: developing
  score_composite: 53.5
  shared: 2
- slug: indykite
  name: Indykite
  description: IndyKite is the runtime control layer for agentic AI. Its enterprise platform applies trust, context, and runtime control across organizational data so autonomous AI agents can act securely, continuously injecting live signals — identity,…
  api_count: 2
  score_band: developing
  score_composite: 52.7
  shared: 2
- slug: quadrillion
  name: Quadrillion
  description: Quadrillion Labs builds Qualia, an AI coding agent for researchers that runs hundreds of agents in parallel to compress weeks of research into hours. Qualia is a Jupyter-compatible notebook IDE with autonomous mode, a central knowledge gra…
  api_count: 1
  score_band: developing
  score_composite: 52.5
  shared: 2
- slug: cognition-labs
  name: Cognition Labs
  description: Cognition Labs is the applied AI lab behind Devin, the autonomous AI software engineer that plans, writes, tests, and ships code inside its own shell, code editor, and browser. The Devin API lets teams create and drive Devin sessions progr…
  api_count: 2
  score_band: developing
  score_composite: 52.3
  shared: 2
- slug: wikidata
  name: Wikidata
  description: Wikidata is a free, collaborative, multilingual knowledge graph hosted by the Wikimedia Foundation. It provides structured linked data for Wikipedia and other Wikimedia projects, as well as a public platform for anyone to read and edit. Wi…
  api_count: 1
  score_band: developing
  score_composite: 52.0
  shared: 2
- slug: orthogonal
  name: Orthogonal
  description: Orthogonal is a unified API and payment layer for AI agents, backed by Pantera Capital and Y Combinator. An agent describes what it needs in natural language and Orthogonal returns the right service from a catalog of 40+ third-party APIs (…
  api_count: 2
  score_band: developing
  score_composite: 51.6
  shared: 2
- slug: chroma
  name: Chroma
  description: Chroma (Chroma DB) is an open-source AI-native embedding database designed to make it easy to build LLM applications by providing storage, retrieval, and management for vector embeddings, full-text search, regex search, and multi-modal ret…
  api_count: 2
  score_band: developing
  score_composite: 51.5
  shared: 2
---
