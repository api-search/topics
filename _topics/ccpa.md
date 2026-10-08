---
layout: topic
slug: ccpa
name: CCPA (California Consumer Privacy Act)
kind: topic
description: 'The California Consumer Privacy Act (CCPA), amended by the California Privacy Rights Act (CPRA), is a state statute that grants California residents rights over their personal information: the right to know, delete, correct, opt-out of sale/sharing, limit use of sensitive personal information, and non-discrimination for exercising privacy rights. It is enforced by the California Privacy Protection Agency (CPPA) and the California Attorney General. Technical interoperability mechanisms include the Global Privacy Control (GPC) browser signal and the IAB Tech Lab US Privacy (USP) / Global Privacy Platform (GPP) signals for advertising technology. This index tracks the official regulatory resources, technical privacy signals, and commercial APIs that help businesses comply with CCPA/CPRA obligations.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ccpa.png
tags:
- CPRA
- California
- Compliance
- Data Protection
- Data Subject Rights
- Legal
- Privacy
- Regulations
repo: https://github.com/api-evangelist/ccpa
api_count: 6
apis:
- name: Global Privacy Control (GPC) Specification
  description: Global Privacy Control is a browser-level signal that communicates a user's opt-out preference to websites. The California Attorney General has affirmed that GPC must be treated as a valid CCPA "Do Not Sell or Share" opt-out request.
  url: https://globalprivacycontrol.org/
- name: IAB Tech Lab Global Privacy Platform (GPP)
  description: The IAB Tech Lab Global Privacy Platform (GPP) is the successor to the US Privacy (USP) string. It provides a standardized way to communicate user consent and opt-out signals between publishers, consent management platforms, and adtech ven…
  url: https://iabtechlab.com/gpp/
- name: California Privacy Protection Agency (CPPA) Resources
  description: Official resources from the California Privacy Protection Agency, the body empowered by CPRA to implement, enforce, and publish regulations under the CCPA.
  url: https://cppa.ca.gov/
- name: California Data Broker Registry
  description: Official California Attorney General registry of data brokers required to register under Civil Code section 1798.99.80, providing a public list that consumers can use to submit opt-out requests.
  url: https://oag.ca.gov/data-brokers
- name: CCPA (California Consumer Privacy Act) Download API
  description: Request or download consumer deletion lists(s)
  url: https://globalprivacycontrol.org/
- name: CCPA (California Consumer Privacy Act) Upload API
  description: Submit new or amended status response files
  url: https://globalprivacycontrol.org/
links:
- type: CapabilityMap
  url: https://github.com/api-evangelist/ccpa/blob/main/capabilities/ccpa-capability-edges.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/ccpa/blob/main/security/ccpa-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/ccpa/blob/main/security/ccpa-domain-security.yml
- type: Website
  url: https://oag.ca.gov/privacy/ccpa
- type: Documentation
  url: https://oag.ca.gov/privacy/ccpa
- type: Regulator
  url: https://cppa.ca.gov/
- type: StatuteText
  url: https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?lawCode=CIV&division=3.&title=1.81.5.&part=4.&chapter=&article=
- type: Regulations
  url: https://cppa.ca.gov/regulations/
- type: FAQ
  url: https://oag.ca.gov/privacy/ccpa
- type: DataBrokerRegistry
  url: https://oag.ca.gov/data-brokers
- type: GPC
  url: https://globalprivacycontrol.org/
- type: GPP
  url: https://iabtechlab.com/gpp/
- type: Authentication
  url: https://github.com/api-evangelist/ccpa/blob/main/authentication/ccpa-authentication.yml
- type: OpenAPI
  url: https://github.com/api-evangelist/ccpa/blob/main/openapi/_original/ccpa-drop-databroker-api.yml
- type: Overlay
  url: https://github.com/api-evangelist/ccpa/blob/main/overlays/ccpa-drop-databroker-api-overlay.yaml
- type: WellKnown
  url: https://github.com/api-evangelist/ccpa/blob/main/well-known/ccpa-well-known.yml
- type: SecurityTxt
  url: https://github.com/api-evangelist/ccpa/blob/main/well-known/ccpa-security.txt
- type: Security
  url: https://github.com/api-evangelist/ccpa/blob/main/security/ccpa-vulnerability-disclosure.yml
- type: Conventions
  url: https://github.com/api-evangelist/ccpa/blob/main/conventions/ccpa-conventions.yml
- type: Conformance
  url: https://github.com/api-evangelist/ccpa/blob/main/conformance/ccpa-conformance.yml
- type: ErrorCatalog
  url: https://github.com/api-evangelist/ccpa/blob/main/errors/ccpa-problem-types.yml
- type: Lifecycle
  url: https://github.com/api-evangelist/ccpa/blob/main/lifecycle/ccpa-lifecycle.yml
- type: ChangeLog
  url: https://github.com/api-evangelist/ccpa/blob/main/changelog/ccpa-changelog.yml
- type: Sandbox
  url: https://github.com/api-evangelist/ccpa/blob/main/sandbox/ccpa-sandbox.yml
- type: Webhooks
  url: https://github.com/api-evangelist/ccpa/blob/main/asyncapi/ccpa-drop-webhooks.yml
- type: DataModel
  url: https://github.com/api-evangelist/ccpa/blob/main/data-model/ccpa-data-model.yml
- type: Packages
  url: https://github.com/api-evangelist/ccpa/blob/main/packages/ccpa-packages.yml
- type: SDKs
  url: https://github.com/api-evangelist/ccpa/blob/main/packages/ccpa-packages.yml
- type: AgentSkill
  url: https://github.com/api-evangelist/ccpa/blob/main/skills/_index.yml
- type: LLMsTxt
  url: https://github.com/api-evangelist/ccpa/blob/main/llms/ccpa-llms.txt
- type: RateLimits
  url: https://github.com/api-evangelist/ccpa/blob/main/rate-limits/ccpa-rate-limits.yml
- type: Plans
  url: https://github.com/api-evangelist/ccpa/blob/main/plans/ccpa-plans-pricing.yml
- type: FinOps
  url: https://github.com/api-evangelist/ccpa/blob/main/finops/ccpa-finops.yml
- type: DeveloperPortal
  url: https://privacy.ca.gov/drop-for-data-brokers/
- type: APIReference
  url: https://privacy.ca.gov/drop-for-data-brokers/technical-specifications/api-operations/
- type: GettingStarted
  url: https://privacy.ca.gov/drop-for-data-brokers/technical-specifications/getting-started/
provider_count: 108
providers:
- slug: trustarc
  name: TrustArc
  description: TrustArc is a Walnut Creek, California enterprise privacy management platform that helps organizations operationalize global data privacy programs. Its product portfolio spans three suites. Privacy Studio covers consumer-facing consent and…
  api_count: 2
  score_band: developing
  score_composite: 52.5
  shared: 4
- slug: trustboost-dev
  name: TrustBoost PII Sanitizer
  description: TrustBoost PII Sanitizer is a pay-per-call "privacy firewall" for autonomous AI agent pipelines, built and operated by an individual developer (Teodoro Crispin, GitHub teodorofodocrispin-cmyk) and served entirely from https://api.trustboos…
  api_count: 1
  score_band: developing
  score_composite: 50.1
  shared: 3
- slug: pimloc
  name: Pimloc
  description: Pimloc is a UK-based AI company whose Secure Redact platform automates the redaction and anonymization of personally identifiable information (PII) in video, audio, images and documents — blurring faces, license plates, screens, on-screen…
  api_count: 1
  score_band: developing
  score_composite: 49.1
  shared: 3
- slug: i6eal-open-ai-data-api
  name: i6eal Open AI Data API
  description: A free, no-authentication open-data REST API from i6eal (a German AI studio operated by Syka Ventures UG) exposing 16 AI-related datasets and monitors for Germany and the EU as static JSON/CSV/JSON-LD/Atom files served over HTTPS from Clou…
  api_count: 1
  score_band: developing
  score_composite: 42.7
  shared: 3
- slug: cookieyes
  name: Cookieyes
  description: CookieYes is a Google-certified consent management platform (CMP) that helps websites comply with privacy laws such as GDPR, CCPA/CPRA, LGPD, PIPEDA and POPIA. It provides customizable cookie consent banners, an automatic cookie scanner wi…
  api_count: 0
  score_band: thin
  score_composite: 33.8
  shared: 3
- slug: openlaws
  name: OpenLaws
  description: OpenLaws is a Public Benefit Corporation that provides programmatic access to U.S. law text — federal and state statutes, regulations, constitutions, and case law — through a unified Legal Data API. The platform exposes keyword and citatio…
  api_count: 2
  score_band: thin
  score_composite: 33.0
  shared: 3
- slug: odaseva
  name: Odaseva
  description: Odaseva is an enterprise data security, backup, and governance platform purpose-built for large, complex Salesforce environments. It provides data backup and recovery, archiving, seeding and anonymization/masking, encryption and key manage…
  api_count: 0
  score_band: emerging
  score_composite: 25.3
  shared: 3
- slug: privacy-by-design
  name: Privacy by Design
  description: Privacy By Design is a framework and approach that embeds privacy protections into the design and operation of IT systems, networked infrastructure, and business practices from the ground up, rather than as an afterthought.
  api_count: 0
  score_band: minimal
  score_composite: 2.8
  shared: 3
- slug: onetrust
  name: OneTrust
  description: OneTrust is an enterprise trust, privacy, and AI-governance platform. Its developer portal publishes 37 downloadable OpenAPI definitions covering roughly 631 operations across Universal Consent & Preference Management, Cookie Consent / CMP…
  api_count: 37
  score_band: exemplar
  score_composite: 72.7
  shared: 2
- slug: altr
  name: ALTR
  description: ALTR is a unified data security platform that discovers, classifies, masks, tokenizes and monitors sensitive data across Snowflake, Databricks and OLTP databases (PostgreSQL, MySQL, SQL Server, Oracle, MongoDB). The platform combines autom…
  api_count: 42
  score_band: strong
  score_composite: 58.6
  shared: 2
- slug: california-privacy-protection-agency
  name: California Privacy Protection Agency
  description: The California Privacy Protection Agency (CPPA, branded CalPrivacy) is the state regulator that administers and enforces the California Consumer Privacy Act and the Delete Act. Under the Delete Act it operates DROP, the Delete Request and…
  api_count: 1
  score_band: strong
  score_composite: 54.9
  shared: 2
- slug: bigid
  name: BigID
  description: BigID is a New York City-headquartered data security platform that combines Data Security Posture Management (DSPM), Data Loss Prevention (DLP), access governance, AI security & governance (AISPM), privacy automation, and a unified Data &…
  api_count: 3
  score_band: strong
  score_composite: 54.7
  shared: 2
- slug: amazon-macie
  name: Amazon Macie
  description: Amazon Macie is a data security service that discovers sensitive data by using machine learning and pattern matching, provides visibility into data security risks, and enables automated protection against those risks. Macie automates the d…
  api_count: 2
  score_band: strong
  score_composite: 54.6
  shared: 2
- slug: osano
  name: Osano
  description: Osano is a data privacy platform, founded in 2018 and headquartered in Austin, Texas, that helps organizations build and run privacy programs across consent management, subject rights (DSAR) automation, data mapping and discovery, privacy…
  api_count: 4
  score_band: strong
  score_composite: 54.4
  shared: 2
- slug: immuta
  name: Immuta
  description: Immuta is a data security and access-governance platform that lets organizations register their cloud data platforms — Snowflake, Databricks (Unity Catalog, Lakebase, Spark), Amazon Redshift and Redshift Spectrum, Amazon S3, AWS Lake Forma…
  api_count: 1
  score_band: developing
  score_composite: 54.2
  shared: 2
- slug: singlefile
  name: SingleFile
  description: SingleFile is an AI-powered entity management and corporate compliance platform for corporations, law firms, and investment organizations. It automates business entity formation, EIN filing, annual report filing, registered agent services,…
  api_count: 1
  score_band: developing
  score_composite: 52.5
  shared: 2
- slug: transcend-io
  name: Transcend
  description: Transcend is a privacy and data permissioning platform that helps enterprises decide in real time whether customer data can be used for a given purpose. The platform spans data discovery and inventory, data subject request automation, cons…
  api_count: 1
  score_band: developing
  score_composite: 52.2
  shared: 2
- slug: certifaction
  name: Certifaction
  description: 'Certifaction is a privacy-first digital signature platform built around a Zero Document Knowledge model: documents are hashed and end-to-end encrypted on the client so they can be signed and verified without Certifaction ever seeing their…'
  api_count: 2
  score_band: developing
  score_composite: 51.5
  shared: 2
- slug: confido-legal
  name: Confido Legal
  description: Confido Legal is a payment processing and disbursements platform purpose-built for the legal industry. It enables law firms and legal technology vendors to accept client payments with automated trust-account routing, send real-time digital…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: mine
  name: MINE
  description: Mine (MineOS) is a data privacy, governance, and AI security posture management platform backed by Battery Ventures. Its MineOS product automates data mapping and inventory, data subject / privacy rights requests (DSR), consent management,…
  api_count: 2
  score_band: developing
  score_composite: 50.6
  shared: 2
- slug: nabis
  name: Nabis
  description: Nabis is a licensed cannabis wholesale distributor and B2B marketplace founded in 2018 by Vince C. Ning and Jun S. Lee, operating in California, New York and Nevada. It runs distribution and fulfillment warehouses, an ordering marketplace…
  api_count: 3
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: inth
  name: Inth
  description: Inth is a San Francisco, Y Combinator-backed company building enterprise privacy governance for teams that ship fast, making consent programmable, observable, and compliant by default. Its foundation is c15t (github.com/c15t), an open-sour…
  api_count: 1
  score_band: developing
  score_composite: 49.7
  shared: 2
- slug: relativity
  name: Relativity
  description: Relativity is an eDiscovery and legal review platform offering RelativityOne, a cloud-based SaaS solution for managing the full legal data lifecycle. Its REST API enables programmatic access to workspaces, document import and export, proce…
  api_count: 32
  score_band: developing
  score_composite: 47.9
  shared: 2
- slug: mitratech
  name: Mitratech
  description: Mitratech is an Austin, Texas based enterprise software company supplying legal operations, governance, risk and compliance, and HR compliance software to corporate legal departments, compliance teams and human resources organizations. Its…
  api_count: 2
  score_band: developing
  score_composite: 45.4
  shared: 2
- slug: luminance
  name: Luminance
  description: Luminance Technologies Ltd. is a UK-headquartered legal-AI company, founded in 2015 out of Cambridge mathematics research, that builds what it markets as Legal-Grade AI for the full contract lifecycle — drafting, negotiation, analysis, com…
  api_count: 3
  score_band: developing
  score_composite: 45.1
  shared: 2
- slug: kodex
  name: Kodex
  description: Kodex (Albatross Technologies) operates the Kodex Global Network, a platform for managing law enforcement and government data requests — subpoenas, warrants, and emergency disclosure requests — for crypto exchanges, fintechs, banks, and te…
  api_count: 2
  score_band: developing
  score_composite: 45.0
  shared: 2
- slug: usercentrics
  name: Usercentrics
  description: Usercentrics is a Munich-based consent management platform (CMP) and privacy compliance provider. Founded in 2017 and led by CEO Donna Dror, Usercentrics acquired Danish CMP Cookiebot (Cybot) in September 2021 and acquired MCP Manager in J…
  api_count: 3
  score_band: developing
  score_composite: 44.9
  shared: 2
- slug: workday-security
  name: Workday Security
  description: Collection of Workday Security APIs for managing authentication, authorization, and security configurations including identity management, security groups, audit logging, privacy, and user activity monitoring.
  api_count: 4
  score_band: developing
  score_composite: 44.2
  shared: 2
- slug: spin-ai
  name: Spin.AI
  description: Spin.AI is a SaaS security platform providing data protection, ransomware detection, and compliance management for cloud applications including Google Workspace, Microsoft 365, Salesforce, and Slack. The SpinOne Public API enables programm…
  api_count: 1
  score_band: developing
  score_composite: 44.0
  shared: 2
- slug: k-id
  name: k-ID
  description: k-ID is a compliance platform that lets games, social apps, AI products, and commerce deliver age-appropriate experiences across 200+ jurisdictions. Its Compliance Development Kit (CDK) encodes auto-updating regulatory logic for regimes li…
  api_count: 1
  score_band: developing
  score_composite: 43.9
  shared: 2
---
