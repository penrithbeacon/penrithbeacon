# Penrith Beacon

Home of the **[Open AI Skill Package](https://openaiskillpackage.com/)** specification and the **[Widget Context Protocol](https://widgetcontextprotocol.com)** — two open standards for a new kind of AI-augmented computing.

→ [Open AI Skill Package](#open-ai-skill-package)
→ [Widget Context Protocol](#widget-context-protocol)

---

> ### AI Independence Day — 4 July 2026
>
> On 4 July 2026 — the date we mark as **AI Independence Day** — Penrith Beacon published the Open AI Skill Package specification: the first normative open standard to formalise the separation of AI computation from AI generation.
>
> Until now, when you asked an AI agent to perform a complex task, it authored the solution in the moment — reasoning its way through steps it had never verified, producing output that could differ each time. An AI Skill Package changes that contract. The procedure has been written in advance, tested, packaged, and signed. When the agent runs it, it executes work that already exists — against inputs you provide, toward an outcome that has already been verified.
>
> The computation is independent of the generation. **The AI becomes the executor, not the author.**
>
> That is the independence the date marks. This is where it began.

---

## Open AI Skill Package

Penrith Beacon is the home of the **[Open AI Skill Package](https://openaiskillpackage.com/)** specification — an open standard that defines a new category of AI artefact: the `.aiskill` package.

Most AI interactions are prompt-driven — a user types an instruction and the agent generates a response in the moment. An AI Skill Package is something different. It is a structured, versioned, unit-tested archive containing pre-authored procedure, executable scripts, templates, tests, and a manifest. When an agent receives one, the thinking has already been done. The agent does not improvise — it executes.

The specification is published at [openaiskillpackage.com](https://openaiskillpackage.com/). The first package published under it is **CREATE-AISKILL** — the meta-skill from which every other AI Skill Package can be made.

| Package | Version | Description | Links |
|---------|:-------:|-------------|:-----:|
| **CREATE-AISKILL** | 1.0.0 | The origin skill — scaffolds any new `.aiskill` package from a plain-language description | [GitHub](https://github.com/penrithbeacon/AISKILL-CREATE-AISKILL) · [Download v1.0.0](https://github.com/penrithbeacon/AISKILL-CREATE-AISKILL/releases/tag/v1.0.0) |

---

## Widget Context Protocol

> Building the open standard for embeddable UI widgets in dashboard environments

**[Widget Context Protocol (WCP)](https://widgetcontextprotocol.com)** is an open protocol that allows any server — Docker container, local process, or cloud service — to expose a compact UI widget and register capabilities with a host dashboard. Modelled on the principles of Anthropic's Model Context Protocol (MCP), WCP brings the same plug-and-play extensibility to visual interfaces.

---

## WCP Widget Catalogue

The WCP protocol is open — anyone can build and publish their own widgets. The catalogue below lists the widgets we publish and maintain as part of the Penrith Beacon ecosystem. Our range will continue to grow: some designed for production needs and real-world solutions, others crafted specifically as tutorials to guide developers building their own WCP widgets.

All images below are available on [Docker Hub](https://hub.docker.com/u/penrithbeacon) with full source on GitHub.

| Widget | Version | WCP | Description | Links |
|--------|:-------:|:---:|-------------|:-----:|
| **Markdown Editor** | 1.1.0-beta | 2.1.0 | WYSIWYG markdown editor with folder browser and companion host agent | [GitHub](https://github.com/penrithbeacon/wcp-widget-markdown-editor) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-markdown-editor) |
| **Claude Analytics** | 1.2.0 | 2.1.0 | Claude Code analytics + companion host agent *(experimental)* | [GitHub](https://github.com/penrithbeacon/wcp-widget-claude) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-claude) |
| **GitHub** | 1.4.0 | 2.1.0 | Repository browser for any GitHub account | [GitHub](https://github.com/penrithbeacon/wcp-widget-github) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-github) |
| **Docker** | 1.4.0 | 2.1.0 | Container management — local and remote Docker hosts | [GitHub](https://github.com/penrithbeacon/wcp-widget-docker) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-docker) |
| **Cloudflare** | 1.4.0 | 2.1.0 | Workers, Domains, and DNS management | [GitHub](https://github.com/penrithbeacon/wcp-widget-cloudflare) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-cloudflare) |
| **Theme Studio** | 1.7.0 | 2.1.0 | Theme gallery and editor — 15 built-in themes + custom theme creator | [GitHub](https://github.com/penrithbeacon/wcp-widget-theme-studio) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-theme-studio) |
| **Radio** | 1.6.0 | 2.1.0 | Internet radio player — search and stream thousands of stations | [GitHub](https://github.com/penrithbeacon/wcp-widget-radio) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-radio) |
| **QR Generator** | 1.8.0 | 2.1.0 | QR code generation for any URL or text | [GitHub](https://github.com/penrithbeacon/wcp-widget-qr-generator) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-qr-generator) |
| **Weather Ticker** | 1.6.0 | 2.1.0 | Live weather data via Open-Meteo API | [GitHub](https://github.com/penrithbeacon/wcp-widget-weather-ticker) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-weather-ticker) |

### Companion Agents

| Agent | Version | Description | Links |
|-------|:-------:|-------------|:-----:|
| **Markdown Editor Agent** | 1.0.2 | Host filesystem agent for the Markdown Editor widget — macOS | [GitHub](https://github.com/penrithbeacon/wcp-agent-markdown-editor) |
| **Docker Agent** | 1.2.0 | Authenticated Docker socket proxy for remote container management | [GitHub](https://github.com/penrithbeacon/wcp-docker-agent) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-docker-agent) |

---

## 🔨 AI-Assisted Building

**One URL. Any AI. Design and build any WCP artefact — widget or agent — from first question to running code.**

The **[WCP AI Build](https://github.com/penrithbeacon/wcp-ai-build)** repository is the entry point for building with AI. Give your AI a single URL and it will orient you in the WCP ecosystem, ask what you want to build, and walk you through every design and implementation decision — including technology choice, component structure, data sources, and packaging.

Give your AI a single instruction:

> _"Read https://github.com/penrithbeacon/wcp-ai-build/blob/main/AI-SKILL.md and help me build a WCP artefact."_

Your AI will ask what you want to build and route you to the appropriate specialist skill.
You can also go directly to the right skill:

| Goal | Give your AI this URL |
|------|-----------------------|
| Not sure yet — start here | [wcp-ai-build/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-build/blob/main/AI-SKILL.md) |
| Build a widget | [wcp-ai-build-widget/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-build-widget/blob/main/AI-SKILL.md) |
| Build an agent | [wcp-ai-build-agent/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-build-agent/blob/main/AI-SKILL.md) |
| Build a macOS agent | [wcp-ai-build-agent-mac/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-build-agent-mac/blob/main/AI-SKILL.md) |
| Release a widget or agent | [wcp-ai-release/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-release/blob/main/AI-SKILL.md) |

You do not need to know the implementation technology. The AI will offer industry-standard options and proceed with a conservative, widely-adopted default if you prefer to defer that decision.

---

## 🚀 AI-Powered Release Pipeline

**From verified local build to published Docker image and GitHub Release — guided by AI, with your consent at every public push.**

The **[WCP AI Release](https://github.com/penrithbeacon/wcp-ai-release)** repository is the entry point for releasing any WCP artefact. It establishes the release stage (beta or production) and mode (dry run or live), then routes to the appropriate specialist skill.

Give your AI a single instruction:

> _"Read https://github.com/penrithbeacon/wcp-ai-release/blob/main/AI-SKILL.md and release my WCP widget."_

The pipeline routes to the right specialist:

| Artefact | Specialist skill |
|----------|-----------------|
| Widget | [wcp-ai-release-widget/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-release-widget/blob/main/AI-SKILL.md) |
| Agent (macOS .pkg) | [wcp-ai-release-agent/AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-release-agent/blob/main/AI-SKILL.md) |

The pipeline enforces explicit developer consent before every public push and closes with a mandatory written summary of every action taken — because the developer is personally responsible for everything published under their identity.

The **[WCP AI Automation](https://github.com/penrithbeacon/wcp-ai-automation)** repository provides the supporting standards: documentation templates, audit checklists, and the widget build specification that the build and release pipelines reference.

---

## About Penrith Beacon

This project is maintained by **Penrith Beacon Communications** ([penrithbeacon.com](https://penrithbeacon.com)), a developer tools initiative led by Anthony Harrison. The focus is on WCP — designing and implementing an open protocol for widget orchestration, and building a production-quality reference ecosystem of widgets, host applications, and developer tooling.

---

## Project Status

| | |
|--|--|
| **WCP Version** | 2.1.0 |
| **Active Work** | Layout Doctrine implementation, widget ecosystem expansion, WCP Developer Guide |
| **Coming Soon** | `ai.widgetcontextprotocol.com` — the complete AI build & release guide for WCP; WCP Bonjour — zero-configuration service discovery for widgets |
| **Specification** | [widgetcontextprotocol.com](https://widgetcontextprotocol.com) |

### Penrith Beacon WCP Suite

The full application suite — not yet publicly released — consists of:

- **Penrith Beacon Design Studio** — the primary development environment for creating, configuring, and curating widget orchestrations
- **Penrith Beacon Orchestration Manager** — standalone orchestration management without the full studio
- **Penrith Beacon Kiosk (Alpha / Beta / Release)** — a graduated launch pipeline that, in association with the Orchestration Manager, manages the transition of any widget or application from alpha through beta to production release
- **Penrith Beacon Forge Transformer** *(not yet started)* — takes a distributable `.wcpa` application file and forges it into a fully independent native application for macOS, Linux, or Windows; handles transformation, packaging, and deployment into a standalone distributable

The suite will be publicly released when it reaches public beta. In the meantime, the widgets, protocol specification, and developer guide are available now for anyone building with WCP.

---

## Links

- [Widget Context Protocol Specification](https://widgetcontextprotocol.com)
- [WCP Developer Guide](https://dev.widgetcontextprotocol.com)
- [WCP AI Build](https://github.com/penrithbeacon/wcp-ai-build)
- [WCP AI Build — Widget](https://github.com/penrithbeacon/wcp-ai-build-widget)
- [WCP AI Build — Agent](https://github.com/penrithbeacon/wcp-ai-build-agent)
- [WCP AI Build — Agent (macOS)](https://github.com/penrithbeacon/wcp-ai-build-agent-mac)
- [WCP AI Release](https://github.com/penrithbeacon/wcp-ai-release)
- [WCP AI Release — Widget](https://github.com/penrithbeacon/wcp-ai-release-widget)
- [WCP AI Release — Agent](https://github.com/penrithbeacon/wcp-ai-release-agent)
- [WCP AI Automation](https://github.com/penrithbeacon/wcp-ai-automation)
- [Penrith Beacon](https://penrithbeacon.com)
- [Docker Hub — penrithbeacon](https://hub.docker.com/u/penrithbeacon)
