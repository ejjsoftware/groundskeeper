# Groundskeeper

**Self-hosted IT operations intelligence for schools and Multi-Academy Trusts.**

Groundskeeper pulls together data from the systems your IT team already
relies on — network, cloud, backup, endpoint management, and more — into a
single dashboard with alerts, AI-assisted summaries, and an at-a-glance
traffic-light view for senior leadership.

🔗 **[groundskeeper.ejjsoftware.com](https://groundskeeper.ejjsoftware.com)**

## What it monitors

- **Network** — Cisco Meraki devices and MT environmental sensors
- **Microsoft 365** — service health via Microsoft Graph
- **Backups** — Veeam job status
- **Endpoint management** — Action1 (multi-org, EU/US/AU regions)
- **Active Directory & Windows Server** — health, disk space, Windows 11 readiness
- **Firewalls & UTM** — WatchGuard Firebox and Endpoint
- **Hardware** — Dell iDRAC
- **MIS status pages** — e.g. Bromcom
- **Domain security** — SPF, DMARC, DKIM, TLS, HTTPS, security headers
- and more, with new connectors added regularly

## Why self-hosted

Groundskeeper runs entirely on your own network. Your data never leaves the
school — no cloud subscription, no third party seeing your infrastructure
details. This matters for GDPR compliance and for IT teams who'd rather not
add another vendor with access to their systems.

Groundskeeper is also **read-only** by design: it observes and reports, but
never makes changes to any connected system.

## Optional AI features

AI-assisted features (daily summaries, natural-language queries, drafting
communications) are available and can run either:

- **Locally**, via [Ollama](https://ollama.com/) — fully private, no data
  leaves your network
- Or via a **cloud provider** of your choice (Azure OpenAI, OpenAI,
  Anthropic Claude, Google Gemini) for schools that want a more capable
  assistant and are comfortable with the relevant data processing terms

AI features are entirely optional and can be switched off completely.

## Getting started

- **Website** — visit [groundskeeper.ejjsoftware.com](https://groundskeeper.ejjsoftware.com)
  for an overview of the product
- **Releases** — download the latest installer from the
  [Releases](../../releases) page
- **Documentation** — see the [Wiki](../../wiki) for setup guides, connector
  configuration, and FAQs
- **Discussions** — questions, feature requests and community support happen
  in [Discussions](../../discussions)

## About

Groundskeeper is built by **EJJ Software**, founded by a working school IT
manager and a software developer, for the school IT community.

Visit [ejjsoftware.com](https://ejjsoftware.com) for more information.

## Licence

© EJJ Software. All rights reserved.

This repository is provided for transparency, release distribution, and
community support. No licence is granted for reuse, modification, or
redistribution of the source code.
