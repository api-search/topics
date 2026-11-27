---
layout: topic
slug: accounting-standards
name: Accounting Standards
kind: topic
description: Accounting Standards are the formal rules and guidelines that govern how financial transactions and statements are recorded, reported, and disclosed. They ensure consistency, transparency, and comparability across financial reports, and include frameworks like GAAP and IFRS. Digital reporting standards like XBRL enable structured, machine-readable financial filings.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/accounting-standards.png
tags:
- Accounting Standards
- Finance
- GAAP
- IFRS
- XBRL
- Financial Reporting
- SEC
- FASB
repo: https://github.com/api-evangelist/accounting-standards
api_count: 5
apis:
- name: US GAAP Financial Reporting Taxonomy 2026
  description: The 2026 GAAP Financial Reporting Taxonomy (GRT) is the official XBRL taxonomy maintained by FASB for SEC financial filings. It incorporates updates for FASB accounting standards published through December 1, 2025. The taxonomy provides st…
  url: https://xbrl.us/xbrl-taxonomy/2026-us-gaap/
- name: SEC EDGAR XBRL API
  description: The SEC EDGAR XBRL APIs provide free, real-time access to structured financial data from public company filings. APIs include company submissions, company facts (all XBRL disclosures), company concepts (individual taxonomy tags per company…
  url: https://www.sec.gov/about/developer-resources
- name: IFRS Accounting Standards
  description: International Financial Reporting Standards (IFRS) are global accounting standards issued by the International Accounting Standards Board (IASB). IFRS standards govern the financial reporting of companies in over 140 jurisdictions. The IFR…
  url: https://www.ifrs.org/issued-standards/list-of-standards/
- name: FASB Accounting Standards Codification
  description: The FASB Accounting Standards Codification (ASC) is the single source of authoritative nongovernmental U.S. GAAP. Organized into Topics, Subtopics, Sections, and Paragraphs, the ASC provides the complete set of accounting guidance for US G…
  url: https://asc.fasb.org/
- name: XBRL International Specification
  description: eXtensible Business Reporting Language (XBRL) is an open international standard for digital business reporting maintained by XBRL International. It enables the exchange of business information in a structured, machine-readable format. XBRL…
  url: https://www.xbrl.org/
links:
- type: Plans
  url: https://artifacts.apis.io/accounting-standards/plans/accounting-standards-plans-pricing.yml
- type: RateLimits
  url: https://artifacts.apis.io/accounting-standards/rate-limits/accounting-standards-rate-limits.yml
- type: FinOps
  url: https://artifacts.apis.io/accounting-standards/finops/accounting-standards-finops.yml
- type: DomainSecurity
  url: https://artifacts.apis.io/accounting-standards/security/accounting-standards-domain-security.yml
- type: Website
  url: https://www.fasb.org/
- type: Website
  url: https://www.ifrs.org/
- type: Website
  url: https://xbrl.us/
- type: GitHubOrganization
  url: https://github.com/xbrl
- type: Tools
  url: https://data.sec.gov/
- type: JSONLD
  url: https://artifacts.apis.io/accounting-standards/json-ld/accounting-standards-context.jsonld
- type: Vocabulary
  url: https://artifacts.apis.io/accounting-standards/vocabulary/accounting-standards-vocabulary.yaml
provider_count: 22
providers:
- slug: sec
  name: SEC EDGAR
  description: The U.S. Securities and Exchange Commission (SEC) EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides free public access to corporate financial filings submitted to the SEC. The EDGAR REST API at data.sec.gov deliver…
  api_count: 3
  score_band: thin
  score_composite: 34.7
  shared: 3
- slug: arkolith-com
  name: Arkolith
  description: Arkolith provides real-time institutional market-data APIs and an MCP server that surface SEC filings, 13F holdings, Form 4 insider trades, and derived signals. Users can start with a $1 trial for 300 research credits over 3 days, then sub…
  api_count: 1
  score_band: strong
  score_composite: 56.8
  shared: 2
- slug: algoum-de
  name: Algoum
  description: algoum provides a SEC EDGAR API delivering insider trades, 8‑K filings and 13F data in clear, plain‑language JSON. It transforms official company disclosures into easy‑to‑read updates for investors and algorithmic traders, offering free ac…
  api_count: 2
  score_band: strong
  score_composite: 54.9
  shared: 2
- slug: earningsfeed-com
  name: Earnings Feed
  description: Earnings Feed provides free access to SEC filings as they are accepted by EDGAR, including 8‑K, 10‑K, 10‑Q, and Form 4 insider trades. Users can search by ticker, filter by form type, and build watchlists with digests. The service offers a…
  api_count: 1
  score_band: developing
  score_composite: 47.1
  shared: 2
- slug: metricduck-com
  name: MetricDuck
  description: MetricDuck provides SEC‑filing answers inside AI agents like ChatGPT and Claude. It covers ~6,000 SEC filers, offering 250+ computed metrics, raw XBRL data, filing text, signals and earnings‑call transcripts. The service works via an MCP s…
  api_count: 1
  score_band: developing
  score_composite: 44.6
  shared: 2
- slug: catalystedgescanner-com
  name: Catalyst Edge
  description: Catalyst Edge provides a SEC filing intelligence platform that scans every SEC EDGAR filing overnight. It scores stocks using a multi‑factor catalyst model considering filing type, sentiment, recency, and macro factors, delivering top pick…
  api_count: 2
  score_band: developing
  score_composite: 44.1
  shared: 2
- slug: edgar-tools
  name: edgar.tools
  description: edgar.tools is an MCP server and web platform for SEC EDGAR filings. Analysts, advisors and developers can ask AI assistants about a company and receive answers directly from the latest filing, with links to the public filing pages. The se…
  api_count: 2
  score_band: developing
  score_composite: 43.4
  shared: 2
- slug: ko-io
  name: ko.io
  description: ko.io provides a clean record platform aggregating SEC 13F, insider, and congressional trading data. It offers REST and MCP APIs for institutions, stocks, insider trades, government contracts, and crypto ETF holdings, enabling AI agents an…
  api_count: 1
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: distillmarkets-com
  name: distillmarkets-com
  description: Distill Markets provides point-in-time SEC fundamentals and 13F institutional ownership data via a robust API, delivering the entire universe of filings as they stood at any quarter-end since 2009, with survivorship completeness and benchm…
  api_count: 5
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: filingfirehose-com
  name: filingfirehose-com
  description: FilingFirehose provides a JSON API that delivers structured, normalized SEC EDGAR filings, including detailed 8‑K body‑text parsing, activist 13D tagging, and ATM offering detection. The service offers a free tier and paid plans starting a…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 2
- slug: nomas-fyi
  name: Nomas
  description: Nomas provides SEC data infrastructure for agents, offering clean, structured financial datasets including company fundamentals, insider trading records, FTD entries, and institutional 13F filings. Users can query a parsed database via API…
  api_count: 1
  score_band: thin
  score_composite: 34.1
  shared: 2
- slug: dirigon-com
  name: Dirigon
  description: Dirigon provides a private credit look‑through platform that aggregates SEC EDGAR filings to show what major investment firms such as Blackstone, Blue Owl, Ares and others hold and how they mark the same loan. The service offers searchable…
  api_count: 1
  score_band: thin
  score_composite: 34.0
  shared: 2
- slug: filingsift
  name: FilingSift
  description: FilingSift provides source‑cited SEC filing data through a REST API and client libraries. It enables analysts and software teams to search indexed SEC filings, compare financing disclosures, and retrieve primary‑source rates, bank and cred…
  api_count: 1
  score_band: thin
  score_composite: 31.7
  shared: 2
- slug: 13flow-eu
  name: 13FLOW
  description: 13FLOW is an independent research and data lab operating the 13FLOW platform, which provides read‑only, source‑linked SEC EDGAR filing intelligence. It aggregates 13F ownership data, Form 4 insider activity, and offers API and MCP contract…
  api_count: 1
  score_band: thin
  score_composite: 29.0
  shared: 2
- slug: quotelinks
  name: Quotelinks
  description: Quotelinks provides free JSON APIs delivering standardized SEC financial statements, company profiles, and filings for over 21,000 public companies, as well as European Central Bank exchange rates since 1999. All endpoints are open, requir…
  api_count: 2
  score_band: thin
  score_composite: 28.4
  shared: 2
- slug: agentfilings-com
  name: AgentFilings
  description: AgentFilings provides structured US SEC/EDGAR filing data for AI agents, offering filings, XBRL-derived earnings, and Form 4 insider transactions as clean JSON. The service offers unlimited calls to all endpoints and MCP tools with a singl…
  api_count: 1
  score_band: thin
  score_composite: 27.2
  shared: 2
- slug: secfeedapi-com
  name: secfeedapi-com
  description: SecFeed provides a comprehensive SEC EDGAR data API delivering filings, insider trades, 13F holdings, and XBRL financials as clean JSON. The service offers REST endpoints, real‑time streaming, and MCP access, covering all SEC filing types…
  api_count: 1
  score_band: emerging
  score_composite: 25.5
  shared: 2
- slug: alphacreek-ai
  name: AlphaCreek
  description: AlphaCreek provides a hosted MCP that gives financial AI agents structured, citation‑ready SEC filing data. Covering over 6,000 US tickers, it offers fast retrieval, citation URLs, and seamless integration for Claude, Perplexity, ChatGPT a…
  api_count: 1
  score_band: emerging
  score_composite: 23.8
  shared: 2
- slug: ifrcoworker-app
  name: ifrCoworker
  description: ifrCoworker provides a rule‑based accounting colleague for AI agents, offering real‑time financial reporting, automated journal entries, XBRL tagging, and disclosure checklists. It integrates via MCP, A2A, and REST APIs, supporting continu…
  api_count: 2
  score_band: emerging
  score_composite: 21.2
  shared: 2
- slug: inscopehq
  name: Inscope
  description: Inscope is an AI-powered financial reporting and automation platform for accounting firms and enterprise finance teams. It drafts accurate, GAAP-compliant financial statements, cash flow statements, and audit workpapers in minutes, keeping…
  api_count: 0
  score_band: emerging
  score_composite: 19.8
  shared: 2
- slug: holdingsintel-com
  name: HoldingsIntel
  description: HoldingsIntel combines SEC EDGAR filings (13F, Form 4, 13D/13G) with House and Senate STOCK Act disclosures into smart‑money intelligence for retail stock traders. It tracks what 563 funds (~89% of US 13F capital, $70.7T) are buying, plus…
  api_count: 1
  score_band: emerging
  score_composite: 18.9
  shared: 2
- slug: meritvalue-com
  name: MeritValue
  description: MeritValue provides a free, deterministic valuation engine that calculates intrinsic stock values for over 6,000 US‑listed companies using SEC filing data. The platform updates nightly, offering detailed financial metrics, cash‑flow analys…
  api_count: 1
  score_band: emerging
  score_composite: 16.8
  shared: 2
---
