---
layout: topic
slug: software-defined-networking
name: Software-Defined Networking
kind: topic
description: Software-Defined Networking (SDN) is a network architecture approach that decouples the network control plane from the data forwarding plane, enabling dynamic, programmatically efficient network configuration. SDN controllers expose northbound REST APIs for network applications to define routing, load balancing, and security policies, while southbound APIs communicate with switches and routers. Key SDN controllers include OpenDaylight, ONOS, and Floodlight.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/software-defined-networking.png
tags:
- Cloud Infrastructure
- Network Architecture
- Networking
- Virtualization
- SDN
- OpenDaylight
- ONOS
repo: https://github.com/api-evangelist/software-defined-networking
api_count: 2
apis:
- name: OpenDaylight RESTCONF API
  description: OpenDaylight is an open-source SDN controller platform that exposes RESTCONF APIs for managing network devices, topology, flows, and configuration. It provides northbound REST interfaces for network applications and southbound interfaces f…
  url: https://docs.opendaylight.org/en/latest/
- name: ONOS SDN Controller REST API
  description: ONOS (Open Network Operating System) is an open-source SDN controller that provides REST APIs for network management including topology discovery, flow rule management, host tracking, and device management.
  url: https://wiki.onosproject.org/display/ONOS/REST+API
links:
- type: DomainSecurity
  url: https://github.com/api-evangelist/software-defined-networking/blob/main/security/software-defined-networking-domain-security.yml
- type: Website
  url: https://opennetworking.org/
- type: Reference
  url: https://en.wikipedia.org/wiki/Software-defined_networking
- type: Standards
  url: https://datatracker.ietf.org/doc/html/rfc7426
- type: Reference
  url: https://www.ciena.com/insights/articles/5-key-APIs-to-enable-the-concept-of-SDN-based-virtual-networks.html
- type: GitHubOrganization
  url: https://github.com/opendaylight
- type: GitHubOrganization
  url: https://github.com/opennetworkinglab
- type: JSONLDContext
  url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/json-ld/software-defined-networking-context.jsonld
- type: Vocabulary
  url: https://raw.githubusercontent.com/api-evangelist/software-defined-networking/refs/heads/main/vocabulary/software-defined-networking-vocabulary.yml
provider_count: 21
providers:
- slug: zerotier
  name: ZeroTier
  description: ZeroTier, Inc. builds a software-defined networking (SDN) overlay that securely connects devices, servers, clouds, and networks anywhere in the world as if they were on the same local LAN, without the complexity of traditional VPNs, port f…
  api_count: 2
  score_band: strong
  score_composite: 64.0
  shared: 2
- slug: microsoft-azure-cdn
  name: Microsoft Azure Cdn
  description: Azure Content Delivery Network (CDN) caches static web content at strategically placed edge locations to deliver it to users with maximum throughput and minimum latency. The product is operated through the Microsoft.Cdn Azure Resource Mana…
  api_count: 1
  score_band: strong
  score_composite: 62.2
  shared: 2
- slug: microsoft-azure-private-link
  name: Microsoft Azure Private Link
  description: Microsoft Azure Private Link gives a virtual network a private IP address onto an Azure PaaS service, a partner service, or a service the customer publishes themselves, so traffic reaches it across the Microsoft backbone and never traverse…
  api_count: 2
  score_band: strong
  score_composite: 60.6
  shared: 2
- slug: intersight
  name: Cisco Intersight
  description: Cisco Intersight is Cisco's SaaS operations platform for UCS servers, HyperFlex clusters, Nexus fabrics, third-party storage and virtualization, covering provisioning, firmware lifecycle, workload optimization, telemetry and Kubernetes ser…
  api_count: 11
  score_band: strong
  score_composite: 57.7
  shared: 2
- slug: juniper
  name: Juniper Networks
  description: Juniper Networks (an HPE company since 2025) builds AI-native networking, routing, switching and security for service providers, enterprises and public-sector organizations. Its programmable surface spans the Mist cloud API (1,059 REST ope…
  api_count: 6
  score_band: strong
  score_composite: 54.7
  shared: 2
- slug: cisco-aci
  name: Cisco ACI
  description: Cisco Application Centric Infrastructure (ACI) is Cisco's data-center SDN fabric, programmed through the Application Policy Infrastructure Controller (APIC) and its object model, the Management Information Tree (MIT). Every APIC GUI, CLI a…
  api_count: 1
  score_band: developing
  score_composite: 53.7
  shared: 2
- slug: oxide-computer
  name: Oxide
  description: 'Oxide Computer Company builds a rack-scale cloud computer: integrated server sleds (Gimlet), a rack-level switch (Sidecar), Oxide''s own illumos distribution (Helios), the Propolis/bhyve hypervisor and the Crucible distributed block store,…'
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 2
- slug: citrix
  name: Citrix
  description: Citrix is a global software company providing virtualization, networking, workspace, and digital experience products that allow organizations to deliver applications and desktops securely from data centers and clouds to any device. Citrix…
  api_count: 6
  score_band: developing
  score_composite: 42.7
  shared: 2
- slug: cisco-nexus
  name: Cisco Nexus Dashboard
  description: APIs for managing and monitoring Cisco Nexus data center switches and network infrastructure.
  api_count: 1
  score_band: developing
  score_composite: 42.2
  shared: 2
- slug: equinix
  name: Equinix
  description: Equinix is a global digital infrastructure company that provides interconnection and data center services to enterprises, cloud and IT service providers, and telecommunications networks worldwide. Equinix exposes a broad set of public APIs…
  api_count: 10
  score_band: thin
  score_composite: 39.0
  shared: 2
- slug: broadcom
  name: Broadcom
  description: Broadcom is a global technology company that specializes in the design and manufacturing of semiconductors and other hardware components for a wide range of industries. They provide a diverse portfolio of products for the enterprise, data…
  api_count: 3
  score_band: thin
  score_composite: 32.6
  shared: 2
- slug: simplivity
  name: SimpliVity
  description: SimpliVity is the hyperconverged infrastructure (HCI) pioneer acquired by Hewlett Packard Enterprise in 2017 and now shipped as HPE SimpliVity. Its data virtualization platform runs on the OmniStack software stack, delivering built-in dedu…
  api_count: 1
  score_band: thin
  score_composite: 30.7
  shared: 2
- slug: parallels-swsoft
  name: Parallels (SWSoft)
  description: Parallels is a virtualization and remote-access software company, originally founded as SWSoft in 1999 and renamed Parallels in 2008 (now part of Alludo/Corel). Its flagship enterprise product, Parallels Remote Application Server (RAS), de…
  api_count: 1
  score_band: thin
  score_composite: 30.3
  shared: 2
- slug: nanovms
  name: NanoVMs
  description: NanoVMs builds unikernel infrastructure that lets developers run a single application as its own lightweight, secure virtual machine with no operating system and no devops. Its open-source toolchain centers on OPS (the ops CLI, ops.city) f…
  api_count: 0
  score_band: thin
  score_composite: 26.5
  shared: 2
- slug: lf-broadband
  name: LF Broadband
  description: LF Broadband is a Linux Foundation Directed Fund established in late 2023 that supports open source broadband networking projects, including reference designs and virtualization tools for broadband access networks. Its flagship projects, S…
  api_count: 2
  score_band: emerging
  score_composite: 12.7
  shared: 2
- slug: bti-systems-juniper
  name: BTI Systems (Juniper)
  description: BTI Systems was an Ottawa, Ontario based supplier of cloud and metro packet-optical networking systems and software, best known for the BTI 7800 Series Packet Optical Transport platform, the BTI 800 Series, and the proNX family of manageme…
  api_count: 0
  score_band: minimal
  score_composite: 7.9
  shared: 2
- slug: barefoot-networks
  name: Barefoot Networks
  description: Barefoot Networks was a computer-networking company founded in 2013 in Santa Clara, California, that designed and produced programmable network-switch silicon, systems, and software. Its flagship Tofino Intelligent Fabric Processor was the…
  api_count: 0
  score_band: minimal
  score_composite: 7.2
  shared: 2
- slug: nicira-networks
  name: Nicira Networks
  description: Nicira Networks was a software-defined networking (SDN) and network virtualization pioneer founded in 2007 out of research by Martin Casado, Nick McKeown, and Scott Shenker on OpenFlow. Its Network Virtualization Platform (NVP) decoupled v…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
- slug: plexxi
  name: Plexxi *
  description: Plexxi was a software-defined networking (SDN) startup building data-center fabric and network orchestration, backed by GV and Lightspeed Venture Partners. It was acquired by Hewlett Packard Enterprise (HPE) and folded into the Aruba Netwo…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
- slug: snaproute
  name: Snaproute
  description: SnapRoute was a cloud-native networking startup, backed by Lightspeed Venture Partners and Norwest Venture Partners, that built a containerized, microservices-based network operating system (its FlexSwitch / Cloud-Native Network OS) aimed…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
- slug: stateless
  name: Stateless
  description: Stateless was a Boulder, Colorado network-infrastructure startup (founded 2016) that built a software platform for network automation in the hybrid multi-cloud era, delivering network functions such as firewalls and load balancers through…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
---
