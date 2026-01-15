<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://port-graphical-assets.s3.eu-west-1.amazonaws.com/logos/port-logo-dark-bg.svg">
  <source media="(prefers-color-scheme: light)" srcset="https://port-graphical-assets.s3.eu-west-1.amazonaws.com/logos/port-logo-light-bg.svg">
  <img alt="Port" src="https://port-graphical-assets.s3.eu-west-1.amazonaws.com/Port+Logo+With+Background.png" width="200">
</picture>

# The Agentic Developer Portal

<p align="center">
  <strong>Where AI agents meet platform engineering. Context-aware. Guardrailed. Autonomous.</strong>
</p>

<p align="center">
  <a href="https://www.port.io"><img src="https://img.shields.io/badge/Website-port.io-6C5CE7?style=for-the-badge" alt="Website"></a>
  <a href="https://docs.port.io"><img src="https://img.shields.io/badge/Docs-Read%20Now-00B894?style=for-the-badge" alt="Documentation"></a>
  <a href="https://demo.port.io"><img src="https://img.shields.io/badge/Demo-Try%20Live-0984E3?style=for-the-badge" alt="Live Demo"></a>
  <a href="https://join.slack.com/t/port-community/shared_invite/zt-1wdjwizkn-0i7g9LQeQ4rdU5_YSe6vDA"><img src="https://img.shields.io/badge/Community-Join%20Slack-E91E63?style=for-the-badge&logo=slack" alt="Slack"></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Series%20C-$100M-gold?style=flat-square" alt="Funding">
  <img src="https://img.shields.io/badge/Valuation-$800M-gold?style=flat-square" alt="Valuation">
  <img src="https://img.shields.io/badge/Customers-GitHub%20%7C%20Visa%20%7C%20BT-blue?style=flat-square" alt="Customers">
  <img src="https://img.shields.io/badge/Growth-300%25%20YoY-brightgreen?style=flat-square" alt="Growth">
</p>

---

## AI Agents Are Here

Coding is only 10% of a developer's day. The other 90%? Operational chaos.

**Port's AI agents autonomously handle the rest:**

| Agent | What It Does |
|-------|--------------|
| **Task Manager** | Plans your day, surfaces priority work, executes self-service actions |
| **Incident Manager** | Acknowledges pages, pulls runbooks, coordinates response |
| **Clarity AI** | Auto-enriches Jira tickets with service context & ownership |
| **Custom Agents** | Build your own with Port's blueprints & guardrails |

### Ask Your Portal Anything

```
"Who is on call for the payments service?"
"Which services don't meet our Gold standard?"
"What are my team's open PRs to review?"
"Scaffold a new microservice for me"
```

Agents inherit your RBAC permissions. They only see what you're allowed to see.

> *"Not just using AI, but making AI agents first-class citizens in the developer portal."*

<p align="center">
  <a href="https://docs.port.io/ai-agents/"><img src="https://img.shields.io/badge/Learn-AI%20Agents%20Docs-blueviolet?style=for-the-badge" alt="AI Agents Documentation"></a>
  <a href="https://demo.port.io"><img src="https://img.shields.io/badge/Try-Live%20Demo-00B894?style=for-the-badge" alt="Try Demo"></a>
</p>

---

## Why Port for AI Agents?

**Context is King.** Without the right context, agents hallucinate. With Port, they don't.

<table>
<tr>
<td align="center" width="33%">
<h3>Context</h3>
<p>Dynamic context enrichment from your entire stack: K8s, GitHub, Jira, PagerDuty, and 50+ integrations. Agents know your services, ownership, dependencies, and runbooks.</p>
</td>
<td align="center" width="33%">
<h3>Guardrails</h3>
<p>Input validation, output filtering, action authorization. Define what agents can and cannot do. Monitor behavior, trigger alerts on violations.</p>
</td>
<td align="center" width="33%">
<h3>Observability</h3>
<p>Full visibility into agent workflows. Track decisions, audit actions, debug issues. Know exactly what happened and why.</p>
</td>
</tr>
</table>

> *"Port provides the context that allows you to build and ship agents that you can actually trust."*

---

## Works Where You Work

Port meets developers in their flow. Zero context-switching. Zero friction.

<table>
<tr>
<td align="center" width="150">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/vscode/vscode-original.svg" width="48" height="48" alt="Cursor"/>
  <br><strong>Cursor / VS Code</strong>
  <br><sub>MCP Integration</sub>
</td>
<td align="center" width="150">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/slack/slack-original.svg" width="48" height="48" alt="Slack"/>
  <br><strong>Slack</strong>
  <br><sub>Native Bot</sub>
</td>
<td align="center" width="150">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/jira/jira-original.svg" width="48" height="48" alt="Jira"/>
  <br><strong>Jira</strong>
  <br><sub>Bi-directional Sync</sub>
</td>
<td align="center" width="150">
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/github/github-original.svg" width="48" height="48" alt="GitHub"/>
  <br><strong>GitHub</strong>
  <br><sub>Copilot Ready</sub>
</td>
</tr>
</table>

### MCP Server for AI IDEs

Connect your AI-powered IDE directly to Port's Context Lake:

```bash
# Install via uvx (recommended)
uvx mcp-server-port --client-id <YOUR_ID> --client-secret <YOUR_SECRET>

# Or via Docker
docker pull ghcr.io/port-labs/port-mcp-server:latest
```

<p align="center">
  <a href="https://github.com/port-labs/port-mcp-server"><img src="https://img.shields.io/badge/GitHub-port--mcp--server-181717?style=flat-square&logo=github" alt="MCP Server Repo"></a>
</p>

---

## The Platform

<table>
<tr>
<td width="50%">

### Context Lake
The unified data layer that feeds your AI agents with the right context, the right guardrails, and the right scope.

- Real-time ingestion from all sources
- Dynamic software modeling
- Agent-ready data structures

</td>
<td width="50%">

### Software Catalog
Not a static wiki. A living, breathing map of your entire software ecosystem.

- Auto-discovered from K8s, Terraform, GitHub
- Scorecards & maturity tracking
- Custom data models (Blueprints)

</td>
</tr>
<tr>
<td width="50%">

### Self-Service Actions
Golden paths without the bottlenecks. Developers ship, platforms govern.

- No-code workflow builder
- Approval flows & RBAC
- Any backend: GitHub Actions, Jenkins, ArgoCD

</td>
<td width="50%">

### Scorecards
Production readiness isn't a vibe. It's measurable.

- Security, reliability, ownership
- Real-time compliance tracking
- Gamified developer experience

</td>
</tr>
</table>

---

## Open Source Ecosystem

We believe in open foundations. Our core integrations are open source.

<table>
<tr>
<td align="center">
<a href="https://github.com/port-labs/ocean">
<img src="https://img.shields.io/github/stars/port-labs/ocean?style=social" alt="Stars">
<br><strong>Ocean</strong>
<br><sub>Integration Framework</sub>
</a>
</td>
<td align="center">
<a href="https://github.com/port-labs/port-k8s-exporter">
<img src="https://img.shields.io/github/stars/port-labs/port-k8s-exporter?style=social" alt="Stars">
<br><strong>K8s Exporter</strong>
<br><sub>Kubernetes Integration</sub>
</a>
</td>
<td align="center">
<a href="https://github.com/port-labs/port-aws-exporter">
<img src="https://img.shields.io/github/stars/port-labs/port-aws-exporter?style=social" alt="Stars">
<br><strong>AWS Exporter</strong>
<br><sub>Cloud Resources</sub>
</a>
</td>
<td align="center">
<a href="https://github.com/port-labs/terraform-provider-port-labs">
<img src="https://img.shields.io/github/stars/port-labs/terraform-provider-port-labs?style=social" alt="Stars">
<br><strong>Terraform Provider</strong>
<br><sub>IaC Native</sub>
</a>
</td>
</tr>
<tr>
<td align="center">
<a href="https://github.com/port-labs/port-agent">
<img src="https://img.shields.io/github/stars/port-labs/port-agent?style=social" alt="Stars">
<br><strong>Port Agent</strong>
<br><sub>Self-Hosted Runner</sub>
</a>
</td>
<td align="center">
<a href="https://github.com/port-labs/port-mcp-server">
<img src="https://img.shields.io/github/stars/port-labs/port-mcp-server?style=social" alt="Stars">
<br><strong>MCP Server</strong>
<br><sub>AI IDE Integration</sub>
</a>
</td>
<td align="center">
<a href="https://github.com/port-labs/pulumi-port">
<img src="https://img.shields.io/github/stars/port-labs/pulumi-port?style=social" alt="Stars">
<br><strong>Pulumi Provider</strong>
<br><sub>Modern IaC</sub>
</a>
</td>
<td align="center">
<a href="https://github.com/port-labs/port-docs">
<img src="https://img.shields.io/github/stars/port-labs/port-docs?style=social" alt="Stars">
<br><strong>Documentation</strong>
<br><sub>Open Source Docs</sub>
</a>
</td>
</tr>
</table>

---

## Quick Start

```bash
# 1. Sign up at port.io (free tier available)

# 2. Install the Ocean CLI for integrations
pip install port-ocean

# 3. Connect your first data source
ocean sail github  # or: kubernetes, aws, jira, pagerduty...

# 4. Start building self-service actions
# Use the UI or Terraform/Pulumi providers
```

<p align="center">
  <a href="https://docs.port.io/quickstart"><img src="https://img.shields.io/badge/Quickstart-5%20Minutes-success?style=for-the-badge" alt="Quickstart Guide"></a>
</p>

---

## Trusted By Engineering Teams Worldwide

<p align="center">
  <strong>GitHub</strong> · <strong>Visa</strong> · <strong>British Telecom</strong> · <strong>CyberArk</strong> · <strong>StubHub</strong> · <strong>Sonar</strong> · <strong>Wiz</strong> · <strong>Nando's</strong>
</p>

---

## Get Involved

<table>
<tr>
<td align="center">
  <a href="https://github.com/port-labs/ocean/issues?q=is%3Aissue+is%3Aopen+label%3A%22good+first+issue%22">
    <strong>Good First Issues</strong>
  </a>
  <br><sub>Start contributing</sub>
</td>
<td align="center">
  <a href="https://join.slack.com/t/port-community/shared_invite/zt-1wdjwizkn-0i7g9LQeQ4rdU5_YSe6vDA">
    <strong>Slack Community</strong>
  </a>
  <br><sub>5000+ members</sub>
</td>
<td align="center">
  <a href="https://docs.port.io/actions-and-automations/">
    <strong>Build Self-Service</strong>
  </a>
  <br><sub>Tutorials & guides</sub>
</td>
<td align="center">
  <a href="https://www.port.io/blog">
    <strong>Engineering Blog</strong>
  </a>
  <br><sub>Deep dives & insights</sub>
</td>
</tr>
</table>

---

<p align="center">
  <sub>Built with conviction in Tel Aviv · Backed by <a href="https://www.accel.com">Accel</a>, <a href="https://www.generalatlantic.com">General Atlantic</a> & <a href="https://www.bvp.com">Bessemer</a></sub>
</p>

<p align="center">
  <a href="https://twitter.com/tweetsbyport"><img src="https://img.shields.io/badge/Twitter-@tweetsbyport-1DA1F2?style=flat-square&logo=twitter" alt="Twitter"></a>
  <a href="https://www.linkedin.com/company/getport/"><img src="https://img.shields.io/badge/LinkedIn-Port-0A66C2?style=flat-square&logo=linkedin" alt="LinkedIn"></a>
  <a href="https://www.youtube.com/@getport"><img src="https://img.shields.io/badge/YouTube-Port-FF0000?style=flat-square&logo=youtube" alt="YouTube"></a>
</p>
