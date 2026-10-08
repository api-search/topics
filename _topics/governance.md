---
layout: topic
slug: governance
name: API Governance
kind: topic
description: API Governance is the practice of defining and enforcing the policies, standards, and processes that guide how APIs are designed, built, secured, versioned, and retired across an organization. This topic indexes the providers, tools, and open-source linters that operationalize spec governance, design governance, security governance, and lifecycle governance for the API estate.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/governance.png
tags:
- Governance
- Policies
- Rules
- Spectral
- Linting
- Lifecycle
- Compliance
- Standards
- OpenAPI
- AsyncAPI
repo: https://github.com/api-evangelist/governance
api_count: 16
apis:
- name: Apiwiz API Governance
  description: Federated API management platform with automated linting, build templates, policy enforcement, and multi-gateway governance for the full API lifecycle.
  url: https://www.apiwiz.io/
- name: Treblle API Intelligence and Governance
  description: API observability and governance platform that scores, monitors, and audits production APIs in real time, surfacing design and security issues against OpenAPI specifications.
  url: https://treblle.com/
- name: 42Crunch API Security Platform
  description: Security-first API governance platform that audits OpenAPI contracts, runs 300+ conformance and security checks, performs automated fuzzing, and enforces policies from design through runtime.
  url: https://42crunch.com/
- name: APIContext (formerly Apimetrics)
  description: API monitoring and governance service measuring availability, performance, and conformance of production APIs from distributed locations for SLA and regulatory reporting.
  url: https://apicontext.com/
- name: Postman API Governance
  description: Governance product inside the Postman API platform combining a pre-built rule library, custom Spectral-compatible rules, CLI/CI enforcement, and a reporting dashboard for the API estate.
  url: https://www.postman.com/api-platform/api-governance/
- name: Stoplight Spaces and Style Guides
  description: API design platform with built-in style guides, custom Spectral rulesets, and workspace-level governance, now offered as part of SmartBear's API Hub.
  url: https://stoplight.io/api-governance
- name: Spectral
  description: Open-source JSON/YAML linter and style-guide enforcer for OpenAPI, AsyncAPI, and JSON Schema — the de facto standard rule engine behind most API governance products.
  url: https://stoplight.io/open-source/spectral
- name: Vacuum
  description: Open-source, Go-based OpenAPI linter that is 100% compatible with Spectral rulesets, supports OpenAPI 2 through 3.2, ships custom Go and JavaScript functions, and adds auto-fix and change-detection.
  url: https://quobix.com/vacuum/
- name: Redocly Reunite
  description: Redocly's collaborative governance and documentation workspace with Git-backed previews, audit trails, and review workflows that wrap Redocly's OpenAPI linting and bundling toolchain.
  url: https://redocly.com/reunite
- name: Optic
  description: Open-source and hosted tool that captures real API traffic, diffs it against the OpenAPI contract, and turns every change into a reviewable pull request with breaking-change detection.
  url: https://www.useoptic.com/
- name: Speakeasy Linter
  description: OpenAPI linter shipped with the Speakeasy SDK generation platform offering 90+ rules across six categories — SDK generation, spec correctness, best practices, security, schema validation, and Speakeasy-specific checks.
  url: https://www.speakeasy.com/docs/linting
- name: Apicurio Registry
  description: Open-source runtime registry that stores OpenAPI, AsyncAPI, GraphQL, Avro, Protobuf, JSON Schema, WSDL, and XSD artifacts and enforces validity, compatibility, and integrity rules across their lifecycle.
  url: https://www.apicur.io/registry/
- name: RepreZen API Studio
  description: Historical commercial OpenAPI/RAPID-ML modeling IDE that drove contract-first API governance; the product line has been retired and the domain reprezen.com is no longer maintained.
  url: https://github.com/RepreZen
- name: Bump.sh
  description: API documentation hub for OpenAPI and AsyncAPI with automatic changelog generation, breaking-change detection, and contract-level policy enforcement that feeds into governance workflows.
  url: https://bump.sh/
- name: API Governance Program
  description: Rules, vocabulary, JSON Schema, JSON-LD, and example records for an organizational API governance program covering spec, design, security, and lifecycle governance across the API estate.
- name: Sensedia SMART API Governance
  description: AI-powered federated governance platform delivering centralized visibility, contract validation, shadow API detection, and lifecycle policy enforcement across multi-cloud and multi-gateway estates.
  url: https://www.sensedia.com/
links:
- type: IssueTracker
  url: https://github.com/stoplightio/spectral/issues
- type: Releases
  url: https://github.com/stoplightio/spectral/releases
- type: CodeOfConduct
  url: https://github.com/stoplightio/spectral/blob/develop/.github/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/stoplightio/spectral/blob/develop/CONTRIBUTING.md
- type: License
  url: https://github.com/stoplightio/spectral/blob/develop/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/governance/blob/main/security/governance-domain-security.yml
- type: Reference
  url: https://stoplight.io/open-source/spectral
- type: Reference
  url: https://github.com/daveshanley/vacuum
- type: Reference
  url: https://www.postman.com/api-platform/api-governance/
- type: Reference
  url: https://owasp.org/www-project-api-security/
- type: Reference
  url: https://developer.apievangelist.com/feeds/policies/
- type: Reference
  url: https://developer.apievangelist.com/feeds/rules/
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: DeveloperPortal
  url: https://developer.apievangelist.com/
provider_count: 75
providers:
- slug: redocly
  name: Redocly
  description: Redocly is a company that specializes in API documentation and governance tooling. Their platform helps organizations create, manage, and publish API documentation through Realm (the integrated lifecycle platform that unifies Redoc, Revel,…
  api_count: 4
  score_band: exemplar
  score_composite: 82.6
  shared: 3
- slug: stoplight
  name: Stoplight
  description: Stoplight is a collaborative, design-first API platform providing a visual editor for OpenAPI specifications, interactive hosted documentation, automatic mock servers, API style guides and governance, and open-source tools including Prism…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 3
- slug: vacuum
  name: Vacuum
  description: Vacuum is the world's fastest and most versatile OpenAPI linter and toolkit, built in Go for validating and linting API specifications at scale. It is 100% compatible with Spectral rulesets and supports OpenAPI 3.0, 3.1, and 3.2.
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: spotlight-rules
  name: Spotlight Rules
  description: Spotlight Rules is an openly-governed build of the Spectral API linter and, more importantly, the first attempt to publish the Spectral ruleset format as a standalone specification with its own portable JSON Schema — so that an organizatio…
  api_count: 0
  score_band: emerging
  score_composite: 18.4
  shared: 3
- slug: postman
  name: Postman
  description: Postman is the world's leading API platform, used by 35+ million developers to design, build, test, document, mock, monitor, and govern APIs across the entire API lifecycle. The platform spans Collections, Workspaces, the API Client, Spec…
  api_count: 21
  score_band: exemplar
  score_composite: 79.6
  shared: 2
- slug: anecdotes
  name: anecdotes
  description: anecdotes is an enterprise Governance, Risk and Compliance (GRC) platform, founded in 2020 and headquartered in Tel Aviv, that pairs a GRC data engine with AI agents to replace point-in-time audit cycles with continuous, evidence-backed co…
  api_count: 3
  score_band: strong
  score_composite: 64.0
  shared: 2
- slug: eclipse
  name: Eclipse Foundation
  description: The Eclipse Foundation is a non-profit (Belgian AISBL) that provides a global community of individuals and organizations with a mature, scalable and business-friendly environment for open source software collaboration and innovation. It is…
  api_count: 19
  score_band: strong
  score_composite: 63.6
  shared: 2
- slug: bump-sh
  name: Bump.sh
  description: Bump.sh is "the modern API doc platform" — automatic, diff-aware documentation for OpenAPI and AsyncAPI specifications, plus a managed Model Context Protocol (MCP) platform that compiles Flower or Arazzo workflow documents into determinist…
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: netcracker
  name: Netcracker
  description: Netcracker Technology is a Waltham, Massachusetts-based BSS/OSS and digital business software vendor and a wholly owned subsidiary of NEC Corporation. It sells cloud BSS, digital commerce and monetization, convergent charging, service and…
  api_count: 4
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: amazon-config
  name: Amazon Config
  description: AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past, enabling assessment, auditing, and evaluati…
  api_count: 1
  score_band: strong
  score_composite: 56.7
  shared: 2
- slug: amazon-cloudtrail
  name: Amazon CloudTrail
  description: AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account by tracking user activity and API usage across AWS environments, hybrid setups, and multicloud deployments with immutable audit trai…
  api_count: 1
  score_band: strong
  score_composite: 54.4
  shared: 2
- slug: amazon-organizations
  name: Amazon Organizations
  description: AWS Organizations is an account management service that enables you to consolidate multiple AWS accounts into an organization that you create and centrally manage.
  api_count: 1
  score_band: developing
  score_composite: 54.2
  shared: 2
- slug: sweep
  name: Sweep
  description: Sweep is the agentic layer for enterprise systems. By connecting to platforms like Salesforce, Snowflake, ServiceNow, and HubSpot, Sweep reads live metadata and gives AI agents the context they need to understand, plan, and govern changes…
  api_count: 2
  score_band: developing
  score_composite: 52.2
  shared: 2
- slug: etsi
  name: ETSI
  description: ETSI, the European Telecommunications Standards Institute, is a not-for-profit standards development organisation headquartered in Sophia Antipolis, France, and one of only three bodies officially recognised by the European Union as a Euro…
  api_count: 24
  score_band: developing
  score_composite: 50.2
  shared: 2
- slug: torii
  name: Torii
  description: Torii is the market leading SaaS Management Platform built to bring all your software into one place. Discover shadow IT, enforce governance, cut costs, and operationalize every app. Torii integrates with 180+ SaaS applications to provide…
  api_count: 1
  score_band: developing
  score_composite: 49.9
  shared: 2
- slug: vanta
  name: Vanta
  description: Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate…
  api_count: 2
  score_band: developing
  score_composite: 48.8
  shared: 2
- slug: openpages
  name: OpenPages
  description: IBM OpenPages is an AI-driven, unified governance, risk, and compliance (GRC) platform delivered as a managed service on IBM Cloud. Originally founded as OpenPages Inc. (a Matrix Partners portfolio company) and acquired by IBM in 2010, it…
  api_count: 1
  score_band: developing
  score_composite: 47.7
  shared: 2
- slug: wegalvanize
  name: Wegalvanize
  description: Wegalvanize.com is the former web home of Galvanize, the governance, risk, and compliance (GRC) software company behind the HighBond platform; Galvanize was acquired by Diligent and wegalvanize.com now redirects to diligent.com. The HighBo…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 2
- slug: amazon-control-tower
  name: Amazon Control Tower
  description: AWS Control Tower provides the easiest way to set up and govern a secure, multi-account AWS environment based on best practices. It establishes a landing zone with pre-configured governance and guardrails, enabling organizations to maintai…
  api_count: 4
  score_band: developing
  score_composite: 46.1
  shared: 2
- slug: 3gpp
  name: 3GPP
  description: 3GPP (the 3rd Generation Partnership Project) is the global standards partnership that writes the technical specifications for mobile networks — GSM, UMTS, LTE, 5G and the ongoing 6G work — through seven regional Organizational Partners (A…
  api_count: 116
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: google-cloud-assured-workloads
  name: Google Cloud Assured Workloads
  description: Google Cloud Assured Workloads enables organizations to create and manage compliance-controlled environments on Google Cloud. It provides guardrails for regulatory compliance frameworks such as FedRAMP, HIPAA, CJIS, ITAR, and others by enf…
  api_count: 1
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: goethena
  name: Goethena
  description: Ethena (goethena.com) is an AI-powered compliance training and ethics platform used by 2,000+ organizations to run harassment prevention, code of conduct, data privacy, anti-bribery, and regulatory compliance programs across their workforc…
  api_count: 1
  score_band: developing
  score_composite: 45.3
  shared: 2
- slug: microsoft-azure-policy
  name: Azure Policy
  description: Azure Policy is a service that enables you to create, assign, and manage policies that enforce rules and effects over your Azure resources. It helps with compliance, governance, and consistency by evaluating resources against business stan…
  api_count: 2
  score_band: developing
  score_composite: 42.4
  shared: 2
- slug: montycloud
  name: MontyCloud
  description: MontyCloud is a Bellevue, Washington software company whose DAY2 platform is a no-code, autonomous CloudOps product for AWS-focused managed service providers and enterprise cloud teams. DAY2 connects to customer AWS (and Azure) accounts th…
  api_count: 2
  score_band: developing
  score_composite: 39.7
  shared: 2
- slug: nudge-security
  name: Nudge Security
  description: Nudge Security is a SaaS and AI security management platform that discovers all SaaS and cloud applications used across an organization, helps security teams manage OAuth grants, enforce security policies, monitor app-to-app integrations,…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 2
- slug: kion
  name: Kion
  description: Kion is a cloud operations platform that provides automated governance and FinOps capabilities across AWS, Azure, GCP, and OCI through a self-hosted deployment model. The platform consolidates multiple point solutions into a comprehensive…
  api_count: 1
  score_band: thin
  score_composite: 38.2
  shared: 2
- slug: open-policy-agent
  name: Open Policy Agent
  description: Open Policy Agent (OPA) is an open-source project that provides a flexible and powerful policy engine for cloud-native environments. OPA enables users to define and enforce policies across their infrastructure, applications, and services t…
  api_count: 7
  score_band: thin
  score_composite: 37.7
  shared: 2
- slug: netwrix
  name: Netwrix
  description: Netwrix provides data security and governance solutions that help organizations protect, monitor, and manage their critical information assets. Their platform offers visibility into data usage, detects risky behavior, and ensures complianc…
  api_count: 4
  score_band: thin
  score_composite: 35.8
  shared: 2
- slug: ketryx
  name: Ketryx
  description: Ketryx is an AI-native application lifecycle management (ALM) and compliance platform for regulated medical-device and life-sciences software teams. It integrates with developer tools such as Jira and GitHub to automate the documentation,…
  api_count: 1
  score_band: thin
  score_composite: 33.7
  shared: 2
- slug: apicurio
  name: Apicurio
  description: Apicurio is an open source API and schema tooling platform maintained by Red Hat under the Apache 2.0 license. It includes Apicurio Registry (a high-performance schema and API design registry), Apicurio Studio (a visual API designer for Op…
  api_count: 1
  score_band: thin
  score_composite: 32.3
  shared: 2
---
