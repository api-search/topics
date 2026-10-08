---
layout: topic
slug: activitypub
name: ActivityPub
kind: topic
description: ActivityPub is a W3C Recommendation that defines a decentralized social networking protocol and REST API standard for federated social interactions. It provides both a client-to-server API for creating and managing social content and a server-to-server federation protocol for distributing activities across instances. Built on ActivityStreams 2.0 and JSON-LD, it powers the Fediverse — including Mastodon, Pixelfed, PeerTube, and hundreds of other platforms — enabling interoperable social networking across independently operated servers.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/activitypub.png
tags:
- Open Standard
- Social Network
- Federation
- Fediverse
- W3C
repo: https://github.com/api-evangelist/activitypub
api_count: 10
apis:
- name: ActivityPub Followers and Following API
  description: Actors expose followers and following as OrderedCollection or Collection endpoints. These endpoints enumerate the social graph connections for an actor. The Follow activity posted to the outbox initiates a follow relationship; the target a…
- name: ActivityPub Liked Collection API
  description: The liked collection is an optional OrderedCollection endpoint on an actor listing all objects the actor has liked. Posting a Like activity to the actor's outbox adds the referenced object to this collection. It is publicly readable and su…
- name: ActivityPub Object and Activity Delivery API
  description: ActivityPub defines a server-to-server federation protocol for delivering activities between instances. Servers dereference actor inboxes from WebFinger or direct URLs, then HTTP POST signed Activity objects (Create, Update, Delete, Announ…
- name: ActivityPub WebFinger Discovery API
  description: ActivityPub implementations commonly use WebFinger (RFC 7033) for actor discovery. A GET request to /.well-known/webfinger?resource=acct:user@example.com returns a JSON Resource Descriptor (JRD) linking to the actor's canonical ActivityPub…
- name: ActivityPub NodeInfo API
  description: NodeInfo is a complementary protocol used by ActivityPub servers to expose server capability metadata at /.well-known/nodeinfo. It describes the software name, version, supported protocols, usage statistics, and open registration status, e…
- name: ActivityPub Actors API
  description: Actors are the primary objects in ActivityPub that represent entities capable of performing activities. Each actor has a unique IRI and exposes properties such as inbox, outbox, followers, following, and liked collections. Actor objects ar…
- name: ActivityPub Collections API
  description: Followers, following, and liked collections
- name: ActivityPub Discovery API
  description: WebFinger and NodeInfo discovery endpoints
- name: ActivityPub Inbox API
  description: The inbox is an OrderedCollection endpoint on each actor that receives activities delivered by remote servers. Servers POST activities to an actor's inbox to federate content. The inbox also supports GET for authorized clients to retrieve…
- name: ActivityPub Outbox API
  description: The outbox is an OrderedCollection endpoint that stores activities published by an actor. Clients POST activities to an actor's outbox to create, update, delete, follow, like, and perform other social interactions. The server then federate…
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/activitypub/blob/main/agentic-access/activitypub-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/activitypub/blob/main/security/activitypub-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/activitypub/blob/main/authentication/activitypub-authentication.yml
- type: Website
  url: https://activitypub.rocks/
- type: Documentation
  url: https://www.w3.org/TR/activitypub/
- type: Specification
  url: https://www.w3.org/TR/activitypub/
- type: GettingStarted
  url: https://activitypub.rocks/
- type: Authentication
  url: https://www.w3.org/TR/activitypub/#authorization
- type: Security
  url: https://www.w3.org/TR/activitypub/#security-considerations
- type: UseCases
  url: https://www.w3.org/TR/activitypub/#overview
- type: GitHubOrganization
  url: https://github.com/w3c/activitypub
- type: GitHubRepository
  url: https://github.com/w3c/activitypub
- type: Forums
  url: https://socialhub.activitypub.rocks/
- type: ChangeLog
  url: https://www.w3.org/TR/activitypub/#change-log
- type: Vocabulary
  url: https://www.w3.org/TR/activitystreams-vocabulary/
- type: JSONSchema
  url: https://www.w3.org/TR/activitystreams-core/
- type: RateLimits
  url: https://github.com/api-evangelist/activitypub/blob/main/rate-limits/activitypub-rate-limits.yml
- type: Plans
  url: https://github.com/api-evangelist/activitypub/blob/main/plans/activitypub-plans.yml
- type: FinOps
  url: https://github.com/api-evangelist/activitypub/blob/main/finops/activitypub-finops.yml
provider_count: 8
providers:
- slug: misskey
  name: Misskey
  description: Misskey is a free, open-source, decentralized microblogging platform that implements the ActivityPub protocol, enabling federation across independent instances and interoperability with other fediverse software such as Mastodon and Pleroma…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: atproto
  name: AT Protocol
  description: AT Protocol (Authenticated Transfer Protocol) is an open, federated social networking protocol developed by Bluesky Social PBC that powers the Bluesky social network and its 40M+ users. The protocol defines a public HTTP API surface via XR…
  api_count: 2
  score_band: developing
  score_composite: 45.0
  shared: 2
- slug: pixelfed
  name: Pixelfed
  description: Pixelfed is a decentralized, federated photo-sharing platform and open-source alternative to Instagram. Built on the ActivityPub protocol, it connects with the broader Fediverse — including Mastodon, PeerTube, and other federated networks…
  api_count: 1
  score_band: developing
  score_composite: 44.2
  shared: 2
- slug: diaspora
  name: Diaspora
  description: diaspora* is a privacy-aware, decentralized, open source social network, launched in 2010 and released under the AGPL. Rather than running on servers owned by a single company, diaspora* runs as a federated network of independently operate…
  api_count: 1
  score_band: developing
  score_composite: 42.2
  shared: 2
- slug: lemmy
  name: Lemmy
  description: Lemmy is a free, open-source, self-hostable federated link aggregator and discussion platform built as a Reddit alternative. It exposes a versioned REST API at /api/v4/ for creating posts, commenting, managing communities, voting, searchin…
  api_count: 1
  score_band: developing
  score_composite: 41.8
  shared: 2
- slug: elk
  name: Elk
  description: Elk is a nimble, MIT-licensed Mastodon web client maintained by Anthony Fu, Daniel Roe, Kevin Deng and Patak. It runs as a Nuxt 4 progressive web app at elk.zone and connects to any Mastodon-compatible instance the user chooses, speaking t…
  api_count: 1
  score_band: thin
  score_composite: 30.0
  shared: 2
- slug: zot
  name: Zot
  description: A decentralized communication protocol and platform for federated social networking, enabling secure and private content sharing across distributed servers.
  api_count: 1
  score_band: emerging
  score_composite: 18.5
  shared: 2
- slug: salduu-profe-social
  name: Salduu (Profe Social)
  description: Salduu, operating as Profe Social at profe.social, is a 500 Global-backed social networking platform. The live host serves Mastodon's default robots.txt (Disallow /search, sitemap.xml.gz) and a Ruby on Rails error stack, indicating the pla…
  api_count: 0
  score_band: minimal
  score_composite: 2.9
  shared: 2
---
