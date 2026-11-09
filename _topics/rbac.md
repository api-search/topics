---
layout: topic
slug: rbac
name: RBAC
kind: concept
description: 'Role-Based Access Control (RBAC) is a security paradigm that restricts system access based on assigned roles rather than individual user identities. Users are granted permissions through role membership, simplifying access management and ensuring the principle of least privilege. RBAC is foundational to enterprise identity, authorization, and compliance programs and is implemented across operating systems, cloud platforms, databases, and APIs. The NIST/ANSI/INCITS 359-2004 standard formally defines the RBAC model across four components: Core RBAC, Hierarchical RBAC, Static Separation of Duty, and Dynamic Separation of Duty. Cloud platforms (AWS IAM, Azure RBAC, GCP IAM) and Kubernetes all implement RBAC natively, making it the de facto authorization standard for enterprise and cloud-native environments.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/rbac.png
tags:
- Access Control
- Authorization
- Cloud-Native
- Compliance
- Identity and Access Management
- Kubernetes
- RBAC
- Security
area: security
repo: https://github.com/api-evangelist/rbac
api_count: 0
apis: []
links:
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-schema/rbac-role.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-schema/rbac-permission.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-schema/rbac-assignment.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-structure/rbac-role-structure.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-structure/rbac-permission-structure.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-structure/rbac-assignment-structure.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/json-ld/rbac-context.jsonld
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/examples/rbac-role-example.json
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/examples/rbac-permission-example.json
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/examples/rbac-assignment-example.json
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/rbac/refs/heads/main/vocabulary/rbac-vocabulary.yml
- type: Standards
  url: https://csrc.nist.gov/projects/role-based-access-control
- type: Documentation
  url: https://kubernetes.io/docs/reference/access-authn-authz/rbac/
- type: Documentation
  url: https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies.html
provider_count: 386
providers:
- slug: c1
  name: C1
  description: C1 (ConductorOne) is an identity and access management platform engineered for the AI era. It provides unified access governance across human identities, AI agents, and services — agentic identity management, policy-driven access controls,…
  api_count: 1
  score_band: strong
  score_composite: 58.6
  shared: 4
- slug: amazon-iam-access-analyzer
  name: Amazon IAM Access Analyzer
  description: AWS IAM Access Analyzer helps you set, verify, and refine your IAM policies by providing a suite of capabilities including findings for external, internal, and unused access, basic and custom policy checks for validating policies, and poli…
  api_count: 1
  score_band: developing
  score_composite: 54.1
  shared: 4
- slug: adaptive-automation-technologies
  name: Adaptive Automation Technologies
  description: Adaptive Automation Technologies, Inc. — trading as Adaptive (adaptive.live) — builds a privileged access management and data security platform that brokers credential-less, fully audited access to databases, Kubernetes clusters, virtual m…
  api_count: 2
  score_band: developing
  score_composite: 52.8
  shared: 4
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 42.6
  shared: 4
- slug: oso
  name: Oso Cloud
  description: Oso Cloud is an authorization-as-a-service platform that provides a REST API for defining and enforcing relationship-based access control policies. It enables developers to model RBAC, ReBAC, and ABAC authorization patterns, manage authori…
  api_count: 1
  score_band: thin
  score_composite: 35.7
  shared: 4
- slug: infra
  name: Infra
  description: Infra is open-source authentication and access management for infrastructure. It grants short-lived, identity-based access to Kubernetes clusters, servers, and databases by connecting an organization's OIDC identity providers (Okta, Google…
  api_count: 1
  score_band: thin
  score_composite: 32.5
  shared: 4
- slug: zero-trust-architecture
  name: Zero Trust Architecture
  description: Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that requires all users and devices to be authenticated, authorized, and continuously validated before being granted access to applications and data, regardle…
  api_count: 5
  score_band: emerging
  score_composite: 23.1
  shared: 4
- slug: aceiss
  name: Aceiss
  description: Aceiss is a security monitoring and access-visibility platform that gives CISOs and risk managers continuous insight into who has access to their GitHub organizations and repositories. It monitors user access across repositories, detects u…
  api_count: 0
  score_band: emerging
  score_composite: 14.8
  shared: 4
- slug: aserto
  name: Aserto
  description: Aserto is a cloud-native authorization platform providing fine-grained, policy-based access control for applications and APIs. Built on Open Policy Agent (OPA) and a Google Zanzibar-inspired directory, Aserto exposes REST and gRPC APIs for…
  api_count: 3
  score_band: minimal
  score_composite: 0
  shared: 4
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 75.9
  shared: 3
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 8
  score_band: exemplar
  score_composite: 72.2
  shared: 3
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 4
  score_band: exemplar
  score_composite: 72.1
  shared: 3
- slug: altr
  name: ALTR
  description: ALTR is a unified data security platform that discovers, classifies, masks, tokenizes and monitors sensitive data across Snowflake, Databricks and OLTP databases (PostgreSQL, MySQL, SQL Server, Oracle, MongoDB). The platform combines autom…
  api_count: 21
  score_band: strong
  score_composite: 62.1
  shared: 3
- slug: frontegg
  name: Frontegg
  description: Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS. It provides self-serve authentication, multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that…
  api_count: 11
  score_band: strong
  score_composite: 59.2
  shared: 3
- slug: amazon-iam
  name: Amazon IAM
  description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their acces…
  api_count: 1
  score_band: strong
  score_composite: 59.0
  shared: 3
- slug: clawvisor
  name: Clawvisor
  description: Clawvisor is the authorization layer for AI agents — a Y Combinator (Spring 2026) security gateway that sits between an AI agent and the tools it acts on (Gmail, Calendar, Drive, Contacts, GitHub, Slack, Notion, Linear, Stripe, Twilio, iMe…
  api_count: 1
  score_band: strong
  score_composite: 55.7
  shared: 3
- slug: sailpoint
  name: SailPoint
  description: Enterprise identity security and governance platform providing identity management, access governance, and compliance solutions for workforce and non-employee identities. SailPoint delivers cloud-native IAM, certification automation, role…
  api_count: 1
  score_band: strong
  score_composite: 54.6
  shared: 3
- slug: indykite
  name: Indykite
  description: IndyKite is the runtime control layer for agentic AI. Its enterprise platform applies trust, context, and runtime control across organizational data so autonomous AI agents can act securely, continuously injecting live signals — identity,…
  api_count: 2
  score_band: strong
  score_composite: 54.3
  shared: 3
- slug: border0
  name: Border0
  description: Border0 is an identity-aware Zero Trust network access platform for securing access to infrastructure — SSH and RDP servers, PostgreSQL/MySQL/MSSQL/MongoDB/Elasticsearch databases, Kubernetes clusters, AWS consoles and S3 buckets, and any…
  api_count: 1
  score_band: developing
  score_composite: 50.7
  shared: 3
- slug: strongdm
  name: StrongDM
  description: StrongDM is a Zero Trust Privileged Access Management (PAM) platform that brokers and governs access to infrastructure — databases, servers, Kubernetes clusters, cloud resources, network devices, and internal web apps — through a central c…
  api_count: 2
  score_band: developing
  score_composite: 50.0
  shared: 3
- slug: cerbos
  name: Cerbos
  description: Cerbos is an open-core, language-agnostic, scalable authorization platform that decouples access control from application code by externalizing fine-grained, context-aware permission decisions into policy-as-code. Authorization is expresse…
  api_count: 1
  score_band: developing
  score_composite: 49.9
  shared: 3
- slug: sysdig
  name: Sysdig
  description: Sysdig is a cloud and container security platform that provides runtime threat detection, vulnerability management, cloud security posture management (CSPM), compliance automation, and observability for containers, Kubernetes, and cloud en…
  api_count: 2
  score_band: developing
  score_composite: 47.9
  shared: 3
- slug: authzed
  name: Authzed
  description: Authzed is a SpiceDB-based authorization platform providing REST and gRPC APIs for Zanzibar-style relationship-based access control. It enables developers to manage schemas, write relationship tuples, and execute fine-grained permission ch…
  api_count: 1
  score_band: developing
  score_composite: 46.6
  shared: 3
- slug: permit-io
  name: Permit.io
  description: Permit.io is an authorization-as-a-service platform that helps developers build, manage, and enforce fine-grained access control in their applications. It provides a Policy Decision Point (PDP), management API, REST API, and permission que…
  api_count: 1
  score_band: developing
  score_composite: 46.6
  shared: 3
- slug: spideroak
  name: SpiderOak
  description: SpiderOak (SpiderOak, Inc. / SpiderOak Mission Systems) builds zero-trust access governance and secure data exchange software for defense, aerospace and commercial operators working in contested, disconnected, degraded, intermittent and lo…
  api_count: 1
  score_band: developing
  score_composite: 44.8
  shared: 3
- slug: p0-security
  name: P0 Security
  description: P0 Security is a cloud-native Privileged Access Management (PAM) platform that governs runtime authorization for human users, machine/service accounts, and AI agents across hybrid and multi-cloud environments. Its AuthZ Control Plane enfor…
  api_count: 1
  score_band: developing
  score_composite: 44.2
  shared: 3
- slug: isovalent
  name: Isovalent
  description: Isovalent is the company founded in 2017 by the creators of Cilium, the eBPF-based networking, security, and observability platform for Kubernetes and cloud-native infrastructure. Isovalent builds and maintains the open source Cilium proje…
  api_count: 2
  score_band: developing
  score_composite: 42.8
  shared: 3
- slug: cilium
  name: Cilium
  description: Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary kernel technology eBPF. Cilium provides network security, load balancing, and observ…
  api_count: 1
  score_band: developing
  score_composite: 42.6
  shared: 3
- slug: soveren
  name: Soveren
  description: Soveren is a unified Data Security Posture Management (DSPM) and Data Detection and Response (DDR) platform that delivers real-time data observability for Kubernetes and cloud environments. It combines at-rest data detection with eBPF-base…
  api_count: 1
  score_band: developing
  score_composite: 42.5
  shared: 3
- slug: cakewalk
  name: Cakewalk
  description: Cakewalk is the agentic access management platform for fast-moving companies, combining a granular identity governance and administration (IGA) platform with AI-driven workflows. Cakewalk governs access for both human identities and AI age…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 3
---
