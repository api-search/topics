---
layout: topic
slug: agents-md
name: AGENTS.md
kind: topic
description: AGENTS.md is an open standard file format that provides context and instructions to AI coding agents working on software projects. Like a README for agents, an AGENTS.md file lives in the project repository and tells AI agents how to build, test, and contribute code — including coding standards, build commands, testing procedures, and development conventions. Supported by over 60,000 open-source projects and major platforms including OpenAI Codex, Google Jules, Cursor, Devin, Windsurf, GitHub Copilot, and goose. Stewarded by the Agentic AI Foundation under the Linux Foundation.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/agents-md.png
tags:
- AI Agents
- AI Copilot
- Coding Standards
- Developer Workflow
- Open Standard
- Documentation
repo: https://github.com/api-evangelist/agents-md
api_count: 1
apis:
- name: AGENTS.md Specification
  description: The AGENTS.md specification defines a standard Markdown file format for providing project context, build instructions, coding standards, and testing procedures to AI coding agents. The file is version-controlled with the project and discov…
  url: https://agents.md/
links:
- type: Plans
  url: https://artifacts.apis.io/agents-md/plans/agents-md-plans-pricing.yml
- type: RateLimits
  url: https://artifacts.apis.io/agents-md/rate-limits/agents-md-rate-limits.yml
- type: FinOps
  url: https://artifacts.apis.io/agents-md/finops/agents-md-finops.yml
- type: Website
  url: https://www.agents.md/
- type: IssueTracker
  url: https://github.com/openai/agents.md/issues
- type: License
  url: https://github.com/openai/agents.md/blob/main/LICENSE
- type: DomainSecurity
  url: https://artifacts.apis.io/agents-md/security/agents-md-domain-security.yml
- type: Portal
  url: https://agents.md/
- type: Documentation
  url: https://agents.md/
- type: GitHubOrganization
  url: https://github.com/agentic-ai-foundation
- type: UsageTerms
  url: https://artifacts.apis.io/agents-md/terms/agents-md-terms-of-service.yml
- type: DataLicense
  url: https://artifacts.apis.io/agents-md/data-license/agents-md-data-license.yml
provider_count: 22
providers:
- slug: cursorrules
  name: .cursorrules
  description: .cursorrules is a project-level configuration file used by the Cursor AI code editor to define custom rules, coding conventions, and behavioral instructions that shape how the editor's AI assistant generates and edits code. The file is pla…
  api_count: 0
  score_band: null
  score_composite: 0
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
- slug: instructions-md
  name: Instructions.md
  description: File-scoped custom instruction files for GitHub Copilot and VS Code, using applyTo patterns to target specific file types or tasks with tailored AI guidance. These markdown-based instruction files allow developers to provide context-specif…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: archbee
  name: Archbee
  description: Archbee is a documentation and knowledge-portal platform for software teams. It creates, manages and publishes technical documentation, API references and internal wikis, with collaborative editing, revision history, branching and review,…
  api_count: 11
  score_band: exemplar
  score_composite: 70.8
  shared: 2
- slug: componecat-ai
  name: Componecat
  description: Componecat is a software catalog and MCP context service for AI agents, built by Shaftware. It catalogs an organization's systems, services and libraries with their owning teams, dependencies, API endpoint definitions and documentation, ke…
  api_count: 1
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: assembled
  name: Assembled
  description: Assembled is a San Francisco-headquartered support operations platform that unifies workforce management (WFM), AI agents, and AI Copilot for modern customer support teams. Founded in 2020 by former Stripe operations engineers, Assembled l…
  api_count: 4
  score_band: strong
  score_composite: 56.8
  shared: 2
- slug: sweep
  name: Sweep
  description: Sweep is the agentic layer for enterprise systems. By connecting to platforms like Salesforce, Snowflake, ServiceNow, and HubSpot, Sweep reads live metadata and gives AI agents the context they need to understand, plan, and govern changes…
  api_count: 2
  score_band: strong
  score_composite: 55.7
  shared: 2
- slug: corestory
  name: CoreStory
  description: CoreStory is an AI code intelligence platform that ingests large brownfield and legacy codebases and reverse-engineers a persistent understanding of how they work — generating product requirements (PRDs), technical specifications, dependen…
  api_count: 1
  score_band: developing
  score_composite: 45.9
  shared: 2
- slug: aisera
  name: Aisera
  description: Aisera is an enterprise agentic AI platform that builds, deploys, and orchestrates AI agents and assistants for IT service management, HR, finance, procurement, and customer service. The AiseraGPT platform combines domain-specific LLMs, co…
  api_count: 4
  score_band: developing
  score_composite: 43.0
  shared: 2
- slug: squiredocs-com
  name: squiredocs-com
  description: Squire Docs is an open‑source collaborative document editor designed for people and AI agents to edit the same documents in real time. Every edit is attributed, and the platform provides two‑way markdown synchronization with your repositor…
  api_count: 1
  score_band: thin
  score_composite: 37.0
  shared: 2
- slug: knowledgeforagents-com
  name: Knowledge for Agents
  description: Knowledge for Agents is a public knowledge network that records technical conversations, problems, candidate solutions, and outcomes related to AI agents and MCP troubleshooting. It allows agents and humans to read, search, and contribute…
  api_count: 1
  score_band: thin
  score_composite: 35.6
  shared: 2
- slug: supernova
  name: Supernova
  description: Supernova is an AI-powered platform for product teams that unifies design system management, documentation, code automation, and collaborative prototyping around a single source of truth for design tokens, components, and brand. Its "Conte…
  api_count: 0
  score_band: thin
  score_composite: 33.2
  shared: 2
- slug: diagramzu-ai
  name: DiagramZu
  description: DiagramZu is an MCP server plus shared workspace where Claude Code, Cursor, ChatGPT and any other MCP client write Mermaid diagrams directly. Its fourteen MCP tools search, create, read and update diagrams, browse folders, trace version hi…
  api_count: 2
  score_band: emerging
  score_composite: 18.7
  shared: 2
- slug: botclaw-tech
  name: BotClaw
  description: 'botclaw-tech is a company surfaced via the API Evangelist harvest backlog (source: mcp-registry) and added to the network as a stub for full-pipeline profiling.'
  api_count: 1
  score_band: emerging
  score_composite: 13.5
  shared: 2
- slug: aiignore
  name: .AIIgnore
  description: The .aiignore file is a configuration specification that tells AI coding agents and LLM-powered developer tools which files, directories, and content should not be read, processed, or modified. Modeled after .gitignore syntax, .aiignore fi…
  api_count: 1
  score_band: null
  score_composite: 0
  shared: 2
- slug: prompt-md
  name: .Prompt.md
  description: Reusable prompt template files for AI coding assistants, defining task-specific instructions that can be executed from chat interfaces. Used for standardizing common development tasks like code review, refactoring, and test generation.
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: mcp-json
  name: mcp.json
  description: mcp.json is a Model Context Protocol configuration file format that defines MCP server connections for AI coding assistants and agents. It enables tool integration and enhanced AI capabilities through a standardized configuration schema.
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
---
