---
layout: topic
slug: jules-md
name: JULES.md
kind: topic
description: JULES.md is a configuration file format for the Google Jules AI coding agent, providing project-specific instructions, architecture context, and coding standards to guide AI-assisted development workflows. Similar in spirit to AGENTS.md, CLAUDE.md, and other agent-context files, JULES.md scopes Jules behavior to a repository.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/jules-md.png
tags:
- AI Agents
- AI Copilot
- Developer Workflow
- Google Jules
- Agent Configuration
- Coding Agents
repo: https://github.com/api-evangelist/jules-md
api_count: 1
apis:
- name: Google Jules AI
  description: Google Jules is an asynchronous AI coding agent that uses JULES.md configuration files to understand project context and assist with software development tasks across a repository.
  url: https://jules.google.com/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/jules-md/blob/main/security/jules-md-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/jules-md/blob/main/security/jules-md-domain-security.yml
- type: Website
  url: https://jules.google.com/
- type: Documentation
  url: https://jules.google.com/
- type: LlmsText
  url: https://jules.google.com/llms.txt
provider_count: 26
providers:
- slug: cursorrules
  name: .cursorrules
  description: .cursorrules is a project-level configuration file used by the Cursor AI code editor to define custom rules, coding conventions, and behavioral instructions that shape how the editor's AI assistant generates and edits code. The file is pla…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: agent-md
  name: AGENT.md
  description: AGENT.md is a vendor-neutral AI coding agent configuration file format providing project context and instructions for AI agents. It serves as an alternative to AGENTS.md, unifying agent guidance across tools like GitHub Copilot, Cursor, Cl…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: codex-md
  name: CODEX.md
  description: CODEX.md is a project-level Markdown memory file that the OpenAI Codex CLI loads to bootstrap an AI coding agent with persistent project instructions, coding conventions, build and test commands, and team conventions. The OpenAI Codex CLI…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: gemini-md
  name: GEMINI.md
  description: GEMINI.md is the project context file convention used by the Google Gemini CLI to provide project-specific instructions, coding standards, architectural notes, and development workflows to the Gemini AI agent. The format follows a hierarch…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: guidelines-md
  name: Guidelines.md
  description: JetBrains Junie AI agent configuration file stored in the .junie/ directory providing persistent project-level context and coding guidelines for AI code assistants.
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: runloop-ai
  name: Runloop
  description: Runloop is the AI Agent Accelerator — secure code sandboxes (Devboxes), evaluation infrastructure (Benchmarks, Scenarios), and production-grade orchestration for AI coding agents at enterprise scale. The platform provides a single REST API…
  api_count: 14
  score_band: strong
  score_composite: 59.0
  shared: 2
- slug: assembled
  name: Assembled
  description: Assembled is a San Francisco-headquartered support operations platform that unifies workforce management (WFM), AI agents, and AI Copilot for modern customer support teams. Founded in 2020 by former Stripe operations engineers, Assembled l…
  api_count: 4
  score_band: strong
  score_composite: 57.5
  shared: 2
- slug: amika
  name: Amika
  description: Amika is a Y Combinator-backed infrastructure company for running AI coding agents in isolated cloud sandboxes. Teams spawn agents from Slack, Linear, GitHub, a CLI, a TypeScript SDK, or the hosted HTTP API to understand a codebase, run in…
  api_count: 1
  score_band: developing
  score_composite: 50.8
  shared: 2
- slug: standard-compute
  name: Standard Compute
  description: An independent, flat-rate LLM inference API for AI coding agents. Standard Compute runs a single OpenAI-compatible (and Anthropic Messages-compatible) inference endpoint that smart-routes each request to the best-fit model across closed fr…
  api_count: 1
  score_band: developing
  score_composite: 46.9
  shared: 2
- slug: aisera
  name: Aisera
  description: Aisera is an enterprise agentic AI platform that builds, deploys, and orchestrates AI agents and assistants for IT service management, HR, finance, procurement, and customer service. The AiseraGPT platform combines domain-specific LLMs, co…
  api_count: 4
  score_band: developing
  score_composite: 45.1
  shared: 2
- slug: kimetsu-dev
  name: Kimetsu
  description: Kimetsu (kimetsu.dev) is Rodrigo Córdoba's open-source infrastructure for coding agents. Kimetsu itself is a local, model-free memory sidecar — one Rust binary and one SQLite brain per project — that Claude Code, Codex, Cursor, Pi and Open…
  api_count: 2
  score_band: developing
  score_composite: 44.4
  shared: 2
- slug: ellipsis
  name: Ellipsis
  description: Ellipsis is a managed cloud platform for running autonomous coding agents at scale. Engineering teams define agents as YAML config files that live in their repositories, and Ellipsis runs them in isolated, ephemeral sandboxes to review pul…
  api_count: 1
  score_band: thin
  score_composite: 37.3
  shared: 2
- slug: hoplite
  name: Hoplite
  description: Hoplite is a cloud coding-agent platform (Y Combinator S26). You connect a GitHub repository, describe a task in a thread, and an autonomous agent does the work inside an isolated, cloned dev environment (a "sandbox") — reading and editing…
  api_count: 1
  score_band: thin
  score_composite: 35.8
  shared: 2
- slug: niteshift
  name: Niteshift
  description: Niteshift is the full-stack cloud for coding agents. Engineering teams define their dev environment, tools, and policies once, then run frontier or open-source coding agents (Claude Code, Codex, Cursor, OpenCode, Pi) inside fully configure…
  api_count: 0
  score_band: emerging
  score_composite: 25.8
  shared: 2
- slug: openblock-labs
  name: OpenBlock Labs
  description: OpenBlock Labs builds OB-1, a self-improving autonomous coding agent that automates the software development lifecycle from PM to PR. OB-1 runs as a native terminal CLI and inside VS Code and JetBrains IDEs, consumes MCP (Model Context Pro…
  api_count: 1
  score_band: emerging
  score_composite: 23.5
  shared: 2
- slug: continua
  name: Continua
  description: Continua AI, Inc. is a Brooklyn-based startup founded by former Google Distinguished Engineer David Petrou and backed by GV, Bessemer Venture Partners, and angel investors. Its product, Wheelie, is a public Development OS for agentic codin…
  api_count: 0
  score_band: emerging
  score_composite: 22.8
  shared: 2
- slug: perseus
  name: Perseus
  description: Perseus (legal name Efficient Systems Inc.) is an applied AI lab focused on semantic search in latent spaces, founded by Samrath Chadha and backed by Y Combinator (Fall 2025 batch). Its first product is a retrieval engine that grounds codi…
  api_count: 0
  score_band: emerging
  score_composite: 22.1
  shared: 2
- slug: igent
  name: iGent
  description: iGent AI is a UK-based artificial intelligence company (Altrincham, Cheshire) building Maestro, an autonomous AI software-engineering agent. Maestro pairs adaptive autonomy with an ensemble of frontier AI models to plan, generate, test, an…
  api_count: 0
  score_band: emerging
  score_composite: 20.7
  shared: 2
- slug: sparkles
  name: Sparkles
  description: Sparkles (sparkles.dev) is a San Francisco developer-tools startup in Y Combinator's Winter 2026 batch building AI coding agents for a whole team, not just engineers. A technical owner connects the company's GitHub repositories and configu…
  api_count: 0
  score_band: emerging
  score_composite: 11.1
  shared: 2
- slug: everest
  name: Everest
  description: Everest is an early-stage Y Combinator (Fall 2025 / F25) startup based in San Francisco building agent-ready technical support for developer tools. Its premise is that a growing share of a devtool's users will be coding agents rather than…
  api_count: 0
  score_band: minimal
  score_composite: 3.3
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
- slug: clinerules
  name: .clinerules
  description: .clinerules is the rule-file convention used by the Cline open-source AI coding agent. Projects expose persistent guidance to Cline by placing a .clinerules/ directory at the repository root containing one or more Markdown or text files. E…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: claude-md
  name: CLAUDE.md
  description: CLAUDE.md is the markdown-based project memory format used by Anthropic's Claude Code CLI to give the model persistent, session-spanning instructions about a codebase. CLAUDE.md files are plain markdown that Claude Code loads at the start…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: instructions-md
  name: Instructions.md
  description: File-scoped custom instruction files for GitHub Copilot and VS Code, using applyTo patterns to target specific file types or tasks with tailored AI guidance. These markdown-based instruction files allow developers to provide context-specif…
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
