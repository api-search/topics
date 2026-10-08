---
layout: topic
slug: linux-server
name: Linux Server
kind: topic
description: Linux Server is a topic catalog covering management, administration, and monitoring interfaces used to operate Linux servers in production. It organizes references to systemd, cockpit, the Linux audit framework, package managers (apt, dnf, rpm), configuration management and provisioning tooling, and remote administration protocols commonly used on Linux servers.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/linux-server.png
tags:
- Infrastructure
- Linux
- Servers
- System Administration
- DevOps
repo: https://github.com/api-evangelist/linux-server
api_count: 7
apis:
- name: systemd
  description: System and service manager for Linux, providing process supervision, socket activation, journaled logging, and a D-Bus management API.
  url: https://systemd.io/
- name: Cockpit
  description: Web-based graphical interface for Linux server administration, providing tools for managing services, storage, networking, and accounts.
  url: https://cockpit-project.org/
- name: Linux Audit
  description: The Linux audit subsystem and userspace tools for tracking security-relevant events on a Linux server.
  url: https://github.com/linux-audit/audit-documentation
- name: APT
  description: The Advanced Package Tool used by Debian, Ubuntu, and derivatives for installing, upgrading, and removing software packages.
  url: https://wiki.debian.org/Apt
- name: DNF
  description: The Dandified YUM package manager used on Fedora, RHEL, CentOS Stream, and related distributions.
  url: https://dnf.readthedocs.io/
- name: OpenSSH
  description: The de facto standard suite for secure remote login, command execution, and file transfer on Linux servers.
  url: https://www.openssh.com/
- name: systemd-journald
  description: The systemd journal daemon, providing structured, indexed logs for the Linux server with a query API via journalctl and libsystemd.
  url: https://www.freedesktop.org/software/systemd/man/systemd-journald.service.html
links:
- type: IssueTracker
  url: https://github.com/systemd/systemd/issues
- type: Releases
  url: https://github.com/systemd/systemd/releases
- type: SecurityPolicy
  url: https://github.com/systemd/systemd/blob/main/docs/SECURITY.md
- type: CodeOfConduct
  url: https://github.com/systemd/systemd/blob/main/docs/CODE_OF_CONDUCT.md
- type: ContributionGuide
  url: https://github.com/systemd/systemd/blob/main/docs/CONTRIBUTING.md
- type: License
  url: https://github.com/systemd/systemd/blob/main/LICENSE
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/linux-server/blob/main/security/linux-server-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/linux-server/blob/main/security/linux-server-domain-security.yml
- type: Website
  url: https://www.linuxfoundation.org/
- type: Documentation
  url: https://www.kernel.org/doc/html/latest/
- type: Reference
  url: https://man7.org/linux/man-pages/
provider_count: 51
providers:
- slug: coreos
  name: CoreOS
  description: CoreOS was a San Francisco-based container infrastructure company founded in 2013 that built a lightweight, automatically-updating Linux distribution (Container Linux, originally CoreOS Linux) and a family of now-foundational cloud-native…
  api_count: 0
  score_band: minimal
  score_composite: 2.8
  shared: 3
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 3
  score_band: exemplar
  score_composite: 75.3
  shared: 2
- slug: new-relic
  name: New Relic
  description: New Relic offers an AI‑powered observability platform that provides application performance monitoring, digital experience monitoring, infrastructure monitoring, log management, and security services. The platform helps enterprises gain re…
  api_count: 5
  score_band: exemplar
  score_composite: 72.3
  shared: 2
- slug: ibm
  name: IBM
  description: IBM offers solutions that protect identities and sensitive access for enterprise customers. Its IBM Vault® product is highlighted as a tool for identity protection and regulatory compliance, and IBM hosts webinars on trust, identity, and g…
  api_count: 1
  score_band: exemplar
  score_composite: 69.1
  shared: 2
- slug: spectro-cloud
  name: Spectro Cloud
  description: Spectro Cloud provides Palette, an enterprise platform for managing the full lifecycle of Kubernetes clusters and cloud-native and AI infrastructure across data centers, public clouds, bare metal, and the edge. Palette uses declarative clu…
  api_count: 3
  score_band: exemplar
  score_composite: 66.6
  shared: 2
- slug: facets
  name: Facets
  description: Facets is an AI-native SDLC orchestrator and platform-engineering control plane that unifies infrastructure provisioning, CI/CD and configuration management into a single declarative blueprint model, so product teams get self-serve, drift-…
  api_count: 2
  score_band: strong
  score_composite: 61.5
  shared: 2
- slug: platform.sh
  name: Platform.sh
  description: Platform.sh is the container-based Platform-as-a-Service (PaaS) founded in 2010 and headquartered in Paris and San Francisco, best known for Git-driven deployments in which a single push plus a few YAML files provisions an entire cluster o…
  api_count: 3
  score_band: strong
  score_composite: 57.9
  shared: 2
- slug: nuon
  name: Nuon
  description: Nuon is a Bring Your Own Cloud (BYOC) continuous-delivery platform for software vendors. It lets vendors package existing applications — Terraform, Pulumi, Helm charts, Kubernetes manifests, and container images — and deploy them into thei…
  api_count: 2
  score_band: strong
  score_composite: 55.8
  shared: 2
- slug: scale3
  name: Scale3
  description: Scale3 Labs is a modern observability and infrastructure platform for Web3 and generative AI. Its Web3 products (Autopilot, Nodepilot and Blockchain Intelligence) let node operators and validators deploy, monitor, log and alert on blockcha…
  api_count: 1
  score_band: strong
  score_composite: 54.3
  shared: 2
- slug: strongdm
  name: StrongDM
  description: StrongDM is a Zero Trust Privileged Access Management (PAM) platform that brokers and governs access to infrastructure — databases, servers, Kubernetes clusters, cloud resources, network devices, and internal web apps — through a central c…
  api_count: 3
  score_band: developing
  score_composite: 52.6
  shared: 2
- slug: gameye
  name: Gameye
  description: Gameye is a managed game server orchestration platform for multiplayer game studios, founded in 2017 in Rotterdam (Gameye B.V.). It runs dedicated, containerized game servers across bare metal, cloud, and edge providers behind a single RES…
  api_count: 1
  score_band: developing
  score_composite: 51.7
  shared: 2
- slug: openbao
  name: OpenBao
  description: OpenBao is an open source, community-driven identity-based secrets and encryption management system, forked from HashiCorp Vault in 2023 and governed by the Linux Foundation as a sandbox project of the Open Source Security Foundation (Open…
  api_count: 1
  score_band: developing
  score_composite: 51.6
  shared: 2
- slug: render
  name: Render
  description: Render is a cloud platform for building and running applications and websites with automatic Git-based deployments. It provides managed infrastructure for web services, static sites, background workers, cron jobs, private services, Postgre…
  api_count: 1
  score_band: developing
  score_composite: 50.5
  shared: 2
- slug: termius
  name: Termius
  description: Termius is a modern, cross-platform SSH client for DevOps professionals, network engineers, and infrastructure teams, available on Windows, macOS, Linux, iOS, iPadOS, and Android. It provides secure remote access with encrypted team vaults…
  api_count: 2
  score_band: developing
  score_composite: 49.3
  shared: 2
- slug: dell-servers
  name: Dell Servers
  description: APIs for managing and monitoring Dell PowerEdge servers and infrastructure, including the iDRAC Redfish out-of-band management interface, OpenManage Enterprise centralized console and its modular, power, support, and VMware integrations, t…
  api_count: 2
  score_band: developing
  score_composite: 46.4
  shared: 2
- slug: digital-ocean
  name: Digital Ocean
  description: DigitalOcean Holdings, Inc. is an American multinational technology company and cloud service provider. The company is headquartered in New York City, New York, US, with 15 globally distributed data centers. DigitalOcean provides developer…
  api_count: 1
  score_band: developing
  score_composite: 45.6
  shared: 2
- slug: netdata
  name: Netdata
  description: Netdata is a real-time infrastructure monitoring and observability platform that collects per-second metrics from physical servers, virtual machines, cloud deployments, Kubernetes clusters, and IoT devices. It provides a REST API for query…
  api_count: 1
  score_band: developing
  score_composite: 44.6
  shared: 2
- slug: hashicorp-vault
  name: HashiCorp Vault
  description: HashiCorp Vault is a secrets management tool that provides secure storage, access control, and distribution of tokens, passwords, certificates, and encryption keys. It provides a unified interface to any secret while providing tight access…
  api_count: 8
  score_band: developing
  score_composite: 43.9
  shared: 2
- slug: localstack
  name: LocalStack
  description: LocalStack is a cloud service emulator that runs in a single container on your laptop or in your CI environment, providing a local test and mocking framework for developing cloud applications against AWS, Snowflake, and Azure without provi…
  api_count: 1
  score_band: developing
  score_composite: 43.6
  shared: 2
- slug: stakpak
  name: StakPak
  description: Stakpak is an open-source autonomous DevOps AI agent, distributed as a single Rust binary, that runs 24/7 on your machines to keep applications running — performing health checks, auto-healing failures, monitoring cloud cost, rotating secr…
  api_count: 1
  score_band: developing
  score_composite: 43.5
  shared: 2
- slug: docker
  name: Docker
  description: Docker is a platform for developers and sysadmins to build, share, and run applications in containers, packaging code and dependencies together for consistent deployment across environments.
  api_count: 1
  score_band: developing
  score_composite: 41.1
  shared: 2
- slug: nomad
  name: HashiCorp Nomad
  description: HashiCorp Nomad is a flexible workload orchestrator that enables organizations to deploy and manage containers, legacy applications, and batch jobs across any infrastructure. The Nomad developer platform provides a comprehensive HTTP API,…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: vagrant
  name: Vagrant
  description: Vagrant, by HashiCorp, is a tool for building and managing virtualized development environments. Their developer platform provides APIs and SDKs for interacting with Vagrant Cloud and the HCP Vagrant Box Registry, enabling automation of bo…
  api_count: 2
  score_band: developing
  score_composite: 40.3
  shared: 2
- slug: dell-technologies
  name: Dell Technologies
  description: Dell Technologies is a global Fortune 500 technology company that designs, develops, manufactures, and supports a wide range of computing products, including PCs, servers, storage, networking equipment, and software services. Dell publishe…
  api_count: 1
  score_band: developing
  score_composite: 40.0
  shared: 2
- slug: civil-infrastructure-platform
  name: Civil Infrastructure Platform
  description: The Civil Infrastructure Platform (CIP) is a Linux Foundation collaborative project that builds an industrial-grade open source base layer for civil infrastructure systems such as transportation, power generation and distribution, building…
  api_count: 3
  score_band: developing
  score_composite: 39.9
  shared: 2
- slug: rackspace-technology
  name: Rackspace Technology
  description: Rackspace Technology is a multicloud solutions provider offering managed services, professional services, and consulting across cloud infrastructure, applications, data, AI, and cybersecurity. The company operates as a trusted operator of…
  api_count: 26
  score_band: developing
  score_composite: 39.7
  shared: 2
- slug: hetzner
  name: Hetzner
  description: Hetzner Online is a German hosting provider offering cloud servers, dedicated servers, and domain services. Hetzner provides a Cloud API for programmatic management of cloud resources, as well as a DNS API for managing DNS zones and record…
  api_count: 1
  score_band: thin
  score_composite: 38.2
  shared: 2
- slug: aviatrix
  name: Aviatrix
  description: Aviatrix is a cloud network security company whose Cloud Native Security Fabric (CNSF) delivers zero-trust, workload-level network security and runtime protection across AWS, Azure, GCP, OCI, and hybrid/edge environments. The platform - bu…
  api_count: 0
  score_band: thin
  score_composite: 37.2
  shared: 2
- slug: railway-app
  name: Railway
  description: Railway is a cloud application deployment platform (PaaS) that builds, deploys, and scales services, databases, and cron jobs from a Git repository or Docker image. Its programmatic surface is a GraphQL-first Public API served at https://b…
  api_count: 13
  score_band: thin
  score_composite: 36.9
  shared: 2
- slug: sensu
  name: Sensu
  description: Sensu (Sensu by Sumo Logic) is an observability pipeline that delivers monitoring as code across multi-cloud and hybrid environments. Sensu Go codifies monitoring workflows into declarative, versionable configuration and exposes a backend…
  api_count: 1
  score_band: thin
  score_composite: 36.5
  shared: 2
---
