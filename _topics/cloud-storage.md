---
layout: topic
slug: cloud-storage
name: Cloud Storage
kind: topic
description: Cloud Storage is a topic profile in the API Evangelist Network covering the major cloud and S3-compatible object, file, and block storage APIs. The topic indexes the canonical hyperscaler offerings (Amazon S3, Google Cloud Storage, Azure Blob Storage) alongside S3-compatible alternatives (Wasabi, Backblaze B2, MinIO, Cloudflare R2, IBM Cloud Object Storage, DigitalOcean Spaces, Linode Object Storage), file storage (Amazon EFS, Google Filestore, Azure Files), and block storage (Amazon EBS, Google Persistent Disk, Azure Managed Disks). It is the parent topic to more specialized profiles in the network such as cloud-storage-and-data-acquisition.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/cloud-storage.png
tags:
- Block Storage
- Cloud
- Cloud Storage
- File Storage
- Object Storage
- S3 Compatible
- Storage
repo: https://github.com/api-evangelist/cloud-storage
api_count: 11
apis:
- name: Amazon S3
  description: Amazon Simple Storage Service (S3) is the de-facto standard cloud object store. Its REST API at s3.amazonaws.com supports buckets, objects, multipart uploads, lifecycle rules, server- side encryption, replication, and event notifications.
  url: https://aws.amazon.com/s3/
- name: Google Cloud Storage
  description: Google Cloud Storage provides unified object storage with the JSON API at storage.googleapis.com. It supports buckets, objects, IAM, customer-managed encryption keys, and Pub/Sub change notifications.
  url: https://cloud.google.com/storage
- name: Azure Blob Storage
  description: Azure Blob Storage offers block, append, and page blob types through the Blob service REST API. It supports access tiers, lifecycle management, lease semantics, and Event Grid integration for change notifications.
  url: https://azure.microsoft.com/en-us/services/storage/blobs/
- name: Cloudflare R2
  description: Cloudflare R2 is a zero-egress-fee object store with an S3-compatible API. R2 buckets are accessed at <accountid>.r2.cloudflarestorage.com and integrate with Cloudflare Workers for edge-computed access patterns.
  url: https://www.cloudflare.com/products/r2/
- name: Backblaze B2 Cloud Storage
  description: Backblaze B2 Cloud Storage provides low-cost object storage with a native B2 API and an S3-compatible API. It is widely used as a backup and media storage target.
  url: https://www.backblaze.com/cloud-storage
- name: Wasabi Hot Cloud Storage
  description: Wasabi Hot Cloud Storage offers S3-compatible object storage at a flat per-TB price with no egress or API request fees. It is positioned as a hot tier replacement for S3.
  url: https://wasabi.com/
- name: MinIO
  description: MinIO is a high-performance, S3-compatible object store designed for AI/ML, analytics, and on-premises private cloud use cases. It can be deployed standalone or as a distributed erasure-coded cluster.
  url: https://min.io/
- name: IBM Cloud Object Storage
  description: IBM Cloud Object Storage exposes an S3-compatible API and Aspera high-speed transfer integrations. It supports SmartTier placement and Immutable Object Storage.
  url: https://www.ibm.com/cloud/object-storage
- name: DigitalOcean Spaces
  description: DigitalOcean Spaces is an S3-compatible object store with a built-in CDN, designed for developers building on the DigitalOcean platform.
  url: https://www.digitalocean.com/products/spaces
- name: Amazon EFS
  description: Amazon Elastic File System (EFS) is a managed NFS file system for Linux workloads. The control-plane API manages file systems, mount targets, lifecycle policies, and access points.
  url: https://aws.amazon.com/efs/
- name: Amazon EBS
  description: Amazon Elastic Block Store (EBS) provides persistent block volumes for EC2. The control-plane API manages volumes, snapshots, encryption, and direct snapshot access.
  url: https://aws.amazon.com/ebs/
links:
- type: TrustCenter
  url: https://github.com/api-evangelist/cloud-storage/blob/main/security/cloud-storage-trust-center.yml
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/cloud-storage/blob/main/security/cloud-storage-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/cloud-storage/blob/main/security/cloud-storage-domain-security.yml
- type: Topic
  url: https://apievangelist.com/topics/cloud-storage/
- type: API Evangelist
  url: https://apievangelist.com/
- type: Network
  url: https://network.apievangelist.com/
- type: GitHub
  url: https://github.com/api-evangelist
- type: Related Topic
  url: https://github.com/api-evangelist/cloud-storage-and-data-acquisition
- type: JSONLD
  url: https://github.com/api-evangelist/cloud-storage/blob/main/json-ld/cloud-storage-context.jsonld
- type: Spectral
  url: https://github.com/api-evangelist/cloud-storage/blob/main/rules/cloud-storage-rules.yml
provider_count: 70
providers:
- slug: pure-storage
  name: Pure Storage
  description: Pure Storage is an American publicly traded technology company specializing in all-flash data storage hardware and software products. The company provides enterprise data storage platforms including FlashArray, FlashBlade, and Pure1 fleet…
  api_count: 3
  score_band: developing
  score_composite: 52.6
  shared: 5
- slug: gcp-cloud-storage
  name: Google Cloud Storage
  description: Object storage service offering high durability, availability, and scalability for storing and accessing data on Google Cloud Platform.
  api_count: 1
  score_band: strong
  score_composite: 65.0
  shared: 4
- slug: rook
  name: Rook
  description: Rook is a CNCF graduated cloud-native storage orchestrator for Kubernetes, providing the platform, framework, and support for Ceph distributed storage systems to natively integrate with cloud-native environments. It automates the deploymen…
  api_count: 1
  score_band: developing
  score_composite: 42.7
  shared: 4
- slug: cloudflare-r2
  name: Cloudflare R2
  description: Cloudflare R2 is S3-compatible object storage with zero egress fees. It provides both an S3-compatible REST API and a Cloudflare API for managing buckets, objects, and storage policies at global scale. R2 offers a generous free tier includ…
  api_count: 2
  score_band: developing
  score_composite: 42.5
  shared: 4
- slug: cubbit
  name: Cubbit
  description: Cubbit is a European cloud storage provider offering DS3, a sovereign, geo-distributed, S3-compatible object storage platform. DS3 encrypts (AES-256), fragments, and replicates data across multiple user-selected locations using Reed-Solomo…
  api_count: 1
  score_band: thin
  score_composite: 39.0
  shared: 4
- slug: filebase
  name: Filebase
  description: Filebase is an S3-compatible object storage and IPFS pinning platform that combines familiar cloud storage APIs with decentralized, blockchain-backed infrastructure. Developers can store, manage, and pin files to IPFS using standard S3 too…
  api_count: 4
  score_band: thin
  score_composite: 38.3
  shared: 4
- slug: storone
  name: StorONE
  description: StorONE builds S1, a software-defined enterprise storage platform that consolidates block, file and object storage onto a single hardware-agnostic engine, with auto-tiering across flash and disk, snapshots, replication, erasure coding and…
  api_count: 1
  score_band: thin
  score_composite: 34.0
  shared: 4
- slug: xsky
  name: XSKY
  description: XSKY (XSKY Data Technology, 星辰天合) is a Beijing-based software-defined storage vendor serving nearly 2,000 large government and enterprise institutions, ranked first in China's object-storage software market. Its distributed storage product…
  api_count: 1
  score_band: thin
  score_composite: 31.5
  shared: 4
- slug: wasabi
  name: Wasabi
  description: Wasabi Hot Cloud Storage is an S3-compatible object storage service offering a REST API that mirrors the Amazon S3 API for storing, retrieving, and managing objects and buckets. Wasabi provides always-consistent storage at lower cost than…
  api_count: 4
  score_band: thin
  score_composite: 30.9
  shared: 4
- slug: ceph
  name: Ceph
  description: Ceph is an open source, distributed storage platform that provides unified object, block, and file storage on commodity hardware with no single point of failure. The Ceph Manager (ceph-mgr) ships with a RESTful API that exposes the same op…
  api_count: 1
  score_band: emerging
  score_composite: 25.1
  shared: 4
- slug: storj
  name: Storj
  description: Decentralized Open-Source Cloud Storage
  api_count: 1
  score_band: minimal
  score_composite: 6.0
  shared: 4
- slug: amazon-s3
  name: Amazon S3
  description: Amazon Simple Storage Service (S3) is an object storage service offering industry-leading scalability, data availability, security, and performance.
  api_count: 2
  score_band: exemplar
  score_composite: 69.7
  shared: 3
- slug: microsoft-azure-blob-storage
  name: Azure Blob Storage
  description: Microsoft Azure Blob Storage is a service for storing large amounts of unstructured object data, such as text or binary data, that can be accessed from anywhere in the world via HTTP or HTTPS.
  api_count: 1
  score_band: strong
  score_composite: 58.3
  shared: 3
- slug: minio
  name: MinIO
  description: MinIO is a high-performance, S3-compatible object storage system built for large-scale AI, analytics, and cloud-native data infrastructure. Its API is a drop-in implementation of the Amazon S3 REST API (bucket and object operations, multip…
  api_count: 2
  score_band: developing
  score_composite: 50.9
  shared: 3
- slug: azure-storage-accounts
  name: Azure Storage Accounts
  description: Azure Storage is Microsoft's cloud storage solution for modern data storage scenarios offering highly available, massively scalable, durable, and secure storage for blobs, files, queues, tables, and disks.
  api_count: 2
  score_band: developing
  score_composite: 49.5
  shared: 3
- slug: backblaze
  name: Backblaze
  description: Backblaze is a cloud storage and data backup provider offering B2 Cloud Storage - a low-cost, S3-compatible object storage service. Backblaze provides both a native B2 API and an S3-compatible API, enabling developers to build applications…
  api_count: 7
  score_band: developing
  score_composite: 48.2
  shared: 3
- slug: impossible-cloud
  name: Impossible Cloud
  description: Impossible Cloud is a European sovereign cloud platform headquartered in Hamburg, Germany, providing S3-compatible object storage (11 nines durability, Object Lock/WORM, no egress or API-call fees), bare metal NVIDIA GPU servers, and manag…
  api_count: 1
  score_band: developing
  score_composite: 47.2
  shared: 3
- slug: cubefs
  name: CubeFS
  description: CubeFS is a CNCF graduated cloud-native distributed file system supporting POSIX, HDFS, and S3-compatible object storage protocols. It provides multi-tenancy, multi-AZ deployment, cross-region replication, and erasure coding for both hot a…
  api_count: 2
  score_band: developing
  score_composite: 43.8
  shared: 3
- slug: qumulo
  name: Qumulo
  description: Qumulo is an enterprise data platform company that delivers a single, unified file and object storage system spanning on-premises data centers, the edge, and the public cloud (AWS, Azure, GCP) at exabyte scale. Every Qumulo cluster exposes…
  api_count: 1
  score_band: developing
  score_composite: 39.8
  shared: 3
- slug: azure-file-storage
  name: Azure Files
  description: Azure Files is a fully managed cloud file share service from Microsoft Azure that provides hosted SMB and NFS file shares accessible from cloud and on-premises clients using standard file system protocols and the FileREST HTTPS API. It sup…
  api_count: 1
  score_band: thin
  score_composite: 38.0
  shared: 3
- slug: tigris-data
  name: Tigris
  description: Tigris is a globally distributed, multi-cloud, S3-compatible object storage service. Data is automatically placed close to where it is read for low latency worldwide, with no egress fees. The storage API speaks the AWS S3 protocol at https…
  api_count: 1
  score_band: thin
  score_composite: 36.4
  shared: 3
- slug: inspur-cloud
  name: Inspur Cloud
  description: Inspur Cloud (浪潮云) is the public-cloud arm of the Chinese IT conglomerate Inspur Group, operating from cloud.inspur.com across the cn-north-3 (华北三), cn-south-1 (华南一) and cn-east-1 (华东一) regions. It publishes a broad IaaS/PaaS catalog — 94…
  api_count: 18
  score_band: thin
  score_composite: 34.0
  shared: 3
- slug: emc
  name: EMC
  description: EMC Corporation, acquired by Dell Technologies in 2016 and now operating as Dell EMC, builds enterprise storage, data management and data protection platforms — ECS/ObjectScale object storage, Unity, VNX, PowerMax (VMAX lineage), PowerScal…
  api_count: 2
  score_band: thin
  score_composite: 31.9
  shared: 3
- slug: ctera
  name: CTERA
  description: CTERA operates the CTERA Intelligent Data Platform, a unified edge-to-cloud global file system and data fabric for managing unstructured file data across distributed enterprises. The platform combines secure file collaboration, cyber prote…
  api_count: 1
  score_band: thin
  score_composite: 28.5
  shared: 3
- slug: openio
  name: OpenIO
  description: OpenIO SDS is an open-source, software-defined object storage platform for building hyper-scalable, high-performance storage infrastructures. It stores data across commodity hardware and exposes it through an Amazon S3-compatible gateway a…
  api_count: 1
  score_band: emerging
  score_composite: 17.2
  shared: 3
- slug: elastifile
  name: Elastifile
  description: Elastifile was an enterprise cloud file-storage company founded in 2013 in Tel Aviv, Israel. It built a software-defined, scale-out distributed file system (the Elastifile Cloud File System / ECFS) that delivered elastic, high-performance…
  api_count: 0
  score_band: minimal
  score_composite: 2.5
  shared: 3
- slug: avere-systems
  name: Avere Systems
  description: Avere Systems was a Pittsburgh-based enterprise storage company building hybrid cloud NAS technology, best known for its FXT Series Edge filers and the vFXT virtual appliance that accelerated and tiered file workloads across on-premises NA…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: bitcasa
  name: Bitcasa
  description: Bitcasa, Inc. was an American cloud storage company (founded 2011 in St. Louis, Missouri; later based in Mountain View, California) known for its converged/infinite storage model and, for developers, the CloudFS API — a white-label cloud-s…
  api_count: 0
  score_band: minimal
  score_composite: 0
  shared: 3
- slug: cloudflare
  name: Cloudflare
  description: Cloudflare is a global network designed to make everything you connect to the Internet secure, private, fast, and reliable.
  api_count: 25
  score_band: exemplar
  score_composite: 80.6
  shared: 2
- slug: amazon-lightsail
  name: Amazon Lightsail
  description: Amazon Lightsail is a virtual private server (VPS) provider and is the easiest way to get started with AWS for developers, small businesses, students, and other users who need a solution to build and host their applications on cloud. Light…
  api_count: 3
  score_band: exemplar
  score_composite: 75.3
  shared: 2
---
