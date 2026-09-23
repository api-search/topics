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
provider_count: 49
providers:
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, w…
  api_count: 2
  score_band: developing
  score_composite: 43.1
  shared: 4
- slug: pusher
  name: Pusher
  description: Pusher is a realtime communication platform owned by MessageBird/Bird. Its primary product Channels provides pub/sub messaging over WebSocket and HTTP; Beams provides device push notifications. Authentication uses an app key + secret per P…
  api_count: 1
  score_band: developing
  score_composite: 40.1
  shared: 4
- slug: pubnub
  name: PubNub
  description: PubNub is a realtime communication platform supporting pub/sub, presence, chat, App Context (object metadata), Functions (server-less compute on the edge), Push Notifications, and IoT messaging across 1B+ devices. The PubNub REST API runs…
  api_count: 2
  score_band: thin
  score_composite: 33.9
  shared: 4
- slug: liveblocks
  name: Liveblocks
  description: Liveblocks is a real-time collaboration platform that provides ready-made building blocks for multiplayer experiences, including presence, broadcast events, shared storage (LiveObject/LiveList/LiveMap), comments and threads, notifications,…
  api_count: 1
  score_band: strong
  score_composite: 60.4
  shared: 3
- slug: microsoft-azure-web-pubsub
  name: Azure Web PubSub
  description: Azure Web PubSub is a fully-managed service that enables building real-time, two-way messaging applications using publish-subscribe patterns over WebSockets. It supports broadcasting messages to clients in groups, sending messages to speci…
  api_count: 1
  score_band: developing
  score_composite: 51.4
  shared: 3
- slug: hivemq
  name: HiveMQ
  description: HiveMQ is an enterprise MQTT broker and IoT connectivity platform that provides reliable, scalable bidirectional messaging between connected devices and back-end systems using the MQTT protocol. It supports MQTT 3, MQTT 5, MQTT over WebSoc…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 3
- slug: superviz
  name: SuperViz
  description: SuperViz provides real-time collaboration and data-synchronization infrastructure for web applications - presence, realtime data channels, video huddle/meetings, contextual comments, and mouse pointers. The product is SDK-first (@superviz/…
  api_count: 1
  score_band: thin
  score_composite: 27.7
  shared: 3
- slug: heroiclabs
  name: Heroic Labs
  description: Heroic Labs is the company behind Nakama, a leading open-source game backend server providing a comprehensive REST, WebSocket, and gRPC API for building scalable multiplayer and social games. The platform delivers essential backend service…
  api_count: 4
  score_band: exemplar
  score_composite: 67.5
  shared: 2
- slug: polygon
  name: Massive (formerly Polygon.io)
  description: Polygon (Polygon.io, rebranded as Massive in early 2026) provides real-time and historical market data APIs across US stocks, options, indices, forex, cryptocurrencies, and futures. Coverage is delivered through REST endpoints and WebSocke…
  api_count: 7
  score_band: exemplar
  score_composite: 67.2
  shared: 2
- slug: dolby
  name: Dolby
  description: Dolby Laboratories is an audio and video technology company whose developer platform, Dolby OptiView, is the merged surface of the original dolby.io platform, THEO Technologies (THEOplayer, THEOlive, THEOads) and Millicast. It ships public…
  api_count: 13
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: siftingio
  name: SiftingIO
  description: Cross-asset market data APIs covering US equities, forex, cryptocurrency, DeFi/on-chain, commodities, and SEC/EDGAR fundamentals, aggregated across venues and normalized into one JSON schema so every asset class shares the same fields, aut…
  api_count: 1
  score_band: strong
  score_composite: 63.9
  shared: 2
- slug: red5
  name: Red5
  description: Red5 provides real-time streaming infrastructure for live video and audio delivery at scale. The Red5 Pro platform includes a media server, Stream Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite stream productio…
  api_count: 3
  score_band: strong
  score_composite: 62.5
  shared: 2
- slug: odds-api
  name: Odds API
  description: OpenAPI-first sports betting odds API (odds-api.net) providing bookmaker odds, odds comparison, arbitrage, positive EV, line movement, and racing/sports coverage via REST plus SSE and WebSocket streaming. Agent-native with an MCP server, l…
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 2
- slug: amazon-sns
  name: Amazon SNS
  description: Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It enables pub/sub, SMS, email, and mobile push notifications.
  api_count: 1
  score_band: strong
  score_composite: 55.7
  shared: 2
- slug: decart
  name: Decart
  description: Decart is an AI research lab and API platform building real-time world models — foundation models that generate and transform video frame-by-frame as they are watched. Its Decart API Platform (platform.decart.ai) exposes the Lucy family of…
  api_count: 2
  score_band: strong
  score_composite: 55.3
  shared: 2
- slug: qfex
  name: Qfex
  description: QFEX is the first 24/7 exchange built exclusively for US equities, commodities, and FX, offering high-leverage perpetual futures on traditional assets without a broker. Founded by former Tower Research and Citadel engineers who met studyin…
  api_count: 1
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: whereby
  name: Whereby
  description: Whereby is an embeddable video API plus standalone meetings product that lets developers add browser-based, no-download video calls to their apps with a few lines of code or build deeply customized experiences via SDKs. The REST API at api…
  api_count: 1
  score_band: developing
  score_composite: 52.8
  shared: 2
- slug: getstream
  name: Stream
  description: Stream (GetStream.io) provides scalable, API-first infrastructure for in-app chat messaging, activity feeds, audio/video calling and livestreaming, and AI moderation. The server-side platform is a documented REST API (base https://chat.str…
  api_count: 6
  score_band: developing
  score_composite: 52.5
  shared: 2
- slug: open-poker
  name: Open Poker
  description: A free competitive arena where AI bots play 6-max No-Limit Texas Hold'em against each other over WebSocket in 14-day seasons, tracked on a public leaderboard. Bots connect via WebSocket, receive game state as JSON, and send actions back —…
  api_count: 2
  score_band: developing
  score_composite: 51.3
  shared: 2
- slug: gladia
  name: Gladia
  description: Gladia is an AI audio infrastructure platform that offers speech-to-text transcription via both REST and WebSocket APIs, supporting asynchronous pre-recorded audio processing and real-time live transcription. The platform provides speaker…
  api_count: 1
  score_band: developing
  score_composite: 50.4
  shared: 2
- slug: daily-co
  name: Daily
  description: Daily provides WebRTC video and audio infrastructure for developers — REST APIs for rooms, recordings, transcripts, meetings, dial-out and Daily Bots / Pipecat Cloud (voice AI agents), plus client SDKs for Web, iOS, Android, React Native a…
  api_count: 1
  score_band: developing
  score_composite: 49.7
  shared: 2
- slug: microsoft-azure-signalr
  name: Azure SignalR Service
  description: Azure SignalR Service REST API enables management of real-time web communication services. It supports creating SignalR instances, managing connections, sending messages to clients and groups, and configuring upstream endpoints for serverl…
  api_count: 2
  score_band: developing
  score_composite: 49.5
  shared: 2
- slug: neuphonic
  name: Neuphonic
  description: Neuphonic is an ultra-low-latency voice AI platform specializing in real-time text-to-speech synthesis with sub-25ms latency, making it suitable for conversational AI and live applications. The platform provides both a cloud-hosted API wit…
  api_count: 1
  score_band: developing
  score_composite: 46.6
  shared: 2
- slug: lightstream
  name: Lightstream
  description: Lightstream (Infiniscene, Inc.) is a Techstars-backed live video company best known for Lightstream Studio, a browser-based streaming studio used by creators to broadcast to Twitch, YouTube and other destinations without installing desktop…
  api_count: 3
  score_band: developing
  score_composite: 46.5
  shared: 2
- slug: reactor
  name: Reactor
  description: Reactor is a real-time video AI platform that streams generative video from GPU-hosted models to web and mobile applications over WebRTC, with sub-second round-trip latency and no infrastructure to manage. Developers connect through a Java…
  api_count: 1
  score_band: developing
  score_composite: 46.0
  shared: 2
- slug: cartesia-ai
  name: Cartesia
  description: Cartesia builds real-time voice AI - the Sonic family of text-to-speech models, Ink speech-to-text models, and a Voice Agents platform for building and deploying telephone and web voice agents. The core generation surface is exposed both a…
  api_count: 1
  score_band: developing
  score_composite: 44.8
  shared: 2
- slug: partykit
  name: PartyKit
  description: PartyKit is a real-time backend framework, now part of Cloudflare, that wraps Cloudflare Durable Objects with an opinionated developer experience for building multiplayer applications. It exposes a Party.Server library API for backend logi…
  api_count: 4
  score_band: developing
  score_composite: 43.7
  shared: 2
- slug: streamelements
  name: StreamElements
  description: StreamElements is a cloud-based platform for live streamers and content creators on Twitch, YouTube, Kick and Facebook, offering 100% free customizable overlays and alerts, a chatbot, tipping and donations, loyalty points, giveaways and co…
  api_count: 1
  score_band: developing
  score_composite: 42.6
  shared: 2
- slug: kotoba
  name: Kotoba
  description: Kotoba Technologies is a Japan-founded frontier voice AI company building a foundational real-time speech model and simultaneous translation technology. Its developer platform exposes three JSON-over-WebSocket realtime capabilities — ASR (…
  api_count: 4
  score_band: developing
  score_composite: 42.2
  shared: 2
- slug: rivet
  name: Rivet
  description: Rivet is infrastructure for the agentic era, providing durable, stateful compute for AI agents and realtime applications. Its core primitive, Rivet Actors (RivetKit), is a runtime for long-lived processes that co-locate in-memory state wit…
  api_count: 1
  score_band: developing
  score_composite: 41.1
  shared: 2
---
