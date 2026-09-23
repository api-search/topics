---
layout: topic
slug: hipaa
name: HIPAA
kind: topic
description: HIPAA (Health Insurance Portability and Accountability Act) is U.S. legislation providing data privacy and security provisions for safeguarding medical information. HIPAA compliance is required for healthcare providers, health plans, and their business associates handling protected health information (PHI).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/hipaa.png
tags:
- Compliance
- Healthcare
- Privacy
- Security
repo: https://github.com/api-evangelist/hipaa
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/hipaa/blob/main/security/hipaa-domain-security.yml
- type: Website
  url: https://www.hhs.gov/hipaa/index.html
- type: Reference
  url: https://www.hhs.gov/hipaa/for-professionals/index.html
provider_count: 217
providers:
- slug: paubox
  name: Paubox
  description: Paubox is a HIPAA compliant, HITRUST certified email infrastructure company serving healthcare organizations in the United States. Its products encrypt outbound email without recipient portals, passwords, or plugins, and work alongside Goo…
  api_count: 3
  score_band: exemplar
  score_composite: 71.5
  shared: 3
- slug: onetrust
  name: OneTrust
  description: OneTrust is an enterprise trust, privacy, and AI-governance platform. Its developer portal publishes 37 downloadable OpenAPI definitions covering roughly 631 operations across Universal Consent & Preference Management, Cookie Consent / CMP…
  api_count: 37
  score_band: strong
  score_composite: 65.6
  shared: 3
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 43.7
  shared: 3
- slug: blindinsight
  name: BlindInsight
  description: BlindInsight (Blind Insight) is an end-to-end encrypted datastore and privacy-preserving data-analysis platform. It lets teams encrypt, ingest, search, and run machine learning and LLM queries over fully encrypted records without ever expo…
  api_count: 1
  score_band: thin
  score_composite: 36.5
  shared: 3
- slug: truevault
  name: TrueVault
  description: TrueVault provides developer infrastructure for storing and managing sensitive personal data in a compliant way. Its original product, TrueVault Safe, is a HIPAA-oriented REST API and secure datastore that lets applications create Vaults a…
  api_count: 1
  score_band: thin
  score_composite: 31.4
  shared: 3
- slug: odaseva
  name: Odaseva
  description: Odaseva is an enterprise data security, backup, and governance platform purpose-built for large, complex Salesforce environments. It provides data backup and recovery, archiving, seeding and anonymization/masking, encryption and key manage…
  api_count: 0
  score_band: emerging
  score_composite: 22.5
  shared: 3
- slug: privado
  name: Privado
  description: Privado (Privado.ai) is a privacy engineering and data-privacy compliance company that helps engineering and privacy teams build privacy-first products. Its flagship is an open-source static code-analysis scanner that detects personal-data…
  api_count: 0
  score_band: emerging
  score_composite: 20.9
  shared: 3
- slug: feroot
  name: Feroot
  description: Feroot Security is a Toronto-based cybersecurity company providing AI-powered client-side (browser) security and compliance automation for websites and mobile apps. Its platform gives organizations visibility into the third-party JavaScrip…
  api_count: 0
  score_band: emerging
  score_composite: 17.7
  shared: 3
- slug: lightbeam-ai
  name: Lightbeam
  description: Lightbeam is an AI data security and guardrails platform that discovers and classifies sensitive data across cloud, SaaS and on-premises systems, ties that data to identity and access context through its Data Identity Graph, and enforces g…
  api_count: 0
  score_band: emerging
  score_composite: 12.9
  shared: 3
- slug: privacy-by-design
  name: Privacy by Design
  description: Privacy By Design is a framework and approach that embeds privacy protections into the design and operation of IT systems, networked infrastructure, and business practices from the ground up, rather than as an afterthought.
  api_count: 0
  score_band: minimal
  score_composite: 5.3
  shared: 3
- slug: dasera
  name: Dasera
  description: Dasera is a data security company in the data security posture management (DSPM) and data governance space, founded by Ani Chaudhuri and backed by Sierra Ventures. Its platform was built to continuously discover, classify, and monitor sens…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: drata
  name: Drata
  description: Drata is a continuous security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, and more, with policies, evidence, and trust center. Drata exposes a public REST API plus the SafeBase Trust API (acquired…
  api_count: 3
  score_band: exemplar
  score_composite: 67.3
  shared: 2
- slug: spruce-health
  name: Spruce Health
  description: Spruce Health is a HIPAA-compliant healthcare communication platform that unifies phone, SMS, secure messaging, video, e-fax, team chat, mobile payments and VoIP phone lines into one system for medical practices, with AI-enabled voicemail…
  api_count: 16
  score_band: strong
  score_composite: 64.2
  shared: 2
- slug: anecdotes
  name: anecdotes
  description: anecdotes is an enterprise Governance, Risk and Compliance (GRC) platform, founded in 2020 and headquartered in Tel Aviv, that pairs a GRC data engine with AI agents to replace point-in-time audit cycles with continuous, evidence-backed co…
  api_count: 3
  score_band: strong
  score_composite: 63.1
  shared: 2
- slug: datavant
  name: Datavant
  description: Datavant is a United States health-data logistics company, formed from the 2021 merger of Datavant and Ciox Health, that connects and de-identifies healthcare data across a "network of networks" spanning 350+ real-world data partners, 80,0…
  api_count: 2
  score_band: strong
  score_composite: 61.3
  shared: 2
- slug: atomadic-tech
  name: Atomadic Tech
  description: 'Atomadic Tech operates AAAA-Nexus, an "agent control plane" for autonomous AI agents: a 149-operation REST API on atomadic.tech covering security and threat scoring, trust and reputation oracles, agent-to-agent escrow, SLA enforcement, EU…'
  api_count: 1
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: medtrainer
  name: MedTrainer
  description: MedTrainer is a healthcare workforce compliance software company that consolidates learning management, credentialing and provider enrollment, document and policy management, incident reporting, safety plans, contract management and exclus…
  api_count: 1
  score_band: strong
  score_composite: 60.1
  shared: 2
- slug: verifiable
  name: Verifiable
  description: Verifiable is an API-first provider network management and credentialing platform for healthcare. Its RESTful API lets health plans, credentialing vendors, and digital health companies programmatically manage provider and facility records,…
  api_count: 2
  score_band: strong
  score_composite: 58.8
  shared: 2
- slug: fraud-net
  name: Fraud.net
  description: 'Fraud.net (FraudNet) is an enterprise fraud, risk and compliance platform used by payment processors, acquirers, PSPs, fintechs, banks and digital commerce platforms. Its Public API is a risk-decisioning surface: Check operations submit a…'
  api_count: 2
  score_band: strong
  score_composite: 58.1
  shared: 2
- slug: amazon-iam-access-analyzer
  name: Amazon IAM Access Analyzer
  description: AWS IAM Access Analyzer helps you set, verify, and refine your IAM policies by providing a suite of capabilities including findings for external, internal, and unused access, basic and custom policy checks for validating policies, and poli…
  api_count: 1
  score_band: strong
  score_composite: 57.5
  shared: 2
- slug: amazon-guardduty
  name: Amazon GuardDuty
  description: Amazon GuardDuty is an intelligent threat detection service that continuously monitors your AWS accounts, workloads, and data for malicious activity. It uses machine learning, anomaly detection, and integrated threat intelligence to identi…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: amazon-iot-device-defender
  name: Amazon IoT Device Defender
  description: AWS IoT Device Defender is a security service that lets you continuously audit your IoT configurations to detect deviations from security best practices. It also lets you detect abnormal device behavior through ML-based anomaly detection a…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: chef-software
  name: Chef Software
  description: Chef Software is the DevOps automation company behind Chef Infra, Chef InSpec, Chef Habitat, and Chef Automate, now part of Progress Software. Chef pioneered infrastructure-as-code, letting teams define, deploy, and continuously enforce th…
  api_count: 24
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: aptible
  name: Aptible
  description: Aptible is a Platform as a Service (PaaS) built for teams that have to prove security and compliance, not just ship. It deploys web apps, managed databases (PostgreSQL, MySQL, Redis, Elasticsearch, InfluxDB, RabbitMQ, SFTP) and AI workload…
  api_count: 3
  score_band: strong
  score_composite: 56.9
  shared: 2
- slug: amazon-firewall-manager
  name: Amazon Firewall Manager
  description: AWS Firewall Manager is a security management service that allows you to centrally configure and manage firewall rules across your accounts and applications in AWS Organizations. It makes it easier to bring new applications and resources i…
  api_count: 1
  score_band: strong
  score_composite: 56.7
  shared: 2
- slug: credentially
  name: Credentially
  description: Credentially is a UK-founded, healthcare-only onboarding and compliance automation platform used by NHS trusts, private providers, urgent care and clinical staffing agencies in the UK and US. It brings pre-employment checks, DBS and right-…
  api_count: 2
  score_band: strong
  score_composite: 55.8
  shared: 2
- slug: sailpoint
  name: SailPoint
  description: Enterprise identity security and governance platform providing identity management, access governance, and compliance solutions for workforce and non-employee identities. SailPoint delivers cloud-native IAM, certification automation, role…
  api_count: 1
  score_band: strong
  score_composite: 55.3
  shared: 2
- slug: amazon-config
  name: Amazon Config
  description: AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past, enabling assessment, auditing, and evaluati…
  api_count: 1
  score_band: strong
  score_composite: 55.2
  shared: 2
- slug: freshpaint
  name: Freshpaint
  description: Freshpaint is a healthcare privacy platform and customer-data platform that collects first-party event data and governs it for HIPAA compliance before fanning it out to 100+ marketing, analytics, and data destinations. Its server-side HTTP…
  api_count: 1
  score_band: strong
  score_composite: 55.1
  shared: 2
- slug: cisco-psirt
  name: Cisco PSIRT openVuln API
  description: The Cisco Product Security Incident Response Team (PSIRT) openVuln API is Cisco's machine-readable vulnerability disclosure service. It lets security teams query Cisco security advisories by CVE, advisory ID, severity, publication date, af…
  api_count: 1
  score_band: strong
  score_composite: 55.0
  shared: 2
---
