---
layout: topic
slug: imap
name: IMAP
kind: topic
description: IMAP (Internet Message Access Protocol) is a standard email protocol that allows email clients to access and manage email messages stored on a mail server. IMAP enables users to view and manage email from multiple devices while keeping messages synchronized on the server.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/imap.png
tags:
- Email
- IMAP
- Messaging
- Protocol
repo: https://github.com/api-evangelist/imap
api_count: 0
apis: []
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/imap/blob/main/security/imap-domain-security.yml
- type: Website
  url: https://www.ietf.org/rfc/rfc3501.txt
provider_count: 48
providers:
- slug: agentmail
  name: AgentMail
  description: AgentMail is an API-first email platform that gives AI agents their own email inboxes to autonomously send, receive, reply to, and act on email. Unlike traditional transactional email APIs built for one-way notifications, AgentMail is desi…
  api_count: 1
  score_band: strong
  score_composite: 60.2
  shared: 3
- slug: smtp
  name: SMTP
  description: Simple Mail Transfer Protocol (SMTP) is the foundational internet standard for transmitting electronic mail across networks. Defined in RFC 5321 (October 2008), SMTP uses a command-response model over TCP port 25 (or 587 for submission, 46…
  api_count: 2
  score_band: emerging
  score_composite: 13.0
  shared: 3
- slug: nylas
  name: Nylas
  description: Nylas connects your application to every email inbox and calendar in the world. The Nylas v3 platform provides REST APIs for email, calendar, contacts, scheduling, meeting notetaking, authentication, and administration across Google, Micro…
  api_count: 2
  score_band: exemplar
  score_composite: 93.2
  shared: 2
- slug: customer-io
  name: Customer.io
  description: Customer.io is a customer engagement platform that combines a customer data platform, marketing automation, and messaging delivery to send behavior-triggered email, push, SMS, and in-app messages. Its API surface includes the Track API for…
  api_count: 4
  score_band: exemplar
  score_composite: 83.8
  shared: 2
- slug: infobip
  name: Infobip
  description: Infobip is a global communications platform as a service (CPaaS) provider headquartered in Vodnjan, Croatia, and is Croatia's largest technology company. It sells programmable messaging, voice, video, email and customer engagement APIs on…
  api_count: 48
  score_band: exemplar
  score_composite: 82.4
  shared: 2
- slug: brevo
  name: Brevo
  description: Brevo (formerly Sendinblue) is a French customer-relationship platform that combines email marketing, transactional email and SMTP relay, transactional and campaign SMS, WhatsApp messaging, web and mobile push, live chat, a sales CRM, an e…
  api_count: 21
  score_band: exemplar
  score_composite: 81.7
  shared: 2
- slug: amazon-ses
  name: Amazon SES
  description: Amazon Simple Email Service (SES) is AWS's cloud email platform for sending and receiving mail at scale — marketing, notification and transactional. The current contract is the SES v2 API (version 2019-09-27), an 86-operation REST-JSON ser…
  api_count: 2
  score_band: exemplar
  score_composite: 80.5
  shared: 2
- slug: amazon-pinpoint
  name: Amazon Pinpoint
  description: Amazon Pinpoint is a flexible and scalable outbound and inbound marketing communications service that enables you to engage with customers across multiple messaging channels including email, SMS, push notifications, and voice messages. Not…
  api_count: 2
  score_band: exemplar
  score_composite: 78.9
  shared: 2
- slug: twilio
  name: Twilio
  description: Cloud communications platform providing APIs for SMS, voice, video, and authentication services. Twilio offers 30+ APIs covering messaging, voice, video, email, identity verification, IoT connectivity, and contact center solutions. Used by…
  api_count: 40
  score_band: exemplar
  score_composite: 77.8
  shared: 2
- slug: braze
  name: Braze
  description: Braze is a leading customer engagement platform providing REST APIs for managing user profiles, orchestrating multi-channel messaging campaigns, and exporting analytics. The platform supports email, SMS, push notifications, in-app messages…
  api_count: 1
  score_band: exemplar
  score_composite: 75.1
  shared: 2
- slug: novu
  name: Novu
  description: Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — wit…
  api_count: 1
  score_band: exemplar
  score_composite: 71.1
  shared: 2
- slug: postmark
  name: Postmark
  description: Postmark is an email delivery service that helps businesses send and track transactional and broadcast email reliably, replacing SMTP with a scalable service that surfaces detailed delivery analytics, bounce tracking, open and click tracki…
  api_count: 3
  score_band: exemplar
  score_composite: 70.2
  shared: 2
- slug: sendpulse
  name: SendPulse
  description: SendPulse is a multichannel marketing automation platform covering bulk email, SMTP transactional email, SMS, web push, website pop-ups, a CRM, an online course builder, and chatbots across WhatsApp, Telegram, Facebook Messenger, Instagram…
  api_count: 20
  score_band: exemplar
  score_composite: 69.5
  shared: 2
- slug: smtp2go
  name: SMTP2GO
  description: SMTP2GO is a New Zealand-founded email and SMS delivery platform, running since 2006, that sends and tracks transactional and marketing messages over SMTP relay or a JSON REST API from data centres in the United States, the European Union…
  api_count: 1
  score_band: exemplar
  score_composite: 69.0
  shared: 2
- slug: paubox
  name: Paubox
  description: Paubox is a HIPAA compliant, HITRUST certified email infrastructure company serving healthcare organizations in the United States. Its products encrypt outbound email without recipient portals, passwords, or plugins, and work alongside Goo…
  api_count: 3
  score_band: exemplar
  score_composite: 68.4
  shared: 2
- slug: knock-app
  name: Knock
  description: Knock is notifications infrastructure as a service — a product and customer messaging platform you use to power transactional, lifecycle, broadcast, and in-product messaging across email, SMS, push, in-app, in-app guides, chat (Slack / Dis…
  api_count: 13
  score_band: exemplar
  score_composite: 68.1
  shared: 2
- slug: zavu
  name: Zavu
  description: Zavu is a unified multi-channel messaging platform that consolidates SMS, WhatsApp, Telegram, Email, Voice, and Messenger behind a single REST API, so developers integrate once instead of stitching together Twilio, Vonage, MessageBird and…
  api_count: 1
  score_band: strong
  score_composite: 60.1
  shared: 2
- slug: amazon-sns
  name: Amazon SNS
  description: Amazon Simple Notification Service (SNS) is a fully managed messaging service for both application-to-application (A2A) and application-to-person (A2P) communication. It enables pub/sub, SMS, email, and mobile push notifications.
  api_count: 1
  score_band: strong
  score_composite: 58.5
  shared: 2
- slug: dyspatch
  name: Dyspatch
  description: Dyspatch is an email template management and production platform that lets marketing, design, and engineering teams build, collaborate on, approve, localize, and publish transactional and marketing messages without hand-coding HTML. Conten…
  api_count: 1
  score_band: strong
  score_composite: 58.3
  shared: 2
- slug: cordial
  name: Cordial
  description: Cordial is a cross-channel marketing and customer data platform headquartered in San Diego, California, used by consumer brands to unify customer data and orchestrate personalized messaging across email, SMS/MMS, RCS, mobile app (push, in-…
  api_count: 2
  score_band: strong
  score_composite: 58.2
  shared: 2
- slug: mailersend
  name: MailerSend
  description: MailerSend is a transactional email and SMS platform built for developers. Its v1 REST API covers email sending (single, bulk to 500 objects per request, and scheduled up to 72 hours out), SMTP relay, templates, sending domains and DNS ver…
  api_count: 1
  score_band: strong
  score_composite: 57.4
  shared: 2
- slug: insider
  name: Insider
  description: Insider (rebranded Insider One; useinsider.com now redirects to insiderone.com) is an AI-native customer engagement and personalization platform used by 2,000+ global brands. It unifies a Customer Data Platform, cross-channel journey orche…
  api_count: 18
  score_band: developing
  score_composite: 54.0
  shared: 2
- slug: route-mobile
  name: Route Mobile
  description: Route Mobile Limited is a Mumbai-headquartered cloud communications platform (CPaaS) provider and one of India's largest A2P messaging aggregators, listed on the BSE and NSE and now majority-owned by Belgium's Proximus Group, where it sits…
  api_count: 5
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: frontapp
  name: FrontApp
  description: Front is a customer service and communication platform that combines the efficiency of a help desk with the familiarity of email, giving teams a shared inbox across email, SMS, chat, and social channels. The Front Core API is a REST API (b…
  api_count: 1
  score_band: developing
  score_composite: 49.9
  shared: 2
- slug: bluecore
  name: Bluecore
  description: Bluecore is a retail marketing technology platform that unifies shopper identity, behavior, and product data into a customer data platform with 20+ predictive AI models, cross-channel experience orchestration (email, SMS, site, paid media)…
  api_count: 3
  score_band: developing
  score_composite: 48.8
  shared: 2
- slug: fyno
  name: Fyno
  description: Fyno is a notification routing and orchestration platform that provides a single unified REST API for sending and managing notifications across 10+ communication channels including email, SMS, push, WhatsApp, in-app, RCS, voice, and iMessa…
  api_count: 1
  score_band: developing
  score_composite: 48.3
  shared: 2
- slug: commsharbor
  name: CommsHarbor
  description: Transactional email and permission-based marketing infrastructure with tenant isolation, deliverability tracking, CRM, and multi-tenant governance. Self-describes as an agent-first HTTP API with a hosted MCP server.
  api_count: 2
  score_band: developing
  score_composite: 46.5
  shared: 2
- slug: missive
  name: Missive
  description: Missive is a team inbox and collaboration platform that brings email, SMS, WhatsApp, Instagram, Facebook Messenger, and live chat into one unified workspace. It provides a REST API for managing conversations, messages, contacts, labels, dr…
  api_count: 1
  score_band: developing
  score_composite: 46.5
  shared: 2
- slug: bird
  name: Bird
  description: Bird (formerly MessageBird) is an omnichannel customer communications platform offering REST APIs for email, SMS, WhatsApp, RCS, push notifications, voice, and data management. Trusted by more than 450,000 developers, Bird provides enterpr…
  api_count: 23
  score_band: developing
  score_composite: 45.5
  shared: 2
- slug: google-gmail
  name: Google Gmail
  description: The Gmail API lets you view and manage Gmail mailbox data like threads, messages, and labels. It provides RESTful access to Gmail mailboxes, supporting message sending, drafting, organizing with labels, managing settings, and push notifica…
  api_count: 1
  score_band: developing
  score_composite: 44.2
  shared: 2
---
