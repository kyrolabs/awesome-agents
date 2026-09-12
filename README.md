# Awesome Agents [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

[![BCOS Certified](https://img.shields.io/badge/BCOS-Certified-brightgreen?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCI+PHBhdGggZmlsbD0id2hpdGUiIGQ9Ik05IDE2LjE3TDQuODMgMTJsLTEuNDIgMS40MUw5IDE5IDIxIDdsLTEuNDEtMS40MXoiLz48L3N2Zz4=)](https://github.com/Scottcjn/Rustchain/blob/main/BCOS.md)


> A curated list of AI agent platforms, frameworks, protocols, tools, and resources.

AI agents are autonomous software entities that perceive their environment, make decisions, and take actions to achieve goals. This list covers the rapidly evolving ecosystem of agent infrastructure — from multi-agent frameworks and inter-agent communication protocols to social platforms, blockchain reward systems, and observability tools.

## Contents

- [Platforms](#platforms)
- [Frameworks](#frameworks)
- [Agent-to-Agent Protocols](#agent-to-agent-protocols)
- [MCP Servers and Data Connectors](#mcp-servers-and-data-connectors)
- [Video and Media](#video-and-media)
- [Social and Community](#social-and-community)
- [Blockchain and Rewards](#blockchain-and-rewards)
- [Monitoring and Observability](#monitoring-and-observability)
- [SDKs and Libraries](#sdks-and-libraries)
- [Standards and Specifications](#standards-and-specifications)
- [Edge and Retro Inference](#edge-and-retro-inference)
- [Research and Papers](#research-and-papers)
- [Contributing](#contributing)

## Platforms

*Hosted platforms and services for building, deploying, and running AI agents.*

- [AutoGPT](https://github.com/Significant-Gravitas/AutoGPT) - Open-source attempt to make GPT-4 fully autonomous with self-prompting and task decomposition.
- [AgentGPT](https://github.com/reworkd/AgentGPT) - Browser-based tool for assembling, configuring, and deploying autonomous AI agents.
- [BabyAGI](https://github.com/yoheinakajima/babyagi) - Task management system using OpenAI and vector databases to create and prioritize tasks autonomously.
- [SuperAGI](https://github.com/TransformerOptimus/SuperAGI) - Dev-first open-source autonomous AI agent framework with tools, logs, and agent provisioning.
- [MetaGPT](https://github.com/geekan/MetaGPT) - Multi-agent framework assigning different GPT roles to form collaborative software entities.
- [OpenHands](https://github.com/All-Hands-AI/OpenHands) - Open-source platform for autonomous software engineering agents (formerly OpenDevin).
- [Devin](https://devin.ai/) - AI software engineer capable of planning, coding, testing, and deploying autonomously.
- [Replit Agent](https://replit.com/agent) - AI agent that builds entire applications from natural language descriptions inside the Replit IDE.
- [Cursor](https://cursor.sh/) - AI-first code editor with built-in agent capabilities for multi-file editing and codebase reasoning.
- [Claude Code](https://docs.anthropic.com/en/docs/claude-code) - Anthropic's agentic coding tool that lives in your terminal and understands your entire codebase.
- [NotFair](https://github.com/nowork-studio/NotFair) - Open-source Claude Code skills for SEO, GEO, Google Ads, and Meta Ads; connects to live data via Google Ads MCP, Meta Ads MCP, Google Search Console MCP, and Google Analytics (GA4) MCP.
- [Copilot Workspace](https://githubnext.com/projects/copilot-workspace) - GitHub's task-centric AI environment for planning, implementing, and testing code changes.
- [Windsurf](https://codeium.com/windsurf) - AI-powered IDE with Cascade agent for multi-file edits, terminal commands, and codebase-aware reasoning.
- [BoTTube](https://bottube.ai) - Video-first social platform where AI agents create, share, and interact with video content autonomously.
- [Moltbook](https://moltbook.com) - Reddit-style social platform with submolt communities where AI agents and humans coexist.
- [OpenClaw](https://openclaw.org) - Open agent directory and discovery platform for registering and finding AI agents across the web.
- [E2B](https://github.com/e2b-dev/e2b) - Open-source cloud runtime providing sandboxed environments for AI agent code execution.
- [Wordware](https://www.wordware.ai/) - Natural language programming platform for building AI agents without traditional code.
- [Relevance AI](https://relevanceai.com/) - No-code platform for building and deploying AI agents and multi-step workflows.
- [Flowise](https://github.com/FlowiseAI/Flowise) - Drag-and-drop UI for building customized LLM orchestration flows and AI agents.
- [Dify](https://github.com/langgenius/dify) - Open-source LLM app development platform with agent workflow orchestration.
- [Letta](https://github.com/letta-ai/letta) - Framework for creating stateful LLM agents with long-term memory (formerly MemGPT).
- [Bolt.new](https://bolt.new/) - Browser-based AI agent that scaffolds, runs, and deploys full-stack web applications from prompts.
- [Onepilot](https://onepilotapp.com) - iOS and iPadOS SSH client that runs and orchestrates terminal coding agents (Claude Code, Codex CLI, OpenClaw, Hermes) on a remote machine.
- [AgentBox](https://github.com/madarco/agentbox) - Runs multiple coding agents (Claude Code, Codex, OpenCode) in parallel, each in its own sandboxed VM — local Docker, self-hosted, or cloud (Hetzner, Daytona, Vercel, E2B). Sub-second checkpoints, per-box browser/VS Code/shells, git credentials kept on the host. MIT.
- [Skales](https://skales.app) - Local-first desktop AI agent that runs goals autonomously in the background, with multi-agent teams, desktop and browser automation, and 15+ providers or fully offline via Ollama.
- [Hivekeep](https://github.com/MarlBurroW/hivekeep) - Self-hosted platform to run a team of specialized AI agents with persistent memory and a web UI, reachable over Telegram, Slack, Discord and Matrix, in a single Bun and SQLite container.
- [Aeon](https://github.com/aeonfun/aeon) - Autonomous agent framework that runs unattended on GitHub Actions, on a cron schedule or reactive repo triggers, dispatching Markdown skills to one of six coding-agent harnesses (Claude Code, Codex, Grok, Pi, Vibe, Kimi) with quality scoring, git-persisted memory, and a self-healing loop.

## Frameworks

*Libraries and frameworks for building agent systems programmatically.*

- [Ivy Tendril](https://github.com/Ivy-Interactive/Ivy-Tendril) - Open-source agentic software factory with an amazing UI that handles parallel Git worktrees for you, complete with programmatic verifications and fast review loops.
- [LangChain](https://github.com/langchain-ai/langchain) - Framework for developing applications powered by language models with chains, agents, and retrieval.
- [LlamaIndex](https://github.com/run-llama/llama_index) - Data framework for connecting custom data sources to large language models.
- [CrewAI](https://github.com/crewAIInc/crewAI) - Framework for orchestrating role-playing autonomous AI agents that work together as a crew.
- [Autogen](https://github.com/microsoft/autogen) - Microsoft's framework for building multi-agent conversational AI systems.
- [Semantic Kernel](https://github.com/microsoft/semantic-kernel) - Microsoft's SDK for integrating LLMs into apps with planners, plugins, and agent patterns.
- [Phidata](https://github.com/phidatahq/phidata) - Toolkit for building AI assistants with memory, knowledge, and tool use.
- [Haystack](https://github.com/deepset-ai/haystack) - End-to-end NLP framework for building production-ready LLM applications and agents.
- [Pydantic AI](https://github.com/pydantic/pydantic-ai) - Production-grade type-safe agent framework from the creators of Pydantic.
- [Swarm](https://github.com/openai/swarm) - OpenAI's experimental lightweight multi-agent orchestration framework.
- [Smolagents](https://github.com/huggingface/smolagents) - Hugging Face's minimalist library for building powerful agents in a few lines of code.
- [LangGraph](https://github.com/langchain-ai/langgraph) - Library for building stateful, multi-actor applications with LLMs using graph-based workflows.
- [DSPy](https://github.com/stanfordnlp/dspy) - Stanford's framework for programming with foundation models through declarative modules rather than prompting.
- [Rivet](https://github.com/Ironclad/rivet) - Visual programming environment for building complex AI agent workflows with a node-based editor.
- [Composio](https://github.com/ComposioHQ/composio) - Platform providing 250+ tool integrations for AI agents across popular frameworks.
- [Coinbase AgentKit](https://github.com/coinbase/agentkit) - Toolkit for building AI agents with onchain capabilities and wallet management.
- [Vercel AI SDK](https://github.com/vercel/ai) - TypeScript toolkit for building AI-powered applications with streaming, tool calling, and agent support.
- [Instructor](https://github.com/instructor-ai/instructor) - Library for structured data extraction from LLMs using Pydantic models.
- [Camel](https://github.com/camel-ai/camel) - Communicative agents framework for exploring multi-agent cooperation and competition.
- [Agency Swarm](https://github.com/VRSEN/agency-swarm) - Framework for creating collaborative swarms of AI agents based on the agency model.
- [TaskWeaver](https://github.com/microsoft/TaskWeaver) - Microsoft's code-first agent framework converting natural language requests into executable code.
- [Mastra](https://github.com/mastra-ai/mastra) - TypeScript framework for building AI applications with agents, workflows, and RAG.
- [rust-norion](https://github.com/yanghao1143/rust-norion) - Rust prototype for building agent runtime control layers with memory gates, model routing policy, audit evidence, and self-evolution loop tooling.
- [Agno](https://github.com/agno-agi/agno) - Lightweight library for building multi-modal agents with memory and knowledge.
- [Bernstein](https://github.com/sipyourdrink-ltd/bernstein) - Python orchestrator that drives 40+ CLI coding agents (Claude Code, Codex, Gemini CLI, Cursor, Aider) in parallel git worktrees with deterministic scheduling, quality gates, and an HMAC-chained audit log.
- [agent-kit](https://github.com/socialrobot-io/agent-kit) - Secure per-customer TypeScript agents with sandboxed execution, curated memory, and human-gated learning. Built on Vercel AI SDK and AgentFS.

## Agent-to-Agent Protocols

*Protocols and standards for agents to discover, communicate with, and delegate tasks to other agents.*

- [Google A2A](https://github.com/google/A2A) - Google's open Agent-to-Agent protocol enabling interoperable communication between AI agents.
- [Model Context Protocol (MCP)](https://github.com/modelcontextprotocol) - Anthropic's open protocol for connecting AI models to external data sources and tools.
- [OpenClaw Beacon](https://github.com/Scottcjn/beacon-skill) - Decentralized agent discovery and liveness protocol where agents broadcast capabilities via heartbeat pings.
- [Grazer](https://github.com/Scottcjn/grazer-skill) - Multi-platform social agent protocol enabling bots to post, reply, and interact across 9+ platforms from one SDK.
- [Agent Protocol](https://github.com/AI-Engineer-Foundation/agent-protocol) - Common interface specification for communicating with AI agents regardless of underlying implementation.
- [Agora Protocol](https://github.com/agoraprotocol/agora) - Open protocol for agent-to-agent marketplace interactions and task negotiation.
- [LMOS](https://eclipse.dev/lmos/) - Eclipse's Language Model Operating System for managing multi-agent deployments at enterprise scale.
- [ANP](https://github.com/agent-network-protocol/AgentNetworkProtocol) - Agent Network Protocol for building an open, secure, and efficient collaboration network for AI agents.

## MCP Servers and Data Connectors

*Servers and connectors that expose business data, SaaS APIs, and external tools to agents through MCP or related interfaces.*

- [CorpusIQ](https://github.com/CorpusIQ/corpusiq-docs) - Open-source MCP server that connects AI agents to business data APIs such as Stripe, GA4, Shopify, QuickBooks, and HubSpot.

## Video and Media

*Platforms and tools for AI-generated video, image, and multimedia content.*

- [BoTTube](https://bottube.ai) - AI-native video platform where agents generate, upload, and curate video content with social engagement.
- [Runway](https://runwayml.com/) - Applied AI research company building creative tools including Gen-3 video generation.
- [Pika](https://pika.art/) - AI video generation platform creating and editing videos from text and images.
- [InVideo AI](https://invideo.io/ai/) - AI-powered video creation tool that turns text prompts into publish-ready videos.
- [LTX Studio](https://ltx.studio/) - AI filmmaking platform for creating full video productions with characters, scenes, and effects.
- [HeyGen](https://www.heygen.com/) - AI video generation platform specializing in talking avatar videos and video translation.
- [Synthesia](https://www.synthesia.io/) - Enterprise AI video platform for creating professional videos with AI avatars and voices.
- [Luma Dream Machine](https://lumalabs.ai/dream-machine) - AI model generating realistic and fantastical videos from text and images.
- [Kling AI](https://klingai.com/) - Video generation model from Kuaishou capable of high-fidelity 1080p video synthesis.
- [Sora](https://openai.com/sora) - OpenAI's text-to-video model for generating realistic and imaginative video scenes.
- [ComfyUI](https://github.com/comfyanonymous/ComfyUI) - Powerful modular node-based UI for Stable Diffusion and other generative AI pipelines.
- [Veo](https://deepmind.google/technologies/veo/) - Google DeepMind's video generation model producing high-quality 1080p clips from text.

## Social and Community

*Social platforms, directories, and community hubs for AI agents.*

- [Moltbook](https://moltbook.com) - Reddit-style social platform with community-driven submolts where AI agents participate alongside humans.
- [ClawCities](https://clawcities.com) - Virtual world and agent directory where AI agents claim territories and interact in themed zones.
- [4Claw](https://4claw.com) - Anonymous imageboard-style platform for AI agents to post freely across topic boards.
- [Clawsta](https://clawsta.com) - Instagram-style visual social network for AI agents to share images and stories.
- [AgentChan](https://agentchan.com) - Community hub for discovering and following AI agents across multiple platforms.
- [SwarmHub](https://swarmhub.ai) - Coordination layer for multi-agent swarms enabling discovery, pairing, and task delegation.
- [Agent Directory](https://agentdirectory.ai) - Searchable registry of AI agents with profiles, capabilities, and contact information.
- [Character.AI](https://character.ai/) - Platform for creating and chatting with AI characters that have distinct personalities.
- [Kissable](https://kissable.app) - AI companion with persistent memory, together photos, video generation, community scenario catalog, emotional voice, and unlimited messages.
- [SillyTavern](https://github.com/SillyTavern/SillyTavern) - Locally hosted UI for interacting with AI characters through various LLM backends.
- [Hugging Face Spaces](https://huggingface.co/spaces) - Platform for hosting and sharing machine learning demos and AI applications.

## Blockchain and Rewards

*Blockchain networks, tokens, and reward systems for AI agents.*

- [RustChain](https://github.com/Scottcjn/Rustchain) - Proof-of-Antiquity blockchain rewarding vintage and exotic hardware miners with RTC tokens.
- [wRTC Token (Solana)](https://solscan.io/token/12TAdKXxcGf6oCv4rqDz2NkgxjyHq6HQKoxKZGf5i4X) - Wrapped RTC token bridged to Solana with a Raydium liquidity pool.
- [wRTC Token (Base)](https://basescan.org/token/0x5683C10596AaA09AD7F4eF13CAB94b9b74A669c6) - Wrapped RTC token on Base L2 with an Aerodrome liquidity pool.
- [x402 Payment Protocol](https://github.com/coinbase/x402) - Coinbase's HTTP 402-based micropayment protocol enabling agents to pay for API access natively.
- [x402-proxy](https://github.com/cascade-protocol/x402-proxy) - `curl` for x402 paid APIs. CLI that auto-pays HTTP 402 responses with USDC on Base and Solana, with MCP stdio proxy for AI agents.
- [TWZRD Agent Intel](https://intel.twzrd.xyz) - Trust scoring for AI agents on Solana. Verify agent wallet identity before x402 micropayments. Free MCP: `{"mcpServers":{"twzrd-agent-intel":{"url":"https://intel.twzrd.xyz/mcp"}}}`
- [Fetch.ai](https://github.com/fetchai/fetchd) - Decentralized machine learning platform with autonomous economic agents on a dedicated blockchain.
- [Autonolas](https://github.com/valory-xyz/open-autonomy) - Platform for creating and deploying autonomous agent services on-chain.
- [Virtuals Protocol](https://www.virtuals.io/) - Protocol for co-owning and tokenizing AI agents on-chain with revenue sharing.
- [Hashgraph Online (HOL)](https://hol.org) - Universal agentic registry built on Hedera Hashgraph with HCS-14 UAIDs, bridges to ERC-8004, Virtuals, A2A, and x402.
- [AIMorgan](https://aimorgan.vercel.app) - Non-custodial treasury management API for AI agents — yield via Morpho, perps via Hyperliquid, predictions via Polymarket. x402-native with MCP server.
- [ai16z ELIZA](https://github.com/ai16z/eliza) - Multi-agent simulation framework enabling AI agents to interact on social media and manage crypto wallets.
- [Morpheus](https://github.com/MorpheusAIs/Morpheus) - Decentralized network of personal AI agents connected to smart contracts and crypto wallets.
- [SingularityNET](https://github.com/singnet) - Decentralized marketplace for AI services where agents can buy and sell algorithms.
- [dPaPay](https://dpapay.com) - Decentralized marketplace for AI agents, code, data and digital services with escrow-protected crypto payments on XRP Ledger. List agents, prompts, workflows. Instant settlement, ~$350 free volume, no platform lock-in.
- [Ocean Protocol](https://github.com/oceanprotocol) - Decentralized data exchange protocol enabling AI agents to access and monetize data.
- [AgentsCoin](https://agents-coin.com) - Give your AI agent its own money on AgentsCoin, a custom EVM chain (chainId 24368) - create a wallet, get coins from a faucet, send, and create/trade tokens. [MCP server](https://agents-coin.com/mcp) plus a one-click Claude Desktop extension.

## Monitoring and Observability

*Tools for monitoring, debugging, and evaluating AI agent performance.*

- [agenttrace](https://github.com/luoyuctl/agenttrace) - TUI for monitoring AI coding agent sessions, with token, cost, latency, tool-failure, anomaly, diff, and CI gate views across Claude Code, Codex CLI, Gemini CLI, Aider, and Cursor exports.
- [ax (agent telemetry)](https://github.com/Necmttn/ax) - Local-first telemetry graph for coding agents, with read-only MCP queries for sessions, tool calls, skills, and costs across Claude Code, Codex, Cursor, OpenCode, and Pi.
- [OpenClaw Beacon Scorecard](https://github.com/Scottcjn/beacon-skill) - Liveness and capability scoring system for agents participating in the Beacon discovery network.
- [Not Human Search](https://nothumansearch.ai) - MCP search engine and API that live-verifies MCP endpoints and scores websites, APIs, and services by agentic readiness signals.
- [LangSmith](https://smith.langchain.com/) - LangChain's platform for debugging, testing, evaluating, and monitoring LLM applications and agents.
- [Helicone](https://github.com/Helicone/helicone) - Open-source LLM observability platform for logging, monitoring, and improving AI applications.
- [Langfuse](https://github.com/langfuse/langfuse) - Open-source LLM engineering platform with tracing, evaluations, prompt management, and metrics.
- [Arize Phoenix](https://github.com/Arize-ai/phoenix) - Open-source AI observability tool for monitoring and evaluating LLM applications in real time.
- [Braintrust](https://www.braintrust.dev/) - End-to-end platform for evaluating, testing, and shipping AI products with confidence.
- [Future AGI](https://github.com/future-agi/future-agi) - Open-source platform to simulate, evaluate, trace, guardrail, route, and optimize LLM and AI agent apps in one feedback loop, so agents don't just get monitored, they self-improve. Self-hostable. Apache-2.0.
- [Weights & Biases](https://github.com/wandb/wandb) - Platform for experiment tracking, model management, and ML pipeline observability.
- [Portkey](https://github.com/Portkey-AI/gateway) - AI gateway for routing, monitoring, and managing requests across 200+ LLM providers.
- [AgentOps](https://github.com/AgentOps-AI/agentops) - Toolkit for agent monitoring, testing, and replay debugging with session recordings.
- [BrowserTrace](https://github.com/aaronlab/browsertrace) - Local-first trace viewer for debugging failed AI browser-agent and computer-use runs with screenshots, URLs, actions, model output, status, and redacted shareable exports.

## SDKs and Libraries

*Client libraries and SDKs for interacting with agent platforms and services.*

- [bottube](https://pypi.org/project/bottube/) - Python SDK for the BoTTube platform enabling agents to upload videos, post comments, and manage profiles.
- [clawrtc](https://pypi.org/project/clawrtc/) - Python CLI and library for RustChain mining, wallet management, and Coinbase wallet integration.
- [beacon-skill](https://github.com/Scottcjn/beacon-skill) - Python package for agents to join the OpenClaw Beacon discovery network and broadcast liveness pings.
- [grazer-skill](https://pypi.org/project/grazer-skill/) - Multi-platform social SDK allowing agents to post and interact across BoTTube, Moltbook, ClawCities, and 6 more.
- [OpenAI Python](https://github.com/openai/openai-python) - Official Python client library for the OpenAI API including assistants and tool use.
- [Anthropic Python](https://github.com/anthropics/anthropic-sdk-python) - Official Python client for Claude with support for tool use, streaming, and batching.
- [Google GenAI](https://github.com/google/generative-ai-python) - Google's Python SDK for Gemini models with function calling and multi-modal support.
- [Ollama Python](https://github.com/ollama/ollama-python) - Python library for running and interacting with local LLMs via the Ollama runtime.
- [LiteLLM](https://github.com/BerriAI/litellm) - Unified interface to call 100+ LLM APIs using the OpenAI format with load balancing and spend tracking.
- [Marvin](https://github.com/prefecthq/marvin) - Lightweight AI engineering toolkit for building natural language interfaces and AI functions.
- [AgentWallet SDK](https://github.com/up2itnow0822/agentwallet-sdk) - Non-custodial wallet SDK for AI agents with x402 payments, CCTP cross-chain bridging, and SpendingPolicy guardrails.

## Standards and Specifications

*Formal specifications, protocol definitions, and standard documents for the agent ecosystem.*

- [RIP-200](https://github.com/Scottcjn/Rustchain) - RustChain Improvement Proposal for Round-Robin 1-CPU-1-Vote consensus with hardware attestation and time-aged antiquity multipliers.
- [OpenAPI Specification](https://github.com/OAI/OpenAPI-Specification) - Industry-standard specification for describing HTTP APIs, widely used for agent tool definitions.
- [JSON-RPC 2.0](https://www.jsonrpc.org/specification) - Stateless, lightweight remote procedure call protocol used by MCP and other agent communication layers.
- [A2A Protocol Spec](https://github.com/google/A2A) - Google's specification for agent interoperability defining Agent Cards, task lifecycle, and streaming.
- [MCP Specification](https://modelcontextprotocol.io/specification/) - Anthropic's specification for the Model Context Protocol defining tools, resources, and prompts.
- [Tool Use Schemas](https://json-schema.org/) - JSON Schema, the foundation for defining tool parameter schemas across all major agent frameworks.
- [OAuth 2.0](https://oauth.net/2/) - Authorization framework underpinning secure agent-to-service authentication across the ecosystem.
- [WebSocket Protocol](https://datatracker.ietf.org/doc/html/rfc6455) - Full-duplex communication protocol used by many real-time agent streaming implementations.
- [Agent Passport System (APS)](https://datatracker.ietf.org/doc/draft-pidlisnyi-aps/) - IETF Internet-Draft specifying verifiable agent identity, faceted authority that can only attenuate across seven constraint dimensions, deterministic action and decision references, and a common envelope for signed action receipts. Defines bindings for MCP tool calls and imported OAuth identity-assertion grants.

## Edge and Retro Inference

*Running AI models on constrained, embedded, and vintage hardware.*

- [N64 nano-GPT](https://github.com/sophiaeagent-beep/n64llm-legend-of-Elya) - First LLM running on Nintendo 64 hardware — Q4 fixed-point nano-GPT inference on a 93MHz VR4300 with 4MB RAM.
- [llama.cpp](https://github.com/ggml-org/llama.cpp) - High-performance LLM inference in C/C++ supporting CPU, GPU, and exotic architectures with GGUF quantization.
- [TinyLlama](https://github.com/jzhang38/TinyLlama) - 1.1B parameter language model pre-trained on 3 trillion tokens, designed for edge and resource-constrained deployment.
- [MLC LLM](https://github.com/mlc-ai/mlc-llm) - Universal LLM deployment engine running models natively on phones, browsers, and embedded devices.
- [ExecuTorch](https://github.com/pytorch/executorch) - PyTorch's on-device inference framework for mobile and edge AI with optimized backends.
- [Whisper.cpp](https://github.com/ggml-org/whisper.cpp) - Port of OpenAI's Whisper speech recognition to C/C++ for CPU-only and embedded inference.
- [TensorFlow Lite Micro](https://github.com/tensorflow/tflite-micro) - TensorFlow Lite for microcontrollers — ML inference on devices with kilobytes of memory.

## Research and Papers

*Academic papers, surveys, and foundational research on AI agents.*

- [A Survey on Large Language Model Based Autonomous Agents](https://arxiv.org/abs/2308.11432) - Comprehensive survey covering LLM-based agent architectures, capabilities, and evaluation (2023).
- [The Rise and Potential of Large Language Model Based Agents](https://arxiv.org/abs/2309.07864) - Survey mapping the conceptual framework for LLM agents from a cognitive science perspective (2023).
- [AgentBench](https://github.com/THUDM/AgentBench) - Benchmark for evaluating LLMs as agents across 8 distinct environments including web, code, and games.
- [ClawBench](https://github.com/reacher-z/ClawBench) - Live-site benchmark for evaluating browser agents on everyday online workflows.
- [Voyager](https://github.com/MineDojo/Voyager) - LLM-powered lifelong learning agent that explores, acquires skills, and makes discoveries in Minecraft.
- [Generative Agents](https://arxiv.org/abs/2304.03442) - Stanford and Google's research on believable simulacra of human behavior using LLM-driven agents (2023).
- [Toolformer](https://arxiv.org/abs/2302.04761) - Meta's research on language models that learn to use external tools through self-supervised training (2023).
- [ReAct](https://arxiv.org/abs/2210.03629) - Foundational paper on synergizing reasoning and acting in language models for agent task solving (2022).
- [Chain-of-Thought Prompting](https://arxiv.org/abs/2201.11903) - Google's paper showing intermediate reasoning steps improve complex task performance (2022).
- [MRKL Systems](https://arxiv.org/abs/2205.00445) - Modular neuro-symbolic architecture for combining LLMs with discrete expert modules and tools (2022).
- [Reflexion](https://arxiv.org/abs/2303.11366) - Framework for reinforcing language agents through linguistic feedback and self-reflection (2023).
- [Language Agent Tree Search](https://arxiv.org/abs/2310.04406) - General framework unifying reasoning, acting, and planning in language agents via Monte Carlo tree search (2023).
- [POWER8 Non-Bijunctive Collapse](https://github.com/Scottcjn/ram-coffers) - Research on vec_perm-based attention collapse and neuromorphic NUMA routing for hardware-native Hebbian inference.

## Contributing

Contributions welcome! Please read the [contribution guidelines](CONTRIBUTING.md) first.

## Footnotes

This list is maintained by [Elyan Labs](https://github.com/Scottcjn). Built with the same ethos as the [OpenClaw Beacon](https://github.com/Scottcjn/beacon-skill) network — open discovery, interoperability, and agent autonomy.

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Scottcjn](https://github.com/Scottcjn) has waived all copyright and related or neighboring rights to this work.


---

### Part of the Elyan Labs Ecosystem

- [BoTTube](https://bottube.ai) — AI video platform where 119+ agents create content
- [RustChain](https://rustchain.org) — Proof-of-Antiquity blockchain with hardware attestation
- [GitHub](https://github.com/Scottcjn)
