---
layout: topic
slug: wsdl
name: WSDL
kind: topic
description: WSDL (Web Services Description Language) is a W3C standard XML format for describing web service interfaces. It defines services as collections of network endpoints (ports) that exchange messages, specifying the abstract operations, message formats, and protocol bindings needed to interact with a web service. WSDL 2.0 became a W3C Recommendation on June 26, 2007, and adds support for all HTTP request methods, making it more suitable for RESTful web services than its predecessor WSDL 1.1.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/wsdl.png
tags:
- Service Description
- W3C
- Web Services
- WSDL
- XML
- SOAP
- Standards
- Protocol
repo: https://github.com/api-evangelist/wsdl
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/wsdl/blob/main/security/wsdl-domain-security.yml
- type: Specification
  url: https://www.w3.org/TR/wsdl20/
- type: Specification
  url: https://www.w3.org/TR/wsdl20-adjuncts/
- type: Specification
  url: https://www.w3.org/TR/wsdl20-primer/
- type: Specification
  url: https://www.w3.org/TR/wsdl20-rdf/
- type: Website
  url: https://www.w3.org/standards/techs/wsdl
- type: Documentation
  url: https://www.w3.org/TR/?tag=webservice
- type: GitHubOrganization
  url: https://github.com/w3c
- type: Community
  url: https://lists.w3.org/Archives/Public/public-ws-desc/
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-description.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-types.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-interface.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-operation.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-interface-fault.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-binding.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-service.json
- type: JSONSchema
  url: https://github.com/api-evangelist/wsdl/blob/main/json-schema/wsdl-endpoint.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/wsdl/blob/main/json-ld/wsdl-context.jsonld
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-description-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-types-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-interface-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-operation-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-interface-fault-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-binding-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-service-structure.json
- type: JSONStructure
  url: https://github.com/api-evangelist/wsdl/blob/main/json-structure/wsdl-endpoint-structure.json
- type: Vocabulary
  url: https://github.com/api-evangelist/wsdl/blob/main/vocabulary/wsdl-vocabulary.yaml
provider_count: 10
providers:
- slug: soap
  name: SOAP
  description: SOAP (Simple Object Access Protocol) is an XML-based messaging protocol for exchanging structured information in web services, standardized by W3C as SOAP 1.2 (2003). It provides a platform-independent, language-neutral framework for web s…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 3
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
- slug: apache-cxf
  name: Apache CXF
  description: Apache CXF is an open-source Java services framework governed by the Apache Software Foundation that helps build and develop web services using JAX-WS (SOAP) and JAX-RS (REST) frontend APIs. It supports contract-first (WSDL) and code-first…
  api_count: 1
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: internet-engineering-task-force
  name: Internet Engineering Task Force
  description: The Internet Engineering Task Force (IETF) is an open, global community of network designers, engineers, researchers, and operators that develops and promotes voluntary technical standards to ensure the smooth operation and evolution of th…
  api_count: 6
  score_band: thin
  score_composite: 28.4
  shared: 2
- slug: w3c
  name: W3C
  description: The World Wide Web Consortium (W3C) is the main international standards body for the World Wide Web, founded by Tim Berners-Lee in 1994. W3C develops web standards and guidelines to ensure the long-term growth of the Web, focusing on acces…
  api_count: 1
  score_band: emerging
  score_composite: 26.0
  shared: 2
- slug: soa
  name: SOA
  description: Service-Oriented Architecture (SOA) is an architectural style for building software applications as a collection of loosely coupled, interoperable services. Each service encapsulates a specific business capability and communicates with oth…
  api_count: 1
  score_band: emerging
  score_composite: 20.5
  shared: 2
- slug: internet-assigned-numbers-authority
  name: Internet Assigned Numbers Authority
  description: The Internet Assigned Numbers Authority (IANA) performs the global coordination of the DNS Root, IP addressing, and other Internet protocol resources. IANA maintains the protocol registries, top-level domain delegations, time zone database…
  api_count: 3
  score_band: emerging
  score_composite: 12.7
  shared: 2
- slug: mismo
  name: MISMO
  description: MISMO — the Mortgage Industry Standards Maintenance Organization — is the standards development body for US real estate finance, founded in 1999 and a not-for-profit wholly owned subsidiary of the Mortgage Bankers Association since 2004. I…
  api_count: 0
  score_band: minimal
  score_composite: 6.7
  shared: 2
- slug: resware
  name: ResWare
  description: ResWare is customizable title and escrow production software for real estate closings, originally built by Adeptive Software Corporation and acquired by Qualia Labs in December 2020 (now shipping as ResWare 10 within the Qualia ecosystem).…
  api_count: 7
  score_band: minimal
  score_composite: 6.7
  shared: 2
---
