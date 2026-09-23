---
layout: topic
slug: regulatory
name: Regulatory
kind: topic
description: The regulatory domain encompasses compliance requirements, regulatory reporting, and governance frameworks that organizations must adhere to across industries. APIs in this space enable businesses to automate compliance workflows, track regulatory changes, submit required filings, and manage risk. Key sectors include financial services (SEC, FINRA, CFTC), healthcare (FDA, CMS), telecommunications (FCC), and environmental regulation (EPA).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/regulatory.png
tags:
- Compliance
- Financial-Services
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
provider_count: 194
providers:
- slug: emtech
  name: EMTECH
  description: EMTECH is a financial-technology company founded in 2019 that modernizes financial market infrastructure for central banks, financial regulators, and financial service providers. Its Beyond Suite delivers regulatory sandbox management (Bey…
  api_count: 0
  score_band: thin
  score_composite: 32.1
  shared: 4
- slug: hadrius
  name: Hadrius
  description: Hadrius is an AI-native compliance platform for SEC- and FINRA-regulated financial firms, including broker-dealers, registered investment advisors (RIAs), private funds, and compliance consultants. The platform consolidates multiple compli…
  api_count: 0
  score_band: emerging
  score_composite: 14.6
  shared: 4
- slug: greenboard
  name: Greenboard
  description: Greenboard is an AI-native compliance software platform for SEC- and FINRA-regulated financial institutions, consolidating communications archiving, employee compliance monitoring, marketing/advertising review, firm-wide compliance managem…
  api_count: 0
  score_band: emerging
  score_composite: 11.7
  shared: 4
- slug: fenergo
  name: Fenergo
  description: Fenergo is an Irish-headquartered financial-services SaaS vendor whose Fen-X platform delivers Client Lifecycle Management (CLM), Know Your Customer (KYC), AML screening, client onboarding, transaction monitoring and regulatory compliance…
  api_count: 145
  score_band: strong
  score_composite: 60.0
  shared: 3
- slug: spektr
  name: Spektr
  description: Spektr is an AI-powered compliance automation platform for banks and fintechs, backed by Northzone and Seedcamp. It automates KYB and KYC onboarding, continuous customer monitoring, risk scoring, remediation, and transaction monitoring usi…
  api_count: 1
  score_band: developing
  score_composite: 50.6
  shared: 3
- slug: vanta
  name: Vanta
  description: Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate…
  api_count: 2
  score_band: developing
  score_composite: 47.9
  shared: 3
- slug: openpages
  name: OpenPages
  description: IBM OpenPages is an AI-driven, unified governance, risk, and compliance (GRC) platform delivered as a managed service on IBM Cloud. Originally founded as OpenPages Inc. (a Matrix Partners portfolio company) and acquired by IBM in 2010, it…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 3
- slug: acin
  name: Acin
  description: Acin is a London-based operational and non-financial risk (NFR) data company for financial services, founded in 2018 and acquired by regulatory-intelligence firm CUBE in June 2025. Its platform ingests a bank's process, risk and control in…
  api_count: 1
  score_band: thin
  score_composite: 29.7
  shared: 3
- slug: hummingbird-regtech
  name: Hummingbird RegTech
  description: Hummingbird RegTech, Inc. is a financial-crime compliance (RegTech) platform that unifies risk and compliance operations for banks, fintechs, and financial institutions. The product spans customer screening (sanctions, PEP, and adverse-med…
  api_count: 1
  score_band: emerging
  score_composite: 21.9
  shared: 3
- slug: bretton
  name: Bretton
  description: Bretton AI (formerly Greenlite AI) is a San Francisco fintech building AI-native operational infrastructure for financial institutions' back-office and financial-crime-compliance workflows. Its audit-ready AI agents automate AML alert inve…
  api_count: 0
  score_band: emerging
  score_composite: 20.5
  shared: 3
- slug: risk-ledger
  name: Risk Ledger
  description: Risk Ledger is a London-based third-party and supply chain risk management platform that helps organizations assess, monitor, and continuously manage the security risks across their supplier networks. Through its "Active Supply Chain Secur…
  api_count: 0
  score_band: emerging
  score_composite: 20.0
  shared: 3
- slug: carbide
  name: Carbide
  description: Carbide (carbidesecure.com) is a compliance-automation and risk-management platform that pairs software with credentialed security advisors to help fast-growing organizations achieve and maintain security certifications and regulatory comp…
  api_count: 0
  score_band: emerging
  score_composite: 19.5
  shared: 3
- slug: hummingbird
  name: Hummingbird
  description: Hummingbird is an AI-powered compliance operations platform for financial institutions and fintechs. It automates customer screening (sanctions, PEP, and adverse-media checks), transaction monitoring for financial crime, investigations and…
  api_count: 0
  score_band: emerging
  score_composite: 18.5
  shared: 3
- slug: behavox
  name: Behavox
  description: Behavox is an AI-native compliance and conduct-surveillance software company serving the world's leading financial institutions and regulated enterprises. Its Unified AI Controls Platform spans directive, preventive, detective, and correct…
  api_count: 0
  score_band: emerging
  score_composite: 17.6
  shared: 3
- slug: complybridge-inc
  name: ComplyBridge, Inc.
  description: ComplyBridge is a compliance operating system for regulated financial services firms operating in the European Economic Area — banks and credit institutions, electronic money institutions, crypto-asset service providers, payment institutio…
  api_count: 0
  score_band: emerging
  score_composite: 15.7
  shared: 3
- slug: norm-ai
  name: Norm Ai
  description: Norm Ai (legal name Nomos AI, Inc.) is a legal and compliance AI company that embeds law and regulation directly into autonomous AI agents. Its platform spans Norm Law (an AI-native law firm), Norm Technology (domain-expert-built complianc…
  api_count: 0
  score_band: emerging
  score_composite: 12.8
  shared: 3
- slug: umony
  name: Umony
  description: Umony is a London-based communications compliance platform, founded in 2017 and backed by Seedcamp, that captures, records, and archives employee voice calls, SMS, WhatsApp, and Microsoft Teams conversations at the telecom-network level fo…
  api_count: 0
  score_band: emerging
  score_composite: 12.6
  shared: 3
- slug: eisen
  name: Eisen
  description: Eisen is an AI-enabled compliance operations platform for financial institutions and digital asset companies, managing escheatment (unclaimed property), disbursement, customer outreach, and 1099 tax reporting across all account types. Its…
  api_count: 0
  score_band: minimal
  score_composite: 10.8
  shared: 3
- slug: silent-eight
  name: Silent Eight
  description: Silent Eight is an AI-driven financial crime compliance (FCC) technology company founded in Singapore in 2015 and operating globally. Its flagship platform, Iris 7, delivers policy-bound agentic AI that replicates the investigative judgeme…
  api_count: 0
  score_band: minimal
  score_composite: 10.6
  shared: 3
- slug: payna
  name: Payna
  description: Payna is a compliance operating system for financial licensing that automates applications, renewals, maintenance, and monitoring across all 50 US states and jurisdictions. It tracks state statutes, NMLS procedures, and FinCEN requirements…
  api_count: 0
  score_band: minimal
  score_composite: 9.3
  shared: 3
- slug: scenario-x-global-holding-pte-ltd
  name: SCENARIO-X GLOBAL HOLDING PTE. LTD.
  description: SCENARIO-X GLOBAL HOLDING PTE. LTD. (Scenario X) is a financial-technology company building an AI- and quantum-computing-powered platform for financial risk analysis, stress testing, and regulatory reporting. The integrated platform is org…
  api_count: 0
  score_band: minimal
  score_composite: 8.3
  shared: 3
- slug: tongdun
  name: Tongdun
  description: Tongdun (同盾科技 / Tongdun Technology) is a Hangzhou-based intelligent risk-control and anti-fraud analytics company whose public product presence now operates under the 小盾未来 (Xiaodun Future) brand at xiaodun.com. It uses AI and intelligent-a…
  api_count: 0
  score_band: minimal
  score_composite: 7.6
  shared: 3
- slug: bayshore
  name: Bayshore
  description: Bayshore (bayshore AI GmbH) is a Munich-based legal and compliance technology company building an agentic AI platform that turns any ruleset — from sector regulations to internal corporate policies — into deterministic, machine-readable gu…
  api_count: 0
  score_band: minimal
  score_composite: 7.1
  shared: 3
- slug: klaimee
  name: Klaimee
  description: Klaimee is a Y Combinator (Spring/P26 batch) startup building certification, financial guarantee, and liability insurance for AI agents running in production. The company evaluates an autonomous agent across risk dimensions such as scope,…
  api_count: 0
  score_band: minimal
  score_composite: 7.1
  shared: 3
- slug: cambridge-blockchain
  name: Cambridge Blockchain
  description: Cambridge Blockchain, Inc. was a blockchain-based digital identity and compliance software company founded in 2015 and headquartered in Cambridge / Boston, Massachusetts. Its enterprise platform let financial institutions deliver strong di…
  api_count: 0
  score_band: minimal
  score_composite: 5.3
  shared: 3
- slug: internal-control-standards
  name: Internal Control Standards
  description: Internal Control Standards are frameworks of policies and procedures designed to provide reasonable assurance regarding the achievement of objectives in operational effectiveness, reliable financial reporting, and compliance with laws and…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: security-standards-and-procedures
  name: Security Standards and Procedures
  description: Frameworks and documented guidelines that establish security requirements, controls, and best practices for protecting organizational assets and information systems. It plays a critical role in protecting organizational assets and maintain…
  api_count: 0
  score_band: minimal
  score_composite: 4.3
  shared: 3
- slug: outils-de-gestion-des-risques
  name: Outils De Gestion Des Risques
  description: Outils de Gestion des Risques refers to risk management tools and services used in French-speaking business and regulatory environments, covering risk assessment, monitoring, mitigation, reporting, and compliance. No verifiable public APIs…
  api_count: 0
  score_band: minimal
  score_composite: 4.1
  shared: 3
- slug: clausematch
  name: Clausematch
  description: Clausematch is a London-founded regulatory technology (RegTech) company providing a cloud platform for policy and procedure management, regulatory change management, and structured document authoring and collaboration for banks, insurers,…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 3
- slug: fenrock-ai
  name: Fenrock AI
  description: Fenrock AI is a Y Combinator (W26) company building specialized AI agents for the banking back office. Founded in 2026 and based in San Francisco by Charu Sharma and Michael M., Fenrock overlays on a bank's existing systems and ingests int…
  api_count: 0
  score_band: minimal
  score_composite: 1.5
  shared: 3
---
