---
layout: topic
slug: scorm
name: SCORM
kind: topic
description: SCORM (Sharable Content Object Reference Model) is a set of technical standards for e-learning software products. Originally developed by the Advanced Distributed Learning (ADL) Initiative, SCORM defines how online learning content and Learning Management Systems (LMS) communicate with each other, enabling interoperability between authoring tools, content packages, and LMS platforms. Key versions include SCORM 1.2 and SCORM 2004, with xAPI (Tin Can) as a modern successor.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/scorm.png
tags:
- E-Learning
- LMS
- Standards
- Education
- Interoperability
repo: https://github.com/api-evangelist/scorm
api_count: 3
apis:
- name: SCORM 1.2 Runtime API
  description: The SCORM 1.2 Run-Time Environment defines communication between e-learning content and an LMS via a JavaScript API. The API Adapter is an ECMAScript object named "API" accessible through the DOM. It enables content to initialize sessions,…
  url: https://scorm.com/scorm-explained/technical-scorm/scorm-12-overview-for-developers/
- name: SCORM 2004 Runtime API
  description: The SCORM 2004 Run-Time Environment extends SCORM 1.2 with improved sequencing and navigation capabilities. The API Adapter is an ECMAScript object named "API_1484_11". It supports 8 core API functions for session management, data model ac…
  url: https://scorm.com/scorm-explained/technical-scorm/scorm-2004-overview-for-developers/
- name: xAPI (Experience API / Tin Can)
  description: xAPI (Experience API), also known as Tin Can API, is the modern successor to SCORM developed by ADL. It uses a Learning Record Store (LRS) and defines learning statements in a subject-verb-object format, enabling tracking of a much wider r…
  url: https://xapi.com/
links:
- type: Website
  url: https://scorm.com
- type: DomainSecurity
  url: https://github.com/api-evangelist/scorm/blob/main/security/scorm-domain-security.yml
- type: Blog
  url: https://scorm.com/blog/
provider_count: 86
providers:
- slug: go1
  name: Go1
  description: Go1 is an AI-powered corporate learning and development (L&D) platform that consolidates employee training into a single subscription. Its content library aggregates courses from 250+ providers across 40+ languages, layered with curation,…
  api_count: 1
  score_band: strong
  score_composite: 63.5
  shared: 3
- slug: thinkific
  name: Thinkific
  description: Thinkific is an online course creation and delivery platform that enables creators and businesses to build, market, and sell courses, communities, and digital products. The Thinkific Admin REST API provides programmatic access to site data…
  api_count: 1
  score_band: developing
  score_composite: 51.5
  shared: 3
- slug: adobe-captivate
  name: Adobe Captivate
  description: Adobe Captivate is an eLearning authoring tool used to create responsive eLearning content, software demonstrations, and interactive training modules.
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 3
- slug: epignosis-talentlms-efront-talentcards
  name: Epignosis (TalentLMS, eFront, TalentCards)
  description: 'Epignosis is a learning-technology company serving more than 70,000 organizations worldwide with a family of cloud training products: TalentLMS (an all-in-one LMS for growing businesses), eFront (a flexible enterprise LMS), TalentCards (mo…'
  api_count: 1
  score_band: developing
  score_composite: 47.7
  shared: 3
- slug: talentlms
  name: TalentLMS
  description: TalentLMS is a cloud-based learning management system (LMS) with a REST API for managing users, courses, categories, branches, groups, and enrollments, as well as accessing completion and assessment report data. The API supports over 50 en…
  api_count: 1
  score_band: developing
  score_composite: 42.3
  shared: 3
- slug: thought-industries
  name: Thought Industries
  description: Thought Industries is a B2B learning platform (LMS/LXP) providing REST and GraphQL APIs for programmatic access to courses, users, enrollments, content management, and reporting. Their developer portal enables integration of learning exper…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 3
- slug: learnworlds
  name: LearnWorlds
  description: LearnWorlds is an online course and learning management (LMS) platform that lets creators, trainers, and businesses build, sell, and run branded online schools. Its REST API (v2) is served per-school from https://{school}.learnworlds.com/a…
  api_count: 1
  score_band: thin
  score_composite: 33.8
  shared: 3
- slug: uteach-inc
  name: Uteach
  description: Uteach is an all-in-one online teaching platform and LMS that lets educators, coaches, and businesses create a branded website and sell online courses, coaching sessions, live lessons, quizzes with certificates, digital products, and commu…
  api_count: 0
  score_band: thin
  score_composite: 33.7
  shared: 3
- slug: class-technologies
  name: Class Technologies
  description: Class Technologies Inc. builds Class, a virtual instructor-led learning platform that layers a full classroom experience on top of Zoom and Microsoft Teams, plus the web-based Class Collaborate. It gives instructors breakout rooms, whitebo…
  api_count: 1
  score_band: thin
  score_composite: 32.7
  shared: 3
- slug: edools
  name: Edools
  description: Edools is a Brazilian e-learning and digital-education platform for creating, hosting, and selling online courses, learning paths, and training programs under a white-label school (LMS) with a Netflix-style members area, video hosting, and…
  api_count: 1
  score_band: thin
  score_composite: 29.4
  shared: 3
- slug: coursebase
  name: Coursebase
  description: Coursebase is an AI-powered corporate Learning Management System (LMS) used by over 1,000 organizations to create, deliver, and manage employee training across online, in-person, and blended formats. The platform offers a library of 1,000+…
  api_count: 0
  score_band: emerging
  score_composite: 12.8
  shared: 3
- slug: yellowbrink
  name: YellowBrink
  description: YellowBrink is a Netherlands-based, vendor-neutral community platform for open health data, founded by Jan de Lange and Bouwe Koopal to connect healthcare professionals, vendors, researchers and policymakers working with open standards suc…
  api_count: 0
  score_band: minimal
  score_composite: 4.0
  shared: 3
- slug: canvas
  name: Canvas
  description: Canvas is Instructure's open-source learning management system (LMS) used by K-12, higher education, and corporate training organizations to deliver courses, assessments, and learner communication. Canvas exposes a comprehensive REST API a…
  api_count: 146
  score_band: exemplar
  score_composite: 68.2
  shared: 2
- slug: canvas-lms
  name: Canvas LMS
  description: Canvas is the open, AGPLv3-licensed learning management system created and maintained by Instructure, Inc. and used by more than 30 million students, teachers, and administrators across higher education, K-12, business, and government. Can…
  api_count: 1
  score_band: exemplar
  score_composite: 66.9
  shared: 2
- slug: drillster
  name: Drillster
  description: Drillster is a Utrecht-based adaptive learning platform for corporate and vocational training, built on repetition-based drills that schedule practice at the moment a learner is about to forget. Customers in aviation, healthcare, financial…
  api_count: 1
  score_band: developing
  score_composite: 52.4
  shared: 2
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
- slug: teachable
  name: Teachable
  description: Teachable is an online course and coaching platform that empowers creators to build and sell educational content without technical expertise. The Teachable REST API provides programmatic access to school management capabilities including c…
  api_count: 2
  score_band: developing
  score_composite: 49.7
  shared: 2
- slug: cloud-academy
  name: Cloud Academy
  description: Cloud Academy is a hands-on technology skills training platform, now operating as the QA Learning Platform (cloudacademy.com redirects to platform.qa.com). It combines self-paced course content with hands-on labs, learning paths, quizzes,…
  api_count: 1
  score_band: developing
  score_composite: 46.7
  shared: 2
- slug: ispring
  name: iSpring Learn
  description: iSpring Learn is an eLearning platform and LMS that provides a REST API for managing courses, users, groups, departments, enrollments, learning paths, and accessing detailed learner progress reports. The API supports content management, as…
  api_count: 1
  score_band: developing
  score_composite: 46.4
  shared: 2
- slug: clever
  name: Clever
  description: Clever is a K-12 EdTech identity platform that provides a unified single sign-on portal and roster synchronization service used by over 111,000 US schools, including 95 of the largest 100 districts. The Clever REST API enables application…
  api_count: 2
  score_band: developing
  score_composite: 44.7
  shared: 2
- slug: coorpacademy
  name: Coorpacademy
  description: Coorpacademy is a Swiss-French corporate digital-learning platform, founded in 2013 and acquired by Australian edtech Go1 in April 2022, now marketed as "Coorpacademy by Go1". It sells a B2B SaaS learning experience platform built on inver…
  api_count: 14
  score_band: developing
  score_composite: 42.9
  shared: 2
- slug: renaissance
  name: Renaissance
  description: Renaissance Learning, Inc. is a pre-K–12 education technology company whose assessment, practice and analytics products — Star Assessments, Accelerated Reader, Freckle, myON, Lalilo, Flocabulary, Nearpod, FastBridge, DnA, eduCLIMBER, eScho…
  api_count: 5
  score_band: developing
  score_composite: 41.9
  shared: 2
- slug: instructure
  name: Instructure
  description: Instructure is an EdTech company best known for Canvas LMS, a widely adopted learning management system used by thousands of educational institutions and organizations worldwide. The platform provides a comprehensive REST API and GraphQL A…
  api_count: 1
  score_band: developing
  score_composite: 40.9
  shared: 2
- slug: itslearning
  name: itslearning
  description: itslearning is a Norwegian learning management system (LMS) founded in 1999 and headquartered in Bergen, Norway, now part of the Sanoma Learning group. Its cloud platform serves primary, secondary, vocational, higher education, lifelong-le…
  api_count: 4
  score_band: developing
  score_composite: 40.6
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
- slug: brightspace
  name: D2L Brightspace
  description: D2L Brightspace is an enterprise learning management system (LMS) used by higher education, K-12, and corporate organizations. Its public REST API is the Valence Learning Framework API, exposed under https://{host}/d2l/api/ and split into…
  api_count: 1
  score_band: thin
  score_composite: 36.0
  shared: 2
- slug: edlink
  name: Edlink
  description: Edlink is an education-integration platform offering a unified API for rostering and school data across SIS and LMS systems. The Edlink Graph API exposes normalized districts, schools, classes, sections, courses, people, and enrollments fr…
  api_count: 1
  score_band: thin
  score_composite: 34.6
  shared: 2
- slug: santeacademie
  name: Santé Académie
  description: Santé Académie is a French continuing-professional-development (DPC) training provider for healthcare professionals — physicians, nurses, pharmacists, pharmacy technicians, nursing assistants and health-facility training managers — deliver…
  api_count: 4
  score_band: thin
  score_composite: 34.3
  shared: 2
---
