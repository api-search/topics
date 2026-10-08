---
layout: topic
slug: test-first
name: Test First
kind: topic
description: A software development approach where tests are written before the implementation code, ensuring code quality and driving design decisions through test requirements. Test-first development is the foundational principle behind test-driven development (TDD) and behavior-driven development (BDD), where the specification of expected behavior is captured in executable tests before any production code is written.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/test-first.png
tags:
- Behavior-Driven Development
- Best Practices
- Methodology
- Software Design
- Software Development
- Testing
repo: https://github.com/api-evangelist/test-first
api_count: 5
apis:
- name: Cucumber API
  description: REST API and tooling for Cucumber BDD framework supporting test-first development with Gherkin feature files, scenario definitions, and step implementations.
  url: https://cucumber.io
- name: Pact Broker API
  description: REST API for Pact Broker contract testing service, enabling consumer-driven contract testing where consumer tests define the API contract before providers implement it.
  url: https://docs.pact.io
- name: Stoplight API
  description: API design-first platform enabling teams to write API specifications before implementation, supporting test-first development with mock servers, contract testing, and API style guides.
  url: https://stoplight.io
- name: Microcks API
  description: Open-source cloud-native tool for API mocking and contract testing, supporting test-first development by generating mocks from OpenAPI, Postman, and gRPC specifications.
  url: https://microcks.io
- name: Dredd API
  description: Command-line HTTP API testing framework that validates API implementations against API Blueprint or OpenAPI descriptions, enabling test-first API development.
  url: https://dredd.org
links:
- type: IssueTracker
  url: https://github.com/cucumber/cucumber-js/issues
- type: Releases
  url: https://github.com/cucumber/cucumber-js/releases
- type: CodeOfConduct
  url: https://github.com/cucumber/.github/blob/main/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/cucumber/cucumber-js/blob/main/CONTRIBUTING.md
- type: License
  url: https://github.com/cucumber/cucumber-js/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/test-first/blob/main/security/test-first-domain-security.yml
- type: Documentation
  url: https://en.wikipedia.org/wiki/Test-driven_development
- type: Documentation
  url: https://www.agilealliance.org/glossary/tdd/
- type: JSONSchema
  url: https://github.com/api-evangelist/test-first/blob/main/json-schema/test-first-specification-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-first/blob/main/json-schema/test-first-contract-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/test-first/blob/main/json-schema/test-first-mock-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/test-first/blob/main/json-ld/test-first-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/test-first/blob/main/vocabulary/test-first-vocabulary.yml
provider_count: 6
providers:
- slug: cucumber
  name: Cucumber
  description: Cucumber is an open-source Behavior Driven Development (BDD) tool for running automated tests written in plain language using the Gherkin syntax. It enables collaboration between technical and non-technical team members by expressing execu…
  api_count: 5
  score_band: thin
  score_composite: 28.2
  shared: 2
- slug: approxima
  name: Approxima
  description: 'Approxima is a Y Combinator (Winter 2026) startup building AI agents that test every pull request. Approxima plugs into your CI/CD pipeline and runs autonomous agents on each PR: the agents build your application in an isolated sandbox, ex…'
  api_count: 0
  score_band: minimal
  score_composite: 10.1
  shared: 2
- slug: secure-by-design
  name: Secure-By-Design
  description: A software development approach that prioritizes security from the initial design phase through implementation, ensuring security considerations are built into the foundation of systems rather than added as an afterthought. It is widely ad…
  api_count: 0
  score_band: minimal
  score_composite: 3.0
  shared: 2
- slug: secure-by-default
  name: Secure-By-Default
  description: A security design principle where systems and software are configured with the most secure settings from the initial deployment, requiring users to explicitly opt-in to less secure options rather than having to manually enable security fea…
  api_count: 0
  score_band: minimal
  score_composite: 2.7
  shared: 2
- slug: security-by-design
  name: Security by Design
  description: A software development approach that integrates security considerations and practices from the initial design phase through the entire development lifecycle, rather than adding security as an afterthought. It plays a critical role in prote…
  api_count: 0
  score_band: minimal
  score_composite: 1.8
  shared: 2
- slug: methodology
  name: Methodology
  description: Methodology is a concept entry covering systematic approaches and processes used in technology, software development, and computing to address specific technical challenges and improve outcomes.
  api_count: 0
  score_band: minimal
  score_composite: 0.7
  shared: 2
---
