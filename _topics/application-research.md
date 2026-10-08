---
layout: topic
slug: application-research
name: Application Research
kind: topic
description: 'Application Research is a topic collection focused on specifications for declaring application service integration dependencies. It covers five specification formats: Score (platform-agnostic workload specs), Cloud Native Application Bundle (CNAB), Open Component Model (OCM), Open Resource Discovery (ORD), and Radius — all aimed at enabling deployment teams to understand what services (APIs, databases, caches, message buses, blob stores) an application requires.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/application-research.png
tags:
- Application Dependencies
- Cloud-Native
- Integration
- Research
- Specification
- Workload Specifications
repo: https://github.com/api-evangelist/application-research
api_count: 36
apis:
- name: Application Research API Resources API
  description: API Resource operations
  url: https://score.dev
- name: Application Research Applications API
  description: Application resource operations
  url: https://score.dev
- name: Application Research Bundles API
  description: Operations for managing CNAB bundle descriptors
  url: https://score.dev
- name: Application Research Capabilities API
  description: Capability operations
  url: https://score.dev
- name: Application Research Claim Results API
  description: Operations for managing claim execution results
  url: https://score.dev
- name: Application Research Claims API
  description: Operations for managing installation claims
  url: https://score.dev
- name: Application Research Components API
  description: Operations for managing component descriptors
  url: https://score.dev
- name: Application Research Configurations API
  description: Operations for managing component configurations
  url: https://score.dev
- name: Application Research Consumption Bundles API
  description: Consumption Bundle operations
  url: https://score.dev
- name: Application Research Containers API
  description: Container resource operations
  url: https://score.dev
- name: Application Research Credentials API
  description: Credential management operations
  url: https://score.dev
- name: Application Research Dapr API
  description: Dapr component operations
  url: https://score.dev
- name: Application Research Data Products API
  description: Data Product operations
  url: https://score.dev
- name: Application Research Datastores API
  description: Datastore portable resource operations
  url: https://score.dev
- name: Application Research Entity Types API
  description: Entity Type operations
  url: https://score.dev
- name: Application Research Environments API
  description: Environment resource operations
  url: https://score.dev
- name: Application Research Event Resources API
  description: Event Resource operations
  url: https://score.dev
- name: Application Research Extenders API
  description: Extender portable resource operations
  url: https://score.dev
- name: Application Research Gateways API
  description: Gateway resource operations
  url: https://score.dev
- name: Application Research Groups API
  description: Group and Group Type operations
  url: https://score.dev
- name: Application Research Integration Dependencies API
  description: Integration Dependency operations
  url: https://score.dev
- name: Application Research Messaging API
  description: Messaging portable resource operations
  url: https://score.dev
- name: Application Research ORD Documents API
  description: Operations for ORD Document management
  url: https://score.dev
- name: Application Research Packages API
  description: Package management operations
  url: https://score.dev
- name: Application Research Planes API
  description: Plane management operations
  url: https://score.dev
- name: Application Research Products API
  description: Product operations
  url: https://score.dev
- name: Application Research Resources API
  description: Operations for managing component resources
  url: https://score.dev
- name: Application Research SecretStores API
  description: Secret store operations
  url: https://score.dev
- name: Application Research Signatures API
  description: Operations for component signing and verification
  url: https://score.dev
- name: Application Research Sources API
  description: Operations for managing component sources
  url: https://score.dev
- name: Application Research Status API
  description: Operations for querying installation status
  url: https://score.dev
- name: Application Research Validation API
  description: Workload validation operations
  url: https://score.dev
- name: Application Research Vendors API
  description: Vendor operations
  url: https://score.dev
- name: Application Research Volumes API
  description: Volume resource operations
  url: https://score.dev
- name: Application Research Workloads API
  description: Score workload management operations
  url: https://score.dev
- name: Application Research Resource Groups API
  description: Resource group operations
  url: https://score.dev
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/application-research/blob/main/capabilities/application-research-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/application-research/blob/main/agentic-access/application-research-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/application-research/blob/main/security/application-research-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/application-research/blob/main/authentication/application-research-authentication.yml
- type: OAuthScopes
  url: https://github.com/api-evangelist/application-research/blob/main/scopes/application-research-scopes.yml
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: JSONLD
  url: https://github.com/api-evangelist/application-research/blob/main/json-ld/application-research-context.jsonld
- type: SpectralRules
  url: https://github.com/api-evangelist/application-research/blob/main/rules/application-research-spectral-rules.yml
- type: Vocabulary
  url: https://github.com/api-evangelist/application-research/blob/main/vocabulary/application-research-vocabulary.yaml
provider_count: 2
providers:
- slug: cloudevents
  name: CloudEvents
  description: CloudEvents is a CNCF graduated specification for describing event data in a common way. It provides a consistent format for event metadata across services, platforms, and systems, enabling interoperability between event producers and cons…
  api_count: 1
  score_band: thin
  score_composite: 37.6
  shared: 2
- slug: openfeature
  name: OpenFeature
  description: OpenFeature is a CNCF incubating open specification for feature flag management. It provides a vendor-agnostic API for evaluating feature flags, enabling developers to use a consistent interface regardless of the underlying feature flag pr…
  api_count: 1
  score_band: thin
  score_composite: 28.0
  shared: 2
---
