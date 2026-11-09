---
layout: topic
slug: ocra
name: OCRA
kind: concept
description: OCRA (OATH Challenge-Response Algorithm) is a standard for generating one-time passwords based on challenge-response authentication as defined in RFC 6287. It extends HOTP and TOTP with challenge-response capabilities for stronger authentication scenarios.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ocra.png
tags:
- Authentication
- OCRA
- OTP
- Security
area: security
repo: https://github.com/api-evangelist/ocra
api_count: 0
apis: []
links:
- type: Reference
  url: https://datatracker.ietf.org/doc/html/rfc6287
provider_count: 70
providers:
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 75.9
  shared: 2
- slug: strivacity
  name: Strivacity
  description: Strivacity is a customer identity and access management (CIAM) vendor that runs a single-tenant, dedicated-cloud identity platform for consumer, partner, B2B and — since its Agentic AI release — AI-agent identities. The product covers regi…
  api_count: 8
  score_band: exemplar
  score_composite: 74.2
  shared: 2
- slug: microsoft-entra
  name: Microsoft Entra
  description: Microsoft Entra (formerly Azure Active Directory) is Microsoft's family of identity and network access products, providing authentication, authorization, directory, identity governance, external identities, verifiable credentials and secur…
  api_count: 1
  score_band: exemplar
  score_composite: 73.9
  shared: 2
- slug: clerk-com
  name: Clerk
  description: Clerk is a complete user management and authentication infrastructure platform offering embeddable UI components, flexible APIs, and admin dashboards. It provides full-stack authentication including multi-factor authentication, social sign…
  api_count: 8
  score_band: exemplar
  score_composite: 72.2
  shared: 2
- slug: auth0
  name: Auth0
  description: Auth0 (now part of Okta) is a leading identity-as-a-service platform providing authentication and authorization for applications, APIs, and AI agents. It implements OpenID Connect, OAuth 2.0, SAML 2.0, WS-Federation, and SCIM, and exposes…
  api_count: 4
  score_band: exemplar
  score_composite: 72.1
  shared: 2
- slug: cisco-xdr
  name: Cisco XDR
  description: Cisco XDR is Cisco's extended detection and response platform, the successor to SecureX. It correlates telemetry from Cisco Secure Endpoint, Secure Firewall, Umbrella, Duo, Secure Email and third-party sources into incidents, and exposes f…
  api_count: 12
  score_band: exemplar
  score_composite: 69.9
  shared: 2
- slug: typingdna
  name: TypingDNA
  description: TypingDNA provides AI-based typing biometrics authentication, recognizing people by how they type on desktop and mobile keyboards. Its RESTful Authentication API enrolls and verifies typing patterns for fraud prevention, account-sharing de…
  api_count: 3
  score_band: strong
  score_composite: 64.7
  shared: 2
- slug: stytch
  name: Stytch
  description: Stytch is an authentication and identity infrastructure provider. Its Consumer and B2B APIs cover passwordless authentication (Magic Links, OTP, OAuth, WebAuthn / Passkeys, TOTP), enterprise SSO (SAML / OIDC) and SCIM, sessions, M2M client…
  api_count: 3
  score_band: strong
  score_composite: 62.4
  shared: 2
- slug: amazon-iam
  name: Amazon IAM
  description: Amazon Identity and Access Management (IAM) enables you to manage access to AWS services and resources securely. Using IAM, you can create and manage AWS users, groups, roles, and policies, and use permissions to allow and deny their acces…
  api_count: 1
  score_band: strong
  score_composite: 59.0
  shared: 2
- slug: barndoor
  name: Barndoor
  description: Barndoor AI is the control plane for agentic AI, providing secure access and governance for AI agents and Model Context Protocol (MCP) servers. Founded in 2024 by Oren Michels (founder of Mashery), Barndoor enables enterprise IT, security,…
  api_count: 1
  score_band: strong
  score_composite: 59.0
  shared: 2
- slug: yubico
  name: Yubico
  description: Yubico is the security company behind the YubiKey hardware authentication device and the inventor of the Yubico One-Time Password (OTP). Its public developer surface centers on YubiCloud, a hosted REST service that verifies Yubico OTPs via…
  api_count: 1
  score_band: strong
  score_composite: 58.3
  shared: 2
- slug: google-cloud-api-gateway
  name: Google Cloud API Gateway
  description: Google Cloud API Gateway enables you to provide secure access to your backend services through a well-defined REST API that is consistent across all of your services. It is a fully managed, pay-per-use gateway designed for serverless workl…
  api_count: 1
  score_band: strong
  score_composite: 56.2
  shared: 2
- slug: onecli
  name: Onecli
  description: OneCLI is an open-source credential gateway and identity layer for AI agents. Agents connect to Gmail, GitHub, Slack, AWS, Jira and 50+ other services through a network-layer proxy that injects real API keys and OAuth tokens at request tim…
  api_count: 1
  score_band: strong
  score_composite: 56.0
  shared: 2
- slug: spycloud
  name: SpyCloud
  description: SpyCloud is an Austin, Texas based identity threat protection company that operates one of the largest repositories of recaptured darknet data — breach records, infostealer malware logs, phishing captures and combolists — and exposes it pr…
  api_count: 9
  score_band: strong
  score_composite: 55.8
  shared: 2
- slug: transmit-security
  name: Transmit Security
  description: Transmit Security provides the Mosaic platform, a comprehensive CIAM (Customer Identity and Access Management) solution offering REST APIs for passkey and WebAuthn authentication, fraud detection and risk-based access control, identity orc…
  api_count: 7
  score_band: strong
  score_composite: 55.2
  shared: 2
- slug: centrify
  name: Centrify
  description: Centrify is an identity and privileged access management (PAM) platform now delivered as part of Delinea (the company formed from the Centrify + Thycotic merger). The Centrify Identity Platform / Cloud Suite / Privileged Access Service sec…
  api_count: 15
  score_band: strong
  score_composite: 54.9
  shared: 2
- slug: eagle-eye-networks
  name: Eagle Eye Networks
  description: Eagle Eye Networks is a cloud video surveillance and video management system (VMS) provider whose Video API Platform (v3) exposes REST APIs for managing bridges, cameras, speakers, switches and multi-cameras; streaming live and recorded vi…
  api_count: 23
  score_band: developing
  score_composite: 53.3
  shared: 2
- slug: trusona
  name: Trusona
  description: Trusona is a Scottsdale, Arizona identity impersonation detection company founded in 2015 by fraud-prevention expert Ori Eisen, funded by Kleiner Perkins and advised by Frank Abagnale. Its ATO Protect suite verifies that the person behind…
  api_count: 2
  score_band: developing
  score_composite: 53.1
  shared: 2
- slug: civic
  name: Civic
  description: Civic is a digital identity and security platform offering authentication, identity verification, and AI agent security infrastructure. Core products include Civic Hub (a Model Context Protocol gateway with guardrails, audit logging, secre…
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 2
- slug: allegion
  name: Allegion
  description: Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Porta…
  api_count: 2
  score_band: developing
  score_composite: 52.9
  shared: 2
- slug: 1kosmos
  name: 1Kosmos
  description: 1Kosmos is a digital identity company whose BlockID platform combines identity proofing, document and biometric verification, and passwordless / FIDO2 authentication into a single tenant-scoped platform used across workforce, customer and…
  api_count: 1
  score_band: developing
  score_composite: 51.9
  shared: 2
- slug: defakto-security
  name: Defakto Security
  description: Defakto (formerly SPIRL) is a non-human identity (NHI) security company that issues short-lived, cryptographically attested identities to workloads, services, CI/CD pipelines and AI agents in place of static secrets, API keys and long-live…
  api_count: 2
  score_band: developing
  score_composite: 48.1
  shared: 2
- slug: dust-identity
  name: Dust Identity
  description: DUST Identity (Newton, Massachusetts; founded 2018 as an MIT spinout) binds physical objects to trusted digital records using the Diamond Unclonable Security Tag — an applied coating of engineered nano-diamonds in a polymer matrix that for…
  api_count: 1
  score_band: developing
  score_composite: 48.0
  shared: 2
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 42.6
  shared: 2
- slug: spire
  name: SPIRE
  description: SPIRE (SPIFFE Runtime Environment) is the reference implementation of the SPIFFE standard, providing a toolchain for establishing trust between software systems across a wide variety of hosting platforms through automated attestation and w…
  api_count: 2
  score_band: developing
  score_composite: 42.4
  shared: 2
- slug: cakewalk
  name: Cakewalk
  description: Cakewalk is the agentic access management platform for fast-moving companies, combining a granular identity governance and administration (IGA) platform with AI-driven workflows. Cakewalk governs access for both human identities and AI age…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 2
- slug: agentsim-dev
  name: AgentSIM
  description: AgentSIM provides operational identity for agents hitting authentication walls. It lets you verify apps you own, run live SMS challenges, and return a code or safe stop into the agent workflow, enabling seamless integration of auth decisio…
  api_count: 1
  score_band: developing
  score_composite: 41.3
  shared: 2
- slug: slashid
  name: SlashID
  description: SlashID is a developer-first identity platform that provides REST APIs for passwordless authentication, multi-factor authentication, passkeys, and comprehensive user management across web and mobile applications. The platform offers three…
  api_count: 1
  score_band: developing
  score_composite: 41.0
  shared: 2
- slug: capy-inc
  name: Capy Inc.
  description: Capy Inc. operates Lemin Captcha, a gamified bot-prevention and CAPTCHA service that replaces traditional image-selection challenges with playful, brandable puzzle games. Lemin protects websites and apps from automated attacks such as acco…
  api_count: 1
  score_band: thin
  score_composite: 38.9
  shared: 2
- slug: apache-knox
  name: Apache Knox
  description: Apache Knox is a REST API and application gateway for the Apache Hadoop ecosystem. It provides a single access point for all REST and HTTP interactions with Apache Hadoop clusters, with authentication, authorization, SSO, and audit capabil…
  api_count: 1
  score_band: thin
  score_composite: 38.8
  shared: 2
---
