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
- type: DomainSecurity
  url: https://github.com/api-evangelist/accounting-standards/blob/main/security/accounting-standards-domain-security.yml
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
  url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/json-ld/accounting-standards-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/accounting-standards/refs/heads/main/vocabulary/accounting-standards-vocabulary.yaml
provider_count: 2
providers:
- slug: sec
  name: SEC EDGAR
  description: The U.S. Securities and Exchange Commission (SEC) EDGAR (Electronic Data Gathering, Analysis, and Retrieval) system provides free public access to corporate financial filings submitted to the SEC. The EDGAR REST API at data.sec.gov deliver…
  api_count: 3
  score_band: developing
  score_composite: 41.9
  shared: 3
- slug: inscopehq
  name: Inscope
  description: Inscope is an AI-powered financial reporting and automation platform for accounting firms and enterprise finance teams. It drafts accurate, GAAP-compliant financial statements, cash flow statements, and audit workpapers in minutes, keeping…
  api_count: 0
  score_band: emerging
  score_composite: 18.1
  shared: 2
---
