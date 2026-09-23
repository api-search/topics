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
provider_count: 177
providers:
- slug: dolby
  name: Dolby
  description: Dolby Laboratories is an audio and video technology company whose developer platform, Dolby OptiView, is the merged surface of the original dolby.io platform, THEO Technologies (THEOplayer, THEOlive, THEOads) and Millicast. It ships public…
  api_count: 13
  score_band: strong
  score_composite: 65.9
  shared: 5
- slug: whereby
  name: Whereby
  description: Whereby is an embeddable video API plus standalone meetings product that lets developers add browser-based, no-download video calls to their apps with a few lines of code or build deeply customized experiences via SDKs. The REST API at api…
  api_count: 1
  score_band: developing
  score_composite: 52.8
  shared: 5
- slug: dolby-io
  name: Dolby.io
  description: Dolby.io (now branded as Dolby OptiView) is Dolby Laboratories' developer platform for media, streaming, communications, and advertising APIs. Originally launched as a hub for Dolby's audio and video processing services (Media APIs, Commun…
  api_count: 2
  score_band: strong
  score_composite: 63.1
  shared: 4
- slug: red5
  name: Red5
  description: Red5 provides real-time streaming infrastructure for live video and audio delivery at scale. The Red5 Pro platform includes a media server, Stream Manager 2.0 for autoscaling cloud deployments, the Brew Mixer for composite stream productio…
  api_count: 3
  score_band: strong
  score_composite: 62.5
  shared: 4
- slug: zoom
  name: Zoom
  description: Zoom is a communications platform that allows users to connect with video, audio, phone, and chat. The Zoom API provides programmatic access to Zoom's core features including meetings, webinars, recordings, users, and more.
  api_count: 12
  score_band: strong
  score_composite: 54.7
  shared: 4
- slug: getstream
  name: Stream
  description: Stream (GetStream.io) provides scalable, API-first infrastructure for in-app chat messaging, activity feeds, audio/video calling and livestreaming, and AI moderation. The server-side platform is a documented REST API (base https://chat.str…
  api_count: 6
  score_band: developing
  score_composite: 52.5
  shared: 4
- slug: daily-co
  name: Daily
  description: Daily provides WebRTC video and audio infrastructure for developers — REST APIs for rooms, recordings, transcripts, meetings, dial-out and Daily Bots / Pipecat Cloud (voice AI agents), plus client SDKs for Web, iOS, Android, React Native a…
  api_count: 1
  score_band: developing
  score_composite: 49.7
  shared: 4
- slug: lightstream
  name: Lightstream
  description: Lightstream (Infiniscene, Inc.) is a Techstars-backed live video company best known for Lightstream Studio, a browser-based streaming studio used by creators to broadcast to Twitch, YouTube and other destinations without installing desktop…
  api_count: 3
  score_band: developing
  score_composite: 46.5
  shared: 4
- slug: kumospace
  name: Kumospace
  description: Kumospace is a virtual office platform for remote and distributed teams, providing a persistent spatial workspace where colleagues move between rooms and floors, with proximity-based spatial audio and video, team chat channels, scheduled a…
  api_count: 1
  score_band: developing
  score_composite: 44.6
  shared: 4
- slug: videosdk
  name: VideoSDK
  description: Real-time voice, video, and AI agent platform for developers. VideoSDK provides REST and WebSocket APIs for building video conferencing, live streaming, interactive broadcast applications, and real-time AI agent integrations with SDKs for…
  api_count: 1
  score_band: developing
  score_composite: 40.1
  shared: 4
- slug: rainbow
  name: Rainbow
  description: Rainbow is a CPaaS platform from Alcatel-Lucent Enterprise (ALE) that lets developers enrich applications with chat, group chat, voice, video, file sharing, and telephony PBX features through more than 200 APIs, REST interfaces, and multi-…
  api_count: 3
  score_band: thin
  score_composite: 39.2
  shared: 4
- slug: dyte
  name: Dyte
  description: Dyte is a live video and voice developer platform offering client SDKs plus a v2 REST API for programmatically creating meetings, adding participants and issuing their auth tokens, querying completed sessions, and managing recordings, live…
  api_count: 1
  score_band: thin
  score_composite: 38.2
  shared: 4
- slug: livekit
  name: LiveKit
  description: LiveKit is an open-source WebRTC platform with a managed Cloud offering. APIs cover Rooms, Participants, Tracks, Egress (recording, RTMP), Ingress (RTMP/SRT), SIP (telephony), and Agents (LLM voice agents). The server APIs use Twirp (HTTP+…
  api_count: 6
  score_band: thin
  score_composite: 32.2
  shared: 4
- slug: superviz
  name: SuperViz
  description: SuperViz provides real-time collaboration and data-synchronization infrastructure for web applications - presence, realtime data channels, video huddle/meetings, contextual comments, and mouse pointers. The product is SDK-first (@superviz/…
  api_count: 1
  score_band: thin
  score_composite: 27.7
  shared: 4
- slug: voxeet
  name: Voxeet
  description: Voxeet was a San Francisco-based startup that built spatial-audio voice and video conferencing APIs and SDKs for web and mobile applications, backed by 500 Global. Dolby Laboratories acquired Voxeet in 2019 and rebranded its technology as…
  api_count: 0
  score_band: minimal
  score_composite: 7.5
  shared: 4
- slug: around
  name: Around
  description: Around was a video-calling application built for designers, developers, and product teams, known for floating circular "heads" that cropped participants to their faces so the call could sit on top of the work rather than dominate the scree…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 4
- slug: signalwire
  name: SignalWire
  description: SignalWire is a Programmable Unified Communications (PUC) platform for voice, messaging, video, fax, SIP and AI voice agents, built by the team behind FreeSWITCH. It publishes two first-party OpenAPI 3.1 contracts from its public documenta…
  api_count: 4
  score_band: exemplar
  score_composite: 68.9
  shared: 3
- slug: ant-media
  name: Ant Media
  description: Ant Media Server is a scalable, open-source media server for ultra-low latency live streaming and WebRTC-based video applications. It supports WebRTC, RTMP, RTSP, SRT, HLS, and CMAF protocols, enabling developers to build real-time video a…
  api_count: 2
  score_band: strong
  score_composite: 59.8
  shared: 3
- slug: wowza
  name: Wowza
  description: Wowza is a Denver, Colorado-based video streaming infrastructure provider that has been simplifying live and on-demand streaming since 2007. The platform spans three flagship products — Wowza Streaming Engine (a self-hosted, on-prem/cloud/…
  api_count: 2
  score_band: strong
  score_composite: 56.3
  shared: 3
- slug: decart
  name: Decart
  description: Decart is an AI research lab and API platform building real-time world models — foundation models that generate and transform video frame-by-frame as they are watched. Its Decart API Platform (platform.decart.ai) exposes the Lucy family of…
  api_count: 2
  score_band: strong
  score_composite: 55.3
  shared: 3
- slug: microsoft-teams
  name: Microsoft Teams
  description: Microsoft Teams is a collaboration platform that combines workplace chat, meetings, file storage, and application integration. It provides APIs for building custom integrations, managing teams and channels, sending messages, scheduling mee…
  api_count: 11
  score_band: developing
  score_composite: 54.0
  shared: 3
- slug: amazon-interactive-video-service
  name: Amazon Interactive Video Service
  description: Amazon Interactive Video Service (Amazon IVS) is a managed live streaming solution designed to provide interactive video experiences. It handles the operational complexity of live streaming so you can focus on building engaging application…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 3
- slug: reactor
  name: Reactor
  description: Reactor is a real-time video AI platform that streams generative video from GPU-hosted models to web and mobile applications over WebRTC, with sub-second round-trip latency and no infrastructure to manage. Developers connect through a Java…
  api_count: 1
  score_band: developing
  score_composite: 46.0
  shared: 3
- slug: discord
  name: Discord
  description: Discord is a voice, video and text communication service used by hundreds of millions of people to hang out and talk with their communities and friends.
  api_count: 3
  score_band: developing
  score_composite: 45.3
  shared: 3
- slug: streamelements
  name: StreamElements
  description: StreamElements is a cloud-based platform for live streamers and content creators on Twitch, YouTube, Kick and Facebook, offering 100% free customizable overlays and alerts, a chatbot, tipping and donations, loyalty points, giveaways and co…
  api_count: 1
  score_band: developing
  score_composite: 42.6
  shared: 3
- slug: castr-live
  name: Castr
  description: Castr is a live video streaming and multistreaming platform with video hosting (VOD), that lets you ingest a single RTMP/SRT source and restream it to multiple destinations, record and clip live streams, host and deliver on-demand video, r…
  api_count: 1
  score_band: developing
  score_composite: 41.6
  shared: 3
- slug: cometchat
  name: CometChat
  description: CometChat is an in-app messaging platform offering chat, voice, and video SDKs plus a server-side REST Management API. The REST API (v3) manages users, auth tokens, groups, group members, messages, conversations, reactions, roles, and webh…
  api_count: 1
  score_band: developing
  score_composite: 40.5
  shared: 3
- slug: confrere
  name: Confrere
  description: Confrere is a privacy-first, embeddable video-consultation platform (now a Compodium product) built in the Nordics for healthcare providers, therapists, consultants, tutors, and sales teams who need secure, encrypted video meetings that cl…
  api_count: 1
  score_band: thin
  score_composite: 38.8
  shared: 3
- slug: synapse
  name: Synapse
  description: Synapse is the reference Matrix homeserver implementation maintained by Element (formerly by the Matrix.org Foundation). Written in Python and Rust, it implements the Matrix open standard for secure, decentralized real-time communication.…
  api_count: 1
  score_band: thin
  score_composite: 35.9
  shared: 3
- slug: overshoot
  name: Overshoot
  description: Overshoot is a real-time video understanding API. Developers create a live video stream, publish frames over WebRTC (LiveKit), then query what the camera sees with vision-language models through an OpenAI-compatible chat completions endpoi…
  api_count: 2
  score_band: thin
  score_composite: 35.6
  shared: 3
---
