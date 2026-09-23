---
layout: topic
slug: cloud
name: Cloud
kind: topic
description: Cloud is a topic profile in the API Evangelist Network covering the major public cloud platforms and their APIs. The topic indexes the hyperscalers (Amazon Web Services, Microsoft Azure, Google Cloud, Oracle Cloud, IBM Cloud, Alibaba Cloud) alongside developer-focused alternatives (DigitalOcean, Linode, Vultr, Hetzner, Scaleway), GPU and AI clouds (CoreWeave, Crusoe, Lambda Labs, RunPod), and edge / network-attached compute (Cloudflare Workers, Fastly Compute, Akamai Connected Cloud). It is the parent topic to specialized profiles in the network such as cloud-storage, cloud-cost-management, and cloud-native.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cloud.png
tags:
- Cloud
- Cloud Computing
- Compute
- Hyperscaler
- Infrastructure-as-a-Service
- Infrastructure
- Platform-as-a-Service
- Public Cloud
- Software-as-a-Service
repo: https://github.com/api-evangelist/cloud
api_count: 16
apis:
- name: Amazon Web Services
  description: Amazon Web Services is the largest public cloud, exposing 200+ services through service-specific REST and AWS-query APIs signed with SigV4. Compute (EC2, Lambda, ECS, EKS), storage (S3, EBS, EFS), database (RDS, DynamoDB, Aurora), networki…
  url: https://aws.amazon.com/
- name: Microsoft Azure
  description: Microsoft Azure provides public-cloud compute, storage, database, AI, and identity services through Azure Resource Manager (ARM) REST APIs. Authentication uses Microsoft Entra ID (formerly Azure AD) OAuth tokens. Microsoft Graph exposes th…
  url: https://azure.microsoft.com/
- name: Google Cloud
  description: Google Cloud Platform exposes 100+ services through Google APIs (REST + gRPC) authenticated with OAuth 2.0 service accounts. Compute Engine, GKE, Cloud Run, BigQuery, Spanner, Firestore, Vertex AI, and Cloud Storage all share the consisten…
  url: https://cloud.google.com/
- name: Oracle Cloud Infrastructure
  description: Oracle Cloud Infrastructure exposes IaaS and database APIs signed with OCI request signatures. Compute, networking, storage, autonomous database, and Oracle Database@Azure / GCP multicloud surfaces are accessible via region-specific REST e…
  url: https://www.oracle.com/cloud/
- name: IBM Cloud
  description: IBM Cloud exposes Kubernetes Service, VPC compute, Cloud Object Storage, Watsonx AI, Db2, and Cloudability cost management APIs. Authentication uses IAM API keys exchanged for bearer tokens.
  url: https://www.ibm.com/cloud
- name: Alibaba Cloud
  description: Alibaba Cloud is the largest public cloud in Asia. APIs cover ECS, OSS object storage, ApsaraDB, Function Compute, and PAI AI services. RPC and ROA-style endpoints are signed with HMAC using AccessKey credentials.
  url: https://www.alibabacloud.com/
- name: DigitalOcean
  description: DigitalOcean offers a developer-friendly REST API for Droplets, Kubernetes, App Platform, Spaces, Volumes, Load Balancers, Databases, and Functions. Authentication uses bearer tokens.
  url: https://www.digitalocean.com/
- name: Linode (Akamai Cloud)
  description: Linode (now Akamai Connected Cloud) exposes a REST API for Linode instances, Kubernetes (LKE), Object Storage, NodeBalancers, and Cloud Firewalls.
  url: https://www.linode.com/
- name: Vultr
  description: Vultr provides REST APIs for cloud compute, bare metal, Kubernetes, Object Storage, Block Storage, DNS, and Load Balancers across 30+ global regions.
  url: https://www.vultr.com/
- name: Hetzner Cloud
  description: Hetzner Cloud is a German hyperscaler offering low-cost cloud servers, volumes, networks, and load balancers via a documented REST API with bearer token authentication.
  url: https://www.hetzner.com/cloud
- name: Scaleway
  description: Scaleway is a French cloud provider with REST APIs for Instances, Kubernetes (Kapsule), Object Storage, Serverless, Databases, and AI inference endpoints.
  url: https://www.scaleway.com/
- name: Cloudflare
  description: Cloudflare offers an edge-attached cloud (Workers, R2, D1, Durable Objects, Queues, AI Gateway) accessible via the Cloudflare REST API authenticated with API tokens.
  url: https://www.cloudflare.com/
- name: Fastly Compute
  description: Fastly Compute runs WebAssembly workloads at the edge. The Fastly REST API manages services, configurations, dictionaries, and Compute deployments.
  url: https://www.fastly.com/products/edge-compute
- name: CoreWeave
  description: CoreWeave is a GPU-first cloud focused on AI training and inference workloads. APIs are exposed primarily through Kubernetes-native CRDs and the CoreWeave Cloud REST API.
  url: https://www.coreweave.com/
- name: Crusoe Cloud
  description: Crusoe Cloud is a sustainable AI-first cloud powered by stranded and renewable energy. The REST API provisions GPU virtual machines, networking, storage, and projects programmatically.
  url: https://crusoecloud.com/
- name: Lambda Labs Cloud
  description: Lambda Cloud provides on-demand and reserved NVIDIA GPU instances. The REST API launches and terminates GPU instances, manages SSH keys, and lists instance types.
  url: https://lambdalabs.com/service/gpu-cloud
links:
- type: TrustCenter
  url: https://github.com/api-evangelist/cloud/blob/main/security/cloud-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/cloud/blob/main/security/cloud-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/cloud/blob/main/security/cloud-domain-security.yml
- type: Topic
  url: https://apievangelist.com/topics/cloud/
- type: API Evangelist
  url: https://apievangelist.com/
- type: Network
  url: https://network.apievangelist.com/
- type: GitHub
  url: https://github.com/api-evangelist
- type: Related Topic
  url: https://github.com/api-evangelist/cloud-storage
- type: Related Topic
  url: https://github.com/api-evangelist/cloud-native
provider_count: 147
providers:
- slug: microsoft-azure
  name: Microsoft Azure
  description: Microsoft Azure is a cloud computing platform and infrastructure for building, deploying, and managing applications and services through Microsoft-managed data centers.
  api_count: 697
  score_band: exemplar
  score_composite: 72.6
  shared: 4
- slug: oracle-cloud
  name: Oracle Cloud Infrastructure
  description: Oracle Cloud Infrastructure (OCI) is Oracle's public cloud, exposed as a REST control plane of 159 service APIs covering compute, virtual cloud networking, block and object storage, identity and access management, Autonomous Database, Kube…
  api_count: 9
  score_band: exemplar
  score_composite: 70.9
  shared: 4
- slug: amazon-ec2
  name: Amazon EC2
  description: Amazon Elastic Compute Cloud (EC2) provides resizable compute capacity in the cloud, allowing you to launch virtual server instances, manage networking, and configure storage with complete control over your computing resources.
  api_count: 1
  score_band: strong
  score_composite: 62.8
  shared: 4
- slug: microsoft-azure-virtual-machines
  name: Azure Virtual Machines
  description: Azure Virtual Machines (VMs) is one of several types of on-demand, scalable computing resources that Azure offers. VMs give you the flexibility of virtualization without having to buy and maintain physical hardware.
  api_count: 1
  score_band: strong
  score_composite: 54.4
  shared: 4
- slug: codesphere
  name: Codesphere
  description: Codesphere is a European-built sovereign cloud platform that lets organizations deploy and operate applications across on-premises, hybrid, and public-cloud infrastructure from a single control layer, without Kubernetes expertise or vendor…
  api_count: 1
  score_band: developing
  score_composite: 47.9
  shared: 4
- slug: aws
  name: Amazon Web Services (AWS)
  description: Amazon Web Services is a comprehensive collection of cloud computing services and APIs provided by Amazon, offering infrastructure as a service, platform as a service, and software as a service solutions globally.
  api_count: 12
  score_band: developing
  score_composite: 43.1
  shared: 4
- slug: evroc
  name: evroc
  description: evroc is a European sovereign cloud provider headquartered in Stockholm, Sweden, building cloud infrastructure for the AI era for organizations that require the highest level of data security and European data residency. Its platform spans…
  api_count: 0
  score_band: thin
  score_composite: 36.9
  shared: 4
- slug: projectx
  name: Projectx
  description: ProjectX is a San Francisco-based Y Combinator (Spring 2026) startup building Infinity (InfinityOS), a cloud operating system designed for AI agents. Infinity lets agents and humans orchestrate GPU workloads through a chat interface rather…
  api_count: 0
  score_band: minimal
  score_composite: 5.7
  shared: 4
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 2
  score_band: exemplar
  score_composite: 73.3
  shared: 3
- slug: oracle
  name: Oracle
  description: Collection of Oracle's APIs and developer resources across cloud infrastructure, databases, AI services, SaaS applications, and platform services.
  api_count: 161
  score_band: exemplar
  score_composite: 66.8
  shared: 3
- slug: nexgen-cloud
  name: NexGen Cloud
  description: NexGen Cloud Limited is a UK-headquartered AI cloud and GPU infrastructure provider. Its on-demand platform, Hyperstack, sells NVIDIA GPU and CPU virtual machines, managed Kubernetes clusters, block storage volumes, S3-compatible object st…
  api_count: 3
  score_band: strong
  score_composite: 65.6
  shared: 3
- slug: google-cloud-platform
  name: Google Cloud Platform
  description: Google Cloud Platform enables developers to build, test, and deploy applications on Google's highly-scalable and reliable infrastructure.
  api_count: 1
  score_band: strong
  score_composite: 59.4
  shared: 3
- slug: microsoft-azure-batch
  name: Microsoft Azure Batch
  description: Azure Batch is Microsoft’s managed job-scheduling and cluster-management service for large-scale parallel and high-performance computing workloads. You describe pools of virtual machines, jobs and tasks through a REST API; Batch allocates…
  api_count: 2
  score_band: strong
  score_composite: 57.8
  shared: 3
- slug: google-cloud-compute-engine
  name: Google Cloud Compute Engine
  description: Google Cloud Compute Engine delivers virtual machines running in Google's innovative data centers and worldwide fiber network. Compute Engine VMs boot quickly, come with persistent disk storage, and deliver consistent performance. It offer…
  api_count: 1
  score_band: developing
  score_composite: 46.0
  shared: 3
- slug: oxide-computer
  name: Oxide
  description: 'Oxide Computer Company builds a rack-scale cloud computer: integrated server sleds (Gimlet), a rack-level switch (Sidecar), Oxide''s own illumos distribution (Helios), the Propolis/bhyve hypervisor and the Crucible distributed block store,…'
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 3
- slug: digital-ocean
  name: Digital Ocean
  description: DigitalOcean Holdings, Inc. is an American multinational technology company and cloud service provider. The company is headquartered in New York City, New York, US, with 15 globally distributed data centers. DigitalOcean provides developer…
  api_count: 1
  score_band: developing
  score_composite: 45.4
  shared: 3
- slug: exoscale
  name: Exoscale
  description: Exoscale is a Swiss cloud infrastructure provider offering secure, reliable, and scalable cloud solutions to businesses of all sizes. Their services include virtual machines, object storage, networking, security, Kubernetes (SKS), Database…
  api_count: 1
  score_band: developing
  score_composite: 43.7
  shared: 3
- slug: jarvislabs
  name: JarvisLabs
  description: JarvisLabs.ai is a GPU cloud for AI development that lets you launch on-demand GPU and CPU instances (H100, H200, A100, RTX Pro 6000, A6000, A5000, L4, A30) from the terminal. Its Python SDK (jarvislabs / legacy jlclient) and jl CLI wrap a…
  api_count: 1
  score_band: developing
  score_composite: 41.5
  shared: 3
- slug: horizoniq
  name: HorizonIQ
  description: HorizonIQ (formerly INAP / Internap) is a US infrastructure provider delivering fully managed private cloud, bare metal servers, and GPU dedicated servers, along with block and object storage, backup and recovery, connectivity, load balanc…
  api_count: 1
  score_band: developing
  score_composite: 40.5
  shared: 3
- slug: railway-app
  name: Railway
  description: Railway is a cloud application deployment platform (PaaS) that builds, deploys, and scales services, databases, and cron jobs from a Git repository or Docker image. Its programmatic surface is a GraphQL-first Public API served at https://b…
  api_count: 13
  score_band: developing
  score_composite: 39.3
  shared: 3
- slug: thundercompute
  name: Thunder Compute
  description: Thunder Compute is a low-cost GPU cloud offering on-demand virtual GPU instances (T4, A6000, A100 80GB, L40, H100 PCIe) billed per minute. Developers provision and manage instances primarily through the tnr CLI, with a documented REST API…
  api_count: 1
  score_band: thin
  score_composite: 39.2
  shared: 3
- slug: apache-cloudstack
  name: Apache CloudStack
  description: Apache CloudStack is an open-source cloud computing platform developed by the Apache Software Foundation for creating, managing, and deploying infrastructure cloud services. It provides a comprehensive IaaS platform supporting multiple hyp…
  api_count: 4
  score_band: thin
  score_composite: 38.1
  shared: 3
- slug: shadeform
  name: Shadeform
  description: Shadeform is a GPU cloud marketplace that exposes a single REST API for deploying and managing GPU compute across many underlying clouds. One interface lets you compare real-time availability and per-GPU-hour pricing, then launch, inspect,…
  api_count: 1
  score_band: thin
  score_composite: 37.2
  shared: 3
- slug: shadow
  name: Shadow
  description: Shadow is a French cloud computing company founded in 2015, launched commercially in 2016, and chaired by OVHcloud founder Octave Klaba. It streams complete high-end Windows desktops (Shadow PC, Shadow PC Pro), sells Nextcloud-based storag…
  api_count: 1
  score_band: thin
  score_composite: 33.1
  shared: 3
- slug: inspur-cloud
  name: Inspur Cloud
  description: Inspur Cloud (浪潮云) is the public-cloud arm of the Chinese IT conglomerate Inspur Group, operating from cloud.inspur.com across the cn-north-3 (华北三), cn-south-1 (华南一) and cn-east-1 (华东一) regions. It publishes a broad IaaS/PaaS catalog — 94…
  api_count: 18
  score_band: thin
  score_composite: 32.0
  shared: 3
- slug: fluidstack
  name: Fluidstack
  description: Fluidstack is an AI cloud platform that builds and operates high-performance, single-tenant GPU clusters for top AI labs, governments, and enterprises. Founded in 2017 out of Oxford University and now headquartered in New York City, Fluids…
  api_count: 1
  score_band: thin
  score_composite: 29.3
  shared: 3
- slug: hpe
  name: Hewlett Packard Enterprise
  description: Hewlett Packard Enterprise (HPE) is a global edge-to-cloud technology company providing servers, storage, networking, and hybrid cloud services, with HPE GreenLake serving as the unified edge-to-cloud platform delivering infrastructure as…
  api_count: 1
  score_band: thin
  score_composite: 28.7
  shared: 3
- slug: specific
  name: Specific
  description: Specific is an infrastructure-as-code platform built for coding agents, positioned as "AWS for coding agents." Any coding agent (Claude Code, Cursor, Codex) defines its whole system in a single specific.hcl file — services, managed Postgre…
  api_count: 1
  score_band: emerging
  score_composite: 25.4
  shared: 3
- slug: cato-digital
  name: Cato Digital
  description: Cato Digital is a sustainable bare metal cloud provider that repurposes large-scale, second-life servers from hyperscalers like Meta and NVIDIA to deliver AI & GPU servers (up to 512GB VRAM), ephemeral application servers, and build-your-o…
  api_count: 0
  score_band: emerging
  score_composite: 15.0
  shared: 3
- slug: jd-technology
  name: JD Technology
  description: JD Technology Group (京东科技集团) is the technology and cloud subsidiary of JD.com, delivering digital-transformation services to government, financial institutions, and enterprises. Its primary developer surface is JD Cloud (京东云), a full-stack…
  api_count: 1
  score_band: emerging
  score_composite: 13.2
  shared: 3
---
