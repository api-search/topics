---
layout: topic
slug: test-plans
name: Test Plans
kind: topic
description: Structured documentation outlining test objectives, scope, approach, resources, schedule, and deliverables for software testing activities. Test plans define the overall strategy for testing a system or feature, specifying what will be tested, how it will be tested, who will test it, and what constitutes a pass or fail. They are critical for coordinating testing efforts across teams and ensuring comprehensive coverage.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-plans.png
tags:
- Documentation
- Quality Assurance
- Software Development
- Test Management
- Testing
repo: https://github.com/api-evangelist/test-plans
api_count: 5
apis:
- name: TestRail API
  description: REST API for TestRail test management including test plans, test runs, milestones, and reporting, enabling structured test planning and execution tracking.
  url: https://www.testrail.com
- name: Jira Software API
  description: REST API for Jira Software project management, supporting test plan tracking via epics, sprints, issues, and custom fields integrated with testing workflows.
  url: https://developer.atlassian.com/cloud/jira/software/rest/intro/
- name: Azure DevOps Test Plans API
  description: REST API for Azure DevOps Test Plans service supporting test plan creation, test suites, test case management, test execution, and results reporting.
  url: https://learn.microsoft.com/en-us/rest/api/azure/devops/testplan/
- name: qTest API
  description: REST API for qTest test management platform by Tricentis, supporting test plan management, test cycle creation, defect linking, and release-level test planning.
  url: https://documentation.tricentis.com/qtestmanager/10.0/en/content/qtestmanager/api/intro.htm
- name: ALM Octane API
  description: REST API for Micro Focus ALM Octane test planning and quality management, supporting test planning, defect management, and release quality tracking.
  url: https://admhelp.microfocus.com/octane/en/latest/Online/Content/API/REST_API.htm
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/test-plans/blob/main/security/test-plans-domain-security.yml
- type: Documentation
  url: https://en.wikipedia.org/wiki/Test_plan
- type: Documentation
  url: https://www.guru99.com/what-is-test-plan-how-to-write-it.html
- type: JSONSchema
  url: https://github.com/api-evangelist/test-plans/blob/main/json-schema/test-plans-test-plan-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-plans/blob/main/json-schema/test-plans-test-cycle-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-plans/blob/main/json-schema/test-plans-milestone-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/test-plans/blob/main/json-ld/test-plans-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/test-plans/blob/main/vocabulary/test-plans-vocabulary.yml
provider_count: 37
providers:
- slug: panaya
  name: Panaya
  description: Panaya is an enterprise change-intelligence and agentic-testing platform for business applications, helping organizations de-risk changes to SAP (including S/4HANA migrations and upgrades), Oracle (EBS, Cloud, NetSuite), Salesforce, Workda…
  api_count: 1
  score_band: developing
  score_composite: 47.2
  shared: 3
- slug: testiny
  name: Testiny
  description: Testiny is a modern test management platform for QA teams that keeps manual and automated test cases, test plans, test runs, and results in a single place, with reporting and integrations for Jira, GitLab, and GitHub. Everything in the pro…
  api_count: 1
  score_band: developing
  score_composite: 40.0
  shared: 3
- slug: qase
  name: Qase
  description: Qase is a cloud test management platform (TestOps) for QA and engineering teams to author test cases, organize them into suites and plans, launch and complete test runs, publish automated results from CI pipelines, and track defects. The Q…
  api_count: 1
  score_band: thin
  score_composite: 35.4
  shared: 3
- slug: bdd
  name: BDD (Behavior-Driven Development)
  description: Behavior-Driven Development (BDD) is a software development methodology that combines test-driven development with domain-driven design, encouraging collaboration between developers, QA, and business stakeholders through human-readable tes…
  api_count: 5
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: tricentis
  name: Tricentis
  description: Tricentis is an enterprise continuous testing and quality engineering company, founded in Austria in 2007 and headquartered in Vienna with US operations in Austin, Texas. Its platform spans model-based UI and API test automation (Tosca, To…
  api_count: 8
  score_band: strong
  score_composite: 64.9
  shared: 2
- slug: treblle
  name: Treblle
  description: Treblle helps engineering and product teams build, ship and understand their REST APIs in one single place. Empowering API producers by showing actionable data in real-time where it matters. Gain a deeper understanding of your API consumer…
  api_count: 1
  score_band: strong
  score_composite: 56.5
  shared: 2
- slug: speakeasy
  name: Speakeasy
  description: The platform to Build APIs your users love. Best in class API tooling for robust SDKs, API docs, Terraform providers and end-to-end testing.
  api_count: 1
  score_band: developing
  score_composite: 53.4
  shared: 2
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
- slug: selenium
  name: Selenium
  description: Selenium is the open-source browser automation project behind the W3C WebDriver and WebDriver BiDi standards. It drives real browsers through a vendor-neutral, standardised HTTP wire protocol that the browser vendors implement themselves,…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: testrail
  name: TestRail
  description: TestRail is a web-based test case management and QA platform (originally by Gurock, now part of IDERA) for organizing test cases, running test runs and test plans, and recording test results across manual and automated testing. Its HTTP AP…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 2
- slug: testmo
  name: Testmo
  description: Testmo is a unified test management platform that brings manual test cases, test automation, and exploratory testing together in one tool, with reporting, milestones, and issue-tracker and CI integrations. Testmo exposes a documented REST…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 2
- slug: cypressio
  name: Cypress.io
  description: Cypress.io, Inc. builds Cypress, an open-source, JavaScript-based end-to-end and component testing framework that runs tests directly in the browser with time-travel debugging, automatic waiting, and cross-browser support. Its commercial C…
  api_count: 1
  score_band: thin
  score_composite: 37.3
  shared: 2
- slug: cucumber
  name: Cucumber
  description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing execu…
  api_count: 5
  score_band: thin
  score_composite: 29.4
  shared: 2
- slug: ranger
  name: Ranger
  description: Ranger is an AI-powered quality-assurance platform that lets coding agents verify their own work in a real browser. Its CLI (@ranger-testing/ranger-cli) sets up a project so an AI coding agent — Claude Code, OpenCode, Cursor, Codex, or any…
  api_count: 0
  score_band: thin
  score_composite: 27.8
  shared: 2
- slug: apigit
  name: APIGit
  description: APIGit is a Git-native platform for full lifecycle API development that combines version control, API design, documentation generation, governance, testing, and dynamic mock servers in a single integrated environment. Teams can build, publ…
  api_count: 4
  score_band: emerging
  score_composite: 26.1
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
- slug: regression-games
  name: Regression Games
  description: Regression Games builds AI agents and bots for video games. Its platform lets studios create bots for QA testing, multiplayer simulation, game balancing, and NPC behavior with minimal code. The Unity SDK (gg.regression.unity.bots / RGUnity…
  api_count: 0
  score_band: emerging
  score_composite: 15.6
  shared: 2
- slug: girnarsoft
  name: GirnarSoft
  description: GirnarSoft is an India-based enterprise software engineering and IT services company headquartered in Jaipur, Rajasthan, with a second delivery centre in Gurugram. Founded in 2007 by IIT Delhi alumni Amit and Anurag Jain, it is the technol…
  api_count: 0
  score_band: emerging
  score_composite: 15.1
  shared: 2
---
