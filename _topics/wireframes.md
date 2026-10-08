---
layout: topic
slug: wireframes
name: Wireframes
kind: topic
description: Wireframes are low-fidelity visual representations of user interface layouts used in early design stages to establish structure, hierarchy, and functionality before high-fidelity design work begins. Major wireframing tools including Figma, Balsamiq, Axure, UXPin, Sketch, and Miro offer APIs and developer integrations for programmatic access to design assets, metadata, and collaboration workflows.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/wireframes.png
tags:
- Design
- Figma
- Prototyping
- UI Design
- UX
- Wireframing
repo: https://github.com/api-evangelist/wireframes
api_count: 8
apis:
- name: Balsamiq Cloud API
  description: Balsamiq provides a fast, focused wireframing tool used by lean product teams. Balsamiq Cloud offers API access for project management and asset integration. Balsamiq is widely used for quick, low-fidelity wireframe sketching.
  url: https://balsamiq.com/
- name: Wireframes Comments API
  description: The Comments API from Wireframes — 2 operation(s) for comments.
  url: https://developers.figma.com/docs/rest-api/
- name: Wireframes Components API
  description: The Components API from Wireframes — 2 operation(s) for components.
  url: https://developers.figma.com/docs/rest-api/
- name: Wireframes Files API
  description: The Files API from Wireframes — 4 operation(s) for files.
  url: https://developers.figma.com/docs/rest-api/
- name: Wireframes Images API
  description: The Images API from Wireframes — 2 operation(s) for images.
  url: https://developers.figma.com/docs/rest-api/
- name: Wireframes Projects API
  description: The Projects API from Wireframes — 3 operation(s) for projects.
  url: https://developers.figma.com/docs/rest-api/
- name: Wireframes Reactions API
  description: The Reactions API from Wireframes — 1 operation(s) for reactions.
  url: https://developers.figma.com/docs/rest-api/
- name: Wireframes Users API
  description: The Users API from Wireframes — 1 operation(s) for users.
  url: https://developers.figma.com/docs/rest-api/
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/wireframes/blob/main/capabilities/wireframes-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/wireframes/blob/main/agentic-access/wireframes-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/wireframes/blob/main/security/wireframes-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/wireframes/blob/main/security/wireframes-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/wireframes/blob/main/authentication/wireframes-authentication.yml
- type: OAuthScopes
  url: https://github.com/api-evangelist/wireframes/blob/main/scopes/wireframes-scopes.yml
- type: Reference
  url: https://en.wikipedia.org/wiki/Website_wireframe
- type: Portal
  url: https://developers.figma.com/
- type: Guide
  url: https://www.figma.com/resource-library/what-is-wireframing/
- type: Website
  url: https://balsamiq.com/
- type: Tools
  url: https://www.figma.com/wireframe-tool/
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/wireframes/refs/heads/main/json-ld/wireframes-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/wireframes/refs/heads/main/vocabulary/wireframes-vocabulary.yml
provider_count: 16
providers:
- slug: uizard-technologies
  name: Uizard Technologies
  description: Uizard is an AI-powered UI design and prototyping platform that lets non-designers turn text prompts, screenshots, and hand-drawn sketches into editable mockups and multi-screen prototypes. Founded in Copenhagen out of the pix2code machine…
  api_count: 0
  score_band: emerging
  score_composite: 16.6
  shared: 4
- slug: figma
  name: Figma
  description: Figma is a collaborative interface design tool with a comprehensive REST API for accessing and manipulating design files, projects, and teams.
  api_count: 3
  score_band: strong
  score_composite: 60.5
  shared: 3
- slug: penpot
  name: Penpot
  description: Penpot is an open-source design and prototyping platform built for design and code collaboration, offering a self-hostable alternative to Figma. It provides a REST RPC API that enables developers to programmatically access and manage proje…
  api_count: 1
  score_band: thin
  score_composite: 34.1
  shared: 3
- slug: ux-magic-ai
  name: UX Magic AI
  description: UXMagic (UX Magic AI) is an AI UI/UX design platform that turns text prompts, screenshots, hand-drawn sketches, website URLs, and existing Figma files into pixel-perfect, Figma-ready UI designs and production-ready code. Built by UXMagic I…
  api_count: 0
  score_band: emerging
  score_composite: 23.7
  shared: 3
- slug: modeinspect
  name: Modeinspect
  description: Modeinspect (operated by Acreom Inc.) is an AI-native design tool that runs inside your codebase. Branded "Mode", it turns a product's real code into editable canvas frames so design engineers can shape production-grade UI on a visual canv…
  api_count: 0
  score_band: emerging
  score_composite: 18.6
  shared: 3
- slug: mockups
  name: Mockups
  description: Mockups are visual representations or prototypes of user interfaces and designs used to demonstrate the look and feel of a product before development. They are used across software, mobile, web, and product design to align stakeholders, va…
  api_count: 0
  score_band: minimal
  score_composite: 3.9
  shared: 3
- slug: zeroheight
  name: Zeroheight
  description: 'zeroheight is a design system platform where teams document components, patterns, guidelines and design tokens in a styleguide, then deliver that documentation to designers, engineers and AI agents. It exposes two machine surfaces: a small…'
  api_count: 1
  score_band: strong
  score_composite: 56.3
  shared: 2
- slug: zeplin
  name: Zeplin
  description: Zeplin is a design-to-development handoff platform that bridges the gap between designers and developers by providing a structured workspace for accessing design specs, assets, style guides, components, and annotations. The Zeplin REST API…
  api_count: 1
  score_band: developing
  score_composite: 42.0
  shared: 2
- slug: uxpin
  name: UXPin
  description: UXPin is an AI-powered, code-based design and prototyping platform where designers work with real production React components instead of vector approximations. Its Merge technology syncs a team's design system from Git or Storybook onto th…
  api_count: 0
  score_band: thin
  score_composite: 34.1
  shared: 2
- slug: sketch
  name: Sketch
  description: Sketch is a digital design tool for Mac providing a REST API for managing workspaces, documents, libraries, components, prototypes, and share links in the Sketch cloud collaboration environment. The Cloud REST API (api.sketch.cloud/v1) sup…
  api_count: 1
  score_band: emerging
  score_composite: 21.4
  shared: 2
- slug: avocode
  name: Avocode
  description: Avocode was a design handoff platform with a REST API for managing projects, design files, shared screens, annotations, and design spec exports for developer-designer collaboration. Acquired by Ceros in October 2021 and sunset on October 1…
  api_count: 1
  score_band: emerging
  score_composite: 18.7
  shared: 2
- slug: pulse-labs
  name: Pulse Labs
  description: Pulse Labs is an AI-powered user experience research platform, founded in 2017, that helps product, design, and UX research teams gather and analyze real-world user feedback. The platform combines surveys, moderated and unmoderated intervi…
  api_count: 0
  score_band: emerging
  score_composite: 17.5
  shared: 2
- slug: variant
  name: Variant
  description: Variant is an AI-powered design tool at variant.com (formerly variant.ai) built around the promise of endless designs for your ideas - enter an idea for an app or site and see endless design options just by scrolling. A Kindred Ventures po…
  api_count: 0
  score_band: minimal
  score_composite: 4.0
  shared: 2
- slug: rivet-design
  name: Rivet Design
  description: 'Rivet is a design agent that works alongside your coding agent: given a prompt or an existing application, it explores dozens of distinct visual and UI design directions in parallel so you can compare them side by side and pick the one tha…'
  api_count: 0
  score_band: minimal
  score_composite: 3.3
  shared: 2
- slug: invision
  name: InVision
  description: InVision was a digital product design platform used by teams to build the world's best customer experiences. It provided REST APIs for managing prototypes, design documents, boards, comments, workflows, and design system components includi…
  api_count: 1
  score_band: minimal
  score_composite: 0
  shared: 2
- slug: invisionapp
  name: InVisionApp
  description: InVision (InVisionApp, Inc.) was a digital product design collaboration platform founded in 2011 by Clark Valberg and Ben Nadel. It built a suite of tools for prototyping, design handoff, and real-time collaboration — including interactive…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 2
---
