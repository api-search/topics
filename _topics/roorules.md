---
layout: topic
slug: roorules
name: .Roorules
kind: topic
description: .roorules is a configuration file convention for Roo Code, an open-source AI-powered autonomous coding assistant built for VS Code. The .roorules file allows developers to define project-specific coding conventions, style rules, architecture guidelines, and behavioral instructions that guide Roo Code AI agents when working within a codebase. Roo Code supports multiple AI providers including Anthropic Claude, OpenAI GPT-4, Google Gemini, and local LLMs via OpenAI-compatible APIs.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/roorules.png
tags:
- AI Agents
- AI Copilot
- Coding Assistant
- Coding Standards
- Developer Workflow
- LLM
- MCP
- Roo Code
- VS Code
repo: https://github.com/api-evangelist/roorules
api_count: 3
apis:
- name: Roo Code VS Code Extension
  description: Roo Code is an AI-powered autonomous coding agent for VS Code that reads and writes code across multiple files, executes terminal commands, manages browser interactions, and adapts to custom modes defined through .roorules and .roomodes co…
  url: https://roocode.com/
- name: Roo Code MCP Integration
  description: Roo Code supports the Model Context Protocol (MCP), allowing it to connect to external MCP servers for extended tool access including file systems, databases, APIs, and cloud services. MCP servers are configured in the Roo Code settings an…
  url: https://docs.roocode.com/features/mcp/
- name: Roo Code API Configuration Profiles
  description: API Configuration Profiles allow Roo Code users to create and switch between different sets of AI provider settings. Each profile configures a specific model and provider (e.g., Claude 3.7 Sonnet on Anthropic, GPT-4o on OpenAI, Gemini Pro…
  url: https://docs.roocode.com/features/api-configuration-profiles
links:
- type: IssueTracker
  url: https://github.com/RooCodeInc/Roo-Code/issues
- type: Releases
  url: https://github.com/RooCodeInc/Roo-Code/releases
- type: SecurityPolicy
  url: https://github.com/RooCodeInc/Roo-Code/blob/main/SECURITY.md
- type: License
  url: https://github.com/RooCodeInc/Roo-Code/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/roorules/blob/main/security/roorules-domain-security.yml
- type: Website
  url: https://roocode.com/
- type: Documentation
  url: https://docs.roocode.com/
- type: GitHubOrganization
  url: https://github.com/RooCodeInc
- type: GitHubRepository
  url: https://github.com/RooCodeInc/Roo-Code
- type: Vocabulary
  url: https://github.com/api-evangelist/roorules/blob/main/vocabulary/roorules-vocabulary.yml
- type: JSONLD
  url: https://github.com/api-evangelist/roorules/blob/main/json-ld/roorules-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/roorules/blob/main/json-schema/roorules-config-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/roorules/blob/main/json-structure/roorules-config-structure.json
- type: Marketplace
  url: https://marketplace.visualstudio.com/items?itemName=RooVeterinaryInc.roo-cline
- type: Discord
  url: https://discord.gg/roocode
- type: X
  url: https://twitter.com/roo_code
provider_count: 446
providers:
- slug: cursorrules
  name: .cursorrules
  description: .cursorrules is a project-level configuration file used by the Cursor AI code editor to define custom rules, coding conventions, and behavioral instructions that shape how the editor's AI assistant generates and edits code. The file is pla…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 5
- slug: refact-ai
  name: Refact.ai
  description: Refact.ai is an open-source, local-first AI coding assistant and autonomous software-engineering agent built by Small Magellanic Cloud Ai Ltd. ("SmallCloud"). The product combines an IDE-integrated chat experience (Ask / Explore / Debug /…
  api_count: 2
  score_band: emerging
  score_composite: 12.6
  shared: 4
- slug: agent-md
  name: AGENT.md
  description: AGENT.md is a vendor-neutral AI coding agent configuration file format providing project context and instructions for AI agents. It serves as an alternative to AGENTS.md, unifying agent guidance across tools like GitHub Copilot, Cursor, Cl…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: codex-md
  name: CODEX.md
  description: CODEX.md is a project-level Markdown memory file that the OpenAI Codex CLI loads to bootstrap an AI coding agent with persistent project instructions, coding conventions, build and test commands, and team conventions. The OpenAI Codex CLI…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: gemini-md
  name: GEMINI.md
  description: GEMINI.md is the project context file convention used by the Google Gemini CLI to provide project-specific instructions, coding standards, architectural notes, and development workflows to the Gemini AI agent. The format follows a hierarch…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: guidelines-md
  name: Guidelines.md
  description: JetBrains Junie AI agent configuration file stored in the .junie/ directory providing persistent project-level context and coding guidelines for AI code assistants.
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: instructions-md
  name: Instructions.md
  description: File-scoped custom instruction files for GitHub Copilot and VS Code, using applyTo patterns to target specific file types or tasks with tailored AI guidance. These markdown-based instruction files allow developers to provide context-specif…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: arcade
  name: Arcade
  description: Arcade.dev is the MCP runtime for production AI agent deployments. The Arcade Engine — a hosted or self-hostable API surface — handles OAuth user authorization, manages user tokens, and exposes 7,000+ pre-built integrations as Model Contex…
  api_count: 1
  score_band: exemplar
  score_composite: 72.9
  shared: 3
- slug: alphaai
  name: AlphaAI
  description: A REST API and agent-native platform for relevance-scored, ticker-linked financial news, built for trading bots, agent backends, and dashboards. Every article is enriched at ingest with a 1-10 relevance score, one of fourteen categories, v…
  api_count: 1
  score_band: exemplar
  score_composite: 66.7
  shared: 3
- slug: webcrawlerapi-com
  name: WebCrawlerAPI
  description: WebCrawlerAPI is a web crawling and scraping API from 103 Labs (Netherlands) that turns websites into clean, LLM-ready markdown, cleaned text, HTML or link lists for AI agents, support bots and RAG pipelines. It offers asynchronous multi-p…
  api_count: 3
  score_band: strong
  score_composite: 64.5
  shared: 3
- slug: gumloop
  name: Gumloop
  description: Gumloop is an AI-agent automation platform for building, deploying, and governing agents that automate real work — data analysis, customer support, CRM management, and back-office tasks — across tools like Slack, Microsoft Teams, and Gmail…
  api_count: 1
  score_band: strong
  score_composite: 57.8
  shared: 3
- slug: 558686-xyz
  name: gpt55-token-gateway
  description: gpt55-token-gateway is the self-chosen service name of an unnamed operator running two OpenAI-compatible AI API gateways on the 558686.xyz domain. GPT55 Model Gateway (gpt55.558686.xyz) sells single GPT-5.6 Luna, GPT-5.5 and GPT-5.3-codex…
  api_count: 3
  score_band: strong
  score_composite: 57.2
  shared: 3
- slug: scrapingant
  name: ScrapingAnt
  description: ScrapingAnt is a web-data infrastructure platform operated by DATAANT that puts headless Chrome rendering, a rotating pool of 3M+ residential and datacenter proxies, CAPTCHA avoidance and AI-powered extraction behind a single HTTP API. One…
  api_count: 2
  score_band: developing
  score_composite: 51.2
  shared: 3
- slug: tarx-com
  name: TARXAN
  description: 'TARXAN Inc (TARX, Austin TX) builds a local-first AI agent runtime: free TARX_OS / TARX Desktop software for Apple Silicon Macs, a shell CLI that installs a local inference daemon and local MCP servers, an optional hosted "Supercomputer" r…'
  api_count: 3
  score_band: developing
  score_composite: 50.3
  shared: 3
- slug: aisera
  name: Aisera
  description: Aisera is an enterprise agentic AI platform that builds, deploys, and orchestrates AI agents and assistants for IT service management, HR, finance, procurement, and customer service. The AiseraGPT platform combines domain-specific LLMs, co…
  api_count: 4
  score_band: developing
  score_composite: 45.1
  shared: 3
- slug: smithery
  name: Smithery
  description: Smithery is a platform for discovering, deploying, and managing Model Context Protocol (MCP) servers and skills. It operates a public registry of community-built MCP extensions that AI agents can use to access external tools, data sources,…
  api_count: 2
  score_band: developing
  score_composite: 44.0
  shared: 3
- slug: dome-systems
  name: Dome Systems
  description: Dome Systems is the enterprise agentic operations platform — the system of control for the agent era. Founded in 2024 by Dave McJannet (former HashiCorp CEO) and Marc Holmes, and backed by Redpoint Ventures, Bessemer Venture Partners, and…
  api_count: 0
  score_band: thin
  score_composite: 33.8
  shared: 3
- slug: guildai
  name: Guild.ai
  description: Guild.ai is a control plane for AI agents that lets engineering teams build, deploy, govern, and share agents in production. Agents are authored in TypeScript with the @guildai/agents-sdk (alongside Guild Native and Goose recipe agent type…
  api_count: 1
  score_band: thin
  score_composite: 28.2
  shared: 3
- slug: agentsea
  name: AgentSea
  description: AgentSea is an open-source agent development kit (ADK) for building agentic AI applications, authored by Michael Fatoki-Bello and published under the lovekaizen GitHub account. It ships as twenty TypeScript/Node packages on npm under the @…
  api_count: 2
  score_band: emerging
  score_composite: 25.0
  shared: 3
- slug: fastmcp
  name: FastMCP
  description: FastMCP is the fast, Pythonic framework for building Model Context Protocol (MCP) servers, clients, and apps. Originally created by Jeremiah Lowin and maintained by PrefectHQ, FastMCP 1.0 was adopted into the official Anthropic MCP Python…
  api_count: 6
  score_band: emerging
  score_composite: 18.2
  shared: 3
- slug: aiignore
  name: .AIIgnore
  description: The .aiignore file is a configuration specification that tells AI coding agents and LLM-powered developer tools which files, directories, and content should not be read, processed, or modified. Modeled after .gitignore syntax, .aiignore fi…
  api_count: 1
  score_band: null
  score_composite: 0
  shared: 3
- slug: clinerules
  name: .clinerules
  description: .clinerules is the rule-file convention used by the Cline open-source AI coding agent. Projects expose persistent guidance to Cline by placing a .clinerules/ directory at the repository root containing one or more Markdown or text files. E…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: claude-md
  name: CLAUDE.md
  description: CLAUDE.md is the markdown-based project memory format used by Anthropic's Claude Code CLI to give the model persistent, session-spanning instructions about a codebase. CLAUDE.md files are plain markdown that Claude Code loads at the start…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: mcp-json
  name: mcp.json
  description: mcp.json is a Model Context Protocol configuration file format that defines MCP server connections for AI coding assistants and agents. It enables tool integration and enhanced AI capabilities through a standardized configuration schema.
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: tray-ai
  name: Tray.ai
  description: Tray.ai (formerly Tray.io) is an AI-ready enterprise orchestration platform for data and AI, combining a Merlin Agent Builder for no-code AI agent creation, an Agent Gateway for governed MCP server management, and an intelligent iPaaS with…
  api_count: 4
  score_band: exemplar
  score_composite: 89.3
  shared: 2
- slug: zoominfo
  name: ZoomInfo
  description: 'ZoomInfo is a B2B go-to-market intelligence platform whose contact and company database, buyer-intent signals, scoops and news feeds are sold to sales, marketing, operations and recruiting teams. Its API estate is mid-migration: the legacy…'
  api_count: 7
  score_band: exemplar
  score_composite: 87.3
  shared: 2
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 2
- slug: anthropic
  name: Anthropic
  description: Anthropic is an AI safety company and the creator of the Claude family of large language models (Opus, Sonnet, Haiku, and the Fable/Mythos frontier line). The Claude Developer Platform exposes them through a single REST API at api.anthropi…
  api_count: 6
  score_band: exemplar
  score_composite: 79.4
  shared: 2
- slug: relevance-ai
  name: Relevance AI
  description: Relevance AI is an agent platform for building, testing and running specialist AI agents and multi-agent "workforces" — teams of agents that coordinate on a shared goal. Domain experts build agents in a no-code visual builder, hold them to…
  api_count: 1
  score_band: exemplar
  score_composite: 78.5
  shared: 2
- slug: close
  name: Close
  description: Close is an inside-sales CRM with calling, email, SMS, and WhatsApp built in. The Close API exposes leads, contacts, opportunities, tasks, activities (calls, emails, SMS, meetings, notes), pipelines, custom objects, sequences, smart views,…
  api_count: 2
  score_band: exemplar
  score_composite: 75.3
  shared: 2
---
