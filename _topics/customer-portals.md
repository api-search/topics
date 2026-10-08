---
layout: topic
slug: customer-portals
name: Customer Portals
kind: topic
description: Customer Portals is the topic dedicated to the architecture, APIs, schemas, and reference designs behind self-service customer portals. A customer portal is a secure web or mobile experience where authenticated customers can manage their profile, view orders and invoices, pay bills, submit and track support tickets, download documents, manage notification preferences, and access account-specific resources. Modern customer portals are typically composed of multiple back-end APIs - authentication and identity, profile and preference management, billing and invoicing, support and ticketing, notifications, and document delivery - surfaced through a single front-end shell. This repository tracks the vendors, patterns, and standards that make customer portals reliable, accessible, and API-driven.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/customer-portals.png
tags:
- Account Management
- Authentication
- Billing
- Customer Self-Service
- Documents
- Identity
- Invoices
- Notification
- Portal
- Profiles
- Self-Service
- Support
- Ticketing
repo: https://github.com/api-evangelist/customer-portals
api_count: 0
apis: []
links:
- type: Salesforce Experience Cloud
  url: https://www.salesforce.com/products/experience-cloud/overview/
- type: Zendesk Help Center
  url: https://www.zendesk.com/service/help-center/
- type: HubSpot Customer Portal
  url: https://www.hubspot.com/products/service/customer-portal
- type: Auth0
  url: https://auth0.com
- type: Okta Customer Identity
  url: https://www.okta.com/products/customer-identity/
- type: Stripe Customer Portal
  url: https://stripe.com/billing/customer-portal
- type: Freshdesk
  url: https://www.freshworks.com/freshdesk/
- type: Zuora
  url: https://www.zuora.com
provider_count: 123
providers:
- slug: blink-identity
  name: Blink Identity
  description: Blink Identity is an Austin, Texas company building a privacy-first facial-recognition identity platform for live entertainment venues, stadiums, and public spaces. Its "identify-in-motion" machine-vision system lets patrons enroll with a…
  api_count: 0
  score_band: minimal
  score_composite: 5.8
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
- slug: cvent-registration
  name: Cvent Registration
  description: Cvent Registration is the event registration product within the Cvent Event Cloud, providing online registration websites, attendee data capture, payment processing, registration travel, group registration, custom field collection, and bad…
  api_count: 2
  score_band: exemplar
  score_composite: 76.9
  shared: 2
- slug: drchrono
  name: drchrono
  description: drchrono, part of EverCommerce's EverHealth portfolio, is an all-in-one EHR, practice management and medical billing platform for independent US medical practices. It publishes two distinct machine-readable API surfaces. The proprietary RE…
  api_count: 2
  score_band: exemplar
  score_composite: 76.3
  shared: 2
- slug: okta
  name: Okta
  description: Okta is the workforce identity incumbent — its Identity Cloud platform (also called the Okta Workforce Identity Platform) covers Single Sign-On, Adaptive MFA, Universal Directory, Lifecycle Management, Identity Governance, Privileged Acces…
  api_count: 2
  score_band: exemplar
  score_composite: 75.3
  shared: 2
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 72.6
  shared: 2
- slug: zendesk
  name: Zendesk
  description: Zendesk provides customer service and engagement software that helps businesses manage support tickets, automate workflows, and offer multi-channel supportincluding email, chat, social media, and phonethrough a unified platform.
  api_count: 76
  score_band: exemplar
  score_composite: 72.2
  shared: 2
- slug: tvarka
  name: Tvarka ATK API
  description: A single REST API estate for Lithuanian eID authentication and qualified electronic signing (QES). The ATK API reads the Lithuanian identity card itself - physical smart-card reader or NFC phone tap - through one request, polling, webhook…
  api_count: 4
  score_band: exemplar
  score_composite: 70.1
  shared: 2
- slug: strivacity
  name: Strivacity
  description: Strivacity is a customer identity and access management (CIAM) vendor that runs a single-tenant, dedicated-cloud identity platform for consumer, partner, B2B and — since its Agentic AI release — AI-agent identities. The product covers regi…
  api_count: 12
  score_band: exemplar
  score_composite: 67.9
  shared: 2
- slug: amazon-cognito
  name: Amazon Cognito
  description: Amazon Cognito is a fully managed AWS user identity and authentication service that adds sign-up, sign-in, and access control to web and mobile applications, scaling to millions of users. It provides User Pools for authentication (user dir…
  api_count: 2
  score_band: exemplar
  score_composite: 67.0
  shared: 2
- slug: microsoft-graph
  name: Microsoft Graph
  description: Microsoft Graph is the gateway to data and intelligence in Microsoft 365. It provides a unified programmability model that you can use to access data in Microsoft 365, Windows 10, and Enterprise Mobility + Security.
  api_count: 71
  score_band: strong
  score_composite: 63.5
  shared: 2
- slug: propelauth
  name: PropelAuth
  description: PropelAuth is a B2B SaaS authentication and multi-tenant user management platform purpose-built for organizations that sell to other organizations. It provides hosted login UIs, first-class organizations / tenants with custom roles and per…
  api_count: 3
  score_band: strong
  score_composite: 63.2
  shared: 2
- slug: barndoor
  name: Barndoor
  description: Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security,…
  api_count: 1
  score_band: strong
  score_composite: 62.0
  shared: 2
- slug: stytch
  name: Stytch
  description: Stytch is an authentication and identity infrastructure provider. Its Consumer and B2B APIs cover passwordless authentication (Magic Links, OTP, OAuth, WebAuthn / Passkeys, TOTP), enterprise SSO (SAML / OIDC) and SCIM, sessions, M2M client…
  api_count: 3
  score_band: strong
  score_composite: 61.4
  shared: 2
- slug: entergram
  name: Entergram
  description: Entergram is a CRM built specifically for Telegram. It connects personal Telegram accounts (not bots) into a shared team workspace where sales, support, community and trading teams manage conversations at scale — a multi-account inbox, a C…
  api_count: 1
  score_band: strong
  score_composite: 61.0
  shared: 2
- slug: transmit-security
  name: Transmit Security
  description: Transmit Security provides the Mosaic platform, a comprehensive CIAM (Customer Identity and Access Management) solution offering REST APIs for passkey and WebAuthn authentication, fraud detection and risk-based access control, identity orc…
  api_count: 7
  score_band: strong
  score_composite: 59.9
  shared: 2
- slug: microsoft-entra
  name: Microsoft Entra
  description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management services including authentication, authorization, and directory services.
  api_count: 1
  score_band: strong
  score_composite: 58.5
  shared: 2
- slug: appdirect
  name: AppDirect
  description: AppDirect is a subscription commerce platform that powers B2B digital marketplaces, billing, provisioning, and reseller/distribution channels for millions of cloud subscriptions worldwide. Its developer platform exposes OAuth 2.0-authentic…
  api_count: 2
  score_band: strong
  score_composite: 58.0
  shared: 2
- slug: unico
  name: Unico
  description: Unico (unico IDtech) is a Brazilian identity-technology company whose IDCloud platform performs facial-biometric identity verification, liveness detection, document capture and OCR, and fraud-risk decisioning for customer onboarding, step-…
  api_count: 3
  score_band: strong
  score_composite: 57.7
  shared: 2
- slug: amazon-iam
  name: Amazon IAM
  description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their acces…
  api_count: 1
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: beyond-identity
  name: Beyond Identity
  description: Beyond Identity is a zero-trust passwordless authentication platform that eliminates passwords by binding credentials to physical devices using platform authenticators and cryptographic passkeys. The platform provides REST APIs for managin…
  api_count: 2
  score_band: strong
  score_composite: 56.7
  shared: 2
- slug: descope
  name: Descope
  description: Descope is a customer and agentic identity access management (CIAM) platform founded in 2022 by veterans of Sentrigo and Demisto (acquired by Palo Alto Networks). Its signature is drag-and-drop Descope Flows — a visual authentication-flow…
  api_count: 1
  score_band: strong
  score_composite: 56.4
  shared: 2
- slug: yubico
  name: Yubico
  description: Yubico is the security company behind the YubiKey hardware authentication device and the inventor of the Yubico One-Time Password (OTP). Its public developer surface centers on YubiCloud, a hosted REST service that verifies Yubico OTPs via…
  api_count: 1
  score_band: strong
  score_composite: 56.4
  shared: 2
- slug: snap
  name: Snap
  description: 'Snap Inc. is the technology company behind Snapchat, Bitmoji, Spectacles, and Lens Studio. Its Snap for Developers program exposes several public APIs and SDKs: the Snapchat Marketing API (Ads API, Ads Gallery API, Conversions API, and Pub…'
  api_count: 4
  score_band: strong
  score_composite: 56.3
  shared: 2
- slug: typingdna
  name: TypingDNA
  description: TypingDNA provides AI-based typing biometrics authentication, recognizing people by how they type on desktop and mobile keyboards. Its RESTful Authentication API enrolls and verifies typing patterns for fraud prevention, account-sharing de…
  api_count: 3
  score_band: strong
  score_composite: 55.3
  shared: 2
- slug: greenhelix-net
  name: Green Helix
  description: 'Green Helix Consulting, LLC builds infrastructure for autonomous AI-agent commerce. Its A2A Commerce Gateway (api.greenhelix.net, v1.4.10) is a single REST API of 137 tools across 16 services: per-agent wallets and metered billing, authori…'
  api_count: 2
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: onecli
  name: Onecli
  description: OneCLI is an open-source credential gateway and identity layer for AI agents. Agents connect to Gmail, GitHub, Slack, AWS, Jira and 50+ other services through a network-layer proxy that injects real API keys and OAuth tokens at request tim…
  api_count: 1
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: clio
  name: Clio
  description: Clio is a cloud-based legal practice management platform used by law firms for matter management, contacts, calendaring, time and billing, trust accounting, document management, tasks, and client communications. The Clio Manage API is a RE…
  api_count: 1
  score_band: developing
  score_composite: 53.3
  shared: 2
- slug: ezoic
  name: ezoic
  description: Ezoic is a website monetization and audience-growth platform for publishers, and a performance advertising marketplace for brands. Publishers integrate EzoicAds (via JavaScript, mobile SDKs for Android/iOS/Flutter/React Native/Unity, or fr…
  api_count: 2
  score_band: developing
  score_composite: 53.1
  shared: 2
---
