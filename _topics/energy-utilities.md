---
layout: topic
slug: energy-utilities
name: Energy and Utilities
kind: topic
description: Energy and Utilities is a topic profile in the API Evangelist Network cataloging the API surfaces that move data across the modern electricity, gas, and water value chain. It indexes utility data integration APIs, grid and wholesale market operator APIs, federal energy data programs, renewable energy research APIs, weather APIs that drive grid demand and solar forecasting, EV charging interoperability protocols, and the Green Button family of customer energy data standards. The repo provides a baseline catalog plus shared semantics (JSON Schema, JSON-LD, vocabulary, examples) for the meter reading / energy data point that ties every one of these surfaces together.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/energy-utilities.png
tags:
- Energy
- Utilities
- Electricity
- Grid
- Smart Meter
- Meter Data
- Green Button
- Demand Response
- DERMS
- EV Charging
- ISO/RTO
- Renewable Energy
- Solar
- Wind
- Weather
- Open Data
repo: https://github.com/api-evangelist/energy-utilities
api_count: 30
apis:
- name: ISO and RTO Wholesale Market APIs
  description: Independent System Operators and Regional Transmission Organizations publish locational marginal prices, load forecasts, generation mix, ancillary services awards, and capacity market data through public data portals and (where available)…
  url: https://oasis.caiso.com/
- name: EIA Open Data API
  description: The U.S. Energy Information Administration publishes time-series data covering electricity, natural gas, petroleum, coal, nuclear outages, renewables, and international energy through APIv2. Datasets are organized by major energy category…
  url: https://www.eia.gov/opendata/
- name: NREL Developer Network APIs
  description: The National Renewable Energy Laboratory exposes a developer network of REST APIs covering solar resource (NSRDB, PVWatts), wind resource, alternative fuel stations, utility rates (URDB), transportation, buildings, and geothermal data. Aut…
  url: https://developer.nrel.gov/
- name: Weather APIs for Grid and Solar
  description: Weather APIs that feed grid-demand modelling, renewable generation forecasts, and outage operations. Includes the National Weather Service public API (no authentication, GeoJSON), OpenWeather solar irradiance and panel-output products, and…
  url: https://api.weather.gov/
- name: EV Charging Interoperability Protocols
  description: Open protocols that govern communication between EV charging stations, charging management systems, and roaming hubs. OCPP is the charger-to-back-office protocol from the Open Charge Alliance. OCPI is the back-office-to-back-office roaming…
  url: https://openchargealliance.org/protocols/open-charge-point-protocol/
- name: OpenADR Demand Response
  description: OpenADR is an open, two-way information exchange model and Smart Grid standard for automating demand response and orchestrating distributed energy resources. The OpenADR Alliance publishes profile specifications, schema files, sample paylo…
  url: https://www.openadr.org/
- name: Green Button (CMD / DMD / ESPI / CDS)
  description: Green Button is the consumer energy data standard for utilities and third-party solution providers. Connect My Data (CMD) is the machine-to-machine sharing flow. Download My Data (DMD) is the user-initiated export flow. The Energy Services…
  url: https://www.greenbuttonalliance.org/
- name: Distributed Energy Resource Management APIs
  description: DERMS platforms aggregate, monitor, dispatch, and optimize distributed energy resources such as rooftop solar, behind-the-meter batteries, EV chargers, and controllable loads. DERMS API surfaces typically wrap OpenADR for event signaling,…
  url: https://www.openadr.org/
- name: Energy and Utilities Accounting API
  description: The Accounting API from Energy and Utilities — 2 operation(s) for accounting.
  url: https://utilityapi.com/
- name: Energy and Utilities Authorizations API
  description: The Authorizations API from Energy and Utilities — 1 operation(s) for authorizations.
  url: https://utilityapi.com/
- name: Energy and Utilities Bills API
  description: The Bills API from Energy and Utilities — 1 operation(s) for bills.
  url: https://utilityapi.com/
- name: Energy and Utilities Events API
  description: The Events API from Energy and Utilities — 1 operation(s) for events.
  url: https://utilityapi.com/
- name: Energy and Utilities Files API
  description: The Files API from Energy and Utilities — 1 operation(s) for files.
  url: https://utilityapi.com/
- name: Energy and Utilities Forms API
  description: The Forms API from Energy and Utilities — 2 operation(s) for forms.
  url: https://utilityapi.com/
- name: Energy and Utilities Intervals API
  description: The Intervals API from Energy and Utilities — 1 operation(s) for intervals.
  url: https://utilityapi.com/
- name: Energy and Utilities Meters API
  description: The Meters API from Energy and Utilities — 1 operation(s) for meters.
  url: https://utilityapi.com/
- name: Energy and Utilities Templates API
  description: The Templates API from Energy and Utilities — 1 operation(s) for templates.
  url: https://utilityapi.com/
- name: Energy and Utilities Alerts API
  description: The Alerts API from Energy and Utilities — 8 operation(s) for alerts.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Aviation API
  description: The Aviation API from Energy and Utilities — 7 operation(s) for aviation.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Glossary API
  description: The Glossary API from Energy and Utilities — 1 operation(s) for glossary.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Gridpoints API
  description: The Gridpoints API from Energy and Utilities — 4 operation(s) for gridpoints.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Icons API
  description: The Icons API from Energy and Utilities — 3 operation(s) for icons.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Offices API
  description: The Offices API from Energy and Utilities — 8 operation(s) for offices.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Points API
  description: The Points API from Energy and Utilities — 3 operation(s) for points.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Products API
  description: The Products API from Energy and Utilities — 9 operation(s) for products.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Radar API
  description: The Radar API from Energy and Utilities — 8 operation(s) for radar.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Radio API
  description: The Radio API from Energy and Utilities — 3 operation(s) for radio.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Stations API
  description: The Stations API from Energy and Utilities — 7 operation(s) for stations.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Thumbnails API
  description: The Thumbnails API from Energy and Utilities — 1 operation(s) for thumbnails.
  url: https://oasis.caiso.com/
- name: Energy and Utilities Zones API
  description: The Zones API from Energy and Utilities — 7 operation(s) for zones.
  url: https://oasis.caiso.com/
links:
- type: IssueTracker
  url: https://github.com/ocpi/ocpi/issues
- type: Releases
  url: https://github.com/ocpi/ocpi/releases
- type: ContributionGuide
  url: https://github.com/ocpi/ocpi/blob/2.3.0/release/core/CONTRIBUTING.md
- type: AgenticAccess
  url: https://artifacts.apis.io/energy-utilities/agentic-access/energy-utilities-agentic-access.yml
- type: DomainSecurity
  url: https://artifacts.apis.io/energy-utilities/security/energy-utilities-domain-security.yml
- type: Authentication
  url: https://artifacts.apis.io/energy-utilities/authentication/energy-utilities-authentication.yml
- type: TopicPage
  url: https://apievangelist.com/topics/energy-utilities/
- type: Website
  url: https://apievangelist.com/
- type: Network
  url: https://network.apievangelist.com/
- type: JSONLD
  url: https://artifacts.apis.io/energy-utilities/json-ld/energy-utilities-context.jsonld
- type: JSONSchema
  url: https://artifacts.apis.io/energy-utilities/json-schema/energy-utilities-meter-reading-schema.json
- type: JSONSchema
  url: https://artifacts.apis.io/energy-utilities/json-schema/energy-utilities-energy-data-point-schema.json
- type: JSONSchema
  url: https://artifacts.apis.io/energy-utilities/json-schema/energy-utilities-usage-point-schema.json
- type: JSONStructure
  url: https://artifacts.apis.io/energy-utilities/json-structure/energy-utilities-meter-reading-structure.json
- type: Vocabulary
  url: https://artifacts.apis.io/energy-utilities/vocabulary/energy-utilities-vocabulary.yml
- type: Examples
  url: https://artifacts.apis.io/energy-utilities/examples/
provider_count: 483
providers:
- slug: con-edison
  name: Con Edison
  description: Consolidated Edison Company of New York, Inc. (CECONY, trading as Con Edison) is the investor-owned electric, gas and steam utility that serves New York City and Westchester County, and together with its sibling Orange & Rockland Utilities…
  api_count: 1
  score_band: developing
  score_composite: 53.4
  shared: 8
- slug: southern-california-edison
  name: Southern California Edison
  description: Southern California Edison (SCE) is the regulated electric utility subsidiary of Edison International, delivering power to roughly 15 million people across a 50,000 square-mile service territory in central, coastal, and southern California…
  api_count: 1
  score_band: thin
  score_composite: 29.9
  shared: 8
- slug: energyhub
  name: EnergyHub
  description: EnergyHub is a Brooklyn, New York distributed energy resource management system (DERMS) vendor and an independent subsidiary of Alarm.com (Nasdaq ALRM), operating in its home market of the United States. Its Edge DERMS platform (formerly m…
  api_count: 2
  score_band: emerging
  score_composite: 23.8
  shared: 8
- slug: virtual-peaker
  name: Virtual Peaker
  description: Virtual Peaker is a Louisville, Kentucky software company selling grid-edge DERMS and virtual power plant software to United States and Canadian electric utilities — investor-owned utilities, municipal utilities, and rural electric coopera…
  api_count: 2
  score_band: developing
  score_composite: 49.4
  shared: 7
- slug: hydro-ottawa
  name: Hydro Ottawa
  description: Hydro Ottawa Holding Inc. is a private corporation 100 percent owned by the City of Ottawa, and the parent of Hydro Ottawa Limited — the regulated local distribution company (LDC) that delivers electricity to roughly 372,000 customers in O…
  api_count: 1
  score_band: thin
  score_composite: 27.6
  shared: 7
- slug: nova-scotia-power
  name: Nova Scotia Power
  description: Nova Scotia Power Incorporated (NSPI) is the investor-owned, vertically integrated regulated electric utility serving roughly half a million customers across Nova Scotia, Canada. A subsidiary of Halifax-based Emera Inc., it owns generation…
  api_count: 0
  score_band: emerging
  score_composite: 20.7
  shared: 7
- slug: uk-power-networks
  name: UK Power Networks
  description: UK Power Networks is the distribution network operator for London, the South East and the East of England, running three electricity distribution licence areas — London Power Networks (LPN), South Eastern Power Networks (SPN) and Eastern P…
  api_count: 2
  score_band: strong
  score_composite: 64.1
  shared: 6
- slug: pge
  name: Pacific Gas and Electric
  description: Pacific Gas and Electric Company is the investor-owned electric and natural gas utility for northern and central California — incorporated in California in 1905, headquartered in Oakland, roughly 23,000 employees, a 70,000-square- mile ser…
  api_count: 3
  score_band: strong
  score_composite: 57.5
  shared: 6
- slug: endeavour-energy
  name: Endeavour Energy
  description: Endeavour Energy is the regulated electricity distribution network service provider (DNSP) for Greater Western Sydney, the Blue Mountains, the Illawarra, the Southern Highlands, the South Coast and Central West of New South Wales, Australi…
  api_count: 2
  score_band: strong
  score_composite: 56.9
  shared: 6
- slug: openadr-alliance
  name: OpenADR Alliance
  description: The OpenADR Alliance is a San Ramon, California mutual-benefit membership corporation that develops, certifies, and promotes OpenADR, the open information-exchange model utilities, ISOs/RTOs, aggregators, and device makers use to automate…
  api_count: 4
  score_band: strong
  score_composite: 55.7
  shared: 6
- slug: hydro-quebec
  name: Hydro-Québec
  description: Hydro-Québec is the government-owned Crown corporation that generates, transmits and distributes almost all of the electricity consumed in Québec, Canada — a vertically integrated, near-monopoly utility running one of the largest hydroelec…
  api_count: 2
  score_band: strong
  score_composite: 55.4
  shared: 6
- slug: miso
  name: MISO
  description: MISO — the Midcontinent Independent System Operator — is the not-for-profit Regional Transmission Organization that operates the electric grid and the wholesale electricity markets across fifteen US states and the Canadian province of Mani…
  api_count: 5
  score_band: developing
  score_composite: 50.4
  shared: 6
- slug: reposit-power
  name: Reposit Power
  description: Reposit Power is an Australian home-energy technology company founded in 2012 and headquartered in Canberra, ACT, that builds the Reposit Controller — a local control device and cloud platform that sits on top of a household's solar, batte…
  api_count: 2
  score_band: developing
  score_composite: 45.9
  shared: 6
- slug: octopus-energy
  name: Octopus Energy
  description: Octopus Energy is a UK-founded retail energy supplier and the parent of Kraken Technologies, the AI-powered energy operating system that runs both Octopus and many of the world's largest utilities. Octopus operates a free, open REST API at…
  api_count: 1
  score_band: developing
  score_composite: 44.1
  shared: 6
- slug: ontario-energy-board
  name: Ontario Energy Board
  description: The Ontario Energy Board (OEB) is the independent regulator of Ontario's electricity and natural gas sectors, licensing and rate-regulating roughly 60 electricity distributors, the province's transmitters, storage and generation licensees,…
  api_count: 2
  score_band: developing
  score_composite: 44.0
  shared: 6
- slug: energy-queensland
  name: Energy Queensland
  description: 'Energy Queensland Limited is the Queensland Government-owned corporation formed on 30 June 2016 by merging Ergon Energy and Energex. It is the whole Queensland electricity value chain below transmission in a single holding company: Energex…'
  api_count: 2
  score_band: developing
  score_composite: 39.4
  shared: 6
- slug: epcor
  name: EPCOR
  description: EPCOR Utilities Inc. is a municipally owned Canadian utility headquartered in Edmonton, Alberta, wholly owned by the City of Edmonton, that builds and operates electricity distribution and transmission, water and wastewater, and natural ga…
  api_count: 1
  score_band: thin
  score_composite: 35.2
  shared: 6
- slug: atco
  name: ATCO
  description: 'ATCO Ltd. (TSX: ACO.X) is a Calgary, Alberta diversified global corporation and the controlling shareholder of Canadian Utilities Limited, through which it runs the regulated energy businesses that make it one of western Canada''s largest u…'
  api_count: 2
  score_band: thin
  score_composite: 32.5
  shared: 6
- slug: jemena
  name: Jemena
  description: Jemena is an Australian energy infrastructure owner-operator, headquartered in Melbourne and owned by SGSP (Australia) Assets — 60% State Grid Corporation of China, 40% Singapore Power. It sits on the poles-and-pipes side of the value chai…
  api_count: 1
  score_band: thin
  score_composite: 28.4
  shared: 6
- slug: essential-energy
  name: Essential Energy
  description: Essential Energy is a New South Wales Government-owned statutory corporation and the distribution network service provider (DNSP) for 95 per cent of the geographic area of NSW plus parts of southern Queensland — the poles, wires, substatio…
  api_count: 3
  score_band: thin
  score_composite: 28.1
  shared: 6
- slug: ausgrid
  name: Ausgrid
  description: Ausgrid is the largest electricity distribution network service provider on Australia's east coast, operating the poles, wires, substations and underground cables that deliver power to more than 1.8 million customers across Sydney, the Cen…
  api_count: 0
  score_band: thin
  score_composite: 27.1
  shared: 6
- slug: hawaiian-electric-industries
  name: Hawaiian Electric Industries
  description: Hawaiian Electric Industries (HEI) is a Honolulu-based holding company whose principal subsidiary, Hawaiian Electric, delivers electricity to roughly 95% of Hawaii's residents through three operating utilities — Hawaiian Electric (Oahu), H…
  api_count: 1
  score_band: emerging
  score_composite: 25.5
  shared: 6
- slug: sa-power-networks
  name: SA Power Networks
  description: SA Power Networks is South Australia's sole electricity distributor — the poles-and-wires DNSP that builds, maintains and upgrades the network delivering power to around 900,000 homes and businesses, and the operator of the state's Flexibl…
  api_count: 0
  score_band: emerging
  score_composite: 23.3
  shared: 6
- slug: uplight
  name: Uplight
  description: Uplight is a Boulder, Colorado energy technology company formed in 2019 from the merger of Tendril and Simple Energy and expanded through the acquisitions of EnergySavvy, FirstFuel, Ecotagious, EEme, and DERMS/VPP provider AutoGrid (closed…
  api_count: 1
  score_band: emerging
  score_composite: 20.0
  shared: 6
- slug: bc-hydro
  name: BC Hydro
  description: British Columbia Hydro and Power Authority (BC Hydro) is a provincial Crown corporation whose sole shareholder is the Province of British Columbia, and which states that it generates and delivers electricity to "95% of the population of B.…
  api_count: 0
  score_band: emerging
  score_composite: 19.3
  shared: 6
- slug: ovo-energy
  name: OVO Energy
  description: OVO Energy is a United Kingdom household electricity and gas supplier founded in Bristol in 2009 by Stephen Fitzpatrick, and — after absorbing SSE's household energy business in January 2020 — the third-largest domestic supplier in Great B…
  api_count: 0
  score_band: emerging
  score_composite: 19.1
  shared: 6
- slug: flexitricity
  name: Flexitricity
  description: Flexitricity Limited is an Edinburgh-based energy flexibility aggregator and licensed electricity supplier operating what it describes as the first, largest and most advanced demand response portfolio in Great Britain — a virtual power pla…
  api_count: 0
  score_band: emerging
  score_composite: 16.6
  shared: 6
- slug: fuse
  name: Fuse
  description: Fuse Energy is a UK retail energy supplier providing gas and electricity to homes and businesses, alongside EV charging, solar and battery storage tracking with grid export, and smart home energy management. The company emphasises savings…
  api_count: 0
  score_band: emerging
  score_composite: 13.6
  shared: 6
- slug: rabotenergy
  name: rabot.energy
  description: rabot.energy (RABOT Energy DE GmbH) is a Hamburg-based German electricity supplier offering dynamic and fixed-rate power tariffs where consumers pay hourly rates that track the wholesale electricity market. The company provides 100% renewa…
  api_count: 0
  score_band: minimal
  score_composite: 10.6
  shared: 6
- slug: autogrid
  name: AutoGrid
  description: AutoGrid Systems is a United States grid-technology company founded in 2011 by Amit Narayan in Redwood City, California, that built AI and machine-learning software for distributed energy resource management (DERMS), virtual power plants,…
  api_count: 0
  score_band: minimal
  score_composite: 8.8
  shared: 6
---
