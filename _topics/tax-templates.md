---
layout: topic
slug: tax-templates
name: Tax Templates
kind: topic
description: Pre-designed templates for organizing and filing tax documents and returns. Financial institutions and enterprises use these templates to streamline tax operations and manage fiscal responsibilities. Covers tax document collection, structured data formats for financial disclosures, corporate tax returns, and regulatory compliance frameworks across jurisdictions.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/tax-templates.png
tags:
- Documentation
- Finance
- Tax
- Templates
- Compliance
repo: https://github.com/api-evangelist/tax-templates
api_count: 5
apis:
- name: TurboTax API
  description: Intuit TurboTax API enables integration with TurboTax for consumer and business tax preparation workflows, including data import, tax calculation, and e-filing.
  url: https://developer.intuit.com/
- name: H&R Block API
  description: H&R Block provides tax preparation templates and tools for individual and small business returns, including document import and guided filing workflows.
  url: https://www.hrblock.com/tax-center/filing/e-file/
- name: Xero Tax API
  description: Xero's Tax API enables accounting software and tax providers to connect to Xero for seamless tax return preparation using real-time financial data.
  url: https://developer.xero.com/documentation/xero-app-store/app-partner-guides/tax/
- name: QuickBooks Tax API
  description: QuickBooks Online API provides access to tax-related financial data including income, expenses, and payroll for generating tax templates and returns.
  url: https://developer.intuit.com/app/developer/qbo/docs/develop
- name: FATCA/CRS Reporting Templates
  description: FATCA (Foreign Account Tax Compliance Act) and CRS (Common Reporting Standard) templates for financial institutions reporting foreign account holders to the IRS and international tax authorities.
  url: https://www.irs.gov/businesses/corporations/foreign-account-tax-compliance-act-fatca
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/tax-templates/blob/main/security/tax-templates-domain-security.yml
- type: Website
  url: https://www.irs.gov/
- type: JSONSchema
  url: https://github.com/api-evangelist/tax-templates/blob/main/json-schema/tax-document-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/tax-templates/blob/main/json-structure/tax-document-structure.json
- type: JSONLD
  url: https://github.com/api-evangelist/tax-templates/blob/main/json-ld/tax-templates-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/tax-templates/blob/main/vocabulary/tax-templates-vocabulary.yml
provider_count: 42
providers:
- slug: vatstack
  name: Vatstack
  description: VAT number validation and EU tax rates REST API for validating European business VAT IDs via VIES and accessing current VAT rates for all EU member states. Vatstack provides automated VAT compliance for digital businesses including real-ti…
  api_count: 1
  score_band: developing
  score_composite: 41.4
  shared: 3
- slug: thomson-reuters
  name: Thomson Reuters
  description: Thomson Reuters provides over 137 APIs across legal, tax and accounting, risk and fraud, and trade and supply industries through their global developer portal. APIs cover Westlaw legal research, Checkpoint tax content, ONESOURCE tax softwa…
  api_count: 6
  score_band: emerging
  score_composite: 13.4
  shared: 3
- slug: ibanforge
  name: IBANforge
  description: Pre-payout IBAN screening for developers and AI agents — validation, issuing-bank identification against national bank registers, Swiss clearing including QR-IID, bank-level sanctions, SEPA and VoP reachability, and risk scoring across 89…
  api_count: 1
  score_band: exemplar
  score_composite: 74.0
  shared: 2
- slug: flowaccount
  name: FlowAccount
  description: FlowAccount is a Thai cloud accounting platform serving 130,000+ SMEs, 17,000+ accountants and admins, and 5,900+ accounting firms. Its products cover online accounting (quotations, invoices, tax invoices, receipts, expenses), MobilePOS po…
  api_count: 1
  score_band: strong
  score_composite: 59.3
  shared: 2
- slug: intuit
  name: Intuit
  description: Collection of APIs offered by Intuit for financial and business management services.
  api_count: 1
  score_band: strong
  score_composite: 59.2
  shared: 2
- slug: globaldatabase-com
  name: Global Database
  description: Global Database (GLOBAL DATA INTELLIGENCE Ltd, UK) is a B2B company-intelligence provider that sources company records directly from 400+ official government registries across 200+ countries — 600M+ company profiles with registry data, off…
  api_count: 2
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: cadana
  name: Cadana
  description: Cadana is a white-label global payment and payroll infrastructure provider for talent platforms, staffing companies, and HR providers. Its APIs let partners onboard and pay employees and contractors in 100+ countries, run multi-currency pa…
  api_count: 5
  score_band: developing
  score_composite: 48.2
  shared: 2
- slug: london-stock-exchange-group
  name: London Stock Exchange Group
  description: London Stock Exchange Group plc is a United Kingdom-based stock exchange and financial information company headquartered in the City of London, England. LSEG provides capital markets, data and analytics, risk management, and post-trade ser…
  api_count: 1
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: inkit
  name: Inkit
  description: Inkit is a Secure Document Generation (SDG) platform that enables organizations to generate, sign, store, and distribute documents in total privacy. The platform provides a REST API for rendering HTML templates into PDFs, automating docume…
  api_count: 1
  score_band: developing
  score_composite: 46.4
  shared: 2
- slug: zoho-sign
  name: Zoho Sign
  description: Zoho Sign is a cloud-based electronic signature platform that provides a REST API for sending documents for signature, managing templates, tracking signing status, and automating signature workflows. The API supports OAuth 2.0 authenticati…
  api_count: 1
  score_band: developing
  score_composite: 45.9
  shared: 2
- slug: boldsign
  name: BoldSign
  description: BoldSign is an e-signature platform built by Syncfusion that provides a REST API for sending documents for electronic signature, managing reusable templates, tracking envelope status, and embedding signing and requesting workflows directly…
  api_count: 1
  score_band: developing
  score_composite: 44.1
  shared: 2
- slug: dealogic
  name: Dealogic
  description: Dealogic is a global provider of content and software for the capital markets — deal management, analytics, league tables and compliance — used by investment banks, syndicate and sales/trading desks, investment managers and corporates, and…
  api_count: 16
  score_band: developing
  score_composite: 39.9
  shared: 2
- slug: planomy-tax-data
  name: Planomy Tax Data
  description: 'A free, keyless open-data JSON API publishing the 2026 US retirement and tax figures that drive the Planomy local-first personal-finance planner: federal income-tax brackets and the standard deduction, FICA rates and the Social Security wa…'
  api_count: 1
  score_band: thin
  score_composite: 37.2
  shared: 2
- slug: filed
  name: Filed
  description: Filed is an AI tax platform for accounting firms and tax professionals. It reads source documents (W-2s, 1099s, K-1s, brokerage statements, prior-year returns), compares them line by line against the draft return to catch errors and find o…
  api_count: 1
  score_band: thin
  score_composite: 35.9
  shared: 2
- slug: finra
  name: FINRA
  description: The Financial Industry Regulatory Authority (FINRA) is a regulatory organization that oversees and regulates the securities industry in the United States. The FINRA Developer Center exposes Query, Notification, and Submission APIs for acce…
  api_count: 6
  score_band: thin
  score_composite: 35.7
  shared: 2
- slug: vistra
  name: Vistra
  description: Vistra is a global corporate services provider operating in over 45 jurisdictions, offering entity management, incorporation, compliance, payroll, and fund administration services. The Vistra REST API enables developers to programmatically…
  api_count: 1
  score_band: thin
  score_composite: 35.3
  shared: 2
- slug: mosey
  name: Mosey
  description: Mosey is a business compliance platform that helps multi-state companies open and manage state and local tax, HR, payroll, insurance, and registration accounts. The Mosey API is a composable set of OpenAPI 3.1 endpoints that let software p…
  api_count: 3
  score_band: thin
  score_composite: 34.2
  shared: 2
- slug: quickbooks
  name: QuickBooks
  description: QuickBooks is Intuit's accounting software platform for small businesses, self-employed, and accountants, available as QuickBooks Online (cloud) and QuickBooks Desktop. The QuickBooks Online Accounting REST API provides programmatic access…
  api_count: 4
  score_band: thin
  score_composite: 34.2
  shared: 2
- slug: cleartax
  name: Cleartax
  description: Cleartax (operating as Clear, clear.in) is an Indian fintech and financial-compliance automation platform that provides tax, GST, and e-invoicing software for individuals, tax professionals, and over 4,000 enterprises. Clear exposes a suit…
  api_count: 5
  score_band: thin
  score_composite: 33.7
  shared: 2
- slug: sphere-tax
  name: Sphere
  description: Sphere is a developer-first global indirect tax compliance platform that automates sales tax, VAT, and GST across nexus monitoring, registration, real-time calculation, and filing/remittance. Its REST API lets billing and checkout flows ca…
  api_count: 1
  score_band: thin
  score_composite: 32.6
  shared: 2
- slug: mainstreet
  name: MainStreet
  description: MainStreet is a US small-business tax-credit and back-office platform that identifies, calculates, and files R&D tax credits alongside a client's CPA. Its service covers qualified research expense (QRE) identification under IRC §41, the IR…
  api_count: 1
  score_band: thin
  score_composite: 31.5
  shared: 2
- slug: clearbooks
  name: Clear Books
  description: Clear Books is UK cloud accounting software with a REST API for managing invoices, expenses, bank transactions, contacts, reports, and tax submissions for small businesses.
  api_count: 1
  score_band: thin
  score_composite: 28.9
  shared: 2
- slug: irs
  name: IRS
  description: The US Internal Revenue Service (IRS) provides REST APIs and Application-to-Application (A2A) interfaces for tax information access, identity verification, income verification, information return filing, and taxpayer account data. Authoriz…
  api_count: 5
  score_band: emerging
  score_composite: 25.4
  shared: 2
- slug: earnipay
  name: Earnipay
  description: Earnipay is a Nigerian fintech that operates an NRS/FIRS-compliant e-invoicing platform for businesses. As an accredited Nigeria Revenue Service (NRS) and NITDA systems integrator, Earnipay lets developers programmatically create businesse…
  api_count: 1
  score_band: emerging
  score_composite: 22.1
  shared: 2
- slug: vatapi
  name: VAT API
  description: EU and UK VAT compliance REST API providing VAT rate retrieval, VAT number validation via the European Commission VIES system and UK HMRC, currency conversion, and VAT-compliant invoice generation. Operated by Eventured Ltd and launched in…
  api_count: 1
  score_band: emerging
  score_composite: 21.3
  shared: 2
- slug: firstbase
  name: Firstbase
  description: Firstbase is an all-in-one startup operating system that helps founders form, run, and grow a US business from anywhere in the world. Its products cover incorporation (Firstbase Start for LLCs and C-Corps in Delaware, Wyoming, New York, Te…
  api_count: 0
  score_band: emerging
  score_composite: 20.0
  shared: 2
- slug: blue-j
  name: Blue J
  description: Blue J is an AI-powered tax research platform that delivers defensible, source-backed answers to complex tax questions in seconds, drawing on primary law plus Tax Notes and IBFD content. Built for tax professionals, the platform supports a…
  api_count: 0
  score_band: emerging
  score_composite: 19.5
  shared: 2
- slug: accordance-ai
  name: Accordance Ai
  description: Accordance (operated by Agnetic Labs Inc.) is a San Francisco frontier AI platform built for tax, audit, and accounting professionals. Founded by researchers from the Stanford AI Lab, it provides a firmwide agentic AI platform that perform…
  api_count: 0
  score_band: emerging
  score_composite: 19.0
  shared: 2
- slug: neotax
  name: Neo.Tax
  description: Neo.Tax is an AI-powered tax automation platform that helps enterprises and their accounting teams generate audit-ready R&D tax credit studies, software capitalization (ASC 350-40), and R&D capitalization (IRC Section 174) documentation. T…
  api_count: 0
  score_band: emerging
  score_composite: 18.8
  shared: 2
- slug: rates-and-limits
  name: Rates and Limits
  description: 'A free, keyless open-data publisher exposing US federal and state tax, payroll, benefits, and wage figures as JSON. Every figure ships bundled with provenance: the exact quoted sentence from the governing government document, byte offsets,…'
  api_count: 1
  score_band: emerging
  score_composite: 18.3
  shared: 2
---
