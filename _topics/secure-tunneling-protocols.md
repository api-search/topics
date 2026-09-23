---
layout: topic
slug: secure-tunneling-protocols
name: Secure Tunneling Protocols
kind: topic
description: Network protocols that create encrypted tunnels for secure data transmission over untrusted networks, including VPN technologies like IPsec, SSL/TLS, WireGuard, and SSH tunneling for protecting communication channels. It is widely adopted across industries to safeguard digital assets and reduce security risks.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/secure-tunneling-protocols.png
tags:
- Encryption
- Networking
- Security
- VPN
repo: https://github.com/api-evangelist/secure-tunneling-protocols
api_count: 0
apis: []
links: []
provider_count: 75
providers:
- slug: vpn
  name: VPN
  description: A VPN (Virtual Private Network) creates an encrypted tunnel between a user's device and a remote network, protecting data from interception and masking the user's IP address. VPN technology is widely used for secure remote access to corpor…
  api_count: 6
  score_band: thin
  score_composite: 31.4
  shared: 4
- slug: amazon-vpn
  name: Amazon VPN
  description: 'AWS VPN solutions establish secure connections between on-premises networks, remote offices, client devices, and the AWS global network. AWS offers two types of private connectivity: AWS Site-to-Site VPN and AWS Client VPN, enabling encryp…'
  api_count: 1
  score_band: exemplar
  score_composite: 73.3
  shared: 3
- slug: zerotier
  name: ZeroTier
  description: ZeroTier, Inc. builds a software-defined networking (SDN) overlay that securely connects devices, servers, clouds, and networks anywhere in the world as if they were on the same local LAN, without the complexity of traditional VPNs, port f…
  api_count: 2
  score_band: strong
  score_composite: 64.0
  shared: 3
- slug: nym-technologies
  name: Nym Technologies
  description: Nym Technologies SA builds Nym, an open-source decentralized privacy infrastructure. Its flagship product NymVPN is a decentralized VPN built on the Nym mixnet, a multi-layer network of mix nodes that shuffles and delays packets to protect…
  api_count: 2
  score_band: developing
  score_composite: 49.7
  shared: 3
- slug: netbird
  name: NetBird
  description: NetBird is an Open-Source Zero Trust Networking platform that allows you to create secure private networks for your organization or home. We designed NetBird to be simple and fast, requiring near-zero configuration effort and leaving behin…
  api_count: 1
  score_band: developing
  score_composite: 39.5
  shared: 3
- slug: perimeter-81
  name: Perimeter 81
  description: Perimeter 81 is a cloud-native Secure Access Service Edge (SASE) and Zero Trust Network Access (ZTNA) platform, now part of Check Point as Check Point Harmony SASE following its 2023 acquisition. It lets organizations build and manage secu…
  api_count: 1
  score_band: thin
  score_composite: 30.1
  shared: 3
- slug: opnsense
  name: OPNsense
  description: OPNsense is an open source FreeBSD-based firewall and routing platform providing stateful packet filtering, VPN (IPsec, OpenVPN, WireGuard), intrusion detection (Suricata), traffic shaping, captive portal, and high availability for home, e…
  api_count: 1
  score_band: emerging
  score_composite: 25.1
  shared: 3
- slug: post-quantum
  name: Post-Quantum
  description: Post-Quantum is a quantum-safe cybersecurity company founded in 2009 that protects critical infrastructure against both present-day threats and future quantum-computing attacks. Its platform spans Identity Protection, a hybrid post-quantum…
  api_count: 0
  score_band: minimal
  score_composite: 9.2
  shared: 3
- slug: uroam
  name: Uroam
  description: uRoam, Inc. (1999-2003) was a Canaan Partners-backed security company that built FirePass, a clientless SSL-VPN appliance for "radically simplified remote access" to enterprise applications from any browser. After merging with Filanet, uRo…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 3
- slug: network-alchemy
  name: Network Alchemy
  description: Network Alchemy, Inc. was a Santa Cruz, California networking-security company backed by Trinity Ventures that developed non-stop IP infrastructure for secure private communications, commerce and collaboration. It marketed what it describe…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: paubox
  name: Paubox
  description: Paubox is a HIPAA compliant, HITRUST certified email infrastructure company serving healthcare organizations in the United States. Its products encrypt outbound email without recipient portals, passwords, or plugins, and work alongside Goo…
  api_count: 3
  score_band: exemplar
  score_composite: 71.5
  shared: 2
- slug: amazon-vpc
  name: Amazon VPC
  description: Amazon Virtual Private Cloud (VPC) lets you provision a logically isolated section of the AWS Cloud where you can launch AWS resources in a virtual network that you define, with complete control over IP addressing, subnets, routing, and ne…
  api_count: 1
  score_band: strong
  score_composite: 64.4
  shared: 2
- slug: ibm
  name: IBM
  description: A collection of IBM's public APIs and developer resources.
  api_count: 1
  score_band: strong
  score_composite: 62.6
  shared: 2
- slug: evervault
  name: Evervault
  description: Evervault is a data-security and payments-infrastructure platform that lets developers encrypt, tokenize, and process sensitive data - especially cardholder data - without it touching their own infrastructure. Its model stores encryption k…
  api_count: 1
  score_band: strong
  score_composite: 61.4
  shared: 2
- slug: amazon-kms
  name: Amazon KMS
  description: AWS Key Management Service (KMS) is a managed service that makes it easy to create and control the cryptographic keys used to protect your data, integrated with other AWS services to simplify encryption of data stored and managed in those…
  api_count: 1
  score_band: strong
  score_composite: 61.1
  shared: 2
- slug: microsoft-azure-private-link
  name: Microsoft Azure Private Link
  description: Microsoft Azure Private Link gives a virtual network a private IP address onto an Azure PaaS service, a partner service, or a service the customer publishes themselves, so traffic reaches it across the Microsoft backbone and never traverse…
  api_count: 2
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: cisco-umbrella
  name: Cisco Umbrella
  description: 'Cisco Umbrella, built on the OpenDNS platform Cisco acquired in 2015 and now sold within Cisco Secure Access, is Cisco''s cloud-delivered security service: DNS-layer security, secure web gateway, cloud-delivered firewall, CASB (Cisco Cloudl…'
  api_count: 52
  score_band: strong
  score_composite: 59.3
  shared: 2
- slug: cisco-secure-firewall
  name: Cisco Secure Firewall
  description: Cisco Secure Firewall is the product line built on the Sourcefire technology Cisco acquired in 2013 — the Firepower/Secure Firewall appliances and Threat Defense (FTD) software, the Secure Firewall Management Center (FMC), the on-box devic…
  api_count: 14
  score_band: strong
  score_composite: 59.2
  shared: 2
- slug: neutrino-api
  name: Neutrino API
  description: 'Neutrino API is a general-purpose API collection that solves common but recurring software-development problems: data validation, telephony, geolocation, security and networking, e-commerce and imaging. It is a single flat REST-style HTTP…'
  api_count: 2
  score_band: strong
  score_composite: 56.9
  shared: 2
- slug: amazon-certificate-manager
  name: Amazon Certificate Manager
  description: AWS Certificate Manager (ACM) handles the complexity of creating, storing, and renewing public and private SSL/TLS X.509 certificates and keys that protect your AWS websites and applications, enabling you to manage certificate lifecycles c…
  api_count: 1
  score_band: strong
  score_composite: 56.2
  shared: 2
- slug: cisco-psirt
  name: Cisco PSIRT openVuln API
  description: The Cisco Product Security Incident Response Team (PSIRT) openVuln API is Cisco's machine-readable vulnerability disclosure service. It lets security teams query Cisco security advisories by CVE, advisory ID, severity, publication date, af…
  api_count: 1
  score_band: strong
  score_composite: 55.0
  shared: 2
- slug: juniper
  name: Juniper Networks
  description: Juniper Networks (an HPE company since 2025) builds AI-native networking, routing, switching and security for service providers, enterprises and public-sector organizations. Its programmable surface spans the Mist cloud API (1,059 REST ope…
  api_count: 6
  score_band: strong
  score_composite: 54.7
  shared: 2
- slug: ironcore-labs
  name: IronCore Labs
  description: IronCore Labs builds application-layer encryption tools that keep sensitive data private while it stays usable. Its products include SaaS Shield (tenant-controlled envelope encryption with customer-managed keys / BYOK for multi-tenant SaaS…
  api_count: 1
  score_band: developing
  score_composite: 52.6
  shared: 2
- slug: macadress
  name: 'MAC Address Lookup: Find Vendor, OUI & Device Type'
  description: REST/JSON API, hosted MCP server, and reference data for MAC address / OUI lookup — resolving vendor, IEEE registration block, device category, and randomization confidence. Data synced twice daily from IEEE MA-L/MA-M/MA-S/IAB/CID registri…
  api_count: 1
  score_band: developing
  score_composite: 51.6
  shared: 2
- slug: dnsfilter
  name: DNSFilter
  description: DNSFilter is an AI-powered DNS security and content-filtering platform that protects organizations from cyber threats and unwanted content at the DNS layer. Its machine-learning engine blocks malicious domains — phishing, malware, ransomwa…
  api_count: 1
  score_band: developing
  score_composite: 51.4
  shared: 2
- slug: amazon-shield
  name: Amazon Shield
  description: AWS Shield is a managed Distributed Denial of Service (DDoS) protection service that safeguards applications running on AWS. It provides always-on detection and automatic inline mitigations that minimize application downtime and latency, w…
  api_count: 1
  score_band: developing
  score_composite: 50.6
  shared: 2
- slug: openbao
  name: OpenBao
  description: OpenBao is an open source, community-driven identity-based secrets and encryption management system, forked from HashiCorp Vault in 2023 and governed by the Linux Foundation as a sandbox project of the Open Source Security Foundation (Open…
  api_count: 1
  score_band: developing
  score_composite: 49.6
  shared: 2
- slug: cilium
  name: Cilium
  description: Cilium is an open source, cloud native solution for providing, securing, and observing network connectivity between workloads, fueled by the revolutionary kernel technology eBPF. Cilium provides network security, load balancing, and observ…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: infisical
  name: Infisical
  description: Infisical is an open-source secrets management platform that provides developers with a centralized, end-to-end encrypted vault for storing, syncing, and rotating secrets across teams, environments, and cloud infrastructure. The platform o…
  api_count: 1
  score_band: developing
  score_composite: 45.4
  shared: 2
- slug: border0
  name: Border0
  description: Border0 is an identity-aware Zero Trust network access platform for securing access to infrastructure — SSH and RDP servers, PostgreSQL/MySQL/MSSQL/MongoDB/Elasticsearch databases, Kubernetes clusters, AWS consoles and S3 buckets, and any…
  api_count: 1
  score_band: developing
  score_composite: 45.3
  shared: 2
---
