---
layout: topic
slug: copilot-instructions-md
name: copilot-instructions.md
kind: topic
description: copilot-instructions.md is a GitHub Copilot custom instructions file placed at .github/copilot-instructions.md in a repository. It provides repository-specific guidance and preferences that GitHub Copilot Chat, Copilot in the IDE, and the Copilot coding agent automatically inject into prompts when working in the repository. The file is plain Markdown in natural language, helping the AI understand build, test, validation, framework, and style conventions so it can produce code that is consistent with the project's expectations and reduce pull request rejections caused by avoidable lint, CI, or convention failures.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/copilot-instructions-md.png
tags:
- AI Coding
- Coding Standards
- Copilot
- Custom Instructions
- Developer Workflow
- GitHub
- GitHub Copilot
- Markdown
- Repository
repo: https://github.com/api-evangelist/copilot-instructions-md
api_count: 2
apis:
- name: copilot-instructions.md Format
  description: The copilot-instructions.md format is an unstructured Markdown file placed at .github/copilot-instructions.md. GitHub Copilot detects the file automatically and prepends its contents to prompts sent to the model in Copilot Chat, Copilot in…
  url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot
- name: Copilot Instructions Ecosystem
  description: Repository copilot-instructions.md is one layer in a stack of GitHub Copilot customization options. Personal custom instructions apply to a single user across all repositories. Organization custom instructions apply to every repository in…
  url: https://docs.github.com/en/copilot/customizing-copilot
links:
- type: Documentation
  url: https://docs.github.com/en/copilot/customizing-copilot/adding-repository-custom-instructions-for-github-copilot
- type: Documentation
  url: https://docs.github.com/en/copilot/customizing-copilot
- type: Examples
  url: https://github.com/github/awesome-copilot
- type: Blog
  url: https://github.blog/changelog/2025-01-23-custom-instructions-for-github-copilot-in-vs-code-now-generally-available/
provider_count: 10
providers:
- slug: claude-md
  name: CLAUDE.md
  description: CLAUDE.md is the markdown-based project memory format used by Anthropic's Claude Code CLI to give the model persistent, session-spanning instructions about a codebase. CLAUDE.md files are plain markdown that Claude Code loads at the start…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: contributing-md
  name: CONTRIBUTING.md
  description: CONTRIBUTING.md is a community health convention used by open source projects on GitHub and other platforms to document how external contributors can participate. The file communicates contribution guidelines, pull request processes, issue…
  api_count: 2
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
- slug: instructions-md
  name: Instructions.md
  description: File-scoped custom instruction files for GitHub Copilot and VS Code, using applyTo patterns to target specific file types or tasks with tailored AI guidance. These markdown-based instruction files allow developers to provide context-specif…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
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
- slug: funding-yml
  name: FUNDING.yml
  description: GitHub configuration file specifying funding platforms and links for project sponsorship, displayed as a Sponsor button on the repository page. Supports platforms including GitHub Sponsors, Patreon, Open Collective, Ko-fi, Liberapay, Tidel…
  api_count: 0
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
---
