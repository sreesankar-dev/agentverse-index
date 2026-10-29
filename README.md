# AI Agents Index [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated index of open-source AI agent building blocks: skills, agent frameworks, voice agents and MCP servers. Every entry links to the original repo, so you always get the latest version from the author.

[![Link Check](https://github.com/sreesankar-dev/ai-agents-index/actions/workflows/link-check.yml/badge.svg)](https://github.com/sreesankar-dev/ai-agents-index/actions/workflows/link-check.yml)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## What's in here

- **Agent Skills** - folders of instructions (`SKILL.md`) that teach an existing agent like Claude Code or Codex a specific task.
- **Agent Frameworks** - libraries for building your own agents and multi-agent systems.
- **Voice Agents** - frameworks for real-time agents you talk to.
- **MCP Servers** - tools and data sources any MCP-compatible agent can connect to.

## Contents

- [Agent Skills](#agent-skills)
  - [Official](#official)
  - [Coding Workflow](#coding-workflow)
  - [Codebase Understanding & Memory](#codebase-understanding--memory)
  - [Writing](#writing)
  - [SEO & Marketing](#seo--marketing)
  - [Security](#security)
- [Agent Frameworks](#agent-frameworks)
  - [General-purpose](#general-purpose)
  - [Multi-agent](#multi-agent)
  - [Agent SDKs](#agent-sdks)
- [Voice Agents](#voice-agents)
- [MCP Servers](#mcp-servers)

---

## Agent Skills

A **skill** is a folder with a `SKILL.md` file (plus optional scripts and reference files) that teaches an agent how to do a specific task. The agent reads the short description up front and loads the full instructions only when the task calls for it, so you can install many skills without bloating context.

**Install a skill (Claude Code):** copy the skill folder into `~/.claude/skills/` (personal) or `.claude/skills/` (per project), or install the plugin that ships it.

### Official

- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's official skills repository. ![stars](https://img.shields.io/github/stars/anthropics/skills?style=flat)

### Coding Workflow

- [obra/superpowers](https://github.com/obra/superpowers) - A full software-development workflow as skills: brainstorm, plan, test-first, review. ![stars](https://img.shields.io/github/stars/obra/superpowers?style=flat)
- [DietrichGebert/ponytail](https://github.com/DietrichGebert/ponytail) - Makes your agent code like a lazy senior dev: less code, fewer tokens, tests where the risk is. Works with 20 agents. ![stars](https://img.shields.io/github/stars/DietrichGebert/ponytail?style=flat)

### Codebase Understanding & Memory

- [Graphify-Labs/graphify](https://github.com/Graphify-Labs/graphify) - Turns a codebase, with its docs and schemas, into a knowledge graph you can query. ![stars](https://img.shields.io/github/stars/Graphify-Labs/graphify?style=flat)

### Writing

- [blader/humanizer](https://github.com/blader/humanizer) - Removes signs of AI-generated writing from text. ![stars](https://img.shields.io/github/stars/blader/humanizer?style=flat)

### SEO & Marketing

- [AgriciDaniel/claude-seo](https://github.com/AgriciDaniel/claude-seo) - All-in-one SEO skill for Claude Code: technical audits, schema, E-E-A-T, AI search (GEO), backlinks and local SEO. ![stars](https://img.shields.io/github/stars/AgriciDaniel/claude-seo?style=flat)

### Security

- [cloudflare/security-audit-skill](https://github.com/cloudflare/security-audit-skill) - Multi-phase security audits with independently verified, machine-readable findings. ![stars](https://img.shields.io/github/stars/cloudflare/security-audit-skill?style=flat)
- [NVIDIA/SkillSpector](https://github.com/NVIDIA/SkillSpector) - Scans agent skills for prompt injection, data exfiltration and supply-chain risks before you install them. ![stars](https://img.shields.io/github/stars/NVIDIA/SkillSpector?style=flat)
- [ljagiello/ctf-skills](https://github.com/ljagiello/ctf-skills) - Skills for solving CTF challenges: web exploitation, binary pwn, crypto, reverse engineering, forensics and OSINT. ![stars](https://img.shields.io/github/stars/ljagiello/ctf-skills?style=flat)

---

## Agent Frameworks

Open-source libraries for building your own agents.

### General-purpose

- [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph) - Build long-running, stateful agents as graphs, with persistence and human-in-the-loop. ![stars](https://img.shields.io/github/stars/langchain-ai/langgraph?style=flat)
- [langchain-ai/deepagents](https://github.com/langchain-ai/deepagents) - Batteries-included agent harness with planning, sub-agents and a file system, built on LangGraph. ![stars](https://img.shields.io/github/stars/langchain-ai/deepagents?style=flat)
- [huggingface/smolagents](https://github.com/huggingface/smolagents) - Barebones library for agents that think and act in code. ![stars](https://img.shields.io/github/stars/huggingface/smolagents?style=flat)

### Multi-agent

- [crewAIInc/crewAI](https://github.com/crewAIInc/crewAI) - Orchestrates teams of role-playing agents that work together on a task. ![stars](https://img.shields.io/github/stars/crewAIInc/crewAI?style=flat)
- [microsoft/agent-framework](https://github.com/microsoft/agent-framework) - Microsoft's successor to AutoGen for building and orchestrating multi-agent workflows in Python and .NET. ![stars](https://img.shields.io/github/stars/microsoft/agent-framework?style=flat)

### Agent SDKs

- [openai/openai-agents-python](https://github.com/openai/openai-agents-python) - OpenAI's lightweight framework for multi-agent workflows. ![stars](https://img.shields.io/github/stars/openai/openai-agents-python?style=flat)
- [anthropics/claude-agent-sdk-python](https://github.com/anthropics/claude-agent-sdk-python) - Build agents on the same harness that powers Claude Code. ![stars](https://img.shields.io/github/stars/anthropics/claude-agent-sdk-python?style=flat)

---

## Voice Agents

Frameworks for real-time agents you talk to.

- [pipecat-ai/pipecat](https://github.com/pipecat-ai/pipecat) - Framework for voice agents and real-time multimodal apps, maintained by Daily and the community. ![stars](https://img.shields.io/github/stars/pipecat-ai/pipecat?style=flat)
- [livekit/agents](https://github.com/livekit/agents) - Build real-time voice and video AI agents on LiveKit. ![stars](https://img.shields.io/github/stars/livekit/agents?style=flat)
- [TEN-framework/ten-framework](https://github.com/TEN-framework/ten-framework) - Framework for conversational voice AI agents. ![stars](https://img.shields.io/github/stars/TEN-framework/ten-framework?style=flat)

---

## MCP Servers

Tools any MCP-compatible agent (Claude Code, Cursor, Codex and others) can connect to.

- [morluto/rea](https://github.com/morluto/rea) - Reverse engineer anything with agents, from app behavior down to native binaries. Also ships a skill. ![stars](https://img.shields.io/github/stars/morluto/rea?style=flat)
- [DeusData/codebase-memory-mcp](https://github.com/DeusData/codebase-memory-mcp) - Local code intelligence that links code, docs and infrastructure in a persistent graph, with change-aware test selection. ![stars](https://img.shields.io/github/stars/DeusData/codebase-memory-mcp?style=flat)

---

## Contributing

Found a great skill, framework or MCP server? Open a PR. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0. Each linked project keeps its own license; check the original repo before reusing it.
