---
layout: topic
slug: aircon
name: Aircon
kind: topic
description: A curated index of APIs, data sources, and developer resources related to air conditioning, HVAC (Heating, Ventilation, and Air Conditioning), and climate control systems. This topic collection covers smart thermostat APIs, building automation protocols, IoT climate APIs, and environmental data APIs used in residential, commercial, and industrial HVAC applications.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/aircon.png
tags:
- Air Conditioning
- HVAC
- Climate Control
- IoT
- Smart Home
- Thermostat
- Building Automation
- Energy Management
repo: https://github.com/api-evangelist/aircon
api_count: 6
apis:
- name: Google Nest Device Access API
  description: The Nest Device Access API (Google Smart Device Management API) provides programmatic control over Nest thermostats, cameras, and doorbells. Supports reading thermostat state, setting target temperatures, switching HVAC modes, and managing…
  url: https://developers.home.google.com/nest/device-access
- name: Ecobee API
  description: The Ecobee API provides access to ecobee smart thermostats for reading and writing thermostat data, managing schedules, reading sensor data, and implementing custom home automation. Supports OAuth2 authentication and provides access to the…
  url: https://www.ecobee.com/home/developer/api/introduction/index.shtml
- name: Resideo (Honeywell Home) API
  description: The Resideo API (formerly Honeywell Home API) provides access to Honeywell and Resideo smart thermostats and home security systems. Supports reading and controlling thermostat setpoints, modes, schedules, and fan operation. Uses OAuth2 and…
  url: https://developer.resideo.com
- name: Sensibo API
  description: The Sensibo API provides control over Sensibo Sky and Air devices that add smart functionality to existing mini-split and window AC units. Supports reading AC state, setting temperature and mode, scheduling, and accessing historical usage…
  url: https://sensibo.github.io
- name: OpenWeatherMap API
  description: OpenWeatherMap provides weather data APIs used in HVAC automation to adapt cooling/heating based on outdoor conditions. Offers current weather, forecasts, historical data, and air quality data relevant to climate control decisions.
  url: https://openweathermap.org/api
- name: Home Assistant REST API
  description: The Home Assistant REST API provides access to all home automation entities including climate/HVAC entities. Supports reading thermostat state, setting temperature, changing HVAC mode, and triggering automations for air conditioning contro…
  url: https://developers.home-assistant.io/docs/api/rest/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/aircon/blob/main/security/aircon-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/aircon/blob/main/security/aircon-domain-security.yml
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/aircon/refs/heads/main/vocabulary/aircon-vocabulary.yaml
provider_count: 102
providers:
- slug: sensibo
  name: Sensibo
  description: Sensibo builds smart air conditioning controllers and indoor air quality monitors (Sensibo Sky, Air, Air Pro, and Elements) that add app, voice, and API control to existing mini-split, window, and portable AC and heat-pump units. The Sensi…
  api_count: 1
  score_band: thin
  score_composite: 39.0
  shared: 5
- slug: lennox-international
  name: Lennox International
  description: Lennox International is a global leader in the heating, air conditioning, and refrigeration markets, providing climate control solutions for residential and commercial applications. Lennox does not publish a general developer portal for HV…
  api_count: 3
  score_band: emerging
  score_composite: 14.2
  shared: 5
- slug: boldr
  name: Boldr
  description: Boldr is a Techstars-backed consumer hardware company building energy-saving smart home climate control devices. Its two products are Kelvin, a smart infrared heater, and Klima, a smart thermostat controller for mini-split air conditioners…
  api_count: 0
  score_band: emerging
  score_composite: 11.8
  shared: 5
- slug: aedifion
  name: Aedifion
  description: aedifion GmbH is a Cologne-based PropTech founded in 2017 that operates a vendor-neutral, patented cloud platform for the optimized operation of non-residential buildings. The platform ingests real-time operating data from all building tra…
  api_count: 2
  score_band: exemplar
  score_composite: 66.7
  shared: 4
- slug: 75f
  name: 75F
  description: 75F is an IoT-based building management and automation company (Burnsville, Minnesota; acquired by Carrier Global in July 2026) whose vertically integrated platform pairs wireless sensors, thermostats and Central Control Units with cloud s…
  api_count: 2
  score_band: developing
  score_composite: 43.0
  shared: 4
- slug: ecobee
  name: ecobee
  description: ecobee makes smart Wi-Fi thermostats, room sensors, cameras, and other connected home devices. The ecobee API is a REST-like JSON interface, based at https://api.ecobee.com/1/, that lets authorized third-party applications read and control…
  api_count: 1
  score_band: thin
  score_composite: 36.1
  shared: 4
- slug: carrier-global
  name: Carrier Global
  description: Carrier Global Corporation is a global provider of healthy, safe, sustainable, and intelligent building and cold-chain solutions, spanning HVAC, refrigeration, fire, security, and building automation technologies. Its digital ecosystem inc…
  api_count: 3
  score_band: developing
  score_composite: 53.4
  shared: 3
- slug: nest
  name: Nest
  description: Nest is Google's smart home brand — thermostats, cameras, doorbells, and the Nest Hub — originally founded as Nest Labs (a Lightspeed Venture Partners portfolio company) and acquired by Google. Developers integrate with authorized Nest dev…
  api_count: 1
  score_band: developing
  score_composite: 46.0
  shared: 3
- slug: google-nest
  name: Google Nest Smart Device Management
  description: The Smart Device Management (SDM) API is a REST API that allows developers to manage Google Nest devices including thermostats, cameras, doorbells, and displays. It provides access to device traits and commands using a trait-based model, e…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 3
- slug: verdigris-technologies
  name: Verdigris Technologies
  description: Verdigris Technologies builds AI-powered building energy intelligence, pairing proprietary current-sensor hardware clamped onto a building's electrical panels with cloud software that monitors every circuit in real time. The Verdigris API…
  api_count: 1
  score_band: developing
  score_composite: 40.3
  shared: 3
- slug: passivelogic
  name: PassiveLogic
  description: PassiveLogic builds a physics-based autonomy platform for buildings and industrial systems — the Hive, Hive Mini and Cell edge controllers, the Sense wireless sensor line, and the Autonomy Suite design/operate applications (Blueprint, Crea…
  api_count: 2
  score_band: developing
  score_composite: 40.0
  shared: 3
- slug: brick
  name: BRICK Schema
  description: BRICK is an open-source community-driven ontology standard for standardizing semantic descriptions of physical, logical, and virtual assets in buildings and the relationships between them. Using Semantic Web (RDF/OWL) technology, BRICK v1.…
  api_count: 2
  score_band: thin
  score_composite: 38.4
  shared: 3
- slug: clockworks-analytics
  name: Clockworks Analytics
  description: Clockworks Analytics is a Boston-area building-analytics company whose cloud platform performs automated fault detection and diagnostics (FDD) on HVAC and building systems. It ingests interval data from Building Management Systems through…
  api_count: 4
  score_band: thin
  score_composite: 36.8
  shared: 3
- slug: hello-therma
  name: Hello Therma
  description: Hello Therma is the original brand of Therma, Inc., the San Francisco cold-chain and cooling intelligence company founded in 2014 by Manik Suri, which rebranded as GlacierGrid in February 2024 and now operates as GlacierGrid, Inc. out of R…
  api_count: 1
  score_band: thin
  score_composite: 35.1
  shared: 3
- slug: trane-technologies
  name: Trane Technologies
  description: 'Trane Technologies plc (NYSE: TT) is an Ireland-domiciled global climate innovator that designs, manufactures, sells, and services heating, ventilation, air conditioning (HVAC), transport refrigeration, and building-automation systems. The…'
  api_count: 8
  score_band: thin
  score_composite: 31.0
  shared: 3
- slug: gridpoint
  name: GridPoint
  description: GridPoint is a Reston, Virginia clean-technology company, founded in 2003, that builds energy management and sustainability systems for commercial buildings, enterprises and government agencies. It combines its own edge hardware — EC2000 a…
  api_count: 0
  score_band: thin
  score_composite: 28.5
  shared: 3
- slug: infinitum
  name: Infinitum
  description: Infinitum (formerly Infinitum Electric) is an Austin, Texas motor manufacturer, founded in 2016 by Ben Schuler, that builds the Aircore EC+ family of air-core printed-circuit-board (PCB) stator electric motors along with integrated fan and…
  api_count: 1
  score_band: emerging
  score_composite: 19.2
  shared: 3
- slug: control4
  name: Control4
  description: Control4 is a smart home and building automation platform, now part of Snap One / ADI Global (Resideo), headquartered in Salt Lake City, Utah. It unifies control of lighting, audio/video, home theater, climate, security, shades, and voice…
  api_count: 0
  score_band: emerging
  score_composite: 14.1
  shared: 3
- slug: universal-electronics
  name: Universal Electronics
  description: Universal Electronics Inc. (UEI) is a global leader in universal control and sensing technologies for the smart home, known for its QuickSet software platform, UEI TIDE smart thermostats and sensors, the Nevo white-label control platform,…
  api_count: 0
  score_band: emerging
  score_composite: 13.8
  shared: 3
- slug: green-fusion
  name: Green Fusion
  description: Green Fusion GmbH is a Berlin-based climate-energy software company that provides an intelligent 360-degree energy management platform for the residential real estate sector (Wohnungswirtschaft). Its software digitizes and optimizes buildi…
  api_count: 0
  score_band: minimal
  score_composite: 9.0
  shared: 3
- slug: 500nettechnologycoltd
  name: 500net Technology Co., Ltd.
  description: 500net Technology Co., Ltd. (五百戶科技股份有限公司) is a Taipei-based systems integrator, founded in 2004, that combines telecommunications integration, electromechanical engineering, hardware design and custom software development into smart-buildi…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: comfort-systems-usa
  name: Comfort Systems USA
  description: 'Comfort Systems USA (NYSE: FIX) is a Houston-based mechanical, electrical and plumbing contractor — one of the largest in the United States — that installs, services and maintains HVAC, piping, electrical and building-automation systems fo…'
  api_count: 0
  score_band: minimal
  score_composite: 4.9
  shared: 3
- slug: altotech-global
  name: AltoTech Global
  description: AltoTech Global is a Bangkok-based energy-management technology company building an AI and IoT (AIoT) platform that optimizes energy consumption and reduces carbon emissions across smart buildings. Its Alto CERO air-side and water-side pro…
  api_count: 0
  score_band: minimal
  score_composite: 4.7
  shared: 3
- slug: allegion
  name: Allegion
  description: Allegion plc is a global security products company with $3.8B in 2024 revenue, 13,000+ employees, and 30+ brands across 120 countries (Schlage, Von Duprin, LCN, CISA, Steelcraft, Interflex, SimonsVoss, Yonomi). The Allegion Developer Porta…
  api_count: 2
  score_band: strong
  score_composite: 58.9
  shared: 2
- slug: clevergy
  name: Clevergy
  description: Clevergy (The Clevergy Solution, SL) is a Madrid-based climate-tech SaaS company, founded in 2022, that sells white-label energy-management software to electricity and gas retailers, solar installers and energy advisors. Its platform inges…
  api_count: 1
  score_band: developing
  score_composite: 54.2
  shared: 2
- slug: lunar-energy
  name: Lunar Energy
  description: Lunar Energy is a Mountain View, California-based residential clean-energy company founded in August 2020 by former Tesla Energy executive Kunal Girotra. The company designs and manufactures the Lunar System — a modular home battery (15–30…
  api_count: 2
  score_band: developing
  score_composite: 53.5
  shared: 2
- slug: sense
  name: Sense
  description: Sense is a ClimateTech company founded in 2013 that provides home energy intelligence through a high-resolution electrical monitoring device installed in residential electrical panels. The Sense platform captures real-time electricity usag…
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: ring
  name: Ring
  description: Ring is an Amazon home-security company (doorbells, cameras, alarm systems, and the Ring Protect subscription) that in 2026 launched the Ring Developer platform and Ring Appstore. Third-party developers can build video-powered apps against…
  api_count: 1
  score_band: developing
  score_composite: 42.3
  shared: 2
- slug: butterflymx
  name: ButterflyMX
  description: ButterflyMX is a property-access technology company whose smart video intercoms, keypads, smart locks, elevator controls, vehicle-access readers, package rooms and front-desk stations are installed in more than 20,000 multifamily, commerci…
  api_count: 2
  score_band: developing
  score_composite: 42.0
  shared: 2
- slug: viridi-parente
  name: Viridi
  description: Viridi (Viridi Parente, Inc.) is a Buffalo, New York manufacturer of fail-safe, modular lithium-ion battery energy storage systems (RPS150, RPS50, RPSLink IN/EX, SBR30, FAVEO and the 1.2 MWh series) built around its Anti-Propagation techno…
  api_count: 2
  score_band: developing
  score_composite: 41.6
  shared: 2
---
