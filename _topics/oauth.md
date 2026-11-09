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
- OAuth
- Security
- Tokens
- Authentication
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
- type: Plans
  url: https://github.com/api-evangelist/oauth/blob/main/plans/oauth-plans-pricing.yml
- type: RateLimits
  url: https://github.com/api-evangelist/oauth/blob/main/rate-limits/oauth-rate-limits.yml
- type: FinOps
  url: https://github.com/api-evangelist/oauth/blob/main/finops/oauth-finops.yml
- type: Blog
  url: https://oauth.net/articles/
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
provider_count: 349
providers:
- slug: strivacity
  name: Strivacity
  description: Strivacity is a customer identity and access management (CIAM) vendor that runs a single-tenant, dedicated-cloud identity platform for consumer, partner, B2B and — since its Agentic AI release — AI-agent identities. The product covers regi…
  api_count: 8
  score_band: exemplar
  score_composite: 74.2
  shared: 4
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 8
  score_band: exemplar
  score_composite: 72.2
  shared: 4
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 4
  score_band: exemplar
  score_composite: 72.1
  shared: 4
- slug: allegion
  name: Allegion
  description: Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Porta…
  api_count: 2
  score_band: developing
  score_composite: 52.9
  shared: 4
- slug: strata-identity
  name: Strata Identity
  description: Strata Identity is a multi-cloud identity orchestration and agentic AI security company whose Maverics platform lets organizations unify authentication and authorization across multiple clouds, identity providers, and applications, and gov…
  api_count: 1
  score_band: thin
  score_composite: 37.9
  shared: 4
- slug: spring-security
  name: Spring Security
  description: Spring Security is a powerful and highly customizable authentication and access-control framework for Java applications. It is the de-facto standard for securing Spring-based applications, providing comprehensive security services includin…
  api_count: 2
  score_band: thin
  score_composite: 37.7
  shared: 4
- slug: keycloak
  name: Keycloak
  description: Keycloak is an open source identity and access management solution for modern applications and services, providing single sign-on, identity brokering, user federation, and fine-grained authorization using OAuth 2.0 and OpenID Connect.
  api_count: 2
  score_band: thin
  score_composite: 35.3
  shared: 4
- slug: zero-trust-architecture
  name: Zero Trust Architecture
  description: Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that requires all users and devices to be authenticated, authorized, and continuously validated before being granted access to applications and data, regardle…
  api_count: 5
  score_band: emerging
  score_composite: 23.1
  shared: 4
- slug: azure-ad
  name: Microsoft Entra ID (formerly Azure AD)
  description: Microsoft's cloud-based identity and access management service that helps employees sign in and access resources. Azure AD provides OAuth, OpenID Connect, SAML, and other identity protocols for securing applications and managing user ident…
  api_count: 9
  score_band: exemplar
  score_composite: 89.0
  shared: 3
- slug: kinde
  name: Kinde
  description: Kinde is a developer-first authentication and customer identity platform that bundles authentication (passwords, passwordless, social, enterprise SSO), authorization (roles, permissions, scopes), B2B organizations, billing, and feature fla…
  api_count: 2
  score_band: exemplar
  score_composite: 88.8
  shared: 3
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 75.9
  shared: 3
- slug: authentik
  name: Authentik
  description: Authentik is an open source identity provider from Authentik Security Inc., a public benefit company, exposing a 1,193-operation REST API at /api/v3 on every self-hosted instance. The published OpenAPI covers users, groups, applications, t…
  api_count: 1
  score_band: exemplar
  score_composite: 74.5
  shared: 3
- slug: cisco-xdr
  name: Cisco XDR
  description: Cisco XDR is Cisco's extended detection and response platform, the successor to SecureX. It correlates telemetry from Cisco Secure Endpoint, Secure Firewall, Umbrella, Duo, Secure Email and third-party sources into incidents, and exposes f…
  api_count: 12
  score_band: exemplar
  score_composite: 69.9
  shared: 3
- slug: gluu
  name: Gluu
  description: Gluu is a technology company that specializes in providing identity and access management solutions for businesses. Their platform allows organizations to centrally manage the authentication and authorization of users across various applic…
  api_count: 12
  score_band: strong
  score_composite: 66.1
  shared: 3
- slug: descope
  name: Descope
  description: Descope is a customer and agentic identity access management (CIAM) platform founded in 2022 by veterans of Sentrigo and Demisto (acquired by Palo Alto Networks). Its signature is drag-and-drop Descope Flows — a visual authentication-flow…
  api_count: 1
  score_band: strong
  score_composite: 66.0
  shared: 3
- slug: cobot
  name: Cobot
  description: 'Cobot is coworking and flexible-workspace management software, built and operated by Upstream - Agile GmbH in Berlin, Germany. It runs the day-to-day of a coworking space or space network from one platform: memberships and plans, resource…'
  api_count: 1
  score_band: strong
  score_composite: 62.6
  shared: 3
- slug: forgerock
  name: ForgeRock
  description: ForgeRock, now part of Ping Identity, provides digital identity and access management solutions for secure authentication, authorization, and identity governance across cloud and hybrid environments.
  api_count: 8
  score_band: strong
  score_composite: 60.7
  shared: 3
- slug: authlete
  name: Authlete
  description: Authlete is an API-first OAuth 2.0 and OpenID Connect backend service that provides a headless authorization-server engine. It handles the OAuth/OIDC protocol logic and token management so organizations can stand up standards-compliant aut…
  api_count: 1
  score_band: strong
  score_composite: 59.9
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
- slug: barndoor
  name: Barndoor
  description: Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security,…
  api_count: 1
  score_band: strong
  score_composite: 59.0
  shared: 3
- slug: c1
  name: C1
  description: C1 (ConductorOne) is an identity and access management platform engineered for the AI era. It provides unified access governance across human identities, AI agents, and services — agentic identity management, policy-driven access controls,…
  api_count: 1
  score_band: strong
  score_composite: 58.6
  shared: 3
- slug: butterflymx
  name: ButterflyMX
  description: ButterflyMX is a property-access technology company whose smart video intercoms, keypads, smart locks, elevator controls, vehicle-access readers, package rooms and front-desk stations are installed in more than 20,000 multifamily, commerci…
  api_count: 1
  score_band: strong
  score_composite: 57.2
  shared: 3
- slug: fusionauth
  name: FusionAuth
  description: FusionAuth is a developer-focused customer identity and access management (CIAM) platform that delivers authentication, authorization, registration, multi-factor authentication, single sign-on, OAuth2 and OpenID Connect, and user managemen…
  api_count: 1
  score_band: strong
  score_composite: 56.6
  shared: 3
- slug: onecli
  name: Onecli
  description: OneCLI is an open-source credential gateway and identity layer for AI agents. Agents connect to Gmail, GitHub, Slack, AWS, Jira and 50+ other services through a network-layer proxy that injects real API keys and OAuth tokens at request tim…
  api_count: 1
  score_band: strong
  score_composite: 56.0
  shared: 3
- slug: clawvisor
  name: Clawvisor
  description: Clawvisor is the authorization layer for AI agents — a Y Combinator (Spring 2026) security gateway that sits between an AI agent and the tools it acts on (Gmail, Calendar, Drive, Contacts, GitHub, Slack, Notion, Linear, Stripe, Twilio, iMe…
  api_count: 1
  score_band: strong
  score_composite: 55.7
  shared: 3
- slug: zitadel
  name: Zitadel
  description: Zitadel is an open source identity infrastructure platform providing secure authentication and user management with built-in support for OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained…
  api_count: 1
  score_band: strong
  score_composite: 55.3
  shared: 3
- slug: indykite
  name: Indykite
  description: IndyKite is the runtime control layer for agentic AI. Its enterprise platform applies trust, context, and runtime control across organizational data so autonomous AI agents can act securely, continuously injecting live signals — identity,…
  api_count: 2
  score_band: strong
  score_composite: 54.3
  shared: 3
- slug: civic
  name: Civic
  description: Civic is a digital identity and security platform offering authentication, identity verification, and AI agent security infrastructure. Core products include Civic Hub (a Model Context Protocol gateway with guardrails, audit logging, secre…
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 3
- slug: ory
  name: Ory
  description: Ory is an open source identity infrastructure platform providing OAuth2 and OpenID Connect (Hydra), identity and user management (Kratos), permissions and authorization (Keto), and a reverse proxy with policy enforcement (Oathkeeper).
  api_count: 17
  score_band: developing
  score_composite: 52.6
  shared: 3
---
