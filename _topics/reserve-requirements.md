---
layout: topic
slug: reserve-requirements
name: Reserve Requirements
kind: topic
description: Reserve Requirements refers to the Federal Reserve's Regulation D framework governing reserve requirement ratios for depository institutions. As of March 26, 2020, the Federal Reserve reduced all reserve requirement ratios to zero percent, eliminating reserve requirements for all depository institutions. The Federal Reserve provides data access through FRED (Federal Reserve Economic Data), the H.6 Money Stock Measures release, and the federalreserve.gov data download program for historical reserve and monetary base data.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/reserve-requirements.png
tags:
- Reserve Requirements
- Federal Reserve
- Banking Regulation
- Monetary Policy
- Regulation D
- Finance
repo: https://github.com/api-evangelist/reserve-requirements
api_count: 5
apis:
- name: Federal Reserve Data Download Program
  description: The Federal Reserve Board's Data Download Program provides structured access to Federal Reserve statistical releases including Regulation D reserve requirement data, H.6 Money Stock Measures, and historical reserve data through a web-based…
  url: https://www.federalreserve.gov/datadownload/
- name: Reserve Requirements Categories API
  description: Browse FRED data categories.
  url: https://fred.stlouisfed.org/
- name: Reserve Requirements Observations API
  description: Retrieve data observations for a series.
  url: https://fred.stlouisfed.org/
- name: Reserve Requirements Releases API
  description: Access Federal Reserve statistical releases.
  url: https://fred.stlouisfed.org/
- name: Reserve Requirements Series API
  description: Search and retrieve economic data time series.
  url: https://fred.stlouisfed.org/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/reserve-requirements/blob/main/agentic-access/reserve-requirements-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/reserve-requirements/blob/main/security/reserve-requirements-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/reserve-requirements/blob/main/authentication/reserve-requirements-authentication.yml
- type: Website
  url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm
- type: Documentation
  url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm
- type: Policy
  url: https://www.federalreserve.gov/monetarypolicy/reservereq.htm
- type: Regulation
  url: https://www.ecfr.gov/current/title-12/chapter-II/subchapter-A/part-204
- type: DataDownload
  url: https://www.federalreserve.gov/datadownload/
- type: FRED
  url: https://fred.stlouisfed.org/categories/32217
- type: H6Release
  url: https://www.federalreserve.gov/releases/h6/
- type: GitHubOrganization
  url: https://github.com/federalreserve
provider_count: 2
providers:
- slug: mandatory-reserves-requirement
  name: Mandatory Reserves Requirement
  description: A central bank regulation requiring commercial banks to hold a minimum percentage of customer deposits as reserves, either as cash in their vaults or as deposits with the central bank, to ensure liquidity and stability in the banking syste…
  api_count: 0
  score_band: minimal
  score_composite: 0.9
  shared: 3
- slug: fred
  name: FRED
  description: The Federal Reserve Economic Data (FRED) API is a public web service operated by the Research Division of the Federal Reserve Bank of St. Louis. It provides programmatic access to more than 800,000 economic time series drawn from 100+ data…
  api_count: 10
  score_band: developing
  score_composite: 39.4
  shared: 2
---
