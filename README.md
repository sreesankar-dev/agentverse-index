# Agent Skills Index [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

> A curated list of skills for AI coding agents: Claude Code, Claude.ai, Codex, Cursor and friends. Every entry links to the original repo, so you always get the latest version from the author.

[![Link Check](https://github.com/sreesankar-dev/agent-skills-index/actions/workflows/link-check.yml/badge.svg)](https://github.com/sreesankar-dev/agent-skills-index/actions/workflows/link-check.yml)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](CONTRIBUTING.md)

## What is a skill?

A **skill** is a folder with a `SKILL.md` file (plus optional scripts and reference files) that teaches an agent how to do a specific task. The agent reads the short description up front and loads the full instructions only when the task calls for it, so you can install many skills without bloating context.

**Install a skill (Claude Code):** copy the skill folder into `~/.claude/skills/` (personal) or `.claude/skills/` (per project), or install the plugin that ships it.

## Contents

- [Official](#official)
- [Development & Workflow](#development--workflow)
- [Testing & QA](#testing--qa)
- [Documents & Office Files](#documents--office-files)
- [Design & Frontend](#design--frontend)
- [Writing & Communication](#writing--communication)
- [Meta: Building Skills](#meta-building-skills)
- [Other Lists](#other-lists)

Legend: ✅ = tried and verified by the maintainer.

---

## Official

- [anthropics/skills](https://github.com/anthropics/skills) - Anthropic's official skills repository. ![stars](https://img.shields.io/github/stars/anthropics/skills?style=flat)

## Development & Workflow

- [mcp-builder](https://github.com/anthropics/skills/tree/main/skills/mcp-builder) - Guides you through building high-quality MCP servers.
- [claude-api](https://github.com/anthropics/skills/tree/main/skills/claude-api) - Reference for building apps on the Claude API and Anthropic SDKs.

## Testing & QA

- [webapp-testing](https://github.com/anthropics/skills/tree/main/skills/webapp-testing) - Drives a real browser with Playwright to test local web apps.

## Documents & Office Files

- [docx](https://github.com/anthropics/skills/tree/main/skills/docx) - Create, edit and read Word documents, including tracked changes.
- [xlsx](https://github.com/anthropics/skills/tree/main/skills/xlsx) - Build and edit spreadsheets with formulas and formatting.
- [pptx](https://github.com/anthropics/skills/tree/main/skills/pptx) - Create and edit PowerPoint decks.
- [pdf](https://github.com/anthropics/skills/tree/main/skills/pdf) - Extract, merge, split, fill and create PDFs.

## Design & Frontend

- [frontend-design](https://github.com/anthropics/skills/tree/main/skills/frontend-design) - Produces distinctive, production-grade frontend UIs instead of generic ones.
- [web-artifacts-builder](https://github.com/anthropics/skills/tree/main/skills/web-artifacts-builder) - Builds multi-component HTML artifacts with React and Tailwind.
- [canvas-design](https://github.com/anthropics/skills/tree/main/skills/canvas-design) - Creates posters and visual art as PNG/PDF.
- [algorithmic-art](https://github.com/anthropics/skills/tree/main/skills/algorithmic-art) - Generative art with p5.js.
- [theme-factory](https://github.com/anthropics/skills/tree/main/skills/theme-factory) - Applies ready-made color and font themes to artifacts.
- [brand-guidelines](https://github.com/anthropics/skills/tree/main/skills/brand-guidelines) - Example of encoding brand colors and typography as a skill.

## Writing & Communication

- [doc-coauthoring](https://github.com/anthropics/skills/tree/main/skills/doc-coauthoring) - A structured workflow for co-writing docs with the agent.
- [internal-comms](https://github.com/anthropics/skills/tree/main/skills/internal-comms) - Status reports, newsletters and other internal updates in house style.
- [slack-gif-creator](https://github.com/anthropics/skills/tree/main/skills/slack-gif-creator) - Makes animated GIFs sized for Slack.

## Meta: Building Skills

- [skill-creator](https://github.com/anthropics/skills/tree/main/skills/skill-creator) - Create, test and improve your own skills.

## Other Lists

<!-- Link related awesome lists here. -->

---

## Contributing

Found a great skill? Open a PR. See [CONTRIBUTING.md](CONTRIBUTING.md).

## License

[![CC0](https://licensebuttons.net/p/zero/1.0/88x31.png)](https://creativecommons.org/publicdomain/zero/1.0/)

This list is released under CC0. Each linked skill keeps its own license; check the original repo before reusing it.
