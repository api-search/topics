---
layout: topic
slug: visioconference
name: Visioconference
kind: topic
description: Visioconference (video conferencing) is a category of communication technology enabling real-time visual and audio communication between remote participants. This repository profiles the video conferencing API ecosystem including leading providers such as Zoom, Microsoft Teams, Google Meet, Webex, Digital Samba, VideoSDK, Daily.co, and others offering REST APIs for embedding and managing video conferencing functionality. The term "visioconference" is commonly used in French-speaking contexts.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/visioconference.png
tags:
- Audio
- Chat
- Collaboration
- Communications
- Conferencing
- Live Streaming
- Real-Time
- Remote Work
- Screen Sharing
- Video
- WebRTC
repo: https://github.com/api-evangelist/visioconference
api_count: 9
apis:
- name: Microsoft Teams API
  description: Microsoft Graph API for Teams provides access to teams, channels, meetings, calls, and messaging in Microsoft Teams.
  url: https://learn.microsoft.com/en-us/graph/teams-concept-overview
- name: Google Meet REST API
  description: Google Meet REST API allows developers to create and manage Meet spaces and retrieve recording artifacts.
  url: https://developers.google.com/meet/api
- name: Cisco Webex API
  description: Cisco Webex REST API for meetings, messaging, calling, and device management. Supports webhooks for event-driven integrations.
  url: https://developer.webex.com/
- name: Daily.co API
  description: Daily.co REST API for creating and managing video call rooms, recording, and participant management using WebRTC.
  url: https://docs.daily.co/reference
- name: Digital Samba Embedded API
  description: European-hosted video conferencing REST API for creating rooms, managing access, and embedding video calls. GDPR-compliant with data stored in Europe.
  url: https://digitalsamba.com/
- name: Visioconference Archiving API
  description: The Archiving API from Visioconference — 3 operation(s) for archiving.
  url: https://developers.zoom.us/
- name: Visioconference Meetings API
  description: The Meetings API from Visioconference — 2 operation(s) for meetings.
  url: https://developers.zoom.us/
- name: Visioconference Recordings API
  description: The Recordings API from Visioconference — 4 operation(s) for recordings.
  url: https://developers.zoom.us/
- name: Visioconference Users API
  description: The Users API from Visioconference — 2 operation(s) for users.
  url: https://developers.zoom.us/
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/visioconference/blob/main/agentic-access/visioconference-agentic-access.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/visioconference/blob/main/security/visioconference-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/visioconference/blob/main/security/visioconference-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/visioconference/blob/main/authentication/visioconference-authentication.yml
- type: OAuthScopes
  url: https://github.com/api-evangelist/visioconference/blob/main/scopes/visioconference-scopes.yml
- type: Website
  url: https://en.wikipedia.org/wiki/Videotelephony
- type: JSONSchema
  url: https://github.com/api-evangelist/visioconference/blob/main/json-schema/visioconference-meeting-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/visioconference/blob/main/json-ld/visioconference-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/visioconference/blob/main/vocabulary/visioconference-vocabulary.yml
provider_count: 195
providers:
- slug: dolby
  name: Dolby
  description: Dolby Laboratories is an audio and video technology company whose developer platform, Dolby OptiView, is the merged surface of the original dolby.io platform, THEO Technologies (THEOplayer, THEOlive, THEOads) and Millicast. It ships public…
  api_count: 13
  score_band: exemplar
  score_composite: 66.5
  shared: 5
- slug: whereby
  name: Whereby
  description: Whereby is an embeddable video API plus standalone meetings product that lets developers add browser-based, no-download video calls to their apps with a few lines of code or build deeply customized experiences via SDKs. The REST API at api…
  api_count: 1
  score_band: developing
  score_composite: 51.4
  shared: 5
- slug: red5
  name: Red5
  description: Red5 provides real-time streaming infrastructure for live video and audio delivery at scale. The Red5 Pro platform includes a media server, Stream Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite stream productio…
  api_count: 3
  score_band: strong
  score_composite: 65.1
  shared: 4
- slug: zoom
  name: Zoom
  description: Zoom is a communications platform that allows users to connect with video, audio, phone, and chat. The Zoom API provides programmatic access to Zoom's core features including meetings, webinars, recordings, users, and more.
  api_count: 12
  score_band: strong
  score_composite: 55.8
  shared: 4
- slug: getstream
  name: Stream
  description: Stream (GetStream.io) provides scalable, API-first infrastructure for in-app chat messaging, activity feeds, audio/video calling and livestreaming, and AI moderation. The server-side platform is a documented REST API (base https://chat.str…
  api_count: 6
  score_band: developing
  score_composite: 51.2
  shared: 4
- slug: daily-co
  name: Daily
  description: Daily provides WebRTC video and audio infrastructure for developers — REST APIs for rooms, recordings, transcripts, meetings, dial-out and Daily Bots / Pipecat Cloud (voice AI agents), plus client SDKs for Web, iOS, Android, React Native a…
  api_count: 1
  score_band: developing
  score_composite: 47.5
  shared: 4
- slug: discord
  name: Discord
  description: Discord is a voice, video and text communication service used by hundreds of millions of people to hang out and talk with their communities and friends.
  api_count: 3
  score_band: developing
  score_composite: 47.4
  shared: 4
- slug: lightstream
  name: Lightstream
  description: Lightstream (Infiniscene, Inc.) is a Techstars-backed live video company best known for Lightstream Studio, a browser-based streaming studio used by creators to broadcast to Twitch, YouTube and other destinations without installing desktop…
  api_count: 3
  score_band: developing
  score_composite: 46.3
  shared: 4
- slug: kumospace
  name: Kumospace
  description: Kumospace is a virtual office platform for remote and distributed teams, providing a persistent spatial workspace where colleagues move between rooms and floors, with proximity-based spatial audio and video, team chat channels, scheduled a…
  api_count: 1
  score_band: developing
  score_composite: 45.2
  shared: 4
- slug: videosdk
  name: VideoSDK
  description: Real-time voice, video, and AI agent platform for developers. VideoSDK provides REST and WebSocket APIs for building video conferencing, live streaming, interactive broadcast applications, and real-time AI agent integrations with SDKs for…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 4
- slug: superviz
  name: SuperViz
  description: SuperViz provides real-time collaboration and data-synchronization infrastructure for web applications - presence, realtime data channels, video huddle/meetings, contextual comments, and mouse pointers. The product is SDK-first (@superviz/…
  api_count: 1
  score_band: thin
  score_composite: 38.9
  shared: 4
- slug: rainbow
  name: Rainbow
  description: Rainbow is a CPaaS platform from Alcatel-Lucent Enterprise (ALE) that lets developers enrich applications with chat, group chat, voice, video, file sharing, and telephony PBX features through more than 200 APIs, REST interfaces, and multi-…
  api_count: 3
  score_band: thin
  score_composite: 36.8
  shared: 4
- slug: dyte
  name: Dyte
  description: Dyte is a live video and voice developer platform offering client SDKs plus a v2 REST API for programmatically creating meetings, adding participants and issuing their auth tokens, querying completed sessions, and managing recordings, live…
  api_count: 1
  score_band: thin
  score_composite: 35.0
  shared: 4
- slug: livekit
  name: LiveKit
  description: LiveKit is an open-source WebRTC platform with a managed Cloud offering. APIs cover Rooms, Participants, Tracks, Egress (recording, RTMP), Ingress (RTMP/SRT), SIP (telephony), and Agents (LLM voice agents). The server APIs use Twirp (HTTP+…
  api_count: 6
  score_band: thin
  score_composite: 31.5
  shared: 4
- slug: agora-io
  name: Agora
  description: Agora is a real-time engagement platform providing ultra-low latency voice, video, signaling, chat, interactive whiteboard, cloud recording, real-time speech-to-text, and conversational AI infrastructure for human-to-human and human-to-AI…
  api_count: 11
  score_band: thin
  score_composite: 30.6
  shared: 4
- slug: voxeet
  name: Voxeet
  description: Voxeet was a San Francisco-based startup that built spatial-audio voice and video conferencing APIs and SDKs for web and mobile applications, backed by 500 Global. Dolby Laboratories acquired Voxeet in 2019 and rebranded its technology as…
  api_count: 0
  score_band: minimal
  score_composite: 5.8
  shared: 4
- slug: around
  name: Around
  description: Around was a video-calling application built for designers, developers, and product teams, known for floating circular "heads" that cropped participants to their faces so the call could sit on top of the work rather than dominate the scree…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 4
- slug: twilio
  name: Twilio
  description: Cloud communications platform providing APIs for SMS, voice, video, and authentication services. Twilio offers 30+ APIs covering messaging, voice, video, email, identity verification, IoT connectivity, and contact center solutions. Used by…
  api_count: 40
  score_band: exemplar
  score_composite: 77.8
  shared: 3
- slug: slack
  name: Slack
  description: Slack is a cloud-based team collaboration platform that provides chat, file sharing, and integrations with other tools and services.
  api_count: 32
  score_band: exemplar
  score_composite: 67.9
  shared: 3
- slug: signalwire
  name: SignalWire
  description: SignalWire is a Programmable Unified Communications (PUC) platform for voice, messaging, video, fax, SIP and AI voice agents, built by the team behind FreeSWITCH. It publishes two first-party OpenAPI 3.1 contracts from its public documenta…
  api_count: 4
  score_band: strong
  score_composite: 65.4
  shared: 3
- slug: ringcentral
  name: RingCentral
  description: RingCentral provides unified cloud communications for businesses including voice, video, messaging, contact center, and events. The RingCentral API exposes call control, SMS, faxing, voicemail, presence, team messaging, video, and analytic…
  api_count: 1
  score_band: strong
  score_composite: 61.0
  shared: 3
- slug: ant-media
  name: Ant Media
  description: Ant Media Server is a scalable, open-source media server for ultra-low latency live streaming and WebRTC-based video applications. It supports WebRTC, RTMP, RTSP, SRT, HLS, and CMAF protocols, enabling developers to build real-time video a…
  api_count: 2
  score_band: strong
  score_composite: 59.8
  shared: 3
- slug: microsoft-teams
  name: Microsoft Teams
  description: Microsoft Teams is a collaboration platform that combines workplace chat, meetings, file storage, and application integration. It provides APIs for building custom integrations, managing teams and channels, sending messages, scheduling mee…
  api_count: 11
  score_band: strong
  score_composite: 56.4
  shared: 3
- slug: decart
  name: Decart
  description: Decart is an AI research lab and API platform building real-time world models — foundation models that generate and transform video frame-by-frame as they are watched. Its Decart API Platform (platform.decart.ai) exposes the Lucy family of…
  api_count: 2
  score_band: strong
  score_composite: 54.8
  shared: 3
- slug: wowza
  name: Wowza
  description: Wowza is a Denver, Colorado-based video streaming infrastructure provider that has been simplifying live and on-demand streaming since 2007. The platform spans three flagship products — Wowza Streaming Engine (a self-hosted, on-prem/cloud/…
  api_count: 2
  score_band: strong
  score_composite: 54.4
  shared: 3
- slug: amazon-interactive-video-service
  name: Amazon Interactive Video Service
  description: Amazon Interactive Video Service (Amazon IVS) is a managed live streaming solution designed to provide interactive video experiences. It handles the operational complexity of live streaming so you can focus on building engaging application…
  api_count: 1
  score_band: developing
  score_composite: 53.5
  shared: 3
- slug: twitch
  name: Twitch
  description: Twitch is a live streaming platform for gamers, content creators, and communities.
  api_count: 6
  score_band: developing
  score_composite: 51.5
  shared: 3
- slug: reactor
  name: Reactor
  description: Reactor is a real-time video AI platform that streams generative video from GPU-hosted models to web and mobile applications over WebRTC, with sub-second round-trip latency and no infrastructure to manage. Developers connect through a Java…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 3
- slug: beeper
  name: Beeper
  description: Beeper is a universal chat app that brings 12+ messaging networks — WhatsApp, Instagram, Telegram, Signal, Messenger, X, Google Messages, Google Chat, Google Voice, LinkedIn, Discord and Slack — into a single unified inbox across macOS, Wi…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 3
- slug: streamelements
  name: StreamElements
  description: StreamElements is a cloud-based platform for live streamers and content creators on Twitch, YouTube, Kick and Facebook, offering 100% free customizable overlays and alerts, a chatbot, tipping and donations, loyalty points, giveaways and co…
  api_count: 1
  score_band: developing
  score_composite: 43.8
  shared: 3
---
