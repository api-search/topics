---
layout: topic
slug: kerberos
name: Kerberos
kind: topic
description: Kerberos is a computer-network authentication protocol that works on the basis of tickets to allow nodes communicating over a non-secure network to prove their identity to one another in a secure manner. It is widely used in enterprise environments for single sign-on authentication.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/kerberos.png
tags:
- Authentication
- Kerberos
- Security
- SSO
repo: https://github.com/api-evangelist/kerberos
api_count: 1
apis:
- name: Kerberos
  description: Kerberos network authentication protocol for secure identity verification in enterprise environments.
  url: https://web.mit.edu/kerberos/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/kerberos/blob/main/security/kerberos-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/kerberos/blob/main/security/kerberos-domain-security.yml
- type: Website
  url: https://web.mit.edu/kerberos/
- type: Documentation
  url: https://web.mit.edu/kerberos/krb5-latest/doc/
provider_count: 96
providers:
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 7
  score_band: exemplar
  score_composite: 70.9
  shared: 3
- slug: transmit-security
  name: Transmit Security
  description: Transmit Security provides the Mosaic platform, a comprehensive CIAM (Customer Identity and Access Management) solution offering REST APIs for passkey and WebAuthn authentication, fraud detection and risk-based access control, identity orc…
  api_count: 7
  score_band: developing
  score_composite: 51.8
  shared: 3
- slug: slashid
  name: SlashID
  description: SlashID is a developer-first identity platform that provides REST APIs for passwordless authentication, multi-factor authentication, passkeys, and comprehensive user management across web and mobile applications. The platform offers three…
  api_count: 1
  score_band: developing
  score_composite: 51.3
  shared: 3
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 43.7
  shared: 3
- slug: apache-knox
  name: Apache Knox
  description: Apache Knox is a REST API and application gateway for the Apache Hadoop ecosystem. It provides a single access point for all REST and HTTP interactions with Apache Hadoop clusters, with authentication, authorization, SSO, and audit capabil…
  api_count: 1
  score_band: developing
  score_composite: 39.8
  shared: 3
- slug: keycloak
  name: Keycloak
  description: Keycloak is an open source identity and access management solution for modern applications and services, providing single sign-on, identity brokering, user federation, and fine-grained authorization using OAuth 2.0 and OpenID Connect.
  api_count: 1
  score_band: thin
  score_composite: 36.7
  shared: 3
- slug: strata-identity
  name: Strata Identity
  description: Strata Identity is a multi-cloud identity orchestration and agentic AI security company whose Maverics platform lets organizations unify authentication and authorization across multiple clouds, identity providers, and applications, and gov…
  api_count: 1
  score_band: thin
  score_composite: 35.8
  shared: 3
- slug: centrify
  name: Centrify
  description: Centrify is an identity and privileged access management (PAM) platform now delivered as part of Delinea (the company formed from the Centrify + Thycotic merger). The Centrify Identity Platform / Cloud Suite / Privileged Access Service sec…
  api_count: 1
  score_band: thin
  score_composite: 27.2
  shared: 3
- slug: imprivata
  name: Imprivata
  description: Imprivata is a digital identity and access management company built for healthcare and other mission-critical industries. Its platform delivers passwordless and multifactor authentication, single sign-on (Enterprise Access Management, form…
  api_count: 0
  score_band: emerging
  score_composite: 23.6
  shared: 3
- slug: idsmanager
  name: idsmanager
  description: IDSManager (Jiuzhou Yunteng, 九州云腾) is a Chinese enterprise cybersecurity vendor providing unified identity management and zero-trust security. Its IDaaS platform centralizes account lifecycle, authentication, and authorization around a 5A…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: kinde
  name: Kinde
  description: Kinde is a developer-first authentication and customer identity platform that bundles authentication (passwords, passwordless, social, enterprise SSO), authorization (roles, permissions, scopes), B2B organizations, billing, and feature fla…
  api_count: 2
  score_band: exemplar
  score_composite: 86.1
  shared: 2
- slug: azure-ad
  name: Microsoft Entra ID (formerly Azure AD)
  description: Microsoft's cloud-based identity and access management service that helps employees sign in and access resources. Azure AD provides OAuth, OpenID Connect, SAML, and other identity protocols for securing applications and managing user ident…
  api_count: 9
  score_band: exemplar
  score_composite: 79.7
  shared: 2
- slug: cvent
  name: Cvent
  description: Cvent is a leading meetings, events, and hospitality technology provider with over 4,800 employees and 22,000+ customers worldwide. The Cvent platform spans Event Cloud (event management, registration, mobile event apps, virtual and hybrid…
  api_count: 2
  score_band: exemplar
  score_composite: 75.2
  shared: 2
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 71.8
  shared: 2
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 3
  score_band: exemplar
  score_composite: 67.9
  shared: 2
- slug: frontegg
  name: Frontegg
  description: Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS. It provides self-serve authentication, multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that…
  api_count: 10
  score_band: exemplar
  score_composite: 67.3
  shared: 2
- slug: barndoor
  name: Barndoor
  description: Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security,…
  api_count: 1
  score_band: strong
  score_composite: 65.1
  shared: 2
- slug: strivacity
  name: Strivacity
  description: Strivacity is a customer identity and access management (CIAM) vendor that runs a single-tenant, dedicated-cloud identity platform for consumer, partner, B2B and — since its Agentic AI release — AI-agent identities. The product covers regi…
  api_count: 12
  score_band: strong
  score_composite: 65.1
  shared: 2
- slug: propelauth
  name: PropelAuth
  description: PropelAuth is a B2B SaaS authentication and multi-tenant user management platform purpose-built for organizations that sell to other organizations. It provides hosted login UIs, first-class organizations / tenants with custom roles and per…
  api_count: 3
  score_band: strong
  score_composite: 64.2
  shared: 2
- slug: stytch
  name: Stytch
  description: Stytch is an authentication and identity infrastructure provider. Its Consumer and B2B APIs cover passwordless authentication (Magic Links, OTP, OAuth, WebAuthn / Passkeys, TOTP), enterprise SSO (SAML / OIDC) and SCIM, sessions, M2M client…
  api_count: 3
  score_band: strong
  score_composite: 63.5
  shared: 2
- slug: cisco-xdr
  name: Cisco XDR
  description: Cisco XDR is Cisco's extended detection and response platform, the successor to SecureX. It correlates telemetry from Cisco Secure Endpoint, Secure Firewall, Umbrella, Duo, Secure Email and third-party sources into incidents, and exposes f…
  api_count: 12
  score_band: strong
  score_composite: 63.2
  shared: 2
- slug: okta
  name: Okta
  description: Okta is the workforce identity incumbent — its Identity Cloud platform (also called the Okta Workforce Identity Platform) covers Single Sign-On, Adaptive MFA, Universal Directory, Lifecycle Management, Identity Governance, Privileged Acces…
  api_count: 1
  score_band: strong
  score_composite: 62.8
  shared: 2
- slug: workos
  name: WorkOS
  description: WorkOS is the "Enterprise Ready" identity platform for B2B SaaS — providing AuthKit user management, enterprise SSO (SAML/OIDC), Directory Sync (SCIM 2.0), Multi-Factor Authentication, Audit Logs, Admin Portal, Fine-Grained Authorization (…
  api_count: 1
  score_band: strong
  score_composite: 60.3
  shared: 2
- slug: allegion
  name: Allegion
  description: Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Porta…
  api_count: 2
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: amazon-iam
  name: Amazon IAM
  description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their acces…
  api_count: 1
  score_band: strong
  score_composite: 56.5
  shared: 2
- slug: microsoft-entra
  name: Microsoft Entra
  description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management services including authentication, authorization, and directory services.
  api_count: 1
  score_band: strong
  score_composite: 56.5
  shared: 2
- slug: descope
  name: Descope
  description: Descope is a customer and agentic identity access management (CIAM) platform founded in 2022 by veterans of Sentrigo and Demisto (acquired by Palo Alto Networks). Its signature is drag-and-drop Descope Flows — a visual authentication-flow…
  api_count: 1
  score_band: strong
  score_composite: 56.2
  shared: 2
- slug: civic
  name: Civic
  description: Civic is a digital identity and security platform offering authentication, identity verification, and AI agent security infrastructure. Core products include Civic Hub (a Model Context Protocol gateway with guardrails, audit logging, secre…
  api_count: 1
  score_band: strong
  score_composite: 56.0
  shared: 2
- slug: yubico
  name: Yubico
  description: Yubico is the security company behind the YubiKey hardware authentication device and the inventor of the Yubico One-Time Password (OTP). Its public developer surface centers on YubiCloud, a hosted REST service that verifies Yubico OTPs via…
  api_count: 1
  score_band: strong
  score_composite: 55.1
  shared: 2
- slug: doximity
  name: Doximity
  description: Doximity is the leading digital platform for U.S. medical professionals, used by the majority of physicians and a large share of nurse practitioners and physician assistants. Its public developer surface is an OAuth 2.0 and OpenID Connect…
  api_count: 1
  score_band: strong
  score_composite: 54.6
  shared: 2
---
