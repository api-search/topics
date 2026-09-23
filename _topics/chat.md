---
layout: topic
slug: chat
name: Chat
kind: topic
description: Topic-level profile capturing the Chat API category in the API Evangelist network. This profile defines a reference vocabulary and a generic OpenAPI shape for chat APIs that manage conversations, messages, and participants, and is used as a baseline when cataloguing chat platform APIs (such as Slack, Discord, Microsoft Teams, Twilio Conversations, and conversational AI platforms) into the broader catalogue.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/chat.png
tags:
- Chat
- Conversational AI
- Conversations
- Customer-Support
- Messaging
- Real-Time
repo: https://github.com/api-evangelist/chat
api_count: 3
apis:
- name: Chat Conversations API
  description: The Conversations API from Chat — 2 operation(s) for conversations.
  url: https://github.com/api-evangelist/chat
- name: Chat Messages API
  description: The Messages API from Chat — 1 operation(s) for messages.
  url: https://github.com/api-evangelist/chat
- name: Chat Participants API
  description: The Participants API from Chat — 1 operation(s) for participants.
  url: https://github.com/api-evangelist/chat
links:
- type: IssueTracker
  url: https://github.com/api-evangelist/chat/issues
- type: AgenticAccess
  url: https://github.com/api-evangelist/chat/blob/main/agentic-access/chat-agentic-access.yml
- type: Authentication
  url: https://github.com/api-evangelist/chat/blob/main/authentication/chat-authentication.yml
- type: Repository
  url: https://github.com/api-evangelist/chat
- type: Catalog
  url: https://apis.json/
- type: JSONLD
  url: https://github.com/api-evangelist/chat/blob/main/json-ld/chat-context.jsonld
- type: JSONSchema
  url: https://github.com/api-evangelist/chat/blob/main/json-schema/chat-conversation-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/chat/blob/main/json-schema/chat-message-schema.json
provider_count: 110
providers:
- slug: getstream
  name: Stream
  description: Stream (GetStream.io) provides scalable, API-first infrastructure for in-app chat messaging, activity feeds, audio/video calling and livestreaming, and AI moderation. The server-side platform is a documented REST API (base https://chat.str…
  api_count: 6
  score_band: developing
  score_composite: 52.5
  shared: 3
- slug: netomi
  name: Netomi
  description: Netomi (founded 2016 as msg.ai) is an enterprise agentic AI platform for customer experience. Its "Agentic OS for CX" orchestrates a network of AI agents across chat, email, telephony, social, search, MCP and API channels, layering a gover…
  api_count: 1
  score_band: developing
  score_composite: 50.3
  shared: 3
- slug: chatwoot
  name: Chatwoot
  description: Chatwoot is an open-source customer support and omni-channel messaging platform that provides REST APIs for managing conversations, contacts, agents, teams, labels, and integrating customer communication workflows. It supports live chat, e…
  api_count: 2
  score_band: developing
  score_composite: 44.6
  shared: 3
- slug: conversica
  name: Conversica
  description: Conversica is an AI conversation automation company - "The Conversation Company" - whose Revenue Digital Assistants and AI Agents hold two-way, natural-language conversations with leads and customers over email, SMS and website chat to gen…
  api_count: 1
  score_band: developing
  score_composite: 44.2
  shared: 3
- slug: ably
  name: Ably
  description: Ably is a realtime messaging platform offering pub/sub, presence, push notifications, chat, LiveSync, and integrations over WebSocket and HTTP. Ably publishes its OpenAPI specifications publicly via the ably/open-specs GitHub repository, w…
  api_count: 2
  score_band: developing
  score_composite: 43.1
  shared: 3
- slug: cometchat
  name: CometChat
  description: CometChat is an in-app messaging platform offering chat, voice, and video SDKs plus a server-side REST Management API. The REST API (v3) manages users, auth tokens, groups, group members, messages, conversations, reactions, roles, and webh…
  api_count: 1
  score_band: developing
  score_composite: 40.5
  shared: 3
- slug: chatfuel
  name: Chatfuel
  description: Chatfuel is a no-code AI-powered chatbot and business-automation platform for conversational commerce across Meta-owned messaging channels — WhatsApp, Instagram, Facebook Messenger, TikTok, and an embeddable website chat widget. An officia…
  api_count: 3
  score_band: developing
  score_composite: 40.4
  shared: 3
- slug: synapse
  name: Synapse
  description: Synapse is the reference Matrix homeserver implementation maintained by Element (formerly by the Matrix.org Foundation). Written in Python and Rust, it implements the Matrix open standard for secure, decentralized real-time communication.…
  api_count: 1
  score_band: thin
  score_composite: 35.9
  shared: 3
- slug: google-business-messages
  name: Google Business Messages
  description: The Google Business Messages API enables agents to send messages, create events, and manage customer satisfaction surveys within conversations. It allows businesses to communicate with customers directly through Google entry points such as…
  api_count: 1
  score_band: thin
  score_composite: 34.0
  shared: 3
- slug: pubnub
  name: PubNub
  description: PubNub is a realtime communication platform supporting pub/sub, presence, chat, App Context (object metadata), Functions (server-less compute on the edge), Push Notifications, and IoT messaging across 1B+ devices. The PubNub REST API runs…
  api_count: 2
  score_band: thin
  score_composite: 33.9
  shared: 3
- slug: meyaai
  name: Meya.ai
  description: Meya is a chatbot and CX-automation platform for building, coding, and launching customer-support conversational apps, digital assistants, and workflow automation. Developers use the Grid platform and Console to script flows in BFML (a YAM…
  api_count: 1
  score_band: thin
  score_composite: 31.0
  shared: 3
- slug: quiq
  name: Quiq
  description: Quiq is an enterprise conversational AI and customer-experience platform for building, deploying, and governing agentic AI systems across digital and voice channels. Its products include AI Agents that resolve customer questions, AI Assist…
  api_count: 1
  score_band: thin
  score_composite: 29.7
  shared: 3
- slug: imbee
  name: imbee
  description: imBee is an AI-powered business omnichannel messaging platform headquartered in Hong Kong that unifies customer conversations across WhatsApp, Instagram, Facebook Messenger, WeChat, LINE, and SMS into a single enterprise-grade inbox. The p…
  api_count: 0
  score_band: emerging
  score_composite: 21.9
  shared: 3
- slug: mybotspro
  name: Mybots.pro
  description: myBots (operated by Global AI Group, Inc.) builds enterprise AI sales and support agents for messaging channels — WhatsApp, Instagram, Telegram, LinkedIn and web chat, under the Mia AI product name. Each agent qualifies inbound leads, answ…
  api_count: 3
  score_band: emerging
  score_composite: 20.6
  shared: 3
- slug: liveperson
  name: LivePerson
  description: LivePerson is a leading provider of conversational AI and digital customer engagement technology. Their platform enables enterprises to design, deploy, and manage AI-powered messaging, voice, and agent-assisted conversations across web, mo…
  api_count: 9
  score_band: emerging
  score_composite: 19.8
  shared: 3
- slug: robylon
  name: Robylon AI
  description: Enterprise AI customer-support platform spanning voice, WhatsApp, chat, email, social media and ticketing. The platform runs AI agents against a customer knowledge base with configurable personas, model selection, human-agent handover and…
  api_count: 1
  score_band: emerging
  score_composite: 14.3
  shared: 3
- slug: boom-ai
  name: Boom Ai
  description: Boom AI (useboom.ai) is a Y Combinator-backed (Fall 2025) San Francisco company building "an AI workforce for your customers" — autonomous agents that hold real, multi-turn conversations over SMS, email, WhatsApp, and phone in 50+ language…
  api_count: 1
  score_band: exemplar
  score_composite: 79.9
  shared: 2
- slug: novu
  name: Novu
  description: Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — wit…
  api_count: 1
  score_band: exemplar
  score_composite: 74.5
  shared: 2
- slug: knock-app
  name: Knock
  description: Knock is notifications infrastructure as a service — a product and customer messaging platform you use to power transactional, lifecycle, broadcast, and in-product messaging across email, SMS, push, in-app, in-app guides, chat (Slack / Dis…
  api_count: 13
  score_band: exemplar
  score_composite: 71.6
  shared: 2
- slug: signalwire
  name: SignalWire
  description: SignalWire is a Programmable Unified Communications (PUC) platform for voice, messaging, video, fax, SIP and AI voice agents, built by the team behind FreeSWITCH. It publishes two first-party OpenAPI 3.1 contracts from its public documenta…
  api_count: 4
  score_band: exemplar
  score_composite: 68.9
  shared: 2
- slug: x
  name: X
  description: X (formerly Twitter) operates the X Developer Platform, the programmable interface to the public conversation on X. The X API v2 is a 190-operation REST surface covering Posts, Users, Direct Messages, the encrypted Chat API, Lists, Spaces,…
  api_count: 2
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: slack
  name: Slack
  description: Slack is a cloud-based team collaboration platform that provides chat, file sharing, and integrations with other tools and services.
  api_count: 32
  score_band: strong
  score_composite: 65.2
  shared: 2
- slug: spruce-health
  name: Spruce Health
  description: Spruce Health is a HIPAA-compliant healthcare communication platform that unifies phone, SMS, secure messaging, video, e-fax, team chat, mobile payments and VoIP phone lines into one system for medical practices, with AI-enabled voicemail…
  api_count: 16
  score_band: strong
  score_composite: 64.2
  shared: 2
- slug: gladly
  name: Gladly
  description: Gladly is a San Francisco–based people-centered customer service AI platform. The Gladly Hero agent workspace unifies voice, chat, SMS, email, and social into a single, channel-agnostic conversation per Customer, while Gladly Sidekick AI h…
  api_count: 1
  score_band: strong
  score_composite: 62.9
  shared: 2
- slug: lithium
  name: Lithium
  description: Lithium Technologies is the enterprise online-community and social-customer-engagement platform that, after merging with Spredfast in 2018, rebranded as Khoros and is today operated by IgniteTech. The Lithium name is still load-bearing in…
  api_count: 28
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: entergram
  name: Entergram
  description: Entergram is a CRM built specifically for Telegram. It connects personal Telegram accounts (not bots) into a shared team workspace where sales, support, community and trading teams manage conversations at scale — a multi-account inbox, a C…
  api_count: 1
  score_band: strong
  score_composite: 58.0
  shared: 2
- slug: fixie
  name: Fixie
  description: Fixie is the company behind Ultravox Realtime, a speech-native voice AI platform for building natural, low-latency conversational voice agents. Rather than transcribing speech to text first, Ultravox processes audio directly to preserve to…
  api_count: 1
  score_band: strong
  score_composite: 57.6
  shared: 2
- slug: intercom
  name: Intercom
  description: Intercom is an AI-powered customer service platform that enables businesses to build seamless customized experiences through its Help Desk and Messenger. The Intercom API allows developers to integrate with the Intercom platform using REST…
  api_count: 1
  score_band: developing
  score_composite: 53.3
  shared: 2
- slug: voicegenie
  name: VoiceGenie
  description: VoiceGenie (Ori Labs Ltd.) is a conversational voice AI platform for sales automation that lets teams deploy AI voice agents to run outbound and inbound phone calls end to end. Businesses build assistants (voice bots) with a chosen voice,…
  api_count: 1
  score_band: developing
  score_composite: 52.7
  shared: 2
- slug: zenzap
  name: ZenZap
  description: Zenzap is an AI-native work communication platform — "Work Chat Built for the AI Era" — used by teams in healthcare, hospitality, construction, food service, retail, franchise, manufacturing, and non-profit operations. It organizes work in…
  api_count: 1
  score_band: developing
  score_composite: 52.3
  shared: 2
---
