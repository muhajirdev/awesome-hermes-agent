<p align="center">
  <img src="https://raw.githubusercontent.com/NousResearch/hermes-agent/main/assets/banner.png" alt="Awesome Hermes Agent" width="600">
</p>

<h1 align="center">Awesome Hermes Agent</h1>

<p align="center">
  <a href="https://awesome.re"><img src="https://awesome.re/badge.svg" alt="Awesome"></a>
</p>

<p align="center">
  Essential resources, tools, and extensions for <a href="https://github.com/NousResearch/hermes-agent">Hermes Agent</a> — the continuously learning AI agent from <a href="https://nousresearch.com">Nous Research</a>.
</p>

---

## What Makes Hermes Different?

Unlike typical agents, Hermes builds **procedural memory** over time. It:
- Generates skills from actual usage patterns
- Refines them through iteration  
- Recalls context from previous sessions
- Forms an evolving understanding of your preferences

Deploy it on anything from a cheap VPS to enterprise GPU clusters. Interact via Telegram, Discord, Slack, or directly in terminal.

---

## Quick Start Path

**First time?** Follow this progression:

| Step | Action | Recommended Resource |
|------|--------|---------------------|
| 1 | Install & configure | [Official Quickstart](https://hermes-agent.nousresearch.com/docs/) |
| 2 | Add capabilities | [wondelai/skills](https://github.com/wondelai/skills) — 250+ stars, multi-agent compatible |
| 3 | Get a visual interface | [hermes-workspace](https://github.com/outsourc-e/hermes-workspace) — native GUI |

---

## Project Maturity

| Icon | Status | Expectations |
|------|--------|--------------|
| 🟢 | **Stable** | Production-ready, documented, maintained |
| 🟡 | **Active** | Functional, evolving, minor issues possible |
| 🔴 | **Early** | Experimental, learning-oriented, may break |

---

## 📚 Table of Contents

- [Core Platform](#core-platform)
- [Skills Library](#skills-library)
  - [By the Community](#by-the-community)
  - [agentskills.io Standard](#agentskillsio-standard)
- [Extensions & Add-ons](#extensions--add-ons)
- [Discovery & Registries](#discovery--registries)
- [Interfaces & Dashboards](#interfaces--dashboards)
- [Deployment Options](#deployment-options)
- [Connectors & Bridges](#connectors--bridges)
- [Multi-Agent Systems](#multi-agent-systems)
- [Specialized Use Cases](#specialized-use-cases)
- [Variants & Forks](#variants--forks)
- [Learning Resources](#learning-resources)
- [Contribute](#contribute)

---

## Core Platform

> Foundation projects from Nous Research

- 🟢 [hermes-agent](https://github.com/NousResearch/hermes-agent) — Main repository. 10k+ stars. Features: learning loop, multi-platform messaging, 6 terminal backends, cron jobs, MCP integration, OpenClaw migration.
- 🟢 [autonovel](https://github.com/NousResearch/autonovel) — Full book generation pipeline. Outputs 100k+ word manuscripts autonomously.
- 🟡 [hermes-paperclip-adapter](https://github.com/NousResearch/hermes-paperclip-adapter) — Paperclip company integration. Deploy Hermes as managed workforce.
- 🟡 [hermes-agent-self-evolution](https://github.com/NousResearch/hermes-agent-self-evolution) — GEPA/DSPy research framework. Evolves prompts genetically.
- 🟢 [Official Documentation](https://hermes-agent.nousresearch.com/docs/) — Complete reference: setup, config, security, architecture.
- 🟡 [tinker-atropos](https://github.com/NousResearch/tinker-atropos) — RL training on real trajectories via Thinking Machines API.
- 🟢 [agentskills.io](https://agentskills.io) — Cross-platform skill standard.
- 🟢 [Discord](https://discord.gg/NousResearch) — Community support and discussion.

---

## Skills Library

### By the Community

- 🟡 [hermes-plugins](https://github.com/42-evey/hermes-plugins) — 4-pack: goals, agent bridge, model picker, cost monitor.
- 🟡 [hermes-skill-factory](https://github.com/Romanescu11/hermes-skill-factory) — Auto-creates skills from repeated workflows.
- 🟡 [litprog-skill](https://github.com/tlehman/litprog-skill) — Literate programming across Claude, OpenCode, Hermes.
- 🔴 [Wizards-of-the-Ghosts](https://github.com/Hmbown/Wizards-of-the-Ghosts) — RPG-themed dev tools. Cast "spells" to refactor, lint, test.
- 🔴 [super-hermes](https://github.com/Cranot/super-hermes) — Self-prompting layer. Agent improves its own prompts before acting.
- 🔴 [hermes-life-os](https://github.com/Lethe044/hermes-life-os) — Lifestyle tracker. Learns routines, not just code patterns.
- 🟡 [hermes-incident-commander](https://github.com/Lethe044/hermes-incident-commander) — Self-healing SRE. Detects incidents, diagnoses, fixes.
- 🟡 [hermes-dojo](https://github.com/Yonkoo11/hermes-dojo) — Performance monitor. Finds weak skills and auto-improves them.
- 🔴 [hermes-skill-marketplace](https://github.com/Lethe044/hermes-skill-marketplace) — Publishes skills autonomously.

### agentskills.io Standard

- 🟢 [wondelai/skills](https://github.com/wondelai/skills) — Cross-platform skill collection.
- 🟢 [Anthropic-Cybersecurity-Skills](https://github.com/mukul975/Anthropic-Cybersecurity-Skills) — 734+ security skills, MITRE mapped. 3.6k stars.
- 🟢 [chainlink-agent-skills](https://github.com/smartcontractkit/chainlink-agent-skills) — Official Chainlink integration. Oracles, CCIP.
- 🟢 [black-forest-labs/skills](https://github.com/black-forest-labs/skills) — Official FLUX image generation.
- 🟢 [pydantic-ai-skills](https://github.com/DougTrajano/pydantic-ai-skills) — Type-safe skill validation.
- 🟡 [cognify-skills](https://github.com/Yarmoluk/cognify-skills) — 19 business ops: CRM, invoices, PM.
- 🟡 [execplan-skill](https://github.com/tiann/execplan-skill) — Long-task lifecycle management.
- 🟡 [maestro](https://github.com/ReinaMacCredy/maestro) — Skill orchestration with planning.
- 🟡 [bmad-module-skill-forge](https://github.com/armelhbobdad/bmad-module-skill-forge) — Repo-to-skill converter.
- 🟡 [Agentic-MCP-Skill](https://github.com/cablate/Agentic-MCP-Skill) — MCP bridge to skills standard.
- 🔴 [ripley-xmr-gateway](https://github.com/KYC-rip/ripley-xmr-gateway) — Monero blockchain gateway.
- 🟡 [skillsdotnet](https://github.com/PederHP/skillsdotnet) — C#/.NET agentskills.io implementation.

---

## Extensions & Add-ons

> Plugins that extend core functionality

- 🔴 [hermes-payguard](https://github.com/nativ3ai/hermes-payguard) — USDC/x402 payments with spending limits.
- 🟡 [hermes-web-search-plus](https://github.com/robbyczgw-cla/hermes-web-search-plus) — Multi-provider search: Serper, Tavily, Exa.
- 🟡 [hermes-weather-plugin](https://github.com/FahrenheitResearch/hermes-weather-plugin) — Professional weather data: NWS, NEXRAD.
- 🔴 [hermes-wxtrain-plugin](https://github.com/FahrenheitResearch/hermes-wxtrain-plugin) — Weather ML dataset builder.
- 🔴 [hermes-plugin-chrome-profiles](https://github.com/anpicasso/hermes-plugin-chrome-profiles) — Profile switching via CDP.
- 🔴 [hermes-cloudflare](https://github.com/raulvidis/hermes-cloudflare) — Cloudflare-based headless browsing.
- 🟡 [evey-bridge-plugin](https://github.com/42-evey/evey-bridge-plugin) — Claude Code ↔ Hermes handoff.

---

## Discovery & Registries

- 🟡 [hermeshub](https://github.com/amanning3390/hermeshub) — Community skill browser.
- 🟢 [skilldock.io](https://github.com/chigwell/skilldock.io) — Cross-platform skill marketplace.

---

## Interfaces & Dashboards

- 🟢 [hermes-workspace](https://github.com/outsourc-e/hermes-workspace) — Full web GUI. Chat, terminal, memory, skills. Nous Hackathon 2026.
- 🟢 [mission-control](https://github.com/builderz-labs/mission-control) — Fleet orchestration. 3k+ stars.
- 🔴 [hermes-neurovision](https://github.com/Tranquil-Flow/hermes-neurovision) — 42 terminal visual themes.
- 🟡 [lintlang](https://github.com/roli-lpci/lintlang) — Config/prompt linter with HERM scoring.
- 🟡 [nix-hermes-agent](https://github.com/0xrsydn/nix-hermes-agent) — Nix/NixOS package.
- 🟡 [openclaw-to-hermes](https://github.com/0xNyk/openclaw-to-hermes) — Migration assistant.
- 🔴 [vessel-browser](https://github.com/unmodeled-tyler/vessel-browser) — AI-native Linux browser with MCP.
- 🟡 [portable-hermes-agent](https://github.com/rookiemann/portable-hermes-agent) — Windows portable bundle.
- 🟡 [hermes-webui](https://github.com/sanchomuzax/hermes-webui) — Lightweight ops dashboard.
- 🟡 [evey-setup](https://github.com/42-evey/evey-setup) — One-command full stack setup.
- 🟡 [flowstate-qmd](https://github.com/amanning3390/flowstate-qmd) — Predictive memory with RAG.

---

## Deployment Options

- 🟡 [hermes-agent-docker](https://github.com/xmbshwll/hermes-agent-docker) — Minimal container.
- 🟡 [hermes-agent-template](https://github.com/Crustocean/hermes-agent-template) — Crustocean cloud image.
- 🔴 [portainer-stack-hermes](https://github.com/ellickjohnson/portainer-stack-hermes) — Docker Compose + Portainer + web terminal.
- 🔴 [hermes-autonomous-server](https://github.com/JackTheGit/hermes-autonomous-server) — systemd/cron server deployment.

---

## Connectors & Bridges

- 🟡 [hermes-android](https://github.com/raulvidis/hermes-android) — Android device control.
- 🟡 [hermes-miniverse](https://github.com/teknium1/hermes-miniverse) — Miniverse pixel world bridge.
- 🔴 [zouroboros-swarm-executors](https://github.com/marlandoj/zouroboros-swarm-executors) — Claude Code local executor bridge.
- 🟡 [reina](https://github.com/Crustocean/reina) — Crustocean platform integration.
- 🟡 [hermes-agent-acp-skill](https://github.com/Rainhoole/hermes-agent-acp-skill) — Hermes/Codex/Claude delegation router.
- 🔴 [hermes-blockchain-oracle](https://github.com/gizdusum/hermes-blockchain-oracle) — Solana on-chain data via MCP.
- 🔴 [hermes-council](https://github.com/Ridwannurudeen/hermes-council) — Multi-perspective debate council.
- 🔴 [NemoHermes](https://github.com/Hmbown/NemoHermes) — NVIDIA GPU registry with Spark routing.

---

## Multi-Agent Systems

- 🔴 [Ankh.md](https://github.com/Abruptive/Ankh.md) — TAW × Hermes swarm framework.
- 🔴 [gladiator](https://github.com/runtimenoteslabs/gladiator) — Competing AI companies hackathon project.
- 🟡 [bigiron](https://github.com/supermodeltools/bigiron) — AI-native SDLC with Supermodel.
- 🟡 [opencode-hermes-multiagent](https://github.com/1ilkhamov/opencode-hermes-multiagent) — 17 specialized OpenCode agents.

---

## Specialized Use Cases

- 🔴 [hermes-embodied](https://github.com/bryercowan/hermes-embodied) — VLA robotics. Nous Hackathon.
- 🟡 [hermescraft](https://github.com/bigph00t/hermescraft) — Minecraft companion with memory.
- 🔴 [Hermes-mars-rover](https://github.com/Snehal707/Hermes-mars-rover) — ROS2/Gazebo rover sim.
- 🟡 [anihermes](https://github.com/rodmarkun/anihermes) — Anime tracker with NLP interface.
- 🟡 [job-scout-agent](https://github.com/Christabel337/job-scout-agent) — Autonomous job search.
- 🟡 [hermes-ai-infrastructure-monitoring-toolkit](https://github.com/JackTheGit/hermes-ai-infrastructure-monitoring-toolkit) — Infra monitoring + Telegram alerts.
- 🔴 [hermes-genesis](https://github.com/Ridwannurudeen/hermes-genesis) — Procedural world generator.
- 🔴 [hermes-legal](https://github.com/Lethe044/hermes-legal) — Contract risk analyzer (EN/TR).
- 🟡 [hermes-startup-architect](https://github.com/dlkakbs/hermes-startup-architect) — Investor kit generator.
- 🟡 [mercury](https://github.com/hxsteric/mercury) — Multi-chain flow analyzer with WebGL.
- 🔴 [hermes-research-agent](https://github.com/Aum08Desai/hermes-research-agent) — End-to-end research automation.

---

## Variants & Forks

- 🟡 [hermes-agent-camel](https://github.com/nativ3ai/hermes-agent-camel) — CaMeL trust boundaries.
- 🔴 [orahermes-agent](https://github.com/jasperan/orahermes-agent) — Oracle Cloud/26ai integration.
- 🟡 [hermes-alpha](https://github.com/kaminocorp/hermes-alpha) — Cloud templates, zero local setup.
- 🔴 [hermes-skill-distillation](https://github.com/beardthelion/hermes-skill-distillation) — Training trajectory generator.

---

## Learning Resources

- 🟡 [hermes-agent-docs](https://github.com/mudrii/hermes-agent-docs) — Community docs, v0.2.0 coverage.
- 🟢 [hermes-wsl-ubuntu](https://github.com/metantonio/hermes-wsl-ubuntu) — Windows WSL2 setup guide.
- 🟡 [HermesWiki](https://github.com/martymcenroe/HermesWiki) — Community patterns and advice.

---

## Contribute

Found something missing? [Open an issue](https://github.com/muhajirdev/awesome-hermes-agent/issues/new).

Guidelines:
1. Must relate to Hermes or agentskills.io
2. Needs clear documentation
3. Check for duplicates first

See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

[![CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

Content: CC BY 4.0 | Individual resources: their own licenses
