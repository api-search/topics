---
layout: topic
slug: realtime
name: Realtime
kind: topic
description: A topic catalog of realtime APIs, protocols, providers, and patterns. Realtime distinguishes itself from streaming by being interactive and typically bidirectional — channels, presence, signaling, and message envelopes flowing in both directions between clients and servers — where streaming is one-way firehose delivery. This index documents the major realtime protocols (WebSocket, Server-Sent Events, WebRTC, MQTT, CoAP, gRPC streaming, GraphQL Subscriptions), hosted realtime providers (Ably, Pusher, PubNub, LiveKit, Daily, Agora, Twilio, Vonage, Amazon IVS, Cloudflare Realtime), open-source frameworks (Socket.IO), and push notification systems (OneSignal, FCM, APNs, Web Push, Pushwoosh).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/realtime.png
tags:
- Real-Time
- WebSocket
- WebRTC
- Server-Sent Events
- MQTT
- Push Notifications
- Pub-Sub
- Presence
- Signaling
- Topic
repo: https://github.com/api-evangelist/realtime
api_count: 26
apis:
- name: WebSocket
  description: A full-duplex communication protocol over a single TCP connection, standardized by the IETF as RFC 6455 and defined in the WHATWG WebSocket API on the client side. WebSocket is the most widely deployed realtime protocol on the web — used f…
  url: https://datatracker.ietf.org/doc/html/rfc6455
- name: Server-Sent Events (SSE)
  description: A unidirectional server-to-client streaming protocol over HTTP, defined by the WHATWG HTML Living Standard. SSE is simpler than WebSocket — it reuses HTTP and supports automatic reconnection — but is one-way only. It has seen a resurgence…
  url: https://html.spec.whatwg.org/multipage/server-sent-events.html
- name: WebRTC
  description: A peer-to-peer realtime communication framework for audio, video, and arbitrary data channels, standardized by the W3C and IETF. WebRTC defines an SDP-based offer/answer signaling model, ICE/STUN/TURN for NAT traversal, SRTP for media, and…
  url: https://webrtc.org/
- name: MQTT
  description: A lightweight publish/subscribe protocol standardized by OASIS, designed for constrained devices and low-bandwidth networks. MQTT is the dominant realtime protocol in IoT, used by AWS IoT Core, Azure IoT Hub, Google Cloud IoT, HiveMQ, EMQX…
  url: https://mqtt.org/
- name: CoAP
  description: The Constrained Application Protocol, defined in IETF RFC 7252, is a RESTful protocol for constrained devices over UDP, with an Observe extension (RFC 7641) that provides realtime resource notification. CoAP is used in industrial IoT and L…
  url: https://datatracker.ietf.org/doc/html/rfc7252
- name: gRPC Streaming
  description: gRPC supports four call patterns — unary, server streaming, client streaming, and bidirectional streaming — all carried over HTTP/2. gRPC streams are widely used for internal service-to-service realtime communication, with gRPC-Web bridgin…
  url: https://grpc.io/docs/what-is-grpc/core-concepts/
- name: GraphQL Subscriptions
  description: A GraphQL operation type that delivers realtime updates to clients, typically carried over WebSocket using the graphql-ws or legacy graphql-transport-ws protocol, or over SSE using the GraphQL-SSE protocol. Subscriptions are supported by A…
  url: https://spec.graphql.org/October2021/#sec-Subscription
- name: WebTransport
  description: A modern web API built on HTTP/3 and QUIC providing bidirectional and unidirectional streams plus unreliable datagrams to browsers. Designed as a higher-performance successor to WebSocket for streaming workloads, supported in Chromium-base…
  url: https://www.w3.org/TR/webtransport/
- name: Ably
  description: A hosted realtime platform offering Pub/Sub Channels, Chat, Spaces, LiveObjects, LiveSync, and AI Transport — built on a global edge network with low-latency multiprotocol fanout (WebSocket, MQTT, SSE, HTTP). Anchored by the documentation…
  url: https://ably.com/
- name: PubNub
  description: A realtime platform offering Pub/Sub messaging, Presence detection, Chat SDKs, Functions (serverless), Events & Actions, Insights analytics, BizOps Workspace, Illuminate, and an Admin API. PubNub markets "Send a message via API and have it…
  url: https://www.pubnub.com/
- name: Pusher
  description: A hosted realtime API from MessageBird offering two products — Channels (pub/sub messaging) and Beams (push notifications) — under the framing "Our hosted APIs are flexible, scalable, and easy to integrate." Pusher Channels uses a propriet…
  url: https://pusher.com/
- name: LiveKit
  description: An open-source WebRTC platform marketed as "The platform for voice, video, and physical AI agents." LiveKit ships an SFU media server, Agents framework for production realtime AI, server SDKs in Go/Node/Python/Ruby, and client SDKs for Jav…
  url: https://livekit.io/
- name: Daily
  description: A WebRTC video API provider offering Prebuilt embeddable video rooms, a Client SDK for custom apps, and Realtime Transport for AI Agents — the underlying infrastructure for Pipecat-deployed voice agents. Daily frames Pipecat as "a vendor-n…
  url: https://www.daily.co/
- name: Agora.io
  description: A realtime engagement platform offering Video Calling, Voice Calling, Signaling, Chat, and a Conversational AI Engine, framed as building "cutting-edge, voice-enabled applications by merging Agora's robust real-time audio streaming with th…
  url: https://www.agora.io/
- name: Twilio Video / Live
  description: Twilio's realtime video and live streaming products. Twilio Video provides WebRTC-based group rooms and peer rooms; Twilio Live (in select markets) layers low-latency interactive live streaming on top. Both share Twilio's identity, access…
  url: https://www.twilio.com/video
- name: Vonage Video API
  description: A WebRTC video API (formerly TokBox / OpenTok) for embedding live video, audio, and screen sharing into web and mobile apps. Provides session/token-based access control, multiparty rooms, broadcasting, archiving, and SIP interop.
  url: https://www.vonage.com/communications-apis/video/
- name: Amazon Interactive Video Service (IVS)
  description: AWS's low-latency interactive video service. IVS Real-Time Streaming offers WebRTC-based stages for multi-host interactivity; IVS Low-Latency Streaming offers HLS-based one-to-many delivery. IVS Chat provides a managed realtime chat servic…
  url: https://aws.amazon.com/ivs/
- name: Cloudflare Realtime
  description: Cloudflare's realtime media stack — RealtimeKit (SDKs and APIs for live video/voice), the Realtime SFU ("a powerful media server that efficiently routes video and audio"), and a managed TURN Service for WebRTC NAT traversal over UDP/TCP/TL…
  url: https://developers.cloudflare.com/realtime/
- name: Socket.IO
  description: A widely deployed open-source realtime engine for Node.js (with clients across JavaScript, Java, Swift, Kotlin, .NET, Python) that layers reconnection, rooms, namespaces, and binary support on top of WebSocket (with HTTP long-polling fallb…
  url: https://socket.io/
- name: Phoenix Channels
  description: The realtime layer of the Elixir Phoenix Framework — soft-realtime channels, presence, and pub/sub built on the BEAM VM. Channels carry WebSocket (or long-poll fallback) topics with broadcast/subscribe semantics; Phoenix Presence implement…
  url: https://hexdocs.pm/phoenix/channels.html
- name: Centrifugo
  description: An open-source language-agnostic realtime messaging server providing WebSocket, SSE, HTTP streaming, and WebTransport transports with channel-based pub/sub, presence, history, and JWT-based access tokens. Designed to offload realtime fanou…
  url: https://centrifugal.dev/
- name: OneSignal
  description: A multichannel customer messaging platform with Push (mobile + web), Email, SMS & RCS, and In-App Messages — framed as letting teams "set up and send mobile and web push notifications with advanced targeting and automation." Provides REST…
  url: https://onesignal.com/
- name: Firebase Cloud Messaging (FCM)
  description: Google's cross-platform push notification and message delivery service for Android, iOS, and web. FCM uses HTTP v1 API for server-to-FCM message submission and a long-lived connection (XMPP-derived on Android, APNs for iOS, Web Push for br…
  url: https://firebase.google.com/products/cloud-messaging
- name: Apple Push Notification Service (APNs)
  description: Apple's push notification system for iOS, iPadOS, macOS, tvOS, watchOS, and visionOS. APNs uses an HTTP/2-based provider API with token-based or certificate-based authentication for server-to-Apple delivery, and a persistent device connect…
  url: https://developer.apple.com/documentation/usernotifications
- name: Web Push API
  description: An IETF-standardized push system for the web, comprising the W3C Push API (browser-side subscription), the IETF Web Push Protocol (RFC 8030, server-to-push-service delivery), and Message Encryption for Web Push (RFC 8291). Routed via vendo…
  url: https://www.w3.org/TR/push-api/
- name: Pushwoosh
  description: A customer engagement platform offering push notifications (mobile + web), in-app messaging, email, and SMS with segmentation, journeys, and a Customer Journey Builder. Uses native vendor push gateways (FCM, APNs, Web Push) under the hood.
  url: https://www.pushwoosh.com/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/realtime/blob/main/security/realtime-domain-security.yml
- type: Portal
  url: https://github.com/api-evangelist/realtime
- type: GitHub
  url: https://github.com/api-evangelist/realtime
- type: JSONSchema
  url: https://github.com/api-evangelist/realtime/blob/main/json-schema/realtime-channel.json
- type: JSONSchema
  url: https://github.com/api-evangelist/realtime/blob/main/json-schema/realtime-message-envelope.json
- type: JSONSchema
  url: https://github.com/api-evangelist/realtime/blob/main/json-schema/realtime-subscription.json
- type: JSONSchema
  url: https://github.com/api-evangelist/realtime/blob/main/json-schema/realtime-presence.json
- type: JSONLDContext
  url: https://github.com/api-evangelist/realtime/blob/main/json-ld/realtime-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/realtime/blob/main/vocabulary/realtime-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/realtime/blob/main/examples/
provider_count: 89
providers:
- slug: hivemq
  name: HiveMQ
  description: HiveMQ is an enterprise MQTT broker and IoT connectivity platform that provides reliable, scalable bidirectional messaging between connected devices and back-end systems using the MQTT protocol. It supports MQTT 3, MQTT 5, MQTT over WebSoc…
  api_count: 1
  score_band: developing
  score_composite: 49.2
  shared: 4
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, w…
  api_count: 2
  score_band: developing
  score_composite: 42.1
  shared: 4
- slug: pusher
  name: Pusher
  description: Pusher is a realtime communication platform owned by MessageBird/Bird. Its primary product Channels provides pub/sub messaging over WebSocket and HTTP; Beams provides device push notifications. Authentication uses an app key + secret per P…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 4
- slug: pubnub
  name: PubNub
  description: PubNub is a realtime communication platform supporting pub/sub, presence, chat, App Context (object metadata), Functions (server-less compute on the edge), Push Notifications, and IoT messaging across 1B+ devices. The PubNub REST API runs…
  api_count: 2
  score_band: thin
  score_composite: 32.6
  shared: 4
- slug: liveblocks
  name: Liveblocks
  description: Liveblocks is a real-time collaboration platform that provides ready-made building blocks for multiplayer experiences, including presence, broadcast events, shared storage (LiveObject/LiveList/LiveMap), comments and threads, notifications,…
  api_count: 1
  score_band: strong
  score_composite: 59.4
  shared: 3
- slug: microsoft-azure-web-pubsub
  name: Azure Web PubSub
  description: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to speci…
  api_count: 1
  score_band: developing
  score_composite: 50.6
  shared: 3
- slug: superviz
  name: SuperViz
  description: SuperViz provides real-time collaboration and data-synchronization infrastructure for web applications - presence, realtime data channels, video huddle/meetings, contextual comments, and mouse pointers. The product is SDK-first (@superviz/…
  api_count: 1
  score_band: thin
  score_composite: 38.9
  shared: 3
- slug: wazo
  name: Wazo
  description: Wazo Communication Inc. builds the Wazo Platform, an open-source (GPL-3.0) programmable unified-communications and contact-centre platform assembled from Asterisk, Kamailio, RabbitMQ, PostgreSQL and nginx, which MSPs, carriers, telecom int…
  api_count: 25
  score_band: thin
  score_composite: 38.4
  shared: 3
- slug: agora-io
  name: Agora
  description: Agora is a real-time engagement platform providing ultra-low latency voice, video, signaling, chat, interactive whiteboard, cloud recording, real-time speech-to-text, and conversational AI infrastructure for human-to-human and human-to-AI…
  api_count: 11
  score_band: thin
  score_composite: 30.6
  shared: 3
- slug: massive-com
  name: Massive (formerly Polygon.io)
  description: Polygon (Polygon.io, rebranded as Massive in early 2026) provides real-time and historical market data APIs across US stocks, options, indices, forex, cryptocurrencies, and futures. Coverage is delivered through REST endpoints and WebSocke…
  api_count: 7
  score_band: exemplar
  score_composite: 75.8
  shared: 2
- slug: novu
  name: Novu
  description: Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — wit…
  api_count: 1
  score_band: exemplar
  score_composite: 71.1
  shared: 2
- slug: aws-api-gateway
  name: Amazon API Gateway
  description: Amazon API Gateway is a fully managed service that makes it easy to create, publish, maintain, monitor, and secure APIs at any scale. It acts as the front door for applications to access backend services, supporting REST APIs, HTTP APIs, a…
  api_count: 13
  score_band: exemplar
  score_composite: 70.0
  shared: 2
- slug: azure-service-bus
  name: Azure Service Bus
  description: Azure Service Bus is a fully managed enterprise message broker with message queues and publish-subscribe topics, providing reliable message delivery for decoupling applications and services in cloud and hybrid environments.
  api_count: 1
  score_band: exemplar
  score_composite: 68.0
  shared: 2
- slug: kraken
  name: Kraken
  description: Kraken is one of the world's largest and longest-running cryptocurrency exchanges, founded in 2011 and headquartered in San Francisco. Kraken offers Spot and Futures trading, staking and yield through Kraken Earn, NFT marketplace access, O…
  api_count: 24
  score_band: exemplar
  score_composite: 68.0
  shared: 2
- slug: gemini-trust
  name: Gemini Trust Company
  description: Gemini Trust Company, LLC is a United States cryptocurrency exchange and custodian, founded in 2014 and headquartered in New York, regulated as a New York State Department of Financial Services trust company. It operates the Gemini Exchang…
  api_count: 4
  score_band: exemplar
  score_composite: 67.5
  shared: 2
- slug: cumulocity
  name: Cumulocity
  description: Cumulocity is an enterprise AIoT (Artificial Intelligence of Things) platform that connects, manages, and analyzes industrial assets from cloud to edge. Founded inside Software AG and divested via a 2025 management buyout into an independe…
  api_count: 17
  score_band: exemplar
  score_composite: 67.0
  shared: 2
- slug: dolby
  name: Dolby
  description: Dolby Laboratories is an audio and video technology company whose developer platform, Dolby OptiView, is the merged surface of the original dolby.io platform, THEO Technologies (THEOplayer, THEOlive, THEOads) and Millicast. It ships public…
  api_count: 13
  score_band: exemplar
  score_composite: 66.5
  shared: 2
- slug: heroiclabs
  name: Heroic Labs
  description: Heroic Labs is the company behind Nakama, a leading open-source game backend server providing a comprehensive REST, WebSocket, and gRPC API for building scalable multiplayer and social games. The platform delivers essential backend service…
  api_count: 4
  score_band: strong
  score_composite: 66.3
  shared: 2
- slug: red5
  name: Red5
  description: Red5 provides real-time streaming infrastructure for live video and audio delivery at scale. The Red5 Pro platform includes a media server, Stream Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite stream productio…
  api_count: 3
  score_band: strong
  score_composite: 65.1
  shared: 2
- slug: aedifion
  name: Aedifion
  description: aedifion GmbH is a Cologne-based PropTech founded in 2017 that operates a vendor-neutral, patented cloud platform for the optimized operation of non-residential buildings. The platform ingests real-time operating data from all building tra…
  api_count: 2
  score_band: strong
  score_composite: 62.5
  shared: 2
- slug: siftingio
  name: SiftingIO
  description: Cross-asset market data APIs covering US equities, forex, cryptocurrency, DeFi/on-chain, commodities, and SEC/EDGAR fundamentals, aggregated across venues and normalized into one JSON schema so every asset class shares the same fields, aut…
  api_count: 1
  score_band: strong
  score_composite: 61.1
  shared: 2
- slug: agentmail
  name: AgentMail
  description: AgentMail is an API-first email platform that gives AI agents their own email inboxes to autonomously send, receive, reply to, and act on email. Unlike traditional transactional email APIs built for one-way notifications, AgentMail is desi…
  api_count: 1
  score_band: strong
  score_composite: 60.2
  shared: 2
- slug: thingspeak
  name: ThingSpeak
  description: ThingSpeak is an IoT analytics platform from MathWorks that lets devices aggregate, visualize, and analyze live data streams in the cloud. Devices push telemetry to channels via a REST update endpoint or the `mqtt3.thingspeak.com` MQTT bro…
  api_count: 2
  score_band: strong
  score_composite: 59.2
  shared: 2
- slug: odds-api
  name: Odds API
  description: OpenAPI-first sports betting odds API (odds-api.net) providing bookmaker odds, odds comparison, arbitrage, positive EV, line movement, and racing/sports coverage via REST plus SSE and WebSocket streaming. Agent-native with an MCP server, l…
  api_count: 1
  score_band: strong
  score_composite: 58.8
  shared: 2
- slug: amazon-sns
  name: Amazon SNS
  description: Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It enables pub/sub, SMS, email, and mobile push notifications.
  api_count: 1
  score_band: strong
  score_composite: 58.5
  shared: 2
- slug: maicoin
  name: MaiCoin
  description: MaiCoin is a Taiwan-based digital asset group that operates MAX (MaiCoin Assets eXchange), a regulated cryptocurrency exchange offering spot trading, margin borrowing (m-wallet), staking, and fiat TWD on/off-ramps. MAX publishes a public V…
  api_count: 1
  score_band: strong
  score_composite: 58.2
  shared: 2
- slug: decart
  name: Decart
  description: Decart is an AI research lab and API platform building real-time world models — foundation models that generate and transform video frame-by-frame as they are watched. Its Decart API Platform (platform.decart.ai) exposes the Lucy family of…
  api_count: 2
  score_band: strong
  score_composite: 54.8
  shared: 2
- slug: open-poker
  name: Open Poker
  description: A free competitive arena where AI bots play 6-max No-Limit Texas Hold'em against each other over WebSocket in 14-day seasons, tracked on a public leaderboard. Bots connect via WebSocket, receive game state as JSON, and send actions back —…
  api_count: 1
  score_band: developing
  score_composite: 53.1
  shared: 2
- slug: runway
  name: Runway
  description: Runway is an applied AI research company that builds generative AI tools for creative professionals. Their developer platform provides APIs for video generation, image generation, real-time conversational avatar experiences, media uploads,…
  api_count: 9
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: whereby
  name: Whereby
  description: Whereby is an embeddable video API plus standalone meetings product that lets developers add browser-based, no-download video calls to their apps with a few lines of code or build deeply customized experiences via SDKs. The REST API at api…
  api_count: 1
  score_band: developing
  score_composite: 51.4
  shared: 2
---
