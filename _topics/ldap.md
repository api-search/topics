---
layout: topic
slug: ldap
name: LDAP
kind: topic
description: LDAP (Lightweight Directory Access Protocol) is an industry-standard application protocol for accessing and maintaining distributed directory information services over an IP network, formally specified in RFC 4511. It plays a critical role in protecting organizational assets and maintaining a strong security posture through centralized authentication, authorization, and identity management. LDAP underlies directory services such as Microsoft Active Directory, OpenLDAP, and 389 Directory Server, and is widely used for single sign-on, enterprise address books, and application identity stores.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ldap.png
tags:
- Authentication
- Authorization
- Directory Services
- Identity Management
- LDAP
- Protocol
- SSO
- Standards
repo: https://github.com/api-evangelist/ldap
api_count: 1
apis:
- name: LDAP
  description: Lightweight Directory Access Protocol for accessing and maintaining distributed directory information services over an IP network. The protocol defines bind, search, compare, add, delete, modify, and modifyDN operations carried over a conn…
  url: https://ldap.com/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/ldap/blob/main/security/ldap-domain-security.yml
- type: Website
  url: https://ldap.com/
- type: Documentation
  url: https://ldap.com/
- type: Specification
  url: https://datatracker.ietf.org/doc/html/rfc4511
- type: Wikipedia
  url: https://en.wikipedia.org/wiki/Lightweight_Directory_Access_Protocol
- type: Blog
  url: https://ldap.com/feed/
provider_count: 72
providers:
- slug: kinde
  name: Kinde
  description: Kinde is a developer-first authentication and customer identity platform that bundles authentication (passwords, passwordless, social, enterprise SSO), authorization (roles, permissions, scopes), B2B organizations, billing, and feature fla…
  api_count: 2
  score_band: exemplar
  score_composite: 87.5
  shared: 4
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 7
  score_band: exemplar
  score_composite: 71.4
  shared: 4
- slug: frontegg
  name: Frontegg
  description: Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS. It provides self-serve authentication, multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that…
  api_count: 10
  score_band: strong
  score_composite: 65.0
  shared: 4
- slug: active-directory
  name: Microsoft Active Directory
  description: Microsoft Active Directory and Microsoft Entra ID provide identity and access management for organizations of all sizes. Microsoft Graph API is the unified REST API gateway for accessing and managing Microsoft Entra ID (formerly Azure Acti…
  api_count: 3
  score_band: strong
  score_composite: 61.4
  shared: 4
- slug: authelia
  name: Authelia
  description: Authelia is an open source authentication and authorization server providing multi-factor authentication and single sign-on for applications behind a reverse proxy. It supports OpenID Connect 1.0, OAuth 2.0, TOTP, WebAuthn, and Duo Push as…
  api_count: 1
  score_band: strong
  score_composite: 54.5
  shared: 4
- slug: keycloak
  name: Keycloak
  description: Keycloak is an open source identity and access management solution for modern applications and services, providing single sign-on, identity brokering, user federation, and fine-grained authorization using OAuth 2.0 and OpenID Connect.
  api_count: 1
  score_band: thin
  score_composite: 36.2
  shared: 4
- slug: casdoor
  name: Casdoor
  description: Casdoor is an open-source, AI-first identity and access management (IAM) and MCP gateway authentication server with a web UI. Built in Go (Beego) with a React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, Kerberos/SPNEGO…
  api_count: 1
  score_band: emerging
  score_composite: 23.8
  shared: 4
- slug: azure-ad
  name: Microsoft Entra ID (formerly Azure AD)
  description: Microsoft's cloud-based identity and access management service that helps employees sign in and access resources. Azure AD provides OAuth, OpenID Connect, SAML, and other identity protocols for securing applications and managing user ident…
  api_count: 9
  score_band: exemplar
  score_composite: 82.8
  shared: 3
- slug: okta
  name: Okta
  description: Okta is the workforce identity incumbent — its Identity Cloud platform (also called the Okta Workforce Identity Platform) covers Single Sign-On, Adaptive MFA, Universal Directory, Lifecycle Management, Identity Governance, Privileged Acces…
  api_count: 2
  score_band: exemplar
  score_composite: 75.3
  shared: 3
- slug: authentik
  name: Authentik
  description: Authentik is an open source identity provider from Authentik Security Inc., a public benefit company, exposing a 1,193-operation REST API at /api/v3 on every self-hosted instance. The published OpenAPI covers users, groups, applications, t…
  api_count: 1
  score_band: exemplar
  score_composite: 71.6
  shared: 3
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 3
  score_band: exemplar
  score_composite: 70.0
  shared: 3
- slug: propelauth
  name: PropelAuth
  description: PropelAuth is a B2B SaaS authentication and multi-tenant user management platform purpose-built for organizations that sell to other organizations. It provides hosted login UIs, first-class organizations / tenants with custom roles and per…
  api_count: 3
  score_band: strong
  score_composite: 63.2
  shared: 3
- slug: workos
  name: WorkOS
  description: WorkOS is the "Enterprise Ready" identity platform for B2B SaaS — providing AuthKit user management, enterprise SSO (SAML/OIDC), Directory Sync (SCIM 2.0), Multi-Factor Authentication, Audit Logs, Admin Portal, Fine-Grained Authorization (…
  api_count: 1
  score_band: strong
  score_composite: 59.6
  shared: 3
- slug: forgerock
  name: ForgeRock
  description: ForgeRock, now part of Ping Identity, provides digital identity and access management solutions for secure authentication, authorization, and identity governance across cloud and hybrid environments.
  api_count: 7
  score_band: strong
  score_composite: 56.7
  shared: 3
- slug: descope
  name: Descope
  description: Descope is a customer and agentic identity access management (CIAM) platform founded in 2022 by veterans of Sentrigo and Demisto (acquired by Palo Alto Networks). Its signature is drag-and-drop Descope Flows — a visual authentication-flow…
  api_count: 1
  score_band: strong
  score_composite: 56.4
  shared: 3
- slug: amazon-iam-identity-center
  name: Amazon IAM Identity Center
  description: AWS IAM Identity Center (successor to AWS Single Sign-On) is where you create, or connect, your workforce identities in AWS once and manage access centrally across your AWS organization. You can create user identities directly in IAM Ident…
  api_count: 2
  score_band: developing
  score_composite: 54.2
  shared: 3
- slug: fusionauth
  name: FusionAuth
  description: FusionAuth is a developer-focused customer identity and access management (CIAM) platform that delivers authentication, authorization, registration, multi-factor authentication, single sign-on, OAuth2 and OpenID Connect, and user managemen…
  api_count: 1
  score_band: developing
  score_composite: 52.3
  shared: 3
- slug: amazon-directory-service
  name: Amazon Directory Service
  description: AWS Directory Service for Microsoft Active Directory, also known as AWS Managed Microsoft AD, enables your directory-aware workloads and AWS resources to use managed Active Directory in AWS. It provides a fully managed, highly available Mi…
  api_count: 1
  score_band: developing
  score_composite: 52.0
  shared: 3
- slug: ping-identity
  name: Ping Identity
  description: Identity for enterprises - flawless user experience with fortified enterprise protection. Ping Identity's PingOne platform provides cloud-based identity and access management with REST APIs covering authentication, authorization, user and…
  api_count: 1
  score_band: developing
  score_composite: 50.8
  shared: 3
- slug: zitadel
  name: Zitadel
  description: Zitadel is an open source identity infrastructure platform providing secure authentication and user management with built-in support for OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained…
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 3
- slug: cirrus-identity
  name: Cirrus Identity
  description: Cirrus Identity provides managed identity and access management for higher education, connecting modern identity providers, federations, and legacy systems to standardize authentication across campus environments without replacing existing…
  api_count: 1
  score_band: developing
  score_composite: 44.5
  shared: 3
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 44.2
  shared: 3
- slug: eve-online
  name: EVE Online
  description: EVE Online is a massively multiplayer online (MMO) space game published by CCP Games. The EVE Online third-party developer ecosystem is built around the EVE Swagger Interface (ESI), a RESTful HTTP API hosted at esi.evetech.net that exposes…
  api_count: 7
  score_band: developing
  score_composite: 43.4
  shared: 3
- slug: strata-identity
  name: Strata Identity
  description: Strata Identity is a multi-cloud identity orchestration and agentic AI security company whose Maverics platform lets organizations unify authentication and authorization across multiple clouds, identity providers, and applications, and gov…
  api_count: 1
  score_band: thin
  score_composite: 37.6
  shared: 3
- slug: pingone
  name: PingOne
  description: PingOne is Ping Identity's cloud-based identity and access management platform providing authentication, authorization, single sign-on, MFA, identity verification, risk evaluation, and user lifecycle management for workforce and customer i…
  api_count: 1
  score_band: thin
  score_composite: 33.6
  shared: 3
- slug: better-auth
  name: Better Auth
  description: Better Auth is a framework-agnostic authentication and authorization library for TypeScript. Unlike hosted identity providers, Better Auth runs inside the developer's own application against their own database (Postgres, MySQL, SQLite, Mon…
  api_count: 4
  score_band: thin
  score_composite: 28.4
  shared: 3
- slug: zero-trust-architecture
  name: Zero Trust Architecture
  description: Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that requires all users and devices to be authenticated, authorized, and continuously validated before being granted access to applications and data, regardle…
  api_count: 5
  score_band: emerging
  score_composite: 23.2
  shared: 3
- slug: dex
  name: Dex
  description: A federated OpenID Connect provider that connects to other identity providers through connectors, enabling authentication for applications without handling passwords directly. Dex acts as a portal to other identity providers through connec…
  api_count: 1
  score_band: emerging
  score_composite: 19.7
  shared: 3
- slug: openldap
  name: OpenLDAP
  description: OpenLDAP is an open source implementation of the Lightweight Directory Access Protocol (LDAP) that provides directory server daemons, client libraries, and utilities for managing distributed directory services. The suite includes slapd (th…
  api_count: 1
  score_band: minimal
  score_composite: 6.5
  shared: 3
- slug: idsmanager
  name: idsmanager
  description: IDSManager (Jiuzhou Yunteng, 九州云腾) is a Chinese enterprise cybersecurity vendor providing unified identity management and zero-trust security. Its IDaaS platform centralizes account lifecycle, authentication, and authorization around a 5A…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 3
---
