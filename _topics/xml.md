---
layout: topic
slug: xml
name: XML
kind: topic
description: XML (Extensible Markup Language) is a W3C standard markup language and data format that defines rules for encoding documents in a way that is both human-readable and machine-readable. Originally published as a W3C Recommendation in 1998 (XML 1.0), XML provides the foundation for a wide ecosystem of related standards including XML Schema, XSLT, XPath, XQuery, SOAP, XHTML, SVG, RSS, Atom, and many domain-specific vocabularies. XML remains a core data interchange format for enterprise systems, web services, configuration, and document publishing.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/xml.png
tags:
- Data Formats
- Documents
- Markup Language
- Standards
- W3C
- Web Services
- XML
repo: https://github.com/api-evangelist/xml
api_count: 4
apis:
- name: XML 1.0
  description: Extensible Markup Language (XML) 1.0 is the foundational W3C Recommendation defining the syntax and processing model for XML documents. First published in 1998 and now in its Fifth Edition (2008), XML 1.0 specifies well-formedness, validit…
  url: https://www.w3.org/TR/xml/
- name: XML 1.1
  description: Extensible Markup Language (XML) 1.1 is a W3C Recommendation published in 2006 that extends XML 1.0 to support newer Unicode versions, additional line ending characters, and a broader set of name characters. XML 1.1 is rarely deployed in p…
  url: https://www.w3.org/TR/xml11/
- name: XML Namespaces
  description: Namespaces in XML 1.0 (Third Edition) is the W3C Recommendation that defines a mechanism for qualifying element and attribute names in XML documents using URI references. XML Namespaces allow vocabularies from different sources to be combi…
  url: https://www.w3.org/TR/xml-names/
- name: XML Schema (XSD)
  description: XML Schema Definition Language (XSD) is the W3C Recommendation for describing the structure and constraints of XML documents using an XML-based grammar. XSD 1.1 is the current version and provides element/attribute declarations, complex an…
  url: https://www.w3.org/XML/Schema
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/xml/blob/main/security/xml-domain-security.yml
- type: Website
  url: https://www.w3.org/XML/
- type: Documentation
  url: https://www.w3.org/TR/xml/
- type: Specification
  url: https://www.w3.org/TR/xml/
- type: GitHubOrganization
  url: https://github.com/w3c
- type: GitHubRepository
  url: https://github.com/w3c/xml
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-schema/xml-document-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-schema/xml-element-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-structure/xml-document-structure.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/json-ld/xml-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/xml/refs/heads/main/vocabulary/xml-vocabulary.yml
provider_count: 11
providers:
- slug: jax-ws
  name: JAX-WS
  description: JAX-WS (Java API for XML Web Services) is a Java standard for building and consuming SOAP-based XML web services. Originally specified as JSR 224 under the Java Community Process, JAX-WS is now part of Jakarta EE as Jakarta XML Web Service…
  api_count: 3
  score_band: emerging
  score_composite: 12.9
  shared: 3
- slug: acord
  name: ACORD
  description: ACORD is the global standards-setting body for the insurance industry, publishing the data standards that insurers, reinsurers, brokers, MGAs and software vendors use to exchange policy, claims, party, underwriting, accounting and settleme…
  api_count: 6
  score_band: strong
  score_composite: 55.3
  shared: 2
- slug: opentravel-alliance
  name: OpenTravel Alliance
  description: The OpenTravel Alliance is a volunteer, non-profit travel technology standards body headquartered in Melbourne, Florida, United States. Since 1999 it has published the OpenTravel Specification — the OTA 1.0 XML message suite (releases 2001…
  api_count: 8
  score_band: developing
  score_composite: 44.3
  shared: 2
- slug: w3c
  name: W3C
  description: The World Wide Web Consortium (W3C) is the main international standards body for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web standards and guidelines to ensure the long-term growth of the Web, focusing on acces…
  api_count: 1
  score_band: thin
  score_composite: 28.1
  shared: 2
- slug: soap
  name: SOAP
  description: SOAP (Simple Object Access Protocol) is an XML-based messaging protocol for exchanging structured information in web services, standardized by W3C as SOAP 1.2 (2003). It provides a platform-independent, language-neutral framework for web s…
  api_count: 1
  score_band: emerging
  score_composite: 22.0
  shared: 2
- slug: rss
  name: RSS
  description: RSS (Really Simple Syndication) is the canonical XML feed format family for publishing and subscribing to streams of frequently updated content — blogs, news, podcasts, and other periodic resources. The RSS family in this index covers RSS…
  api_count: 6
  score_band: emerging
  score_composite: 19.5
  shared: 2
- slug: mismo
  name: MISMO
  description: MISMO — the Mortgage Industry Standards Maintenance Organization — is the standards development body for US real estate finance, founded in 1999 and a not-for-profit wholly owned subsidiary of the Mortgage Bankers Association since 2004. I…
  api_count: 0
  score_band: minimal
  score_composite: 8.8
  shared: 2
- slug: dfdl
  name: DFDL
  description: Data Format Description Language (DFDL) is an open standard for describing data formats used in binary and text files and data streams. DFDL is used to describe the format of existing data so that it can be parsed or unparsed (generated) u…
  api_count: 0
  score_band: minimal
  score_composite: 7.2
  shared: 2
- slug: html
  name: HTML
  description: HTML (HyperText Markup Language) is the standard markup language for creating web pages and web applications. Maintained as a Living Standard by WHATWG and developed in close coordination with the W3C, HTML defines the structure and semant…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 2
- slug: html5
  name: HTML5
  description: HTML5 is the fifth major version of the HyperText Markup Language used for structuring and presenting content on the web. Standardized by the W3C in 2014 and now maintained by WHATWG as the HTML Living Standard, HTML5 introduced semantic e…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 2
- slug: markup-language
  name: Markup Language
  description: A markup language is a system for annotating a document in a way that is syntactically distinguishable from the text. Examples include HTML, XML, Markdown, LaTeX, and others that add semantic meaning or formatting instructions to text cont…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
---
