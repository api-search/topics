---
layout: topic
slug: uml
name: UML
kind: topic
description: UML (Unified Modeling Language) is the standard modeling language for software architecture, system design, and technical documentation. Governed by the Object Management Group (OMG), UML defines a set of notation conventions and diagram types — class, sequence, activity, use case, state, component, deployment, and more — used across the software development lifecycle. This collection profiles the ecosystem of tools, APIs, and services that work with UML diagrams programmatically.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/uml.png
tags:
- UML
- Modeling
- Diagrams
- Software Architecture
- Design
- Standards
repo: https://github.com/api-evangelist/uml
api_count: 3
apis:
- name: UML Diagrams API
  description: Generate diagrams from textual descriptions
  url: https://plantuml.com/
- name: UML Health API
  description: Service health check
  url: https://plantuml.com/
- name: UML Validation API
  description: Validate PlantUML source syntax
  url: https://plantuml.com/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/uml/blob/main/agentic-access/uml-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/uml/blob/main/security/uml-domain-security.yml
- type: GitHubOrg
  url: https://github.com/plantuml
- type: GitHubOrg
  url: https://github.com/yuzutech
- type: Website
  url: https://www.omg.org/uml/
- type: Standards
  url: https://www.omg.org/spec/UML/
- type: Wikipedia
  url: https://en.wikipedia.org/wiki/Unified_Modeling_Language
- type: GitHub
  url: https://github.com/plantuml/plantuml
- type: GitHub
  url: https://github.com/yuzutech/kroki
- type: Documentation
  url: https://plantuml.com/
- type: Documentation
  url: https://docs.kroki.io/kroki/
- type: JSONLD
  url: https://github.com/api-evangelist/uml/blob/main/json-ld/uml-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/uml/blob/main/vocabulary/uml-vocabulary.yml
- type: JSONSchema
  url: https://github.com/api-evangelist/uml/blob/main/json-schema/uml-diagram-schema.json
- type: SpectralRules
  url: https://github.com/api-evangelist/uml/blob/main/rules/uml-rules.yml
provider_count: 4
providers:
- slug: napkin
  name: Napkin
  description: 'Napkin AI turns typed or pasted text into editable visuals — diagrams, charts, icons, and infographics — and into full presentation decks, with no prompting or design skill required. Two products share one text-to-visual engine: Napkin Vis…'
  api_count: 1
  score_band: developing
  score_composite: 44.6
  shared: 2
- slug: sparx-enterprise-architect
  name: Sparx Enterprise Architect
  description: Sparx Enterprise Architect is a comprehensive modeling, design, and management platform for enterprise architecture, software engineering, and systems engineering. It provides automation APIs including a COM Automation Interface, Add-In Fr…
  api_count: 4
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: flowcharts
  name: Flowcharts
  description: Flowcharts are a visual modeling technique used across software engineering, systems analysis, business process design, and education to depict the steps, decisions, and flow of a process or algorithm. Within an API context, flowcharts are…
  api_count: 0
  score_band: minimal
  score_composite: 4.4
  shared: 2
- slug: domain-driven-design
  name: Domain-Driven Design
  description: A software development approach that focuses on modeling software to match a domain according to input from domain experts, emphasizing collaboration between technical and domain experts to create a shared understanding through ubiquitous…
  api_count: 0
  score_band: minimal
  score_composite: 3.2
  shared: 2
---
