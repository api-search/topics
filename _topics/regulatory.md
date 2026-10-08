---
layout: topic
slug: regulatory
name: Regulatory
kind: topic
description: The regulatory domain encompasses compliance requirements, regulatory reporting, and governance frameworks that organizations must adhere to across industries. APIs in this space enable businesses to automate compliance workflows, track regulatory changes, submit required filings, and manage risk. Key sectors include financial services (SEC, FINRA, CFTC), healthcare (FDA, CMS), telecommunications (FCC), and environmental regulation (EPA).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/regulatory.png
tags:
- Compliance
- Financial Services
- Governance
- Healthcare Regulation
- Regulatory Reporting
- Risk Management
- RegTech
repo: https://github.com/api-evangelist/regulatory
api_count: 8
apis:
- name: Compliance.ai API
  description: Compliance.ai automatically aggregates regulatory data from Federal and State agencies, enforcement actions, regulatory publications, and millions of rules, providing an API for financial institutions and GRC platforms to stay current on r…
  url: https://www.compliance.ai/api/
- name: Regology API
  description: Regology is an AI-powered global regulatory compliance platform providing APIs for regulatory research, change management, and compliance workflows. Aggregates and organizes regulatory content from thousands of global sources.
  url: https://regology.com/
- name: LSEG Risk and Regulatory Compliance API
  description: London Stock Exchange Group (LSEG) offers a developer portal with APIs for risk and regulatory compliance including sanctions screening, KYC/AML checks, and regulatory reporting tools used by financial institutions globally.
  url: https://developers.lseg.com/en/use-cases-catalog/risk-regulatory-compliance
- name: Regulatory Async API
  description: Asynchronous query operations.
  url: https://developer.finra.org/
- name: Regulatory Data API
  description: Querying records from datasets.
  url: https://developer.finra.org/
- name: Regulatory Datasets API
  description: Dataset discovery and listing.
  url: https://developer.finra.org/
- name: Regulatory Metadata API
  description: Field-level metadata for datasets.
  url: https://developer.finra.org/
- name: Regulatory Partitions API
  description: Partition values for datasets.
  url: https://developer.finra.org/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/regulatory/blob/main/agentic-access/regulatory-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/regulatory/blob/main/security/regulatory-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/regulatory/blob/main/authentication/regulatory-authentication.yml
- type: Website
  url: https://developer.finra.org/
- type: Website
  url: https://www.compliance.ai/api/
- type: Website
  url: https://regology.com/
- type: Website
  url: https://developers.lseg.com/en/use-cases-catalog/risk-regulatory-compliance
- type: Website
  url: https://www.regulativ.ai/
- type: Website
  url: https://nordicapis.com/10-data-regulations-all-api-developers-should-know-about/
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-schema/regulatory-compliance-check-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-structure/regulatory-compliance-check-structure.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/json-ld/regulatory-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/vocabulary/regulatory-vocabulary.yml
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/regulatory/refs/heads/main/examples/regulatory-compliance-check-finra-example.json
provider_count: 233
providers:
- slug: greenboard
  name: Greenboard
  description: Greenboard is an AI-native compliance software platform for SEC- and FINRA-regulated financial institutions, consolidating communications archiving, employee compliance monitoring, marketing/advertising review, firm-wide compliance managem…
  api_count: 0
  score_band: emerging
  score_composite: 12.0
  shared: 5
- slug: fenergo
  name: Fenergo
  description: Fenergo is an Irish-headquartered financial-services SaaS vendor whose Fen-X platform delivers Client Lifecycle Management (CLM), Know Your Customer (KYC), AML screening, client onboarding, transaction monitoring and regulatory compliance…
  api_count: 145
  score_band: strong
  score_composite: 62.3
  shared: 4
- slug: metricstream
  name: MetricStream
  description: MetricStream is a San Jose, California based enterprise software company and a market leader in integrated Governance, Risk, and Compliance (GRC) management, serving large regulated organizations across banking and financial services, insu…
  api_count: 8
  score_band: thin
  score_composite: 31.7
  shared: 4
- slug: emtech
  name: EMTECH
  description: EMTECH is a financial-technology company founded in 2019 that modernizes financial market infrastructure for central banks, financial regulators, and financial service providers. Its Beyond Suite delivers regulatory sandbox management (Bey…
  api_count: 0
  score_band: thin
  score_composite: 30.8
  shared: 4
- slug: acin
  name: Acin
  description: Acin is a London-based operational and non-financial risk (NFR) data company for financial services, founded in 2018 and acquired by regulatory-intelligence firm CUBE in June 2025. Its platform ingests a bank's process, risk and control in…
  api_count: 1
  score_band: thin
  score_composite: 27.7
  shared: 4
- slug: hadrius
  name: Hadrius
  description: Hadrius is an AI-native compliance platform for SEC- and FINRA-regulated financial firms, including broker-dealers, registered investment advisors (RIAs), private funds, and compliance consultants. The platform consolidates multiple compli…
  api_count: 0
  score_band: emerging
  score_composite: 14.4
  shared: 4
- slug: anecdotes
  name: anecdotes
  description: anecdotes is an enterprise Governance, Risk and Compliance (GRC) platform, founded in 2020 and headquartered in Tel Aviv, that pairs a GRC data engine with AI agents to replace point-in-time audit cycles with continuous, evidence-backed co…
  api_count: 3
  score_band: strong
  score_composite: 64.0
  shared: 3
- slug: spektr
  name: Spektr
  description: Spektr is an AI-powered compliance automation platform for banks and fintechs, backed by Northzone and Seedcamp. It automates KYB and KYC onboarding, continuous customer monitoring, risk scoring, remediation, and transaction monitoring usi…
  api_count: 1
  score_band: developing
  score_composite: 50.7
  shared: 3
- slug: vanta
  name: Vanta
  description: Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate…
  api_count: 2
  score_band: developing
  score_composite: 48.8
  shared: 3
- slug: openpages
  name: OpenPages
  description: IBM OpenPages is an AI-driven, unified governance, risk, and compliance (GRC) platform delivered as a managed service on IBM Cloud. Originally founded as OpenPages Inc. (a Matrix Partners portfolio company) and acquired by IBM in 2010, it…
  api_count: 1
  score_band: developing
  score_composite: 47.7
  shared: 3
- slug: wegalvanize
  name: Wegalvanize
  description: Wegalvanize.com is the former web home of Galvanize, the governance, risk, and compliance (GRC) software company behind the HighBond platform; Galvanize was acquired by Diligent and wegalvanize.com now redirects to diligent.com. The HighBo…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 3
- slug: venminder-digital-comply
  name: Venminder (Digital Comply)
  description: Venminder is a third-party risk management (TPRM) platform for financial institutions — vendor onboarding, due diligence, contract tracking, questionnaires, oversight tasks, issue tracking, spend analysis and Venmonitor continuous monitori…
  api_count: 1
  score_band: developing
  score_composite: 45.5
  shared: 3
- slug: green-check-verified
  name: Green Check Verified
  description: Green Check Verified (Green Check) is a New Haven, Connecticut specialty-banking compliance platform founded in 2017 that sits between financial institutions and the cannabis and other cash-intensive businesses they serve. Banks and credit…
  api_count: 1
  score_band: developing
  score_composite: 42.4
  shared: 3
- slug: merkle-science
  name: Merkle Science
  description: Merkle Science is a blockchain analytics and predictive crypto risk platform that helps virtual asset businesses, financial institutions, and government agencies detect fraud, monitor transactions, and stay compliant with AML, KYC, and CFT…
  api_count: 1
  score_band: developing
  score_composite: 41.1
  shared: 3
- slug: anitian
  name: Anitian
  description: Anitian, Inc. is a Portland, Oregon cloud security and compliance automation company that helps SaaS providers reach and maintain U.S. federal compliance. Its FedFlex platform automates the FedRAMP lifecycle — pre-engineered AWS and Azure…
  api_count: 2
  score_band: emerging
  score_composite: 24.0
  shared: 3
- slug: bretton
  name: Bretton
  description: Bretton AI (formerly Greenlite AI) is a San Francisco fintech building AI-native operational infrastructure for financial institutions' back-office and financial-crime-compliance workflows. Its audit-ready AI agents automate AML alert inve…
  api_count: 0
  score_band: emerging
  score_composite: 22.8
  shared: 3
- slug: hummingbird-regtech
  name: Hummingbird RegTech
  description: Hummingbird RegTech, Inc. is a financial-crime compliance (RegTech) platform that unifies risk and compliance operations for banks, fintechs, and financial institutions. The product spans customer screening (sanctions, PEP, and adverse-med…
  api_count: 1
  score_band: emerging
  score_composite: 22.3
  shared: 3
- slug: risk-ledger
  name: Risk Ledger
  description: Risk Ledger is a London-based third-party and supply chain risk management platform that helps organizations assess, monitor, and continuously manage the security risks across their supplier networks. Through its "Active Supply Chain Secur…
  api_count: 0
  score_band: emerging
  score_composite: 20.6
  shared: 3
- slug: carbide
  name: Carbide
  description: Carbide (carbidesecure.com) is a compliance-automation and risk-management platform that pairs software with credentialed security advisors to help fast-growing organizations achieve and maintain security certifications and regulatory comp…
  api_count: 0
  score_band: emerging
  score_composite: 20.5
  shared: 3
- slug: luminosai
  name: Luminos.AI
  description: Luminos.AI is an AI governance and evaluation platform that tests AI systems — classical machine learning, generative AI, and autonomous agents — for legal, regulatory, and reputational risk. The platform automates continuous evaluations a…
  api_count: 0
  score_band: emerging
  score_composite: 20.5
  shared: 3
- slug: azimuth-grc
  name: Azimuth GRC
  description: Azimuth GRC provides automated compliance management software that transforms complex regulatory requirements into clear, actionable guidance. Their platform, VALIDATOR, offers real‑time monitoring, audit automation, and curated legal cont…
  api_count: 1
  score_band: emerging
  score_composite: 20.1
  shared: 3
- slug: behavox
  name: Behavox
  description: Behavox is an AI-native compliance and conduct-surveillance software company serving the world's leading financial institutions and regulated enterprises. Its Unified AI Controls Platform spans directive, preventive, detective, and correct…
  api_count: 0
  score_band: emerging
  score_composite: 19.2
  shared: 3
- slug: hummingbird
  name: Hummingbird
  description: Hummingbird is an AI-powered compliance operations platform for financial institutions and fintechs. It automates customer screening (sanctions, PEP, and adverse-media checks), transaction monitoring for financial crime, investigations and…
  api_count: 0
  score_band: emerging
  score_composite: 19.0
  shared: 3
- slug: complybridge-inc
  name: ComplyBridge
  description: ComplyBridge is a compliance operating system for regulated financial services firms operating in the European Economic Area — banks and credit institutions, electronic money institutions, crypto-asset service providers, payment institutio…
  api_count: 0
  score_band: emerging
  score_composite: 15.7
  shared: 3
- slug: wordsmith
  name: Wordsmith
  description: Wordsmith is an Edinburgh-based legal AI platform built for in-house legal teams, marketed as a Slack-native legal copilot that lets non-legal staff self-serve compliant answers, templates, and contract reviews directly in the tools they a…
  api_count: 2
  score_band: emerging
  score_composite: 15.4
  shared: 3
- slug: themis
  name: Themis
  description: Themis (askthemis.com) is a governance, risk, and compliance (GRC) SaaS platform positioned as a "compliance collaboration" tool that streamlines partnerships between companies and their vendors, banks, credit unions, and fintechs by accel…
  api_count: 0
  score_band: emerging
  score_composite: 14.8
  shared: 3
- slug: scytale
  name: Scytale
  description: Scytale is an AI-powered Governance, Risk, and Compliance (GRC) platform that automates security compliance for cloud and SaaS companies. It combines AI agents with in-house compliance experts to automate evidence collection, continuous co…
  api_count: 0
  score_band: emerging
  score_composite: 14.0
  shared: 3
- slug: norm-ai
  name: Norm Ai
  description: Norm Ai (legal name Nomos AI, Inc.) is a legal and compliance AI company that embeds law and regulation directly into autonomous AI agents. Its platform spans Norm Law (an AI-native law firm), Norm Technology (domain-expert-built complianc…
  api_count: 0
  score_band: emerging
  score_composite: 13.1
  shared: 3
- slug: diligent-boards
  name: Diligent
  description: Diligent Corporation is a governance, risk, and compliance (GRC) software company best known for its board management portal (Diligent Boards / Boardbooks) and the broader Diligent One Platform, which unifies board management, enterprise r…
  api_count: 4
  score_band: emerging
  score_composite: 13.0
  shared: 3
- slug: umony
  name: Umony
  description: Umony is a London-based communications compliance platform, founded in 2017 and backed by Seedcamp, that captures, records, and archives employee voice calls, SMS, WhatsApp, and Microsoft Teams conversations at the telecom-network level fo…
  api_count: 0
  score_band: emerging
  score_composite: 13.0
  shared: 3
---
