# Microsoft Build 2026 — Personal Agenda

**Attendee**: Sinan Nar — Senior Software Engineer & Consultant @ ARINCO  
**Event**: June 2–3, 2026 | San Francisco, CA (PDT, UTC-7)  
**Viewing from**: New Zealand (NZST, UTC+12) — times shown in NZST

> ⏰ **Timezone note**: SF sessions on Jun 2 PDT land on **Jun 3 NZST morning**; Jun 3 PDT sessions land on **Jun 4 NZST**. All times below are NZST.

---

## Schedule Overview

### 📅 Day 1 — Tuesday 3 June (NZST)

*Conference Day 1 — Monday 2 June PDT*

| NZST | PDT | Code | Session | Type | Level |
|------|-----|------|---------|------|-------|
| 8:50 AM | 1:50 PM | [LTG453](2026-06-03/LTG453.md) | Building an End-to-End Enterprise AI Platform on Azure | Lightning Talk | 300 |
| 9:10 AM | 2:10 PM | [LTGSP481](2026-06-03/LTGSP481.md) | Build reliable coding agents with .NET and durable workflows | Lightning Talk | 400 |
| 9:30 AM | 2:30 PM | [BRK223](2026-06-03/BRK223.md) | From rows to reasoning: Designing databases for AI apps and agents | Breakout | 300 |
| 10:00 AM | 3:00 PM | [LAB511](2026-06-03/LAB511.md) | 🧪 Create advanced Postgres-powered agentic apps with Azure HorizonDB | **Lab** | 300 |
| 11:30 AM | 4:30 PM | [DEM310](2026-06-03/DEM310.md) | Ship code faster with AI-powered NoSQL schema design | Demo | 200 |

> 📝 **Schedule change**: LAB511 (75 min hands-on) replaces BRK241 in the Day 1 schedule. BRK241 moved to on-demand — the lab's hands-on PostgreSQL/AI experience is more valuable than a passive breakout for your stack.

### 📅 Day 2 — Wednesday 4 June (NZST)

*Conference Day 2 — Tuesday 3 June PDT*

#### 🌅 Early Block (optional — requires early start)

| NZST | PDT | Code | Session | Type | Level |
|------|-----|------|---------|------|-------|
| 4:30 AM | 9:30 AM | [LTG466](2026-06-04/LTG466.md) | Building your own MCP server | Lightning Talk | 100 |
| 5:30 AM | 10:30 AM | [DEM305](2026-06-04/DEM305.md) | GitHub Copilot Anywhere: From CLIs to Cloud Execution | Demo | 300 |
| 6:30 AM | 11:30 AM | [BRK243](2026-06-04/BRK243.md) | Claw and agent harness in Microsoft Foundry | Breakout | 400 |

#### ☀️ Main Block

| NZST | PDT | Code | Session | Type | Level |
|------|-----|------|---------|------|-------|
| 9:45 AM | 2:45 PM | [BRK205](2026-06-04/BRK205.md) | Aspire for agents: Transform how you build and deploy distributed apps | Breakout | 200 |
| 10:30 AM | 3:30 PM | [DEM361](2026-06-04/DEM361.md) | Understand and fix Agent Framework apps with observability and evals | Demo | 300 |
| 11:00 AM | 4:00 PM | [BRK207](2026-06-04/BRK207.md) | GitHub Copilot in Visual Studio: Agents That Debug, Profile, and Test | Breakout | 300 |
| 11:45 AM | 4:45 PM | [LAB530-R1](2026-06-04/LAB530-R1.md) | 🧪 Engineering agents that reason, act, and adapt | **Lab** | 300 |

> 📝 **Bonus lab**: LAB530-R1 starts right after BRK207 ends — perfect finish to Day 2 with 75 min of hands-on Foundry Agent Service + MCP tools.

---

## ⚠️ Conflicts — Watch On-Demand

These sessions conflict with higher-priority picks but are still highly relevant:

| Code | Title | Conflicts With | Why Watch Later |
|------|-------|----------------|-----------------|
| BRK241 | From prototype to production: build and run agents at scale | LAB511 | Agent Framework lifecycle (replaced by hands-on lab) |
| LTG455 | From Code to Agents: Build Production MCP Servers on Azure Functions | BRK223 (5 min overlap) | MCP + Azure Functions + Azure DevOps CI/CD |
| DEM333 | How Foundry integrates with open-source frameworks and tools | LAB511 | Agent Framework + LangGraph + MCP + A2A |
| BRK221 | Idea to production-ready agent in seconds on AI-native runtime | BRK205 | Azure Container Apps for agentic workloads |
| DEM301 | Rethinking CI: Actions, AI Agents, and the End of Commit-Fail-Commit | BRK205 | GitHub Actions + AI agents + MCP |
| BRK224 | PepsiCo's blueprint for agentic AI | BRK205 | Azure SQL + Cosmos DB + PostgreSQL data layer |
| TT656 | From Locked-In to Liquid: Modernizing .NET Before November 2026 EOL | LAB511 | .NET 8/9 EOL migration strategies |
| BRK250 | Govern open-source AI agents, any framework, any scale | BRK223 | Enterprise agent governance |

## 🧪 Other Labs Worth Considering (Digital/On-Demand)

| Code | Title | Why |
|------|-------|-----|
| LAB502 / LAB502D | Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows | Build custom Copilot agents + MCP + Agent Skills (GitHub partner gold) |
| LAB501 / LAB501D | From zero to deployed on Azure with AI agents | GitHub Copilot CLI + Azure deployment workflow |
| LAB540 / LAB540D | Observe, optimize and protect your hosted agents in Microsoft Foundry | Agent observability, evaluations, red teaming |
| LAB511D | Digital Lab: HorizonDB (same as LAB511) | Backup if you miss the in-person slot |
| LAB530D | Digital Lab: Engineering agents (same as LAB530) | Backup if you miss the in-person slot |

---

## 🎯 Focus Themes

1. **Microsoft Agent Framework + Aspire** — The new distributed AI app story
2. **Azure Data for AI** — Cosmos DB, SQL, HorizonDB (PostgreSQL) + vector search
3. **GitHub Platform Evolution** — Copilot agents, Actions for AI, MCP integration
4. **MCP Servers in C#** — The new integration standard on your stack
5. **Observability for Agents** — OpenTelemetry, evals, debugging agentic apps

---

## 📌 Key Takeaway Sessions by Role

| As a... | Priority Sessions |
|---------|-------------------|
| .NET Consultant | BRK205, BRK243, LTGSP481, BRK207 |
| Azure User Group Organiser | BRK223, BRK241, LTG453 |
| AI/Agent Builder | BRK241, BRK243, DEM361, LTG466 |
| GitHub Partner | DEM305, BRK207, DEM301 (on-demand) |
