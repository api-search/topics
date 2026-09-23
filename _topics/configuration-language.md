---
layout: topic
slug: configuration-language
name: Configuration Language
kind: topic
description: Configuration languages are formats and DSLs used to express the desired state of software systems, infrastructure, applications, and APIs. Configuration languages span a spectrum from simple text-based formats (INI, JSON, YAML, TOML) to typed and templated formats (HCL, Cue, Dhall, Pkl, Jsonnet, KDL) that support imports, schemas, and validation. The choice of configuration language shapes how teams describe Kubernetes manifests, Terraform infrastructure, OpenAPI specs, CI pipelines, and developer environments.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/configuration-language.png
tags:
- Configuration
- DSL
- Infrastructure as Code
- Schema
- Serialization
- Templating
- YAML
repo: https://github.com/api-evangelist/configuration-language
api_count: 9
apis:
- name: YAML
  description: YAML Ain't Markup Language is a human-friendly data serialization language. YAML 1.2 is widely used for configuration in Kubernetes, OpenAPI, GitHub Actions, Ansible, and many other ecosystems. YAML supports comments, scalars, sequences, m…
  url: https://yaml.org/
- name: JSON
  description: JavaScript Object Notation is a lightweight data interchange format defined by RFC 8259 and ECMA-404. JSON is heavily used as a configuration format in Node.js (package.json), VS Code settings, and many other tools, and is the foundation f…
  url: https://www.json.org/
- name: TOML
  description: Tom's Obvious, Minimal Language is a config file format designed to be human-readable and unambiguous. TOML is used by Cargo for Rust projects, Python packaging via pyproject.toml, and Hugo site config.
  url: https://toml.io/
- name: HCL
  description: HashiCorp Configuration Language is a structured configuration language designed for human authoring of complex configurations. HCL underpins Terraform, Packer, Vault, Consul, and Nomad and supports expressions, variables, functions, and b…
  url: https://github.com/hashicorp/hcl
- name: Cue
  description: Cue is an open source data validation language with a powerful type system and unification semantics. Cue is used to validate, generate, and transform configuration for Kubernetes, OpenAPI, and Terraform.
  url: https://cuelang.org/
- name: Dhall
  description: Dhall is a programmable configuration language that adds types and functions to JSON and YAML. Dhall expressions are total (always terminate) and remote imports are content-addressed for safety.
  url: https://dhall-lang.org/
- name: Pkl
  description: Pkl is Apple's open source configuration language with a focus on type safety, composition, and runtime templating. Pkl can render to YAML, JSON, plist, and other formats and offers IDE tooling and language bindings.
  url: https://pkl-lang.org/
- name: Jsonnet
  description: Jsonnet is a data templating language designed for elegant generation of JSON and YAML. It is used heavily for Kubernetes manifests, Grafana dashboards (Grafonnet), and Bazel-based tooling.
  url: https://jsonnet.org/
- name: KDL
  description: KDL is a node-oriented document language combining the readability of YAML and TOML with a unique tree-shaped grammar. KDL is used by Zellij, Helix, and other tools.
  url: https://kdl.dev/
links:
- type: IssueTracker
  url: https://github.com/toml-lang/toml/issues
- type: Releases
  url: https://github.com/toml-lang/toml/releases
- type: License
  url: https://github.com/toml-lang/toml/blob/main/LICENSE
- type: DomainSecurity
  url: https://github.com/api-evangelist/configuration-language/blob/main/security/configuration-language-domain-security.yml
- type: Reference
  url: https://en.wikipedia.org/wiki/Configuration_file
- type: Reference
  url: https://docs.kernel.org/admin-guide/configuration.html
- type: Resources
  url: https://github.com/avelino/awesome-go#configuration
- type: Reference
  url: https://json-schema.org/
provider_count: 4
providers:
- slug: cribl
  name: Cribl
  description: Cribl is an observability pipeline company providing a suite of products for collecting, processing, routing, searching, and storing telemetry data at scale. Cribl's developer platform offers REST APIs across Stream, Edge, Search, Lake, an…
  api_count: 6
  score_band: developing
  score_composite: 53.0
  shared: 2
- slug: carvel
  name: Carvel
  description: Carvel is a set of reliable, single-purpose, composable command-line tools that help build, configure, and deploy applications to Kubernetes. The toolset includes ytt for YAML templating, kapp for application lifecycle management, kbld for…
  api_count: 7
  score_band: thin
  score_composite: 38.3
  shared: 2
- slug: capn-proto
  name: Cap'n Proto
  description: Cap'n Proto is an open-source binary data interchange format and capability-based RPC protocol specification originally created by Kenton Varda. Unlike Protocol Buffers, Cap'n Proto's in-memory representation is identical to its wire forma…
  api_count: 5
  score_band: emerging
  score_composite: 15.8
  shared: 2
- slug: kustomize
  name: Kustomize
  description: Kustomize is a Kubernetes-native configuration management tool that lets you customize untemplated YAML files for multiple purposes, leaving the original YAML intact and usable as-is, using a template-free approach to configuration customi…
  api_count: 1
  score_band: emerging
  score_composite: 14.7
  shared: 2
---
