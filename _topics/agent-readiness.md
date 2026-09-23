---
layout: topic
slug: agent-readiness
name: Agent Readiness
kind: topic
description: A topic index covering the operational practices, signals, and patterns that make an API surface safely usable by autonomous AI agents rather than only by humans. Catalogs the specifications, identity layers, agent skill formats, and edge-layer signals that combine into a coherent agent-readiness posture, with a dimension model, JSON Schema, JSON-LD context, vocabulary, and example signal records for representative providers.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/agent-readiness.png
tags:
- Agent Readiness
- AI Agents
- API Discovery
- API Governance
- Machine-Readable APIs
- MCP
- OpenAPI
- AsyncAPI
repo: https://github.com/api-evangelist/agent-readiness
api_count: 15
apis:
- name: Model Context Protocol (MCP)
  description: An open JSON-RPC protocol that lets AI agents talk to tools, resources, and prompts through a uniform server surface. MCP is the most direct expression of "an API designed for an agent" — every API surface that ships an MCP server scores h…
  url: https://modelcontextprotocol.io
- name: OpenAPI Specification
  description: The dominant machine-readable contract for HTTP APIs. Presence of a public OpenAPI document — with examples, error schemas, security schemes, and rate-limit headers — is the single highest-leverage agent-readiness signal for a REST surface…
  url: https://www.openapis.org
- name: AsyncAPI Specification
  description: Machine-readable contract for event-driven APIs (webhooks, message brokers, streaming). Agent-readiness for event surfaces depends on whether the provider ships an AsyncAPI document so agents can subscribe, dispatch, and validate events pr…
  url: https://www.asyncapi.com
- name: JSON Schema
  description: The vocabulary that lets an agent validate request and response bodies against typed contracts. Published JSON Schemas (independent of, or embedded in, an OpenAPI) are a strong agent-readiness signal because they let agents self-correct pa…
  url: https://json-schema.org
- name: Agent Skills
  description: A community schema for publishing operational instructions an agent should follow when using a site or API. A provider that ships a `/skills/` directory with a skill index is signalling that it has thought about the agent workflow, not jus…
  url: https://agentskills.io
- name: /.well-known/api-catalog (RFC 9727)
  description: RFC 9727 defines `/.well-known/api-catalog` as the canonical machine entrypoint for discovering an organization's APIs, formatted as an RFC 9264 linkset. Presence of a catalog at this path is one of the cheapest, highest-impact agent-readi…
  url: https://www.rfc-editor.org/rfc/rfc9727.html
- name: HTTP Message Signatures (RFC 9421)
  description: A cryptographic signature scheme for HTTP messages, used by the emerging web-bot-auth profile to let agents authenticate themselves to origins. Provider support for verifying or surfacing RFC 9421 signatures is a forward-looking agent-read…
  url: https://www.rfc-editor.org/rfc/rfc9421.html
- name: Web Bot Auth (draft)
  description: IETF draft layering an "identified bot" profile on top of RFC 9421. A provider that publishes a directory of verified agent identities — or surfaces Web Bot Auth verdicts in its responses — is making agent traffic legible at the protocol l…
  url: https://datatracker.ietf.org/doc/draft-meunier-web-bot-auth-architecture/
- name: Content-Usage / AIPREF (IETF AIPREF WG)
  description: 'The IETF AIPREF working group''s effort to standardise machine-readable AI usage preferences (e.g. `Content-Usage: ai-input=y, ai-train=n`). A provider that publishes explicit AIPREF signals is making its consent posture legible to agents r…'
  url: https://datatracker.ietf.org/wg/aipref/about/
- name: Cloudflare Content Signals
  description: Cloudflare's `Content-Signal` robots.txt directive, complementing the AIPREF drafts. Together they let an origin separate "crawl for search" from "use for AI input" from "use for AI training" — a concrete agent-readiness signal that the op…
  url: https://blog.cloudflare.com/content-signals-policy/
- name: APIs.json
  description: The APIs.json format describes a provider's API portfolio in one machine-readable document. Publishing `/apis.json` (or `/apis.yml`) at the site root is the agent-readiness equivalent of a site identity card — it tells an agent who the ope…
  url: https://apisjson.org
- name: OpenID Connect
  description: Identity layer on top of OAuth 2.0. Agent-readiness for authenticated APIs depends on clear, discoverable OIDC metadata (`/.well-known/openid-configuration`) so agents can negotiate auth without reading prose.
  url: https://openid.net/connect/
- name: Stripe API (reference provider)
  description: Reference provider for the agent-readiness signal set. Stripe publishes its full OpenAPI, ships idempotency keys, surfaces rate-limit headers, has a consistent error envelope, and exposes a status page and changelog — close to a maximal ag…
  url: https://docs.stripe.com/api
- name: GitHub REST + GraphQL API (reference provider)
  description: Reference provider with arguably the most extensively-tooled developer surface on the web. Public OpenAPI, GraphQL schema, webhooks, conditional requests, explicit `X-RateLimit-*` headers, status page, and an MCP server — a near-complete a…
  url: https://docs.github.com/en/rest
- name: Twilio API (reference provider)
  description: Reference provider with strong agent-readiness signals on the messaging side — published OpenAPI, idempotency on resource creation, structured error codes, signed webhooks, status page, and SDKs in every major language.
  url: https://www.twilio.com/docs
links:
- type: IssueTracker
  url: https://github.com/api-evangelist/agent-readiness/issues
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/agent-readiness/blob/main/security/agent-readiness-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/agent-readiness/blob/main/security/agent-readiness-domain-security.yml
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: GitHubRepository
  url: https://github.com/api-evangelist/agent-readiness
- type: Documentation
  url: https://github.com/api-evangelist/agent-readiness/blob/main/README.md
- type: JSONSchema
  url: https://github.com/api-evangelist/agent-readiness/blob/main/json-schema/agent-readiness-signal-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/agent-readiness/blob/main/json-schema/agent-readiness-provider-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/agent-readiness/blob/main/json-ld/agent-readiness-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/agent-readiness/blob/main/vocabulary/agent-readiness-vocabulary.yaml
provider_count: 379
providers:
- slug: apis-io
  name: APIs.io
  description: APIs.io is an open-source API search engine and federated discovery network built on the APIs.json specification. It indexes API providers and their individual APIs across the public internet along with the machine-readable artifacts they…
  api_count: 20
  score_band: exemplar
  score_composite: 88.8
  shared: 4
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 72.4
  shared: 4
- slug: farmdash
  name: FarmDash Agent Hub
  description: FarmDash is a zero-custody intelligence and control layer for DeFi agents and airdrop farmers, combining Trail Heat opportunity scoring, Signal Architect swap routing, wallet and Sybil-risk intelligence, and Hyperliquid futures research ac…
  api_count: 1
  score_band: developing
  score_composite: 53.5
  shared: 4
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: developing
  score_composite: 50.0
  shared: 4
- slug: api-evangelist
  name: API Evangelist
  description: The index of everything available via the API Evangelist developer portal at developer.apievangelist.com — sixteen years of API research served as one REST API, an MCP server for agents, and the static JSON feeds behind each network collec…
  api_count: 2
  score_band: exemplar
  score_composite: 66.9
  shared: 3
- slug: archbee
  name: Archbee
  description: Archbee is a documentation and knowledge-portal platform for software teams. It creates, manages and publishes technical documentation, API references and internal wikis, with collaborative editing, revision history, branching and review,…
  api_count: 11
  score_band: exemplar
  score_composite: 66.9
  shared: 3
- slug: explorium
  name: Explorium
  description: Explorium is the B2B data layer for AI agents and go-to-market systems. Its AgentSource platform is one external-data and enrichment API plus a hosted MCP server, resolving, fetching, enriching and monitoring a company dataset and a people…
  api_count: 1
  score_band: strong
  score_composite: 65.9
  shared: 3
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: strong
  score_composite: 65.1
  shared: 3
- slug: taskfolk
  name: Taskfolk
  description: Taskfolk is a project-management and issue-tracking platform built for teams and their AI agents working side by side, operated by UTTER L.L.C-FZ of Dubai, UAE. Workspaces contain projects; projects contain issues moved across board, backl…
  api_count: 4
  score_band: strong
  score_composite: 63.0
  shared: 3
- slug: improvado
  name: Improvado
  description: Improvado is a marketing intelligence and AI-agent platform that connects, extracts, transforms, and loads data from 876+ marketing, advertising, sales, and analytics sources into governed data pipelines, warehouses, and BI tools. Its Embe…
  api_count: 1
  score_band: strong
  score_composite: 62.5
  shared: 3
- slug: routebase
  name: Routebase
  description: API lifecycle platform covering Design (visual OpenAPI editor), Mock (spec-driven mock servers), Test (suites, assertions, OWASP security scanning), Document (published docs portals), and Agents (MCP server), built around a single living O…
  api_count: 1
  score_band: strong
  score_composite: 62.1
  shared: 3
- slug: orthogonal
  name: Orthogonal
  description: Orthogonal is a unified API and payment layer for AI agents, backed by Pantera Capital and Y Combinator. An agent describes what it needs in natural language and Orthogonal returns the right service from a catalog of 40+ third-party APIs (…
  api_count: 2
  score_band: strong
  score_composite: 56.8
  shared: 3
- slug: reachdesk
  name: Reachdesk
  description: Reachdesk is a global B2B corporate gifting and direct mail platform that enables sales, marketing, and customer success teams to send physical gifts, branded merchandise, and digital rewards at scale. The Reachdesk REST API allows program…
  api_count: 2
  score_band: strong
  score_composite: 56.2
  shared: 3
- slug: jentic
  name: Jentic
  description: Jentic is an AI infrastructure company building the agentic knowledge layer for APIs. Founded in late 2024 and backed by $4.5M in pre-seed funding, Jentic enables enterprises to confidently manage, scale, and govern AI agent initiatives in…
  api_count: 1
  score_band: strong
  score_composite: 54.3
  shared: 3
- slug: assetfare
  name: AssetFare
  description: A capped, non-custodial routing API for a single corridor — Solana SOL to Base native ETH — aimed at AI agents. It returns fee-inclusive quotes and bounded unsigned actions; the caller's agent verifies, signs, and submits every transaction…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 3
- slug: sweep
  name: Sweep
  description: Sweep is the agentic layer for enterprise systems. By connecting to platforms like Salesforce, Snowflake, ServiceNow, and HubSpot, Sweep reads live metadata and gives AI agents the context they need to understand, plan, and govern changes…
  api_count: 2
  score_band: developing
  score_composite: 51.6
  shared: 3
- slug: channelseal
  name: ChannelSeal
  description: ChannelSeal scores, monitors, and protects the interfaces AI agents reach — APIs, MCP servers and other agents — with an Interface Scorecard per interface (agent usability, governance, risk, compliance, security), sensitive-data-flow ident…
  api_count: 5
  score_band: developing
  score_composite: 51.1
  shared: 3
- slug: elva
  name: Elva
  description: 'API management platform for the agentic era: reads repos to build an API catalog, enforces per-audience contracts, generates tests, and turns APIs into governed, hosted MCP servers for AI agents. Built by Theneo. Exposes a public no-auth O…'
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 3
- slug: agntcy
  name: AGNTCY
  description: AGNTCY is the open collective for agent interoperability, initiated by Outshift — Cisco's incubation group — and governed under the Linux Foundation (LF Projects, LLC), developed in the open across 52 public repositories. It publishes spec…
  api_count: 4
  score_band: developing
  score_composite: 47.9
  shared: 3
- slug: liblab
  name: Liblab
  description: liblab generates and publishes type-safe, idiomatic SDKs in TypeScript, Python, Java, .NET, Go, PHP, and Terraform from OpenAPI/Swagger/Postman specs, plus MCP servers that expose those APIs to AI agents. The platform ships a CLI, hosted p…
  api_count: 4
  score_band: thin
  score_composite: 28.8
  shared: 3
- slug: onescreen-ai
  name: OneScreen AI
  description: OneScreen AI is a data-driven out-of-home (OOH) advertising company that makes real-world media — billboards, transit, and place-based advertising — as queryable and buyable as any digital channel. It combines more than 1,500 OOH audience…
  api_count: 1
  score_band: thin
  score_composite: 26.6
  shared: 3
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 20.0
  shared: 3
- slug: crow
  name: Crow
  description: Crow is a Y Combinator (Winter 2026) company building an AI infrastructure platform that makes any web or mobile application AI-native. Instead of a simple chatbot, Crow embeds an agent that connects to a product's own APIs and MCP servers…
  api_count: 1
  score_band: emerging
  score_composite: 18.3
  shared: 3
- slug: zoominfo
  name: ZoomInfo
  description: 'ZoomInfo is a B2B go-to-market intelligence platform whose contact and company database, buyer-intent signals, scoops and news feeds are sold to sales, marketing, operations and recruiting teams. Its API estate is mid-migration: the legacy…'
  api_count: 7
  score_band: exemplar
  score_composite: 84.7
  shared: 2
- slug: close
  name: Close
  description: Close is an inside-sales CRM with calling, email, SMS, and WhatsApp built in. The Close API exposes leads, contacts, opportunities, tasks, activities (calls, emails, SMS, meetings, notes), pipelines, custom objects, sequences, smart views,…
  api_count: 2
  score_band: exemplar
  score_composite: 79.8
  shared: 2
- slug: forcedream-ai
  name: ForceDream
  description: 'ForceDream Ltd (UK Company No. 17057770, London) operates a paid, verifiable AI-agent marketplace it calls the ForceDream Intelligence OS: specialist agents for summarisation, structured-data extraction, code generation, security scanning,…'
  api_count: 3
  score_band: exemplar
  score_composite: 77.0
  shared: 2
- slug: 0xarchive
  name: 0xArchive
  description: 0xArchive is a replayable market-data archive for two decentralised perpetuals venues, Hyperliquid and Lighter, delivered as one REST API, one WebSocket API that carries both live subscriptions and historical replay on a single connection,…
  api_count: 2
  score_band: exemplar
  score_composite: 76.4
  shared: 2
- slug: relevance-ai
  name: Relevance AI
  description: Relevance AI is an agent platform for building, testing and running specialist AI agents and multi-agent "workforces" — teams of agents that coordinate on a shared goal. Domain experts build agents in a no-code visual builder, hold them to…
  api_count: 1
  score_band: exemplar
  score_composite: 76.3
  shared: 2
- slug: arcade
  name: Arcade
  description: Arcade.dev is the MCP runtime for production AI agent deployments. The Arcade Engine — a hosted or self-hostable API surface — handles OAuth user authorization, manages user tokens, and exposes 7,000+ pre-built integrations as Model Contex…
  api_count: 4
  score_band: exemplar
  score_composite: 76.2
  shared: 2
- slug: drippay
  name: Drippay
  description: Drippay, Inc. is a Y Combinator company (YC P26) that operates two connected products. dreach — renamed from drip in 2026, with usedrip.ai now redirecting to dreach.ai — is a local-first Mac app for staffing, recruiting and executive searc…
  api_count: 1
  score_band: exemplar
  score_composite: 76.1
  shared: 2
---
