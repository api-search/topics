---
layout: topic
slug: lapis
name: LAPIS
kind: topic
description: LAPIS (Lightweight API Specification for Intelligent Systems) is a compact, LLM-native API description format authored by Daniel Garcia (cr0hn). It is designed as the format you convert your OpenAPI specifications to when the consumer is a Large Language Model rather than a code generator or human reader. By replacing JSON/YAML structural overhead with a function-signature syntax, indentation-based sections, and centralized definitions for errors, webhooks, rate limits, and workflows, a typical LAPIS document carries the same semantic information as its OpenAPI source while consuming roughly 70-80 percent fewer tokens. LAPIS is not a runtime format and does not replace MCP, function calling, or OpenAPI itself - it is an intermediate representation optimized for AI agents that need to reason about an API inside a constrained context window.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/lapis.png
tags:
- Specification
- LLM
- AI Agents
- OpenAPI
- Token Optimization
- Standards
repo: https://github.com/api-evangelist/lapis
api_count: 1
apis:
- name: LAPIS Specification
  description: The LAPIS specification defines a token-minimal, LLM-native format for describing HTTP APIs. A LAPIS document is organized into up to seven indentation-based sections - [meta], [types], [ops], [webhooks], [errors], [limits], and [flows] -…
  url: https://github.com/cr0hn/LAPIS/blob/main/spec.en.md
links:
- type: Portal
  url: https://cr0hn.github.io/LAPIS/
- type: Documentation
  url: https://github.com/cr0hn/LAPIS/blob/main/spec.en.md
- type: Documentation
  url: https://github.com/cr0hn/LAPIS/blob/main/spec.es.md
- type: GettingStarted
  url: https://github.com/cr0hn/LAPIS#getting-started
- type: GitHubRepository
  url: https://github.com/cr0hn/LAPIS
- type: ChangeLog
  url: https://github.com/cr0hn/LAPIS/blob/main/CHANGELOG.md
- type: TermsOfService
  url: https://github.com/cr0hn/LAPIS/blob/main/LICENSE
- type: Compliance
  url: https://github.com/cr0hn/LAPIS/blob/main/CODE_OF_CONDUCT.md
- type: Security
  url: https://github.com/cr0hn/LAPIS/blob/main/SECURITY.md
- type: Contact
  url: https://github.com/cr0hn/LAPIS/blob/main/CONTRIBUTING.md
- type: CLI
  url: https://pypi.org/project/lapis-spec/
- type: SDKs
  url: https://pypi.org/project/lapis-spec/
- type: IDESupport
  url: https://github.com/cr0hn/LAPIS/tree/main/tools/ides/vscode
- type: Sandbox
  url: https://cr0hn.github.io/LAPIS/
- type: Issues
  url: https://github.com/cr0hn/LAPIS/issues
- type: Vocabulary
  url: https://github.com/api-evangelist/lapis/blob/main/vocabulary/lapis-vocabulary.yml
- type: JSONSchema
  url: https://github.com/api-evangelist/lapis/blob/main/json-schema/lapis-document-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/lapis/blob/main/json-structure/lapis-document-structure.json
- type: JSONLD
  url: https://github.com/api-evangelist/lapis/blob/main/json-ld/lapis-context.jsonld
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-invoice-service-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-meta-section-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-types-section-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-ops-section-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-webhooks-section-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-errors-section-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-limits-section-example.lapis
- type: Examples
  url: https://github.com/api-evangelist/lapis/blob/main/examples/lapis-flows-section-example.lapis
provider_count: 97
providers:
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: agntcy
  name: AGNTCY
  description: AGNTCY is the open collective for agent interoperability, initiated by Outshift — Cisco's incubation group — and governed under the Linux Foundation (LF Projects, LLC), developed in the open across 52 public repositories. It publishes spec…
  api_count: 4
  score_band: developing
  score_composite: 48.4
  shared: 3
- slug: reasonblocks
  name: ReasonBlocks
  description: ReasonBlocks is a Y Combinator (Spring 2026) startup building a drop-in runtime layer that makes production AI agents observable, self-correcting, and cheaper to run. The platform detects failing agent trajectories (loops and redundant wor…
  api_count: 1
  score_band: thin
  score_composite: 32.7
  shared: 3
- slug: cursorrules
  name: .cursorrules
  description: .cursorrules is a project-level configuration file used by the Cursor AI code editor to define custom rules, coding conventions, and behavioral instructions that shape how the editor's AI assistant generates and edits code. The file is pla…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: arcade
  name: Arcade
  description: Arcade.dev is the MCP runtime for production AI agent deployments. The Arcade Engine — a hosted or self-hostable API surface — handles OAuth user authorization, manages user tokens, and exposes 7,000+ pre-built integrations as Model Contex…
  api_count: 1
  score_band: exemplar
  score_composite: 72.9
  shared: 2
- slug: archbee
  name: Archbee
  description: Archbee is a documentation and knowledge-portal platform for software teams. It creates, manages and publishes technical documentation, API references and internal wikis, with collaborative editing, revision history, branching and review,…
  api_count: 11
  score_band: exemplar
  score_composite: 70.9
  shared: 2
- slug: alphaai
  name: AlphaAI
  description: A REST API and agent-native platform for relevance-scored, ticker-linked financial news, built for trading bots, agent backends, and dashboards. Every article is enriched at ingest with a 1-10 relevance score, one of fourteen categories, v…
  api_count: 1
  score_band: exemplar
  score_composite: 66.7
  shared: 2
- slug: taskfolk
  name: Taskfolk
  description: Taskfolk is a project-management and issue-tracking platform built for teams and their AI agents working side by side, operated by UTTER L.L.C-FZ of Dubai, UAE. Workspaces contain projects; projects contain issues moved across board, backl…
  api_count: 4
  score_band: strong
  score_composite: 64.7
  shared: 2
- slug: webcrawlerapi-com
  name: WebCrawlerAPI
  description: WebCrawlerAPI is a web crawling and scraping API from 103 Labs (Netherlands) that turns websites into clean, LLM-ready markdown, cleaned text, HTML or link lists for AI agents, support bots and RAG pipelines. It offers asynchronous multi-p…
  api_count: 3
  score_band: strong
  score_composite: 64.5
  shared: 2
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 64.3
  shared: 2
- slug: farmdash
  name: FarmDash Agent Hub
  description: FarmDash is a zero-custody intelligence and control layer for DeFi agents and airdrop farmers, combining Trail Heat opportunity scoring, Signal Architect swap routing, wallet and Sybil-risk intelligence, and Hyperliquid futures research ac…
  api_count: 3
  score_band: strong
  score_composite: 61.3
  shared: 2
- slug: cognition-labs
  name: Cognition Labs
  description: Cognition Labs is the applied AI lab behind Devin, the autonomous AI software engineer that plans, writes, tests, and ships code inside its own shell, code editor, and browser. The Devin API lets teams create and drive Devin sessions progr…
  api_count: 2
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: adanos-market-sentiment-api
  name: Adanos Market Sentiment API
  description: Key-authenticated REST/JSON API for financial market sentiment analytics across Reddit, X.com, news, and Polymarket, plus stock news and crypto sentiment. Provides Buzz Score, Trend Detection, and directional Sentiment signals for traders,…
  api_count: 7
  score_band: strong
  score_composite: 59.7
  shared: 2
- slug: assetfare
  name: AssetFare
  description: A capped, non-custodial routing API for a single corridor — Solana SOL to Base native ETH — aimed at AI agents. It returns fee-inclusive quotes and bounded unsigned actions; the caller's agent verifies, signs, and submits every transaction…
  api_count: 4
  score_band: strong
  score_composite: 58.5
  shared: 2
- slug: trisotech
  name: Trisotech
  description: Trisotech is a Montreal, Canada software company, founded in 1996, that builds the Digital Enterprise Suite — a standards-anchored low-code platform for modelling and automating business processes, cases and decisions. Its modelers impleme…
  api_count: 3
  score_band: strong
  score_composite: 58.4
  shared: 2
- slug: reachdesk
  name: Reachdesk
  description: Reachdesk is a global B2B corporate gifting and direct mail platform that enables sales, marketing, and customer success teams to send physical gifts, branded merchandise, and digital rewards at scale. The Reachdesk REST API allows program…
  api_count: 2
  score_band: strong
  score_composite: 58.2
  shared: 2
- slug: gumloop
  name: Gumloop
  description: Gumloop is an AI-agent automation platform for building, deploying, and governing agents that automate real work — data analysis, customer support, CRM management, and back-office tasks — across tools like Slack, Microsoft Teams, and Gmail…
  api_count: 1
  score_band: strong
  score_composite: 57.8
  shared: 2
- slug: netcracker
  name: Netcracker
  description: Netcracker Technology is a Waltham, Massachusetts-based BSS/OSS and digital business software vendor and a wholly owned subsidiary of NEC Corporation. It sells cloud BSS, digital commerce and monetization, convergent charging, service and…
  api_count: 4
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: dreamthreads
  name: DreamThreads
  description: DreamThreads exposes the DreamGraph API, a context-first dream interpretation and structured parsing platform. It offers a keyless public dream parser, gated partner interpretation endpoints, a hosted MCP server, and full machine-readable…
  api_count: 2
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: 558686-xyz
  name: gpt55-token-gateway
  description: gpt55-token-gateway is the self-chosen service name of an unnamed operator running two OpenAI-compatible AI API gateways on the 558686.xyz domain. GPT55 Model Gateway (gpt55.558686.xyz) sells single GPT-5.6 Luna, GPT-5.5 and GPT-5.3-codex…
  api_count: 3
  score_band: strong
  score_composite: 57.2
  shared: 2
- slug: h2o-ai
  name: H2O.ai
  description: H2O.ai is an open-source artificial-intelligence and machine-learning company whose platform spans H2O-3 (a distributed, in-memory ML engine), H2O Driverless AI (automatic machine learning), H2O MLOps (model deployment, scoring and monitor…
  api_count: 2
  score_band: strong
  score_composite: 56.3
  shared: 2
- slug: mem0
  name: Mem0
  description: Mem0 is a memory infrastructure layer that gives AI agents and applications persistent context across sessions. The platform automatically condenses chat history into compact memories that reduce tokens and latency while preserving the rig…
  api_count: 1
  score_band: strong
  score_composite: 55.3
  shared: 2
- slug: observeai
  name: Observe.AI
  description: Observe.AI is an agentic AI platform for the contact center, providing purpose-built AI agents that handle customer support end-to-end across voice and chat, real-time AI Copilot guidance that assists frontline agents during live interacti…
  api_count: 1
  score_band: strong
  score_composite: 54.9
  shared: 2
- slug: jentic
  name: Jentic
  description: Jentic is an AI infrastructure company building the agentic knowledge layer for APIs. Founded in late 2024 and backed by $4.5M in pre-seed funding, Jentic enables enterprises to confidently manage, scale, and govern AI agent initiatives in…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: gsma
  name: GSMA
  description: The GSMA (GSM Association) is the London-headquartered global trade body for the mobile industry, representing roughly 750 mobile network operators and around 400 companies in the wider mobile ecosystem, and the organiser of MWC Barcelona.…
  api_count: 37
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: quadrillion
  name: Quadrillion
  description: Quadrillion Labs builds Qualia, an AI coding agent for researchers that runs hundreds of agents in parallel to compress weeks of research into hours. Qualia is a Jupyter-compatible notebook IDE with autonomous mode, a central knowledge gra…
  api_count: 1
  score_band: developing
  score_composite: 52.5
  shared: 2
- slug: sweep
  name: Sweep
  description: Sweep is the agentic layer for enterprise systems. By connecting to platforms like Salesforce, Snowflake, ServiceNow, and HubSpot, Sweep reads live metadata and gives AI agents the context they need to understand, plan, and govern changes…
  api_count: 2
  score_band: developing
  score_composite: 52.2
  shared: 2
- slug: coval
  name: Coval
  description: Coval is the deployment-readiness platform for voice and chat AI agents. Teams simulate thousands of realistic conversation scenarios before launch, monitor real production calls, and improve reliability with metrics and human review. Cova…
  api_count: 20
  score_band: developing
  score_composite: 51.6
  shared: 2
- slug: scrapingant
  name: ScrapingAnt
  description: ScrapingAnt is a web-data infrastructure platform operated by DATAANT that puts headless Chrome rendering, a rotating pool of 3M+ residential and datacenter proxies, CAPTCHA avoidance and AI-powered extraction behind a single HTTP API. One…
  api_count: 2
  score_band: developing
  score_composite: 51.2
  shared: 2
- slug: google-gemini
  name: Google Gemini
  description: Google's multimodal AI model APIs for text, image, audio, and video understanding.
  api_count: 1
  score_band: developing
  score_composite: 50.7
  shared: 2
---
