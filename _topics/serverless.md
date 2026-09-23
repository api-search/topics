---
layout: topic
slug: serverless
name: Serverless
kind: topic
description: An index and topic collection covering serverless compute, function-as-a-service (FaaS) runtimes, and edge function platforms. Serverless platforms abstract away server management, scale on demand, and bill per invocation, letting developers ship event-driven functions, scheduled jobs, durable workflows, and HTTP endpoints without provisioning infrastructure. This collection includes hyperscaler functions like AWS Lambda, Azure Functions, and Google Cloud Functions; edge runtimes like Cloudflare Workers, Vercel Edge Functions, Fastly Compute@Edge, and Deno Deploy; container-based serverless like Google Cloud Run and AWS App Runner; WebAssembly-first platforms like Fermyon Spin and wasmCloud; durable workflow services like AWS Step Functions, Inngest, and Trigger.dev; and BaaS function runtimes like Supabase Functions, Firebase Functions, and Convex.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/apis-json-logo.jpg
tags:
- Serverless
- Functions as a Service
- Edge Functions
- Cold Start
- WebAssembly
- Function-as-a-Service
- Durable Workflows
repo: https://github.com/api-evangelist/serverless
api_count: 0
apis: []
links:
- type: Portal
  url: https://apievangelist.com
- type: GitHubOrganization
  url: https://github.com/api-evangelist
provider_count: 12
providers:
- slug: binaris
  name: Binaris
  description: Binaris was a fast, low-latency Function-as-a-Service (FaaS) platform for running production Node.js workloads in the cloud. Founded in 2017 and backed by Lightspeed Venture Partners, its developer surface centered on the `bn` command-line…
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 3
- slug: amazon-lambda
  name: Amazon Lambda
  description: AWS Lambda is a serverless compute service that lets you run code without provisioning or managing servers, automatically scaling and executing your code in response to events from over 200 AWS services and SaaS applications while you pay…
  api_count: 1
  score_band: strong
  score_composite: 61.8
  shared: 2
- slug: insforge
  name: Insforge
  description: InsForge is an open-source (Apache-2.0), agent-native cloud infrastructure platform built so that AI coding agents can provision and operate an entire backend end to end through a CLI and packaged agent skills instead of a human clicking t…
  api_count: 14
  score_band: strong
  score_composite: 57.3
  shared: 2
- slug: fermyon
  name: Fermyon
  description: Fermyon Wasm Functions is a multi-tenant, hosted, globally distributed engine for serverless functions running on Akamai Cloud, the most distributed cloud network. Fermyon is the company behind the Spin Framework and SpinKube, providing to…
  api_count: 2
  score_band: developing
  score_composite: 52.9
  shared: 2
- slug: azure-function-apps
  name: Azure Function Apps
  description: Azure Functions is a serverless compute service that lets you run event-triggered code without having to explicitly provision or manage infrastructure, with APIs for managing function apps, deployments, and runtime operations.
  api_count: 1
  score_band: developing
  score_composite: 48.2
  shared: 2
- slug: golem-cloud
  name: Golem
  description: Golem is an open-source durable computing platform for building agents and distributed applications that never lose state. You deploy WebAssembly components and invoke durable serverless workers through a REST API; the runtime transparentl…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 2
- slug: stack-machine
  name: Stack Machine
  description: StackMachine is elastic, headless infrastructure for AI applications and agents. It runs existing Node.js, Python, and PHP codebases as WebAssembly with sub-5ms cold starts and sandboxed execution for untrusted or AI-generated code, packin…
  api_count: 1
  score_band: developing
  score_composite: 39.8
  shared: 2
- slug: clockwork-labs
  name: Clockwork Labs
  description: 'Clockwork Labs is a San Francisco software company (founded 2019) that builds SpacetimeDB, a relational database that is also an application server: developers upload their schema and server-side business logic as a WebAssembly "module" (w…'
  api_count: 1
  score_band: thin
  score_composite: 36.8
  shared: 2
- slug: wasmedge
  name: WasmEdge
  description: WasmEdge is a lightweight, high-performance, and extensible WebAssembly runtime for cloud native, edge, and decentralized applications. It powers serverless apps, embedded functions, microservices, smart contracts, and IoT devices. WasmEdg…
  api_count: 5
  score_band: thin
  score_composite: 32.2
  shared: 2
- slug: spin
  name: Spin
  description: Spin is an open source framework by Fermyon for building and running fast, secure, and composable cloud microservices with WebAssembly. Spin provides a developer experience for creating event-driven serverless applications that compile to…
  api_count: 5
  score_band: thin
  score_composite: 31.1
  shared: 2
- slug: apache-openwhisk
  name: Apache OpenWhisk
  description: Apache OpenWhisk is an open-source serverless cloud platform that executes functions in response to events at any scale. It supports multiple programming languages and provides a rich programming model for creating serverless APIs and even…
  api_count: 6
  score_band: thin
  score_composite: 26.5
  shared: 2
- slug: suborbital
  name: Suborbital
  description: 'Suborbital was a developer-tools company building a WebAssembly-based extensibility platform: the Suborbital Extension Engine (SE2, formerly Suborbital Compute), a hosted service for running sandboxed third-party plugins; E2 Core / Reactr,…'
  api_count: 0
  score_band: null
  score_composite: 0
  shared: 2
---
