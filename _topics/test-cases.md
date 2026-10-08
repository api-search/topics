---
layout: topic
slug: test-cases
name: Test Cases
kind: topic
description: Structured scenarios that verify software functionality by defining inputs, execution conditions, and expected results to ensure quality and correctness. Test cases are the fundamental units of software testing that document what needs to be tested, the conditions under which the test runs, and the expected outcomes. They are widely used across manual testing, automated testing, and API testing workflows.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-cases.png
tags:
- API Testing
- Automation
- Developer Tools
- Quality Assurance
- Software Development
- Software Testing
- Testing
repo: https://github.com/api-evangelist/test-cases
api_count: 9
apis:
- name: Postman API
  description: API for managing Postman collections, environments, monitors, mock servers, and test runs programmatically. Supports creating and executing test cases via Newman and Postman scripts.
  url: https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a
- name: TestRail API
  description: REST API for TestRail test case management system, enabling programmatic creation, update, and retrieval of test cases, test runs, test plans, and results.
  url: https://www.testrail.com/api
- name: Zephyr Scale API
  description: REST API for Zephyr Scale test management in Jira Cloud, supporting test case creation, test cycles, test execution, and reporting within Jira.
  url: https://support.smartbear.com/zephyr-scale-cloud/api-docs/
- name: Xray Test Management API
  description: REST API for Xray test management in Jira, supporting test case management, test execution, test coverage, and CI/CD integration for structured test case workflows.
  url: https://docs.getxray.app/display/XRAYCLOUD/REST+API
- name: PractiTest API
  description: REST API for PractiTest test management platform supporting test case libraries, test runs, requirements, defects, and full quality management workflows.
  url: https://developers.practitest.com
- name: Katalon TestOps API
  description: API for Katalon TestOps test automation platform, providing endpoints for test case management, test execution, reports, and integration with CI/CD pipelines.
  url: https://katalon.com
- name: Test Cases Collections API
  description: The Collections API from Test Cases — 2 operation(s) for collections.
  url: https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a
- name: Test Cases Environments API
  description: The Environments API from Test Cases — 2 operation(s) for environments.
  url: https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a
- name: Test Cases Mocks API
  description: The Mocks API from Test Cases — 1 operation(s) for mocks.
  url: https://www.postman.com/postman/workspace/postman-public-workspace/collection/12959542-c8142d51-e97c-46b6-bd77-52bb66712c9a
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/test-cases/blob/main/capabilities/test-cases-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/test-cases/blob/main/agentic-access/test-cases-agentic-access.yml
- type: TrustCenter
  url: https://github.com/api-evangelist/test-cases/blob/main/security/test-cases-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/test-cases/blob/main/security/test-cases-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/test-cases/blob/main/security/test-cases-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/test-cases/blob/main/authentication/test-cases-authentication.yml
- type: Documentation
  url: https://en.wikipedia.org/wiki/Test_case
- type: JSONSchema
  url: https://github.com/api-evangelist/test-cases/blob/main/json-schema/test-cases-test-case-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-cases/blob/main/json-schema/test-cases-test-step-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-cases/blob/main/json-schema/test-cases-test-result-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-cases/blob/main/json-schema/test-cases-test-suite-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/test-cases/blob/main/json-ld/test-cases-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/test-cases/blob/main/vocabulary/test-cases-vocabulary.yml
provider_count: 151
providers:
- slug: testim-io
  name: Testim
  description: Testim is an AI-powered functional test automation platform for web and mobile applications, using machine learning to author, run, and self-heal UI tests. Acquired by Tricentis in 2022, Testim is offered as part of the Tricentis quality-e…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 5
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
- slug: sauce-labs
  name: Sauce Labs
  description: Sauce Labs is a cloud-based cross-browser and mobile app testing platform trusted by over 100,000 customers worldwide. It provides a comprehensive set of REST APIs for managing test jobs, devices, builds, insights, and results across virtu…
  api_count: 2
  score_band: developing
  score_composite: 44.9
  shared: 4
- slug: testsprite
  name: TestSprite
  description: 'TestSprite is an AI-powered software testing platform (a Techstars-backed company) that gives autonomous coding agents a verification loop: it uses an app like a real user, generates and executes end-to-end UI and backend API tests, and re…'
  api_count: 0
  score_band: thin
  score_composite: 34.0
  shared: 4
- slug: rest-assured
  name: REST Assured
  description: REST Assured is a Java library for simplifying the testing and validation of RESTful APIs. It provides a fluent domain-specific language (DSL) built on the given-when-then BDD pattern, making it easy to write readable and maintainable API…
  api_count: 1
  score_band: thin
  score_composite: 28.9
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
- slug: github-actions
  name: GitHub Actions
  description: GitHub Actions is GitHub's hosted CI/CD and workflow automation platform, and this record covers the REST API surface that drives it. Eighty-two operations across eleven resource areas let a caller dispatch and cancel workflow runs, poll r…
  api_count: 1
  score_band: exemplar
  score_composite: 82.8
  shared: 3
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: smartbear
  name: SmartBear
  description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI fo…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 3
- slug: keploy
  name: Keploy
  description: Open-source, AI-native testing platform that captures real production API traffic with eBPF and replays it in CI as deterministic tests, auto-generated mocks, and production-like sandboxes with zero code changes. Publishes a first-party Op…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 3
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 54.0
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
- slug: bruno-api
  name: Bruno
  description: Bruno is an open-source (MIT), git-native API client - a lightweight, offline-first alternative to Postman and Insomnia for exploring and testing APIs. It is a developer TOOL, not a hosted HTTP API provider. Collections are stored on the l…
  api_count: 6
  score_band: developing
  score_composite: 51.9
  shared: 3
- slug: opkey
  name: Opkey
  description: Opkey (Smart Software Testing Solutions, Inc.) is a US-headquartered Cloud Application Lifecycle Management and AI-powered test automation vendor for enterprise packaged applications. Its no-code platform ships pre-built automated tests an…
  api_count: 1
  score_band: developing
  score_composite: 48.9
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
- slug: selenium
  name: Selenium
  description: Selenium is the open-source browser automation project behind the W3C WebDriver and WebDriver BiDi standards. It drives real browsers through a vendor-neutral, standardised HTTP wire protocol that the browser vendors implement themselves,…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 3
- slug: cypressio
  name: Cypress.io
  description: Cypress.io, Inc. builds Cypress, an open-source, JavaScript-based end-to-end and component testing framework that runs tests directly in the browser with time-travel debugging, automatic waiting, and cross-browser support. Its commercial C…
  api_count: 1
  score_band: thin
  score_composite: 37.8
  shared: 3
- slug: ellipsis
  name: Ellipsis
  description: Ellipsis is a managed cloud platform for running autonomous coding agents at scale. Engineering teams define agents as YAML config files that live in their repositories, and Ellipsis runs them in isolated, ephemeral sandboxes to review pul…
  api_count: 1
  score_band: thin
  score_composite: 37.3
  shared: 3
- slug: antithesis
  name: Antithesis
  description: Antithesis is an autonomous software testing platform that finds deep bugs in mission-critical systems using deterministic simulation and continuous fuzzing. It runs your entire system inside a deterministic hypervisor, injects faults and…
  api_count: 1
  score_band: thin
  score_composite: 34.1
  shared: 3
- slug: ranger
  name: Ranger
  description: Ranger is an AI-powered quality-assurance platform that lets coding agents verify their own work in a real browser. Its CLI (@ranger-testing/ranger-cli) sets up a project so an AI coding agent — Claude Code, OpenCode, Cursor, Codex, or any…
  api_count: 0
  score_band: thin
  score_composite: 29.0
  shared: 3
- slug: cucumber
  name: Cucumber
  description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing execu…
  api_count: 5
  score_band: thin
  score_composite: 28.2
  shared: 3
- slug: headspin
  name: HeadSpin
  description: HeadSpin is a real-device digital-experience, functional, and performance testing platform for mobile, web, and OTT applications. Teams test, monitor, and optimize app behavior on real devices and real SIMs across 60+ locations in 50+ coun…
  api_count: 1
  score_band: emerging
  score_composite: 22.9
  shared: 3
- slug: igent
  name: iGent
  description: iGent AI is a UK-based artificial intelligence company (Altrincham, Cheshire) building Maestro, an autonomous AI software-engineering agent. Maestro pairs adaptive autonomy with an ensemble of frontier AI models to plan, generate, test, an…
  api_count: 0
  score_band: emerging
  score_composite: 20.7
  shared: 3
- slug: runscope
  name: Runscope
  description: Runscope is an API monitoring and testing platform that lets teams create, schedule, and run automated tests against their APIs to catch performance problems, uptime issues, and functional regressions before customers do. Originally an ind…
  api_count: 1
  score_band: emerging
  score_composite: 19.2
  shared: 3
- slug: testlio
  name: Testlio
  description: Testlio is a managed software testing and quality assurance company that pairs a global, vetted community of expert testers with a testing-management platform (powered by its Leo AI Engine) to deliver on-demand manual, automated, functiona…
  api_count: 0
  score_band: emerging
  score_composite: 18.6
  shared: 3
---
