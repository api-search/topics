---
layout: topic
slug: rfid
name: RFID
kind: topic
description: Radio-Frequency Identification (RFID) is an automatic identification technology that uses radio waves to read and capture information stored on a tag attached to an object. RFID powers supply chain visibility, inventory management, asset tracking, access control, and contactless payments. The RFID ecosystem includes hardware vendors (Zebra, Impinj, Alien Technology), software platforms (ClearStream, TagMatiks, Jetstream), and open standards (GS1 EPCIS, EPC Tag Data Standard, ISO 18000 series).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/rfid.png
tags:
- RFID
- IoT
- Supply Chain
- Inventory Management
- Asset Tracking
- GS1
- EPCIS
repo: https://github.com/api-evangelist/rfid
api_count: 7
apis:
- name: Zebra Data Services for RFID
  description: Zebra Technologies provides cloud-based REST APIs for managing RFID readers, collecting tag data, and integrating RFID intelligence into enterprise applications. Cloud Connect for RFID enables remote reader management and data collection v…
  url: https://developer.zebra.com/data-services-rfid-developer-guide
- name: ClearStream RFID REST API
  description: ClearStream provides a RESTful API for RFID and Bluetooth Beacon technology, giving developers full control of RFID readers and gateways to integrate tag data into existing applications and websites.
  url: https://www.clearstreamrfid.com/software/integrate/api/
- name: Impinj ItemSense RAIN RFID API
  description: Impinj provides APIs for RAIN RFID reader management and item location data, enabling real-time item-level inventory visibility in retail, healthcare, and manufacturing environments.
  url: https://developer.impinj.com/
- name: GS1 EPCIS API
  description: The Electronic Product Code Information Services (EPCIS) is GS1's standard for sharing supply chain visibility data. EPCIS 2.0 supports REST/HTTP and JSON-LD for capturing and querying RFID events including Object, Aggregation, Transaction…
  url: https://www.gs1.org/standards/epcis
- name: RFID Discovery API
  description: EPCIS service discovery and capabilities
  url: https://developer.zebra.com/data-services-rfid-developer-guide
- name: RFID Events API
  description: Capture and query EPCIS events (Object, Aggregation, Transaction, Transformation, Association)
  url: https://developer.zebra.com/data-services-rfid-developer-guide
- name: RFID Queries API
  description: Named query management for subscription-based event filtering
  url: https://developer.zebra.com/data-services-rfid-developer-guide
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/rfid/blob/main/agentic-access/rfid-agentic-access.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/rfid/blob/main/security/rfid-domain-security.yml
- type: Authentication
  url: https://github.com/api-evangelist/rfid/blob/main/authentication/rfid-authentication.yml
- type: Website
  url: https://developer.zebra.com/products/rfid
- type: Website
  url: https://www.clearstreamrfid.com/
- type: Website
  url: https://www.gs1.org/standards/epcis
- type: Standards
  url: https://www.gs1.org/standards/epc-rfid-epcis-id-keys/epc-rfid-tds/1-12
provider_count: 58
providers:
- slug: wiliot
  name: Wiliot
  description: Wiliot operates an ambient IoT platform built on battery-free "IoT Pixels" - postage-stamp-sized Bluetooth sensor tags - and a cloud that turns everyday physical items into a continuous, real-time data source for supply-chain visibility ("…
  api_count: 3
  score_band: emerging
  score_composite: 23.7
  shared: 4
- slug: savi-technology
  name: Savi Technology
  description: Savi Technology provides Internet of Things (IoT) and active RFID (aRFID) solutions for real-time supply chain visibility, asset tracking, and cargo security. Combining active RFID tags, environmental condition sensors, and machine intelli…
  api_count: 0
  score_band: minimal
  score_composite: 8.1
  shared: 4
- slug: invendor
  name: Invendor
  description: Invendor is a smart industrial vending and vendor-managed inventory (VMI) platform for industrial distributors and manufacturers, combining weight-sensing (Gravity) and scan-based (Capture) smart cabinets, a Storeroom mobile app, and cloud…
  api_count: 2
  score_band: thin
  score_composite: 35.9
  shared: 3
- slug: got-its
  name: Reelables
  description: Reelables provides Track Anywhere smart labels and a RESTful platform API for global supply-chain and logistics visibility. The paper-thin Bluetooth and cellular smart labels are printed on off-the-shelf barcode printers, activated, attach…
  api_count: 2
  score_band: thin
  score_composite: 33.9
  shared: 3
- slug: avery-dennison
  name: Avery Dennison
  description: Avery Dennison is a global materials science and manufacturing company specializing in the design and manufacture of labeling and functional materials, packaging, and intelligent labels. Its RFID and digital-identification business runs at…
  api_count: 1
  score_band: emerging
  score_composite: 17.9
  shared: 3
- slug: ampaworks
  name: AMPAworks
  description: AMPAworks builds AI-powered smart-shelf inventory management for healthcare and defense supply chains. Its platform pairs computer-vision cameras and rolling kiosks that image inventory to auto-count stock in real time with software that t…
  api_count: 0
  score_band: emerging
  score_composite: 15.8
  shared: 3
- slug: trackonomy
  name: Trackonomy
  description: Trackonomy is a supply chain visibility company that digitizes real-world operations with barely-there smart label sensors. Its SmartTape and THL Tape products provide item-level tracking, monitoring location, temperature, humidity, and li…
  api_count: 0
  score_band: emerging
  score_composite: 11.3
  shared: 3
- slug: sensefinity
  name: Sensefinity
  description: Sensefinity is a supply-chain IoT company ("The IoT Transformation Company") delivering real-time tracking, monitoring, and analytics for global cargo and logistics operations. Its platform combines GPS/NB-IoT tracking devices for maritime…
  api_count: 0
  score_band: minimal
  score_composite: 10.2
  shared: 3
- slug: now
  name: DNOW
  description: 'DNOW Inc. (NYSE: DNOW), formerly NOW Inc. and operating as DistributionNOW, is a Houston-headquartered Fortune 1000 distributor of pipe, valves, fittings (PVF), pumps and packaged, engineered process and production equipment serving the up…'
  api_count: 1
  score_band: minimal
  score_composite: 8.0
  shared: 3
- slug: vue
  name: Vue
  description: Vue (Vue Technology) was an item-level RFID hardware and software company based in Lake Forest, California, backed by Canaan Partners at Series A. Its product family combined RFID readpoints and networking devices with a software platform…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: hubble-network
  name: Hubble Network
  description: Hubble Network is a Seattle-based IoT connectivity company, founded in 2021 by Alex Haro (Life360) and Ben Wild (Amazon Sidewalk), building a dual-stack global network that any standard Bluetooth Low Energy 5.0+ chip can reach with no mode…
  api_count: 2
  score_band: exemplar
  score_composite: 68.5
  shared: 2
- slug: kontaktio
  name: Kontakt.io
  description: Kontakt.io is an AI-powered real-time location system (RTLS) and IoT platform for healthcare operations, founded in 2013 with offices in New York and Krakow. Its Kio Cloud platform combines BLE/UWB tags, badges, gateways and sensors with s…
  api_count: 8
  score_band: strong
  score_composite: 65.7
  shared: 2
- slug: avnet
  name: Avnet
  description: 'Avnet is a global technology distributor and solutions provider that delivers electronic components, embedded solutions, and design and supply chain services to industrial and commercial customers. It publishes two API surfaces: the Avnet…'
  api_count: 15
  score_band: strong
  score_composite: 55.1
  shared: 2
- slug: tailor
  name: Tailor
  description: Tailor Technologies builds Tailor Platform, a headless, API-first ERP for retail, e-commerce and manufacturing operators. Its control plane is exposed as a single 254-RPC ConnectRPC service published as Protocol Buffers, and every applicat…
  api_count: 3
  score_band: developing
  score_composite: 53.0
  shared: 2
- slug: tracelink
  name: TraceLink
  description: TraceLink, Inc. is a Massachusetts-based supply chain digitalization company for the life sciences and healthcare industries, best known for pharmaceutical serialization and track-and-trace compliance (US DSCSA, EU FMD, and roughly two doz…
  api_count: 6
  score_band: developing
  score_composite: 52.1
  shared: 2
- slug: relex
  name: RELEX Solutions
  description: RELEX Solutions is a Helsinki-headquartered supply chain and retail planning software company whose unified platform covers demand forecasting, inventory and replenishment, space and assortment, pricing and promotions, workforce and store…
  api_count: 2
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: logiwa
  name: Logiwa
  description: Logiwa is a Chicago-based cloud fulfillment software company whose flagship product, Logiwa IO, is a warehouse management and fulfillment management system (WMS/FMS) built for high-volume B2C and DTC brands, wholesalers and third-party log…
  api_count: 2
  score_band: developing
  score_composite: 44.4
  shared: 2
- slug: dust-identity
  name: Dust Identity
  description: DUST Identity (Newton, Massachusetts; founded 2018 as an MIT spinout) binds physical objects to trusted digital records using the Diamond Unclonable Security Tag — an applied coating of engineered nano-diamonds in a polymer matrix that for…
  api_count: 2
  score_band: developing
  score_composite: 44.3
  shared: 2
- slug: canix
  name: Canix
  description: Canix is a cannabis enterprise resource planning (ERP) and seed-to-sale platform used by licensed cultivators, manufacturers and distributors to run cultivation, processing, inventory, sales and compliance operations. The product covers pl…
  api_count: 1
  score_band: developing
  score_composite: 39.9
  shared: 2
- slug: extensiv
  name: Extensiv
  description: Extensiv (formerly 3PL Central, rebranded in 2022) is a cloud-native omnichannel fulfillment software company for third-party logistics providers (3PLs) and brands. Its platform combines warehouse management (3PL Warehouse Manager and Ware…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 2
- slug: instock
  name: Instock
  description: Instock is a robotics company delivering a goods-to-person automated storage and retrieval system (ASRS) as a fulfillment robotics-as-a-service (RaaS) offering. The system pairs a static "Grid" racking framework, stackable "Bins", and auto…
  api_count: 1
  score_band: thin
  score_composite: 37.4
  shared: 2
- slug: crunchtime
  name: Crunchtime
  description: Crunchtime (CrunchTime! Information Systems) is an AI-powered restaurant operations management platform used by 850+ multi-unit restaurant brands across 150,000+ locations to run inventory and food-cost control, labor and scheduling, opera…
  api_count: 1
  score_band: thin
  score_composite: 36.8
  shared: 2
- slug: happy-cabbage-analytics
  name: Happy Cabbage Analytics
  description: Happy Cabbage Analytics is a cannabis retail software company founded in 2019 and headquartered in San Francisco, California, whose Happy Buyers platform gives dispensary buyers AI-assisted inventory management, demand forecasting, repleni…
  api_count: 2
  score_band: thin
  score_composite: 36.0
  shared: 2
- slug: estimote
  name: Estimote
  description: Estimote is a proximity and indoor-location company founded in 2012 that designs Bluetooth Low Energy, Ultra-Wideband (UWB) and LTE-M/NB-IoT beacons together with the Estimote Cloud platform for managing them at fleet scale. The Estimote C…
  api_count: 1
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: samsara
  name: Samsara
  description: Samsara is a leading connected operations platform for physical operations industries including transportation, logistics, construction, field services, and energy. The Samsara REST API provides programmatic access to fleet telematics, dri…
  api_count: 1
  score_band: thin
  score_composite: 34.9
  shared: 2
- slug: tive
  name: Tive
  description: Tive is a real-time supply-chain and shipment visibility platform built on cellular IoT trackers. The Tive Public API (v3) lets you programmatically create and track shipments, manage trackers/devices, pull sensor data (location, temperatu…
  api_count: 1
  score_band: thin
  score_composite: 34.4
  shared: 2
- slug: prediko
  name: Prediko
  description: Prediko is an AI-powered inventory management and planning platform for Shopify D2C and B2B brands, covering demand forecasting, supply and replenishment planning, purchase-order management, raw-materials and bill-of-materials tracking, an…
  api_count: 1
  score_band: thin
  score_composite: 29.2
  shared: 2
- slug: crunchtime-information-systems
  name: Crunchtime Information Systems
  description: Crunchtime (Crunchtime Information Systems) is a Boston-based provider of AI-powered operations-management software for multi-unit restaurants, founded in 1995 and serving 850+ restaurant brands across 150,000+ locations. Its platform unif…
  api_count: 1
  score_band: thin
  score_composite: 28.8
  shared: 2
- slug: stord
  name: Stord
  description: Stord is a commerce fulfillment platform that combines physical warehouse infrastructure with integrated software to manage omnichannel logistics for DTC and B2B brands. The platform provides REST APIs for managing orders, inventory, shipm…
  api_count: 1
  score_band: thin
  score_composite: 26.6
  shared: 2
- slug: warego
  name: WareGo
  description: Cloud-based Warehouse Management System (WMS) for wholesalers, distributors, 3PLs, and ecommerce businesses, covering inventory tracking, order fulfillment, serial-number tracking, kitting, replenishment, inventory forecasting and supply-c…
  api_count: 1
  score_band: emerging
  score_composite: 23.6
  shared: 2
---
