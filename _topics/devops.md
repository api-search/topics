---
layout: topic
slug: devops
name: DevOps
kind: topic
description: DevOps is a cultural and technical movement that combines software development and IT operations to shorten the development lifecycle and deliver high-quality software continuously. It emphasizes automation, collaboration, monitoring, and infrastructure as code to bridge the gap between building software and running it in production. DevOps spans tooling categories including version control, CI/CD, infrastructure automation, observability, and security integration.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/devops.png
tags:
- Automation
- CI/CD
- Configuration Management
- Containers
- Continuous Deployment
- Continuous Integration
- Developer Tools
- DevOps
- Infrastructure as Code
- Monitoring
- Observability
- Version Control
repo: https://github.com/api-evangelist/devops
api_count: 0
apis: []
links:
- type: Wikipedia
  url: https://en.wikipedia.org/wiki/DevOps
provider_count: 512
providers:
- slug: github-actions
  name: GitHub Actions
  description: GitHub Actions is GitHub's hosted CI/CD and workflow automation platform, and this record covers the REST API surface that drives it. Eighty-two operations across eleven resource areas let a caller dispatch and cancel workflow runs, poll r…
  api_count: 1
  score_band: exemplar
  score_composite: 82.8
  shared: 6
- slug: gitops
  name: GitOps
  description: A operational framework that takes DevOps best practices used for application development such as version control, collaboration, compliance, and CI/CD, and applies them to infrastructure automation. GitOps uses Git as a single source of t…
  api_count: 0
  score_band: minimal
  score_composite: 5.7
  shared: 6
- slug: circleci
  name: CircleCI
  description: CircleCI is a continuous integration and continuous delivery (CI/CD) platform that automates software build, test, and deployment pipelines. Their developer surface includes the REST API v2 (the recommended modern interface), the legacy v1…
  api_count: 2
  score_band: exemplar
  score_composite: 67.6
  shared: 5
- slug: woodpecker-ci
  name: Woodpecker CI
  description: 'Woodpecker CI is a free, open-source (Apache-2.0) continuous integration and delivery engine, forked from Drone and maintained by a community organization on GitHub. It is self-hosted: an operator runs a Woodpecker server plus one or more…'
  api_count: 1
  score_band: developing
  score_composite: 41.8
  shared: 5
- slug: avrea
  name: Avrea
  description: 'Avrea is CI/CD infrastructure for GitHub Actions: high-performance managed runners (AMD EPYC and Apple M-series), smart multi-system caching, and full build observability with flaky-test detection and live SSH debugging into running jobs.…'
  api_count: 0
  score_band: thin
  score_composite: 31.7
  shared: 5
- slug: jenkins-pipeline
  name: Jenkins Pipeline
  description: Jenkins Pipeline is a suite of plugins for the Jenkins automation server that supports implementing and integrating continuous delivery pipelines as code. It provides an extensible domain-specific language (DSL) with two syntax styles - De…
  api_count: 0
  score_band: minimal
  score_composite: 9.7
  shared: 5
- slug: microsoft-azure-devops
  name: Azure DevOps
  description: Azure DevOps provides developer services for support teams to plan work, collaborate on code development, and build and deploy applications.
  api_count: 11
  score_band: exemplar
  score_composite: 76.3
  shared: 4
- slug: cloudbees
  name: CloudBees
  description: CloudBees provides software delivery automation across continuous integration, continuous deployment, release orchestration, and feature management. Their developer surface includes the CloudBees CI REST API (an extension of the Jenkins RE…
  api_count: 5
  score_band: exemplar
  score_composite: 72.8
  shared: 4
- slug: bitbucket
  name: Bitbucket
  description: Bitbucket is a Git-based source code repository hosting service owned by Atlassian offering both commercial plans and free accounts with unlimited private repositories, along with CI/CD pipelines, code reviews via pull requests, and code c…
  api_count: 1
  score_band: exemplar
  score_composite: 70.0
  shared: 4
- slug: red-hat-ansible-automation-platform
  name: Red Hat Ansible Automation Platform
  description: Red Hat Ansible Automation Platform is an enterprise automation solution that provides a framework for building and operating IT automation at scale. It includes the Automation Controller, Automation Hub, Event-Driven Ansible, and Ansible…
  api_count: 5
  score_band: strong
  score_composite: 66.0
  shared: 4
- slug: platform.sh
  name: Platform.sh
  description: Platform.sh is the container-based Platform-as-a-Service (PaaS) founded in 2010 and headquartered in Paris and San Francisco, best known for Git-driven deployments in which a single push plus a few YAML files provisions an entire cluster o…
  api_count: 3
  score_band: strong
  score_composite: 57.9
  shared: 4
- slug: lightrun
  name: Lightrun
  description: Lightrun is a developer-native observability and live-debugging platform. Language agents embedded in a running JVM, Python, Node.js or .NET process accept dynamic actions — logs, snapshots, counters, tic-toc timings and custom metrics — p…
  api_count: 1
  score_band: strong
  score_composite: 55.8
  shared: 4
- slug: amazon-proton
  name: Amazon Proton
  description: AWS Proton is a managed service for platform engineers that helps them publish standardized container and serverless application templates to empower developers. It provides automated infrastructure provisioning and manages deployment pipe…
  api_count: 1
  score_band: strong
  score_composite: 55.5
  shared: 4
- slug: kubeshop
  name: Kubeshop
  description: Kubeshop is the company behind Testkube, an open-core, Kubernetes-native test orchestration platform. Testkube runs agents inside Kubernetes clusters under a central control plane, orchestrating tests written for existing frameworks — Cypr…
  api_count: 3
  score_band: developing
  score_composite: 52.9
  shared: 4
- slug: google-cloud-build
  name: Google Cloud Build
  description: Google Cloud Build is a fully managed continuous integration and continuous delivery (CI/CD) platform that lets you build, test, and deploy software quickly across all languages and frameworks. It executes builds on Google Cloud infrastruc…
  api_count: 1
  score_band: developing
  score_composite: 48.9
  shared: 4
- slug: brownie
  name: IncidentFox (Brownie)
  description: IncidentFox (the company was surfaced in the API Evangelist network under its Y Combinator portfolio codename "Brownie") is an open-source, AI-powered SRE platform that automates production incident investigation and response. Its multi-ag…
  api_count: 1
  score_band: developing
  score_composite: 48.6
  shared: 4
- slug: ansible
  name: Ansible
  description: Ansible is an open-source IT automation platform developed by Red Hat that provides agentless configuration management, application deployment, cloud provisioning, and orchestration. Using YAML-based playbooks and an SSH-native architectur…
  api_count: 1
  score_band: developing
  score_composite: 47.8
  shared: 4
- slug: nevercode
  name: Nevercode
  description: Codemagic (built by Nevercode, founded in Estonia) is a continuous integration and delivery (CI/CD) platform purpose-built for mobile app teams. It automates building, testing, code signing, and releasing apps across Flutter, React Native,…
  api_count: 1
  score_band: developing
  score_composite: 47.4
  shared: 4
- slug: semaphore
  name: Semaphore
  description: Semaphore is a cloud-based CI/CD platform designed for high-performance engineering teams, providing fast and reliable continuous integration and continuous delivery pipelines. The platform offers a comprehensive REST API that enables prog…
  api_count: 1
  score_band: developing
  score_composite: 47.3
  shared: 4
- slug: ansible-playbooks
  name: Ansible Playbooks
  description: A curated collection of APIs, tools, and platforms for managing and executing Ansible playbooks for IT automation, configuration management, and orchestration. Covers the Ansible Automation Platform, AWX, Galaxy, Automation Hub, Runner, an…
  api_count: 1
  score_band: developing
  score_composite: 46.8
  shared: 4
- slug: teamcity
  name: TeamCity
  description: JetBrains TeamCity is a powerful continuous integration and deployment server that helps development teams build, test, and deploy software efficiently. TeamCity provides a comprehensive REST API for automating CI/CD workflows, managing pr…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 4
- slug: engflow
  name: EngFlow
  description: EngFlow provides remote build execution, remote caching, CI runners, and a Build & Test UI that accelerate large-scale software builds for Bazel, BuildStream, Goma, Pants, Soong, CMake, and Buck2. EngFlow clusters expose a gRPC / Protocol…
  api_count: 1
  score_band: developing
  score_composite: 43.3
  shared: 4
- slug: cycloid
  name: Cycloid
  description: Cycloid is a unified Internal Developer Portal & Platform combining self-service Service Catalogs (Stacks and StackForms), Infrastructure as Code orchestration, multi-cloud asset inventory (Asset Inventory and InfraView), CI/CD pipeline ce…
  api_count: 1
  score_band: developing
  score_composite: 42.9
  shared: 4
- slug: ansible-roles
  name: Ansible Roles
  description: A curated collection of APIs and resources for discovering, managing, and consuming Ansible roles — the primary unit of reusable automation content in the Ansible ecosystem. Covers the Galaxy and Automation Hub APIs for role discovery, dow…
  api_count: 1
  score_band: developing
  score_composite: 42.6
  shared: 4
- slug: launchable
  name: Launchable
  description: Launchable is a software development intelligence platform for continuous integration that applies machine learning to CI and test data to speed up software delivery. Its flagship capability, Predictive Test Selection, records builds, test…
  api_count: 1
  score_band: developing
  score_composite: 42.0
  shared: 4
- slug: devtron
  name: Devtron
  description: Devtron is an open-source, AI-native Kubernetes management and software delivery platform that unifies application, infrastructure, and cost management for engineering, DevOps, and SRE teams. It provides Kubernetes-native CI/CD, GitOps (Ar…
  api_count: 1
  score_band: developing
  score_composite: 40.4
  shared: 4
- slug: aws-codebuild
  name: AWS CodeBuild
  description: AWS CodeBuild is a fully managed continuous integration build service that compiles source code, runs unit tests, and produces deployable artifacts. It eliminates the need to provision, manage, and scale build servers by providing prepacka…
  api_count: 48
  score_band: developing
  score_composite: 39.7
  shared: 4
- slug: drone
  name: Drone
  description: Drone is an open-source, container-native continuous integration and continuous delivery platform that automates software build, testing, and deployment pipelines entirely through Docker containers. Acquired by Harness in 2021, Drone enabl…
  api_count: 1
  score_band: thin
  score_composite: 39.1
  shared: 4
- slug: jenkins
  name: Jenkins
  description: Jenkins is the leading open source automation server that enables developers to reliably build, test, and deploy software. Jenkins exposes a machine-consumable Remote Access API for nearly every resource it manages, available in XML (with…
  api_count: 4
  score_band: thin
  score_composite: 36.6
  shared: 4
- slug: loggly
  name: Loggly
  description: Loggly is a cloud-based log management and analytics service (part of SolarWinds) that aggregates, searches, and visualizes application, server, and infrastructure logs in real time. Developers ship logs over syslog or the HTTP/S event end…
  api_count: 2
  score_band: thin
  score_composite: 36.3
  shared: 4
---
