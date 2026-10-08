---
layout: topic
slug: rss
name: RSS
kind: topic
description: RSS (Really Simple Syndication) is the canonical XML feed format family for publishing and subscribing to streams of frequently updated content — blogs, news, podcasts, and other periodic resources. The RSS family in this index covers RSS 2.0 (stewarded by the RSS Advisory Board), Atom 1.0 (RFC 4287), JSON Feed 1.1, the RSS Best Practices Profile, OPML 2.0 for feed subscription lists, and HTML autodiscovery conventions used by feed readers to locate feeds from a site's homepage.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/rss.png
tags:
- Syndication
- RSS
- Atom
- JSON Feed
- OPML
- Content
- XML
- Specification
- Standards
repo: https://github.com/api-evangelist/rss
api_count: 6
apis:
- name: RSS 2.0
  description: RSS 2.0 is the dominant XML-based syndication format, stewarded by the RSS Advisory Board. A feed consists of a root <rss version="2.0"> element wrapping a single <channel> with required title, link, and description, plus a sequence of <it…
  url: https://www.rssboard.org/rss-specification
- name: Atom 1.0
  description: Atom 1.0, defined by IETF RFC 4287, is an XML-based syndication format developed as a more rigorously specified alternative to RSS 2.0. An Atom feed (atom:feed) contains required atom:id, atom:title, atom:updated, and atom:author elements…
  url: https://datatracker.ietf.org/doc/html/rfc4287
- name: JSON Feed 1.1
  description: JSON Feed 1.1 is a JSON-based syndication format created by Brent Simmons and Manton Reece as a developer-friendly alternative to RSS and Atom. A JSON Feed has top-level version, title, and items, with each item carrying a required id and…
  url: https://www.jsonfeed.org/version/1.1/
- name: RSS Best Practices Profile
  description: The RSS Best Practices Profile is the RSS Advisory Board's normative guidance on producing RSS feeds that interoperate cleanly across the diverse population of feed readers. It covers character data, date formats, email addresses, URLs, el…
  url: https://www.rssboard.org/rss-profile
- name: OPML 2.0
  description: OPML (Outline Processor Markup Language) 2.0 is an XML format for outlines, most commonly used to exchange lists of RSS/Atom feed subscriptions between feed readers. A subscription list OPML file has a body containing outline elements with…
  url: http://opml.org/spec2.opml
- name: Feed Autodiscovery
  description: Feed autodiscovery is the HTML convention by which a web page advertises the location of its RSS, Atom, or JSON Feed using a <link rel="alternate" type="application/rss+xml" href="..."> element in the document head. Feed readers, browsers,…
  url: https://www.rssboard.org/rss-autodiscovery
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/rss/blob/main/security/rss-domain-security.yml
- type: Website
  url: https://www.rssboard.org/
- type: Documentation
  url: https://www.rssboard.org/rss-specification
- type: BestPractices
  url: https://www.rssboard.org/rss-profile
- type: Validator
  url: https://www.rssboard.org/rss-validator/
- type: Blog
  url: https://www.rssboard.org/news
- type: AtomSpecification
  url: https://datatracker.ietf.org/doc/html/rfc4287
- type: JSONFeedSpecification
  url: https://www.jsonfeed.org/version/1.1/
- type: OPMLSpecification
  url: http://opml.org/spec2.opml
- type: JSONLDContext
  url: https://github.com/api-evangelist/rss/blob/main/json-ld/rss-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/rss/blob/main/vocabulary/rss-vocabulary.yml
provider_count: 22
providers:
- slug: gsma
  name: GSMA
  description: The GSMA (GSM Association) is the London-headquartered global trade body for the mobile industry, representing roughly 750 mobile network operators and around 400 companies in the wider mobile ecosystem, and the organiser of MWC Barcelona.…
  api_count: 37
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: acord
  name: ACORD
  description: ACORD is the global standards-setting body for the insurance industry, publishing the data standards that insurers, reinsurers, brokers, MGAs and software vendors use to exchange policy, claims, party, underwriting, accounting and settleme…
  api_count: 6
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: asyncapi
  name: AsyncAPI
  description: AsyncAPI is a Linux Foundation project that improves the state of event-driven architectures by providing an open specification and tooling ecosystem for defining asynchronous and event-driven APIs. It enables developers to document, valid…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: opentravel-alliance
  name: OpenTravel Alliance
  description: The OpenTravel Alliance is a volunteer, non-profit travel technology standards body headquartered in Melbourne, Florida, United States. Since 1999 it has published the OpenTravel Specification — the OTA 1.0 XML message suite (releases 2001…
  api_count: 8
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: meredith
  name: Dotdash Meredith / People Inc
  description: Profile for People Inc (formerly Dotdash Meredith) in the API Evangelist network. America's largest digital and print publisher, operating 40+ brands including PEOPLE, Better Homes & Gardens, Allrecipes, Investopedia, Verywell, Food & Wine…
  api_count: 30
  score_band: developing
  score_composite: 43.0
  shared: 2
- slug: rss-app
  name: RSS.app
  description: RSS.app provides a no‑code platform that lets users generate RSS feeds from any website or social media source, create embeddable widgets, and automate content distribution via bots to Discord, Slack, Telegram, and email. It offers a suite…
  api_count: 3
  score_band: developing
  score_composite: 39.8
  shared: 2
- slug: vice-media
  name: Vice Media
  description: Vice Media is the Brooklyn, New York youth-culture and news media company founded in 1994 in Montreal by Suroosh Alvi, Shane Smith and Gavin McInnes, which grew from the VICE magazine into a global multi-platform publisher, film and televi…
  api_count: 6
  score_band: thin
  score_composite: 36.5
  shared: 2
- slug: newsblur
  name: NewsBlur
  description: NewsBlur is a personal news reader that brings people together to talk about the world. It is an RSS/Atom feed aggregator with training-based intelligence (hide or highlight stories per feed), original-site and original-text views, saved (…
  api_count: 1
  score_band: thin
  score_composite: 35.2
  shared: 2
- slug: aousd
  name: Alliance for OpenUSD
  description: The Alliance for OpenUSD (AOUSD) is a Linux Foundation project dedicated to promoting interoperability of 3D content through Universal Scene Description (OpenUSD). Founded by Pixar, Adobe, Apple, Autodesk, and NVIDIA, AOUSD standardizes 3D…
  api_count: 2
  score_band: thin
  score_composite: 29.8
  shared: 2
- slug: apis-json
  name: APIs.json
  description: APIs.json is an open, machine-readable specification that API providers can use to describe their API operations, similar to how websites use sitemap.xml. The format provides a lightweight means for individuals and organizations to documen…
  api_count: 1
  score_band: thin
  score_composite: 28.2
  shared: 2
- slug: openehr
  name: openEHR
  description: 'openEHR is the open specification family for electronic health records, and the main structural alternative to HL7 FHIR. It is governed by two UK not-for-profit entities: the openEHR Foundation, a company limited by guarantee that holds th…'
  api_count: 13
  score_band: thin
  score_composite: 27.0
  shared: 2
- slug: agentic-resource-discovery
  name: Agentic Resource Discovery (ARD)
  description: Agentic Resource Discovery (ARD) is a proposed open standard for the discovery layer that sits in front of every agentic protocol — the step before invocation, where a client asks "what is available for this task?" and gets back a ranked s…
  api_count: 1
  score_band: emerging
  score_composite: 23.5
  shared: 2
- slug: cbs
  name: CBS (Paramount Global)
  description: CBS is the flagship broadcast television network of Paramount (Paramount Skydance Corporation, formerly Paramount Global), covering CBS Entertainment, CBS News, CBS Sports and the CBS owned-and-operated stations, and feeding Paramount+. CB…
  api_count: 2
  score_band: emerging
  score_composite: 23.1
  shared: 2
- slug: wired
  name: Wired
  description: Wired (wired.com) is an American technology and culture magazine published by Condé Nast, covering how emerging technologies affect culture, the economy, and politics. Founded in 1993, Wired provides RSS feeds for programmatic content cons…
  api_count: 1
  score_band: emerging
  score_composite: 21.9
  shared: 2
- slug: federal-accounting-standards-advisory-board
  name: Federal Accounting Standards Advisory Board
  description: The Federal Accounting Standards Advisory Board (FASAB) is the U.S. federal advisory body designated to set generally accepted accounting principles for the federal government and its component reporting entities. FASAB issues Statements o…
  api_count: 1
  score_band: emerging
  score_composite: 21.2
  shared: 2
- slug: ogc
  name: Open Geospatial Consortium (OGC)
  description: The Open Geospatial Consortium is the standards body for geospatial interoperability — a member-funded consortium founded in 1994 and headquartered in the United States, with 362 member organizations plus 159 individual members across gove…
  api_count: 24
  score_band: emerging
  score_composite: 17.8
  shared: 2
- slug: hackernoon
  name: Hackernoon
  description: HackerNoon is an independent technology publishing platform and community CMS, founded in 2016 by David Smooke and headquartered in Edwards, Colorado. It operates a free, open library of more than 150,000 practitioner-authored, human-edite…
  api_count: 0
  score_band: emerging
  score_composite: 16.9
  shared: 2
- slug: astm-international
  name: ASTM International
  description: ASTM International is one of the world's largest voluntary standards development organizations, founded in 1898. ASTM publishes more than 13,000 globally recognized consensus standards across 150+ technical committees and 2,100+ subcommitt…
  api_count: 2
  score_band: emerging
  score_composite: 13.2
  shared: 2
- slug: openapi-initiative
  name: OpenAPI Initiative
  description: The OpenAPI Initiative is a Linux Foundation project that promotes the OpenAPI Specification for defining standard, language-agnostic interfaces to RESTful APIs. It provides governance, tooling ecosystem support, and community collaboratio…
  api_count: 1
  score_band: minimal
  score_composite: 10.1
  shared: 2
- slug: mismo
  name: MISMO
  description: MISMO — the Mortgage Industry Standards Maintenance Organization — is the standards development body for US real estate finance, founded in 1999 and a not-for-profit wholly owned subsidiary of the Mortgage Bankers Association since 2004. I…
  api_count: 0
  score_band: minimal
  score_composite: 6.7
  shared: 2
- slug: fox-rothschild
  name: Fox Rothschild
  description: 'Fox Rothschild LLP is a national US law firm with approximately 1,000 attorneys across 30+ offices. The firm has no public developer APIs. Its programmatic surface is limited to publication and content distribution: subscription-based emai…'
  api_count: 21
  score_band: minimal
  score_composite: 6.3
  shared: 2
- slug: associated-content
  name: Associated Content
  description: Associated Content was an open content publishing platform founded in 2005 by Luke Beatty that paid contributors to publish articles, video, audio, and images on any topic, then distributed that library through associatedcontent.com and a…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 2
---
