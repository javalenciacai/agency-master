# agency-master

A complete AI agency — **178 skills** with a master Director that automatically routes any task to the right specialist.

Fork of [agency-agents](https://github.com/msitarzewski/agency-agents) enhanced with a hierarchical orchestration system.

```
npx skills add javalenciacai/agency-master
```

---

## What is this?

One install. 178 specialist AI skills. Instead of picking the right agent yourself, just describe your task to the **Director** and it delegates automatically — to the right domain lead, who delegates to the right specialist.

```
You: "Build a React dashboard with auth and deploy to AWS"

Director → TechLead → frontend-developer
                    → backend-architect
                    → devops-automator
```

---

## Hierarchy

```
director  (master entry point)
├── techlead      →  35 specialists: engineering, DevOps, security, spatial computing
├── datalead      →  14 specialists: data pipelines, AI/ML, analytics, RAG
├── qalead        →  14 specialists: testing, QA, security audits, compliance
├── productlead   →  22 specialists: product, UX/UI, design, game dev
├── marketinglead →  37 specialists: content, SEO, paid media, China market
├── saleslead     →  13 specialists: sales, BD, proposals, market entry
├── financelead   →  13 specialists: finance, legal, accounting, tax
└── opslead       →  20 specialists: support, HR, ops, healthcare, real estate
```

---

## Install

### Via skills.sh (recommended)
```bash
npx skills add javalenciacai/agency-master
```

### Claude Code
```bash
# Just the orchestrator
cp orchestrator/SKILL.md ~/.claude/agents/master-director.md
cp orchestrator/leads/*.md ~/.claude/agents/

# All 178 skills
cp -r skills/*/SKILL.md ~/.claude/agents/
```

### GitHub Copilot
```bash
cp orchestrator/SKILL.md ~/.github/agents/master-director.md
cp orchestrator/leads/*.md ~/.github/agents/
```

### OpenCode
```bash
cp orchestrator/SKILL.md ~/.config/opencode/agents/master-director.md
cp orchestrator/leads/*.md ~/.config/opencode/agents/
```

### Antigravity / Gemini
```bash
# Install each skill to its own folder
for dir in skills/*/; do
  name=$(basename "$dir")
  mkdir -p ~/.gemini/antigravity/skills/$name
  cp "$dir/SKILL.md" ~/.gemini/antigravity/skills/$name/
done
```

---

## Usage

Activate the `director` skill in your AI tool and describe your task. No need to know which agent does what — Director figures it out.

```
@director Build a SaaS app with Next.js, auth, and payments
@director Write a 30-day LinkedIn + Twitter content calendar
@director We have a production incident, memory leak, P0
@director Prepare our Series A data room and financial model
@director We want to expand to Korea and Brazil
```

You can also activate any specialist directly if you know exactly what you need:

```
@seo-specialist audit our blog for technical SEO issues
@legal-document-review review this vendor contract
@data-engineer build a Postgres → Snowflake ETL pipeline
```

---

## Use Cases

→ **[USE-CASES.md](USE-CASES.md)** — 50+ real examples organized by domain, including multi-lead orchestration flows

Quick overview:

| Domain | Example |
|---|---|
| 🛠 Engineering | Build APIs, ship mobile apps, fix production incidents, set up CI/CD |
| 📊 Data & AI | ETL pipelines, ML models, RAG systems, data quality cleanup |
| 🔍 QA & Security | Test plans, security audits, smart contract review, performance tuning |
| 🎨 Product & Design | PRDs, UX flows, sprint planning, rapid prototypes |
| 📣 Marketing | Content calendars, SEO strategy, paid media audit, launch campaigns |
| 💼 Sales | Sales playbooks, proposals, outbound sequences, Salesforce setup |
| 💰 Finance & Legal | Financial models, contract review, tax planning, bookkeeping |
| ⚙️ Operations | HR onboarding, support systems, recruitment, technical docs |
| 🌏 China & Asia | WeChat strategy, Douyin, Baidu SEO, Xiaohongshu, Korea entry |
| 🎮 Game Dev | Game design, audio direction, level design |
| 🚀 Cross-domain | Launch a startup, raise funding, respond to a breach, enter new markets |

---

## All 178 Skills

<details>
<summary>Orchestration (9)</summary>

`director` `techlead` `datalead` `qalead` `productlead` `marketinglead` `saleslead` `financelead` `opslead`

</details>

<details>
<summary>Engineering (35)</summary>

`software-architect` `senior-developer` `frontend-developer` `backend-architect` `mobile-app-builder` `rapid-prototyper` `code-reviewer` `minimal-change-engineer` `codebase-onboarding-engineer` `git-workflow-master` `devops-automator` `infrastructure-maintainer` `sre-site-reliability-engineer` `security-engineer` `mcp-builder` `cms-developer` `embedded-firmware-engineer` `terminal-integration-specialist` `lsp-index-engineer` `visionos-spatial-engineer` `macos-spatial-metal-engineer` `xr-immersive-developer` `xr-interface-architect` `xr-cockpit-interaction-specialist` `solidity-smart-contract-engineer` `wechat-mini-program-developer` `feishu-integration-developer` `voice-ai-integration-engineer` `workflow-architect` `workflow-optimizer` `tool-evaluator` `developer-advocate` `technical-writer` `automation-governance-architect` `autonomous-optimization-architect`

</details>

<details>
<summary>Data & AI (14)</summary>

`ai-engineer` `data-engineer` `database-optimizer` `pipeline-analyst` `model-qa-specialist` `experiment-tracker` `identity-graph-operator` `data-consolidation-agent` `ai-data-remediation-engineer` `analytics-reporter` `agentic-identity-trust-architect` `zk-steward` `search-query-analyst` `agentic-search-optimizer`

</details>

<details>
<summary>QA & Security (14)</summary>

`api-tester` `performance-benchmarker` `test-results-analyzer` `threat-detection-engineer` `blockchain-security-auditor` `incident-response-commander` `compliance-auditor` `accessibility-auditor` `reality-checker` `evidence-collector` `tracking-measurement-specialist` `ai-citation-strategist` `inclusive-visuals-specialist` `filament-optimization-specialist`

</details>

<details>
<summary>Product & Design (22)</summary>

`product-manager` `ux-architect` `ux-researcher` `ui-designer` `rapid-prototyper` `sprint-prioritizer` `jira-workflow-steward` `project-shepherd` `senior-project-manager` `chief-of-staff` `discovery-coach` `feedback-synthesizer` `game-designer` `level-designer` `narrative-designer` `game-audio-engineer` `technical-artist` `visual-storyteller` `image-prompt-engineer` `document-generator` `executive-summary-generator` `report-distribution-agent`

</details>

<details>
<summary>Marketing & Growth (37)</summary>

`content-creator` `social-media-strategist` `seo-specialist` `brand-guardian` `growth-hacker` `email-intelligence-engineer` `linkedin-content-creator` `twitter-engager` `instagram-curator` `reddit-community-builder` `tiktok-strategist` `douyin-strategist` `kuaishou-strategist` `bilibili-content-strategist` `weibo-strategist` `xiaohongshu-specialist` `zhihu-strategist` `wechat-official-account-manager` `baidu-seo-specialist` `china-market-localization-strategist` `china-e-commerce-operator` `cross-border-e-commerce-specialist` `private-domain-operator` `livestream-commerce-coach` `app-store-optimizer` `video-optimization-specialist` `short-video-editing-coach` `podcast-strategist` `carousel-growth-engine` `behavioral-nudge-engine` `trend-researcher` `cultural-intelligence-strategist` `korean-business-navigator` `french-consulting-market-navigator` `healthcare-marketing-compliance-specialist` `whimsy-injector` `narratologist`

</details>

<details>
<summary>Paid Media (7)</summary>

`paid-media-auditor` `paid-social-strategist` `ppc-campaign-strategist` `programmatic-display-buyer` `ad-creative-strategist` `account-strategist` `government-digital-presales-consultant`

</details>

<details>
<summary>Sales & BD (13)</summary>

`sales-coach` `deal-strategist` `outbound-strategist` `proposal-strategist` `sales-engineer` `salesforce-architect` `sales-outreach` `sales-data-extraction-agent` `pipeline-analyst` `discovery-coach` `language-translator` `book-co-author` `studio-producer`

</details>

<details>
<summary>Finance & Legal (13)</summary>

`financial-analyst` `fp-a-analyst` `finance-tracker` `bookkeeper-controller` `accounts-payable-agent` `investment-researcher` `tax-strategist` `loan-officer-assistant` `legal-document-review` `legal-compliance-checker` `legal-client-intake` `legal-billing-time-tracking` `compliance-auditor`

</details>

<details>
<summary>Operations & Specialized (20)</summary>

`customer-service` `support-responder` `retail-customer-returns` `healthcare-customer-service` `hospitality-guest-services` `hr-onboarding` `recruitment-specialist` `corporate-training-designer` `real-estate-buyer-seller` `supply-chain-strategist` `studio-operations` `study-abroad-advisor` `civil-engineer` `geographer` `historian` `anthropologist` `psychologist` `narratologist` `government-digital-presales-consultant` `agents-orchestrator`

</details>

---

## Credits

- Original 169 agents: [agency-agents](https://github.com/msitarzewski/agency-agents) by [@msitarzewski](https://github.com/msitarzewski) — MIT
- Orchestration hierarchy: [develop-skills](https://github.com/javalenciacai/develop-skills) by [@javalenciacai](https://github.com/javalenciacai)
- This fork: [agency-master](https://github.com/javalenciacai/agency-master) by [@javalenciacai](https://github.com/javalenciacai)
