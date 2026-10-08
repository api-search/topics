---
layout: topic
slug: tcp-ip
name: TCP/IP
kind: topic
description: TCP/IP (Transmission Control Protocol/Internet Protocol) is the foundational communication protocol suite that powers the internet and most computer networks. It provides reliable, ordered delivery of data between applications across diverse network hardware through a layered architecture of protocols. The suite encompasses protocols at multiple layers including TCP, IP, UDP, HTTP, and many others, defined through IETF RFCs maintained at the RFC Editor.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/tcp-ip.png
tags:
- Networking
- Protocol
- Internet
- Standards
- IETF
- RFC
- TCP
- IP
repo: https://github.com/api-evangelist/tcp-ip
api_count: 1
apis:
- name: Berkeley Sockets API
  description: The de facto standard programming interface for TCP/IP networking, defined in RFC 3493. Implemented nearly ubiquitously in modern operating systems and programming languages, the Sockets API provides functions for creating network connecti…
  url: https://www.rfc-editor.org/rfc/rfc3493
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/tcp-ip/blob/main/security/tcp-ip-domain-security.yml
- type: Documentation
  url: https://www.rfc-editor.org/
- type: Documentation
  url: https://datatracker.ietf.org/
- type: Specification
  url: https://www.rfc-editor.org/rfc/rfc9293
- type: Specification
  url: https://www.rfc-editor.org/rfc/rfc791
- type: Specification
  url: https://www.rfc-editor.org/rfc/rfc768
- type: Specification
  url: https://www.rfc-editor.org/rfc/rfc1180
- type: Specification
  url: https://www.rfc-editor.org/rfc/rfc3493
- type: Specification
  url: https://www.rfc-editor.org/rfc/rfc4614
- type: Website
  url: https://www.ietf.org/
provider_count: 8
providers:
- slug: internet-engineering-task-force
  name: Internet Engineering Task Force
  description: The Internet Engineering Task Force (IETF) is an open, global community of network designers, engineers, researchers, and operators that develops and promotes voluntary technical standards to ensure the smooth operation and evolution of th…
  api_count: 6
  score_band: thin
  score_composite: 28.4
  shared: 4
- slug: http-2
  name: HTTP/2
  description: HTTP/2 is the second major version of the Hypertext Transfer Protocol, defined by the IETF in RFC 7540 and standardized in 2015. It optimizes use of network resources and reduces perceived latency by introducing a binary framing layer over…
  api_count: 0
  score_band: minimal
  score_composite: 4.2
  shared: 3
- slug: lumen-technologies
  name: Lumen Technologies
  description: Lumen Technologies is a multinational technology company that delivers networking, edge cloud, security, communication and collaboration, and managed and professional services to global enterprises and consumers. Through its Developer Cent…
  api_count: 1
  score_band: thin
  score_composite: 31.6
  shared: 2
- slug: smtp
  name: SMTP
  description: Simple Mail Transfer Protocol (SMTP) is the foundational internet standard for transmitting electronic mail across networks. Defined in RFC 5321 (October 2008), SMTP uses a command-response model over TCP port 25 (or 587 for submission, 46…
  api_count: 2
  score_band: emerging
  score_composite: 13.0
  shared: 2
- slug: internet-assigned-numbers-authority
  name: Internet Assigned Numbers Authority
  description: The Internet Assigned Numbers Authority (IANA) performs the global coordination of the DNS Root, IP addressing, and other Internet protocol resources. IANA maintains the protocol registries, top-level domain delegations, time zone database…
  api_count: 3
  score_band: emerging
  score_composite: 12.7
  shared: 2
- slug: snmp
  name: SNMP
  description: Simple Network Management Protocol (SNMP) is the foundational IETF standard for monitoring and managing network devices. SNMP defines a request/response protocol over UDP (ports 161 and 162) for retrieving and altering management variables…
  api_count: 5
  score_band: minimal
  score_composite: 10.8
  shared: 2
- slug: messaging-protocol
  name: Messaging Protocol
  description: Messaging Protocol is a networking technology or protocol that facilitates communication, data transfer, or traffic management between systems and devices. Examples include AMQP, MQTT, STOMP, and other protocols that enable reliable, effic…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 2
- slug: sockeye-networks
  name: Sockeye Networks
  description: Sockeye Networks was a network-management software company founded in 2000 and headquartered in Waltham, Massachusetts. It provided intelligent internet routing and connectivity-optimization services, combining real-time global internet tr…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 2
---
