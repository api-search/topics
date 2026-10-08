---
layout: topic
slug: test-suites
name: Test Suites
kind: topic
description: A collection of organized test cases designed to validate specific functionality or features of software applications and APIs. Test suites group related test cases into logical units that can be executed together, providing comprehensive coverage of a system's behavior. They are widely used by developers to build, maintain, and scale software testing across functional testing, regression testing, contract testing, and compliance validation. Test suites range from unit test collections in JUnit and pytest to API test collection suites in Postman, Bruno, and Karate.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-suites.png
tags:
- API Testing
- Collection
- Quality Assurance
- Software Development
- Test Management
- Testing
repo: https://github.com/api-evangelist/test-suites
api_count: 10
apis:
- name: JUnit 5
  description: JUnit 5 is the Java testing framework used to organize test cases into test suites. The @Suite annotation enables test class grouping, tag-based filtering, and hierarchical suite composition, making it the standard Java test suite manageme…
  url: https://junit.org/junit5/
- name: pytest
  description: pytest is the Python testing framework supporting test suite organization through test classes, directories, markers, and fixtures. Its plugin architecture enables test suite reporting, parallel execution, and integration with coverage ana…
  url: https://pytest.org/
- name: Jasmine
  description: Jasmine is a behavior-driven JavaScript testing framework that organizes test cases into describe/it suite blocks. It is commonly used for organizing API client test suites in Node.js environments and browser-based JavaScript applications.
  url: https://jasmine.github.io/
- name: Mocha
  description: Mocha is a flexible JavaScript test suite framework supporting both synchronous and asynchronous API tests. It provides describe/it nesting for suite organization, rich reporting, and integration with assertion libraries such as Chai and S…
  url: https://mochajs.org/
- name: Jest
  description: Jest is a zero-configuration JavaScript testing framework with built-in test suite runner, mocking, coverage reporting, and snapshot testing. Widely used for React applications and Node.js API services, Jest organizes test cases into descr…
  url: https://jestjs.io/
- name: Bruno
  description: Bruno is an open-source API client and test suite manager that stores API collections as plain files alongside application code. It enables version- controlled test suites in a format designed for git-based collaboration, with scripting su…
  url: https://www.usebruno.com/
- name: Hurl
  description: Hurl is a command-line tool that runs HTTP requests defined in a simple plain-text format, enabling lightweight API test suites that can be committed to source control and executed in CI/CD pipelines without additional runtime dependencies.
  url: https://hurl.dev/
- name: TestNG
  description: TestNG is a Java testing framework inspired by JUnit and NUnit that provides advanced test suite configuration including grouping, prioritization, parameterized tests, and parallel execution. It is widely used for API integration test suit…
  url: https://testng.org/
- name: Test Suites Collections API
  description: The Collections API from Test Suites — 2 operation(s) for collections.
  url: https://www.postman.com/
- name: Test Suites Workspaces API
  description: The Workspaces API from Test Suites — 2 operation(s) for workspaces.
  url: https://www.postman.com/
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/test-suites/blob/main/capabilities/test-suites-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/test-suites/blob/main/agentic-access/test-suites-agentic-access.yml
- type: TrustCenter
  url: https://github.com/api-evangelist/test-suites/blob/main/security/test-suites-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/test-suites/blob/main/security/test-suites-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/test-suites/blob/main/security/test-suites-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/test-suites/blob/main/authentication/test-suites-authentication.yml
- type: GitHubOrg
  url: https://github.com/api-evangelist/test-suites
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-schema/test-suites-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-structure/test-suites-structure.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/json-ld/test-suites-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/test-suites/main/vocabulary/test-suites-vocabulary.yml
provider_count: 45
providers:
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 3
- slug: panaya
  name: Panaya
  description: Panaya is an enterprise change-intelligence and agentic-testing platform for business applications, helping organizations de-risk changes to SAP (including S/4HANA migrations and upgrades), Oracle (EBS, Cloud, NetSuite), Salesforce, Workda…
  api_count: 1
  score_band: developing
  score_composite: 49.3
  shared: 3
- slug: assertible
  name: Assertible
  description: Assertible provides a reliable first line of defense against web service failures by providing simple and powerful assertions to test and monitor APIs. It enables automated API testing with assertions on response status, headers, body cont…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 3
- slug: testim-io
  name: Testim
  description: Testim is an AI-powered functional test automation platform for web and mobile applications, using machine learning to author, run, and self-heal UI tests. Acquired by Tricentis in 2022, Testim is offered as part of the Tricentis quality-e…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 3
- slug: testiny
  name: Testiny
  description: Testiny is a modern test management platform for QA teams that keeps manual and automated test cases, test plans, test runs, and results in a single place, with reporting and integrations for Jira, GitLab, and GitHub. Everything in the pro…
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 3
- slug: qase
  name: Qase
  description: Qase is a cloud test management platform (TestOps) for QA and engineering teams to author test cases, organize them into suites and plans, launch and complete test runs, publish automated results from CI pipelines, and track defects. The Q…
  api_count: 1
  score_band: thin
  score_composite: 31.4
  shared: 3
- slug: step-ci
  name: Step CI
  description: Step CI is an open source API testing and monitoring framework that uses YAML-based workflows to define and run automated API test scenarios. It supports REST, GraphQL, gRPC, tRPC, and SOAP protocols in a single unified testing framework.…
  api_count: 1
  score_band: emerging
  score_composite: 18.9
  shared: 3
- slug: muuktest
  name: Muuktest
  description: MuukTest (MuukLabs) is an AI-powered test automation and managed QA services company founded in 2019 that helps software teams reach high end-to-end test coverage in weeks rather than months. It blends an AI-driven automation platform with…
  api_count: 0
  score_band: emerging
  score_composite: 12.1
  shared: 3
- slug: tricentis
  name: Tricentis
  description: Tricentis is an enterprise continuous testing and quality engineering company, founded in Austria in 2007 and headquartered in Vienna with US operations in Austin, Texas. Its platform spans model-based UI and API test automation (Tosca, To…
  api_count: 8
  score_band: exemplar
  score_composite: 68.0
  shared: 2
- slug: smartbear
  name: SmartBear
  description: SmartBear is a software company that provides AI-powered tools for API lifecycle management including design, testing, documentation, and governance. Their product portfolio includes SwaggerHub for API design and documentation, ReadyAPI fo…
  api_count: 1
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: keploy
  name: Keploy
  description: Open-source, AI-native testing platform that captures real production API traffic with eBPF and replays it in CI as deterministic tests, auto-generated mocks, and production-like sandboxes with zero code changes. Publishes a first-party Op…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: testfairy
  name: TestFairy
  description: TestFairy is a mobile app testing and distribution platform, now part of Sauce Labs, that lets teams upload iOS and Android builds, distribute them to beta testers, and record video sessions of testers using the app alongside device logs,…
  api_count: 1
  score_band: developing
  score_composite: 53.7
  shared: 2
- slug: kubeshop
  name: Kubeshop
  description: Kubeshop is the company behind Testkube, an open-core, Kubernetes-native test orchestration platform. Testkube runs agents inside Kubernetes clusters under a central control plane, orchestrating tests written for existing frameworks — Cypr…
  api_count: 3
  score_band: developing
  score_composite: 52.9
  shared: 2
- slug: bruno-api
  name: Bruno
  description: Bruno is an open-source (MIT), git-native API client - a lightweight, offline-first alternative to Postman and Insomnia for exploring and testing APIs. It is a developer TOOL, not a hosted HTTP API provider. Collections are stored on the l…
  api_count: 6
  score_band: developing
  score_composite: 51.9
  shared: 2
- slug: coval
  name: Coval
  description: Coval is the deployment-readiness platform for voice and chat AI agents. Teams simulate thousands of realistic conversation scenarios before launch, monitor real production calls, and improve reliability with metrics and human review. Cova…
  api_count: 20
  score_band: developing
  score_composite: 51.6
  shared: 2
- slug: automation-preflight-api
  name: Automation Preflight API
  description: A self-serve REST API by TinyOps Studio LLC that inspects a public URL and returns deterministic, bounded JSON integration-readiness evidence across reachability, integration surface, and readiness scoring. It rejects private/credential-be…
  api_count: 2
  score_band: developing
  score_composite: 49.2
  shared: 2
- slug: opkey
  name: Opkey
  description: Opkey (Smart Software Testing Solutions, Inc.) is a US-headquartered Cloud Application Lifecycle Management and AI-powered test automation vendor for enterprise packaged applications. Its no-code platform ships pre-built automated tests an…
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 2
- slug: rainforest-qa
  name: Rainforest QA
  description: Rainforest QA is a no-code software testing platform that combines AI-powered test creation, crowdsourced manual QA, and automated browser testing in one place. Its REST API and command-line interface let teams create and manage tests, env…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 2
- slug: accessibe
  name: accessiBe
  description: accessiBe is a web accessibility technology company whose products help organizations make websites and web applications usable by people with disabilities and compliant with WCAG, the ADA, Section 508, AODA and the European Accessibility…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: replay
  name: Replay
  description: Replay is an AI-native QA and time-travel debugging platform for web applications. Replay QA autonomously explores a web app, records every session in a deterministic Replay Browser, finds real bugs, and hands a coding agent the root cause…
  api_count: 1
  score_band: developing
  score_composite: 44.9
  shared: 2
- slug: sauce-labs
  name: Sauce Labs
  description: Sauce Labs is a cloud-based cross-browser and mobile app testing platform trusted by over 100,000 customers worldwide. It provides a comprehensive set of REST APIs for managing test jobs, devices, builds, insights, and results across virtu…
  api_count: 2
  score_band: developing
  score_composite: 44.9
  shared: 2
- slug: selenium
  name: Selenium
  description: Selenium is the open-source browser automation project behind the W3C WebDriver and WebDriver BiDi standards. It drives real browsers through a vendor-neutral, standardised HTTP wire protocol that the browser vendors implement themselves,…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 2
- slug: cypressio
  name: Cypress.io
  description: Cypress.io, Inc. builds Cypress, an open-source, JavaScript-based end-to-end and component testing framework that runs tests directly in the browser with time-travel debugging, automatic waiting, and cross-browser support. Its commercial C…
  api_count: 1
  score_band: thin
  score_composite: 37.8
  shared: 2
- slug: testrail
  name: TestRail
  description: TestRail is a web-based test case management and QA platform (originally by Gurock, now part of IDERA) for organizing test cases, running test runs and test plans, and recording test results across manual and automated testing. Its HTTP AP…
  api_count: 1
  score_band: thin
  score_composite: 35.5
  shared: 2
- slug: testmo
  name: Testmo
  description: Testmo is a unified test management platform that brings manual test cases, test automation, and exploratory testing together in one tool, with reporting, milestones, and issue-tracker and CI integrations. Testmo exposes a documented REST…
  api_count: 1
  score_band: thin
  score_composite: 35.3
  shared: 2
- slug: testsprite
  name: TestSprite
  description: 'TestSprite is an AI-powered software testing platform (a Techstars-backed company) that gives autonomous coding agents a verification loop: it uses an app like a real user, generates and executes end-to-end UI and backend API tests, and re…'
  api_count: 0
  score_band: thin
  score_composite: 34.0
  shared: 2
- slug: ranger
  name: Ranger
  description: Ranger is an AI-powered quality-assurance platform that lets coding agents verify their own work in a real browser. Its CLI (@ranger-testing/ranger-cli) sets up a project so an AI coding agent — Claude Code, OpenCode, Cursor, Codex, or any…
  api_count: 0
  score_band: thin
  score_composite: 29.0
  shared: 2
- slug: rest-assured
  name: REST Assured
  description: REST Assured is a Java library for simplifying the testing and validation of RESTful APIs. It provides a fluent domain-specific language (DSL) built on the given-when-then BDD pattern, making it easy to write readable and maintainable API…
  api_count: 1
  score_band: thin
  score_composite: 28.9
  shared: 2
- slug: cucumber
  name: Cucumber
  description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing execu…
  api_count: 5
  score_band: thin
  score_composite: 28.2
  shared: 2
---
