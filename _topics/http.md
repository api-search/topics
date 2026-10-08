---
layout: topic
slug: http
name: HTTP
kind: topic
description: HTTP (Hypertext Transfer Protocol) is the foundation-level protocol for data communication on the World Wide Web, defining how messages are formatted and transmitted between clients and servers. It operates as a request-response protocol enabling browsers, APIs, and other clients to interact with web servers using standard methods like GET, POST, PUT, and DELETE.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/http.png
tags:
- Networking
- Protocol
- Standards
- Web
repo: https://github.com/api-evangelist/http
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/http/blob/main/security/http-domain-security.yml
- type: GitHubOrganization
  url: https://github.com/httpwg
- type: Website
  url: https://developer.mozilla.org/en-US/docs/Web/HTTP
- type: Reference
  url: https://httpwg.org/specs/
- type: JSONLDContext
  url: https://github.com/api-evangelist/http/blob/main/json-ld/http-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/http/blob/main/json-schema/http-request.json
- type: JSONSchema
  url: https://github.com/api-evangelist/http/blob/main/json-schema/http-response.json
- type: JSONSchema
  url: https://github.com/api-evangelist/http/blob/main/json-schema/http-problem-details.json
- type: Rules
  url: https://github.com/api-evangelist/http/blob/main/rules/http-rules.yml
provider_count: 5
providers:
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
- slug: internet-assigned-numbers-authority
  name: Internet Assigned Numbers Authority
  description: The Internet Assigned Numbers Authority (IANA) performs the global coordination of the DNS Root, IP addressing, and other Internet protocol resources. IANA maintains the protocol registries, top-level domain delegations, time zone database…
  api_count: 3
  score_band: emerging
  score_composite: 12.7
  shared: 2
- slug: http-2
  name: HTTP/2
  description: HTTP/2 is the second major version of the Hypertext Transfer Protocol, defined by the IETF in RFC 7540 and standardized in 2015. It optimizes use of network resources and reduces perceived latency by introducing a binary framing layer over…
  api_count: 0
  score_band: minimal
  score_composite: 4.2
  shared: 2
- slug: messaging-protocol
  name: Messaging Protocol
  description: Messaging Protocol is a networking technology or protocol that facilitates communication, data transfer, or traffic management between systems and devices. Examples include AMQP, MQTT, STOMP, and other protocols that enable reliable, effic…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 2
---
