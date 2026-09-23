---
layout: topic
slug: safe-agile
name: SAFe Agile
kind: topic
description: 'The Scaled Agile Framework (SAFe) is an enterprise-scale agile framework developed by Scaled Agile, Inc. that provides guidance for implementing agile practices across large organizations with multiple teams. SAFe organizes around five core disciplines: Lean Portfolio Management, Team and Technical Agility, Product Development Flow, Large Solution Integration and Delivery, and Leadership and Culture. Organizations use SAFe to align stakeholders, coordinate Agile Release Trains (ARTs), track PI objectives, and accelerate delivery of value. SAFe tools integrate with CI/CD pipelines, ERP systems, and planning platforms to support enterprise agile transformation.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/safe-agile.png
tags:
- Agile
- Enterprise
- Framework
- Project Management
- Scaled Agile
- Lean Portfolio
- DevOps
repo: https://github.com/api-evangelist/safe-agile
api_count: 5
apis:
- name: Scaled Agile Framework (SAFe)
  description: The official Scaled Agile Framework by Scaled Agile, Inc. provides comprehensive guidance for enterprise agile transformation including roles, events, artifacts, and competencies for Lean Portfolio Management, Agile Release Trains, and PI…
  url: https://framework.scaledagile.com/
- name: Jira SAFe Integration
  description: Jira by Atlassian provides SAFe-aligned project management and PI planning capabilities through the Advanced Roadmaps feature and SAFe-compatible workflows for Agile Release Trains, Epics, Features, and Stories. Jira's REST API enables pro…
  url: https://www.atlassian.com/agile/safe
- name: Azure DevOps SAFe Integration
  description: Azure DevOps provides SAFe-aligned planning and tracking through work item types aligned to SAFe hierarchy (Epics, Features, User Stories), delivery plans for Program Increment visualization, and REST APIs for programmatic access to backlo…
  url: https://learn.microsoft.com/en-us/azure/devops/
- name: Planview SAFe Tool
  description: Planview provides enterprise agile planning supporting SAFe through its portfolio management, Lean flow, and Agile delivery capabilities. Enables organizations to connect strategy to delivery across multiple ARTs with real-time program boa…
  url: https://www.planview.com/resources/articles/safe-agile/
- name: SpiraPlan SAFe Tool
  description: SpiraPlan by Inflectra is an enterprise agile portfolio and risk management platform that supports SAFe, Nexus, Scrum of Scrums, and LeSS frameworks. Provides REST API for programmatic access to portfolio, program, and team level planning…
  url: https://www.inflectra.com/SpiraPlan/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/safe-agile/blob/main/security/safe-agile-domain-security.yml
- type: Website
  url: https://scaledagile.com/
- type: Documentation
  url: https://framework.scaledagile.com/
- type: Blog
  url: https://scaledagile.com/blog/
- type: Certification
  url: https://scaledagile.com/training/find-training-provider/
- type: JSONSchema
  url: https://github.com/api-evangelist/safe-agile/blob/main/json-schema/safe-agile-program-increment-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/safe-agile/blob/main/json-structure/safe-agile-art-structure.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/safe-agile/blob/main/json-ld/safe-agile-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/safe-agile/blob/main/vocabulary/safe-agile-vocabulary.yml
provider_count: 35
providers:
- slug: scaled-agile
  name: Scaled Agile
  description: Scaled Agile, Inc. is the provider of SAFe® (Scaled Agile Framework), the world's leading framework for business agility at scale. SAFe helps organizations plan better, work smarter, deliver faster, and scale sustainably by aligning people…
  api_count: 1
  score_band: emerging
  score_composite: 20.8
  shared: 5
- slug: microsoft-azure-devops
  name: Azure DevOps
  description: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications.
  api_count: 11
  score_band: exemplar
  score_composite: 74.4
  shared: 3
- slug: hansoft
  name: Hansoft
  description: Hansoft, now branded P4 Plan by Perforce, is a real-time agile project planning and portfolio management tool for software, game, and hardware teams. It lets multiple teams work in their preferred methodology simultaneously (Scrum, Kanban,…
  api_count: 3
  score_band: developing
  score_composite: 46.5
  shared: 3
- slug: scrum
  name: Scrum
  description: Scrum is an agile project management framework that organizes work into fixed-length iterations called sprints, typically lasting two to four weeks. It defines clear roles (Product Owner, Scrum Master, Developers) and ceremonies (sprint pl…
  api_count: 0
  score_band: minimal
  score_composite: 5.2
  shared: 3
- slug: jira
  name: Jira
  description: APIs for Atlassian Jira project management and issue tracking platform.
  api_count: 4
  score_band: exemplar
  score_composite: 73.5
  shared: 2
- slug: red-hat-ansible-automation-platform
  name: Red Hat Ansible Automation Platform
  description: Red Hat Ansible Automation Platform is an enterprise automation solution that provides a framework for building and operating IT automation at scale. It includes the Automation Controller, Automation Hub, Event-Driven Ansible, and Ansible…
  api_count: 5
  score_band: strong
  score_composite: 63.0
  shared: 2
- slug: taskfolk
  name: Taskfolk
  description: Taskfolk is a project-management and issue-tracking platform built for teams and their AI agents working side by side, operated by UTTER L.L.C-FZ of Dubai, UAE. Workspaces contain projects; projects contain issues moved across board, backl…
  api_count: 4
  score_band: strong
  score_composite: 63.0
  shared: 2
- slug: ibm
  name: IBM
  description: A collection of IBM's public APIs and developer resources.
  api_count: 1
  score_band: strong
  score_composite: 62.6
  shared: 2
- slug: leankit
  name: LeanKit
  description: LeanKit is the enterprise Kanban platform now shipped by Planview as Planview AgilePlace, used to visually track and manage the flow of work from strategy to delivery across boards, lanes, cards, taskboards, and connected parent/child hier…
  api_count: 2
  score_band: strong
  score_composite: 60.9
  shared: 2
- slug: shortcut-software
  name: Shortcut Software
  description: Shortcut (formerly Clubhouse, renamed 2021) is a fast, lightweight project-management platform where software teams and their AI agents plan, build, and ship together — issue tracking, sprints, docs, and roadmaps in one tool. Founded in 20…
  api_count: 1
  score_band: strong
  score_composite: 58.1
  shared: 2
- slug: perforce
  name: Perforce
  description: Perforce Software provides enterprise-scale development tools, including version control, application lifecycle management, agile planning, and static analysis solutions for development teams.
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: spring
  name: Spring Framework
  description: Spring is the leading open-source application framework for Java. The Spring ecosystem provides a comprehensive programming and configuration model for modern Java-based enterprise applications, covering web MVC, data access, security, mes…
  api_count: 3
  score_band: developing
  score_composite: 46.2
  shared: 2
- slug: favro
  name: Favro
  description: Favro is a cloud planning and collaboration platform for agile teams, combining planning boards, backlogs, sprint/kanban widgets, roadmaps, and OKR/portfolio management in a single organization-scoped workspace. Its public REST API (https:…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: oracle-fusion
  name: Oracle Fusion Cloud Applications
  description: Oracle Fusion Cloud Applications represent a comprehensive suite of cloud-based enterprise resource planning (ERP), human capital management (HCM), customer experience (CX), supply chain management (SCM), and enterprise performance managem…
  api_count: 7
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: amazon-codestar
  name: Amazon CodeStar
  description: AWS CodeStar provides a unified user interface enabling you to easily manage your software development activities in one place. With AWS CodeStar, you can set up your entire continuous delivery toolchain in minutes, allowing you to create…
  api_count: 1
  score_band: developing
  score_composite: 44.3
  shared: 2
- slug: openproject
  name: OpenProject
  description: OpenProject is an open source project management platform offering work package tracking, Gantt charts, agile boards, time tracking, BIM, and enterprise project portfolio management. The OpenProject APIv3 is a hypermedia (HAL+JSON) REST AP…
  api_count: 1
  score_band: developing
  score_composite: 41.4
  shared: 2
- slug: spring-boot-3
  name: Spring Boot 3
  description: Spring Boot 3 is the major release of the opinionated Spring application framework, now built on Spring Framework 6, requiring Java 17 baseline and Jakarta EE 10. It delivers native image support via GraalVM, improved observability with Mi…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 2
- slug: ubuntu
  name: Ubuntu
  description: Collection of APIs and services provided by Canonical for Ubuntu and related products. Includes the Snap Store API for package management, Launchpad API for project hosting and bug tracking, Ubuntu Security CVE API for vulnerability intell…
  api_count: 3
  score_band: thin
  score_composite: 35.9
  shared: 2
- slug: kanban
  name: Kanban Tool
  description: Kanban Tool is a visual project management platform for managing boards, tasks, and workflows using the Kanban methodology. It provides REST APIs (v1 and v3), browser SDK, and DevKit for programmatic access to boards, tasks, columns, comme…
  api_count: 12
  score_band: thin
  score_composite: 33.0
  shared: 2
- slug: puppet
  name: Puppet
  description: Puppet provides infrastructure automation and configuration management for hybrid and cloud environments. Puppet Enterprise exposes a collection of service APIs (Orchestrator, RBAC, Node Classifier, Code Manager, Activity, Status, Inventor…
  api_count: 1
  score_band: thin
  score_composite: 32.5
  shared: 2
- slug: github-enterprise
  name: GitHub Enterprise
  description: 'GitHub Enterprise is GitHub''s offering for organizations that need advanced security, compliance, identity, and scale on top of the GitHub platform. It ships in two flavors: GitHub Enterprise Cloud, a hosted multi-tenant service on api.git…'
  api_count: 1
  score_band: thin
  score_composite: 28.9
  shared: 2
- slug: assembla
  name: Assembla
  description: Assembla provides managed cloud hosting for Perforce, Subversion (SVN) and Git repositories, along with integrated project management tools. Their platform offers enterprise‑grade security, SOC 2 Type II compliance, GDPR adherence, and AI‑…
  api_count: 1
  score_band: thin
  score_composite: 28.4
  shared: 2
- slug: software-development-lifecycle
  name: Software Development Lifecycle
  description: The Software Development Lifecycle (SDLC) encompasses all processes, tools, and methodologies involved in planning, developing, testing, and delivering software from inception to retirement. Modern SDLC platforms integrate project planning…
  api_count: 7
  score_band: emerging
  score_composite: 25.0
  shared: 2
- slug: taiga
  name: Taiga
  description: Taiga is an open-source agile project management platform with a comprehensive REST API for managing projects, sprints, user stories, issues, tasks, epics, wiki pages, webhooks, and team member assignments. The API supports both standard b…
  api_count: 1
  score_band: emerging
  score_composite: 24.8
  shared: 2
- slug: kagent
  name: kagent
  description: kagent is an open-source framework for running AI agents in Kubernetes, automating complex DevOps operations and troubleshooting tasks with intelligent workflows. It is a Cloud Native Computing Foundation sandbox project that brings agenti…
  api_count: 1
  score_band: emerging
  score_composite: 24.6
  shared: 2
- slug: tintri
  name: Tintri
  description: 'Tintri, now part of DDN, builds intelligent enterprise data-management and storage infrastructure: the VMstore virtualization-aware storage platform, the Tintri Cloud Platform (TCP) and Cloud Engine (TCE), and the Tintri Global Center (TGC…'
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 2
- slug: meetandy-ai
  name: MeetAndy AI
  description: MeetAndy (operated by MeetTomorrow Inc.) is an AI project assistant — an "AI teammate" that lives in Slack, Google Chat, GitHub, GitLab, and Jira and turns plain-language requests into reviewable plans, opens pull requests, runs CI, and re…
  api_count: 0
  score_band: emerging
  score_composite: 20.7
  shared: 2
- slug: plangrid
  name: PlanGrid
  description: PlanGrid is a construction productivity platform (now part of Autodesk Construction Cloud) that gives field and office teams access to construction drawings, sheets, documents, photos, RFIs, submittals, field reports, tasks, and punch list…
  api_count: 1
  score_band: emerging
  score_composite: 19.6
  shared: 2
- slug: qt
  name: Qt
  description: Qt Group is a global software company that builds cross-platform development, design, and quality-assurance tools used across more than 70 industries and billions of devices. Its portfolio spans the Qt Framework (cross-platform C++ softwar…
  api_count: 0
  score_band: emerging
  score_composite: 19.0
  shared: 2
- slug: agile-delivery
  name: Agile Delivery
  description: A collection of resources, tools, and APIs related to agile delivery practices — the iterative approach to project management and software delivery that helps teams ship value faster through sprints, continuous feedback, and adaptive plann…
  api_count: 0
  score_band: minimal
  score_composite: 10.8
  shared: 2
---
