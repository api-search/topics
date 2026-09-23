---
layout: topic
slug: json-schema
name: JSON Schema
kind: topic
description: JSON Schema is a vocabulary for annotating and validating JSON documents, widely used for defining API request and response shapes across REST APIs. The current stable specification is Draft 2020-12. JSON Schema differentiates between the instance being validated and the schema document containing the validation rules, and supports URI-based references for recursive and cross-document definitions.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/json-schema.png
tags:
- API Design
- Specification Language
- JSON
- Validation
- Schema
repo: https://github.com/api-evangelist/json-schema
api_count: 1
apis:
- name: JSON Schema
  description: JSON Schema is a vocabulary for annotating and validating JSON documents, widely used for defining API request and response shapes across REST APIs. Current spec version is Draft 2020-12. Supports validation, code generation, API documenta…
  url: https://json-schema.org
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/json-schema/blob/main/security/json-schema-domain-security.yml
- type: Website
  url: https://json-schema.org
- type: Documentation
  url: https://json-schema.org/learn/getting-started-step-by-step
- type: Specification
  url: https://json-schema.org/draft/2020-12/release-notes
- type: GitHubOrganization
  url: https://github.com/json-schema-org
provider_count: 5
providers:
- slug: api-blueprint
  name: API Blueprint
  description: API Blueprint is a high-level API description language using Markdown-based syntax for designing, documenting, and prototyping web APIs. Created by Apiary and released under the MIT License, API Blueprint uses .apib files with a concise Ma…
  api_count: 1
  score_band: developing
  score_composite: 40.5
  shared: 2
- slug: typespec
  name: TypeSpec
  description: TypeSpec is an API description language developed by Microsoft for defining API shapes that compile to OpenAPI, JSON Schema, Protobuf, and other output formats. It provides a language and toolchain for describing REST APIs, gRPC services,…
  api_count: 6
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: raml
  name: RAML
  description: RAML (RESTful API Modeling Language) is a YAML-based specification language for describing RESTful APIs with first-class support for reusable patterns, traits, resource types, data type annotations, libraries, overlays, and extensions. Dev…
  api_count: 1
  score_band: emerging
  score_composite: 24.0
  shared: 2
- slug: specifications
  name: API Specifications
  description: Meta-index of the specification languages used to describe APIs, events, schemas, and service interfaces across the modern API landscape. This repo is the META layer above the topical repos that profile each individual specification — it c…
  api_count: 13
  score_band: emerging
  score_composite: 22.5
  shared: 2
- slug: connexion
  name: Connexion
  description: Connexion is an open source Python framework that automatically handles HTTP requests based on OpenAPI specifications. Connexion 3 provides AsyncApp, FlaskApp, and ConnexionMiddleware as primary entry points, with built-in routing, request…
  api_count: 2
  score_band: emerging
  score_composite: 17.2
  shared: 2
---
