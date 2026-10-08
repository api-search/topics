---
layout: topic
slug: ble
name: BLE
kind: topic
description: Bluetooth Low Energy (BLE), also known as Bluetooth Smart, is a wireless personal area network technology designed and marketed by the Bluetooth Special Interest Group (Bluetooth SIG). Aimed at IoT and embedded applications, BLE provides reduced power consumption while maintaining similar communication range to classic Bluetooth. The specification is managed by the Bluetooth SIG and covers the full protocol stack including the Generic Attribute Profile (GATT), Generic Access Profile (GAP), and the various service and characteristic specifications used for device interoperability.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/ble.png
tags:
- BLE
- Bluetooth
- Embedded
- IoT
- Protocol
- Standards
- Wireless
repo: https://github.com/api-evangelist/ble
api_count: 3
apis:
- name: Bluetooth Core Specification
  description: The Bluetooth Core Specification defines the complete Bluetooth wireless communication protocol stack including BLE (LE) and Classic Bluetooth. The current stable version is Bluetooth 6.0. The specification covers the Physical Layer, Link…
  url: https://www.bluetooth.com/specifications/specs/core60/
- name: GATT and Assigned Numbers
  description: The Generic Attribute Profile (GATT) defines the framework for data transfer between Bluetooth LE devices. The Bluetooth SIG maintains assigned numbers for services, characteristics, and descriptors that enable interoperable implementation…
  url: https://www.bluetooth.com/specifications/assigned-numbers/
- name: Bluetooth Mesh Networking
  description: Bluetooth Mesh enables many-to-many device communications and is particularly suited for IoT applications that require large-scale device networks, including building automation, industrial IoT, and smart city infrastructure.
  url: https://www.bluetooth.com/specifications/specs/mesh-profile/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/ble/blob/main/security/ble-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/ble/blob/main/security/ble-domain-security.yml
- type: Website
  url: https://www.bluetooth.com/
- type: Documentation
  url: https://www.bluetooth.com/develop-with-bluetooth/
- type: Specification
  url: https://www.bluetooth.com/specifications/specs/
- type: Training
  url: https://www.bluetooth.com/develop-with-bluetooth/training/
- type: Community
  url: https://www.bluetooth.com/develop-with-bluetooth/
- type: SDKs
  url: https://www.bluetooth.com/develop-with-bluetooth/developer-resources/
- type: Conformance
  url: https://www.bluetooth.com/develop-with-bluetooth/qualification-listing/
- type: SpectralRules
  url: https://github.com/api-evangelist/ble/blob/main/rules/ble-spectral-rules.yml
- type: Vocabulary
  url: https://github.com/api-evangelist/ble/blob/main/vocabulary/ble-vocabulary.yaml
provider_count: 56
providers:
- slug: silabs
  name: Silicon Labs
  description: Silicon Labs (Silabs) is a fabless semiconductor company headquartered in Austin, Texas that designs silicon, software, and solutions for a more connected, IoT world. Its portfolio includes wireless connectivity SoCs and modules for Blueto…
  api_count: 0
  score_band: emerging
  score_composite: 16.9
  shared: 4
- slug: particle
  name: Particle
  description: Particle is an integrated IoT Platform-as-a-Service that provides cellular, Wi-Fi, and Bluetooth hardware modules alongside a comprehensive cloud platform for building and managing connected devices at scale. The Particle Device Cloud expo…
  api_count: 2
  score_band: strong
  score_composite: 62.2
  shared: 3
- slug: allegion
  name: Allegion
  description: Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Porta…
  api_count: 2
  score_band: strong
  score_composite: 59.8
  shared: 3
- slug: bouffalolab
  name: Bouffalo Lab
  description: Bouffalo Lab (博流智能) is a fabless chip design company founded in 2016 and headquartered in Nanjing, China, focused on ultra-low-power AIoT (AI + IoT) and edge-computing system chips. Its product line centers on RISC-V based microcontrollers…
  api_count: 0
  score_band: minimal
  score_composite: 3.7
  shared: 3
- slug: cypress
  name: Cypress
  description: Cypress Semiconductor Corporation was a San Jose, California semiconductor company founded in 1982, and an early Mayfield venture investment. It designed and manufactured mixed-signal, embedded, and connectivity silicon — most notably the…
  api_count: 0
  score_band: minimal
  score_composite: 2.8
  shared: 3
- slug: losant
  name: Losant
  description: Losant is an Enterprise IoT Platform that lets product teams build connected experiences, manage fleets of devices, orchestrate edge and embedded compute, and visualize and act on IoT data. The platform exposes a comprehensive REST API (th…
  api_count: 6
  score_band: exemplar
  score_composite: 83.1
  shared: 2
- slug: hubble-network
  name: Hubble Network
  description: Hubble Network is a Seattle-based IoT connectivity company, founded in 2021 by Alex Haro (Life360) and Ben Wild (Amazon Sidewalk), building a dual-stack global network that any standard Bluetooth Low Energy 5.0+ chip can reach with no mode…
  api_count: 2
  score_band: exemplar
  score_composite: 70.4
  shared: 2
- slug: kontaktio
  name: Kontakt.io
  description: Kontakt.io is an AI-powered real-time location system (RTLS) and IoT platform for healthcare operations, founded in 2013 with offices in New York and Krakow. Its Kio Cloud platform combines BLE/UWB tags, badges, gateways and sensors with s…
  api_count: 8
  score_band: strong
  score_composite: 61.4
  shared: 2
- slug: viam
  name: Viam
  description: Viam is a robotics and edge AI platform founded in 2020 by Eliot Horowitz (MongoDB co-founder and former CTO). It pairs viam-server — a gRPC-based runtime that runs on Linux single-board computers (RDK) and ESP32-class microcontrollers (mi…
  api_count: 13
  score_band: strong
  score_composite: 60.2
  shared: 2
- slug: verizon
  name: Verizon
  description: Verizon is a leading telecommunications company providing wireless, wireline, broadband, and global enterprise services. Verizon offers developer APIs for IoT device management via ThingSpace, 5G edge computing, TM Forum service management…
  api_count: 18
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: reliance-jio
  name: Reliance Jio
  description: Reliance Jio Infocomm, the telecom arm of Jio Platforms Limited and Reliance Industries, is India's largest mobile network operator, serving roughly half a billion subscribers on an all-IP 4G/5G network from its home market of India, along…
  api_count: 6
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: etsi
  name: ETSI
  description: ETSI, the European Telecommunications Standards Institute, is a not-for-profit standards development organisation headquartered in Sophia Antipolis, France, and one of only three bodies officially recognised by the European Union as a Euro…
  api_count: 24
  score_band: developing
  score_composite: 50.2
  shared: 2
- slug: 1nce
  name: 1NCE
  description: 1NCE is a Cologne-headquartered global IoT connectivity provider best known for the IoT Lifetime Flat — a single one-time fee that bundles a multi-network SIM with 500 MB of data and 250 SMS over a 10-year subscription. The 1NCE Management…
  api_count: 8
  score_band: developing
  score_composite: 48.9
  shared: 2
- slug: golioth
  name: Golioth
  description: Golioth is an IoT device management cloud and firmware SDK for connected hardware. The platform pairs an open-source Firmware SDK (Zephyr RTOS, nRF Connect SDK, ESP-IDF, ModusToolbox, Linux) with a REST Management API at api.golioth.io, a…
  api_count: 1
  score_band: developing
  score_composite: 48.0
  shared: 2
- slug: telia
  name: Telia Company
  description: Telia Company is the Nordic and Baltic telecommunications group headquartered in Solna, Sweden, operating mobile and fixed networks in Sweden, Finland, Norway, Denmark, Lithuania, Latvia and Estonia, plus a global carrier and IoT business.…
  api_count: 1
  score_band: developing
  score_composite: 46.8
  shared: 2
- slug: celona
  name: Celona
  description: Celona provides enterprise private 5G and LTE cellular networking that connects where Wi-Fi cannot reach. The platform combines Celona Edge appliances, indoor and outdoor 5G Access Points, and the cloud-delivered Celona Orchestrator (CSO)…
  api_count: 1
  score_band: developing
  score_composite: 46.2
  shared: 2
- slug: swift-navigation
  name: Swift Navigation
  description: Swift Navigation builds precise positioning technology for mass-market applications — automotive ADAS and autonomy, mobile handsets, robotics, drones, micromobility, fleet and asset tracking, GIS and construction. Its flagship service, Sky…
  api_count: 4
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: memfault
  name: Memfault
  description: Memfault is a device observability and reliability platform for connected products built on MCUs, embedded Linux, and Android. The Memfault Cloud ingests device data (coredumps, logs, metrics, reboots) and provides issue grouping, alerting…
  api_count: 1
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: cesanta
  name: Cesanta
  description: Cesanta is an embedded software and IoT company, established in 2013 to develop and support the Mongoose embedded web server and networking library (HTTP, WebSocket, MQTT, CoAP, TCP/IP) that ships in over 100 million devices from vendors s…
  api_count: 1
  score_band: developing
  score_composite: 39.6
  shared: 2
- slug: elisa
  name: ELISA
  description: ELISA (Enabling Linux in Safety Applications) is a Linux Foundation collaborative project that builds the shared tools, processes and evidence needed to use Linux in safety-critical systems. Its working groups and special interest groups s…
  api_count: 1
  score_band: thin
  score_composite: 37.8
  shared: 2
- slug: zephyr
  name: Zephyr Project
  description: The Zephyr Project is a Linux Foundation project that delivers a small, scalable, secure, and open-source real-time operating system (RTOS) for resource-constrained embedded devices. Zephyr supports 1000+ boards across ARM Cortex, RISC-V,…
  api_count: 3
  score_band: thin
  score_composite: 37.0
  shared: 2
- slug: atmosic
  name: Atmosic
  description: Atmosic Technologies is a fabless semiconductor company headquartered in San Jose, California that designs ultra-low-power wireless system-on-chips for the Internet of Things, with the stated goal of radically reducing — and in some deploy…
  api_count: 0
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: estimote
  name: Estimote
  description: Estimote is a proximity and indoor-location company founded in 2012 that designs Bluetooth Low Energy, Ultra-Wideband (UWB) and LTE-M/NB-IoT beacons together with the Estimote Cloud platform for managing them at fleet scale. The Estimote C…
  api_count: 1
  score_band: thin
  score_composite: 34.2
  shared: 2
- slug: got-its
  name: Reelables
  description: Reelables provides Track Anywhere smart labels and a RESTful platform API for global supply-chain and logistics visibility. The paper-thin Bluetooth and cellular smart labels are printed on off-the-shelf barcode printers, activated, attach…
  api_count: 2
  score_band: thin
  score_composite: 33.8
  shared: 2
- slug: flic
  name: Flic
  description: Flic (Shortcut Labs) makes wireless smart buttons and dials — the Flic Button, Flic Twist, Flic Duo, and the Flic Hub — that let people control smart-home devices, lights, music, and cloud services with a single press. Its developer surfac…
  api_count: 0
  score_band: thin
  score_composite: 33.6
  shared: 2
- slug: toit
  name: Toit
  description: Toit builds an open-source, high-level programming language and runtime for microcontrollers, targeting the ESP32 family, together with fleet-management tooling for deploying, monitoring and hot-reloading software across large fleets of co…
  api_count: 0
  score_band: thin
  score_composite: 32.9
  shared: 2
- slug: cypress-semiconductor
  name: Cypress Semiconductor
  description: Cypress Semiconductor was a US-based semiconductor company known for its PSoC programmable system-on-chip microcontrollers, WICED Wi-Fi and Bluetooth connectivity stacks, NOR Flash memory, CapSense capacitive touch sensing, and Traveo auto…
  api_count: 6
  score_band: thin
  score_composite: 30.7
  shared: 2
- slug: internet-engineering-task-force
  name: Internet Engineering Task Force
  description: The Internet Engineering Task Force (IETF) is an open, global community of network designers, engineers, researchers, and operators that develops and promotes voluntary technical standards to ensure the smooth operation and evolution of th…
  api_count: 6
  score_band: thin
  score_composite: 28.4
  shared: 2
- slug: cisco-meraki
  name: Cisco Meraki
  description: Cisco Meraki is a cloud-managed networking platform that provides wireless access points, switches, security appliances, cameras, sensors, and mobile device management from a single dashboard. The Meraki Dashboard API is a RESTful interfac…
  api_count: 6
  score_band: thin
  score_composite: 27.8
  shared: 2
- slug: blynk
  name: Blynk
  description: Blynk is a low-code / no-code IoT software platform that helps companies prototype, deploy, and remotely manage connected devices and applications across consumer and commercial markets. The platform combines four components — Blynk.Consol…
  api_count: 3
  score_band: thin
  score_composite: 27.4
  shared: 2
---
