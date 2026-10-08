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
- Inventory
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
- type: CapabilityMap
  url: https://github.com/api-evangelist/rfid/blob/main/capabilities/rfid-capability-edges.yml
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
provider_count: 86
providers:
- slug: wiliot
  name: Wiliot
  description: Wiliot operates an ambient IoT platform built on battery-free "IoT Pixels" - postage-stamp-sized Bluetooth sensor tags - and a cloud that turns everyday physical items into a continuous, real-time data source for supply-chain visibility ("…
  api_count: 3
  score_band: emerging
  score_composite: 24.8
  shared: 4
- slug: savi-technology
  name: Savi Technology
  description: Savi Technology provides Internet of Things (IoT) and active RFID (aRFID) solutions for real-time supply chain visibility, asset tracking, and cargo security. Combining active RFID tags, environmental condition sensors, and machine intelli…
  api_count: 0
  score_band: minimal
  score_composite: 7.0
  shared: 4
- slug: invendor
  name: Invendor
  description: Invendor is a smart industrial vending and vendor-managed inventory (VMI) platform for industrial distributors and manufacturers, combining weight-sensing (Gravity) and scan-based (Capture) smart cabinets, a Storeroom mobile app, and cloud…
  api_count: 2
  score_band: thin
  score_composite: 37.3
  shared: 3
- slug: got-its
  name: Reelables
  description: Reelables provides Track Anywhere smart labels and a RESTful platform API for global supply-chain and logistics visibility. The paper-thin Bluetooth and cellular smart labels are printed on off-the-shelf barcode printers, activated, attach…
  api_count: 2
  score_band: thin
  score_composite: 33.8
  shared: 3
- slug: avery-dennison
  name: Avery Dennison
  description: Avery Dennison is a global materials science and manufacturing company specializing in the design and manufacture of labeling and functional materials, packaging, and intelligent labels. Its RFID and digital-identification business runs at…
  api_count: 1
  score_band: emerging
  score_composite: 18.7
  shared: 3
- slug: ampaworks
  name: AMPAworks
  description: AMPAworks builds AI-powered smart-shelf inventory management for healthcare and defense supply chains. Its platform pairs computer-vision cameras and rolling kiosks that image inventory to auto-count stock in real time with software that t…
  api_count: 0
  score_band: emerging
  score_composite: 15.7
  shared: 3
- slug: simbe-robotics
  name: Simbe Robotics
  description: Simbe Robotics (Simbe) is a San Francisco Bay Area physical-AI and retail-robotics company whose Store Intelligence platform combines the Tally shelf-scanning robot, fixed in-store sensors and RFID to give grocery, wholesale-club, home-imp…
  api_count: 1
  score_band: emerging
  score_composite: 15.6
  shared: 3
- slug: trackonomy
  name: Trackonomy
  description: Trackonomy is a supply chain visibility company that digitizes real-world operations with barely-there smart label sensors. Its SmartTape and THL Tape products provide item-level tracking, monitoring location, temperature, humidity, and li…
  api_count: 0
  score_band: minimal
  score_composite: 10.9
  shared: 3
- slug: sensefinity
  name: Sensefinity
  description: Sensefinity is a supply-chain IoT company ("The IoT Transformation Company") delivering real-time tracking, monitoring, and analytics for global cargo and logistics operations. Its platform combines GPS/NB-IoT tracking devices for maritime…
  api_count: 0
  score_band: minimal
  score_composite: 9.1
  shared: 3
- slug: now
  name: DNOW
  description: 'DNOW Inc. (NYSE: DNOW), formerly NOW Inc. and operating as DistributionNOW, is a Houston-headquartered Fortune 1000 distributor of pipe, valves, fittings (PVF), pumps and packaged, engineered process and production equipment serving the up…'
  api_count: 1
  score_band: minimal
  score_composite: 8.3
  shared: 3
- slug: vue
  name: Vue
  description: Vue (Vue Technology) was an item-level RFID hardware and software company based in Lake Forest, California, backed by Canaan Partners at Series A. Its product family combined RFID readpoints and networking devices with a software platform…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: hubble-network
  name: Hubble Network
  description: Hubble Network is a Seattle-based IoT connectivity company, founded in 2021 by Alex Haro (Life360) and Ben Wild (Amazon Sidewalk), building a dual-stack global network that any standard Bluetooth Low Energy 5.0+ chip can reach with no mode…
  api_count: 2
  score_band: exemplar
  score_composite: 70.4
  shared: 2
- slug: optoro
  name: Optoro
  description: Optoro is a returns management and reverse-logistics software company (Washington, DC; acquired by Blue Yonder in August 2025) whose OptiTurn platform powers the full returns lifecycle for retailers, brands and 3PLs — a shopper-facing retu…
  api_count: 34
  score_band: strong
  score_composite: 61.8
  shared: 2
- slug: kontaktio
  name: Kontakt.io
  description: Kontakt.io is an AI-powered real-time location system (RTLS) and IoT platform for healthcare operations, founded in 2013 with offices in New York and Krakow. Its Kio Cloud platform combines BLE/UWB tags, badges, gateways and sensors with s…
  api_count: 8
  score_band: strong
  score_composite: 61.4
  shared: 2
- slug: leaflink
  name: LeafLink
  description: LeafLink is the wholesale cannabis marketplace and B2B commerce platform connecting licensed cannabis brands, distributors and retailers across roughly 30 US markets. The platform bundles a wholesale marketplace, order management, payments…
  api_count: 2
  score_band: strong
  score_composite: 61.0
  shared: 2
- slug: walmart
  name: Walmart
  description: Walmart is a multinational retail corporation that operates a chain of hypermarkets, discount department stores, and grocery stores. The company is known for offering a wide range of products at competitive prices, attracting customers fro…
  api_count: 27
  score_band: strong
  score_composite: 60.9
  shared: 2
- slug: katana
  name: Katana
  description: Katana is a cloud manufacturing ERP and inventory management platform for product businesses. It gives makers and small-to-midsize manufacturers real-time inventory control across multiple locations and sales channels, production and manuf…
  api_count: 1
  score_band: strong
  score_composite: 60.4
  shared: 2
- slug: tailor
  name: Tailor
  description: Tailor Technologies builds Tailor Platform, a headless, API-first ERP for retail, e-commerce and manufacturing operators. Its control plane is exposed as a single 254-RPC ConnectRPC service published as Protocol Buffers, and every applicat…
  api_count: 3
  score_band: strong
  score_composite: 54.8
  shared: 2
- slug: shipmonk
  name: ShipMonk
  description: ShipMonk is a Florida-headquartered third-party logistics (3PL) and ecommerce fulfillment provider operating a network of fulfillment centres across the United States, Canada, Mexico, the United Kingdom and Czechia. It runs an order manage…
  api_count: 6
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: avnet
  name: Avnet
  description: 'Avnet is a global technology distributor and solutions provider that delivers electronic components, embedded solutions, and design and supply chain services to industrial and commercial customers. It publishes two API surfaces: the Avnet…'
  api_count: 23
  score_band: developing
  score_composite: 53.3
  shared: 2
- slug: relex
  name: RELEX Solutions
  description: RELEX Solutions is a Helsinki-headquartered supply chain and retail planning software company whose unified platform covers demand forecasting, inventory and replenishment, space and assortment, pricing and promotions, workforce and store…
  api_count: 2
  score_band: developing
  score_composite: 53.3
  shared: 2
- slug: nabis
  name: Nabis
  description: Nabis is a licensed cannabis wholesale distributor and B2B marketplace founded in 2018 by Vince C. Ning and Jun S. Lee, operating in California, New York and Nevada. It runs distribution and fulfillment warehouses, an ordering marketplace…
  api_count: 3
  score_band: developing
  score_composite: 50.0
  shared: 2
- slug: tracelink
  name: TraceLink
  description: TraceLink, Inc. is a Massachusetts-based supply chain digitalization company for the life sciences and healthcare industries, best known for pharmaceutical serialization and track-and-trace compliance (US DSCSA, EU FMD, and roughly two doz…
  api_count: 6
  score_band: developing
  score_composite: 49.6
  shared: 2
- slug: logiwa
  name: Logiwa
  description: Logiwa is a Chicago-based cloud fulfillment software company whose flagship product, Logiwa IO, is a warehouse management and fulfillment management system (WMS/FMS) built for high-volume B2C and DTC brands, wholesalers and third-party log…
  api_count: 2
  score_band: developing
  score_composite: 46.5
  shared: 2
- slug: dust-identity
  name: Dust Identity
  description: DUST Identity (Newton, Massachusetts; founded 2018 as an MIT spinout) binds physical objects to trusted digital records using the Diamond Unclonable Security Tag — an applied coating of engineered nano-diamonds in a polymer matrix that for…
  api_count: 2
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: kargo-ai
  name: Kargo
  description: Kargo (Kargo Technologies, kargo.ai) builds an AI-powered smart loading dock for warehouses and distribution centers. Camera towers (Kargo Tower) and forklift-mounted cameras (Kargo Lift) apply computer vision to every pallet that moves th…
  api_count: 1
  score_band: developing
  score_composite: 44.0
  shared: 2
- slug: canix
  name: Canix
  description: Canix is a cannabis enterprise resource planning (ERP) and seed-to-sale platform used by licensed cultivators, manufacturers and distributors to run cultivation, processing, inventory, sales and compliance operations. The product covers pl…
  api_count: 1
  score_band: developing
  score_composite: 41.3
  shared: 2
- slug: whiplash-merchandising
  name: Whiplash Merchandising
  description: Whiplash (now Ryder E-commerce by Whiplash) is an order-fulfillment and third-party logistics (3PL) platform for direct-to-consumer and ecommerce brands. It runs a network of fulfillment centers offering pick-pack-ship, warehousing, invent…
  api_count: 1
  score_band: developing
  score_composite: 39.9
  shared: 2
- slug: omniful-inc
  name: Omniful
  description: Omniful is an AI-powered unified supply chain and fulfillment platform that consolidates order management (OMS), warehouse management (WMS), transportation management (TMS), inventory, point of sale, and returns into a single intelligent s…
  api_count: 1
  score_band: developing
  score_composite: 39.5
  shared: 2
- slug: crunchtime
  name: Crunchtime
  description: Crunchtime (CrunchTime! Information Systems) is an AI-powered restaurant operations management platform used by 850+ multi-unit restaurant brands across 150,000+ locations to run inventory and food-cost control, labor and scheduling, opera…
  api_count: 1
  score_band: thin
  score_composite: 38.6
  shared: 2
---
