---
layout: topic
slug: zero-trust
name: Zero Trust
kind: topic
description: Zero Trust is the umbrella cybersecurity strategy that eliminates implicit trust based on network location and requires continuous verification of every user, device, workload, and access request. This index aggregates the core specifications (NIST, CISA, DoD, NSA, NCSC), the leading vendor platforms that implement Zero Trust (Cloudflare, Zscaler, Netskope, Palo Alto Networks, Tailscale, Twingate, Microsoft, Google), and the CNCF-graduated open standards that the ecosystem depends on (SPIFFE, SPIRE, OPA). Three sister API Evangelist topics cover Zero Trust Architecture, Zero Trust Network Access (ZTNA), and the Zero Trust Security Model in greater depth.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/zero-trust.png
tags:
- Access Control
- Cloud Security
- Cybersecurity
- Federal
- Identity and Access Management
- Network Security
- Security
- Zero Trust
repo: https://github.com/api-evangelist/zero-trust
api_count: 9
apis:
- name: NIST SP 800-207 Zero Trust Architecture
  description: The foundational US specification of Zero Trust, defining the seven tenets, PDP/PEP/PA components, and three deployment variants (enhanced identity governance, microsegmentation, network infrastructure / SDP).
  url: https://csrc.nist.gov/pubs/sp/800/207/final
- name: CISA Zero Trust Maturity Model v2
  description: The federal-civilian Zero Trust roadmap from CISA, with four maturity levels across the Identity, Devices, Networks, Applications & Workloads, and Data pillars plus cross-cutting capabilities for Visibility & Analytics, Automation & Orches…
  url: https://www.cisa.gov/zero-trust-maturity-model
- name: DoD Zero Trust Reference Architecture
  description: The Department of Defense seven-pillar Zero Trust reference architecture and 152-capability target/advanced execution roadmap.
  url: https://dodcio.defense.gov/library/
- name: Cloudflare Zero Trust API
  description: Cloudflare's Zero Trust platform combining ZTNA, SWG, CASB, RBI, DLP and an REST API for managing all of it.
  url: https://developers.cloudflare.com/cloudflare-one/
- name: Zscaler Zero Trust Exchange API
  description: Zscaler's combined ZIA (internet access) and ZPA (private access) Zero Trust platform with REST APIs for both.
  url: https://help.zscaler.com/
- name: Microsoft Entra Zero Trust APIs
  description: Microsoft Entra (formerly Azure AD), Conditional Access, Defender for Cloud Apps, and Microsoft Intune together implement Zero Trust on the Microsoft platform; Microsoft Graph exposes a unified REST surface.
  url: https://learn.microsoft.com/en-us/security/zero-trust/
- name: Google BeyondCorp Enterprise
  description: Google's productized Zero Trust platform building on the original BeyondCorp research; provides context-aware access through Identity-Aware Proxy and Chrome Enterprise.
  url: https://cloud.google.com/beyondcorp-enterprise
- name: SPIFFE / SPIRE
  description: CNCF-graduated workload identity standard (SPIFFE) and reference runtime (SPIRE) used as the workload-identity foundation in Zero Trust deployments.
  url: https://spiffe.io/
- name: Open Policy Agent (OPA)
  description: CNCF-graduated general-purpose policy engine commonly deployed as the PDP in Zero Trust implementations.
  url: https://www.openpolicyagent.org/
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/zero-trust/blob/main/security/zero-trust-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/zero-trust/blob/main/security/zero-trust-domain-security.yml
- type: Documentation
  url: https://www.nist.gov/publications/zero-trust-architecture
- type: Documentation
  url: https://nvlpubs.nist.gov/nistpubs/specialpublications/NIST.SP.800-207.pdf
- type: Documentation
  url: https://nvlpubs.nist.gov/nistpubs/SpecialPublications/NIST.SP.800-207A.pdf
- type: Compliance
  url: https://www.cisa.gov/zero-trust-maturity-model
- type: Compliance
  url: https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf
- type: Compliance
  url: https://dodcio.defense.gov/Portals/0/Documents/Library/ZT-Reference-Architecture.pdf
- type: Documentation
  url: https://www.nsa.gov/Press-Room/News-Highlights/Article/Article/2899282/nsa-releases-guidance-on-zero-trust-security-model/
- type: Documentation
  url: https://www.ncsc.gov.uk/collection/zero-trust-architecture
- type: Portal
  url: https://www.cloudflare.com/zero-trust/
- type: Portal
  url: https://www.zscaler.com/products-and-solutions/zero-trust-exchange
- type: Portal
  url: https://www.netskope.com/platform/sase
- type: Portal
  url: https://www.paloaltonetworks.com/sase/access
- type: Portal
  url: https://learn.microsoft.com/en-us/security/zero-trust/
- type: Portal
  url: https://cloud.google.com/beyondcorp
- type: Portal
  url: https://tailscale.com/
- type: Portal
  url: https://www.twingate.com/
- type: GitHubOrganization
  url: https://github.com/spiffe
- type: GitHubOrganization
  url: https://github.com/open-policy-agent
- type: Resources
  url: https://github.com/api-evangelist/zero-trust-architecture
- type: Resources
  url: https://github.com/api-evangelist/zero-trust-network-access
- type: Resources
  url: https://github.com/api-evangelist/zero-trust-security-model
- type: JSONSchema
  url: https://github.com/api-evangelist/zero-trust/blob/main/json-schema/zero-trust-access-decision-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/zero-trust/blob/main/json-schema/zero-trust-subject-schema.json
- type: JSONStructure
  url: https://github.com/api-evangelist/zero-trust/blob/main/json-structure/zero-trust-access-decision-structure.json
- type: JSONLD
  url: https://github.com/api-evangelist/zero-trust/blob/main/json-ld/zero-trust-context.jsonld
- type: CodeExamples
  url: https://github.com/api-evangelist/zero-trust/blob/main/examples/zero-trust-access-decision-example.json
- type: Resources
  url: https://github.com/api-evangelist/zero-trust/blob/main/vocabulary/zero-trust-vocabulary.yaml
provider_count: 398
providers:
- slug: zero-trust-network-access
  name: Zero Trust Network Access
  description: Zero Trust Network Access (ZTNA) is a security framework and product category that grants access to private applications and resources based on identity, device posture, and context, rather than network location. ZTNA replaces the implicit…
  api_count: 1
  score_band: thin
  score_composite: 35.9
  shared: 6
- slug: zero-trust-security-model
  name: Zero-Trust Security Model
  description: The Zero Trust security model is a strategic cybersecurity approach that eliminates implicit trust and requires continuous verification of every user, device, workload, and request attempting to access resources, regardless of network loca…
  api_count: 5
  score_band: emerging
  score_composite: 25.4
  shared: 6
- slug: iboss
  name: iboss
  description: iboss, Inc. is a Boston-headquartered cybersecurity company founded in 2003 that operates an AI-powered, cloud-native Zero Trust SASE (Secure Access Service Edge) platform used by more than 4,000 enterprise, US federal, state and local gov…
  api_count: 1
  score_band: thin
  score_composite: 29.5
  shared: 5
- slug: zero-trust-architecture
  name: Zero Trust Architecture
  description: Zero Trust Architecture (ZTA) is a security framework defined by NIST SP 800-207 that requires all users and devices to be authenticated, authorized, and continuously validated before being granted access to applications and data, regardle…
  api_count: 5
  score_band: emerging
  score_composite: 23.2
  shared: 5
- slug: zero-networks
  name: Zero Networks
  description: Zero Networks is an Israeli-American network security company whose Segment platform delivers automated, agentless microsegmentation and identity segmentation for enterprise networks. It builds a host-based firewall "bubble" around every a…
  api_count: 1
  score_band: developing
  score_composite: 45.2
  shared: 4
- slug: spideroak
  name: SpiderOak
  description: SpiderOak (SpiderOak, Inc. / SpiderOak Mission Systems) builds zero-trust access governance and secure data exchange software for defense, aerospace and commercial operators working in contested, disconnected, degraded, intermittent and lo…
  api_count: 1
  score_band: developing
  score_composite: 44.7
  shared: 4
- slug: p0-security
  name: P0 Security
  description: P0 Security is a cloud-native Privileged Access Management (PAM) platform that governs runtime authorization for human users, machine/service accounts, and AI agents across hybrid and multi-cloud environments. Its AuthZ Control Plane enfor…
  api_count: 1
  score_band: developing
  score_composite: 42.5
  shared: 4
- slug: coronet
  name: CoroNet
  description: Coro (CoroNet) is a cybersecurity company delivering a unified, AI-native security platform for lean IT teams, growing organizations, and managed service providers (MSPs). A single platform and dashboard consolidate endpoint protection, em…
  api_count: 1
  score_band: developing
  score_composite: 42.0
  shared: 4
- slug: pulse
  name: Pulse
  description: 'Ivanti''s secure-access product family, formerly Pulse Secure, acquired by Ivanti in 2020. Three administrator-facing REST APIs configure and observe it: Ivanti Connect Secure for SSL VPN remote access, Ivanti Policy Secure for 802.1X and R…'
  api_count: 3
  score_band: developing
  score_composite: 40.0
  shared: 4
- slug: checkpoint
  name: Check Point
  description: Check Point Software Technologies is a global cybersecurity vendor providing network, cloud, endpoint, mobile, and email security through its Quantum, CloudGuard, and Harmony product families. Check Point exposes a wide range of REST APIs…
  api_count: 5
  score_band: thin
  score_composite: 35.9
  shared: 4
- slug: illumio
  name: Illumio
  description: Illumio is a Zero Trust Segmentation (microsegmentation) cybersecurity company whose platform stops the lateral spread of ransomware and breaches across data centers, cloud, and endpoints. Its Policy Compute Engine (PCE) exposes a REST API…
  api_count: 1
  score_band: thin
  score_composite: 30.8
  shared: 4
- slug: perimeter-81
  name: Perimeter 81
  description: Perimeter 81 is a cloud-native Secure Access Service Edge (SASE) and Zero Trust Network Access (ZTNA) platform, now part of Check Point as Check Point Harmony SASE following its 2023 acquisition. It lets organizations build and manage secu…
  api_count: 1
  score_band: thin
  score_composite: 28.6
  shared: 4
- slug: unisys
  name: Unisys
  description: Unisys is a global information technology company that provides specialized solutions integrated with leading-edge security. Unisys delivers digital workplace services, cloud and infrastructure services, and enterprise computing solutions…
  api_count: 4
  score_band: emerging
  score_composite: 23.9
  shared: 4
- slug: xage
  name: Xage
  description: Xage Security is a Palo Alto, California zero trust access and protection company whose Xage Fabric Platform enforces identity-based access control across operational technology (OT), IT, cloud and edge environments — covering privileged a…
  api_count: 0
  score_band: emerging
  score_composite: 15.6
  shared: 4
- slug: firemon
  name: FireMon
  description: FireMon is a cybersecurity company providing firewall and security policy management across hybrid, on-premises, and cloud environments. Its platform normalizes and governs security policies spanning firewalls, cloud security groups, and m…
  api_count: 0
  score_band: emerging
  score_composite: 15.4
  shared: 4
- slug: aceiss
  name: Aceiss
  description: Aceiss is a security monitoring and access-visibility platform that gives CISOs and risk managers continuous insight into who has access to their GitHub organizations and repositories. It monitors user access across repositories, detects u…
  api_count: 0
  score_band: emerging
  score_composite: 14.8
  shared: 4
- slug: 6cloudtechnology
  name: 6Cloud Technology
  description: 6Cloud Technology (Chinese name 六方云; legal entity Beijing 6Cloud Information Technology Co., Ltd. / 北京六方云信息技术有限公司) is a Beijing-based industrial and critical-infrastructure cybersecurity product vendor founded in 2018 and backed by China's…
  api_count: 0
  score_band: minimal
  score_composite: 4.7
  shared: 4
- slug: axis-security
  name: Axis Security
  description: Axis Security was a Security Service Edge (SSE) and Zero Trust Network Access (ZTNA) vendor founded in 2018 and headquartered in San Mateo, California, with research and development in Israel. Its cloud-delivered Atmos platform combined ZT…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 4
- slug: cyemptive
  name: Cyemptive
  description: Cyemptive Technologies is a cybersecurity vendor founded in 2014 by Rob Pike, headquartered in Washington State with additional offices in North Carolina, the United Kingdom, France and India. It sells preemptive, detection-independent sec…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 4
- slug: guardicore
  name: Guardicore
  description: Guardicore is a micro-segmentation and Zero Trust network security company, founded in 2013 and backed by Battery Ventures and Partech, best known for its Centra platform for software-defined segmentation, application dependency mapping, a…
  api_count: 0
  score_band: minimal
  score_composite: 3.4
  shared: 4
- slug: palo-alto-networks
  name: Palo Alto Networks
  description: Palo Alto Networks is a global cybersecurity leader providing advanced security platforms and services across network security, cloud security, and security operations. Its developer platform at pan.dev offers REST and XML APIs for PAN-OS…
  api_count: 468
  score_band: exemplar
  score_composite: 76.9
  shared: 3
- slug: aembit
  name: Aembit
  description: Aembit is a Workload Identity and Access Management (Workload IAM) platform for non-human identities — AI agents, applications, microservices, CI/CD pipelines, scripts and service accounts. Instead of long-lived, hard-coded secrets, Aembit…
  api_count: 2
  score_band: exemplar
  score_composite: 72.6
  shared: 3
- slug: tenable
  name: Tenable
  description: Tenable is a cybersecurity and exposure-management company, maker of Nessus and the Tenable One platform, providing vulnerability management, web application scanning, cloud security, identity exposure, attack surface management and OT sec…
  api_count: 8
  score_band: exemplar
  score_composite: 67.5
  shared: 3
- slug: cisco-umbrella
  name: Cisco Umbrella
  description: 'Cisco Umbrella, built on the OpenDNS platform Cisco acquired in 2015 and now sold within Cisco Secure Access, is Cisco''s cloud-delivered security service: DNS-layer security, secure web gateway, cloud-delivered firewall, CASB (Cisco Cloudl…'
  api_count: 52
  score_band: strong
  score_composite: 62.1
  shared: 3
- slug: microsoft-entra
  name: Microsoft Entra
  description: Microsoft Entra (formerly Azure Active Directory) provides identity and access management services including authentication, authorization, and directory services.
  api_count: 1
  score_band: strong
  score_composite: 58.5
  shared: 3
- slug: cisco-secure-firewall
  name: Cisco Secure Firewall
  description: Cisco Secure Firewall is the product line built on the Sourcefire technology Cisco acquired in 2013 — the Firepower/Secure Firewall appliances and Threat Defense (FTD) software, the Secure Firewall Management Center (FMC), the on-box devic…
  api_count: 14
  score_band: strong
  score_composite: 56.4
  shared: 3
- slug: nord-security
  name: Nord Security
  description: Nord Security is a Lithuania-founded digital security and privacy company whose consumer and business portfolio spans NordVPN, NordPass, NordLocker, NordLayer (network access security for business), NordProtect/Coveron, Saily (eSIM) and No…
  api_count: 7
  score_band: strong
  score_composite: 56.4
  shared: 3
- slug: c1
  name: C1
  description: C1 (ConductorOne) is an identity and access management platform engineered for the AI era. It provides unified access governance across human identities, AI agents, and services — agentic identity management, policy-driven access controls,…
  api_count: 1
  score_band: strong
  score_composite: 55.6
  shared: 3
- slug: amazon-iam-access-analyzer
  name: Amazon IAM Access Analyzer
  description: AWS IAM Access Analyzer helps you set, verify, and refine your IAM policies by providing a suite of capabilities including findings for external, internal, and unused access, basic and custom policy checks for validating policies, and poli…
  api_count: 1
  score_band: strong
  score_composite: 54.5
  shared: 3
- slug: britive
  name: Britive
  description: Britive is a runtime privileged access management (PAM) platform that issues just-in-time, ephemeral privileges to human users, non-human identities and AI agents across AWS, Azure, GCP, Oracle Cloud, Kubernetes, Snowflake, Okta, Salesforc…
  api_count: 3
  score_band: developing
  score_composite: 53.0
  shared: 3
---
