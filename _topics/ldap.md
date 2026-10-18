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
- Identity and Access Management
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
- type: Plans
  url: https://github.com/api-evangelist/ldap/blob/main/plans/ldap-plans-pricing.yml
- type: RateLimits
  url: https://github.com/api-evangelist/ldap/blob/main/rate-limits/ldap-rate-limits.yml
- type: FinOps
  url: https://github.com/api-evangelist/ldap/blob/main/finops/ldap-finops.yml
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
provider_count: 88
providers:
- slug: casdoor
  name: Casdoor
  description: Casdoor is an open-source, AI-first identity and access management (IAM) and MCP gateway authentication server with a web UI. Built in Go (Beego) with a React frontend, Casdoor supports OAuth 2.0, OIDC, SAML 2.0, CAS, LDAP, Kerberos/SPNEGO…
  api_count: 1
  score_band: emerging
  score_composite: 22.5
  shared: 5
- slug: kinde
  name: Kinde
  description: Kinde is a developer-first authentication and customer identity platform that bundles authentication (passwords, passwordless, social, enterprise SSO), authorization (roles, permissions, scopes), B2B organizations, billing, and feature fla…
  api_count: 3
  score_band: exemplar
  score_composite: 82.9
  shared: 4
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 7
  score_band: exemplar
  score_composite: 70.3
  shared: 4
- slug: active-directory
  name: Microsoft Active Directory
  description: Microsoft Active Directory and Microsoft Entra ID provide identity and access management for organizations of all sizes. Microsoft Graph API is the unified REST API gateway for accessing and managing Microsoft Entra ID (formerly Azure Acti…
  api_count: 3
  score_band: strong
  score_composite: 60.5
  shared: 4
- slug: frontegg
  name: Frontegg
  description: Frontegg is a customer identity and access management (CIAM) platform for B2B SaaS. It provides self-serve authentication, multi-tenancy, role-based access control, single sign-on, SCIM provisioning, entitlements, and an admin portal that…
  api_count: 10
  score_band: strong
  score_composite: 57.1
  shared: 4
- slug: authelia
  name: Authelia
  description: Authelia is an open source authentication and authorization server providing multi-factor authentication and single sign-on for applications behind a reverse proxy. It supports OpenID Connect 1.0, OAuth 2.0, TOTP, WebAuthn, and Duo Push as…
  api_count: 1
  score_band: developing
  score_composite: 53.1
  shared: 4
- slug: strata-identity
  name: Strata Identity
  description: Strata Identity is a multi-cloud identity orchestration and agentic AI security company whose Maverics platform lets organizations unify authentication and authorization across multiple clouds, identity providers, and applications, and gov…
  api_count: 1
  score_band: thin
  score_composite: 37.9
  shared: 4
- slug: keycloak
  name: Keycloak
  description: Keycloak is an open source identity and access management solution for modern applications and services, providing single sign-on, identity brokering, user federation, and fine-grained authorization using OAuth 2.0 and OpenID Connect.
  api_count: 1
  score_band: thin
  score_composite: 34.7
  shared: 4
- slug: pingone
  name: PingOne
  description: PingOne is Ping Identity's cloud-based identity and access management platform providing authentication, authorization, single sign-on, MFA, identity verification, risk evaluation, and user lifecycle management for workforce and customer i…
  api_count: 1
  score_band: thin
  score_composite: 33.6
  shared: 4
- slug: azure-ad
  name: Microsoft Entra ID (formerly Azure AD)
  description: Microsoft's cloud-based identity and access management service that helps employees sign in and access resources. Azure AD provides OAuth, OpenID Connect, SAML, and other identity protocols for securing applications and managing user ident…
  api_count: 9
  score_band: exemplar
  score_composite: 81.8
  shared: 3
- slug: okta
  name: Okta
  description: Okta is the workforce identity incumbent — its Identity Cloud platform (also called the Okta Workforce Identity Platform) covers Single Sign-On, Adaptive MFA, Universal Directory, Lifecycle Management, Identity Governance, Privileged Acces…
  api_count: 3
  score_band: exemplar
  score_composite: 74.3
  shared: 3
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 72.6
  shared: 3
- slug: authentik
  name: Authentik
  description: Authentik is an open source identity provider from Authentik Security Inc., a public benefit company, exposing a 1,193-operation REST API at /api/v3 on every self-hosted instance. The published OpenAPI covers users, groups, applications, t…
  api_count: 2
  score_band: exemplar
  score_composite: 70.1
  shared: 3
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 3
  score_band: exemplar
  score_composite: 69.1
  shared: 3
- slug: gluu
  name: Gluu
  description: Gluu is a technology company that specializes in providing identity and access management solutions for businesses. Their platform allows organizations to centrally manage the authentication and authorization of users across various applic…
  api_count: 23
  score_band: strong
  score_composite: 62.9
  shared: 3
- slug: workos
  name: WorkOS
  description: WorkOS is the "Enterprise Ready" identity platform for B2B SaaS — providing AuthKit user management, enterprise SSO (SAML/OIDC), Directory Sync (SCIM 2.0), Multi-Factor Authentication, Audit Logs, Admin Portal, Fine-Grained Authorization (…
  api_count: 1
  score_band: strong
  score_composite: 58.7
  shared: 3
- slug: centrify
  name: Centrify
  description: Centrify is an identity and privileged access management (PAM) platform now delivered as part of Delinea (the company formed from the Centrify + Thycotic merger). The Centrify Identity Platform / Cloud Suite / Privileged Access Service sec…
  api_count: 15
  score_band: strong
  score_composite: 57.6
  shared: 3
- slug: descope
  name: Descope
  description: Descope is a customer and agentic identity access management (CIAM) platform founded in 2022 by veterans of Sentrigo and Demisto (acquired by Palo Alto Networks). Its signature is drag-and-drop Descope Flows — a visual authentication-flow…
  api_count: 1
  score_band: strong
  score_composite: 56.5
  shared: 3
- slug: propelauth
  name: PropelAuth
  description: PropelAuth is a B2B SaaS authentication and multi-tenant user management platform purpose-built for organizations that sell to other organizations. It provides hosted login UIs, first-class organizations / tenants with custom roles and per…
  api_count: 3
  score_band: strong
  score_composite: 56.5
  shared: 3
- slug: amazon-iam
  name: Amazon IAM
  description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their acces…
  api_count: 1
  score_band: strong
  score_composite: 55.9
  shared: 3
- slug: forgerock
  name: ForgeRock
  description: ForgeRock, now part of Ping Identity, provides digital identity and access management solutions for secure authentication, authorization, and identity governance across cloud and hybrid environments.
  api_count: 7
  score_band: strong
  score_composite: 55.7
  shared: 3
- slug: amazon-iam-identity-center
  name: Amazon IAM Identity Center
  description: AWS IAM Identity Center (successor to AWS Single Sign-On) is where you create, or connect, your workforce identities in AWS once and manage access centrally across your AWS organization. You can create user identities directly in IAM Ident…
  api_count: 2
  score_band: developing
  score_composite: 52.7
  shared: 3
- slug: fusionauth
  name: FusionAuth
  description: FusionAuth is a developer-focused customer identity and access management (CIAM) platform that delivers authentication, authorization, registration, multi-factor authentication, single sign-on, OAuth2 and OpenID Connect, and user managemen…
  api_count: 2
  score_band: developing
  score_composite: 50.8
  shared: 3
- slug: amazon-directory-service
  name: Amazon Directory Service
  description: AWS Directory Service for Microsoft Active Directory, also known as AWS Managed Microsoft AD, enables your directory-aware workloads and AWS resources to use managed Active Directory in AWS. It provides a fully managed, highly available Mi…
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 3
- slug: ping-identity
  name: Ping Identity
  description: Identity for enterprises - flawless user experience with fortified enterprise protection. Ping Identity's PingOne platform provides cloud-based identity and access management with REST APIs covering authentication, authorization, user and…
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 3
- slug: zitadel
  name: Zitadel
  description: Zitadel is an open source identity infrastructure platform providing secure authentication and user management with built-in support for OAuth 2.0, OpenID Connect, SAML 2.0, SCIM, FIDO2, and passkeys. It offers multi-tenancy, fine-grained…
  api_count: 1
  score_band: developing
  score_composite: 49.0
  shared: 3
- slug: cirrus-identity
  name: Cirrus Identity
  description: Cirrus Identity provides managed identity and access management for higher education, connecting modern identity providers, federations, and legacy systems to standardize authentication across campus environments without replacing existing…
  api_count: 1
  score_band: developing
  score_composite: 44.5
  shared: 3
- slug: eve-online
  name: EVE Online
  description: EVE Online is a massively multiplayer online (MMO) space game published by CCP Games. The EVE Online third-party developer ecosystem is built around the EVE Swagger Interface (ESI), a RESTful HTTP API hosted at esi.evetech.net that exposes…
  api_count: 7
  score_band: developing
  score_composite: 44.1
  shared: 3
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 42.6
  shared: 3
- slug: infra
  name: Infra
  description: Infra is open-source authentication and access management for infrastructure. It grants short-lived, identity-based access to Kubernetes clusters, servers, and databases by connecting an organization's OIDC identity providers (Okta, Google…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 3
---
