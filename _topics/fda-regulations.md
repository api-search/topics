---
layout: topic
slug: fda-regulations
name: FDA Regulations
kind: topic
description: 'FDA Regulations is the body of federal rules the U.S. Food and Drug Administration enforces over the safety, efficacy and security of food, human and animal drugs, biologics, medical devices, cosmetics and tobacco products — codified at 21 CFR and administered through the agency''s inspection, citation, import and compliance-action programs. The machine-readable surface for that regulatory activity is the FDA Data Dashboard API (DDAPI), published by the FDA Office of Inspections and Investigations (formerly the Office of Regulatory Affairs), which serves the same inspection classification, inspection citation, import refusal and compliance action datasets that power the public Data Dashboard. Access is credentialed: FDA issues an Authorization-User / Authorization-Key header pair on request, and every endpoint is a POST search over a single dataset with JSON filters, column projection, sorting and offset paging.'
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/fda-regulations.png
tags:
- Regulatory Compliance
- Healthcare
- Medical Devices
- Pharmaceuticals
- Food Safety
- Inspection
- Enforcement
- Federal-Government
- Public Data
- Import
repo: https://github.com/api-evangelist/fda-regulations
api_count: 1
apis:
- name: FDA Regulations FDA Data Dashboard API
  description: The FDA Data Dashboard API API from FDA Regulations — 4 operation(s) for fda data dashboard api.
  url: https://datadashboard.fda.gov/oii/api/index.htm
links:
- type: AgenticAccess
  url: https://github.com/api-evangelist/fda-regulations/blob/main/agentic-access/fda-regulations-agentic-access.yml
- type: AgentSkill
  url: https://github.com/api-evangelist/fda-regulations/blob/main/skills/_index.yml
- type: APIReference
  url: https://datadashboard.fda.gov/oii/api/index.htm#section-endpoints
- type: Authentication
  url: https://github.com/api-evangelist/fda-regulations/blob/main/authentication/fda-regulations-authentication.yml
- type: Conformance
  url: https://github.com/api-evangelist/fda-regulations/blob/main/conformance/fda-regulations-conformance.yml
- type: Conventions
  url: https://github.com/api-evangelist/fda-regulations/blob/main/conventions/fda-regulations-conventions.yml
- type: DataModel
  url: https://github.com/api-evangelist/fda-regulations/blob/main/data-model/fda-regulations-data-model.yml
- type: DeveloperPortal
  url: https://datadashboard.fda.gov/oii/api/index.htm
- type: Documentation
  url: https://datadashboard.fda.gov/oii/api/index.htm
- type: DomainSecurity
  url: https://github.com/api-evangelist/fda-regulations/blob/main/security/fda-regulations-domain-security.yml
- type: ErrorCatalog
  url: https://github.com/api-evangelist/fda-regulations/blob/main/errors/fda-regulations-error-codes.yml
- type: Examples
  url: https://github.com/api-evangelist/fda-regulations/blob/main/examples/fda-regulations-examples.yml
- type: GettingStarted
  url: https://datadashboard.fda.gov/oii/api/index.htm#section-usage
- type: GitHubOrganization
  url: https://github.com/FDA
- type: Lifecycle
  url: https://github.com/api-evangelist/fda-regulations/blob/main/lifecycle/fda-regulations-lifecycle.yml
- type: LLMsTxt
  url: https://github.com/api-evangelist/fda-regulations/blob/main/llms/fda-regulations-llms.txt
- type: OpenAPI
  url: https://github.com/api-evangelist/fda-regulations/blob/main/openapi/_original/fda-regulations-data-dashboard-openapi.yml
- type: Overlay
  url: https://github.com/api-evangelist/fda-regulations/blob/main/overlays/fda-regulations-data-dashboard-overlay.yaml
- type: Packages
  url: https://github.com/api-evangelist/fda-regulations/blob/main/packages/fda-regulations-packages.yml
- type: Plans
  url: https://github.com/api-evangelist/fda-regulations/blob/main/plans/fda-regulations-plans-pricing.yml
- type: PrivacyPolicy
  url: https://www.fda.gov/about-fda/about-website/website-policies
- type: RateLimits
  url: https://github.com/api-evangelist/fda-regulations/blob/main/rate-limits/fda-regulations-rate-limits.yml
- type: Sandbox
  url: https://datadashboard.fda.gov/oii/api/index.htm#section-try
- type: Support
  url: https://github.com/api-evangelist/fda-regulations/blob/main/mailto:FDADataDashboard@fda.hhs.gov
- type: TermsOfService
  url: https://www.fda.gov/about-fda/about-website/website-policies
- type: Website
  url: https://www.fda.gov/regulatory-information/laws-enforced-fda
- type: X-MCPServerCandidate
  url: https://github.com/api-evangelist/fda-regulations/blob/main/mcp/fda-regulations-mcp.yml
- type: X-WellKnownProbe
  url: https://github.com/api-evangelist/fda-regulations/blob/main/well-known/fda-regulations-well-known.yml
provider_count: 581
providers:
- slug: food-and-drug-administration
  name: Food and Drug Administration
  description: openFDA is an Elasticsearch-based public API that serves FDA data on drugs, devices, foods, animal/veterinary products, and tobacco. Each noun exposes one or more datasets including adverse events, recall enforcement reports, product label…
  api_count: 1
  score_band: thin
  score_composite: 33.6
  shared: 3
- slug: johnson-and-johnson
  name: Johnson & Johnson
  description: Johnson & Johnson is a multinational pharmaceutical and medical devices corporation. Operating today as Johnson & Johnson Innovative Medicine and MedTech, J&J has historically connected health platforms and APIs through subsidiaries such a…
  api_count: 1
  score_band: thin
  score_composite: 27.4
  shared: 3
- slug: food-safety-and-inspection-service
  name: Food Safety and Inspection Service
  description: The Food Safety and Inspection Service (FSIS) is a branch of the United States Department of Agriculture (USDA) responsible for ensuring the safety of the nation's commercial supply of meat, poultry, and egg products. FSIS publishes a Reca…
  api_count: 1
  score_band: emerging
  score_composite: 20.9
  shared: 3
- slug: acto
  name: ACTO
  description: ACTO is a Toronto-headquartered Life Sciences software company whose Intelligent Field Excellence (IFE) platform prepares biopharmaceutical, biotech and medtech commercial and medical field teams for healthcare-provider conversations. The…
  api_count: 0
  score_band: emerging
  score_composite: 18.8
  shared: 3
- slug: gan-and-lee-pharmaceuticals
  name: Gan & Lee Pharmaceuticals
  description: 'Gan & Lee Pharmaceuticals (Shanghai Stock Exchange: 603087) is a Chinese biopharmaceutical company founded in 1998, specializing in the research, development, production, and commercialization of recombinant insulin analogs and injection d…'
  api_count: 0
  score_band: minimal
  score_composite: 10.0
  shared: 3
- slug: via-global-health
  name: Via Global Health
  description: Via Global Health (VIA Global Health) is a medical equipment and pharmaceutical supplier serving distributors, healthcare providers, and NGOs across Africa, Asia, and Latin America. The company sources quality diagnostic equipment, surgica…
  api_count: 0
  score_band: minimal
  score_composite: 7.9
  shared: 3
- slug: rakuten-medical
  name: Rakuten Medical
  description: Rakuten Medical, Inc. is a global biotechnology company headquartered in San Diego, California, developing precision, cell-targeting investigational cancer therapies on its proprietary Alluminox platform — a drug-device combination pairing…
  api_count: 0
  score_band: minimal
  score_composite: 7.6
  shared: 3
- slug: panacea
  name: Panacea
  description: Panacea is an AI-native FDA regulatory services firm (Y Combinator Spring 2026, operating as withpanacea.com) that pairs experienced ex-FDA regulatory consultants with a proprietary AI platform to accelerate medical device and pharmaceutic…
  api_count: 0
  score_band: minimal
  score_composite: 4.3
  shared: 3
- slug: zurex-pharma
  name: Zurex Pharma
  description: Zurex Pharma, Inc. is a privately held specialty pharmaceutical and medical technology company founded in 2008 and headquartered in Middleton, Wisconsin, developing a portfolio of patented antimicrobial formulations intended to prevent hea…
  api_count: 0
  score_band: minimal
  score_composite: 2.9
  shared: 3
- slug: hospira
  name: Hospira
  description: Hospira was a global specialty pharmaceutical and medication delivery company providing injectable drugs and infusion technologies before being acquired by Pfizer in 2015. No public APIs are offered under the Hospira brand.
  api_count: 0
  score_band: minimal
  score_composite: 2.4
  shared: 3
- slug: vascular-therapies
  name: Vascular Therapies
  description: Vascular Therapies, Inc. is a privately held, clinical-stage biopharmaceutical company headquartered in Cresskill, New Jersey, developing Sirogen, a proprietary sirolimus formulation delivered from a bioabsorbable collagen implant placed p…
  api_count: 0
  score_band: minimal
  score_composite: 1.8
  shared: 3
- slug: cms
  name: Centers for Medicare and Medicaid Services
  description: The Centers for Medicare and Medicaid Services (CMS) provides a suite of public REST APIs enabling developers to access Medicare provider data, quality measures, drug spending, health plan finder, beneficiary claims, and public health insu…
  api_count: 4
  score_band: exemplar
  score_composite: 81.7
  shared: 2
- slug: veeva
  name: Veeva
  description: Veeva Systems is the leading cloud software provider for the global life sciences industry, serving pharmaceutical, biotechnology, medical device and CRO customers across commercial, clinical, quality, regulatory, medical and safety operat…
  api_count: 1
  score_band: exemplar
  score_composite: 75.6
  shared: 2
- slug: autoderm-ai-dermatology-api
  name: Autoderm – AI Dermatology API
  description: Autoderm is a white-label REST API for AI-assisted analysis of dermatological images, operated as a regulated medical device. A client POSTs a single skin photograph as multipart/form-data and receives the top five most probable conditions…
  api_count: 2
  score_band: strong
  score_composite: 63.5
  shared: 2
- slug: athelas
  name: Athelas
  description: Athelas (Commure d/b/a Athelas) is a healthcare technology company building AI-powered infrastructure for provider organizations, spanning remote patient monitoring (RPM), an AI-native EHR ("Air"), ambient AI scribing, and revenue cycle ma…
  api_count: 1
  score_band: developing
  score_composite: 53.6
  shared: 2
- slug: cancer-gov
  name: Cancer.gov
  description: Cancer.gov is the web presence of the National Cancer Institute (NCI), the U.S. federal government's principal agency for cancer research and training. NCI and its partner programs expose a rich set of open APIs covering cancer clinical tr…
  api_count: 17
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
- slug: centers-for-disease-control-and-prevention
  name: Centers for Disease Control and Prevention
  description: The Centers for Disease Control and Prevention (CDC) is the United States' national public health agency, part of the Department of Health and Human Services. CDC operates a broad portfolio of free, anonymously callable public APIs and ope…
  api_count: 3
  score_band: developing
  score_composite: 47.3
  shared: 2
- slug: open-fda
  name: openFDA
  description: openFDA is the FDA's open data platform providing REST APIs for public access to FDA regulatory datasets. It covers drug adverse events (FAERS), drug labeling (SPL), drug recall enforcement reports, medical device 510(k) clearances, device…
  api_count: 17
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: roivant-sciences
  name: Roivant Sciences
  description: 'Roivant Sciences (Nasdaq: ROIV) is a holding company that builds focused subsidiary biotech and health-tech operating units called "Vants." Founded by Vivek Ramaswamy in 2014 and now led by CEO Matt Gline, Roivant has launched companies ac…'
  api_count: 1
  score_band: developing
  score_composite: 45.7
  shared: 2
- slug: biogen
  name: Biogen
  description: Biogen is a global biotechnology company that discovers, develops, and delivers therapies for people living with serious neurological diseases including multiple sclerosis, Alzheimer's, and spinal muscular atrophy.
  api_count: 1
  score_band: developing
  score_composite: 43.0
  shared: 2
- slug: eko-health
  name: Eko Health
  description: Eko Health Inc. is an Oakland, California digital health company that builds FDA-cleared digital stethoscopes (CORE 500, CORE Digital Attachment, DUO, and the 3M Littmann CORE) together with cloud software and AI algorithms for the detecti…
  api_count: 2
  score_band: developing
  score_composite: 41.7
  shared: 2
- slug: dexcom
  name: Dexcom
  description: Dexcom is a leading medical device company that develops, manufactures, and distributes continuous glucose monitoring (CGM) systems for people with diabetes. The company's wearable sensors stream real-time glucose data to mobile apps, dedi…
  api_count: 7
  score_band: developing
  score_composite: 41.4
  shared: 2
- slug: substance-abuse-and-mental-health-services-administration
  name: Substance Abuse and Mental Health Services Administration
  description: The Substance Abuse and Mental Health Services Administration (SAMHSA) is a branch of the U.S. Department of Health and Human Services dedicated to improving the quality and availability of prevention, treatment, and recovery support servi…
  api_count: 1
  score_band: developing
  score_composite: 41.3
  shared: 2
- slug: usda
  name: USDA
  description: The US Department of Agriculture provides a suite of free public REST APIs covering agricultural statistics, food and nutrition data, market news, food safety inspection records, crop and vegetation monitoring, and geospatial services. API…
  api_count: 1
  score_band: developing
  score_composite: 41.3
  shared: 2
- slug: empatica
  name: Empatica
  description: Empatica Inc. is an MIT Media Lab spinoff, founded in Cambridge, Massachusetts, that builds FDA-cleared medical wearables — EmbracePlus, EmbraceMini and the EpiMonitor epilepsy monitoring system — together with the Empatica Health Monitori…
  api_count: 3
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: united-states-national-library-of-medicine
  name: United States National Library of Medicine
  description: The United States National Library of Medicine (NLM) is the world's largest biomedical library. It serves as a vital resource for researchers, healthcare professionals, and the general public by providing access to a vast collection of bio…
  api_count: 4
  score_band: thin
  score_composite: 39.2
  shared: 2
- slug: doceree
  name: Doceree
  description: Doceree Inc. is a US healthcare marketing technology company (Short Hills, New Jersey) operating a global network of physician-only platforms for programmatic messaging and point-of-care advertising to healthcare professionals. Its platfor…
  api_count: 3
  score_band: thin
  score_composite: 38.4
  shared: 2
- slug: xrhealth
  name: XRHealth
  description: XRHealth is an extended-reality (XR) therapeutics and virtual-clinic company, founded in 2016 with offices in Boston, Massachusetts and Tel Aviv, Israel, that delivers FDA-registered and CE-marked virtual and augmented reality treatment fo…
  api_count: 2
  score_band: thin
  score_composite: 37.8
  shared: 2
- slug: united-states-department-of-agriculture
  name: United States Department of Agriculture
  description: The United States Department of Agriculture (USDA) is a federal agency responsible for developing and executing policies related to farming, agriculture, forestry, and food. The USDA works to ensure the sustainability and safety of America…
  api_count: 4
  score_band: thin
  score_composite: 37.7
  shared: 2
---
