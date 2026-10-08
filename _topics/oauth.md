---
layout: topic
slug: oauth
name: OAuth
kind: topic
description: OAuth is an open authorization framework that enables third-party applications to access user resources without exposing credentials. It provides a secure, token-based delegation mechanism widely used across the web for granting limited access to APIs and services on behalf of users.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/oauth.png
tags:
- Access Control
- Authorization
- Authentication
- Security
- Tokens
repo: https://github.com/api-evangelist/oauth
api_count: 3
apis:
- name: OAuth Authorization API
  description: OAuth 2.0 authorization endpoint operations.
  url: https://oauth.net/2/
- name: OAuth Revocation API
  description: OAuth 2.0 token revocation operations (RFC 7009).
  url: https://oauth.net/2/
- name: OAuth Token API
  description: OAuth 2.0 token endpoint operations.
  url: https://oauth.net/2/
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/oauth/blob/main/capabilities/oauth-capability-edges.yml
- type: AgenticAccess
  url: https://github.com/api-evangelist/oauth/blob/main/agentic-access/oauth-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/oauth/blob/main/security/oauth-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/oauth/blob/main/security/oauth-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/oauth/blob/main/authentication/oauth-authentication.yml
- type: Website
  url: https://oauth.net/
- type: Documentation
  url: https://oauth.net/2/
- type: Reference
  url: https://datatracker.ietf.org/doc/html/rfc6749
provider_count: 130
providers:
- slug: zero-trust-architecture
  name: Zero Trust Architecture
  description: Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that requires all users and devices to be authenticated, authorized, and continuously validated before being granted access to applications and data, regardle…
  api_count: 5
  score_band: emerging
  score_composite: 23.2
  shared: 4
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 72.6
  shared: 3
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 7
  score_band: exemplar
  score_composite: 71.4
  shared: 3
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 3
  score_band: exemplar
  score_composite: 70.0
  shared: 3
- slug: strivacity
  name: Strivacity
  description: Strivacity is a customer identity and access management (CIAM) vendor that runs a single-tenant, dedicated-cloud identity platform for consumer, partner, B2B and — since its Agentic AI release — AI-agent identities. The product covers regi…
  api_count: 12
  score_band: exemplar
  score_composite: 67.9
  shared: 3
- slug: allegion
  name: Allegion
  description: Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Porta…
  api_count: 2
  score_band: strong
  score_composite: 59.8
  shared: 3
- slug: amazon-iam
  name: Amazon IAM
  description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their acces…
  api_count: 1
  score_band: strong
  score_composite: 57.4
  shared: 3
- slug: c1
  name: C1
  description: C1 (ConductorOne) is an identity and access management platform engineered for the AI era. It provides unified access governance across human identities, AI agents, and services — agentic identity management, policy-driven access controls,…
  api_count: 1
  score_band: strong
  score_composite: 55.6
  shared: 3
- slug: indykite
  name: Indykite
  description: IndyKite is the runtime control layer for agentic AI. Its enterprise platform applies trust, context, and runtime control across organizational data so autonomous AI agents can act securely, continuously injecting live signals — identity,…
  api_count: 2
  score_band: developing
  score_composite: 52.6
  shared: 3
- slug: authzed
  name: Authzed
  description: Authzed is a SpiceDB-based authorization platform providing REST and gRPC APIs for Zanzibar-style relationship-based access control. It enables developers to manage schemas, write relationship tuples, and execute fine-grained permission ch…
  api_count: 1
  score_band: developing
  score_composite: 48.3
  shared: 3
- slug: clawvisor
  name: Clawvisor
  description: Clawvisor is the authorization layer for AI agents — a Y Combinator (Spring 2026) security gateway that sits between an AI agent and the tools it acts on (Gmail, Calendar, Drive, Contacts, GitHub, Slack, Notion, Linear, Stripe, Twilio, iMe…
  api_count: 1
  score_band: developing
  score_composite: 45.6
  shared: 3
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 44.2
  shared: 3
- slug: permit-io
  name: Permit.io
  description: Permit.io is an authorization-as-a-service platform that helps developers build, manage, and enforce fine-grained access control in their applications. It provides a Policy Decision Point (PDP), management API, REST API, and permission que…
  api_count: 1
  score_band: developing
  score_composite: 43.8
  shared: 3
- slug: oso
  name: Oso Cloud
  description: Oso Cloud is an authorization-as-a-service platform that provides a REST API for defining and enforcing relationship-based access control policies. It enables developers to model RBAC, ReBAC, and ABAC authorization patterns, manage authori…
  api_count: 1
  score_band: developing
  score_composite: 42.7
  shared: 3
- slug: cakewalk
  name: Cakewalk
  description: Cakewalk is the agentic access management platform for fast-moving companies, combining a granular identity governance and administration (IGA) platform with AI-driven workflows. Cakewalk governs access for both human identities and AI age…
  api_count: 1
  score_band: developing
  score_composite: 41.4
  shared: 3
- slug: spring-security
  name: Spring Security
  description: Spring Security is a powerful and highly customizable authentication and access-control framework for Java applications. It is the de-facto standard for securing Spring-based applications, providing comprehensive security services includin…
  api_count: 2
  score_band: thin
  score_composite: 37.8
  shared: 3
- slug: strata-identity
  name: Strata Identity
  description: Strata Identity is a multi-cloud identity orchestration and agentic AI security company whose Maverics platform lets organizations unify authentication and authorization across multiple clouds, identity providers, and applications, and gov…
  api_count: 1
  score_band: thin
  score_composite: 37.6
  shared: 3
- slug: keycloak
  name: Keycloak
  description: Keycloak is an open source identity and access management solution for modern applications and services, providing single sign-on, identity brokering, user federation, and fine-grained authorization using OAuth 2.0 and OpenID Connect.
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 3
- slug: apache-ranger
  name: Apache Ranger
  description: Apache Ranger is a framework to enable, monitor, and manage comprehensive data security across the Hadoop platform. It provides centralized security administration for fine-grained authorization policies across Hadoop ecosystem components.
  api_count: 1
  score_band: thin
  score_composite: 32.1
  shared: 3
- slug: infra
  name: Infra
  description: Infra is open-source authentication and access management for infrastructure. It grants short-lived, identity-based access to Kubernetes clusters, servers, and databases by connecting an organization's OIDC identity providers (Okta, Google…
  api_count: 1
  score_band: thin
  score_composite: 30.7
  shared: 3
- slug: apache-shiro
  name: Apache Shiro
  description: Apache Shiro is a powerful and easy-to-use Java security framework that performs authentication, authorization, cryptography, and session management. It provides a clean API for securing applications from the smallest mobile applications t…
  api_count: 1
  score_band: thin
  score_composite: 27.3
  shared: 3
- slug: rbac
  name: RBAC
  description: Role-Based Access Control (RBAC) is a security paradigm that restricts system access based on assigned roles rather than individual user identities. Users are granted permissions through role membership, simplifying access management and e…
  api_count: 0
  score_band: emerging
  score_composite: 13.2
  shared: 3
- slug: idsmanager
  name: idsmanager
  description: IDSManager (Jiuzhou Yunteng, 九州云腾) is a Chinese enterprise cybersecurity vendor providing unified identity management and zero-trust security. Its IDaaS platform centralizes account lifecycle, authentication, and authorization around a 5A…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 3
- slug: kinde
  name: Kinde
  description: Kinde is a developer-first authentication and customer identity platform that bundles authentication (passwords, passwordless, social, enterprise SSO), authorization (roles, permissions, scopes), B2B organizations, billing, and feature fla…
  api_count: 2
  score_band: exemplar
  score_composite: 87.5
  shared: 2
- slug: azure-ad
  name: Microsoft Entra ID (formerly Azure AD)
  description: Microsoft's cloud-based identity and access management service that helps employees sign in and access resources. Azure AD provides OAuth, OpenID Connect, SAML, and other identity protocols for securing applications and managing user ident…
  api_count: 9
  score_band: exemplar
  score_composite: 82.8
  shared: 2
- slug: okta
  name: Okta
  description: Okta is the workforce identity incumbent — its Identity Cloud platform (also called the Okta Workforce Identity Platform) covers Single Sign-On, Adaptive MFA, Universal Directory, Lifecycle Management, Identity Governance, Privileged Acces…
  api_count: 2
  score_band: exemplar
  score_composite: 75.3
  shared: 2
- slug: arcade
  name: Arcade
  description: Arcade.dev is the MCP runtime for production AI agent deployments. The Arcade Engine — a hosted or self-hostable API surface — handles OAuth user authorization, manages user tokens, and exposes 7,000+ pre-built integrations as Model Contex…
  api_count: 1
  score_band: exemplar
  score_composite: 72.9
  shared: 2
- slug: authentik
  name: Authentik
  description: Authentik is an open source identity provider from Authentik Security Inc., a public benefit company, exposing a 1,193-operation REST API at /api/v3 on every self-hosted instance. The published OpenAPI covers users, groups, applications, t…
  api_count: 1
  score_band: exemplar
  score_composite: 71.6
  shared: 2
- slug: cisco-xdr
  name: Cisco XDR
  description: Cisco XDR is Cisco's extended detection and response platform, the successor to SecureX. It correlates telemetry from Cisco Secure Endpoint, Secure Firewall, Umbrella, Duo, Secure Email and third-party sources into incidents, and exposes f…
  api_count: 12
  score_band: strong
  score_composite: 65.6
  shared: 2
- slug: frontegg
  name: Frontegg
  description: Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS. It provides self-serve authentication, multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that…
  api_count: 10
  score_band: strong
  score_composite: 65.0
  shared: 2
---
