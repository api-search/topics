---
layout: topic
slug: high-tech
name: High Tech
kind: topic
description: High Tech indexes the APIs, data services, and reference artifacts that power the electronics, semiconductor, hardware, and IoT industries. The landscape covers electronic component data and distribution (Octopart / Nexar, Digi-Key, Mouser, Arrow Electronics, Avnet, Newark / element14), ECAD and PCB design data (SnapEDA, Ultra Librarian, Altium 365 via Nexar Design), hardware lifecycle and IoT device management (AWS IoT, Azure IoT Hub, Particle, Golioth), bill-of-materials and component-search workflows used across hardware product engineering, and the authoritative manufacturer data that anchors a component record (manufacturer part number, manufacturer, datasheet, lifecycle status, RoHS / REACH compliance, real-time inventory and pricing across distributors). This index captures the canonical providers, the shape of a component record as JSON Schema, a JSON-LD context aligning with schema.org Product / Offer / Organization, and the domain vocabulary used across the high-tech
  component supply chain.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/high-tech.png
tags:
- Arrow Electronics
- Availability
- Bill of Materials
- BOM
- Component Data
- Datasheets
- Digi-Key
- Distributor
- ECAD
- Electronic Components
- Electronics
- Footprints
- Hardware
- High Tech
- IoT
- Lifecycle
- Manufacturer Part Number
- Manufacturer
- Mouser
- MPN
- Nexar
- Octopart
- PCB Design
- Pricing
- RoHS
- Semiconductors
- SnapEDA
- Supply Chain
- Symbols
- Ultra Librarian
repo: https://github.com/api-evangelist/high-tech
api_count: 12
apis:
- name: Octopart / Nexar Supply API
  description: Nexar Supply (formerly Octopart API v4) is a GraphQL API that aggregates electronic component data from manufacturers and distributors worldwide. Returns parts, manufacturers, sellers, offers, datasheets, lifecycle status, compliance, and…
  url: https://nexar.com/api
- name: Digi-Key Product Information API
  description: Digi-Key's developer portal exposes a suite of OAuth 2.0 APIs including Product Information V4 (search by MPN, description, manufacturer, category), Quote, Ordering, Order Status, Order Management, MyLists, Supply Chain, Product Change Not…
  url: https://developer.digikey.com/products
- name: Mouser Electronics Search API
  description: Mouser Electronics exposes a REST Search API (SearchByPartNumber, SearchByKeyword, SearchByManufacturer), a Cart API, and an Order API. Authentication uses a per-application API key issued through Mouser's developer portal. Responses inclu…
  url: https://www.mouser.com/api-search/
- name: Arrow Electronics Pricing & Availability API
  description: Arrow Electronics provides a Pricing & Availability API and an Order API. Responses returned as JSON (XML available). Partners request an authorization key through Arrow's developer onboarding. A Quote API is marked "Coming soon".
  url: https://developers.arrow.com/api/
- name: Avnet Developer APIs
  description: Avnet provides distributor APIs for part search, pricing, availability, and order management, primarily for established partner accounts.
  url: https://www.avnet.com/
- name: Newark / element14 API
  description: Newark and element14 (Premier Farnell) expose component search and pricing data via partner APIs for hardware engineers and maker communities.
  url: https://www.newark.com/
- name: SnapEDA Symbols & Footprints API
  description: SnapEDA is a library of free CAD models for electronic components — schematic symbols, PCB footprints, and 3D models — keyed off manufacturer part numbers. Used by PCB design tools to auto-resolve CAD assets for a BoM.
  url: https://www.snapeda.com/home/
- name: Ultra Librarian ECAD API
  description: Ultra Librarian (an EMA Design Automation service) publishes symbols, footprints, and 3D models for over 16 million components, with integrations to major ECAD tools.
  url: https://www.ultralibrarian.com/
- name: Altium 365 / Nexar Design API
  description: Nexar Design exposes Altium 365 workspace data — components, nets, MCAD geometry, and positional data — via GraphQL for programmatic access to PCB designs.
  url: https://nexar.com/api
- name: AWS IoT Core
  description: AWS IoT Core provides device registry, MQTT message broker, device shadow, jobs, and rules engine for connected hardware at scale. Anchors the AWS IoT family (Device Management, Device Defender, Events, FleetWise, Greengrass, SiteWise, Twi…
  url: https://aws.amazon.com/iot-core/
- name: Microsoft Azure IoT Hub
  description: Azure IoT Hub provides bi-directional device-to-cloud and cloud-to-device messaging, device twins, direct methods, and device provisioning service (DPS).
  url: https://azure.microsoft.com/en-us/products/iot-hub/
- name: Particle Device Cloud API
  description: Particle provides a Device Cloud REST API plus webhooks for managing cellular and Wi-Fi connected hardware, firmware OTA, and variable / function / event APIs against devices.
  url: https://docs.particle.io/reference/cloud-apis/api/
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/high-tech/blob/main/security/high-tech-domain-security.yml
- type: ComponentSchema
  url: https://raw.githubusercontent.com/api-evangelist/high-tech/refs/heads/main/json-schema/high-tech-component-schema.json
- type: ComponentStructure
  url: https://raw.githubusercontent.com/api-evangelist/high-tech/refs/heads/main/json-structure/high-tech-component-structure.json
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/high-tech/refs/heads/main/json-ld/high-tech-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/high-tech/refs/heads/main/vocabulary/high-tech-vocabulary.yml
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/high-tech/refs/heads/main/examples/
provider_count: 301
providers:
- slug: snapmagic
  name: SnapMagic
  description: SnapMagic (formerly SnapEDA) is a Silicon Valley company building an AI operating system for electronics design, used by more than two million hardware engineers worldwide. Its SnapMagic Search product provides free, ready-to-use PCB footp…
  api_count: 1
  score_band: emerging
  score_composite: 25.2
  shared: 6
- slug: cofactr
  name: Cofactr
  description: Cofactr provides electronics supply chain infrastructure for hardware manufacturers — component intelligence, procurement execution, and ITAR-registered warehousing and kitting — so teams avoid shortages and production delays with full tra…
  api_count: 1
  score_band: developing
  score_composite: 45.1
  shared: 4
- slug: avnet
  name: Avnet
  description: 'Avnet is a global technology distributor and solutions provider that delivers electronic components, embedded solutions, and design and supply chain services to industrial and commercial customers. It publishes two API surfaces: the Avnet…'
  api_count: 15
  score_band: strong
  score_composite: 55.1
  shared: 3
- slug: renesas
  name: Renesas
  description: 'Renesas Electronics Corporation (TYO: 6723) is a global semiconductor manufacturer producing microcontrollers and microprocessors (RA, RX, RL78, RH850, RZ, Synergy families), analog, power, sensor, timing, connectivity, and memory products…'
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 3
- slug: analog-devices
  name: Analog Devices
  description: Analog Devices (ADI) is a global semiconductor company designing high-performance analog, mixed-signal, and digital signal processing integrated circuits for industrial, communications, automotive, and consumer markets. ADI provides develo…
  api_count: 4
  score_band: developing
  score_composite: 42.5
  shared: 3
- slug: texas-instruments
  name: Texas Instruments
  description: Texas Instruments is an American technology company that designs and manufactures semiconductors and various integrated circuits for industrial, automotive, personal electronics, communications equipment, and enterprise systems markets. TI…
  api_count: 2
  score_band: thin
  score_composite: 38.9
  shared: 3
- slug: atmosic
  name: Atmosic
  description: Atmosic Technologies is a fabless semiconductor company headquartered in San Jose, California that designs ultra-low-power wireless system-on-chips for the Internet of Things, with the stated goal of radically reducing — and in some deploy…
  api_count: 0
  score_band: thin
  score_composite: 36.4
  shared: 3
- slug: cypress-semiconductor
  name: Cypress Semiconductor
  description: Cypress Semiconductor was a US-based semiconductor company known for its PSoC programmable system-on-chip microcontrollers, WICED Wi-Fi and Bluetooth connectivity stacks, NOR Flash memory, CapSense capacitive touch sensing, and Traveo auto…
  api_count: 6
  score_band: thin
  score_composite: 32.6
  shared: 3
- slug: fabric8labs
  name: Fabric8Labs
  description: Fabric8Labs is a San Diego, California based advanced-manufacturing company founded in 2015 that invented and commercialized Electrochemical Additive Manufacturing (ECAM), a room-temperature metal 3D printing process that uses a patented m…
  api_count: 2
  score_band: emerging
  score_composite: 23.1
  shared: 3
- slug: reed-semiconductor
  name: Reed Semiconductor
  description: Reed Semiconductor Corp. is a fabless power-management semiconductor company founded in 2019 and headquartered in Rhode Island, USA, with offices in Taipei, Shenzhen and Bengaluru. The name stands for Robust, Efficient, Eco-friendly and De…
  api_count: 2
  score_band: emerging
  score_composite: 19.0
  shared: 3
- slug: alif-semiconductor
  name: Alif Semiconductor
  description: Alif Semiconductor is a fabless semiconductor company headquartered in Pleasanton, California with engineering operations in Grenoble, France. It designs secure, AI/ML-enabled 32-bit microcontrollers and fusion processors for edge computin…
  api_count: 0
  score_band: emerging
  score_composite: 18.2
  shared: 3
- slug: empower-semiconductor
  name: Empower Semiconductor
  description: Empower Semiconductor is a fabless power-semiconductor company founded in 2014 and headquartered in San Jose, California, with an R&D office in Munich. It designs integrated voltage regulators (IVRs), silicon capacitors (ECAP) and vertical…
  api_count: 0
  score_band: emerging
  score_composite: 11.3
  shared: 3
- slug: pragmatic
  name: Pragmatic
  description: Pragmatic Semiconductor Limited is a UK semiconductor manufacturer that designs and produces FlexICs - ultra-thin, physically flexible integrated circuits built on thin-film transistor (TFT) technology rather than conventional crystalline…
  api_count: 1
  score_band: minimal
  score_composite: 10.9
  shared: 3
- slug: skyworks-solutions
  name: Skyworks Solutions
  description: Skyworks Solutions, Inc. is an American semiconductor company headquartered in Irvine, California that designs, develops, and markets proprietary semiconductor products for wireless communications, automotive, broadband, connected home, in…
  api_count: 0
  score_band: minimal
  score_composite: 10.3
  shared: 3
- slug: celus
  name: Celus
  description: CELUS GmbH is a Munich-based electronics design automation company building an AI-driven, cloud design platform that automates the early stages of printed circuit board (PCB) engineering. The CELUS Design Platform turns high-level product…
  api_count: 0
  score_band: minimal
  score_composite: 10.2
  shared: 3
- slug: carnot-fleet
  name: Carnot Fleet
  description: Carnot Fleet (Carnotfleet) is a Seoul-based cold-chain technology company that converts non-refrigerated vehicles into temperature-controlled units in under 30 minutes using modular insulation panels and proprietary solid-state thermoelect…
  api_count: 0
  score_band: minimal
  score_composite: 9.6
  shared: 3
- slug: accusilicon
  name: Accusilicon
  description: Accusilicon (Guangzhou Ruixin Microelectronics Co., Ltd. / 广州睿芯微电子有限公司) is a fabless mixed-signal semiconductor company founded in July 2014 and headquartered in the Huangpu district of Guangzhou, China, with additional sites in Xi'an and…
  api_count: 0
  score_band: minimal
  score_composite: 7.0
  shared: 3
- slug: ossia
  name: Ossia
  description: Ossia, Inc. is a Redmond, Washington wireless power technology company founded by physicist Hatem Zeine (incorporated as Omnilectric in 2008, operating as Ossia from 2013) and the inventor of Cota Real Wireless Power — a patented RF smart-…
  api_count: 0
  score_band: minimal
  score_composite: 6.7
  shared: 3
- slug: atmi-sales
  name: ATMI Sales
  description: ATMI Sales (Advanced Technical Marketing Inc.) is a manufacturers' representative and technical sales firm serving the electronics and semiconductor industry across the Pacific Northwest and Western Canada. The company connects customers w…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 3
- slug: atom-semiconductor
  name: Atom Semiconductor
  description: Atom Semiconductor (Atom Semiconductor Technologies Limited) is a fabless mixed-signal chip design company founded in Hong Kong in October 2020, with offices in Shenzhen and Shanghai. It designs high-performance analog and mixed-signal sem…
  api_count: 0
  score_band: minimal
  score_composite: 6.4
  shared: 3
- slug: aichengtechnology
  name: Aicheng Technology
  description: 'Aicheng Technology (Suzhou Innovation Ceramic Technology Co., Ltd., "SiCT" — 苏州艾成科技技术有限公司) is a Suzhou, China advanced-ceramics manufacturer founded in July 2021 that makes power-electronics substrates: AlN and Si3N4 ceramic substrates, DC…'
  api_count: 0
  score_band: minimal
  score_composite: 6.0
  shared: 3
- slug: mk-semi
  name: Mauna Kea Semiconductors
  description: Mauna Kea Semiconductors (mk-semi.com) is a Silicon Valley-based fabless semiconductor company founded by industry veterans to develop what it describes as the world's lowest-power Ultra-Wideband (UWB) solution for high precision location…
  api_count: 0
  score_band: minimal
  score_composite: 6.0
  shared: 3
- slug: aspinity
  name: Aspinity
  description: Aspinity is a Pittsburgh, Pennsylvania semiconductor company that develops analog machine learning (AnalogML) technology combining ultra-low-power analog signal processing with machine learning for always-on, battery-operated edge AI event…
  api_count: 0
  score_band: minimal
  score_composite: 5.5
  shared: 3
- slug: avago-technologies
  name: Avago Technologies
  description: Avago Technologies Limited was the Singapore-headquartered semiconductor company spun out of Agilent Technologies' semiconductor products group in 2005 that acquired Broadcom Corporation for $37 billion on February 1, 2016 and renamed itse…
  api_count: 0
  score_band: minimal
  score_composite: 5.4
  shared: 3
- slug: cypress
  name: Cypress
  description: Cypress Semiconductor Corporation was a San Jose, California semiconductor company founded in 1982, and an early Mayfield venture investment. It designed and manufactured mixed-signal, embedded, and connectivity silicon — most notably the…
  api_count: 0
  score_band: minimal
  score_composite: 5.3
  shared: 3
- slug: upverter
  name: Upverter
  description: Upverter is a browser-based, collaborative electronic design automation (EDA) platform for schematic capture and PCB layout, founded in Toronto in 2010 (Y Combinator W11) and acquired by Altium in 2017. Surfaced as a Version One Ventures p…
  api_count: 0
  score_band: minimal
  score_composite: 5.3
  shared: 3
- slug: acela-micro
  name: Acela Micro
  description: Acela Micro (Suzhou Acela Microelectronics, founded 2013) is a Chinese fabless semiconductor company designing high-end signal chain integrated circuits — ultra-high-speed and high-precision analog-to-digital converters (ADC), digital-to-a…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: weft
  name: Weft
  description: Weft was a Burlington, Vermont based supply-chain logistics startup, founded by Marc Held around 2013-2014, that combined hardware sensors and software to track the shipping of physical goods worldwide in real time. It raised a seed round…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: eigencomm
  name: eigencomm
  description: Shanghai Eigencomm Technology Co., Ltd. is a fabless semiconductor company founded in 2017 and headquartered in the Zhangjiang district of Shanghai, China, dedicated to the research, design, and sale of cellular Internet of Things (IoT) co…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: airtouch
  name: Airtouch
  description: AirTouch (Shanghai) Intelligent Technology Co., Ltd. (隔空科技) is a Shanghai-based fabless semiconductor company founded in November 2017 that designs microwave and millimeter-wave radar sensor chips — 5.8 GHz, 10.525 GHz, 24 GHz, 60 GHz and…
  api_count: 0
  score_band: minimal
  score_composite: 4.6
  shared: 3
---
