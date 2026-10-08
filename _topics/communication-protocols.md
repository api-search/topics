---
layout: topic
slug: communication-protocols
name: Communication Protocols
kind: topic
description: Communication protocols are systems of rules that allow two or more entities in a networked system to exchange information. Modern API platforms rely on layered protocol stacks that span the physical and link layers, network and transport layers, and application protocols such as HTTP, gRPC, MQTT, AMQP, WebSockets, SSE, and Webhooks. The communication protocols topic surveys the most relevant standards bodies (IETF, W3C, IEEE, ITU, ISO), the most widely deployed protocols at each layer, and the way protocol choice shapes API design, performance, security, and interoperability.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/communication-protocols.png
tags:
- Application Protocols
- Communication Protocols
- Internet
- IETF
- Networking
- Real-Time
- Standards
- Transport
- Web
repo: https://github.com/api-evangelist/communication-protocols
api_count: 7
apis:
- name: gRPC
  description: A high-performance, contract-first RPC framework built on HTTP/2 with Protocol Buffers as the default IDL. gRPC supports unary, server streaming, client streaming, and bidirectional streaming and is widely used for microservice-to-microser…
  url: https://grpc.io/
- name: GraphQL
  description: A query language and runtime for client-driven data APIs over HTTP and WebSockets. GraphQL exposes a single endpoint with a typed schema defining queries, mutations, and subscriptions, allowing clients to request precisely the data they ne…
  url: https://graphql.org/
- name: WebSocket
  description: A bidirectional, full-duplex communication protocol over a single TCP connection, defined in RFC 6455. WebSocket upgrades from HTTP and is widely used for chat, collaborative editing, live dashboards, and game servers.
  url: https://www.rfc-editor.org/rfc/rfc6455
- name: MQTT
  description: A lightweight publish-subscribe messaging protocol designed for constrained devices and unreliable networks. MQTT is an OASIS standard and is widely used in IoT, automotive, and edge environments. MQTT 5 adds user properties, reason codes,…
  url: https://mqtt.org/
- name: AMQP
  description: The Advanced Message Queuing Protocol, an OASIS standard for interoperable, broker-mediated messaging. AMQP 1.0 defines a wire protocol with strong typing, links, sessions, and connection-level security and is used by RabbitMQ, Azure Servi…
  url: https://www.amqp.org/
- name: Webhooks
  description: An HTTP-based pattern for delivering event notifications from one service to another by performing an outbound HTTP POST to a URL registered by the consumer. Webhooks are not a single specification but the broader pattern is increasingly g…
  url: https://webhooks.fyi/
- name: Server-Sent Events (SSE)
  description: A simple, one-way, server-to-client streaming protocol defined as part of the HTML living standard. SSE runs over plain HTTP, supports automatic reconnection, and is widely used for live status feeds and LLM token streaming.
  url: https://html.spec.whatwg.org/multipage/server-sent-events.html
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/communication-protocols/blob/main/security/communication-protocols-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/communication-protocols/blob/main/security/communication-protocols-domain-security.yml
- type: Documentation
  url: https://www.iana.org/assignments/uri-schemes/uri-schemes.xhtml
- type: Reference
  url: https://www.rfc-editor.org/standards
- type: Reference
  url: https://www.iso.org/standard/74534.html
- type: Reference
  url: https://en.wikipedia.org/wiki/Communication_protocol
- type: Resources
  url: https://www.cncf.io/
- type: ProductPage
  url: https://httpwg.org/specs/
provider_count: 10
providers:
- slug: openadr-alliance
  name: OpenADR Alliance
  description: The OpenADR Alliance is a San Ramon, California mutual-benefit membership corporation that develops, certifies, and promotes OpenADR, the open information-exchange model utilities, ISOs/RTOs, aggregators, and device makers use to automate…
  api_count: 4
  score_band: strong
  score_composite: 54.5
  shared: 2
- slug: firebase
  name: Firebase
  description: Firebase is Google's app development platform — a backend-as-a-service (BaaS) suite for building, running, and growing web and mobile apps. It bundles managed backend products including Authentication, Cloud Firestore, Realtime Database, C…
  api_count: 4
  score_band: developing
  score_composite: 46.0
  shared: 2
- slug: transportapi
  name: TransportAPI
  description: TransportAPI is a managed data service provider for UK public transport, offering real-time and scheduled bus, rail, and multimodal transport data via REST and WebSocket APIs to power apps, websites, analytics, and data-mining workflows.
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: lumen-technologies
  name: Lumen Technologies
  description: Lumen Technologies is a multinational technology company that delivers networking, edge cloud, security, communication and collaboration, and managed and professional services to global enterprises and consumers. Through its Developer Cent…
  api_count: 1
  score_band: thin
  score_composite: 31.6
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
- slug: websockets
  name: WebSockets
  description: WebSockets is a communication protocol providing full-duplex communication channels over a single TCP connection, enabling real-time data exchange between client and server. Standardized by RFC 6455 and the WHATWG Living Standard, it is fu…
  api_count: 0
  score_band: emerging
  score_composite: 19.2
  shared: 2
- slug: http-2
  name: HTTP/2
  description: HTTP/2 is the second major version of the Hypertext Transfer Protocol, defined by the IETF in RFC 7540 and standardized in 2015. It optimizes use of network resources and reduces perceived latency by introducing a binary framing layer over…
  api_count: 0
  score_band: minimal
  score_composite: 4.2
  shared: 2
- slug: sockeye-networks
  name: Sockeye Networks
  description: Sockeye Networks was a network-management software company founded in 2000 and headquartered in Waltham, Massachusetts. It provided intelligent internet routing and connectivity-optimization services, combining real-time global internet tr…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 2
- slug: subspace
  name: Subspace
  description: Subspace was a real-time network-as-a-service platform delivering a dedicated, performance-optimized global network for latency-sensitive applications — WebRTC, VoIP/SIP calling, video conferencing, multiplayer gaming, and fintech. Its Pro…
  api_count: 1
  score_band: minimal
  score_composite: 0
  shared: 2
---
