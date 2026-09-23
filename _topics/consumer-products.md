---
layout: topic
slug: consumer-products
name: Consumer Products
kind: topic
description: Industry-vertical index of APIs, data sources, syndication networks, and product information management (PIM) platforms that power the consumer packaged goods (CPG) and consumer products ecosystem. Catalogs corporate developer surfaces from large CPG manufacturers (P&G, Unilever, Nestle, Coca-Cola, PepsiCo, Mondelez, Kimberly-Clark, Colgate-Palmolive), product-identifier registries (GS1 Digital Link, GTIN/UPC lookup), open product databases (Open Food Facts, Open Beauty Facts), commercial syndication networks (Salsify, Syndigo, 1WorldSync), and PIM platforms (Akeneo, Pimcore, Plytix, Sales Layer).
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/consumer-products.png
tags:
- Consumer Products
- CPG
- Product Data
- Retail
- GTIN
- Barcodes
- Product Catalog
- Product Information Management
- Syndication
- Schema.org Product
repo: https://github.com/api-evangelist/consumer-products
api_count: 18
apis:
- name: GS1 Digital Link
  description: GS1 Digital Link is the global standard that turns GS1 identifiers (GTINs, SSCCs, GLNs) into web URIs so a single barcode or QR code can connect to multiple sources of brand, regulatory, supply chain, and consumer information. It is the co…
  url: https://www.gs1.org/standards/gs1-digital-link
- name: Open Food Facts
  description: Open Food Facts is a collaborative, free, open database of food products from around the world maintained by a global community of contributors. Its REST API exposes ingredients, nutrition facts, additives, allergens, Nutri-Score, NOVA gro…
  url: https://world.openfoodfacts.org/
- name: Open Beauty Facts
  description: Open Beauty Facts is the Open Food Facts sister project covering cosmetics and personal care products. The same REST shape exposes ingredients (INCI), labels, packaging, and brand metadata for beauty products contributed by a global commun…
  url: https://world.openbeautyfacts.org/
- name: Procter & Gamble (P&G) Brands
  description: Procter & Gamble is the world's largest CPG company by revenue, operating ten product categories across Beauty, Grooming, Health Care, Fabric & Home Care, and Baby, Feminine & Family Care. P&G does not publish a public consumer-facing deve…
  url: https://us.pg.com/brands/
- name: Unilever Brands
  description: Unilever is a multinational CPG company with more than 400 brands across Beauty & Wellbeing, Personal Care, Home Care, Nutrition, and Ice Cream. Public APIs are not consolidated under a single developer portal; integrations run through ret…
  url: https://www.unilever.com/brands/
- name: Nestle Brands
  description: Nestle is the world's largest food and beverage company with more than 2,000 brands across Beverages, Dairy, Confectionery, Nutrition, Pet Care, and Prepared Dishes. Like other large CPGs, Nestle has no public unified developer portal; pro…
  url: https://www.nestle.com/brands
- name: The Coca-Cola Company
  description: The Coca-Cola Company manufactures more than 200 brands across sparkling soft drinks, water, sports drinks, juice, tea, coffee, and plant-based beverages. Public developer surfaces are limited to the Coca-Cola Freestyle dispenser ecosystem…
  url: https://www.coca-colacompany.com/brands
- name: PepsiCo Brands
  description: PepsiCo operates a portfolio of 22 billion-dollar brands spanning Beverages (Pepsi, Gatorade, Tropicana, Lipton, Bubly) and Convenient Foods (Lay's, Doritos, Cheetos, Quaker, SodaStream). Developer integration occurs through PepsiCo Partne…
  url: https://www.pepsico.com/brands
- name: Mondelez International
  description: Mondelez International is the global snacks leader with billion-dollar brands including Oreo, Cadbury, Milka, Toblerone, Ritz, Trident, and Halls. Public-facing developer assets are limited; retail master data flows through 1WorldSync and…
  url: https://www.mondelezinternational.com/snack-brands
- name: Kimberly-Clark Brands
  description: Kimberly-Clark is a personal-care CPG making essentials in Family Care, Personal Care, and K-C Professional. Brands include Huggies, Kleenex, Scott, Cottonelle, Kotex, Depend, and Poise. Like its CPG peers, Kimberly-Clark does not publish…
  url: https://www.kimberly-clark.com/en-us/brands
- name: Colgate-Palmolive Brands
  description: Colgate-Palmolive is a global CPG focused on Oral Care, Personal Care, Home Care, and Pet Nutrition (Hill's). Lead brands include Colgate, Tom's of Maine, Palmolive, Speed Stick, Softsoap, Ajax, Murphy Oil Soap, and Hill's Science Diet / P…
  url: https://www.colgatepalmolive.com/en-us/brands
- name: Salsify Product Experience Cloud
  description: Salsify is a Product Experience Management (PXM) platform that combines PIM, digital asset management, syndication, and digital shelf analytics. Salsify's REST APIs let brands centralize product content and syndicate it to thousands of ret…
  url: https://developers.salsify.com/
- name: Syndigo Content Experience Hub
  description: Syndigo is a Master Data Management (MDM), PIM, and content syndication network that distributes product, location, and digital asset data to retailers and recipients across grocery, hardlines, foodservice, and healthcare. Syndigo APIs cov…
  url: https://www.syndigo.com/
- name: 1WorldSync GDSN
  description: 1WorldSync is the largest GS1-certified Global Data Synchronization Network (GDSN) data pool, operating the Content1 platform for product content management and syndication. Brands publish master data once and synchronize it with subscribi…
  url: https://www.1worldsync.com/
- name: Akeneo Product Cloud
  description: Akeneo is an open-source-rooted Product Information Management (PIM) platform. Its REST API exposes products, product models, families, attributes, categories, channels, locales, reference entities, and assets, enabling integration with e-…
  url: https://api.akeneo.com/
- name: Pimcore Platform
  description: Pimcore is an open-source Digital Experience Platform combining PIM, MDM, DAM, CDP, and DXP capabilities. Pimcore exposes both REST and GraphQL APIs (the Datahub) for product data, classification stores, object bricks, assets, documents, a…
  url: https://pimcore.com/
- name: Plytix PIM
  description: Plytix is a SaaS Product Information Management platform aimed at mid-market brands, with channel syndication, brand portals, and a public REST API for products, variants, attributes, categories, assets, and relationships, used to feed mar…
  url: https://help.plytix.com/en/api
- name: Sales Layer PIM
  description: Sales Layer is a cloud PIM platform with REST API access to product catalogs, attribute schemas, categories, media, related products, and syndication channels. It connects brands and retailers across marketplaces, e-commerce platforms, and…
  url: https://docs.saleslayer.com/
links:
- type: IssueTracker
  url: https://github.com/gs1/GS1DigitalLinkToolkit.js/issues
- type: DomainSecurity
  url: https://github.com/api-evangelist/consumer-products/blob/main/security/consumer-products-domain-security.yml
- type: Website
  url: https://github.com/api-evangelist/consumer-products
- type: GitHubOrganization
  url: https://github.com/api-evangelist
- type: Standards
  url: https://www.gs1.org/standards
- type: Standards
  url: https://schema.org/Product
- type: OpenData
  url: https://world.openfoodfacts.org/data
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-schema/consumer-product-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-schema/product-identifier-schema.json
- type: JSONSchema
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-schema/nutrition-facts-schema.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-structure/consumer-product-structure.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-structure/product-identifier-structure.json
- type: JSONStructure
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-structure/nutrition-facts-structure.json
- type: JSONLD
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/json-ld/consumer-products-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/vocabulary/consumer-products-vocabulary.yml
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/examples/consumer-product-food-example.json
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/examples/consumer-product-beauty-example.json
- type: Examples
  url: https://raw.githubusercontent.com/api-evangelist/consumer-products/refs/heads/main/examples/consumer-product-household-example.json
provider_count: 66
providers:
- slug: salsify
  name: Salsify
  description: Salsify is a product experience management (PXM) and supplier experience management (SXM) platform used by brands, distributors and retailers to centralize product content, digital assets and syndication to the digital shelf. The Salsify p…
  api_count: 3
  score_band: strong
  score_composite: 56.1
  shared: 3
- slug: 1worldsync
  name: 1WorldSync
  description: 1WorldSync is the leading product content network and a GS1-certified GDSN data pool, helping consumer goods brands, manufacturers, and retailers create, manage, syndicate, and verify trusted product content across the digital shelf and th…
  api_count: 1
  score_band: developing
  score_composite: 49.8
  shared: 3
- slug: powerreviews
  name: PowerReviews
  description: PowerReviews provides ratings and reviews software and APIs for collecting, syndicating, and displaying user-generated reviews, questions, and answers so shoppers can make better purchase decisions and retailers and brands can drive e-comm…
  api_count: 4
  score_band: developing
  score_composite: 47.5
  shared: 3
- slug: akeneo
  name: Akeneo
  description: Akeneo is a Product Information Management (PIM) platform that centralizes, enriches, and distributes product data across digital commerce channels, enabling brands, retailers, and manufacturers to deliver consistent product experiences. T…
  api_count: 1
  score_band: thin
  score_composite: 32.3
  shared: 3
- slug: colgate-palmolive
  name: Colgate-Palmolive
  description: Colgate-Palmolive Company is a global consumer-products manufacturer operating in oral care, personal care, home care, and pet nutrition through brands such as Colgate, Palmolive, Hill's Pet Nutrition, Speed Stick, Ajax, and Softsoap. Colg…
  api_count: 0
  score_band: emerging
  score_composite: 13.6
  shared: 3
- slug: noviconnect
  name: Novi Connect
  description: Novi Connect (Novi) is an AI shopping optimization platform and data infrastructure for CPG and retail brands. It connects brands, certification bodies, and major retailers to verify, standardize, and distribute product data so products ar…
  api_count: 0
  score_band: minimal
  score_composite: 9.8
  shared: 3
- slug: alkemics
  name: Alkemics
  description: Alkemics was a French SaaS company founded in 2011 in Paris that operated a collaborative commerce platform connecting consumer packaged goods (CPG) brands and retailers to share, enrich, and distribute product content and data across the…
  api_count: 0
  score_band: minimal
  score_composite: 8.3
  shared: 3
- slug: green-thumb-industries
  name: Green Thumb Industries
  description: A leading U.S. cannabis consumer packaged goods company operating a nationwide portfolio of retail dispensaries under the RISE brand and a collection of cannabis brands. Operates manufacturing facilities and retail locations across multipl…
  api_count: 0
  score_band: minimal
  score_composite: 7.7
  shared: 3
- slug: open-food-facts
  name: Open Food Facts
  description: Open Food Facts is a collaborative, free and open database of food products from around the world, built by everyone for everyone. Anyone can scan a barcode and contribute product data, and the whole database is published under the Open Da…
  api_count: 1
  score_band: strong
  score_composite: 63.3
  shared: 2
- slug: bazaarvoice
  name: Bazaarvoice
  description: Bazaarvoice operates a retail and brand user-generated-content network that collects, moderates, syndicates and now makes machine-discoverable the ratings, reviews, questions and answers, and visual content published across thousands of br…
  api_count: 23
  score_band: strong
  score_composite: 61.3
  shared: 2
- slug: erply
  name: Erply
  description: Erply is a cloud-based retail management platform providing point-of-sale (POS), inventory and warehouse management, product information management (PIM), CRM, sales reporting and ecommerce integrations for retailers running one or more st…
  api_count: 4
  score_band: strong
  score_composite: 59.0
  shared: 2
- slug: back-market
  name: Back Market
  description: Back Market is a French-founded global online marketplace dedicated exclusively to refurbished consumer electronics — smartphones, laptops, tablets, consoles, watches, audio and home appliances — operating across 17 countries on three regi…
  api_count: 1
  score_band: developing
  score_composite: 53.7
  shared: 2
- slug: channable
  name: Channable
  description: Channable is a feed management and marketplace integration platform that helps online retailers, brands, and agencies optimize, distribute, and advertise their product data across more than 2,500 marketing channels, price comparison sites,…
  api_count: 1
  score_band: developing
  score_composite: 50.2
  shared: 2
- slug: treez
  name: Treez
  description: Treez is an enterprise cloud commerce platform for US cannabis retail, providing dispensary point-of-sale, retail analytics, cashless payments, ecommerce and loyalty to high-volume operators across the largest legal state markets. Its publ…
  api_count: 13
  score_band: developing
  score_composite: 46.0
  shared: 2
- slug: fabric-com
  name: fabric
  description: fabric is a composable, headless commerce platform. Its API covers catalog and product information management, pricing and promotions, cart and checkout, orders and order management, inventory, customers and addresses, and returns and appe…
  api_count: 16
  score_band: developing
  score_composite: 44.8
  shared: 2
- slug: smarter-sorting
  name: Smarter Sorting
  description: Smarter Sorting (which rebranded as SmarterX in 2023 and now operates as part of Syndigo) is an Austin, Texas product-intelligence and regulatory-classification company serving retailers, consumer-goods brands and the logistics industry. I…
  api_count: 2
  score_band: developing
  score_composite: 44.7
  shared: 2
- slug: coldsnap
  name: ColdSnap
  description: ColdSnap (formerly Sigma Phase, Corp.) is a Billerica, Massachusetts hardware and frozen-confection company founded in October 2018 by Matt Fonte, whose plug-and-play countertop appliance chills and churns a single serving of premium ice c…
  api_count: 3
  score_band: developing
  score_composite: 43.4
  shared: 2
- slug: lily-ai
  name: Lily AI
  description: Lily AI, Inc. is a retail product-intelligence company whose platform, Lily Max, enriches e-commerce product catalogs so that products are legible to advertising platforms, search engines, onsite search, and AI shopping agents. Agents iden…
  api_count: 2
  score_band: developing
  score_composite: 39.7
  shared: 2
- slug: kroger
  name: Kroger
  description: The Kroger Co. is the largest supermarket operator in the United States and runs a two-tier developer programme from developer.kroger.com. The Public tier is self-service after account and application registration and covers Products, Loca…
  api_count: 14
  score_band: developing
  score_composite: 39.5
  shared: 2
- slug: maison-safqa-holdings-limited
  name: Maison Safqa Holdings Limited
  description: Maison Safqa Holdings Limited operates Maison Safqa, a members-only luxury flash-sale marketplace (built on Shopify) offering exclusive time-limited sales on high-end brands. For its partner brands it publishes the Maison Safqa Brand Devel…
  api_count: 1
  score_band: thin
  score_composite: 39.1
  shared: 2
- slug: tecovas
  name: Tecovas
  description: Tecovas is an Austin, Texas direct-to-consumer Western wear brand selling handcrafted cowboy boots, work boots, hats, leather goods and apparel for men, women and kids, made by artisans in Leon, Mexico and sold online and through its own U…
  api_count: 3
  score_band: thin
  score_composite: 35.9
  shared: 2
- slug: venzee
  name: Venzee
  description: Venzee is a product data syndication and Product Information Management (PIM) platform for ecommerce brands, manufacturers, and distributors, now operating as Jasper PIM (JasperX) with a channel connector ecosystem powered by Venzee's MESH…
  api_count: 1
  score_band: thin
  score_composite: 35.0
  shared: 2
- slug: bybe
  name: BYBE
  description: BYBE, Inc. is a promotion platform for the beer, wine, and spirits industry, connecting alcohol beverage brands, retailers, and consumers through digital cash-back rebates. Brands fund offers in the BYBE dashboard; retailers embed those of…
  api_count: 1
  score_band: thin
  score_composite: 34.6
  shared: 2
- slug: therabody
  name: Therabody
  description: Therabody is a Los Angeles-based wellness technology company founded in 2016 by Dr. Jason Wersland, best known for inventing the Theragun percussive therapy device. Its product ecosystem spans percussive therapy (Theragun), pneumatic compr…
  api_count: 3
  score_band: thin
  score_composite: 34.1
  shared: 2
- slug: circana
  name: Circana
  description: Circana (formerly IRI and The NPD Group) is the leading advisor on the complexity of consumer behavior, providing data-driven insights, analytics, and technology solutions that help almost 7,000 brands and retailers understand and predict…
  api_count: 20
  score_band: thin
  score_composite: 33.4
  shared: 2
- slug: madeiramadeira
  name: Madeiramadeira
  description: MadeiraMadeira (MadeiraMadeira Comercio Eletronico S/A, Curitiba, Parana) is one of Brazil's largest online retailers and marketplaces for home goods - furniture, decor, appliances, building materials, bathroom and kitchen fixtures, and pl…
  api_count: 7
  score_band: thin
  score_composite: 33.4
  shared: 2
- slug: ikea
  name: IKEA
  description: A Swedish multinational furniture and home goods retailer known for its affordable, ready-to-assemble products. Operates hundreds of stores worldwide and is the world's largest furniture retailer with a distinctive showroom-based shopping…
  api_count: 4
  score_band: thin
  score_composite: 33.3
  shared: 2
- slug: flipp-wishabi
  name: Flipp (Wishabi)
  description: Flipp (operated by Wishabi) is a Toronto-based retail media and digital merchandising company that connects retailers, brands, and consumers through shoppable digital experiences. Its consumer app aggregates weekly digital flyers, coupons,…
  api_count: 2
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: ibotta
  name: Ibotta
  description: 'Ibotta is a Denver-based consumer technology company (NYSE: IBTA) that operates a cash-back rewards platform and the Ibotta Performance Network (IPN), a digital promotions and retail-media network. Consumers earn real cash back on everyday…'
  api_count: 2
  score_band: thin
  score_composite: 31.0
  shared: 2
- slug: zentail
  name: Zentail
  description: Zentail is a multichannel ecommerce platform that helps brands and retailers manage product listings, inventory, pricing, and orders across marketplaces like Amazon, Walmart, Target Plus, eBay, Shopify, BigCommerce, and Newegg from a singl…
  api_count: 1
  score_band: thin
  score_composite: 30.5
  shared: 2
---
