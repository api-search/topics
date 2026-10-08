---
layout: topic
slug: web-standards
name: Web Standards
kind: topic
description: Specifications and guidelines that define how web technologies should work, ensuring interoperability and consistency across browsers and platforms. Web standards are developed by organizations like W3C, WHATWG, IETF, and ECMA International. This topic covers the full landscape of web standards including HTML, CSS, JavaScript APIs, networking, security, graphics, media, and emerging technologies.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/web-standards.png
tags:
- Browser Compatibility
- CSS
- HTML
- Interoperability
- JavaScript
- Standards
- Web API
- Web Development
repo: https://github.com/api-evangelist/web-standards
api_count: 24
apis:
- name: WHATWG HTML Living Standard
  description: The core markup language of the web, including Web Workers, localStorage, history, the canvas element, forms, and numerous JavaScript APIs. Maintained by WHATWG and published as a continuously updated Living Standard.
  url: https://html.spec.whatwg.org/multipage/
- name: WHATWG Fetch Living Standard
  description: The networking model for resource retrieval on the web. Defines the Fetch API used by browsers and JavaScript to make HTTP requests, replacing the older XMLHttpRequest API.
  url: https://fetch.spec.whatwg.org/
- name: WHATWG DOM Living Standard
  description: The core infrastructure used to define the web. Specifies the Document Object Model (DOM), which represents HTML/XML documents as a tree of nodes that scripts can manipulate.
  url: https://dom.spec.whatwg.org/
- name: WHATWG URL Living Standard
  description: Infrastructure and algorithms around URLs on the web. Defines how URLs are parsed, serialized, and resolved, and specifies the URL and URLSearchParams APIs.
  url: https://url.spec.whatwg.org/
- name: WHATWG Streams Living Standard
  description: APIs for creating, composing, and consuming streams of data. Defines ReadableStream, WritableStream, and TransformStream interfaces for efficient data processing.
  url: https://streams.spec.whatwg.org/
- name: WHATWG WebSockets Living Standard
  description: APIs to enable web applications to maintain bidirectional communications with server-side processes. Defines the WebSocket interface for full-duplex communication channels over a single TCP connection.
  url: https://websockets.spec.whatwg.org/
- name: WHATWG Storage Living Standard
  description: Persistent storage API, quota management, and platform storage architecture. Defines how web applications can store data persistently and manage storage quotas.
  url: https://storage.spec.whatwg.org/
- name: WHATWG Encoding Living Standard
  description: Character encoding functionality on the web. Defines the TextEncoder and TextDecoder APIs for converting between strings and binary data using various character encodings.
  url: https://encoding.spec.whatwg.org/
- name: WHATWG Notifications API Living Standard
  description: Provides an API allowing web pages to control the display of system notifications to end users, enabling alerts outside the context of a web page.
  url: https://notifications.spec.whatwg.org/
- name: WHATWG File System Living Standard
  description: Infrastructure and API for accessing the file system. Provides FileSystemHandle, FileSystemFileHandle, and FileSystemDirectoryHandle interfaces for reading and writing files on the user's local device.
  url: https://fs.spec.whatwg.org/
- name: W3C CSS Specifications
  description: Cascading Style Sheets specifications developed by the W3C CSS Working Group. Covers layout (Flexbox, Grid), selectors, animations, transforms, custom properties, and all aspects of web presentation.
  url: https://www.w3.org/Style/CSS/
- name: W3C Web Authentication (WebAuthn)
  description: A W3C Recommendation that defines a strong authentication API for web applications, enabling passwordless and multi-factor authentication using public key cryptography and hardware authenticators.
  url: https://www.w3.org/TR/webauthn/
- name: W3C WebRTC
  description: Web Real-Time Communications specifications enabling peer-to-peer audio, video, and data communication directly between browsers without plugins. Developed by the W3C WebRTC Working Group.
  url: https://www.w3.org/TR/webrtc/
- name: W3C WebGPU
  description: A W3C specification providing a modern GPU-accelerated graphics and compute interface for the web. Developed by the GPU for the Web Working Group as a successor to WebGL.
  url: https://www.w3.org/TR/webgpu/
- name: W3C Web Components
  description: 'A suite of W3C specifications enabling reusable custom elements: Custom Elements v1, Shadow DOM, and HTML Templates. Allows developers to create encapsulated, reusable UI components.'
  url: https://www.w3.org/standards/techs/components
- name: W3C Service Workers
  description: A W3C specification that enables web applications to work offline, do background synchronization, and intercept network requests. Service Workers act as a programmable network proxy between the browser and network.
  url: https://www.w3.org/TR/service-workers/
- name: W3C Payment Request API
  description: A W3C Recommendation that standardizes the checkout process on the web, reducing the need for forms by using browser-stored payment information and supporting multiple payment methods.
  url: https://www.w3.org/TR/payment-request/
- name: W3C WebAssembly
  description: A portable binary instruction format for a stack-based virtual machine. Enables near-native performance for web applications written in languages like C, C++, and Rust.
  url: https://www.w3.org/TR/wasm-core-1/
- name: W3C JSON-LD
  description: JSON-LD 1.1 is a W3C Recommendation for Linked Data in JSON format. Provides a method to encode Linked Data using JSON, enabling semantic interoperability and integration with the Semantic Web.
  url: https://www.w3.org/TR/json-ld11/
- name: W3C Verifiable Credentials
  description: A W3C Recommendation that defines a data model for expressing credentials on the web in a cryptographically secure, privacy-respecting, and machine-verifiable way.
  url: https://www.w3.org/TR/vc-data-model/
- name: W3C Web Neural Network API (WebNN)
  description: A W3C specification enabling hardware-accelerated machine learning inference directly in web browsers, providing a low-level API for neural network operations on CPUs, GPUs, and dedicated ML accelerators.
  url: https://www.w3.org/TR/webnn/
- name: W3C Decentralized Identifiers (DIDs)
  description: A W3C Recommendation defining a new type of identifier enabling verifiable, decentralized digital identity. DIDs are globally unique, resolvable with high availability, and cryptographically verifiable.
  url: https://www.w3.org/TR/did-core/
- name: IETF HTTP Specifications
  description: The IETF HTTP Working Group specifications defining the HyperText Transfer Protocol. Includes HTTP/1.1 (RFC 9110), HTTP/2 (RFC 9113), HTTP/3 (RFC 9114), and related standards for caching, cookies, and security headers.
  url: https://httpwg.org/
- name: ECMA JavaScript (ECMAScript)
  description: The ECMAScript specification (ECMA-262) defines the JavaScript programming language. Published annually by TC39 with new features, ECMAScript is the foundation for all JavaScript runtime environments including browsers and Node.js.
  url: https://ecma-international.org/publications-and-standards/standards/ecma-262/
links:
- type: IssueTracker
  url: https://github.com/whatwg/html/issues
- type: ContributionGuide
  url: https://github.com/whatwg/html/blob/main/.github/CONTRIBUTING.md
- type: DomainSecurity
  url: https://github.com/api-evangelist/web-standards/blob/main/security/web-standards-domain-security.yml
- type: Website
  url: https://www.w3.org/
- type: Website
  url: https://whatwg.org/
- type: Website
  url: https://ietf.org/
- type: Website
  url: https://ecma-international.org/
- type: Documentation
  url: https://www.w3.org/TR/
- type: APIReference
  url: https://developer.mozilla.org/en-US/docs/Web/API
- type: APIReference
  url: https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference
- type: Tools
  url: https://caniuse.com/
- type: Tools
  url: https://wpt.fyi/
- type: GitHubRepository
  url: https://github.com/web-platform-tests/wpt
- type: GitHubOrganization
  url: https://github.com/w3c
- type: GitHubOrganization
  url: https://github.com/whatwg
- type: GitHubOrganization
  url: https://github.com/tc39
- type: GitHubOrganization
  url: https://github.com/WICG
- type: JSONLD
  url: https://github.com/api-evangelist/web-standards/blob/main/json-ld/web-standards-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/web-standards/blob/main/vocabulary/web-standards-vocabulary.yml
provider_count: 19
providers:
- slug: ehrbase
  name: EHRbase
  description: EHRbase is an open source openEHR Clinical Data Repository (CDR) - a standards-based backend for storing, versioning and querying structured clinical data. It implements the official openEHR REST API (ITS-REST 1.0.2) against openEHR Refere…
  api_count: 1
  score_band: developing
  score_composite: 51.0
  shared: 2
- slug: agentic-ai-foundation
  name: Agentic AI Foundation
  description: 'The Agentic AI Foundation (AAIF) is a Linux Foundation project, announced 9 December 2025, that gives the core open standards and projects of the AI agent ecosystem a neutral home. It hosts five projects: Anthropic''s Model Context Protocol…'
  api_count: 1
  score_band: developing
  score_composite: 50.4
  shared: 2
- slug: typescript
  name: TypeScript
  description: TypeScript is a strongly typed programming language that builds on JavaScript, adding optional static type checking and other features. Developed and maintained by Microsoft, TypeScript compiles to plain JavaScript and is widely used for l…
  api_count: 3
  score_band: developing
  score_composite: 43.4
  shared: 2
- slug: canada-health-infoway
  name: Canada Health Infoway
  description: Canada Health Infoway is an independent, federally funded not-for-profit organization that leads the adoption of digital health and pan-Canadian interoperability across Canada's province- and territory-fragmented healthcare system. Infoway…
  api_count: 2
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: cabolabs
  name: CaboLabs
  description: CaboLabs Health Informatics is a Montevideo, Uruguay based health informatics company founded in 2012 by Pablo Pazos Gutierrez, specializing in clinical data standards and interoperability. It builds and licenses Atomik, a standardized ope…
  api_count: 2
  score_band: thin
  score_composite: 37.6
  shared: 2
- slug: aousd
  name: Alliance for OpenUSD
  description: The Alliance for OpenUSD (AOUSD) is a Linux Foundation project dedicated to promoting interoperability of 3D content through Universal Scene Description (OpenUSD). Founded by Pixar, Adobe, Apple, Autodesk, and NVIDIA, AOUSD standardizes 3D…
  api_count: 2
  score_band: thin
  score_composite: 29.8
  shared: 2
- slug: openehr
  name: openEHR
  description: 'openEHR is the open specification family for electronic health records, and the main structural alternative to HL7 FHIR. It is governed by two UK not-for-profit entities: the openEHR Foundation, a company limited by guarantee that holds th…'
  api_count: 13
  score_band: thin
  score_composite: 27.0
  shared: 2
- slug: meteor
  name: Meteor
  description: Meteor is a full-stack JavaScript platform for building modern web and mobile applications. It provides documentation, resources, and API references to help developers build and deploy applications with real-time capabilities.
  api_count: 1
  score_band: emerging
  score_composite: 25.1
  shared: 2
- slug: sails-co
  name: Sails Co
  description: Sails Co. is a full-service web, mobile, and cloud development studio (Y Combinator W15, Austin, Texas) founded by the creators of Sails.js. Sails.js is an open-source, API-driven MVC framework for Node.js — built on top of Express and Soc…
  api_count: 0
  score_band: emerging
  score_composite: 22.4
  shared: 2
- slug: paper
  name: Paper
  description: Paper (paper.design) is a modern, agent-native design tool built on HTML and CSS web standards — a connected canvas where teams design, share, and ship with AI agents. Instead of drawing abstract vector representations of interfaces, Paper…
  api_count: 0
  score_band: emerging
  score_composite: 21.8
  shared: 2
- slug: thymeleaf
  name: Thymeleaf
  description: Thymeleaf is a modern server-side Java template engine for both web and standalone environments, capable of processing HTML, XML, JavaScript, CSS, and plain text. Its primary goal is to bring elegant natural templates to development workfl…
  api_count: 3
  score_band: emerging
  score_composite: 21.2
  shared: 2
- slug: fhir
  name: Fast Healthcare Interoperability Resources
  description: FHIR (Fast Healthcare Interoperability Resources) is a platform specification developed by HL7 that defines a set of capabilities for use across the healthcare process, in all jurisdictions, and in many different clinical and administrativ…
  api_count: 1
  score_band: emerging
  score_composite: 19.9
  shared: 2
- slug: ogc
  name: Open Geospatial Consortium (OGC)
  description: The Open Geospatial Consortium is the standards body for geospatial interoperability — a member-funded consortium founded in 1994 and headquartered in the United States, with 362 member organizations plus 159 individual members across gove…
  api_count: 24
  score_band: emerging
  score_composite: 17.8
  shared: 2
- slug: angular
  name: Angular
  description: Angular is an open-source TypeScript-based web application framework maintained by Google and a community of contributors. It provides a comprehensive platform for building single-page applications with a component-based architecture, reac…
  api_count: 10
  score_band: emerging
  score_composite: 15.3
  shared: 2
- slug: ember
  name: Ember
  description: Ember.js is a productive, battle-tested JavaScript framework for building modern web applications. It includes Ember CLI for scaffolding and builds, a best-in-class router with async data loading, the Ember Data layer, a three-level testin…
  api_count: 0
  score_band: emerging
  score_composite: 11.6
  shared: 2
- slug: react
  name: React
  description: A JavaScript library for building user interfaces, maintained by Meta and the open source community.
  api_count: 2
  score_band: emerging
  score_composite: 11.0
  shared: 2
- slug: freshehr
  name: freshEHR
  description: freshEHR Clinical Informatics Ltd is a UK open-standards health and social care informatics consultancy, founded in 2014 by Dr Ian McNicoll and registered in England as company 08989238. It provides openEHR and HL7 FHIR expertise rather th…
  api_count: 0
  score_band: minimal
  score_composite: 6.6
  shared: 2
- slug: html
  name: HTML
  description: HTML (HyperText Markup Language) is the standard markup language for creating web pages and web applications. Maintained as a Living Standard by WHATWG and developed in close coordination with the W3C, HTML defines the structure and semant…
  api_count: 0
  score_band: minimal
  score_composite: 4.8
  shared: 2
- slug: yellowbrink
  name: YellowBrink
  description: YellowBrink is a Netherlands-based, vendor-neutral community platform for open health data, founded by Jan de Lange and Bouwe Koopal to connect healthcare professionals, vendors, researchers and policymakers working with open standards suc…
  api_count: 0
  score_band: minimal
  score_composite: 4.0
  shared: 2
---
