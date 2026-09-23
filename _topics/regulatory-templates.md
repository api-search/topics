---
layout: topic
slug: regulatory-templates
name: Regulatory Templates
kind: topic
description: Pre-built templates, frameworks, and policy libraries for meeting regulatory compliance requirements across industries and jurisdictions including GDPR, HIPAA, SOC 2, ISO 27001, PCI DSS, and more. Compliance platforms and API governance tools provide template-driven approaches to accelerate audit readiness, evidence collection, and risk management workflows.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/regulatory-templates.png
tags:
- Compliance
- Governance
- GDPR
- HIPAA
- ISO 27001
- PCI DSS
- Policy Templates
- Regulatory
- SOC 2
- Templates
repo: https://github.com/api-evangelist/regulatory-templates
api_count: 4
apis:
- name: OneTrust API
  description: OneTrust provides a privacy, security, and data governance platform with APIs for automating compliance with GDPR, CCPA, HIPAA, and 50+ regulatory frameworks. Offers pre-built templates for consent management, data subject requests, and ri…
  url: https://developer.onetrust.com/
- name: Vanta API
  description: Vanta automates security compliance for SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The API enables programmatic access to compliance monitoring, evidence collection, and audit preparation workflows with pre-built control templates.
  url: https://developer.vanta.com/
- name: Drata API
  description: Drata is a security and compliance automation platform providing pre-built control frameworks and policy templates for SOC 2, ISO 27001, HIPAA, GDPR, and PCI DSS. The API supports continuous compliance monitoring and evidence collection au…
  url: https://drata.com/
- name: Scrut Automation API
  description: Scrut Automation provides a compliance platform supporting 50+ frameworks including SOC 2, ISO 27001, HIPAA, GDPR, and PCI DSS, with built-in integrations and automated evidence collection through API-driven workflows.
  url: https://www.scrut.io/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/regulatory-templates/blob/main/security/regulatory-templates-domain-security.yml
- type: Website
  url: https://usercentrics.com/knowledge-hub/regulatory-compliance-platform/
- type: Website
  url: https://www.vero-ai.com/blog/regulatory-compliance-software-vendors
- type: Website
  url: https://riskonnect.com/solutions/regulatory-compliance-software/
- type: Website
  url: https://www.speakeasy.com/api-design/api-compliance
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/json-schema/regulatory-templates-control-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/json-structure/regulatory-templates-control-structure.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/json-ld/regulatory-templates-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/vocabulary/regulatory-templates-vocabulary.yml
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/regulatory-templates/refs/heads/main/examples/regulatory-templates-soc2-control-example.json
- type: Integrations
  url: https://usercentrics.com/integrations/
provider_count: 105
providers:
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 80.4
  shared: 4
- slug: heidi-health
  name: Heidi Health
  description: Heidi Health is a Melbourne, Australia-founded AI care partner for clinicians, founded in 2019 by Dr. Tom Kelly (CEO), Waleed Mussa (CFO), and Yu Liu (CTO). The product began as an ambient AI medical scribe and now spans four capability su…
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 4
- slug: google-cloud-assured-workloads
  name: Google Cloud Assured Workloads
  description: Google Cloud Assured Workloads enables organizations to create and manage compliance-controlled environments on Google Cloud. It provides guardrails for regulatory compliance frameworks such as FedRAMP, HIPAA, CJIS, ITAR, and others by enf…
  api_count: 1
  score_band: developing
  score_composite: 43.6
  shared: 4
- slug: carbide
  name: Carbide
  description: Carbide (carbidesecure.com) is a compliance-automation and risk-management platform that pairs software with credentialed security advisors to help fast-growing organizations achieve and maintain security certifications and regulatory comp…
  api_count: 0
  score_band: emerging
  score_composite: 19.5
  shared: 4
- slug: scytale
  name: Scytale
  description: Scytale is an AI-powered Governance, Risk, and Compliance (GRC) platform that automates security compliance for cloud and SaaS companies. It combines AI agents with in-house compliance experts to automate evidence collection, continuous co…
  api_count: 0
  score_band: emerging
  score_composite: 14.3
  shared: 4
- slug: drata
  name: Drata
  description: Drata is a continuous security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, and more, with policies, evidence, and trust center. Drata exposes a public REST API plus the SafeBase Trust API (acquired…
  api_count: 3
  score_band: exemplar
  score_composite: 67.3
  shared: 3
- slug: signwell
  name: SignWell
  description: E-signature platform with a REST API for sending documents for signature, creating templates, tracking document status, and managing signers programmatically. Supports embedded signing, bulk send, webhooks, and white-label customization wi…
  api_count: 1
  score_band: developing
  score_composite: 49.3
  shared: 3
- slug: secureframe
  name: Secureframe
  description: Secureframe automates security and privacy compliance for SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, CMMC, FedRAMP, NIST 800-171 and more. Its Public API is a 112-operation, JSON:API-shaped REST contract over the compliance record of truth —…
  api_count: 1
  score_band: developing
  score_composite: 48.8
  shared: 3
- slug: inkit
  name: Inkit
  description: Inkit is a Secure Document Generation (SDG) platform that enables organizations to generate, sign, store, and distribute documents in total privacy. The platform provides a REST API for rendering HTML templates into PDFs, automating docume…
  api_count: 1
  score_band: developing
  score_composite: 48.4
  shared: 3
- slug: ketryx
  name: Ketryx
  description: Ketryx is an AI-native application lifecycle management (ALM) and compliance platform for regulated medical-device and life-sciences software teams. It integrates with developer tools such as Jira and GitHub to automate the documentation,…
  api_count: 1
  score_band: thin
  score_composite: 35.5
  shared: 3
- slug: wordsmith
  name: Wordsmith
  description: Wordsmith is an Edinburgh-based legal AI platform built for in-house legal teams, marketed as a Slack-native legal copilot that lets non-legal staff self-serve compliant answers, templates, and contract reviews directly in the tools they a…
  api_count: 2
  score_band: emerging
  score_composite: 16.2
  shared: 3
- slug: sprinto
  name: Sprinto
  description: Sprinto is a security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, GDPR, PCI DSS, and more. Sprinto offers an API for building custom compliance and risk workflows; specific public reference docs are limited and r…
  api_count: 1
  score_band: emerging
  score_composite: 14.3
  shared: 3
- slug: tugboat-logic
  name: Tugboat Logic
  description: Tugboat Logic is a security assurance and compliance automation platform acquired by OneTrust in 2021. It supports SOC 2, ISO 27001, HIPAA, GDPR, and NIST. As of 2024, the product has been rebranded under OneTrust's Certification Automatio…
  api_count: 1
  score_band: emerging
  score_composite: 11.8
  shared: 3
- slug: innovatrix-tech-corp
  name: Innovatrix Tech, Corp.
  description: Innovatrix Tech, Corp. operates Sahl (getsahl.io), an AI-powered Governance, Risk, and Compliance (GRC) platform built in the MENA region for MENA organizations. Sahl automates policy generation, control mapping, risk assessment, evidence…
  api_count: 0
  score_band: minimal
  score_composite: 7.7
  shared: 3
- slug: auditocity
  name: Auditocity
  description: Auditocity is an HR compliance software platform that helps organizations of any size master regulatory requirements and best practices. It maintains a library of more than 14,000 questions spanning federal, state, and industry-specific HR…
  api_count: 0
  score_band: minimal
  score_composite: 7.6
  shared: 3
- slug: paubox
  name: Paubox
  description: Paubox is a HIPAA compliant, HITRUST certified email infrastructure company serving healthcare organizations in the United States. Its products encrypt outbound email without recipient portals, passwords, or plugins, and work alongside Goo…
  api_count: 3
  score_band: exemplar
  score_composite: 71.5
  shared: 2
- slug: 123formbuilder
  name: 123FormBuilder
  description: 123FormBuilder is an online form, survey, and workflow builder used to collect, route, and integrate submission data across websites, customer portals, and back-office systems with no-code design and HIPAA-ready configurations. The 123Form…
  api_count: 1
  score_band: strong
  score_composite: 64.2
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
- slug: synthflow
  name: Synthflow
  description: Synthflow is an enterprise-ready no-code Voice AI platform for automating phone conversations at scale. The product combines a visual agent designer with in-house telephony, sub-100ms latency, and a 99.99% uptime guarantee, so businesses c…
  api_count: 1
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: aptible
  name: Aptible
  description: Aptible is a Platform as a Service (PaaS) built for teams that have to prove security and compliance, not just ship. It deploys web apps, managed databases (PostgreSQL, MySQL, Redis, Elasticsearch, InfluxDB, RabbitMQ, SFTP) and AI workload…
  api_count: 3
  score_band: strong
  score_composite: 56.9
  shared: 2
- slug: amazon-config
  name: Amazon Config
  description: AWS Config provides a detailed view of the configuration of AWS resources in your AWS account. This includes how the resources are related to one another and how they were configured in the past, enabling assessment, auditing, and evaluati…
  api_count: 1
  score_band: strong
  score_composite: 55.2
  shared: 2
- slug: osano
  name: Osano
  description: Osano is a data privacy platform, founded in 2018 and headquartered in Austin, Texas, that helps organizations build and run privacy programs across consent management, subject rights (DSAR) automation, data mapping and discovery, privacy…
  api_count: 4
  score_band: strong
  score_composite: 54.5
  shared: 2
- slug: amazon-cloudtrail
  name: Amazon CloudTrail
  description: AWS CloudTrail enables governance, compliance, operational auditing, and risk auditing of your AWS account by tracking user activity and API usage across AWS environments, hybrid setups, and multicloud deployments with immutable audit trai…
  api_count: 1
  score_band: strong
  score_composite: 54.3
  shared: 2
- slug: transcend-io
  name: Transcend
  description: Transcend is a privacy and data permissioning platform that helps enterprises decide in real time whether customer data can be used for a given purpose. The platform spans data discovery and inventory, data subject request automation, cons…
  api_count: 1
  score_band: developing
  score_composite: 54.1
  shared: 2
- slug: formassembly
  name: FormAssembly
  description: FormAssembly is an enterprise form and data collection platform with a REST API for managing forms, exporting submission data, handling Salesforce integrations, and building compliant data collection workflows. The API supports OAuth2 auth…
  api_count: 1
  score_band: developing
  score_composite: 53.9
  shared: 2
- slug: qualio
  name: Qualio
  description: Qualio is an AI-powered quality management system (QMS) and compliance platform built for life sciences companies — medical devices, pharmaceuticals, biotech, software as a medical device (SaMD), cosmetics, cannabis and contract research o…
  api_count: 1
  score_band: developing
  score_composite: 52.8
  shared: 2
- slug: trustarc
  name: TrustArc
  description: TrustArc is a Walnut Creek, California enterprise privacy management platform that helps organizations operationalize global data privacy programs. Its product portfolio spans three suites. Privacy Studio covers consumer-facing consent and…
  api_count: 2
  score_band: developing
  score_composite: 52.7
  shared: 2
- slug: enable-banking
  name: Enable Banking
  description: Enable Banking is a Finland-based Open Banking connectivity engine and licensed PSD2 Account Information Service Provider (AISP) regulated by the Finnish Financial Supervisory Authority (FIN-FSA). Headquartered in Espoo, Enable Banking pro…
  api_count: 1
  score_band: developing
  score_composite: 50.9
  shared: 2
- slug: singlefile
  name: SingleFile
  description: SingleFile is an AI-powered entity management and corporate compliance platform for corporations, law firms, and investment organizations. It automates business entity formation, EIN filing, annual report filing, registered agent services,…
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 2
---
