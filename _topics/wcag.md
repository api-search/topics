---
layout: topic
slug: wcag
name: WCAG
kind: topic
description: Web Content Accessibility Guidelines (WCAG) are a set of international standards published by the W3C Web Accessibility Initiative (WAI) for making web content accessible to people with disabilities. WCAG covers a wide range of recommendations across four principles (Perceivable, Operable, Understandable, Robust), with conformance levels A, AA, and AAA. WCAG 2.2 (ISO/IEC 40500:2025) is the current standard, while WCAG 3.0 is in active development targeting broader coverage of websites, mobile apps, VR environments, and digital documents.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/wcag.png
tags:
- Accessibility
- W3C
- WCAG
- Web Standards
- Disability
- Inclusive Design
repo: https://github.com/api-evangelist/wcag
api_count: 4
apis:
- name: WCAG 2.2
  description: Web Content Accessibility Guidelines 2.2, the current stable version and ISO/IEC 40500:2025 standard. Introduces 9 new success criteria beyond WCAG 2.1, including focus appearance, dragging movements, and consistent help. Organized into fo…
  url: https://www.w3.org/TR/WCAG22/
- name: WCAG 3.0
  description: W3C Accessibility Guidelines 3.0 (working draft), expanding scope beyond web content to cover mobile apps, VR, authoring tools, and digital documents. Introduces outcome-based testing and a new scoring model. Working Draft published Januar…
  url: https://www.w3.org/WAI/standards-guidelines/wcag/wcag3-intro/
- name: WAI-ARIA
  description: Accessible Rich Internet Applications (WAI-ARIA) 1.2 specification providing semantic roles, states, and properties for accessible user interface components. Includes API mappings for browsers and assistive technologies.
  url: https://www.w3.org/TR/wai-aria/
- name: Accessibility Conformance Testing (ACT) Rules
  description: ACT Rules provide machine-executable rules for testing WCAG 2.x conformance, enabling consistent automated and manual accessibility evaluation across tools and methodologies.
  url: https://www.w3.org/WAI/standards-guidelines/act/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/wcag/blob/main/security/wcag-domain-security.yml
- type: Website
  url: https://www.w3.org/WAI/
- type: Documentation
  url: https://www.w3.org/WAI/standards-guidelines/
- type: GitHubOrganization
  url: https://github.com/w3c
- type: Tools
  url: https://www.w3.org/WAI/test-evaluate/tools/list/
- type: Tools
  url: https://github.com/w3c/wcag-em-report-tool
- type: Vocabulary
  url: https://github.com/api-evangelist/wcag/blob/main/vocabulary/wcag-vocabulary.yml
- type: JSONLD
  url: https://github.com/api-evangelist/wcag/blob/main/json-ld/wcag-context.jsonld
provider_count: 7
providers:
- slug: w3c
  name: W3C
  description: The World Wide Web Consortium (W3C) is the main international standards body for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web standards and guidelines to ensure the long-term growth of the Web, focusing on acces…
  api_count: 1
  score_band: emerging
  score_composite: 26.0
  shared: 3
- slug: accessibe
  name: accessiBe
  description: accessiBe is a web accessibility technology company whose products help organizations make websites and web applications usable by people with disabilities and compliant with WCAG, the ADA, Section 508, AODA and the European Accessibility…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: stark
  name: Stark
  description: Stark is a digital accessibility compliance platform used by more than 50,000 companies as their accessibility infrastructure across the entire software product lifecycle, from issue detection and remediation to insights and governance. St…
  api_count: 0
  score_band: emerging
  score_composite: 20.7
  shared: 2
- slug: u-s-access-board
  name: U.S. Access Board
  description: The U.S. Access Board is an independent federal agency that promotes equality for people with disabilities through the development of accessibility guidelines and standards. The Board develops criteria for accessibility in the built enviro…
  api_count: 0
  score_band: emerging
  score_composite: 19.9
  shared: 2
- slug: echo-labs
  name: Echo Labs
  description: Echo Labs is a San Francisco-based company building AI-powered media accessibility for higher education. Its platform audits, captions, and audio describes entire institutional video libraries within 24 hours, producing ADA / Title II and…
  api_count: 0
  score_band: minimal
  score_composite: 6.7
  shared: 2
- slug: html
  name: HTML
  description: HTML (HyperText Markup Language) is the standard markup language for creating web pages and web applications. Maintained as a Living Standard by WHATWG and developed in close coordination with the W3C, HTML defines the structure and semant…
  api_count: 0
  score_band: minimal
  score_composite: 4.8
  shared: 2
- slug: user1st
  name: User1st
  description: User1st is a web and mobile digital accessibility company whose U1 Suite gives organizations an efficient path to WCAG, ADA, and European Accessibility Act (EAA) compliance. It provides accessibility toolkits and remediation across web fra…
  api_count: 0
  score_band: minimal
  score_composite: 4.6
  shared: 2
---
