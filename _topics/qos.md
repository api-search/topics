---
layout: topic
slug: qos
name: QoS
kind: concept
description: Quality of Service (QoS) is the description or measurement of overall performance of a service, particularly in computer networking and telecommunications. QoS encompasses traffic prioritization, packet loss management, latency control, and bandwidth allocation to ensure reliable performance for applications such as VoIP, video streaming, and real-time systems.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/qos.png
tags:
- Quality of Service
- Networking
- Traffic Management
- Performance
area: reliability
repo: https://github.com/api-evangelist/qos
api_count: 0
apis: []
links: []
provider_count: 7
providers:
- slug: amazon-global-accelerator
  name: Amazon Global Accelerator
  description: Amazon Global Accelerator is a networking service that improves the performance and availability of applications with local or global users. It provides static IP addresses that act as a fixed entry point to your applications and uses the…
  api_count: 1
  score_band: strong
  score_composite: 59.4
  shared: 2
- slug: google-cloud-load-balancing
  name: Google Cloud Load Balancing
  description: Google Cloud Load Balancing provides high-performance, scalable load balancing for Google Cloud Platform services, distributing traffic across multiple instances, regions, and backends to ensure reliability and low latency.
  api_count: 1
  score_band: developing
  score_composite: 52.0
  shared: 2
- slug: f5-load-balancer
  name: F5 Load Balancer
  description: APIs for managing F5 BIG-IP Load Balancer configuration, monitoring, and operations. F5 BIG-IP is an application delivery controller that provides intelligent traffic management, load balancing, and application security.
  api_count: 3
  score_band: thin
  score_composite: 38.7
  shared: 2
- slug: bfe
  name: BFE
  description: BFE (Beyond Front End) is an open-source layer 7 load balancer developed by Baidu, providing advanced traffic routing, forwarding, and load balancing capabilities with support for HTTP, HTTPS, HTTP/2, WebSocket, TLS, and gRPC. BFE is a CNC…
  api_count: 3
  score_band: thin
  score_composite: 31.0
  shared: 2
- slug: ns1
  name: NS1
  description: NS1 (now IBM NS1 Connect) is a managed authoritative DNS, traffic management, and DDI platform. Its data-driven DNS steers traffic with real-time telemetry (Pulsar RUM), health-check monitoring, filter-chain traffic-steering policies, GeoD…
  api_count: 1
  score_band: emerging
  score_composite: 23.6
  shared: 2
- slug: merbridge
  name: Merbridge
  description: Merbridge is an open source, eBPF-based service mesh acceleration tool that replaces iptables rules with eBPF traffic interception and uses msg_redirect to shorten the datapath between sidecars and services. It is a CNCF Sandbox project an…
  api_count: 1
  score_band: emerging
  score_composite: 15.3
  shared: 2
- slug: http-2
  name: HTTP/2
  description: HTTP/2 is the second major version of the Hypertext Transfer Protocol, defined by the IETF in RFC 7540 and standardized in 2015. It optimizes use of network resources and reduces perceived latency by introducing a binary framing layer over…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
---
