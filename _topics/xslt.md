---
layout: topic
slug: xslt
name: XSLT
kind: topic
description: XSLT (Extensible Stylesheet Language Transformations) is a W3C standard language for transforming XML documents into other formats such as HTML, plain text, or different XML structures. It uses template-based rules and XPath expressions to select and restructure XML data. The current version is XSLT 3.0, a W3C Recommendation since June 2017. XSLT is commonly used in data integration, document publishing, and enterprise data exchange pipelines. The primary production implementation is Saxon by Saxonica, which supports XSLT 3.0, XQuery 3.1, and XPath 3.1.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/xslt.png
tags:
- Data Transformation
- Standards
- W3C
- XML
- XSLT
- XPath
repo: https://github.com/api-evangelist/xslt
api_count: 3
apis:
- name: XSLT 3.0
  description: XSLT 3.0 is the current W3C Recommendation for XSL Transformations, published June 8, 2017. It introduces streaming support, maps and arrays, higher-order functions, improved modularity, and enhanced error handling over XSLT 2.0. The speci…
  url: https://www.w3.org/TR/xslt-30/
- name: XSLT 2.0
  description: XSLT 2.0 is a W3C Recommendation published January 23, 2007. It significantly enhanced XSLT 1.0 with type system integration from XML Schema, grouping, multiple result documents, regular expressions, improved string handling, and user-defi…
  url: https://www.w3.org/TR/xslt20/
- name: XSLT 1.0
  description: XSLT 1.0 is the foundational W3C Recommendation for XSL Transformations, published November 16, 1999. It established the template-based transformation model using XPath 1.0 for node selection. XSLT 1.0 is still widely supported by all majo…
  url: https://www.w3.org/TR/xslt-10/
links:
- type: IssueTracker
  url: https://github.com/Saxonica/Saxon-HE/issues
- type: Releases
  url: https://github.com/Saxonica/Saxon-HE/releases
- type: DomainSecurity
  url: https://github.com/api-evangelist/xslt/blob/main/security/xslt-domain-security.yml
- type: Website
  url: https://www.w3.org/TR/xslt/
- type: Documentation
  url: https://www.w3.org/TR/xslt-30/
- type: GitHubOrganization
  url: https://github.com/w3c
- type: GitHubRepository
  url: https://github.com/Saxonica/Saxon-HE
- type: Specification
  url: https://www.w3.org/TR/xslt-30/
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-schema/xslt-stylesheet-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-schema/xslt-transformation-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-structure/xslt-stylesheet-structure.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-structure/xslt-transformation-structure.json
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/examples/xslt-stylesheet-example.json
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/examples/xslt-transformation-example.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/json-ld/xslt-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/xslt/refs/heads/main/vocabulary/xslt-vocabulary.yml
provider_count: 4
providers:
- slug: acord
  name: ACORD
  description: ACORD is the global standards-setting body for the insurance industry, publishing the data standards that insurers, reinsurers, brokers, MGAs and software vendors use to exchange policy, claims, party, underwriting, accounting and settleme…
  api_count: 6
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: opentravel-alliance
  name: OpenTravel Alliance
  description: The OpenTravel Alliance is a volunteer, non-profit travel technology standards body headquartered in Melbourne, Florida, United States. Since 1999 it has published the OpenTravel Specification — the OTA 1.0 XML message suite (releases 2001…
  api_count: 8
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: w3c
  name: W3C
  description: The World Wide Web Consortium (W3C) is the main international standards body for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web standards and guidelines to ensure the long-term growth of the Web, focusing on acces…
  api_count: 1
  score_band: emerging
  score_composite: 26.0
  shared: 2
- slug: mismo
  name: MISMO
  description: MISMO — the Mortgage Industry Standards Maintenance Organization — is the standards development body for US real estate finance, founded in 1999 and a not-for-profit wholly owned subsidiary of the Mortgage Bankers Association since 2004. I…
  api_count: 0
  score_band: minimal
  score_composite: 6.7
  shared: 2
---
