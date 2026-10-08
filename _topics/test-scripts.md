---
layout: topic
slug: test-scripts
name: Test Scripts
kind: topic
description: Automated scripts used to verify software functionality, validate code behavior, and ensure quality through repeatable testing procedures. Test scripts encode testing logic in executable form, enabling continuous integration pipelines to run validation automatically on every code change. They support unit testing, integration testing, end-to-end testing, contract testing, performance testing, and security scanning across REST, GraphQL, SOAP, and gRPC APIs.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-scripts.png
tags:
- Automation
- CI/CD
- Contract Testing
- Developer Tools
- Quality Assurance
- Software Development
- Testing
repo: https://github.com/api-evangelist/test-scripts
api_count: 11
apis:
- name: Newman CLI
  description: Newman is the command-line companion for Postman, enabling Postman collections and test scripts to be run directly from the terminal or integrated into CI/CD pipelines such as GitHub Actions, Jenkins, and GitLab CI.
  url: https://github.com/postmanlabs/newman
- name: Karate API Testing Framework
  description: Karate is an open-source framework that combines API test automation, mocks, performance testing, and UI automation into a single framework. Test scripts are written in plain-text Gherkin syntax, making them readable by non-programmers whi…
  url: https://karatelabs.github.io/karate/
- name: REST Assured
  description: REST Assured is a Java-based DSL for simplifying testing of REST services. It integrates with JUnit and TestNG, and supports BDD-style test scripting with a fluent API for validating HTTP responses, headers, and JSON/XML payloads.
  url: https://rest-assured.io/
- name: Dredd API Testing Framework
  description: Dredd is an open-source language-agnostic command-line tool for validating API documentation written in OpenAPI or API Blueprint against its backend implementation. It reads test scripts derived from API specifications and automatically ve…
  url: https://dredd.org/
- name: Playwright Test
  description: Playwright is a cross-browser end-to-end testing framework from Microsoft that supports writing test scripts in JavaScript, TypeScript, Python, Java, and .NET. It is widely used for API testing, browser automation, and full-stack integrati…
  url: https://playwright.dev/
- name: Schemathesis
  description: Schemathesis is a property-based testing tool for web APIs. It reads OpenAPI or GraphQL schemas and automatically generates test scripts to discover edge cases, crashes, and specification violations through stateful, hypothesis-driven test…
  url: https://schemathesis.io/
- name: Test Scripts Collections API
  description: The Collections API from Test Scripts — 2 operation(s) for collections.
  url: https://www.postman.com/postman/postman-public-workspace/
- name: Test Scripts Environments API
  description: The Environments API from Test Scripts — 1 operation(s) for environments.
  url: https://www.postman.com/postman/postman-public-workspace/
- name: Test Scripts Mocks API
  description: The Mocks API from Test Scripts — 1 operation(s) for mocks.
  url: https://www.postman.com/postman/postman-public-workspace/
- name: Test Scripts Monitors API
  description: The Monitors API from Test Scripts — 1 operation(s) for monitors.
  url: https://www.postman.com/postman/postman-public-workspace/
- name: Cypress
  description: Cypress is a JavaScript end-to-end testing framework designed for modern web applications. Its test scripting API supports both API testing and browser automation, with real-time test runner feedback and built-in parallelization for CI/CD…
  url: https://www.cypress.io/
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/test-scripts/blob/main/capabilities/test-scripts-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/test-scripts/blob/main/agentic-access/test-scripts-agentic-access.yml
- type: TrustCenter
  url: https://github.com/api-evangelist/test-scripts/blob/main/security/test-scripts-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/test-scripts/blob/main/security/test-scripts-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/test-scripts/blob/main/security/test-scripts-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/test-scripts/blob/main/authentication/test-scripts-authentication.yml
- type: GitHubOrg
  url: https://github.com/api-evangelist/test-scripts
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-schema/test-scripts-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-structure/test-scripts-structure.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/json-ld/test-scripts-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/test-scripts/main/vocabulary/test-scripts-vocabulary.yml
provider_count: 203
providers:
- slug: sauce-labs
  name: Sauce Labs
  description: Sauce Labs is a cloud-based cross-browser and mobile app testing platform trusted by over 100,000 customers worldwide. It provides a comprehensive set of REST APIs for managing test jobs, devices, builds, insights, and results across virtu…
  api_count: 2
  score_band: developing
  score_composite: 44.9
  shared: 5
- slug: github-actions
  name: GitHub Actions
  description: GitHub Actions is GitHub's hosted CI/CD and workflow automation platform, and this record covers the REST API surface that drives it. Eighty-two operations across eleven resource areas let a caller dispatch and cancel workflow runs, poll r…
  api_count: 1
  score_band: exemplar
  score_composite: 82.8
  shared: 4
- slug: keploy
  name: Keploy
  description: Open-source, AI-native testing platform that captures real production API traffic with eBPF and replays it in CI as deterministic tests, auto-generated mocks, and production-like sandboxes with zero code changes. Publishes a first-party Op…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 4
- slug: automation-preflight-api
  name: Automation Preflight API
  description: A self-serve REST API by TinyOps Studio LLC that inspects a public URL and returns deterministic, bounded JSON integration-readiness evidence across reachability, integration surface, and readiness scoring. It rejects private/credential-be…
  api_count: 2
  score_band: developing
  score_composite: 49.2
  shared: 4
- slug: rainforest-qa
  name: Rainforest QA
  description: Rainforest QA is a no-code software testing platform that combines AI-powered test creation, crowdsourced manual QA, and automated browser testing in one place. Its REST API and command-line interface let teams create and manage tests, env…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 4
- slug: assertible
  name: Assertible
  description: Assertible provides a reliable first line of defense against web service failures by providing simple and powerful assertions to test and monitor APIs. It enables automated API testing with assertions on response status, headers, body cont…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 4
- slug: testim-io
  name: Testim
  description: Testim is an AI-powered functional test automation platform for web and mobile applications, using machine learning to author, run, and self-heal UI tests. Acquired by Tricentis in 2022, Testim is offered as part of the Tricentis quality-e…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 4
- slug: cypressio
  name: Cypress.io
  description: Cypress.io, Inc. builds Cypress, an open-source, JavaScript-based end-to-end and component testing framework that runs tests directly in the browser with time-travel debugging, automatic waiting, and cross-browser support. Its commercial C…
  api_count: 1
  score_band: thin
  score_composite: 37.8
  shared: 4
- slug: step-ci
  name: Step CI
  description: Step CI is an open source API testing and monitoring framework that uses YAML-based workflows to define and run automated API test scenarios. It supports REST, GraphQL, gRPC, tRPC, and SOAP protocols in a single unified testing framework.…
  api_count: 1
  score_band: emerging
  score_composite: 18.9
  shared: 4
- slug: muuktest
  name: Muuktest
  description: MuukTest (MuukLabs) is an AI-powered test automation and managed QA services company founded in 2019 that helps software teams reach high end-to-end test coverage in weeks rather than months. It blends an AI-driven automation platform with…
  api_count: 0
  score_band: emerging
  score_composite: 12.1
  shared: 4
- slug: approxima
  name: Approxima
  description: 'Approxima is a Y Combinator (Winter 2026) startup building AI agents that test every pull request. Approxima plugs into your CI/CD pipeline and runs autonomous agents on each PR: the agents build your application in an isolated sandbox, ex…'
  api_count: 0
  score_band: minimal
  score_composite: 10.1
  shared: 4
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: browserstack
  name: BrowserStack
  description: BrowserStack provides instant access to 3,500+ real desktop browsers and 30,000+ real mobile device units for manual and automated software testing. Its products span cross-browser testing (Live, Automate), mobile app testing (App Live, Ap…
  api_count: 1
  score_band: exemplar
  score_composite: 67.8
  shared: 3
- slug: smartbear
  name: SmartBear
  description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI fo…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 3
- slug: gradle
  name: Gradle
  description: Gradle Inc. (Gradle Technologies) is the company behind the open-source Gradle Build Tool, downloaded more than 25 million times a month across the Java, JVM, Android, Kotlin, C/C++, and native ecosystems, and Develocity (formerly Gradle E…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 3
- slug: testfairy
  name: TestFairy
  description: TestFairy is a mobile app testing and distribution platform, now part of Sauce Labs, that lets teams upload iOS and Android builds, distribute them to beta testers, and record video sessions of testers using the app alongside device logs,…
  api_count: 1
  score_band: developing
  score_composite: 53.7
  shared: 3
- slug: kubeshop
  name: Kubeshop
  description: Kubeshop is the company behind Testkube, an open-core, Kubernetes-native test orchestration platform. Testkube runs agents inside Kubernetes clusters under a central control plane, orchestrating tests written for existing frameworks — Cypr…
  api_count: 3
  score_band: developing
  score_composite: 52.9
  shared: 3
- slug: amika
  name: Amika
  description: Amika is a Y Combinator-backed infrastructure company for running AI coding agents in isolated cloud sandboxes. Teams spawn agents from Slack, Linear, GitHub, a CLI, a TypeScript SDK, or the hosted HTTP API to understand a codebase, run in…
  api_count: 1
  score_band: developing
  score_composite: 50.8
  shared: 3
- slug: gitar
  name: Gitar
  description: Gitar is an AI code review platform that goes beyond commenting on pull and merge requests — it automatically fixes broken builds, failing tests, linting errors, and code-review findings, and validates every change against your CI pipeline…
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 3
- slug: opkey
  name: Opkey
  description: Opkey (Smart Software Testing Solutions, Inc.) is a US-headquartered Cloud Application Lifecycle Management and AI-powered test automation vendor for enterprise packaged applications. Its no-code platform ships pre-built automated tests an…
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 3
- slug: teamcity
  name: TeamCity
  description: JetBrains TeamCity is a powerful continuous integration and deployment server that helps development teams build, test, and deploy software efficiently. TeamCity provides a comprehensive REST API for automating CI/CD workflows, managing pr…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 3
- slug: accessibe
  name: accessiBe
  description: accessiBe is a web accessibility technology company whose products help organizations make websites and web applications usable by people with disabilities and compliant with WCAG, the ADA, Section 508, AODA and the European Accessibility…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 3
- slug: replay
  name: Replay
  description: Replay is an AI-native QA and time-travel debugging platform for web applications. Replay QA autonomously explores a web app, records every session in a deterministic Replay Browser, finds real bugs, and hands a coding agent the root cause…
  api_count: 1
  score_band: developing
  score_composite: 44.9
  shared: 3
- slug: qa-wolf
  name: QA Wolf
  description: 'QA Wolf is a hybrid platform and service that takes QA off software teams'' plates: AI maps an application''s user journeys, converts plain-language prompts into Playwright and Appium tests, and runs those flows in massively parallel cloud i…'
  api_count: 1
  score_band: developing
  score_composite: 43.9
  shared: 3
- slug: ardent
  name: Ardent
  description: Ardent is a database branching platform for Postgres that lets developers and AI coding agents clone any production or development database in seconds into fully isolated, disposable branches. Each branch is isolated at both the compute an…
  api_count: 1
  score_band: developing
  score_composite: 42.9
  shared: 3
- slug: launchable
  name: Launchable
  description: Launchable is a software development intelligence platform for continuous integration that applies machine learning to CI and test data to speed up software delivery. Its flagship capability, Predictive Test Selection, records builds, test…
  api_count: 1
  score_band: developing
  score_composite: 42.0
  shared: 3
- slug: selenium
  name: Selenium
  description: Selenium is the open-source browser automation project behind the W3C WebDriver and WebDriver BiDi standards. It drives real browsers through a vendor-neutral, standardised HTTP wire protocol that the browser vendors implement themselves,…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 3
- slug: reflect
  name: Reflect
  description: Reflect is an AI-powered automated end-to-end testing platform that enables teams to effortlessly create, execute, and troubleshoot automated browser tests. Reflect provides a no-code test recorder for capturing user workflows and a REST A…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 3
- slug: ellipsis
  name: Ellipsis
  description: Ellipsis is a managed cloud platform for running autonomous coding agents at scale. Engineering teams define agents as YAML config files that live in their repositories, and Ellipsis runs them in isolated, ephemeral sandboxes to review pul…
  api_count: 1
  score_band: thin
  score_composite: 37.3
  shared: 3
- slug: testmo
  name: Testmo
  description: Testmo is a unified test management platform that brings manual test cases, test automation, and exploratory testing together in one tool, with reporting, milestones, and issue-tracker and CI integrations. Testmo exposes a documented REST…
  api_count: 1
  score_band: thin
  score_composite: 35.3
  shared: 3
---
