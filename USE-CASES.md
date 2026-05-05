# Use Cases — agency-master

Real-world examples showing how to use the Director and individual skills. Start with the [Quick Examples](#quick-examples) or jump to your domain.

---

## Table of Contents

- [How to activate a skill](#how-to-activate-a-skill)
- [Quick Examples](#quick-examples)
- [🛠 Engineering](#-engineering)
- [📊 Data & AI](#-data--ai)
- [🔍 QA & Security](#-qa--security)
- [🎨 Product & Design](#-product--design)
- [📣 Marketing & Growth](#-marketing--growth)
- [💼 Sales & Business Development](#-sales--business-development)
- [💰 Finance & Legal](#-finance--legal)
- [⚙️ Operations & Specialized](#%EF%B8%8F-operations--specialized)
- [🌏 China & Asia Market](#-china--asia-market)
- [🎮 Game Development](#-game-development)
- [🚀 Cross-Domain (Multi-Lead)](#-cross-domain-multi-lead)

---

## How to activate a skill

In **Claude Code**: `@<skill-name>`  
In **GitHub Copilot**: `@<skill-name>`  
In **OpenCode**: `@<skill-name>`  
In **Antigravity**: skills activate automatically based on context

For multi-step tasks, activate `@director` and just describe what you need — it will route automatically.

---

## Quick Examples

| You say | Director routes to |
|---|---|
| `"Build a REST API for user authentication"` | TechLead → `backend-architect` + `security-engineer` |
| `"Write 5 LinkedIn posts about our launch"` | MarketingLead → `linkedin-content-creator` |
| `"Review this contract before we sign"` | FinanceLead → `legal-document-review` + `compliance-auditor` |
| `"Build a TikTok growth strategy"` | MarketingLead → `tiktok-strategist` + `short-video-editing-coach` |
| `"Model our 18-month financial runway"` | FinanceLead → `fp-a-analyst` + `financial-analyst` |
| `"Find security vulnerabilities in this codebase"` | QALead → `security-engineer` + `threat-detection-engineer` |
| `"Help me close this deal"` | SalesLead → `deal-strategist` + `proposal-strategist` |
| `"We want to launch in Korea"` | Multiple leads → `korean-business-navigator` + `account-strategist` |

---

## 🛠 Engineering

### Build a full-stack web app
**Prompt:** `"Build a SaaS app with Next.js frontend, Node.js API, and PostgreSQL. Include auth and payments."`  
**Route:** `director` → `techlead` → `software-architect` → `frontend-developer` + `backend-architect` + `database-optimizer`

### Ship a mobile app (iOS + Android)
**Prompt:** `"Create a React Native fitness tracker with offline sync and push notifications"`  
**Route:** `techlead` → `mobile-app-builder` + `backend-architect`

### Onboard to a new codebase
**Prompt:** `"I just joined this project. Walk me through the architecture and key files."`  
**Skill:** `codebase-onboarding-engineer`

### Set up CI/CD pipeline
**Prompt:** `"Set up GitHub Actions for our Node.js app: lint, test, Docker build, deploy to ECS"`  
**Skill:** `devops-automator`

### Code review before merging
**Prompt:** `"Review this PR for security issues, performance regressions, and style violations"`  
**Skill:** `code-reviewer`

### Build an MCP server
**Prompt:** `"Create an MCP server that connects to our internal Notion workspace"`  
**Skill:** `mcp-builder`

### Fix a production incident
**Prompt:** `"We have a P0 — memory leak in prod, 503s spiking. Help me triage and resolve."`  
**Skill:** `incident-response-commander` + `sre-site-reliability-engineer`

### Embed firmware for IoT device
**Prompt:** `"Write firmware in C for an STM32 sensor that reads temperature and sends via UART"`  
**Skill:** `embedded-firmware-engineer`

### Build a visionOS app
**Prompt:** `"Create an immersive visionOS product viewer in SwiftUI with RealityKit"`  
**Skill:** `visionos-spatial-engineer` + `macos-spatial-metal-engineer`

---

## 📊 Data & AI

### Build a data pipeline
**Prompt:** `"Build an ETL pipeline: Postgres → S3 → Snowflake, scheduled daily with failure alerts"`  
**Route:** `datalead` → `data-engineer` + `pipeline-analyst`

### Train and deploy an ML model
**Prompt:** `"Train a churn prediction model on our customer data and deploy it as a REST API"`  
**Route:** `datalead` → `ai-engineer` + `model-qa-specialist` + `experiment-tracker`

### Build a RAG system
**Prompt:** `"Set up RAG over our internal docs using LlamaIndex + Pinecone + Claude"`  
**Skill:** `ai-engineer`

### Fix messy data quality issues
**Prompt:** `"Our CRM has 40% duplicate records and inconsistent phone formats. Clean it up."`  
**Skill:** `ai-data-remediation-engineer` + `data-consolidation-agent`

### Analytics dashboard
**Prompt:** `"Build a weekly dashboard: revenue, churn, CAC, LTV — pull from our data warehouse"`  
**Skill:** `analytics-reporter` + `database-optimizer`

### Set up identity resolution
**Prompt:** `"We have users across 3 systems with different IDs. Build a unified identity graph."`  
**Skill:** `identity-graph-operator`

---

## 🔍 QA & Security

### Full test plan for a release
**Prompt:** `"We're launching v2.0 next week. Write a complete test plan: unit, integration, E2E, regression"`  
**Route:** `qalead` → `api-tester` + `performance-benchmarker` + `test-results-analyzer`

### Security audit
**Prompt:** `"Audit our infrastructure and API for OWASP Top 10 vulnerabilities"`  
**Skill:** `security-engineer` + `threat-detection-engineer`

### Accessibility review
**Prompt:** `"Review our web app for WCAG 2.2 AA compliance"`  
**Skill:** `accessibility-auditor`

### Smart contract audit
**Prompt:** `"Audit this Solidity token contract for reentrancy, overflow, and access control issues"`  
**Skill:** `blockchain-security-auditor` + `solidity-smart-contract-engineer`

### Performance benchmarking
**Prompt:** `"Our API P99 latency is 800ms. Find the bottleneck and optimize to under 200ms"`  
**Skill:** `performance-benchmarker` + `database-optimizer`

---

## 🎨 Product & Design

### Write a PRD
**Prompt:** `"Write a Product Requirements Document for a B2B invoicing feature"`  
**Route:** `productlead` → `product-manager` + `ux-researcher`

### Design a user flow
**Prompt:** `"Design the end-to-end user flow for onboarding a new enterprise customer"`  
**Skill:** `ux-architect` + `ui-designer`

### Sprint planning
**Prompt:** `"We have 47 tickets in backlog. Help us prioritize for a 2-week sprint given our OKRs"`  
**Skill:** `sprint-prioritizer` + `jira-workflow-steward`

### Run a discovery session
**Prompt:** `"Facilitate a discovery session to understand why users drop off at step 3"`  
**Skill:** `discovery-coach` + `ux-researcher`

### Rapid prototype
**Prompt:** `"Build a clickable prototype for our new checkout flow in 2 hours"`  
**Skill:** `rapid-prototyper`

### Manage a complex project
**Prompt:** `"We have 3 teams, 12 people, 90-day deadline. Set up the project structure and tracking"`  
**Skill:** `senior-project-manager` + `project-shepherd` + `chief-of-staff`

---

## 📣 Marketing & Growth

### Social media content calendar
**Prompt:** `"Create a 30-day content calendar for LinkedIn, Twitter, and Instagram for a B2B SaaS product"`  
**Route:** `marketinglead` → `linkedin-content-creator` + `twitter-engager` + `instagram-curator` + `content-creator`

### SEO strategy
**Prompt:** `"We're launching a new blog. Build a 6-month SEO strategy targeting mid-funnel SaaS buyers"`  
**Skill:** `seo-specialist` + `agentic-search-optimizer` + `content-creator`

### Paid media audit
**Prompt:** `"Audit our Google Ads account. CPA is $280, we need to get it under $150"`  
**Skill:** `paid-media-auditor` + `ppc-campaign-strategist`

### Growth hacking experiment
**Prompt:** `"Design 5 growth experiments we can run this quarter to increase signups by 30%"`  
**Skill:** `growth-hacker` + `behavioral-nudge-engine` + `experiment-tracker`

### Product launch campaign
**Prompt:** `"Plan the full launch campaign for our new AI feature: messaging, channels, timeline"`  
**Route:** `marketinglead` → `brand-guardian` + `content-creator` + `social-media-strategist` + `email-intelligence-engineer`

### Podcast strategy
**Prompt:** `"We want to start a B2B podcast. Define format, topics, distribution, and guest strategy"`  
**Skill:** `podcast-strategist`

### Short-form video content
**Prompt:** `"Create a TikTok + Reels content strategy for our consumer app launch"`  
**Skill:** `tiktok-strategist` + `short-video-editing-coach` + `video-optimization-specialist`

---

## 💼 Sales & Business Development

### Build a sales playbook
**Prompt:** `"Create a sales playbook for our enterprise SaaS: ICP, discovery questions, objection handling, closing"`  
**Route:** `saleslead` → `sales-coach` + `deal-strategist` + `discovery-coach`

### Write a proposal
**Prompt:** `"Write a proposal for a $250K enterprise deal with a logistics company"`  
**Skill:** `proposal-strategist`

### Outbound prospecting campaign
**Prompt:** `"Build a 5-step outbound sequence for CFOs at mid-market manufacturing companies"`  
**Skill:** `outbound-strategist` + `email-intelligence-engineer`

### Salesforce setup
**Prompt:** `"Set up our Salesforce pipeline stages, custom fields, and automation rules for an SMB sales motion"`  
**Skill:** `salesforce-architect`

### Extract insights from sales calls
**Prompt:** `"Analyze these 20 call transcripts. What are the top 5 objections and what closes deals?"`  
**Skill:** `sales-data-extraction-agent` + `pipeline-analyst`

### Market entry strategy
**Prompt:** `"We're entering the French enterprise market. What's our GTM strategy?"`  
**Skill:** `french-consulting-market-navigator` + `account-strategist`

---

## 💰 Finance & Legal

### Build a financial model
**Prompt:** `"Build a 3-year P&L forecast with revenue scenarios, burn rate, and break-even analysis"`  
**Route:** `financelead` → `fp-a-analyst` + `financial-analyst`

### Review a contract
**Prompt:** `"Review this SaaS vendor agreement. Flag risky clauses, liability exposure, and auto-renewal terms"`  
**Skill:** `legal-document-review` + `legal-compliance-checker`

### Tax planning
**Prompt:** `"We're a US-incorporated startup with revenue in 6 countries. Plan our international tax structure"`  
**Skill:** `tax-strategist`

### Investment research
**Prompt:** `"Research Series A SaaS comps: median ARR, multiples, and growth rates for 2023-2024"`  
**Skill:** `investment-researcher`

### Set up bookkeeping
**Prompt:** `"We're 12 months old, $800K ARR, no real accounting system. Set up chart of accounts and categorize transactions"`  
**Skill:** `bookkeeper-controller` + `accounts-payable-agent`

### Legal intake for a new client
**Prompt:** `"A new enterprise client wants a custom contract. Run the intake and identify all legal requirements"`  
**Skill:** `legal-client-intake` + `legal-billing-time-tracking`

---

## ⚙️ Operations & Specialized

### Set up HR onboarding
**Prompt:** `"Create a 30-60-90 day onboarding plan for a new senior engineer"`  
**Skill:** `hr-onboarding` + `corporate-training-designer`

### Customer support system
**Prompt:** `"Design our support playbook: ticket routing, escalation paths, SLA targets, canned responses"`  
**Skill:** `support-responder` + `customer-service` + `feedback-synthesizer`

### Supply chain optimization
**Prompt:** `"Our COGS is too high. Analyze our supplier list and suggest consolidation and negotiation strategies"`  
**Skill:** `supply-chain-strategist`

### Real estate analysis
**Prompt:** `"Analyze these 3 commercial properties for lease vs buy for our new office"`  
**Skill:** `real-estate-buyer-seller`

### Healthcare communication
**Prompt:** `"Write HIPAA-compliant patient communication templates for appointment reminders and lab results"`  
**Skill:** `healthcare-customer-service` + `compliance-auditor`

### Recruitment pipeline
**Prompt:** `"We need to hire 5 engineers in 60 days. Build the sourcing strategy and interview process"`  
**Skill:** `recruitment-specialist`

### Technical documentation
**Prompt:** `"Write developer docs for our API: authentication, rate limits, endpoints, code examples in 3 languages"`  
**Skill:** `technical-writer` + `developer-advocate`

---

## 🌏 China & Asia Market

### Enter the Chinese market
**Prompt:** `"We want to launch our SaaS in China. What's the strategy — entity, platforms, localization?"`  
**Route:** `marketinglead` + `saleslead` → `china-market-localization-strategist` + `china-e-commerce-operator` + `cross-border-e-commerce-specialist`

### WeChat content strategy
**Prompt:** `"Plan 3 months of WeChat Official Account content for a B2B software company"`  
**Skill:** `wechat-official-account-manager` + `private-domain-operator`

### Douyin / TikTok China
**Prompt:** `"Build a Douyin content strategy for a consumer electronics brand"`  
**Skill:** `douyin-strategist` + `livestream-commerce-coach` + `short-video-editing-coach`

### Baidu SEO
**Prompt:** `"Our Baidu rankings are low. Audit our site and create a 90-day SEO plan for China"`  
**Skill:** `baidu-seo-specialist`

### Xiaohongshu (RED) growth
**Prompt:** `"Create a Xiaohongshu KOL strategy for our skincare brand targeting Gen Z women in China"`  
**Skill:** `xiaohongshu-specialist` + `image-prompt-engineer`

### Korea market entry
**Prompt:** `"Evaluate entering the Korean enterprise market: regulations, local partners, sales approach"`  
**Skill:** `korean-business-navigator`

---

## 🎮 Game Development

### Design a game concept
**Prompt:** `"Design a mobile roguelite with unique meta-progression. Include core loop, monetization, and retention hooks"`  
**Skill:** `game-designer` + `narrative-designer` + `level-designer`

### Game audio direction
**Prompt:** `"Design the audio identity for a dark fantasy RPG: music style, SFX library, adaptive music system"`  
**Skill:** `game-audio-engineer`

### 3D printing optimization
**Prompt:** `"Optimize print settings for PETG at high speed: temperature, retraction, cooling profile"`  
**Skill:** `filament-optimization-specialist`

---

## 🚀 Cross-Domain (Multi-Lead)

These are the most powerful use cases — Director delegates to multiple leads simultaneously.

### Launch a startup
**Prompt:** `"We're launching a B2B SaaS in 90 days. Cover everything: MVP, go-to-market, legal entity, funding pitch"`

```
director
├── techlead      → software-architect + rapid-prototyper + devops-automator
├── productlead   → product-manager + ux-architect
├── marketinglead → content-creator + seo-specialist + social-media-strategist
├── saleslead     → outbound-strategist + proposal-strategist
└── financelead   → fp-a-analyst + legal-document-review
```

### Hire and scale a team
**Prompt:** `"We're growing from 5 to 20 people in 6 months. Handle recruiting, onboarding, and HR systems"`

```
director
├── opslead  → recruitment-specialist + hr-onboarding + corporate-training-designer
└── techlead → devops-automator (access provisioning)
```

### Respond to a security breach
**Prompt:** `"We have a potential data breach. Customer data may be exposed. What do we do right now?"`

```
director
├── qalead      → incident-response-commander + threat-detection-engineer + security-engineer
├── opslead     → customer-service (user notification) + support-responder
└── financelead → legal-compliance-checker (breach notification laws) + legal-document-review
```

### Enter a new international market
**Prompt:** `"We want to expand to Japan and Brazil simultaneously. Build the full market entry plan"`

```
director
├── saleslead     → account-strategist + deal-strategist
├── marketinglead → cultural-intelligence-strategist + language-translator + social-media-strategist
├── financelead   → tax-strategist + legal-compliance-checker
└── opslead       → supply-chain-strategist + hr-onboarding
```

### Build and ship an AI product
**Prompt:** `"Build an AI-powered customer support tool: train on our docs, integrate with Zendesk, launch in 6 weeks"`

```
director
├── techlead    → ai-engineer + backend-architect + mcp-builder
├── datalead    → data-engineer + model-qa-specialist + experiment-tracker
├── qalead      → api-tester + performance-benchmarker
├── productlead → product-manager + ux-architect
└── opslead     → support-responder (training data from existing tickets)
```

### Raise a funding round
**Prompt:** `"Prepare everything for our Series A: deck, data room, financial model, investor outreach"`

```
director
├── financelead   → fp-a-analyst + financial-analyst + investment-researcher
├── productlead   → product-manager (roadmap narrative)
├── marketinglead → visual-storyteller + brand-guardian
└── saleslead     → proposal-strategist + deal-strategist
```

---

> **Tip:** You can activate any skill directly (e.g. `@seo-specialist`) without going through the Director — useful when you already know exactly what you need.

> **Install:** `npx skills add javalenciacai/agency-master`
