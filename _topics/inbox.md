---
layout: topic
slug: inbox
name: Inbox
kind: topic
description: Inbox is an API Evangelist index of email and inbox-oriented API platforms that developers use to send, receive, parse, route, schedule, and verify email messages. The index focuses on transactional and conversational email providers exposing programmatic access to message lifecycle, deliverability, and inbox automation primitives.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/inbox.png
tags:
- Email
- Inbox
- Messaging
- Deliverability
- Transactional Email
repo: https://github.com/api-evangelist/inbox
api_count: 2
apis:
- name: Mailgun Email API
  description: Mailgun provides a programmable email API for sending, receiving, tracking, and validating email at scale. Endpoints cover messages, domains, suppressions, mailing lists, webhooks, inbound routes, event streams, and inbox placement testing…
  url: https://www.mailgun.com/
- name: Nylas Email API
  description: Nylas exposes a unified REST API for email, calendar, contacts, and scheduling across Google, Microsoft, iCloud, and IMAP providers. Developers can read, send, and thread messages, manage folders and labels, handle attachments, and subscri…
  url: https://www.nylas.com/products/email-api/
links:
- type: TrustCenter
  url: https://github.com/api-evangelist/inbox/blob/main/security/inbox-trust-center.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/inbox/blob/main/security/inbox-domain-security.yml
- type: LLMsTxt
  url: https://github.com/api-evangelist/inbox/blob/main/llms/inbox-llms.txt
- type: Website
  url: https://apievangelist.com/
provider_count: 70
providers:
- slug: postmark
  name: Postmark
  description: Postmark is an email delivery service that helps businesses send and track transactional and broadcast email reliably, replacing SMTP with a scalable service that surfaces detailed delivery analytics, bounce tracking, open and click tracki…
  api_count: 3
  score_band: exemplar
  score_composite: 70.2
  shared: 4
- slug: smtp2go
  name: SMTP2GO
  description: SMTP2GO is a New Zealand-founded email and SMS delivery platform, running since 2006, that sends and tracks transactional and marketing messages over SMTP relay or a JSON REST API from data centres in the United States, the European Union…
  api_count: 1
  score_band: exemplar
  score_composite: 69.0
  shared: 4
- slug: mailersend
  name: MailerSend
  description: MailerSend is a transactional email and SMS platform built for developers. Its v1 REST API covers email sending (single, bulk to 500 objects per request, and scheduled up to 72 hours out), SMTP relay, templates, sending domains and DNS ver…
  api_count: 1
  score_band: strong
  score_composite: 57.4
  shared: 4
- slug: commsharbor
  name: CommsHarbor
  description: Transactional email and permission-based marketing infrastructure with tenant isolation, deliverability tracking, CRM, and multi-tenant governance. Self-describes as an agent-first HTTP API with a hosted MCP server.
  api_count: 2
  score_band: developing
  score_composite: 46.5
  shared: 4
- slug: customer-io
  name: Customer.io
  description: Customer.io is a customer engagement platform that combines a customer data platform, marketing automation, and messaging delivery to send behavior-triggered email, push, SMS, and in-app messages. Its API surface includes the Track API for…
  api_count: 4
  score_band: exemplar
  score_composite: 83.8
  shared: 3
- slug: sendgrid
  name: SendGrid
  description: SendGrid is a cloud-based email delivery platform, acquired by Twilio in 2019, that provides transactional and marketing email at scale over an HTTP v3 REST API and an SMTP relay. The platform spans Mail Send, dynamic transactional templat…
  api_count: 44
  score_band: exemplar
  score_composite: 82.4
  shared: 3
- slug: brevo
  name: Brevo
  description: Brevo (formerly Sendinblue) is a French customer-relationship platform that combines email marketing, transactional email and SMTP relay, transactional and campaign SMS, WhatsApp messaging, web and mobile push, live chat, a sales CRM, an e…
  api_count: 21
  score_band: exemplar
  score_composite: 81.7
  shared: 3
- slug: amazon-ses
  name: Amazon SES
  description: Amazon Simple Email Service (SES) is AWS's cloud email platform for sending and receiving mail at scale — marketing, notification and transactional. The current contract is the SES v2 API (version 2019-09-27), an 86-operation REST-JSON ser…
  api_count: 2
  score_band: exemplar
  score_composite: 80.5
  shared: 3
- slug: novu
  name: Novu
  description: Novu is the open-source notification infrastructure for developers. A single REST API and workflow engine route a triggered event across in-app inbox, email, SMS, push, chat (Slack / Discord / MS Teams / WhatsApp) and custom channels — wit…
  api_count: 1
  score_band: exemplar
  score_composite: 71.1
  shared: 3
- slug: sendpulse
  name: SendPulse
  description: SendPulse is a multichannel marketing automation platform covering bulk email, SMTP transactional email, SMS, web push, website pop-ups, a CRM, an online course builder, and chatbots across WhatsApp, Telegram, Facebook Messenger, Instagram…
  api_count: 20
  score_band: exemplar
  score_composite: 69.5
  shared: 3
- slug: paubox
  name: Paubox
  description: Paubox is a HIPAA compliant, HITRUST certified email infrastructure company serving healthcare organizations in the United States. Its products encrypt outbound email without recipient portals, passwords, or plugins, and work alongside Goo…
  api_count: 3
  score_band: exemplar
  score_composite: 68.4
  shared: 3
- slug: agentmail
  name: AgentMail
  description: AgentMail is an API-first email platform that gives AI agents their own email inboxes to autonomously send, receive, reply to, and act on email. Unlike traditional transactional email APIs built for one-way notifications, AgentMail is desi…
  api_count: 1
  score_band: strong
  score_composite: 60.2
  shared: 3
- slug: mailpace
  name: MailPace
  description: MailPace is a fast, privacy-focused transactional email API for developers. It delivers application email - password resets, receipts, notifications - over a simple HTTPS REST API and SMTP, with DKIM-verified sending domains, Ed25519-signe…
  api_count: 1
  score_band: thin
  score_composite: 32.8
  shared: 3
- slug: mailgun
  name: Mailgun
  description: Mailgun (by Sinch) is a transactional email API service for developers to send, receive, validate, and track emails at scale. The platform provides SMTP and HTTP APIs for sending email, inbound message routing, deliverability analytics, su…
  api_count: 1
  score_band: thin
  score_composite: 30.9
  shared: 3
- slug: nylas
  name: Nylas
  description: Nylas connects your application to every email inbox and calendar in the world. The Nylas v3 platform provides REST APIs for email, calendar, contacts, scheduling, meeting notetaking, authentication, and administration across Google, Micro…
  api_count: 2
  score_band: exemplar
  score_composite: 93.2
  shared: 2
- slug: ahasend
  name: AhaSend
  description: AhaSend is a developer-focused transactional email platform providing fast, reliable email delivery via REST API and SMTP relay. It offers features including email tracking, webhooks, email routing, suppression management, domain managemen…
  api_count: 2
  score_band: exemplar
  score_composite: 84.3
  shared: 2
- slug: infobip
  name: Infobip
  description: Infobip is a global communications platform as a service (CPaaS) provider headquartered in Vodnjan, Croatia, and is Croatia's largest technology company. It sells programmable messaging, voice, video, email and customer engagement APIs on…
  api_count: 48
  score_band: exemplar
  score_composite: 82.4
  shared: 2
- slug: mailchimp
  name: Mailchimp
  description: Mailchimp is an Intuit company providing a marketing automation platform and email marketing service for managing mailing lists, creating email marketing campaigns, and automating marketing workflows. It exposes two distinct developer surf…
  api_count: 4
  score_band: exemplar
  score_composite: 79.2
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
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 76.7
  shared: 2
- slug: braze
  name: Braze
  description: Braze is a leading customer engagement platform providing REST APIs for managing user profiles, orchestrating multi-channel messaging campaigns, and exporting analytics. The platform supports email, SMS, push notifications, in-app messages…
  api_count: 1
  score_band: exemplar
  score_composite: 75.1
  shared: 2
- slug: plunk
  name: Plunk
  description: Plunk is an open-source (AGPL-3.0) email platform for developers that unifies transactional email, marketing campaigns, contact segmentation and event-driven workflow automation behind a single REST API. It publishes its own OpenAPI 3.1.0…
  api_count: 2
  score_band: exemplar
  score_composite: 75.1
  shared: 2
- slug: mailerlite
  name: MailerLite
  description: MailerLite is an email marketing and automation platform used by creators, e-commerce sellers and small businesses to build lists, send campaigns and run behavioural automations. The current REST API at connect.mailerlite.com exposes subsc…
  api_count: 1
  score_band: exemplar
  score_composite: 73.7
  shared: 2
- slug: loops
  name: Loops
  description: Loops is an email platform built for software companies, combining marketing campaigns, product and lifecycle automation, and transactional email on one contact model. Its REST API v1 exposes 64 operations across contacts, contact properti…
  api_count: 1
  score_band: exemplar
  score_composite: 71.4
  shared: 2
- slug: mailboxlayer
  name: Mailboxlayer
  description: Real-time email validation and verification REST/JSON API operated by APILayer. Provides syntax checks, typo suggestions, MX-record lookup, SMTP verification, catch-all/role/disposable/free-provider detection, and a deliverability quality…
  api_count: 2
  score_band: exemplar
  score_composite: 68.9
  shared: 2
- slug: knock-app
  name: Knock
  description: Knock is notifications infrastructure as a service — a product and customer messaging platform you use to power transactional, lifecycle, broadcast, and in-product messaging across email, SMS, push, in-app, in-app guides, chat (Slack / Dis…
  api_count: 13
  score_band: exemplar
  score_composite: 68.1
  shared: 2
- slug: ortto
  name: Ortto
  description: Ortto (formerly Autopilot) is a marketing automation, customer data platform (CDP), and analytics product. Its REST API at https://api.ap3api.com/v1 lets applications create and update people/contacts and accounts, send custom activity eve…
  api_count: 1
  score_band: exemplar
  score_composite: 67.5
  shared: 2
- slug: benchmark-email
  name: Benchmark Email
  description: Benchmark Email is an email marketing platform for small businesses, run by Benchmark Internet Group, with two live REST API generations. The current Benchmark Email API on the benchmarkemail.io platform covers contacts, contact structures…
  api_count: 2
  score_band: strong
  score_composite: 65.0
  shared: 2
- slug: mailmodo
  name: Mailmodo
  description: Mailmodo is an AI-powered interactive email marketing and automation platform headquartered in Bengaluru with a presence in San Francisco. It pioneered AMP-for-Email at scale, letting brands embed forms, quizzes, polls, carousels, and cale…
  api_count: 9
  score_band: strong
  score_composite: 64.4
  shared: 2
---
