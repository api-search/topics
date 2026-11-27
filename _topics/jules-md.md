---
layout: topic
slug: jules-md
name: JULES.md
kind: topic
description: JULES.md is a configuration file format for the Google Jules AI coding agent, providing project-specific instructions, architecture context, and coding standards to guide AI-assisted development workflows. Similar in spirit to AGENTS.md, CLAUDE.md, and other agent-context files, JULES.md scopes Jules behavior to a repository. Jules also exposes a public REST API (jules.googleapis.com, v1alpha) for sessions, activities and sources, authenticated with an x-goog-api-key header, and a Jules Tools CLI (@google/jules).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/jules-md.png
tags:
- AI Agents
- AI Copilot
- Developer Workflow
- Google Jules
- Agent Configuration
- Coding Agents
repo: https://github.com/api-evangelist/jules-md
api_count: 3
apis:
- name: Google Jules AI
  description: Google Jules is an asynchronous AI coding agent that uses JULES.md configuration files to understand project context and assist with software development tasks across a repository.
  url: https://jules.google.com/
- name: JULES.md Md Sessions API
  description: The Md Sessions API from JULES.md — 8 operation(s) for md sessions.
  url: https://jules.google.com/
- name: JULES.md Md Sources API
  description: The Md Sources API from JULES.md — 2 operation(s) for md sources.
  url: https://jules.google.com/
links:
- type: AgenticAccess
  url: https://artifacts.apis.io/jules-md/agentic-access/jules-md-agentic-access.yml
- type: Spectral
  url: https://artifacts.apis.io/jules-md/rules/jules-md-rules.yml
- type: JSONLD
  url: https://artifacts.apis.io/jules-md/json-ld/jules-md-context.jsonld
- type: Vocabulary
  url: https://artifacts.apis.io/jules-md/vocabulary/jules-md-vocabulary.yml
- type: AgentSkill
  url: https://artifacts.apis.io/jules-md/skills/_index.yml
- type: DataModel
  url: https://artifacts.apis.io/jules-md/data-model/jules-md-data-model.yml
- type: CLI
  url: https://artifacts.apis.io/jules-md/cli/jules-md-cli.yml
- type: ErrorCatalog
  url: https://artifacts.apis.io/jules-md/errors/jules-md-problem-types.yml
- type: Conformance
  url: https://artifacts.apis.io/jules-md/conformance/jules-md-conformance.yml
- type: LLMsTxt
  url: https://artifacts.apis.io/jules-md/llms/jules-md-llms.txt
- type: WellKnown
  url: https://artifacts.apis.io/jules-md/well-known/jules-md-well-known.yml
- type: Hosts
  url: https://artifacts.apis.io/jules-md/hosts/jules-md-hosts.yml
- type: SDKs
  url: https://artifacts.apis.io/jules-md/packages/jules-md-packages.yml
- type: Packages
  url: https://artifacts.apis.io/jules-md/packages/jules-md-packages.yml
- type: Security
  url: https://accounts.google.com/ServiceLogin?hl=en-US&continue=https://myaccount.google.com/intro/security
- type: Sandbox
  url: https://play.google.com/console/about/
- type: Login
  url: https://accounts.google.com/v3/signin/identifier?continue=https://docs.google.com/&emr=1&followup=https://docs.google.com/&osid=1&passive=1209600&flowName=GlifWebSignIn&flowEntry=ServiceLogin&dsh=S639346758:1794455781883337
- type: DeveloperPortal
  url: https://developers.google.com/
- type: OAuthScopes
  url: https://artifacts.apis.io/jules-md/scopes/jules-md-scopes.yml
- type: Authentication
  url: https://artifacts.apis.io/jules-md/authentication/jules-md-authentication.yml
- type: Plans
  url: https://artifacts.apis.io/jules-md/plans/jules-md-plans-pricing.yml
- type: RateLimits
  url: https://artifacts.apis.io/jules-md/rate-limits/jules-md-rate-limits.yml
- type: FinOps
  url: https://artifacts.apis.io/jules-md/finops/jules-md-finops.yml
- type: VulnerabilityDisclosure
  url: https://artifacts.apis.io/jules-md/security/jules-md-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://artifacts.apis.io/jules-md/security/jules-md-domain-security.yml
- type: Website
  url: https://jules.google.com/
- type: Documentation
  url: https://jules.google/docs
- type: APIReference
  url: https://developers.google.com/jules/api/reference/rest
- type: GettingStarted
  url: https://jules.google/docs/api/reference/
- type: ChangeLog
  url: https://jules.google/docs/changelog/
- type: PrivacyPolicy
  url: https://policies.google.com/privacy
- type: Pricing
  url: https://jules.google/docs/usage-limits/
provider_count: 32
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
- slug: tembo
  name: Tembo
  description: Tembo (tembo.io) is a cloud platform for running AI coding agents (Claude Code, Codex, Cursor, Amp, OpenCode and others) in isolated, shareable sandbox environments connected to repositories, issue trackers, observability tools and databas…
  api_count: 1
  score_band: exemplar
  score_composite: 71.7
  shared: 2
- slug: amika
  name: Amika
  description: Amika is a Y Combinator-backed infrastructure company for running AI coding agents in isolated cloud sandboxes. Teams spawn agents from Slack, Linear, GitHub, a CLI, a TypeScript SDK, or the hosted HTTP API to understand a codebase, run in…
  api_count: 1
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: runloop-ai
  name: Runloop
  description: Runloop is the AI Agent Accelerator — secure code sandboxes (Devboxes), evaluation infrastructure (Benchmarks, Scenarios), and production-grade orchestration for AI coding agents at enterprise scale. The platform provides a single REST API…
  api_count: 14
  score_band: strong
  score_composite: 58.2
  shared: 2
- slug: ctlsurf-com
  name: ctlsurf
  description: ctlsurf is a shared workspace for people and their AI agents, built by Phenx Machine Learning Technologies Inc. Users create and revise documents, presentations, diagrams, datasets and tasks in the browser, and connected AI coding agents (…
  api_count: 2
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: assembled
  name: Assembled
  description: Assembled is a San Francisco-headquartered support operations platform that unifies workforce management (WFM), AI agents, and AI Copilot for modern customer support teams. Founded in 2020 by former Stripe operations engineers, Assembled l…
  api_count: 4
  score_band: strong
  score_composite: 56.8
  shared: 2
- slug: coordigent-com
  name: Coordigent
  description: Coordigent coordinates the AI coding agents a team runs on the same repository. It is a model-agnostic MCP server (coord-mcp) plus a command-line tool (coord) that connects to Claude Code, Codex, Cursor, VS Code, Windsurf and Kiro through…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: standard-compute
  name: Standard Compute
  description: An independent, flat-rate LLM inference API for AI coding agents. Standard Compute runs a single OpenAI-compatible (and Anthropic Messages-compatible) inference endpoint that smart-routes each request to the best-fit model across closed fr…
  api_count: 1
  score_band: developing
  score_composite: 50.6
  shared: 2
- slug: kimetsu-dev
  name: Kimetsu
  description: Kimetsu (kimetsu.dev) is Rodrigo Córdoba's open-source infrastructure for coding agents. Kimetsu itself is a local, model-free memory sidecar — one Rust binary and one SQLite brain per project — that Claude Code, Codex, Cursor, Pi and Open…
  api_count: 1
  score_band: developing
  score_composite: 47.8
  shared: 2
- slug: commonrig-com
  name: CommonRig
  description: CommonRig is an agent operating kit for Claude Code, Codex and opencode, sold by Benys Labs (an Australian registered business name; CommonRig is one of its products). The kit provides a single rule source rendered into CLAUDE.md and AGENT…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: corpole-com
  name: CorPole
  description: CorPole is a governance platform for teams building with AI coding agents. It keeps a solution's requirements, decisions and constraints as records that each carry a state (Draft, Approved, Authority, Retired), hands the agent only what is…
  api_count: 2
  score_band: developing
  score_composite: 44.8
  shared: 2
- slug: chiefisnext-com
  name: Chief
  description: Chief (chiefisnext.com) is an AI agent manager for Claude Code and Codex, plus agents from Gemini, Muse, DeepSeek and more, letting one person run many coding agents in parallel. It organizes work into projects, goals, tasks and milestones…
  api_count: 1
  score_band: developing
  score_composite: 44.7
  shared: 2
- slug: aisera
  name: Aisera
  description: Aisera is an enterprise agentic AI platform that builds, deploys, and orchestrates AI agents and assistants for IT service management, HR, finance, procurement, and customer service. The AiseraGPT platform combines domain-specific LLMs, co…
  api_count: 4
  score_band: developing
  score_composite: 43.0
  shared: 2
- slug: ellipsis
  name: Ellipsis
  description: Ellipsis is a managed cloud platform for running autonomous coding agents at scale. Engineering teams define agents as YAML config files that live in their repositories, and Ellipsis runs them in isolated, ephemeral sandboxes to review pul…
  api_count: 1
  score_band: thin
  score_composite: 38.2
  shared: 2
- slug: hoplite
  name: Hoplite
  description: Hoplite is a cloud coding-agent platform (Y Combinator S26). You connect a GitHub repository, describe a task in a thread, and an autonomous agent does the work inside an isolated, cloned dev environment (a "sandbox") — reading and editing…
  api_count: 1
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: niteshift
  name: Niteshift
  description: Niteshift is the full-stack cloud for coding agents. Engineering teams define their dev environment, tools, and policies once, then run frontier or open-source coding agents (Claude Code, Codex, Cursor, OpenCode, Pi) inside fully configure…
  api_count: 0
  score_band: thin
  score_composite: 28.4
  shared: 2
- slug: perseus
  name: Perseus
  description: Perseus (legal name Efficient Systems Inc.) is an applied AI lab focused on semantic search in latent spaces, founded by Samrath Chadha and backed by Y Combinator (Fall 2025 batch). Its first product is a retrieval engine that grounds codi…
  api_count: 0
  score_band: emerging
  score_composite: 25.8
  shared: 2
- slug: openblock-labs
  name: OpenBlock Labs
  description: OpenBlock Labs builds OB-1, a self-improving autonomous coding agent that automates the software development lifecycle from PM to PR. OB-1 runs as a native terminal CLI and inside VS Code and JetBrains IDEs, consumes MCP (Model Context Pro…
  api_count: 1
  score_band: emerging
  score_composite: 22.2
  shared: 2
- slug: continua
  name: Continua
  description: Continua AI, Inc. is a Brooklyn-based startup founded by former Google Distinguished Engineer David Petrou and backed by GV, Bessemer Venture Partners, and angel investors. Its product, Wheelie, is a public Development OS for agentic codin…
  api_count: 0
  score_band: emerging
  score_composite: 21.9
  shared: 2
- slug: igent
  name: iGent
  description: iGent AI is a UK-based artificial intelligence company (Altrincham, Cheshire) building Maestro, an autonomous AI software-engineering agent. Maestro pairs adaptive autonomy with an ensemble of frontier AI models to plan, generate, test, an…
  api_count: 0
  score_band: emerging
  score_composite: 21.3
  shared: 2
- slug: sparkles
  name: Sparkles
  description: Sparkles (sparkles.dev) is a San Francisco developer-tools startup in Y Combinator's Winter 2026 batch building AI coding agents for a whole team, not just engineers. A technical owner connects the company's GitHub repositories and configu…
  api_count: 0
  score_band: emerging
  score_composite: 12.1
  shared: 2
- slug: everest
  name: Everest
  description: Everest is an early-stage Y Combinator (Fall 2025 / F25) startup based in San Francisco building agent-ready technical support for developer tools. Its premise is that a growing share of a devtool's users will be coding agents rather than…
  api_count: 0
  score_band: minimal
  score_composite: 3.0
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
---
