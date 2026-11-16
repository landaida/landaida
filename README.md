# Ariel Landaida

Senior full-stack developer. I build scrapers and automations that keep working on sites that block everyone else, the backend systems around them, and lately the tooling that lets AI agents touch real systems safely. Paraguay (UTC-3). English, Spanish, Portuguese.

## What I build

- **Data collection at scale, behind anti-bot walls.** A production engine that collects about one million records a year from large marketplaces protected by Akamai, DataDome, Cloudflare and PerimeterX: headed Chrome/Firefox on Xvfb (never headless), residential and mobile proxies with session pinning, queues, resumable processing, and monitoring that pages me before the client notices. Public references of the same craft: Leboncoin.fr, Vinted, golf and padel booking platforms.
- **Mobile app APIs when there is no public API.** Rooted Android emulator, mitmproxy, Frida, WebSocket protocols (SendBird, Ably), HMAC-signed requests. You get a documented working client.
- **AI agents with guarded tool access.** MCP servers and Claude Code automation (hooks, skills, subagents) that give an agent database or system access without write access, unbounded reads or an invisible audit trail. I also run scheduled multi-agent pipelines in production: an orchestrator drives cheap sub-agents, and every conclusion has to cite the command that produced it.
- **Atlassian Confluence.** Data Center plugins in Java (blueprints, Active Objects, REST, Comala, Scroll) and Data Center → Forge migrations. Built the official-correspondence system of Itaipu Binacional on Confluence DC, in production since 2023.
- **Web apps and internal tools.** Next.js/React dashboards on AWS Lambda + CloudFront, Node/Express APIs, Java 21 Spring Boot backends (MySQL, SQS, Cognito). I also finish and fix apps started with AI tools.

## Selected repositories

| Repository | What it is |
|---|---|
| [pg-readonly-mcp](https://github.com/landaida/pg-readonly-mcp) | Read-only PostgreSQL MCP server with layered guardrails (AST table allow-list, SELECT-only, READ ONLY transactions, timeouts, row/byte caps, JSONL audit) plus a Claude Code hook and skill. 94 unit + 15 integration tests. |
| [playwright-firefox-headful-harness](https://github.com/landaida/playwright-firefox-headful-harness) | Headful Playwright + Firefox on Xvfb in Docker, the shape of browser that survives anti-bot scoring. |
| [xinput-browser-driver](https://github.com/landaida/xinput-browser-driver) | Drive a real browser through X input events instead of a CDP client, for sites where any automation client triggers challenges. |
| [android-api-capture-playbook](https://github.com/landaida/android-api-capture-playbook) | Reproducible rig for capturing an Android app's private API: rootable AVD, CA injection, QUIC blocking, Frida, realtime WebSocket capture. |
| [forge-confluence-template-pages](https://github.com/landaida/forge-confluence-template-pages) | Atlassian Forge app: create Confluence pages from templates, the Forge-side counterpart of a Data Center blueprint plugin. |
| [atlassian-confluence-blueprint-plugin-with-aop](https://github.com/landaida/atlassian-confluence-blueprint-plugin-with-aop) | Confluence Data Center blueprint plugin in Java with AOP, the pattern behind the Itaipu correspondence system. |

## How I work

You send the URL, the fields and the daily volume; I reply with a feasibility check within 24 hours, then deliver Dockerized code with a README and a sample dataset. I don't scrape personal data of private individuals, log into accounts you don't own, or bypass payments or DRM.

- Upwork: [21 contracts, all rated 5.0](https://www.upwork.com/freelancers/~01e6848ab590f8b508)
- Workana: [profile](https://www.workana.com/freelancer/531da92e7cecd2b472ce00ac877afef8)
