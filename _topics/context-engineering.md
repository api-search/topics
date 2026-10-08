---
layout: topic
slug: context-engineering
name: Context Engineering
kind: topic
description: Context engineering is the practice of curating the information that large language models receive at inference time so that the model can perform a task reliably and cost-effectively. It treats the context window as a finite attention budget and looks for the smallest set of high-signal tokens that maximize the likelihood of the desired outcome. Context engineering subsumes and extends prompt engineering, system prompts, tool design, retrieval, agent loops, structured note taking, compaction, and multi-agent decomposition. It is a foundational discipline for building production AI agents and assistants.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/context-engineering.png
tags:
- Agents
- Artificial Intelligence
- Anthropic
- Compaction
- Context Window
- LLM
- Memory
- Prompt Engineering
- RAG
- Tools
repo: https://github.com/api-evangelist/context-engineering
api_count: 5
apis:
- name: Effective Context Engineering for AI Agents
  description: Anthropic's engineering guide to context engineering, framing context as a finite attention budget and walking through system prompts, tool design, few-shot examples, just-in-time retrieval, compaction, structured note taking, and multi-ag…
  url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
- name: Retrieval-Augmented Generation (RAG)
  description: RAG is a context engineering pattern that augments LLM prompts with passages retrieved at inference time from a vector store, search index, or knowledge base. RAG keeps facts outside the model and is one of the most widely used context eng…
  url: https://arxiv.org/abs/2005.11401
- name: Prompt Engineering
  description: Prompt engineering is the discipline of crafting model instructions and examples to guide model behavior. Prompt engineering remains a sub-discipline of context engineering and includes techniques like role prompting, chain-of-thought, few…
  url: https://www.promptingguide.ai/
- name: Agentic Loops and Tool Use
  description: 'Agentic loops are iterative reasoning patterns in which an LLM plans, calls tools, observes results, and refines its plan. Tool design is a central context engineering concern: tools must be token-efficient, have minimal overlap, and inclu…'
  url: https://docs.anthropic.com/en/docs/build-with-claude/tool-use/overview
- name: Long-Horizon Context Strategies
  description: Long-horizon strategies handle conversations and tasks that exceed the context window. Techniques include compaction (summarizing history into a smaller representation), structured note taking (persistent external memory), and multi-agent…
  url: https://www.anthropic.com/news/contextual-retrieval
links:
- type: VulnerabilityDisclosure
  url: https://github.com/api-evangelist/context-engineering/blob/main/security/context-engineering-vulnerability-disclosure.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/context-engineering/blob/main/security/context-engineering-domain-security.yml
- type: Reference
  url: https://www.anthropic.com/engineering/effective-context-engineering-for-ai-agents
- type: Reference
  url: https://www.promptingguide.ai/
- type: Reference
  url: https://docs.anthropic.com/en/docs/build-with-claude/prompt-engineering/overview
- type: Reference
  url: https://docs.llamaindex.ai/
- type: Reference
  url: https://python.langchain.com/docs/concepts/rag/
provider_count: 561
providers:
- slug: cognee
  name: Cognee
  description: Cognee is an open-source AI memory and knowledge graph platform that enables developers to build persistent, structured memory for AI agents and LLM applications. The platform provides a REST API and Python/TypeScript SDKs for ingesting do…
  api_count: 1
  score_band: developing
  score_composite: 49.5
  shared: 5
- slug: anthropic
  name: Anthropic
  description: Anthropic is an AI safety company and the creator of the Claude family of large language models (Opus, Sonnet, Haiku, and the Fable/Mythos frontier line). The Claude Developer Platform exposes them through a single REST API at api.anthropi…
  api_count: 6
  score_band: exemplar
  score_composite: 79.4
  shared: 4
- slug: dust-tt
  name: Dust
  description: Dust is a Paris-based enterprise AI platform for building, deploying, and operating teams of AI agents that have shared context across a company's knowledge and tools. Dust positions itself as the platform for "AI Operators" — the people w…
  api_count: 9
  score_band: exemplar
  score_composite: 73.0
  shared: 4
- slug: seekr
  name: Seekr
  description: Seekr Technologies builds explainable, auditable, sovereign AI for regulated industries and high-stakes government missions. Its platform, SeekrFlow, is an end-to-end AI operating system that covers document ingestion and AI-ready data pre…
  api_count: 8
  score_band: strong
  score_composite: 63.0
  shared: 4
- slug: compresr
  name: Compresr
  description: Compresr is an LLM context-compression API. You send the long context you would otherwise pass to a model plus the query you want answered, and Compresr returns a shorter context that keeps the answer-bearing spans and drops the rest — few…
  api_count: 1
  score_band: strong
  score_composite: 61.0
  shared: 4
- slug: amazon-bedrock
  name: Amazon Bedrock
  description: Amazon Bedrock is a fully managed AWS service that makes high-performing foundation models from leading AI companies available through a unified API for building generative AI applications. It supports text and image generation, conversati…
  api_count: 2
  score_band: strong
  score_composite: 55.0
  shared: 4
- slug: vectara
  name: Vectara
  description: Vectara is a Retrieval Augmented Generation (RAG) as a service platform that provides grounded generative AI for enterprises. The API-first platform exposes a unified REST API v2 for managing corpora, ingesting documents, performing semant…
  api_count: 1
  score_band: strong
  score_composite: 54.8
  shared: 4
- slug: pydantic-ai
  name: PydanticAI
  description: PydanticAI is an open-source, model-agnostic Python agent framework built by the Pydantic team, designed to bring the ergonomic, type-safe design philosophy of FastAPI to production-grade generative AI application development. It provides…
  api_count: 2
  score_band: strong
  score_composite: 54.5
  shared: 4
- slug: letta
  name: Letta
  description: Letta (formerly MemGPT) is a stateful AI agents platform built around long-term memory, tool execution, and multi-agent coordination. The Letta REST API exposes 239 endpoints across 36 public resource categories — agents, memory blocks, ar…
  api_count: 2
  score_band: developing
  score_composite: 52.4
  shared: 4
- slug: ragflow
  name: RAGFlow
  description: RAGFlow is the open-source Retrieval-Augmented Generation engine built by InfiniFlow Inc. It combines deep document understanding (DeepDoc parsing of PDFs, images, tables and scanned files) with hybrid retrieval — dense vector search, BM25…
  api_count: 1
  score_band: developing
  score_composite: 47.8
  shared: 4
- slug: stacks-ai
  name: Stacks Ai
  description: StackAI (Stack AI, Inc.) is an enterprise AI agent platform that lets teams build, deploy, and govern no-code agentic workflows at scale. Its visual Workflow Builder chains LLMs, knowledge bases, connections, and logic nodes into productio…
  api_count: 1
  score_band: developing
  score_composite: 46.3
  shared: 4
- slug: flowise
  name: Flowise
  description: Flowise is an open-source, low-code visual builder for LangChain-based LLM workflows and AI agents. Built on Node.js and TypeScript as a pnpm/Turbo monorepo, Flowise lets developers and non-developers compose chatflows, multi-agent agentfl…
  api_count: 1
  score_band: developing
  score_composite: 45.8
  shared: 4
- slug: ai21-labs
  name: AI21 Labs
  description: AI21 Labs is an enterprise foundation-model company best known for the Jamba family of open-weight hybrid Mamba/Transformer models and AI21 Maestro, a dynamic planning system that orchestrates tools, retrieval, and validated output during…
  api_count: 1
  score_band: developing
  score_composite: 40.6
  shared: 4
- slug: julep
  name: Julep
  description: Julep is an open-source platform for building stateful AI agents that remember past interactions and execute long-running, multi-step tasks. Its cloud API and self-hostable server expose agents, sessions, tasks, executions, documents (RAG)…
  api_count: 1
  score_band: thin
  score_composite: 36.9
  shared: 4
- slug: langbase
  name: Langbase
  description: Langbase is a serverless AI developer platform for building, deploying, and scaling AI agents and applications. Its composable primitives - Pipes (agents), Memory (managed RAG), Threads, Agent (one API over 100+ LLMs), Tools, Parser, Chunk…
  api_count: 1
  score_band: thin
  score_composite: 35.3
  shared: 4
- slug: ondemand
  name: Ondemand
  description: OnDemand AI (on-demand.io) is a RAG-powered AI Platform-as-a-Service that lets companies infuse AI into their products without managing model infrastructure. The platform exposes a REST API for chat sessions and queries against a library o…
  api_count: 1
  score_band: thin
  score_composite: 34.3
  shared: 4
- slug: adapter
  name: Adapter
  description: Adapter is a cognition API — a persistent memory and knowledge-graph layer that sits alongside AI models so understanding is already available when agents need answers. Founded by Adam Ghetti and David Bader, Adapter continuously reads and…
  api_count: 1
  score_band: thin
  score_composite: 32.8
  shared: 4
- slug: miriel
  name: Miriel
  description: 'Miriel is the context engine and platform for AI-native development. It gives AI apps and agents the context they need in real time through a simple API: developers connect a data source with the learn operation and retrieve relevant conte…'
  api_count: 7
  score_band: emerging
  score_composite: 24.8
  shared: 4
- slug: dify
  name: Dify
  description: Dify is an open-source platform for building AI applications, combining Backend-as-a-Service and LLMOps to streamline the development of generative AI solutions for developers and non-technical innovators alike. Teams build agentic workflo…
  api_count: 2
  score_band: exemplar
  score_composite: 75.3
  shared: 3
- slug: exa-ai
  name: Exa
  description: Exa is a web search API and AI research platform built specifically for LLMs and agents — semantic and keyword search across the open web with token-efficient highlights, structured outputs, sub-200ms latency tiers, and verticals for code,…
  api_count: 7
  score_band: strong
  score_composite: 58.5
  shared: 3
- slug: edgee
  name: Edgee
  description: Edgee is a French edge-native AI Gateway that sits between coding agents and LLM providers, intercepting, routing, compressing, metering and securing every request. Its OpenAI-compatible gateway API at edgee.io exposes chat completions, an…
  api_count: 1
  score_band: strong
  score_composite: 58.3
  shared: 3
- slug: perplexity
  name: Perplexity
  description: Perplexity AI is an answer engine that delivers accurate answers to complex questions using large language models with real-time web search capabilities.
  api_count: 1
  score_band: strong
  score_composite: 57.0
  shared: 3
- slug: llamaparse
  name: LlamaParse
  description: LlamaParse is an enterprise document parsing and AI pipeline platform from LlamaIndex that converts complex PDFs, Office files, and 130+ document formats into LLM-ready structured outputs. The platform offers six composable products under…
  api_count: 1
  score_band: strong
  score_composite: 56.7
  shared: 3
- slug: h2o-ai
  name: H2O.ai
  description: H2O.ai is an open-source artificial-intelligence and machine-learning company whose platform spans H2O-3 (a distributed, in-memory ML engine), H2O Driverless AI (automatic machine learning), H2O MLOps (model deployment, scoring and monitor…
  api_count: 2
  score_band: strong
  score_composite: 56.3
  shared: 3
- slug: serper
  name: Serper
  description: Serper is the world's fastest and most affordable Google Search API, delivering real-time SERP data in 1-2 seconds via a simple REST interface. It supports web search, images, news, maps, places, videos, shopping, scholar, patents, and aut…
  api_count: 2
  score_band: strong
  score_composite: 56.3
  shared: 3
- slug: scorecard
  name: Scorecard
  description: Scorecard is a simulation and evaluation platform for building, testing, and deploying frontier AI agents. Teams run their agents through thousands of realistic scenarios, judge outputs with configurable AI, human, and heuristic metrics, a…
  api_count: 1
  score_band: developing
  score_composite: 53.0
  shared: 3
- slug: sambanova-systems
  name: SambaNova Systems
  description: SambaNova Systems is an AI infrastructure company that builds custom Reconfigurable Dataflow Unit (RDU) chips and the SambaCloud, SambaStack, and SambaRack platforms for fast, energy-efficient AI inference. Its developer-facing product, Sa…
  api_count: 2
  score_band: developing
  score_composite: 52.7
  shared: 3
- slug: dedaluslabs
  name: Dedalus Labs
  description: 'Dedalus Labs builds infrastructure for AI agents. It runs two production APIs: the Dedalus Agents API, an OpenAI-compatible MCP gateway that lets you mix and match any model from any provider with tools drawn from the Dedalus MCP marketpla…'
  api_count: 2
  score_band: developing
  score_composite: 52.6
  shared: 3
- slug: h-company
  name: H Company
  description: H Company (hcompany.ai) is a Paris-based AI lab, backed by Accel and Creandum, that builds the Holo family of vision-language models and a Computer-Use Agents platform for automating work on browsers and desktops. It ships two public APIs:…
  api_count: 1
  score_band: developing
  score_composite: 51.8
  shared: 3
- slug: gemini
  name: Gemini
  description: Google's Gemini API provides access to state-of-the-art generative AI models for text generation, multimodal understanding, code generation, and more.
  api_count: 1
  score_band: developing
  score_composite: 50.1
  shared: 3
---
