---
layout: topic
slug: cybersecurity-standards
name: Cybersecurity Standards
kind: topic
description: Cybersecurity Standards captures the public, machine-readable, and reference frameworks that establish best practices for protecting information systems, networks, software, and data from cyber threats. The landscape is anchored by U.S. National Institute of Standards and Technology (NIST) publications such as the Cybersecurity Framework (CSF) 2.0, SP 800-53 controls, SP 800-171 controls for controlled unclassified information, the Risk Management Framework (RMF), and the Secure Software Development Framework (SSDF SP 800-218); the international ISO/IEC 27001 / 27002 information security management standard family; the Center for Internet Security (CIS) Critical Security Controls and Benchmarks; the OWASP Top 10 and ASVS for application security; PCI DSS for payment data; HITRUST CSF for healthcare; SOC 2 trust services criteria; and FedRAMP / StateRAMP for cloud authorization. This index aggregates authoritative URLs, machine-readable artifacts (e.g., OSCAL), and cross-references
  for organizations building or auditing cybersecurity programs.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cybersecurity-standards.png
tags:
- CIS Controls
- Compliance
- CSF
- Cybersecurity
- FedRAMP
- Framework
- HIPAA
- HITRUST
- Information Security
- ISO 27001
- ISO 27002
- NIST
- NIST 800-171
- NIST 800-218
- NIST 800-53
- OSCAL
- OWASP
- PCI DSS
- Risk Management
- SOC 2
- SSDF
- Standards
repo: https://github.com/api-evangelist/cybersecurity-standards
api_count: 10
apis:
- name: NIST Cybersecurity Framework (CSF) 2.0
  description: The NIST Cybersecurity Framework 2.0 is a voluntary risk-based framework organizing cybersecurity activities into six core functions (Govern, Identify, Protect, Detect, Respond, Recover) with categories and subcategories. NIST publishes in…
  url: https://www.nist.gov/cyberframework
- name: NIST SP 800-53 Security and Privacy Controls
  description: NIST Special Publication 800-53 Revision 5 catalogs security and privacy controls for information systems and organizations. Used as the basis of FedRAMP authorizations and Risk Management Framework implementations. Available in machine-re…
  url: https://csrc.nist.gov/publications/detail/sp/800-53/rev-5/final
- name: NIST SP 800-171 Protecting CUI
  description: NIST SP 800-171 specifies requirements for protecting Controlled Unclassified Information (CUI) in non-federal systems. Forms the basis of CMMC (Cybersecurity Maturity Model Certification) for the U.S. defense industrial base.
  url: https://csrc.nist.gov/publications/detail/sp/800-171/rev-3/final
- name: NIST SP 800-218 Secure Software Development Framework (SSDF)
  description: NIST SP 800-218 defines the Secure Software Development Framework (SSDF), a set of high-level secure-development practices referenced by U.S. Executive Order 14028 and procurement attestations.
  url: https://csrc.nist.gov/publications/detail/sp/800-218/final
- name: ISO/IEC 27001 Information Security Management
  description: ISO/IEC 27001 is the international standard for information security management systems (ISMS). The 2022 revision aligns Annex A controls with the ISO/IEC 27002:2022 catalog. Certification is performed by accredited bodies.
  url: https://www.iso.org/standard/27001
- name: CIS Critical Security Controls and Benchmarks
  description: The Center for Internet Security publishes the Critical Security Controls (currently v8.1) and a library of CIS Benchmarks providing prescriptive secure configuration guidance for OSes, cloud platforms, and applications.
  url: https://www.cisecurity.org/controls
- name: OWASP Top 10 and ASVS
  description: OWASP publishes the Top 10 web application risks, the API Security Top 10, and the Application Security Verification Standard (ASVS) used as a baseline for application security reviews.
  url: https://owasp.org/Top10/
- name: PCI DSS Payment Card Industry Data Security Standard
  description: PCI DSS, maintained by the PCI Security Standards Council, defines requirements for organizations that store, process, or transmit cardholder data. Version 4.0.1 is the current edition.
  url: https://www.pcisecuritystandards.org/
- name: SOC 2 Trust Services Criteria
  description: SOC 2 (System and Organization Controls 2) reports are issued by AICPA-licensed auditors against the Trust Services Criteria (Security, Availability, Processing Integrity, Confidentiality, Privacy). Widely adopted by SaaS vendors.
  url: https://www.aicpa-cima.com/topic/audit-assurance/audit-and-assurance-greater-than-soc-2
- name: FedRAMP Federal Cloud Authorization
  description: The Federal Risk and Authorization Management Program provides a standardized approach for U.S. federal agencies to authorize cloud services, anchored on NIST SP 800-53 baselines.
  url: https://www.fedramp.gov/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/cybersecurity-standards/blob/main/security/cybersecurity-standards-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/cybersecurity-standards/blob/main/security/cybersecurity-standards-domain-security.yml
- type: NIST
  url: https://www.nist.gov/cyberframework
- type: NISTCSRC
  url: https://csrc.nist.gov/
- type: OSCALContent
  url: https://github.com/usnistgov/oscal-content
- type: ISO
  url: https://www.iso.org/standard/27001
- type: CIS
  url: https://www.cisecurity.org/
- type: OWASP
  url: https://owasp.org/
- type: PCI
  url: https://www.pcisecuritystandards.org/
- type: AICPA
  url: https://www.aicpa-cima.com/
- type: FedRAMP
  url: https://www.fedramp.gov/
- type: HITRUST
  url: https://hitrustalliance.net/
provider_count: 197
providers:
- slug: secureframe
  name: Secureframe
  description: Secureframe automates security and privacy compliance for SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, CMMC, FedRAMP, NIST 800-171 and more. Its Public API is a 112-operation, JSON:API-shaped REST contract over the compliance record of truth —…
  api_count: 1
  score_band: strong
  score_composite: 57.1
  shared: 5
- slug: drata
  name: Drata
  description: Drata is a continuous security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, PCI DSS, GDPR, and more, with policies, evidence, and trust center. Drata exposes a public REST API plus the SafeBase Trust API (acquired…
  api_count: 3
  score_band: exemplar
  score_composite: 70.2
  shared: 4
- slug: regscale
  name: RegScale
  description: RegScale is a Continuous Controls Monitoring (CCM) and compliance-automation company whose cloud-native, OSCAL-native GRC platform keeps organizations continuously audit-ready by turning compliance documentation into living, machine-readab…
  api_count: 3
  score_band: developing
  score_composite: 46.5
  shared: 4
- slug: carbide
  name: Carbide
  description: Carbide (carbidesecure.com) is a compliance-automation and risk-management platform that pairs software with credentialed security advisors to help fast-growing organizations achieve and maintain security certifications and regulatory comp…
  api_count: 0
  score_band: emerging
  score_composite: 20.5
  shared: 4
- slug: cleardata
  name: Cleardata
  description: ClearDATA is healthcare's dedicated cloud security, compliance, and operations partner, helping providers, payers, health-tech software companies, medical device makers, and life sciences organizations build and run on AWS, Microsoft Azure…
  api_count: 0
  score_band: emerging
  score_composite: 14.7
  shared: 4
- slug: scytale
  name: Scytale
  description: Scytale is an AI-powered Governance, Risk, and Compliance (GRC) platform that automates security compliance for cloud and SaaS companies. It combines AI agents with in-house compliance experts to automate evidence collection, continuous co…
  api_count: 0
  score_band: emerging
  score_composite: 14.0
  shared: 4
- slug: sprinto
  name: Sprinto
  description: Sprinto is a security and compliance automation platform supporting SOC 2, ISO 27001, HIPAA, GDPR, PCI DSS, and more. Sprinto offers an API for building custom compliance and risk workflows; specific public reference docs are limited and r…
  api_count: 1
  score_band: emerging
  score_composite: 13.3
  shared: 4
- slug: svix
  name: Svix
  description: Svix is an enterprise webhooks-as-a-service platform on the sending side of the webhook market. It provides a single API for delivering reliable, secure, low-latency webhooks at scale, with hosted UIs (Consumer App Portal), a polyglot SDK…
  api_count: 1
  score_band: exemplar
  score_composite: 76.7
  shared: 3
- slug: anecdotes
  name: anecdotes
  description: anecdotes is an enterprise Governance, Risk and Compliance (GRC) platform, founded in 2020 and headquartered in Tel Aviv, that pairs a GRC data engine with AI agents to replace point-in-time audit cycles with continuous, evidence-backed co…
  api_count: 3
  score_band: strong
  score_composite: 64.0
  shared: 3
- slug: viso-trust
  name: VISO Trust
  description: VISO TRUST is an AI-powered third-party risk management (TPRM) platform that helps security teams assess and continuously monitor vendor risk across third, fourth, and nth parties. Its Artifact Intelligence AI engine reads vendor security…
  api_count: 1
  score_band: developing
  score_composite: 50.2
  shared: 3
- slug: vanta
  name: Vanta
  description: Vanta is a trust management platform that automates security compliance for frameworks including SOC 2, ISO 27001, HIPAA, PCI DSS, and GDPR. The Vanta API enables organizations to programmatically manage their compliance posture, automate…
  api_count: 2
  score_band: developing
  score_composite: 48.8
  shared: 3
- slug: formassembly
  name: FormAssembly
  description: FormAssembly is an enterprise form and data collection platform with a REST API for managing forms, exporting submission data, handling Salesforce integrations, and building compliant data collection workflows. The API supports OAuth2 auth…
  api_count: 1
  score_band: developing
  score_composite: 48.5
  shared: 3
- slug: google-cloud-assured-workloads
  name: Google Cloud Assured Workloads
  description: Google Cloud Assured Workloads enables organizations to create and manage compliance-controlled environments on Google Cloud. It provides guardrails for regulatory compliance frameworks such as FedRAMP, HIPAA, CJIS, ITAR, and others by enf…
  api_count: 1
  score_band: developing
  score_composite: 45.6
  shared: 3
- slug: heidi-health
  name: Heidi Health
  description: Heidi Health is a Melbourne, Australia-founded AI care partner for clinicians, founded in 2019 by Dr. Tom Kelly (CEO), Waleed Mussa (CFO), and Yu Liu (CTO). The product began as an ambient AI medical scribe and now spans four capability su…
  api_count: 1
  score_band: developing
  score_composite: 44.6
  shared: 3
- slug: security-scorecard
  name: SecurityScorecard
  description: SecurityScorecard is a cybersecurity ratings and third-party risk management platform that continuously rates the security posture of any company from the outside in, producing an A-F security score across ten risk factors. Its REST API (b…
  api_count: 1
  score_band: developing
  score_composite: 43.8
  shared: 3
- slug: nucleus-security
  name: Nucleus Security
  description: Nucleus Security is a risk-based vulnerability and exposure management platform that unifies findings from across an organization's scanning estate - network, application, cloud, container and penetration-test tooling - into a single norma…
  api_count: 2
  score_band: thin
  score_composite: 35.0
  shared: 3
- slug: cynomi
  name: Cynomi
  description: Cynomi is an AI-powered, automated virtual CISO (vCISO) platform built for MSPs, MSSPs, and cybersecurity consultancies to deliver scalable security and compliance services to their clients. The platform automates risk assessments, generat…
  api_count: 1
  score_band: thin
  score_composite: 28.5
  shared: 3
- slug: thoropass
  name: Thoropass
  description: Thoropass is an auditor-led, AI-powered compliance and audit automation platform that combines software with expert auditor services. Its products span continuous compliance monitoring and alerting, automated evidence collection, a global…
  api_count: 1
  score_band: emerging
  score_composite: 24.7
  shared: 3
- slug: anitian
  name: Anitian
  description: Anitian, Inc. is a Portland, Oregon cloud security and compliance automation company that helps SaaS providers reach and maintain U.S. federal compliance. Its FedFlex platform automates the FedRAMP lifecycle — pre-engineered AWS and Azure…
  api_count: 2
  score_band: emerging
  score_composite: 24.0
  shared: 3
- slug: risk-ledger
  name: Risk Ledger
  description: Risk Ledger is a London-based third-party and supply chain risk management platform that helps organizations assess, monitor, and continuously manage the security risks across their supplier networks. Through its "Active Supply Chain Secur…
  api_count: 0
  score_band: emerging
  score_composite: 20.6
  shared: 3
- slug: tugboat-logic
  name: Tugboat Logic
  description: Tugboat Logic is a security assurance and compliance automation platform acquired by OneTrust in 2021. It supports SOC 2, ISO 27001, HIPAA, GDPR, and NIST. As of 2024, the product has been rebranded under OneTrust's Certification Automatio…
  api_count: 1
  score_band: minimal
  score_composite: 10.9
  shared: 3
- slug: hyperproof
  name: Hyperproof
  description: Hyperproof is a continuous compliance and risk management platform that automates evidence collection, control management, and audit workflows. It exposes a public REST API covering 20+ resources (Controls, Policies, Programs, Risks, Proof…
  api_count: 2
  score_band: minimal
  score_composite: 10.1
  shared: 3
- slug: cowbell
  name: Cowbell
  description: Cowbell is a Pleasanton, California-based adaptive cyber insurance provider serving small and medium-sized businesses (SMBs) and the middle market with standalone cyber liability coverage, technology errors & omissions (Tech E&O), manageme…
  api_count: 0
  score_band: minimal
  score_composite: 9.6
  shared: 3
- slug: alyne
  name: Alyne
  description: Alyne is a cloud-native governance, risk and compliance (GRC) platform, founded in Munich in 2015 and acquired by Mitratech in 2021, where it is now offered as Mitratech's Alyne. The platform pairs a large curated library of controls and r…
  api_count: 0
  score_band: minimal
  score_composite: 4.7
  shared: 3
- slug: onetrust
  name: OneTrust
  description: OneTrust is an enterprise trust, privacy, and AI-governance platform. Its developer portal publishes 37 downloadable OpenAPI definitions covering roughly 631 operations across Universal Consent & Preference Management, Cookie Consent / CMP…
  api_count: 37
  score_band: exemplar
  score_composite: 72.7
  shared: 2
- slug: paubox
  name: Paubox
  description: Paubox is a HIPAA compliant, HITRUST certified email infrastructure company serving healthcare organizations in the United States. Its products encrypt outbound email without recipient portals, passwords, or plugins, and work alongside Goo…
  api_count: 3
  score_band: exemplar
  score_composite: 68.4
  shared: 2
- slug: dun-and-bradstreet
  name: Dun & Bradstreet
  description: Dun & Bradstreet is a leading global provider of business decisioning data and analytics, anchored by the D-U-N-S Number — a unique nine-digit identifier assigned to more than 500 million businesses worldwide. Founded in 1841 as The Mercan…
  api_count: 1
  score_band: strong
  score_composite: 65.9
  shared: 2
- slug: fenergo
  name: Fenergo
  description: Fenergo is an Irish-headquartered financial-services SaaS vendor whose Fen-X platform delivers Client Lifecycle Management (CLM), Know Your Customer (KYC), AML screening, client onboarding, transaction monitoring and regulatory compliance…
  api_count: 145
  score_band: strong
  score_composite: 62.3
  shared: 2
- slug: spruce-health
  name: Spruce Health
  description: Spruce Health is a HIPAA-compliant healthcare communication platform that unifies phone, SMS, secure messaging, video, e-fax, team chat, mobile payments and VoIP phone lines into one system for medical practices, with AI-enabled voicemail…
  api_count: 16
  score_band: strong
  score_composite: 61.2
  shared: 2
- slug: azure-health
  name: Microsoft Azure Health Data Services
  description: Microsoft Azure Health Data Services is a cloud-based suite of managed API services built on open healthcare standards (FHIR R4, DICOM, HL7) that enables healthcare organizations to collect, store, analyze, and exchange protected health in…
  api_count: 2
  score_band: strong
  score_composite: 61.0
  shared: 2
---
