---
layout: topic
slug: acceptance-criteria
name: Acceptance Criteria
kind: topic
description: Acceptance criteria are predefined conditions that a product, feature, or user story must meet to be considered complete and acceptable by stakeholders. These criteria establish clear, testable requirements that guide development, validate when work is done, and serve as the foundation for automated testing through frameworks like Cucumber, SpecFlow, and Behave. APIs in this space support requirements management, behavior-driven development (BDD), test execution tracking, and agile project management workflows.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/acceptance-criteria.png
tags:
- Agile
- Behavior-Driven Development
- Gherkin
- Quality Assurance
- Requirements
- Testing
- User Stories
repo: https://github.com/api-evangelist/acceptance-criteria
api_count: 9
apis:
- name: GitHub Issues API
  description: GitHub Issues API enables teams to create, manage, and track user stories and acceptance criteria as structured issue records with labels, milestones, and custom fields. Commonly used to attach acceptance criteria directly to issues using…
  url: https://docs.github.com/en/rest/issues
- name: Jira Issues API
  description: Jira REST API provides access to issues, user stories, epics, and acceptance criteria stored in custom fields. Teams use Jira to define, link, and track acceptance criteria against development work items throughout the sprint lifecycle.
  url: https://developer.atlassian.com/cloud/jira/platform/rest/v3/
- name: Azure DevOps Work Items API
  description: Azure DevOps Work Items REST API enables management of user stories, acceptance criteria, and test cases in Azure Boards. Acceptance criteria are stored as a rich text field on Product Backlog Items and User Story work item types, accessib…
  url: https://learn.microsoft.com/en-us/rest/api/azure/devops/wit/
- name: Linear API
  description: Linear GraphQL API provides access to issues, projects, and cycles used by engineering teams to track features and acceptance criteria. Linear supports structured issue descriptions with Markdown, enabling teams to embed acceptance criteri…
  url: https://developers.linear.app/docs/graphql/working-with-the-graphql-api
- name: TestRail API
  description: TestRail REST API provides access to test cases, test runs, test plans, and results. Teams use TestRail to formally document acceptance criteria as test cases with preconditions, expected results, and step-by-step validation criteria that…
  url: https://support.testrail.com/hc/en-us/articles/7077792415124-Introduction-to-the-TestRail-API
- name: Acceptance Criteria Acceptance Criteria API
  description: The Acceptance Criteria API from Acceptance Criteria — 2 operation(s) for acceptance criteria.
  url: https://docs.github.com/en/rest/issues
- name: Acceptance Criteria BDD Scenarios API
  description: The BDD Scenarios API from Acceptance Criteria — 1 operation(s) for bdd scenarios.
  url: https://docs.github.com/en/rest/issues
- name: Acceptance Criteria Test Runs API
  description: The Test Runs API from Acceptance Criteria — 1 operation(s) for test runs.
  url: https://docs.github.com/en/rest/issues
- name: Acceptance Criteria User Stories API
  description: The User Stories API from Acceptance Criteria — 2 operation(s) for user stories.
  url: https://docs.github.com/en/rest/issues
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/agentic-access/acceptance-criteria-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/security/acceptance-criteria-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/authentication/acceptance-criteria-authentication.yml
- type: Website
  url: https://www.agilealliance.org/glossary/acceptance-criteria/
- type: GettingStarted
  url: https://www.mountaingoatsoftware.com/blog/clarifying-the-relationship-between-definition-of-done-and-conditions-of-satisfaction
- type: SpectralRules
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/rules/acceptance-criteria-spectral-rules.yml
- type: Vocabulary
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/vocabulary/acceptance-criteria-vocabulary.yaml
- type: OpenAPI
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/openapi/_original/acceptance-criteria-management.yaml
- type: JSONSchema
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-schema/acceptance-criteria-management-user-story-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-schema/acceptance-criteria-management-acceptance-criterion-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-schema/acceptance-criteria-management-scenario-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-schema/acceptance-criteria-management-test-run-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-structure/acceptance-criteria-management-user-story-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-structure/acceptance-criteria-management-acceptance-criterion-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-structure/acceptance-criteria-management-scenario-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-structure/acceptance-criteria-management-test-run-structure.json
- type: JSONLD
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/json-ld/acceptance-criteria-management-context.jsonld
- type: Examples
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/examples/acceptance-criteria-management-user-story-example.json
- type: Examples
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/examples/acceptance-criteria-management-acceptance-criterion-example.json
- type: Examples
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/examples/acceptance-criteria-management-scenario-example.json
- type: Examples
  url: https://github.com/api-evangelist/acceptance-criteria/blob/main/examples/acceptance-criteria-management-test-run-example.json
provider_count: 33
providers:
- slug: cucumber
  name: Cucumber
  description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing execu…
  api_count: 5
  score_band: thin
  score_composite: 29.4
  shared: 4
- slug: bdd
  name: BDD (Behavior-Driven Development)
  description: Behavior-Driven Development (BDD) is a software development methodology that combines test-driven development with domain-driven design, encouraging collaboration between developers, QA, and business stakeholders through human-readable tes…
  api_count: 5
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: testfairy
  name: TestFairy
  description: TestFairy is a mobile app testing and distribution platform, now part of Sauce Labs, that lets teams upload iOS and Android builds, distribute them to beta testers, and record video sessions of testers using the app alongside device logs,…
  api_count: 1
  score_band: developing
  score_composite: 52.6
  shared: 2
- slug: coval
  name: Coval
  description: Coval is the deployment-readiness platform for voice and chat AI agents. Teams simulate thousands of realistic conversation scenarios before launch, monitor real production calls, and improve reliability with metrics and human review. Cova…
  api_count: 20
  score_band: developing
  score_composite: 52.1
  shared: 2
- slug: kubeshop
  name: Kubeshop
  description: Kubeshop is the company behind Testkube, an open-core, Kubernetes-native test orchestration platform. Testkube runs agents inside Kubernetes clusters under a central control plane, orchestrating tests written for existing frameworks — Cypr…
  api_count: 3
  score_band: developing
  score_composite: 51.3
  shared: 2
- slug: opkey
  name: Opkey
  description: Opkey (Smart Software Testing Solutions, Inc.) is a US-headquartered Cloud Application Lifecycle Management and AI-powered test automation vendor for enterprise packaged applications. Its no-code platform ships pre-built automated tests an…
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 2
- slug: assertible
  name: Assertible
  description: Assertible provides a reliable first line of defense against web service failures by providing simple and powerful assertions to test and monitor APIs. It enables automated API testing with assertions on response status, headers, body cont…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: rainforest-qa
  name: Rainforest QA
  description: Rainforest QA is a no-code software testing platform that combines AI-powered test creation, crowdsourced manual QA, and automated browser testing in one place. Its REST API and command-line interface let teams create and manage tests, env…
  api_count: 1
  score_band: developing
  score_composite: 47.9
  shared: 2
- slug: automation-preflight-api
  name: Automation Preflight API
  description: A self-serve REST API by TinyOps Studio LLC that inspects a public URL and returns deterministic, bounded JSON integration-readiness evidence across reachability, integration surface, and readiness scoring. It rejects private/credential-be…
  api_count: 2
  score_band: developing
  score_composite: 47.7
  shared: 2
- slug: sauce-labs
  name: Sauce Labs
  description: Sauce Labs is a cloud-based cross-browser and mobile app testing platform trusted by over 100,000 customers worldwide. It provides a comprehensive set of REST APIs for managing test jobs, devices, builds, insights, and results across virtu…
  api_count: 2
  score_band: developing
  score_composite: 47.4
  shared: 2
- slug: panaya
  name: Panaya
  description: Panaya is an enterprise change-intelligence and agentic-testing platform for business applications, helping organizations de-risk changes to SAP (including S/4HANA migrations and upgrades), Oracle (EBS, Cloud, NetSuite), Salesforce, Workda…
  api_count: 1
  score_band: developing
  score_composite: 47.2
  shared: 2
- slug: accessibe
  name: accessiBe
  description: accessiBe is a web accessibility technology company whose products help organizations make websites and web applications usable by people with disabilities and compliant with WCAG, the ADA, Section 508, AODA and the European Accessibility…
  api_count: 1
  score_band: developing
  score_composite: 45.4
  shared: 2
- slug: replay
  name: Replay
  description: Replay is an AI-native QA and time-travel debugging platform for web applications. Replay QA autonomously explores a web app, records every session in a deterministic Replay Browser, finds real bugs, and hands a coding agent the root cause…
  api_count: 1
  score_band: developing
  score_composite: 42.4
  shared: 2
- slug: aha
  name: Aha.io
  description: Aha! is a product development suite that combines roadmapping, idea management, requirements specification, whiteboarding, knowledge bases, and development tracking into a single platform for product teams. The suite spans Aha! Roadmaps, A…
  api_count: 1
  score_band: developing
  score_composite: 41.3
  shared: 2
- slug: selenium
  name: Selenium
  description: Selenium is the open-source browser automation project behind the W3C WebDriver and WebDriver BiDi standards. It drives real browsers through a vendor-neutral, standardised HTTP wire protocol that the browser vendors implement themselves,…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: testiny
  name: Testiny
  description: Testiny is a modern test management platform for QA teams that keeps manual and automated test cases, test plans, test runs, and results in a single place, with reporting and integrations for Jira, GitLab, and GitHub. Everything in the pro…
  api_count: 1
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: cypressio
  name: Cypress.io
  description: Cypress.io, Inc. builds Cypress, an open-source, JavaScript-based end-to-end and component testing framework that runs tests directly in the browser with time-travel debugging, automatic waiting, and cross-browser support. Its commercial C…
  api_count: 1
  score_band: thin
  score_composite: 37.3
  shared: 2
- slug: qase
  name: Qase
  description: Qase is a cloud test management platform (TestOps) for QA and engineering teams to author test cases, organize them into suites and plans, launch and complete test runs, publish automated results from CI pipelines, and track defects. The Q…
  api_count: 1
  score_band: thin
  score_composite: 35.4
  shared: 2
- slug: ranger
  name: Ranger
  description: Ranger is an AI-powered quality-assurance platform that lets coding agents verify their own work in a real browser. Its CLI (@ranger-testing/ranger-cli) sets up a project so an AI coding agent — Claude Code, OpenCode, Cursor, Codex, or any…
  api_count: 0
  score_band: thin
  score_composite: 27.8
  shared: 2
- slug: taiga
  name: Taiga
  description: Taiga is an open-source agile project management platform with a comprehensive REST API for managing projects, sprints, user stories, issues, tasks, epics, wiki pages, webhooks, and team member assignments. The API supports both standard b…
  api_count: 1
  score_band: emerging
  score_composite: 24.8
  shared: 2
- slug: headspin
  name: HeadSpin
  description: HeadSpin is a real-device digital-experience, functional, and performance testing platform for mobile, web, and OTT applications. Teams test, monitor, and optimize app behavior on real devices and real SIMs across 60+ locations in 50+ coun…
  api_count: 1
  score_band: emerging
  score_composite: 21.8
  shared: 2
- slug: evinced
  name: evinced
  description: Evinced is an AI-powered digital accessibility platform that automatically detects, clusters, tracks, and prevents accessibility (WCAG/ADA) issues across web and mobile applications. It ships developer-first automation SDKs for Selenium, C…
  api_count: 0
  score_band: emerging
  score_composite: 20.3
  shared: 2
- slug: step-ci
  name: Step CI
  description: Step CI is an open source API testing and monitoring framework that uses YAML-based workflows to define and run automated API test scenarios. It supports REST, GraphQL, gRPC, tRPC, and SOAP protocols in a single unified testing framework.…
  api_count: 1
  score_band: emerging
  score_composite: 19.8
  shared: 2
- slug: testlio
  name: Testlio
  description: Testlio is a managed software testing and quality assurance company that pairs a global, vetted community of expert testers with a testing-management platform (powered by its Leo AI Engine) to deliver on-demand manual, automated, functiona…
  api_count: 0
  score_band: emerging
  score_composite: 18.1
  shared: 2
- slug: specflow
  name: SpecFlow
  description: SpecFlow was an open-source BDD (Behavior-Driven Development) testing framework for .NET that allowed teams to write executable specifications in natural language using the Gherkin syntax. Originally developed by TechTalk, it was acquired…
  api_count: 2
  score_band: emerging
  score_composite: 17.0
  shared: 2
- slug: gherkin
  name: Gherkin
  description: Gherkin is a business-readable, domain-specific language created to support Behavior-Driven Development (BDD). It lets teams describe software behavior in plain text using a structured Given-When-Then syntax that is human-readable and mach…
  api_count: 0
  score_band: emerging
  score_composite: 16.9
  shared: 2
- slug: regression-games
  name: Regression Games
  description: Regression Games builds AI agents and bots for video games. Its platform lets studios create bots for QA testing, multiplayer simulation, game balancing, and NPC behavior with minimal code. The Unity SDK (gg.regression.unity.bots / RGUnity…
  api_count: 0
  score_band: emerging
  score_composite: 15.6
  shared: 2
- slug: muuktest
  name: Muuktest
  description: MuukTest (MuukLabs) is an AI-powered test automation and managed QA services company founded in 2019 that helps software teams reach high end-to-end test coverage in weeks rather than months. It blends an AI-driven automation platform with…
  api_count: 0
  score_band: emerging
  score_composite: 12.7
  shared: 2
- slug: user-stories
  name: User Stories
  description: A curated collection of API user stories following agile methodology formats. User stories capture software requirements from the end-user perspective using the format "As a [user], I want [goal], so that [benefit]". This repository indexe…
  api_count: 0
  score_band: emerging
  score_composite: 11.8
  shared: 2
- slug: canary
  name: Canary
  description: Canary is an AI QA engineer that reads your source code to understand developer intent. Push a pull request and Canary reads the diff, understands the intent, and runs feature and regression tests against your preview app across real brows…
  api_count: 0
  score_band: minimal
  score_composite: 7.7
  shared: 2
---
