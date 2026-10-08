---
layout: topic
slug: bdd
name: BDD (Behavior-Driven Development)
kind: topic
description: Behavior-Driven Development (BDD) is a software development methodology that combines test-driven development with domain-driven design, encouraging collaboration between developers, QA, and business stakeholders through human-readable test scenarios. The BDD ecosystem includes frameworks, tools, and data providers that enable teams to write specifications in Gherkin syntax (Given-When-Then) and automate those scenarios as executable tests across APIs, UIs, and microservices.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/bdd.png
tags:
- Automation
- BDD
- Software Development
- Testing
- Gherkin
- Quality Assurance
repo: https://github.com/api-evangelist/bdd
api_count: 5
apis:
- name: Cucumber
  description: Cucumber is the world's most popular BDD framework, supporting Java, JavaScript, Ruby, Python, and C#. It uses Gherkin syntax for writing human-readable test scenarios and provides integrations with all major test runners, CI/CD platforms,…
  url: https://cucumber.io/
- name: SpecFlow
  description: SpecFlow is a BDD framework for .NET developers, enabling teams to write behavior specifications in Gherkin and execute them in C# applications. SpecFlow+ Runner and SpecFlow+ LivingDoc provide enhanced test execution and living documentat…
  url: https://specflow.org/
- name: Behave
  description: Behave is a Python BDD framework inspired by Cucumber that enables teams to write behavior specifications in Gherkin syntax and execute them using Python. It integrates with Django, Flask, FastAPI, and REST API testing tools.
  url: https://behave.readthedocs.io/
- name: Karate
  description: Karate is a modern open-source BDD framework that unifies API testing, UI automation, performance testing, and mocking in a single framework. It uses a Gherkin-like DSL and is particularly powerful for REST and GraphQL API testing with JSO…
  url: https://karatelabs.github.io/karate/
- name: JBehave
  description: JBehave is a pioneering BDD framework for Java and JVM languages. It supports web, REST API, and microservices testing with integration for JUnit, Spring, Maven, and Gradle. JBehave Web extends the framework for browser-based BDD testing.
  url: https://jbehave.org/
links:
- type: IssueTracker
  url: https://github.com/cucumber/cucumber-jvm/issues
- type: Releases
  url: https://github.com/cucumber/cucumber-jvm/releases
- type: CodeOfConduct
  url: https://github.com/cucumber/.github/blob/main/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/cucumber/cucumber-jvm/blob/main/CONTRIBUTING.md
- type: License
  url: https://github.com/cucumber/cucumber-jvm/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/bdd/blob/main/security/bdd-domain-security.yml
- type: Website
  url: https://cucumber.io/
- type: Blog
  url: https://cucumber.io/blog/rss.xml
- type: Documentation
  url: https://cucumber.io/docs/
- type: GitHubOrganization
  url: https://github.com/cucumber
provider_count: 42
providers:
- slug: cucumber
  name: Cucumber
  description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing execu…
  api_count: 5
  score_band: thin
  score_composite: 28.2
  shared: 5
- slug: automation-preflight-api
  name: Automation Preflight API
  description: A self-serve REST API by TinyOps Studio LLC that inspects a public URL and returns deterministic, bounded JSON integration-readiness evidence across reachability, integration surface, and readiness scoring. It rejects private/credential-be…
  api_count: 2
  score_band: developing
  score_composite: 49.2
  shared: 3
- slug: sauce-labs
  name: Sauce Labs
  description: Sauce Labs is a cloud-based cross-browser and mobile app testing platform trusted by over 100,000 customers worldwide. It provides a comprehensive set of REST APIs for managing test jobs, devices, builds, insights, and results across virtu…
  api_count: 2
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
- slug: headspin
  name: HeadSpin
  description: HeadSpin is a real-device digital-experience, functional, and performance testing platform for mobile, web, and OTT applications. Teams test, monitor, and optimize app behavior on real devices and real SIMs across 60+ locations in 50+ coun…
  api_count: 1
  score_band: emerging
  score_composite: 22.9
  shared: 3
- slug: step-ci
  name: Step CI
  description: Step CI is an open source API testing and monitoring framework that uses YAML-based workflows to define and run automated API test scenarios. It supports REST, GraphQL, gRPC, tRPC, and SOAP protocols in a single unified testing framework.…
  api_count: 1
  score_band: emerging
  score_composite: 18.9
  shared: 3
- slug: specflow
  name: SpecFlow
  description: SpecFlow was an open-source BDD (Behavior-Driven Development) testing framework for .NET that allowed teams to write executable specifications in natural language using the Gherkin syntax. Originally developed by TechTalk, it was acquired…
  api_count: 2
  score_band: emerging
  score_composite: 16.1
  shared: 3
- slug: github-actions
  name: GitHub Actions
  description: GitHub Actions is GitHub's hosted CI/CD and workflow automation platform, and this record covers the REST API surface that drives it. Eighty-two operations across eleven resource areas let a caller dispatch and cancel workflow runs, poll r…
  api_count: 1
  score_band: exemplar
  score_composite: 82.8
  shared: 2
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 2
- slug: browserstack
  name: BrowserStack
  description: BrowserStack provides instant access to 3,500+ real desktop browsers and 30,000+ real mobile device units for manual and automated software testing. Its products span cross-browser testing (Live, Automate), mobile app testing (App Live, Ap…
  api_count: 1
  score_band: exemplar
  score_composite: 67.8
  shared: 2
- slug: uipath
  name: UiPath
  description: UiPath is an enterprise automation platform offering robotic process automation (RPA), AI-powered automation, and agentic automation capabilities. The platform includes Orchestrator for managing robots and automation jobs, Studio for devel…
  api_count: 6
  score_band: strong
  score_composite: 66.3
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
- slug: coval
  name: Coval
  description: Coval is the deployment-readiness platform for voice and chat AI agents. Teams simulate thousands of realistic conversation scenarios before launch, monitor real production calls, and improve reliability with metrics and human review. Cova…
  api_count: 20
  score_band: developing
  score_composite: 51.6
  shared: 2
- slug: panaya
  name: Panaya
  description: Panaya is an enterprise change-intelligence and agentic-testing platform for business applications, helping organizations de-risk changes to SAP (including S/4HANA migrations and upgrades), Oracle (EBS, Cloud, NetSuite), Salesforce, Workda…
  api_count: 1
  score_band: developing
  score_composite: 49.3
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
- slug: assertible
  name: Assertible
  description: Assertible provides a reliable first line of defense against web service failures by providing simple and powerful assertions to test and monitor APIs. It enables automated API testing with assertions on response status, headers, body cont…
  api_count: 1
  score_band: developing
  score_composite: 48.2
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
- slug: lambdatest
  name: LambdaTest
  description: LambdaTest (rebranding as TestMu AI) is a cloud-based AI-powered test execution platform that enables developers and QA teams to run Selenium, Cypress, Playwright, and Appium automation tests across 3,000+ browser and OS combinations at sc…
  api_count: 2
  score_band: developing
  score_composite: 44.2
  shared: 2
- slug: autifyhq
  name: Autifyhq
  description: Autifyhq provides an AI-powered testing platform that automates end‑to‑end testing for web, mobile, and desktop applications. Leveraging AI agents, Autify enables no‑code test creation, visual recognition, and self‑healing locators, helpin…
  api_count: 6
  score_band: developing
  score_composite: 42.9
  shared: 2
- slug: testim-io
  name: Testim
  description: Testim is an AI-powered functional test automation platform for web and mobile applications, using machine learning to author, run, and self-heal UI tests. Acquired by Tricentis in 2022, Testim is offered as part of the Tricentis quality-e…
  api_count: 1
  score_band: developing
  score_composite: 40.2
  shared: 2
- slug: cypressio
  name: Cypress.io
  description: Cypress.io, Inc. builds Cypress, an open-source, JavaScript-based end-to-end and component testing framework that runs tests directly in the browser with time-travel debugging, automatic waiting, and cross-browser support. Its commercial C…
  api_count: 1
  score_band: thin
  score_composite: 37.8
  shared: 2
- slug: beeceptor
  name: Beeceptor
  description: Beeceptor is an API mocking, HTTP debugging, and proxy platform that lets developers create mock servers instantly without any coding. It supports REST, SOAP, GraphQL, and gRPC mocking, provides real-time HTTP traffic inspection, webhook t…
  api_count: 1
  score_band: thin
  score_composite: 37.4
  shared: 2
- slug: ellipsis
  name: Ellipsis
  description: Ellipsis is a managed cloud platform for running autonomous coding agents at scale. Engineering teams define agents as YAML config files that live in their repositories, and Ellipsis runs them in isolated, ephemeral sandboxes to review pul…
  api_count: 1
  score_band: thin
  score_composite: 37.3
  shared: 2
- slug: testiny
  name: Testiny
  description: Testiny is a modern test management platform for QA teams that keeps manual and automated test cases, test plans, test runs, and results in a single place, with reporting and integrations for Jira, GitLab, and GitHub. Everything in the pro…
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 2
- slug: qase
  name: Qase
  description: Qase is a cloud test management platform (TestOps) for QA and engineering teams to author test cases, organize them into suites and plans, launch and complete test runs, publish automated results from CI pipelines, and track defects. The Q…
  api_count: 1
  score_band: thin
  score_composite: 31.4
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
---
