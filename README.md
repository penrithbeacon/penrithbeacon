# Penrith Beacon — Widget Context Protocol

> Building the open standard for embeddable UI widgets in dashboard environments

**[Widget Context Protocol (WCP)](https://widgetcontextprotocol.com)** is an open protocol that allows any server — Docker container, local process, or cloud service — to expose a compact UI widget and register capabilities with a host dashboard. Modelled on the principles of Anthropic's Model Context Protocol (MCP), WCP brings the same plug-and-play extensibility to visual interfaces.

---

## WCP Widget Catalogue

The WCP protocol is open — anyone can build and publish their own widgets. The catalogue below lists the widgets we publish and maintain as part of the Penrith Beacon ecosystem. Our range will continue to grow: some designed for production needs and real-world solutions, others crafted specifically as tutorials to guide developers building their own WCP widgets.

All images below are available on [Docker Hub](https://hub.docker.com/u/penrithbeacon) with full source on GitHub.

| Widget | Version | WCP | Description | Links |
|--------|:-------:|:---:|-------------|:-----:|
| **QR Generator** | 1.8.0 | 2.1.0 | QR code generation for any URL or text | [GitHub](https://github.com/penrithbeacon/wcp-widget-qr-generator) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-qr-generator) |
| **Weather Ticker** | 1.6.0 | 2.1.0 | Live weather data via Open-Meteo API | [GitHub](https://github.com/penrithbeacon/wcp-widget-weather-ticker) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-weather-ticker) |
| **Theme Studio** | 1.7.0 | 2.1.0 | Theme gallery and editor — 15 built-in themes + custom theme creator | [GitHub](https://github.com/penrithbeacon/wcp-widget-theme-studio) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-theme-studio) |
| **Radio** | 1.6.0 | 2.1.0 | Internet radio player — search and stream thousands of stations | [GitHub](https://github.com/penrithbeacon/wcp-widget-radio) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-radio) |
| **Cloudflare** | 1.4.0 | 2.1.0 | Workers, Domains, and DNS management | [GitHub](https://github.com/penrithbeacon/wcp-widget-cloudflare) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-cloudflare) |
| **GitHub** | 1.4.0 | 2.1.0 | Repository browser for any GitHub account | [GitHub](https://github.com/penrithbeacon/wcp-widget-github) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-github) |
| **Docker** | 1.4.0 | 2.1.0 | Container management — local and remote Docker hosts | [GitHub](https://github.com/penrithbeacon/wcp-widget-docker) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-docker) |
| **Claude Analytics** | 1.2.0 | 2.1.0 | Claude Code analytics + companion host agent *(experimental)* | [GitHub](https://github.com/penrithbeacon/wcp-widget-claude) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-widget-claude) |

### Companion Services

| Service | Version | Description | Links |
|---------|:-------:|-------------|:-----:|
| **Docker Agent** | 1.2.0 | Authenticated Docker socket proxy for remote container management | [GitHub](https://github.com/penrithbeacon/wcp-docker-agent) · [Docker Hub](https://hub.docker.com/r/penrithbeacon/wcp-docker-agent) |

---

## AI-Powered Widget Documentation

**One URL. Any AI. Fully compliant WCP documentation — generated, audited, and maintained automatically.**

The **[WCP AI Automation](https://github.com/penrithbeacon/wcp-ai-automation)** repository contains everything an AI engine needs to produce standardised documentation for any WCP widget. Templates, audit checklists, release workflows, and a detailed AI skill document — all machine-readable and ready to consume.

### How It Works

Give your AI a single instruction:

> _"Read https://github.com/penrithbeacon/wcp-ai-automation/blob/main/AI-SKILL.md and use it to create documentation for my WCP widget."_

Your AI will:
- Extract endpoints, components, and metadata from your widget source code
- Generate a standards-compliant **README.md** and **DOCKER.md**
- Run pre-release audits against the running container
- Cross-reference every route in your code against the documentation

| | |
|--|--|
| **Repository** | [penrithbeacon/wcp-ai-automation](https://github.com/penrithbeacon/wcp-ai-automation) |
| **AI Skill** | [AI-SKILL.md](https://github.com/penrithbeacon/wcp-ai-automation/blob/main/AI-SKILL.md) |
| **Standards Version** | 1.0.0 |

---

## About Penrith Beacon

This project is maintained by **Penrith Beacon Communications** ([penrithbeacon.com](https://penrithbeacon.com)), a developer tools initiative led by Anthony Harrison. The focus is on WCP — designing and implementing an open protocol for widget orchestration, and building a production-quality reference ecosystem of widgets, host applications, and developer tooling.

---

## Project Status

| | |
|--|--|
| **WCP Version** | 2.1.0 |
| **Active Work** | Layout Doctrine implementation, widget ecosystem expansion, WCP Developer Guide |
| **Coming Soon** | WCP Bonjour — zero-configuration service discovery for widgets |
| **Specification** | [widgetcontextprotocol.com](https://widgetcontextprotocol.com) |

### Penrith Beacon WCP Suite

The full application suite — not yet publicly released — consists of:

- **Penrith Beacon Design Studio** — the primary development environment for creating, configuring, and curating widget orchestrations
- **Penrith Beacon Orchestration Manager** — standalone orchestration management without the full studio
- **Penrith Beacon Kiosk (Alpha / Beta / Release)** — a graduated launch pipeline that, in association with the Orchestration Manager, manages the transition of any widget or application from alpha through beta to production release

The suite will be publicly released when it reaches public beta. In the meantime, the widgets, protocol specification, and developer guide are available now for anyone building with WCP.

---

## Links

- [Widget Context Protocol Specification](https://widgetcontextprotocol.com)
- [WCP Developer Guide](https://dev.widgetcontextprotocol.com)
- [WCP AI Automation](https://github.com/penrithbeacon/wcp-ai-automation)
- [Penrith Beacon](https://penrithbeacon.com)
- [Docker Hub — penrithbeacon](https://hub.docker.com/u/penrithbeacon)
