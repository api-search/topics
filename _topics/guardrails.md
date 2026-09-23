---
layout: topic
slug: guardrails
name: AI Guardrails
kind: topic
description: AI Guardrails are runtime and design-time controls that screen the inputs and outputs of large language model (LLM) applications and AI agents. They detect and block prompt injection, jailbreak attempts, personally identifiable information (PII) leakage, toxic or unsafe content, hallucinations, and policy violations, and they validate structured outputs against schemas. This topic repository catalogs the vendor and open-source landscape — provider-native guardrails (AWS Bedrock, Azure Content Safety, Google Model Armor, OpenAI Moderation), third-party AI security platforms (Lakera, HiddenLayer, Cisco AI Defense, Lasso Security, PromptArmor, Wallarm), and open-source frameworks (Guardrails AI, NVIDIA NeMo Guardrails, DeepEval) — and provides a shared vocabulary, JSON Schema for policy and violation records, JSON-LD context, and example payloads.
image: https://kinlane-images.s3.amazonaws.com/shared/apis-json/icons/guardrails.png
tags:
- AI Safety
- AI Security
- Content Moderation
- Guardrails
- Jailbreak Detection
- LLM Security
- PII Detection
- Prompt Injection
- Responsible AI
repo: https://github.com/api-evangelist/guardrails
api_count: 14
apis:
- name: Guardrails AI
  description: Open-source Python framework and commercial Hub for adding programmable input/output validators to LLM applications. Validators cover regex, PII, toxic language, competitor mentions, jailbreak attempts, and structured-output schema enforce…
  url: https://www.guardrailsai.com/
- name: NVIDIA NeMo Guardrails
  description: Open-source toolkit for adding programmable guardrails to LLM-based conversational systems. Implements five rail types — input, output, dialog, retrieval, and execution — using the Colang modeling language. Integrates with OpenAI, LLaMa, F…
  url: https://docs.nvidia.com/nemo/guardrails/
- name: Lakera AI
  description: AI-native security platform protecting generative AI applications and agents from prompt injection, data leakage, toxic content, and compliance risks. Products include Lakera Guard (runtime API), Workforce AI Security, AI Agent Security, A…
  url: https://www.lakera.ai/
- name: Microsoft Azure AI Content Safety — Prompt Shields
  description: Unified API in Azure AI Content Safety that detects and blocks adversarial user-prompt attacks and indirect document attacks on LLMs. Replaces the earlier Jailbreak risk detection service. Detects role-play, system-rule changes, conversati…
  url: https://learn.microsoft.com/en-us/azure/ai-services/content-safety/concepts/jailbreak-detection
- name: Amazon Bedrock Guardrails
  description: Configurable safeguards on Amazon Bedrock providing content filters, denied topics, word filters, sensitive-information (PII) filters, contextual grounding checks (hallucination detection in RAG), and Automated Reasoning checks. Invokable…
  url: https://docs.aws.amazon.com/bedrock/latest/userguide/guardrails.html
- name: OpenAI Moderation API
  description: Free OpenAI endpoint that classifies text and images across harmful-content categories including sexual, hate, harassment, self-harm, violence, and illicit. Multimodal moderation model is omni-moderation-latest.
  url: https://platform.openai.com/docs/guides/moderation
- name: Google Cloud Model Armor
  description: Google Cloud service that screens LLM prompts and responses for prompt injection, jailbreak attacks, sensitive data (PII, credit cards, SSNs, API keys), harmful content (hate, harassment, sexual, dangerous, CSAM), and malicious URLs. State…
  url: https://docs.cloud.google.com/security-command-center/docs/model-armor-overview
- name: HiddenLayer
  description: AI security platform spanning AI Discovery, AI Supply Chain Security, AI Attack Simulation, and AI Runtime Security. Defends against prompt injection, jailbreaks, model manipulation, data leakage, and supply-chain compromise using determin…
  url: https://hiddenlayer.com/
- name: Cisco AI Defense (formerly Robust Intelligence)
  description: Cisco AI Defense — the productization of the Robust Intelligence acquisition — provides AI model validation, runtime protection, and continuous algorithmic red teaming for production LLM and ML applications. Covers prompt injection, jailbr…
  url: https://www.cisco.com/site/us/en/products/security/ai-defense/index.html
- name: Lasso Security
  description: Enterprise AI security platform providing Intent Security, AI Discovery and AI-BOM, Automated AI Red Teaming, AI Detection and Response, and Runtime Enforcement. Deploys at the proxy, API, or AI gateway layer.
  url: https://www.lasso.security/
- name: PromptArmor
  description: Third-party AI risk and assurance platform spanning TPRM, InfoSec, GRC, and Privacy. Assesses risk across 26 vectors aligned with OWASP LLM Top 10, NIST AI RMF, and MITRE Atlas. Best known for research on indirect prompt injection in Claud…
  url: https://promptarmor.com/
- name: Wallarm AI Security
  description: Wallarm extends its API security platform with AI-specific protections covering the OWASP LLM Top 10, prompt injection, and abuse of LLM-backed API endpoints. Deploys as a sidecar, reverse proxy, or in-line API gateway.
  url: https://www.wallarm.com/product/ai-security
- name: Confident AI
  description: AI quality and safety platform behind the open-source DeepEval evaluation framework and DeepTeam red-teaming framework. Provides LLM evaluation, observability, and red-teaming for OWASP Top 10 for Agentic Applications risks including goal…
  url: https://www.confident-ai.com/
- name: Layerup AI
  description: Note Layerup AI has pivoted toward agentic AI for insurance workflows (claims, underwriting). Earlier positioning included LLM guardrails and PII redaction; the current product surface focuses on insurance automation rather than horizontal…
  url: https://uselayerup.com/
links:
- type: IssueTracker
  url: https://github.com/api-evangelist/guardrails/issues
- type: TrustCenter
  url: https://github.com/api-evangelist/guardrails/blob/main/security/guardrails-trust-center.yml
- type: DomainSecurity
  url: https://github.com/api-evangelist/guardrails/blob/main/security/guardrails-domain-security.yml
- type: Repository
  url: https://github.com/api-evangelist/guardrails
- type: JSONSchema
  url: https://github.com/api-evangelist/guardrails/blob/main/json-schema/guardrail-policy-schema.json
- type: JSONSchema
  url: https://github.com/api-evangelist/guardrails/blob/main/json-schema/guardrail-violation-schema.json
- type: JSONLD
  url: https://github.com/api-evangelist/guardrails/blob/main/json-ld/guardrails-context.jsonld
- type: Vocabulary
  url: https://github.com/api-evangelist/guardrails/blob/main/vocabulary/guardrails-vocabulary.yml
- type: Examples
  url: https://github.com/api-evangelist/guardrails/blob/main/examples/
- type: LlmsText
  url: https://docs.lakera.ai/llms.txt
provider_count: 28
providers:
- slug: activefence
  name: ActiveFence
  description: 'ActiveFence — now operating as Alice — is an AI security, safety and trust & safety company headquartered in New York and Tel Aviv. It sells two product families through one REST API at api.alice.io: ActiveFamily (ActiveScore automated det…'
  api_count: 2
  score_band: developing
  score_composite: 51.3
  shared: 6
- slug: lakera
  name: Lakera
  description: Lakera is an AI security company building runtime defenses for generative AI applications. Its flagship Lakera Guard API screens prompts and responses for prompt injection, jailbreaks, PII leakage, unsafe content, and policy violations, wh…
  api_count: 1
  score_band: developing
  score_composite: 41.6
  shared: 4
- slug: gray-swan
  name: Gray Swan
  description: Gray Swan AI is an AI security company that helps enterprises deploy AI with confidence. Its Cygnal product is a real-time, drop-in secure proxy that fronts LLM providers (OpenAI, Anthropic, and Gemini request formats) with input/output fi…
  api_count: 1
  score_band: developing
  score_composite: 40.8
  shared: 4
- slug: silmaril
  name: Silmaril
  description: Silmaril is a Y Combinator-backed runtime security company that builds an AI application firewall for agentic systems. The Silmaril Firewall classifies prompts, retrieved context, tool calls, tool responses, model output, and accumulated e…
  api_count: 1
  score_band: thin
  score_composite: 32.2
  shared: 4
- slug: vijil
  name: Vijil
  description: 'Vijil is an AI agent trust platform (Mayfield-backed, ~$23M raised) that helps enterprises make AI agents reliable, secure, and safe for production. Its Console API and CLI span four products across the agent lifecycle: Diamond (pre-deploy…'
  api_count: 1
  score_band: developing
  score_composite: 48.0
  shared: 3
- slug: alice
  name: Alice
  description: Alice (formerly ActiveFence) is an enterprise AI security, safety, and trust platform for the GenAI era. Its WonderSuite platform stress-tests, guards, and monitors AI models, applications, and agents against jailbreaks, prompt injection,…
  api_count: 1
  score_band: developing
  score_composite: 44.2
  shared: 3
- slug: trojai
  name: TrojAI
  description: TrojAI is an enterprise AI security platform (acquired by A10 Networks) that lets organizations deploy AI models and agents safely. Its two products — TrojAI Detect (generative-AI red teaming, model robustness stress-testing, and integrity…
  api_count: 1
  score_band: thin
  score_composite: 36.9
  shared: 3
- slug: robust-intelligence
  name: Robust Intelligence
  description: Robust Intelligence is an AI security company founded in 2019 to defend ML and GenAI systems against adversarial attacks, data poisoning, prompt injection, and unsafe outputs. Its platform combined automated red teaming (Algorithmic AI Red…
  api_count: 3
  score_band: emerging
  score_composite: 17.5
  shared: 3
- slug: mindgard
  name: Mindgard
  description: Mindgard is a UK-based offensive AI security company (London/Lancaster, spun out of Lancaster University) that provides an automated AI red-teaming and security testing platform for large language models, AI agents, and generative AI syste…
  api_count: 0
  score_band: minimal
  score_composite: 9.5
  shared: 3
- slug: hidden-layer
  name: HiddenLayer
  description: HiddenLayer is an Austin, Texas-based AI security company founded in March 2022 by Chris Sestito (CEO), Tanner Burns (Chief Scientist), and Jim Ballard (CIO) — former Cylance researchers who encountered a real-world attack on production ML…
  api_count: 0
  score_band: minimal
  score_composite: 6.2
  shared: 3
- slug: airia
  name: Airia
  description: 'Airia (Airia LLC, Atlanta) is an enterprise AI orchestration, security and governance platform: a no-code/low-code/pro-code agent builder, a model routing and cost gateway, an MCP Gateway that fronts 1,000+ app connectors and turns hosted…'
  api_count: 2
  score_band: strong
  score_composite: 59.9
  shared: 2
- slug: fiddler-labs
  name: Fiddler Labs
  description: Fiddler Labs (Fiddler AI) is an enterprise AI Observability and Security platform that provides unified visibility, context, and control across AI agents, LLM and GenAI applications, and traditional ML models. The Fiddler platform delivers…
  api_count: 1
  score_band: developing
  score_composite: 53.8
  shared: 2
- slug: patronus-protect
  name: Patronus Protect
  description: Patronus Protect, from Casdo Labs GmbH, is an on-device AI firewall that detects prompt injection, PII/DLP, sensitive documents and agentic tool risk in text, public HTTPS webpages, documents and MCP servers before they are used by AI agen…
  api_count: 1
  score_band: developing
  score_composite: 49.8
  shared: 2
- slug: fiddlerai
  name: fiddler.ai
  description: Fiddler AI is an enterprise AI Observability and Security platform — an "AI Control Plane" for AI agents, LLM applications, and traditional ML models. It delivers unified monitoring, real-time guardrails (safety, hallucination/faithfulness…
  api_count: 1
  score_band: developing
  score_composite: 46.6
  shared: 2
- slug: trustboost-dev
  name: TrustBoost PII Sanitizer
  description: TrustBoost PII Sanitizer is a pay-per-call "privacy firewall" for autonomous AI agent pipelines, built and operated by an individual developer (Teodoro Crispin, GitHub teodorofodocrispin-cmyk) and served entirely from https://api.trustboos…
  api_count: 3
  score_band: developing
  score_composite: 46.0
  shared: 2
- slug: agentcheck-care
  name: AgentCheck
  description: 'AgentCheck is an AI-agent diagnostic service at agentcheck.care: give it the URL of a bot - an A2A agent or an OpenAI-compatible chat endpoint - and it runs synthetic-persona conversations, OWASP LLM Top 10 prompt-injection tests, PII-leak…'
  api_count: 1
  score_band: developing
  score_composite: 40.7
  shared: 2
- slug: lasso-security
  name: Lasso Security
  description: Lasso Security is a GenAI security platform that protects every LLM and AI agent touchpoint. Its Deputy gateway inspects LLM and MCP traffic in real time, and the Classify / Threat Detection API scores prompts and completions for prompt in…
  api_count: 1
  score_band: thin
  score_composite: 38.7
  shared: 2
- slug: promptfoo
  name: Promptfoo
  description: Promptfoo is an open-source LLM evaluation and red-teaming framework distributed as a TypeScript CLI and Node.js library under the MIT license. Developers use it to evaluate prompts, models, and RAG pipelines side by side, run automated re…
  api_count: 6
  score_band: thin
  score_composite: 36.9
  shared: 2
- slug: impart-security
  name: Impart Security
  description: Impart Security is a runtime security platform that unifies WAF, API security, and AI/LLM/agent/MCP protection on one inline enforcement engine. It analyzes the full request/response flow — headers, parameters, query strings, and bodies —…
  api_count: 1
  score_band: emerging
  score_composite: 22.6
  shared: 2
- slug: virtue-ai
  name: Virtue Ai
  description: Virtue AI is an enterprise AI security and safety company that secures AI agents, models, and applications across an organization. Its platform pairs real-time guardrails (VirtueGuard) with automated red-teaming (VirtueRed) and an agent-se…
  api_count: 0
  score_band: emerging
  score_composite: 21.4
  shared: 2
- slug: adversa-ai
  name: Adversa AI
  description: Adversa AI is an autonomous AI red-teaming and security company (founded 2021, Tel Aviv) that provides continuous security assessment for AI agents, LLMs, and GenAI applications. Its platform runs 300+ attack techniques — jailbreaks, promp…
  api_count: 0
  score_band: emerging
  score_composite: 20.9
  shared: 2
- slug: straiker
  name: Straiker
  description: Straiker is an AI-native security company for agentic AI, founded by security veterans from Palo Alto Networks. It protects every layer of AI agent deployments from prompts to infrastructure with a closed-loop system that pairs autonomous…
  api_count: 0
  score_band: emerging
  score_composite: 11.7
  shared: 2
- slug: alinia-ai
  name: Alinia Ai
  description: Alinia is an AI compliance and control platform that helps enterprises deploy large language models and AI agents safely and in compliance with regulations, making AI systems "compliant by design" through regulation-informed control layers…
  api_count: 0
  score_band: minimal
  score_composite: 9.2
  shared: 2
- slug: salus
  name: Salus
  description: Salus provides runtime validation and governance for AI agents. It sits between an agent and its tools as a policy-aware proxy that intercepts each action before it executes, then clarifies, rewrites, escalates for human review, or blocks…
  api_count: 0
  score_band: minimal
  score_composite: 8.7
  shared: 2
- slug: irregular
  name: Irregular
  description: Irregular (formerly Pattern Labs) is a frontier AI security lab founded in 2023 by Dan Lahav and Eli David with the mission of protecting the world as AI systems become increasingly capable and sophisticated. The company runs security asse…
  api_count: 0
  score_band: minimal
  score_composite: 7.6
  shared: 2
- slug: aim-security
  name: Aim Security
  description: Aim Security was an Israeli cybersecurity company (founded 2022) that built a security platform for enterprise adoption of generative AI and large language models — covering GenAI/LLM data-loss prevention, prompt-injection and jailbreak de…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
- slug: apex
  name: Apex (Apex Security)
  description: Apex Security was an AI security startup founded in 2023 in Tel Aviv by Matan Derman (CEO) and Tomer Avni (CPO), backed by Sequoia Capital, Index Ventures and angel investors including Sam Altman. Its platform gave enterprises visibility i…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
- slug: fabraix
  name: Fabraix
  description: Fabraix builds red-teaming AI agents that continuously find security vulnerabilities in customer-facing AI systems. Its flagship product, Nyx, autonomously discovers exploits across chat, voice, browser, and coding agents without needing s…
  api_count: 0
  score_band: minimal
  score_composite: 5.0
  shared: 2
---
