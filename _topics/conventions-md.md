---
layout: topic
slug: conventions-md
name: CONVENTIONS.md
kind: topic
description: CONVENTIONS.md is a Markdown convention popularized by AI pair programming tools such as aider and adopted by AI coding agents like Cursor, Cline, and Claude Code. It documents project-specific coding standards, library preferences, naming conventions, architecture decisions, and development practices in plain natural language so both human developers and AI assistants share the same expectations. The file is loaded into the model context to steer code generation toward project conventions.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/conventions-md.png
tags:
- AI Coding
- Aider
- Best Practices
- Coding Standards
- Conventions
- Developer Workflow
- Documentation
- Markdown
- Project Configuration
repo: https://github.com/api-evangelist/conventions-md
api_count: 2
apis:
- name: CONVENTIONS.md Format
  description: The CONVENTIONS.md format is a free-form Markdown file describing the coding rules an AI coding agent should follow inside a repository. The file is loaded into the chat context, typically in read-only mode, and may be referenced via /read…
  url: https://aider.chat/docs/usage/conventions.html
- name: AI Coding Conventions Ecosystem
  description: CONVENTIONS.md sits alongside several closely related AI coding conventions. CLAUDE.md is used by Claude Code for repository memory. .cursor/rules and .cursorrules are used by Cursor. .github/copilot- instructions.md is used by GitHub Copi…
  url: https://docs.anthropic.com/en/docs/claude-code/memory
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/conventions-md/blob/main/security/conventions-md-domain-security.yml
- type: Documentation
  url: https://aider.chat/docs/usage/conventions.html
- type: Documentation
  url: https://docs.anthropic.com/en/docs/claude-code/memory
- type: Documentation
  url: https://docs.cursor.com/context/rules-for-ai
- type: Documentation
  url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot
- type: Blog
  url: https://aider.chat/feed.xml
provider_count: 17
providers:
- slug: claude-md
  name: CLAUDE.md
  description: CLAUDE.md is the markdown-based project memory format used by Anthropic's Claude Code CLI to give the model persistent, session-spanning instructions about a codebase. CLAUDE.md files are plain markdown that Claude Code loads at the start…
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
  shared: 3
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: hackmd
  name: HackMD
  description: HackMD is a real-time collaborative Markdown editor and knowledge base for individuals and teams. Multiple people can co-edit a Markdown document live, organize notes into folders and team workspaces, and publish them as web pages, slide d…
  api_count: 1
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 2
- slug: slate
  name: Slate
  description: Slate is an open-source tool for creating beautiful, three-panel API documentation from Markdown. Built on Ruby and Middleman, Slate renders a left-side navigation menu, a center documentation panel, and a right-side code sample panel. It…
  api_count: 1
  score_band: emerging
  score_composite: 25.6
  shared: 2
- slug: vitepress
  name: VitePress
  description: VitePress is a Vite and Vue powered static site generator widely used for developer documentation. It converts Markdown content into fast, beautiful documentation sites with support for Vue components embedded directly in Markdown pages. V…
  api_count: 2
  score_band: emerging
  score_composite: 18.4
  shared: 2
- slug: changelog-md
  name: CHANGELOG.md (Keep a Changelog)
  description: CHANGELOG.md is a community convention for a human-readable, Markdown- formatted file at the root of a project that records notable changes between versions. The leading specification is "Keep a Changelog" by Olivier Lacan, which defines a…
  api_count: 0
  score_band: emerging
  score_composite: 13.3
  shared: 2
- slug: mkdocs
  name: MkDocs
  description: MkDocs is a fast, simple, and beautiful static site generator designed for building project documentation from Markdown source files. Written in Python, it reads a single YAML configuration file (mkdocs.yml) and converts a directory of Mar…
  api_count: 0
  score_band: emerging
  score_composite: 11.9
  shared: 2
- slug: markup-language
  name: Markup Language
  description: A markup language is a system for annotating a document in a way that is syntactically distinguishable from the text. Examples include HTML, XML, Markdown, LaTeX, and others that add semantic meaning or formatting instructions to text cont…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 2
- slug: clinerules
  name: .clinerules
  description: .clinerules is the rule-file convention used by the Cline open-source AI coding agent. Projects expose persistent guidance to Cline by placing a .clinerules/ directory at the repository root containing one or more Markdown or text files. E…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: cursorrules
  name: .cursorrules
  description: .cursorrules is a project-level configuration file used by the Cursor AI code editor to define custom rules, coding conventions, and behavioral instructions that shape how the editor's AI assistant generates and edits code. The file is pla…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: agent-md
  name: AGENT.md
  description: AGENT.md is a vendor-neutral AI coding agent configuration file format providing project context and instructions for AI agents. It serves as an alternative to AGENTS.md, unifying agent guidance across tools like GitHub Copilot, Cursor, Cl…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: codex-md
  name: CODEX.md
  description: CODEX.md is a project-level Markdown memory file that the OpenAI Codex CLI loads to bootstrap an AI coding agent with persistent project instructions, coding conventions, build and test commands, and team conventions. The OpenAI Codex CLI…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: contributing-md
  name: CONTRIBUTING.md
  description: CONTRIBUTING.md is a community health convention used by open source projects on GitHub and other platforms to document how external contributors can participate. The file communicates contribution guidelines, pull request processes, issue…
  api_count: 2
  score_band: null
  score_composite: 0
  shared: 2
- slug: guidelines-md
  name: Guidelines.md
  description: JetBrains Junie AI agent configuration file stored in the .junie/ directory providing persistent project-level context and coding guidelines for AI code assistants.
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
---
