---
layout: topic
slug: test-driven-development
name: Test-Driven Development
kind: topic
description: A software development approach where tests are written before the actual code, following a red-green-refactor cycle to ensure code quality and maintainability. TDD requires developers to write failing tests first, then write minimal code to make them pass, then refactor. It supports the full software development lifecycle from design through deployment and maintenance and is foundational to agile and extreme programming methodologies.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-driven-development.png
tags:
- Agile
- Best Practices
- Continuous Integration
- Developer Tools
- Extreme Programming
- Methodology
- Software Development
- Testing
repo: https://github.com/api-evangelist/test-driven-development
api_count: 5
apis:
- name: Jenkins API
  description: REST API for Jenkins automation server supporting build triggers, test execution, and pipeline management for TDD-based development workflows.
  url: https://www.jenkins.io/doc/book/using/remote-access-api/
- name: SonarQube API
  description: REST API for SonarQube code quality and security analysis platform, supporting test coverage metrics, code smells, and quality gate enforcement in TDD pipelines.
  url: https://docs.sonarsource.com/sonarqube/latest/extension-guide/web-api/
- name: Codecov API
  description: REST API for Codecov code coverage reporting service, enabling programmatic access to coverage reports, branch comparisons, and coverage trends in TDD workflows.
  url: https://docs.codecov.com/reference
- name: Coveralls API
  description: REST API for Coveralls code coverage history and statistics service, tracking test coverage over time and integrating with GitHub for TDD feedback loops.
  url: https://docs.coveralls.io
- name: Test-Driven Development Repos API
  description: The Repos API from Test-Driven Development — 7 operation(s) for repos.
  url: https://docs.github.com/en/rest/actions
links:
- type: Plans
  url: https://artifacts.apis.io/test-driven-development/plans/test-driven-development-plans-pricing.yml
- type: RateLimits
  url: https://artifacts.apis.io/test-driven-development/rate-limits/test-driven-development-rate-limits.yml
- type: FinOps
  url: https://artifacts.apis.io/test-driven-development/finops/test-driven-development-finops.yml
- type: BlogRSS
  url: https://www.jenkins.io/rss.xml
- type: CapabilityMap
  url: https://artifacts.apis.io/test-driven-development/capabilities/test-driven-development-capability-edges.yml
- type: AgenticAccess
  url: https://artifacts.apis.io/test-driven-development/agentic-access/test-driven-development-agentic-access.yml
- type: TrustCenter
  url: https://artifacts.apis.io/test-driven-development/security/test-driven-development-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://artifacts.apis.io/test-driven-development/security/test-driven-development-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://artifacts.apis.io/test-driven-development/security/test-driven-development-domain-security.yml
- type: Authentication
  url: https://artifacts.apis.io/test-driven-development/authentication/test-driven-development-authentication.yml
- type: Documentation
  url: https://en.wikipedia.org/wiki/Test-driven_development
- type: Documentation
  url: https://martinfowler.com/bliki/TestDrivenDevelopment.html
- type: JSONSchema
  url: https://artifacts.apis.io/test-driven-development/json-schema/test-driven-development-cycle-schema.json
- type: JSONSchema
  url: https://artifacts.apis.io/test-driven-development/json-schema/test-driven-development-coverage-report-schema.json
- type: JSONSchema
  url: https://artifacts.apis.io/test-driven-development/json-schema/test-driven-development-test-spec-schema.json
- type: JSONLD
  url: https://artifacts.apis.io/test-driven-development/json-ld/test-driven-development-context.jsonld
- type: Vocabulary
  url: https://artifacts.apis.io/test-driven-development/vocabulary/test-driven-development-vocabulary.yml
provider_count: 101
providers:
- slug: github-actions
  name: GitHub Actions
  description: GitHub Actions is GitHub's hosted CI/CD and workflow automation platform, and this record covers the REST API surface that drives it. Eighty-two operations across eleven resource areas let a caller dispatch and cancel workflow runs, poll r…
  api_count: 2
  score_band: exemplar
  score_composite: 82.6
  shared: 3
- slug: shortcut-software
  name: Shortcut Software
  description: Shortcut (formerly Clubhouse, renamed 2021) is a fast, lightweight project-management platform where software teams and their AI agents plan, build, and ship together — issue tracking, sprints, docs, and roadmaps in one tool. Founded in 20…
  api_count: 1
  score_band: exemplar
  score_composite: 71.4
  shared: 3
- slug: signadot
  name: Signadot
  description: 'Signadot is a Kubernetes-native platform for validating microservices and AI-generated code changes against real dependencies before merge. Its core is environment virtualization: large numbers of lightweight ephemeral "sandboxes" spin up…'
  api_count: 1
  score_band: strong
  score_composite: 63.2
  shared: 3
- slug: kubeshop
  name: Kubeshop
  description: Kubeshop is the company behind Testkube, an open-core, Kubernetes-native test orchestration platform. Testkube runs agents inside Kubernetes clusters under a central control plane, orchestrating tests written for existing frameworks — Cypr…
  api_count: 3
  score_band: strong
  score_composite: 62.2
  shared: 3
- slug: opkey
  name: Opkey
  description: Opkey (Smart Software Testing Solutions, Inc.) is a US-headquartered Cloud Application Lifecycle Management and AI-powered test automation vendor for enterprise packaged applications. Its no-code platform ships pre-built automated tests an…
  api_count: 1
  score_band: strong
  score_composite: 59.3
  shared: 3
- slug: teamcity
  name: TeamCity
  description: JetBrains TeamCity is a powerful continuous integration and deployment server that helps development teams build, test, and deploy software efficiently. TeamCity provides a comprehensive REST API for automating CI/CD workflows, managing pr…
  api_count: 1
  score_band: developing
  score_composite: 45.1
  shared: 3
- slug: codspeed
  name: CodSpeed
  description: CodSpeed is a continuous performance testing and optimization platform that automatically detects performance regressions in pull requests and proposes autonomous optimizations. It runs benchmarks with sub-1% variance inside CI (GitHub Act…
  api_count: 0
  score_band: developing
  score_composite: 44.1
  shared: 3
- slug: launchable
  name: Launchable
  description: Launchable is a software development intelligence platform for continuous integration that applies machine learning to CI and test data to speed up software delivery. Its flagship capability, Predictive Test Selection, records builds, test…
  api_count: 1
  score_band: developing
  score_composite: 42.9
  shared: 3
- slug: limrun
  name: Limrun
  description: Limrun (Limrun, Inc.) is a Y Combinator-backed cloud infrastructure company for mobile development, built so cloud coding agents and Linux CI runners can build, run, and test iOS and Android apps without a Mac. Limrun exposes three composa…
  api_count: 1
  score_band: developing
  score_composite: 40.4
  shared: 3
- slug: simantic
  name: Simantic
  description: Simantic builds simulated hardware for embedded QA, modernizing embedded firmware development through hardware simulation designed for AI adoption in hardware engineering. Its platform emulates microcontroller (MCU) systems so engineers ca…
  api_count: 0
  score_band: emerging
  score_composite: 17.6
  shared: 3
- slug: atomicjar
  name: AtomicJar
  description: AtomicJar is a developer-testing company, founded in 2021 by the original creators and maintainers of the open-source Testcontainers project and acquired by Docker in December 2023. AtomicJar builds tooling that lets developers run reliabl…
  api_count: 0
  score_band: emerging
  score_composite: 16.0
  shared: 3
- slug: approxima
  name: Approxima
  description: 'Approxima is a Y Combinator (Winter 2026) startup building AI agents that test every pull request. Approxima plugs into your CI/CD pipeline and runs autonomous agents on each PR: the agents build your application in an isolated sandbox, ex…'
  api_count: 0
  score_band: emerging
  score_composite: 12.2
  shared: 3
- slug: gitlab
  name: GitLab
  description: GitLab Inc. is an open-core company that develops GitLab, a DevOps software platform for building, securing, and managing applications. Created by Ukrainian developer Dmytro Zaporozhets and Dutch developer Sytse Sijbrandij, GitLab became t…
  api_count: 14
  score_band: exemplar
  score_composite: 86.3
  shared: 2
- slug: github
  name: GitHub
  description: The GitHub REST API allows developers to programmatically interact with GitHub resources including repositories, users, organizations, pull requests, issues, and more.
  api_count: 8
  score_band: exemplar
  score_composite: 85.0
  shared: 2
- slug: microsoft-azure-devops
  name: Azure DevOps
  description: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications.
  api_count: 11
  score_band: exemplar
  score_composite: 81.9
  shared: 2
- slug: currents-dev
  name: Currents
  description: Currents (Currents Software Inc., currents.dev) is a Playwright-focused test reporter, cloud dashboard and test orchestrator that helps teams scale Playwright tests in CI and optimize complex test suites for health, reliability and perform…
  api_count: 2
  score_band: exemplar
  score_composite: 77.7
  shared: 2
- slug: circleci
  name: CircleCI
  description: CircleCI is a continuous integration and continuous delivery (CI/CD) platform that automates software build, test, and deployment pipelines. Their developer surface includes the REST API v2 (the recommended modern interface), the legacy v1…
  api_count: 3
  score_band: exemplar
  score_composite: 73.5
  shared: 2
- slug: aws-codebuild
  name: AWS CodeBuild
  description: AWS CodeBuild is a fully managed continuous integration build service that compiles source code, runs unit tests, and produces deployable artifacts. It eliminates the need to provision, manage, and scale build servers by providing prepacka…
  api_count: 14
  score_band: exemplar
  score_composite: 71.8
  shared: 2
- slug: cloudbees
  name: CloudBees
  description: CloudBees provides software delivery automation across continuous integration, continuous deployment, release orchestration, and feature management. Their developer surface includes the CloudBees CI REST API (an extension of the Jenkins RE…
  api_count: 2
  score_band: exemplar
  score_composite: 70.3
  shared: 2
- slug: tempmailgrab
  name: TempMailGrab API
  description: Privacy-first disposable/temporary email service with private 24-hour inboxes, real-time WebSocket delivery, automatic OTP and verification-link extraction, attachments, webhooks, custom domains, and a versioned REST API for QA, test autom…
  api_count: 1
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: taskfolk
  name: Taskfolk
  description: Taskfolk is a project-management and issue-tracking platform built for teams and their AI agents working side by side, operated by UTTER L.L.C-FZ of Dubai, UAE. Workspaces contain projects; projects contain issues moved across board, backl…
  api_count: 2
  score_band: exemplar
  score_composite: 68.3
  shared: 2
- slug: codebahn-net
  name: Codebahn
  description: Codebahn is a private, fast GitHub alternative offering managed Git hosting and CI for developers and teams, built on the open-source Forgejo forge. It is operated by Hackerman AB (Gothenburg, Sweden; Org. nr 559079-1918), runs on EU-only…
  api_count: 2
  score_band: exemplar
  score_composite: 68.1
  shared: 2
- slug: google-cloud-build
  name: Google Cloud Build
  description: Google Cloud Build is a fully managed continuous integration and continuous delivery (CI/CD) platform that lets you build, test, and deploy software quickly across all languages and frameworks. It executes builds on Google Cloud infrastruc…
  api_count: 1
  score_band: exemplar
  score_composite: 66.7
  shared: 2
- slug: scorecard
  name: Scorecard
  description: Scorecard is a simulation and evaluation platform for building, testing, and deploying frontier AI agents. Teams run their agents through thousands of realistic scenarios, judge outputs with configurable AI, human, and heuristic metrics, a…
  api_count: 1
  score_band: strong
  score_composite: 61.6
  shared: 2
- slug: gradle
  name: Gradle
  description: Gradle Inc. (Gradle Technologies) is the company behind the open-source Gradle Build Tool, downloaded more than 25 million times a month across the Java, JVM, Android, Kotlin, C/C++, and native ecosystems, and Develocity (formerly Gradle E…
  api_count: 1
  score_band: strong
  score_composite: 61.1
  shared: 2
- slug: emerge-tools
  name: Emerge Tools
  description: Emerge Tools is a mobile developer-tools platform used by teams at DoorDash, Square, and Duolingo to ship faster, smaller, better-performing iOS and Android apps. Its products include Size Analysis (monitor and reduce app size with PR aler…
  api_count: 1
  score_band: strong
  score_composite: 60.5
  shared: 2
- slug: apidog
  name: Apidog
  description: 'Apidog is an all-in-one API development platform that connects the entire API lifecycle: visual API design, multi-protocol debugging (HTTP, REST, GraphQL, gRPC, WebSocket, SOAP, SSE), automated testing with a CLI, smart mocking, and publis…'
  api_count: 1
  score_band: strong
  score_composite: 59.5
  shared: 2
- slug: mailfixture-com
  name: mailfixture
  description: Mailfixture provides an API that creates real test inboxes for developers. With a single call you can generate a disposable email address, receive OTPs, verification links, and other messages, and retrieve them programmatically. This enabl…
  api_count: 1
  score_band: strong
  score_composite: 59.2
  shared: 2
- slug: keploy
  name: Keploy
  description: Open-source, AI-native testing platform that captures real production API traffic with eBPF and replays it in CI as deterministic tests, auto-generated mocks, and production-like sandboxes with zero code changes. Publishes a first-party Op…
  api_count: 1
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: parabol
  name: Parabol
  description: Parabol is an open-source collaborative workspace that helps teams run more effective, inclusive, and engaging meetings — retrospectives, sprint poker estimation, check-ins/standups, and collaborative Pages documents — all in real time. Pa…
  api_count: 1
  score_band: strong
  score_composite: 58.3
  shared: 2
---
