# agency-master

A complete AI agency with a master orchestrator — fork of [agency-agents](https://github.com/msitarzewski/agency-agents) enhanced with a hierarchical orchestration system.

## What is this?

This repo combines **169 specialized AI agents** from agency-agents with a **custom orchestration hierarchy** that automatically routes tasks to the right specialist.

## Orchestration Hierarchy

```
Director (master entry point)
├── TechLead      → 35 agents: engineering, spatial computing, security
├── DataLead      → 14 agents: data pipelines, AI/ML, analytics
├── QALead        → 14 agents: testing, QA, compliance, security audits
├── ProductLead   → 22 agents: product, UX/UI, design, game dev
├── MarketingLead → 37 agents: content, SEO, paid media, China market
├── SalesLead     → 13 agents: sales, BD, market entry
├── FinanceLead   → 13 agents: finance, legal, accounting
└── OpsLead       → 20 agents: operations, HR, support, academic
```

## Installation

### Claude Code
```bash
cp orchestrator/SKILL.md ~/.claude/agents/master-director.md
cp orchestrator/leads/*.md ~/.claude/agents/
```

### All IDEs (Claude Code, Copilot, OpenCode, Antigravity)
See [INSTALLATION.md](INSTALLATION.md)

## Usage

Activate `master-director` in your AI tool and just describe your task. The Director analyzes it and delegates to the right lead, who then routes to the best specialist agent.

**Example:**
> "Build a React dashboard with authentication and deploy to AWS"
→ Director → TechLead → Frontend Developer + Backend Architect + DevOps Automator

## Credits

- Original agents: [agency-agents](https://github.com/msitarzewski/agency-agents) by @msitarzewski
- Orchestration system: [develop-skills](https://github.com/javalenciacai/develop-skills)
