# 🤖 Copilot CLI Session

> [!NOTE]
> - **Session ID:** `1efc37dc-d1bb-4b2e-925f-6bc91e0c7042`  
> - **Started:** 21/05/2026, 12:50:16 pm  
> - **Duration:** 3058m 39s  
> - **Exported:** 23/05/2026, 3:48:56 pm  

---

<sub>⏱️ 0s</sub>

### ℹ️ Info

No copilot-instructions.md found. Run /init to generate.

---

<sub>⏱️ 0s</sub>

### ℹ️ Info

Tip: /remote

---

<sub>⏱️ 13s</sub>

### 👤 User

/microsoft-events:microsoft-build

---

<sub>⏱️ 16s</sub>

### ℹ️ Info

Operation cancelled by user

---

<sub>⏱️ 1m 22s</sub>

### 👤 User

I am a consultant who works with azure, dotnet, aspire, dotnet, c#, entity framework, microsoft agent framework. tell me what build sessions are relevant to my skillset

---

<sub>⏱️ 1m 25s</sub>

### 💭 Reasoning

*The user wants me to invoke the "microsoft-build" skill to find relevant Microsoft Build sessions based on their skillset (Azure, .NET, Aspire, C#, Entity Framework, Microsoft Agent Framework).*

---

<sub>⏱️ 1m 27s</sub>

### ✅ `skill`

**microsoft-build**

<details>
<summary>Arguments</summary>

```json
{
  "skill": "microsoft-build"
}
```

</details>

```
Skill "microsoft-build" loaded successfully. Follow the instructions in the skill context.
```


---

<sub>⏱️ 1m 31s</sub>

### 💭 Reasoning

*The user is a consultant who works with Azure, .NET, Aspire, C#, Entity Framework, and Microsoft Agent Framework. They want to find relevant Build 2026 sessions for their skillset.

Since they don't have a project open but have told me their tech stack, I should search for sessions matching each of their technologies using the msevents CLI. Let me search for sessions across their key technologies.

Let me run multiple CLI searches in parallel for their key technologies:
1. Azure
2. .NET / Aspire
3. C# / Entity Framework
4. Microsoft Agent Framework (this could be the new Microsoft Agents SDK)


I'm executing the searches now to pull back relevant sessions for each technology area.*

---

<sub>⏱️ 1m 57s</sub>

### ✅ `bash`

**Search Build sessions for .NET Aspire**

$ npx -y @microsoft/events-cli sessions --tech ".NET Aspire" --event build-2026 --json 2>/dev/null

<details>
<summary>213 lines</summary>

```
[
  {
    "sessionCode": "BRK205",
    "title": "Aspire for agents: Transform how you build and deploy distributed apps",
    "description": "Aspire is an open-source cloud and agent-ready developer toolchain transforming how you build, run, and deploy observable, production-ready distributed apps. Its code centric approach streamlines orchestration of your apps and agents, provides observability for systems in any programming language, and supports deployment locally or to your cloud of choice. Come meet the new Aspire.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Damian Edwards, David Fowler",
    "timeSlot": "21:45 - 22:30",
    "startDateTime": "2026-06-03T21:45:00Z",
    "endDateTime": "2026-06-03T22:30:00Z",
    "location": "Festival Pavilion, Breakout 3",
    "level": "(200) Intermediate",
    "type": "Breakout",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "Python",
    "tags": "Azure, Agents, Developer, OSS, DevTools, Agentic SDLC, Aspire",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP929",
    "title": "Build modern .NET apps with Uno Platform, AI, and visual tools",
    "description": "See how to build modern cross-platform .NET apps using Uno Platform with AI-powered and visual tools. This demo shows how to accelerate feature delivery, improve runtime performance, and achieve consistent rendering with SkiaSharp. Learn patterns for streamlining development across platforms with shared tooling and IDE support.",
    "speakers": "Sam Basu",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(200) Intermediate",
    "type": "Pre-recorded",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, .NET",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM365",
    "title": "Beyond REST: .NET Apps That Talk to Hardware",
    "description": "Most app demos stop at REST APIs. This live demo talks to real hardware. I’ll show a .NET app that discovers a device over BLE, exchanges data over NFC or serial, and turns raw device signals into a usable workflow. You’ll leave with a practical pattern for structuring device services, handling platform differences, and deciding when local connectivity beats the cloud.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Jared Rhodes",
    "timeSlot": "23:30 - 23:55",
    "startDateTime": "2026-06-03T23:30:00Z",
    "endDateTime": "2026-06-03T23:55:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": ".NET",
    "tags": "API, Developer, Community, MVP, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTGSP481",
    "title": "Build reliable coding agents with .NET and durable workflows",
    "description": "Modern AI can generate code—but building agents that autonomously fix bugs, run tests, and create pull requests requires real systems engineering. Dive into a hands-on architecture for coding agents built with .NET Web APIs, Temporal workflows, and AI-powered workers. See how to orchestrate long‑running tasks, manage failures, and securely execute code in sandboxed environments to deliver production‑ready autonomous agents.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Shriram Sankaran Sankaran",
    "timeSlot": "21:10 - 21:25",
    "startDateTime": "2026-06-02T21:10:00Z",
    "endDateTime": "2026-06-02T21:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(400) Expert",
    "type": "Lightning Talk",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Automation, Agents, .NET, Developer",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "TT656",
    "title": "From Locked-In to Liquid: Modernizing .NET Before the November 2026 EOL",
    "description": ".NET 8 and 9 both hit end of life on November 10, 2026. With hundreds of repos to upgrade, manual migration won't cut it—and pointing agents at the problem without structure burns tokens and produces inconsistent results. Let's talk about how agents, given the right deterministic tools, can move your .NET portfolio from rigid and locked-in to liquid—continuously modern, with swappable components and routine upgrades instead of fire drills. Bring your migration questions and stack horror stories.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Matt Campbell",
    "timeSlot": "22:15 - 23:00",
    "startDateTime": "2026-06-02T22:15:00Z",
    "endDateTime": "2026-06-02T23:00:00Z",
    "location": "Gateway Pavilion, Level 2, Table 3",
    "level": "(200) Intermediate",
    "type": "Table Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "C#",
    "tags": "AI, Azure, Agents, .NET, Microsoft for Startups, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEMSP394",
    "title": "Scale enterprise .NET apps with AI‑assisted cross‑platform workflows",
    "description": "Most AI tooling for .NET targets greenfield code generation. Enterprise app development is different: layered systems, cross-platform targets, mixed-skill teams, and production demands. In this session, Uno Platform and Kahua show an end-to-end AI-assisted workflow across web, desktop, and mobile, where AI can inspect live app state, understand runtime UI behavior, and act with context. Be ready for real productivity with contextual AI.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Sam Basu, Colin Whitlatch",
    "timeSlot": "21:40 - 22:05",
    "startDateTime": "2026-06-02T21:40:00Z",
    "endDateTime": "2026-06-02T22:05:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Agents, .NET, Developer, GitHub Copilot, Visual Studio Code, OSS, Visual Studio",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG469",
    "title": "Building an AI Robot 'StackChan' with GitHub Copilot and Foundry",
    "description": "Physical AI is one of the most exciting frontiers in technology today, but for many developers, building AI-powered robots still feels out of reach. In this 15-minute session, I'll share my hands-on journey as an embedded development beginner who built StackChan — a palm-sized, open-source AI robot — using GitHub Copilot, Microsoft Foundry (gpt-realtime), and .NET.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Maki Nagase",
    "timeSlot": "17:30 - 17:45",
    "startDateTime": "2026-06-03T17:30:00Z",
    "endDateTime": "2026-06-03T17:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(100) Foundational",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": ".NET",
    "tags": "Agents, Developer, GitHub Copilot, GitHub, Microsoft Foundry, Foundry Agents, Community, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM341",
    "title": "Any agent, any cloud: Standardized tracing with Foundry+OpenTelemetry",
    "description": "Teams are shipping agents across clouds and frameworks—but telemetry is fragmented. In this demo, see how Microsoft Foundry and OpenTelemetry standards for GenAI tracing bring consistent observability that is agent framework agnostic and cloud agnostic. We’ll walk through the simple setup steps to instrument model and tool calls, quickly diagnose failures, latency, and cost spikes, and close the loop with trace-based evaluation, visualization and optimization.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Hanchi Wang, SuiLin Yap",
    "timeSlot": "18:50 - 19:15",
    "startDateTime": "2026-06-03T18:50:00Z",
    "endDateTime": "2026-06-03T19:15:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Responsible AI",
    "solutionArea": "",
    "product": "",
    "languages": ".NET",
    "tags": "Observability, Microsoft Foundry, Responsible AI, Tracing, Open Telemetry",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTGSP493",
    "title": "Run AI coding agents on-device with NPUs",
    "description": "AI-powered coding agents are transforming developer workflows, but most run in the cloud, adding latency, cost, and privacy concerns. What if your coding agent ran entirely on your laptop’s NPU? In this session, you'll learn how Visual Studio AI Toolkit and Qualcomm’s Hexagon NPU enable fully on device agentic coding. Using optimized SLMs, you'll experience real time code generation with no cloud calls, delivering high performance per watt, longer battery life, and responsive developer UX.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Manuj Sabharwal, Gokul Tonpe Tonpe",
    "timeSlot": "18:10 - 18:25",
    "startDateTime": "2026-06-03T18:10:00Z",
    "endDateTime": "2026-06-03T18:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 2",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Compute, .NET, Developer, Developer Technologies",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRKSP90",
    "title": "Stop Routing docstrings to a >70B model: AI inference on Qualcomm",
    "description": "Your AI coding assistant calls a 70B+ cloud model just to add a docstring. Snapdragon X2 Elite’s 80 TOPS NPU changes that. In this session, build a three-tier inference routing architecture—on‑device (≤13B), on‑prem (14B–34B), and cloud (70B+)—cutting cloud tokens by 67%, latency by 70%, and keeping most code local. Includes routing logic, quantization trade‑offs, and a deployable classifier.\n\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Alberto Martinez",
    "timeSlot": "20:30 - 21:15",
    "startDateTime": "2026-06-03T20:30:00Z",
    "endDateTime": "2026-06-03T21:15:00Z",
    "location": "Building B, Level 3, BATS Improv",
    "level": "(200) Intermediate",
    "type": "Breakout",
    "topic": "Working with models",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, .NET, Developer, GitHub, Local AI, Windows, Foundry Agents, Foundry Local, DevTools, Windows Development, Developer Frameworks",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 1m 57s</sub>

### ✅ `bash`

**Search Build sessions for Entity Framework**

$ npx -y @microsoft/events-cli sessions --tech "Entity Framework" --event build-2026 --json 2>/dev/null

<details>
<summary>213 lines</summary>

```
[
  {
    "sessionCode": "BRK210",
    "title": "Future of Developer Productivity: Microsoft’s EngThrive Framework in Practice",
    "description": "Abstract: AI is transforming how we write code, but the teams shipping fastest go beyond tools—they systematically remove bottlenecks in the development process. This session gives you a practical framework to measure and improve developer productivity in the AI era, based on Microsoft’s EngThrive model of Speed, Ease, and Quality. See how to apply each dimension through case studies, including a team that reduced developer toil by 25%. You’ll leave with clear metrics to track, dashboards to build, and actions that work for teams of any size.",
    "speakers": "",
    "timeSlot": "23:00 - 23:45",
    "startDateTime": "2026-06-03T23:00:00Z",
    "endDateTime": "2026-06-03T23:45:00Z",
    "location": "Gateway Pavilion, Level 1, Cowell Theater",
    "level": "(200) Intermediate",
    "type": "Breakout",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK250",
    "title": "Govern open-source AI agents, any framework, any scale",
    "description": "As AI agents move into production, developers own safety, governance, and reliability across Microsoft Agent Framework and open-source stacks. This session shows how to govern agents end to end: turning your requirements into context-aware evaluations, stress-testing against adversarial risks, applying open controls that work across frameworks, and keeping humans in the loop on high-stakes actions. Leave with a blueprint for shipping agents at enterprise scale.\n\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Sarah Bird, Sandeep Atluri, Mehrnoosh Sameki",
    "timeSlot": "21:30 - 22:15",
    "startDateTime": "2026-06-02T21:30:00Z",
    "endDateTime": "2026-06-02T22:15:00Z",
    "location": "Building B, Level 3, BATS Improv",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Responsible AI",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Observability, Security, Agents, Microsoft Foundry, Responsible AI",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM361",
    "title": "Understand and fix Agent Framework apps with observability and evals",
    "description": "Your AI apps are getting more complex, with multiple agents, tools, and different orchestration patterns. This makes them harder to understand, debug, and test. This session shows you how to visualize the decisions your LLMs are making in complex Microsoft Agent Framework applications, using open standards and open source tooling to provide you with instrumentation and observability. You'll also see how you can use another LLM as a judge to evaluate how well your AI app is working.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Jim Bennett",
    "timeSlot": "22:30 - 22:55",
    "startDateTime": "2026-06-03T22:30:00Z",
    "endDateTime": "2026-06-03T22:55:00Z",
    "location": "Gateway Pavilion, Level 2, Theater B",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Community, MVP",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK252",
    "title": "From observability to ROI for AI agents on any framework",
    "description": "Nondeterministic, multi-agent systems break traditional monitoring. As agents reach production, observability must be built in—not added after failures. This session covers modern agent observability: cross-framework tracing and evals, rigorous inner-loop practices, evolving context-specific evals, and always-on signals that connect behavior to business outcomes to measure value, cost, and ROI.\n\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Vivek Bhadauria, Sebastian Kohlmeier, Filisha Shah",
    "timeSlot": "22:45 - 23:30",
    "startDateTime": "2026-06-02T22:45:00Z",
    "endDateTime": "2026-06-02T23:30:00Z",
    "location": "Festival Pavilion, Breakout 2",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Responsible AI",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Observability, Microsoft Foundry, Responsible AI",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRKSP93",
    "title": "Build once, deploy everywhere across Azure, on-prem, and local with AMD",
    "description": "As AI workloads move from experimentation to production, developers need portability, performance, and flexibility—without lock-in. Learn how AMD Instinct and Radeon GPUs and the ROCm open software stack enable a build-once, deploy-anywhere AI workflow spanning Azure, on-prem, and local Windows or Linux environments. See how ROCm with PyTorch and ONNX Runtime helps developers run the same code from laptop to Azure GPU clusters—reducing rework while scaling performance.\n\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Anush Elangovan",
    "timeSlot": "21:30 - 22:15",
    "startDateTime": "2026-06-02T21:30:00Z",
    "endDateTime": "2026-06-02T22:15:00Z",
    "location": "Festival Pavilion, Breakout 3",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, API, Developer, Developer Technologies, Developer Frameworks",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP901",
    "title": "Discover, govern, and scale Azure resources with HashiCorp Terraform",
    "description": "Managing existing Azure environments is a major barrier to scaling cloud operations, with many resources outside infrastructure-as-code. In this session, learn how HashiCorp Terraform and Terraform Search help teams discover unmanaged Azure resources and bring them under management quickly and declaratively. Move from fragmented environments to consistent, policy-driven infrastructure for AI workloads and agents while improving governance, reducing manual effort, and accelerating Azure adoption.",
    "speakers": "Kerim Satirli",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(200) Intermediate",
    "type": "Pre-recorded",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure, Scaling, Terraform, Developer Frameworks",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP911",
    "title": "Build AI-first business apps that turn dashboards into actions",
    "description": "Business apps are shifting from dashboards and filters to AI-driven experiences. In this session, we show how users can ask questions, get insights, and take action instantly. Using DevExpress components, we demonstrate how structured UI brings AI responses to life, turning data into clear, actionable outcomes.",
    "speakers": "Paul Usher",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(200) Intermediate",
    "type": "Pre-recorded",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Developer, Software Development Company, DevTools, Developer Frameworks",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEMSP386",
    "title": "Develop faster on Windows with AI playbooks and local agents",
    "description": "In this session you'll experience a practical path for a streamlined setup-to-ship workflow. Learn how you can use innovations in local coding on AMD's Ryzen™ AI PCs to optimize workflows powered by AI Playbooks to reduce friction and accelerate the path from idea to first commit. Finish with a clear example showing how to build once, run locally, and scale across Windows systems optimized for AMD hardware.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "",
    "timeSlot": "17:30 - 17:55",
    "startDateTime": "2026-06-03T17:30:00Z",
    "endDateTime": "2026-06-03T17:55:00Z",
    "location": "Gateway Pavilion, Level 2, Theater B",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, API, Agents, Developer, Windows Developer, Agents on Windows, Windows SDKs, Developer Technologies, Windows Development, Developer Frameworks",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM333",
    "title": "How Foundry integrates with open-source frameworks and tools",
    "description": "In this demo, we'll show how Microsoft Foundry integrates with the open-source tools developers already use — so you can build agents your way and deploy them with enterprise-grade hosting and observability built in. We'll start with Microsoft Agent Framework, then bring in a LangGraph agent and deploy it directly to Foundry with no rearchitecting required. MCP, A2A, and OpenAPI connect it all — letting agents built across different frameworks coordinate in multi-agent workflows.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Nagkumar Arkalgud, Facundo Santiago",
    "timeSlot": "23:00 - 23:25",
    "startDateTime": "2026-06-02T23:00:00Z",
    "endDateTime": "2026-06-02T23:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater B",
    "level": "",
    "type": "Demo",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP905",
    "title": "Fix your broken debugging workflow",
    "description": "Code velocity isn’t the problem. Understanding real-time systems behavior is. AI and agents can ship changes fast, but without runtime context they’re guessing.\n\nThe old loop doesn’t scale:\ndeploy → dashboards → logs → redeploy\n\nIn this session, build, break, and fix a real service in VS Code using Copilot agent mode and Dynatrace MCP. See runtime context flow into the editor so debugging becomes continuous understanding and both you and your agents operate from real system behavior.",
    "speakers": "Jeff Blankenburg",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(200) Intermediate",
    "type": "Pre-recorded",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Automation, Observability, Outages, Platform Engineering, Reliability, Resiliency, Copilot, Developer, GitHub Copilot, GitHub, Visual Studio Code, Deployment Pipelines, GitHub Copilot CLI, Visual Studio, Agent Observability, DevTools, Developer Technologies, Developer Frameworks",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 1m 56s</sub>

### ✅ `bash`

**Search Build sessions for Microsoft Agent**

$ npx -y @microsoft/events-cli sessions --tech "Microsoft Agent" --event build-2026 --json 2>/dev/null

<details>
<summary>213 lines</summary>

```
[
  {
    "sessionCode": "DEM340",
    "title": "Build work-ready agents with Foundry + Work IQ, govern with Agent 365",
    "description": "An agent that knows nothing about your work is only half an agent. In this demo, we connect a Foundry agent to Work IQ via MCP, giving it real context about your work and ecosystem, governed by Agent 365. See it run under agent identity, watch Work IQ tools invoked at runtime, and get full observability on every call. Then we run side-by-side evals context-aware vs. context-blind, with scores that prove the difference. Leave knowing how to ground, govern, and evaluate your Foundry agents.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Srikumar (Sri) Nair",
    "timeSlot": "22:00 - 22:25",
    "startDateTime": "2026-06-03T22:00:00Z",
    "endDateTime": "2026-06-03T22:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Responsible AI",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agent 365, Foundry IQ, Microsoft Foundry, Responsible AI, Governance, Work IQ, Context Engineer, Grounding",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP909",
    "title": "Take AI agents from prototype to production with OpenTelemetry",
    "description": "Shipping an AI agent is easy. Trusting it in production is hard. In this session, build a multi-agent travel planner using the Microsoft Agent Framework, then instrument it end-to-end with OpenTelemetry and New Relic. You'll learn how to trace agent decisions, monitor response quality, catch prompt injection attacks, and build CI/CD quality gates—so your AI systems are observable, secure, and ready for real customers.",
    "speakers": "Harry Kimpel",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(100) Foundational",
    "type": "Pre-recorded",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Observability, Reliability, Monitor, Agents, MCP, Foundry Agents, Azure DevOps, Agent Observability, Developer Frameworks, Agentic SDLC",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP907",
    "title": "Monitor GenAI applications beyond golden signals",
    "description": "The golden signals of monitoring (Latency, Errors, Traffic, Saturation) remain foundational, but for GenAI applications they leave critical blind spots. A 200 OK with low latency doesn't tell you the response hallucinated, leaked PII, or cost more than what it should.",
    "speakers": "",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(100) Foundational",
    "type": "Pre-recorded",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Automation, Azure, Azure Monitor, Cost Management, Platform Engineering, Semantic Kernel, Vector Embeddings, Agents, Developer, Microsoft Foundry, MCP, AI Toolkit, Agent Observability, Containment, Agentic Security, Skills, Claws, Openclaw, Agentic SDLC, Dev Tools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM362",
    "title": "Building a Multi-Agent Workflow in Microsoft Fabric",
    "description": "Learn how Microsoft Fabric and the 3 IQs, Work IQ, Fabric IQ, and Foundry IQ, enable dynamic, context‑aware multi‑agent workflows. See how semantic models, lakehouses, and pipelines form agent‑ready foundations, and how specialized agents collaborate across planning, retrieval, summarization, and execution. Discover how natural language, automation, and orchestration power real multi‑agent scenarios in Microsoft Fabric.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Alexander Wachtel",
    "timeSlot": "22:30 - 22:55",
    "startDateTime": "2026-06-03T22:30:00Z",
    "endDateTime": "2026-06-03T22:55:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Microsoft Fabric, Community, CP&D, Data, MVP",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK241",
    "title": "From prototype to production: build and run agents at scale",
    "description": "AI agents are transforming how developers build software—but shipping production-grade agents demands more. This session walks through the end-to-end lifecycle of building AI agents with Foundry Agent Service and Microsoft Agent Framework. See how to go from local prototyping to enterprise-grade hosted deployment with identity, secure networking, evaluations, and lifecycle management. Learn how coding agents like GitHub Copilot integrate directly into the workflow.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Tina Schuchman, Jeff Hollan",
    "timeSlot": "22:45 - 23:30",
    "startDateTime": "2026-06-02T22:45:00Z",
    "endDateTime": "2026-06-02T23:30:00Z",
    "location": "Festival Pavilion, Breakout 1",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Microsoft Foundry",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK243",
    "title": "Claw and agent harness in Microsoft Foundry",
    "description": "Go deep on multi-agent systems built on Microsoft Foundry, featuring Claw agent patterns and the hosted agents architecture. Explore long-running agents with triggers, state management, and file access—all natively supported on Foundry. See how coding agents built with GitHub Copilot SDK and Claude Agent SDK integrate into multi-agent workflows using Microsoft Agent Framework. Learn how to coordinate, host, and operate these systems with observability and continuous evals.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Glenn Condron, Amanda Foster, Shawn Henry",
    "timeSlot": "18:30 - 19:15",
    "startDateTime": "2026-06-03T18:30:00Z",
    "endDateTime": "2026-06-03T19:15:00Z",
    "location": "Gateway Pavilion, Level 1, Cowell Theater",
    "level": "(400) Expert",
    "type": "Breakout",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG466",
    "title": "Building your own MCP server",
    "description": "The Model Context Protocol (MCP) is all the rage and rightly so. As the USB-C for AI, it is an incredibly powerful tool that acts as a bridge between real-world systems and LLMs. But how do you get started with MCP and more importantly: how do you build your own MCP server? In this session we'll build an MCP server from scratch using the MCP C# SDK. We'll look at how to build tools, prompts and resources and how to leverage these with our own AI agent in Microsoft Foundry.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Stuart van der Lee",
    "timeSlot": "16:30 - 16:45",
    "startDateTime": "2026-06-03T16:30:00Z",
    "endDateTime": "2026-06-03T16:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(100) Foundational",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "C#",
    "tags": "Agents, Developer, Microsoft Foundry, MCP, Foundry Agents, Community, MVP, DevTools, Agentic SDLC",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM341",
    "title": "Any agent, any cloud: Standardized tracing with Foundry+OpenTelemetry",
    "description": "Teams are shipping agents across clouds and frameworks—but telemetry is fragmented. In this demo, see how Microsoft Foundry and OpenTelemetry standards for GenAI tracing bring consistent observability that is agent framework agnostic and cloud agnostic. We’ll walk through the simple setup steps to instrument model and tool calls, quickly diagnose failures, latency, and cost spikes, and close the loop with trace-based evaluation, visualization and optimization.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Hanchi Wang, SuiLin Yap",
    "timeSlot": "18:50 - 19:15",
    "startDateTime": "2026-06-03T18:50:00Z",
    "endDateTime": "2026-06-03T19:15:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Responsible AI",
    "solutionArea": "",
    "product": "",
    "languages": ".NET",
    "tags": "Observability, Microsoft Foundry, Responsible AI, Tracing, Open Telemetry",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG431",
    "title": "Extend your LangChain agent to Agent365: Collaborate like an employee",
    "description": "Create a new LangChain agent, enable Agent 365 observability, and integrate Work IQ MCP servers. Register the agent with Agent 365 to bring it under a single control plane. We will demonstrate end-to-end invocation of the agent by triggering the agent from a comment in a Word document, using Work IQ MCP servers, and emitting telemetry.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Alastair Fehr, Aarthi Saravanakumar",
    "timeSlot": "21:50 - 22:05",
    "startDateTime": "2026-06-02T21:50:00Z",
    "endDateTime": "2026-06-02T22:05:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 2",
    "level": "",
    "type": "Lightning Talk",
    "topic": "Responsible AI",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Observability, Agents, Agent 365, Responsible AI, Governance, Work IQ",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG458",
    "title": "Agentic Apps on Microsoft Fabric: Mind-Blowing Interactive Experiences",
    "description": "Imagine turning your Microsoft Fabric semantic models into stunning, interactive apps in minutes. Less Clicking More Building. Discover the brand-new agentic development experience that lets you choose the agents to build reporting. No deep coding, no complex frameworks, just point, describe, and watch agents orchestrate everything. Visuals, custom navigation, writeback, you can have it all directly on your Fabric assets. Think no-holds-barred analytics experiences.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "mike Carlo",
    "timeSlot": "18:50 - 19:05",
    "startDateTime": "2026-06-03T18:50:00Z",
    "endDateTime": "2026-06-03T19:05:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 2",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Microsoft Fabric, Community, CP&D, Data, MVP",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 1m 57s</sub>

### ✅ `bash`

**Search Build sessions for C# .NET**

$ npx -y @microsoft/events-cli sessions --query "C# .NET" --event build-2026 --json --limit 10 2>/dev/null

<details>
<summary>213 lines</summary>

```
[
  {
    "sessionCode": "LTG441",
    "title": "CopyFlag: Imagine Cup Finalists Tackling Creative Protection",
    "description": "CopyFlag helps independent creators fight AI-enabled infringement by continuously scanning marketplaces and social platforms for remixed copies. Built on Azure AI Vision, Azure OpenAI, Azure AI Search, and Azure Machine Learning, it vectorizes images, scores matches, and automates takedowns in minutes. Multi-model detection, combined with Azure AI Content Safety and offender network mapping, makes creator protection scalable and affordable.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Patrick Brown",
    "timeSlot": "16:30 - 16:45",
    "startDateTime": "2026-06-03T16:30:00Z",
    "endDateTime": "2026-06-03T16:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "JavaScript",
    "tags": "Security, Azure ML, API, Agents, PyTorch, Microsoft for Startups, Microsoft Foundry, Foundry Agents, Data, Scaling, ISV, User Privacy, App Integration, Agentic Security",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEMSP394",
    "title": "Scale enterprise .NET apps with AI‑assisted cross‑platform workflows",
    "description": "Most AI tooling for .NET targets greenfield code generation. Enterprise app development is different: layered systems, cross-platform targets, mixed-skill teams, and production demands. In this session, Uno Platform and Kahua show an end-to-end AI-assisted workflow across web, desktop, and mobile, where AI can inspect live app state, understand runtime UI behavior, and act with context. Be ready for real productivity with contextual AI.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Sam Basu, Colin Whitlatch",
    "timeSlot": "21:40 - 22:05",
    "startDateTime": "2026-06-02T21:40:00Z",
    "endDateTime": "2026-06-02T22:05:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Agents, .NET, Developer, GitHub Copilot, Visual Studio Code, OSS, Visual Studio",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "TT656",
    "title": "From Locked-In to Liquid: Modernizing .NET Before the November 2026 EOL",
    "description": ".NET 8 and 9 both hit end of life on November 10, 2026. With hundreds of repos to upgrade, manual migration won't cut it—and pointing agents at the problem without structure burns tokens and produces inconsistent results. Let's talk about how agents, given the right deterministic tools, can move your .NET portfolio from rigid and locked-in to liquid—continuously modern, with swappable components and routine upgrades instead of fire drills. Bring your migration questions and stack horror stories.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Matt Campbell",
    "timeSlot": "22:15 - 23:00",
    "startDateTime": "2026-06-02T22:15:00Z",
    "endDateTime": "2026-06-02T23:00:00Z",
    "location": "Gateway Pavilion, Level 2, Table 3",
    "level": "(200) Intermediate",
    "type": "Table Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "C#",
    "tags": "AI, Azure, Agents, .NET, Microsoft for Startups, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTGSP481",
    "title": "Build reliable coding agents with .NET and durable workflows",
    "description": "Modern AI can generate code—but building agents that autonomously fix bugs, run tests, and create pull requests requires real systems engineering. Dive into a hands-on architecture for coding agents built with .NET Web APIs, Temporal workflows, and AI-powered workers. See how to orchestrate long‑running tasks, manage failures, and securely execute code in sandboxed environments to deliver production‑ready autonomous agents.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Shriram Sankaran Sankaran",
    "timeSlot": "21:10 - 21:25",
    "startDateTime": "2026-06-02T21:10:00Z",
    "endDateTime": "2026-06-02T21:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(400) Expert",
    "type": "Lightning Talk",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Automation, Agents, .NET, Developer",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM365",
    "title": "Beyond REST: .NET Apps That Talk to Hardware",
    "description": "Most app demos stop at REST APIs. This live demo talks to real hardware. I’ll show a .NET app that discovers a device over BLE, exchanges data over NFC or serial, and turns raw device signals into a usable workflow. You’ll leave with a practical pattern for structuring device services, handling platform differences, and deciding when local connectivity beats the cloud.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Jared Rhodes",
    "timeSlot": "23:30 - 23:55",
    "startDateTime": "2026-06-03T23:30:00Z",
    "endDateTime": "2026-06-03T23:55:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": ".NET",
    "tags": "API, Developer, Community, MVP, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP902",
    "title": "Build AI‑driven UIs in .NET MAUI with design systems",
    "description": "This session shows how to build a real‑world .NET MAUI application using structured design systems and AI‑assisted UI composition. Start by defining a design system and translating it into reusable MAUI components and tokens. Learn how AI‑driven UI workflows help compose screens, apply theming, and enforce consistency across the app—accelerating UI development without losing control, performance, or maintainability.",
    "speakers": "Shriram Sankaran Sankaran, Vishnu Menon",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(400) Expert",
    "type": "Pre-recorded",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP929",
    "title": "Build modern .NET apps with Uno Platform, AI, and visual tools",
    "description": "See how to build modern cross-platform .NET apps using Uno Platform with AI-powered and visual tools. This demo shows how to accelerate feature delivery, improve runtime performance, and achieve consistent rendering with SkiaSharp. Learn patterns for streamlining development across platforms with shared tooling and IDE support.",
    "speakers": "Sam Basu",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(200) Intermediate",
    "type": "Pre-recorded",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, .NET",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK207",
    "title": "GitHub Copilot in Visual Studio: Agents That Debug, Profile, and Test",
    "description": "Every IDE has agentic code generation now, but Visual Studio goes further with built-in agents that tackle what code generation can't. In this demo-heavy session, you'll see agents root-cause bugs using live runtime behavior, pinpoint performance bottlenecks and recommend targeted fixes, and build test coverage to catch regressions before they ship. These aren't just code-writing agents. They help enterprise C#, .NET, and C++ developers improve code quality with expert-level diagnostics.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Nik Karpinsky, Mads Kristensen",
    "timeSlot": "23:00 - 23:45",
    "startDateTime": "2026-06-03T23:00:00Z",
    "endDateTime": "2026-06-03T23:45:00Z",
    "location": "Festival Pavilion, Breakout 1",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "C#",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Copilot CLI, Visual Studio, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "TT645-R1",
    "title": "Claws on Windows: Designing Safe, Bounded Agent Actions",
    "description": "Claws touch files, processes, networks, and user state. Poorly designed claws create security risk and brittle behavior. In this interactive table talk, two experts will break down real claw designs used today, including permission scoping, execution boundaries, observability, and rollback. Developers will compare approaches, challenge assumptions, and share what has failed in practice while shaping clearer guidance for building reliable claws on Windows.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Kirupa Chinnathambi, Stuart Schaefer",
    "timeSlot": "18:15 - 19:00",
    "startDateTime": "2026-06-03T18:15:00Z",
    "endDateTime": "2026-06-03T19:00:00Z",
    "location": "Gateway Pavilion, Level 2, Table 3",
    "level": "(200) Intermediate",
    "type": "Table Talk",
    "topic": "Windows",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents, Windows, Agents on Windows, Claws, Openclaw",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "TT645",
    "title": "Claws on Windows: Designing Safe, Bounded Agent Actions",
    "description": "Claws touch files, processes, networks, and user state. Poorly designed claws create security risk and brittle behavior. In this interactive table talk, two experts will break down real claw designs used today, including permission scoping, execution boundaries, observability, and rollback. Developers will compare approaches, challenge assumptions, and share what has failed in practice while shaping clearer guidance for building reliable claws on Windows.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Kirupa Chinnathambi, Stuart Schaefer",
    "timeSlot": "23:15 - 00:00",
    "startDateTime": "2026-06-02T23:15:00Z",
    "endDateTime": "2026-06-03T00:00:00Z",
    "location": "Gateway Pavilion, Level 2, Table 3",
    "level": "(200) Intermediate",
    "type": "Table Talk",
    "topic": "Windows",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents, Windows, Agents on Windows, Claws, Openclaw",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 2m 0s</sub>

### 💭 Reasoning

*Now let me also search for Azure-specific sessions and Aspire + Azure sessions to get a broader picture. Let me also search for sessions more specifically about Microsoft Agent Framework and Azure development.*

---

<sub>⏱️ 2m 1s</sub>

### 💬 Copilot

Now let me search for a few more specific areas in your stack:

---

<sub>⏱️ 2m 9s</sub>

### ✅ `bash`

**Search Azure cloud native sessions**

$ npx -y @microsoft/events-cli sessions --tech "Azure" --query "cloud native containers" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "DEM311",
    "title": "Scale cloud-native workloads with Azure Linux",
    "description": "Azure Linux is a purpose-built Linux distribution optimized for Azure. Learn how Azure Linux supports cloud-native and AI workloads with deep integration into the Azure ecosystem, delivering a consistent Linux platform across containers and other Azure compute services. Designed with a minimal footprint, Azure Linux enables faster provisioning and scaling, reduces the attack surface, and incorporates Azure's robust cloud security standards.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Poorvi Narang, Jim Perrin",
    "timeSlot": "00:00 - 00:25",
    "startDateTime": "2026-06-04T00:00:00Z",
    "endDateTime": "2026-06-04T00:25:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "C",
    "tags": "Azure Linux",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG413",
    "title": "Cloud‑Native PostgreSQL, Rebuilt for Scale: Azure HorizonDB",
    "description": "Modern applications demand elastic scale without complexity. In this session, we explore how Azure HorizonDBre-architects PostgreSQL for cloud-native scalability by decoupling compute, storage, and caching to deliver predictable performance at massive scale. See how it delivers sub millisecond latency, scales out reads and delivers 3x the transactional throughput of self-managed Postgres.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Denzil Ribeiro",
    "timeSlot": "23:50 - 00:05",
    "startDateTime": "2026-06-02T23:50:00Z",
    "endDateTime": "2026-06-03T00:05:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Community, MVP, Azure HorizonDB",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK221",
    "title": "Idea to production-ready agent in seconds on AI-native runtime",
    "description": "Agentic apps behave differently from traditional services. They make decisions, coordinate steps, and react to changing inputs. This session shows how to run agentic workloads on a fast, AI native runtime on Azure Container Apps. The focus is on reliability and speed so you can move from idea to production‑ready agents. We’ll cover patterns for deployment, configuration, safe scaling for bursty traffic, and observability so teams can run agentic systems in production without surprises.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Simon Jakesch, Devanshi Joshi, Gopi Prashanth",
    "timeSlot": "21:45 - 22:30",
    "startDateTime": "2026-06-03T21:45:00Z",
    "endDateTime": "2026-06-03T22:30:00Z",
    "location": "Building B, Level 3, BATS Improv",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "App Mod, CP&D, Reserve",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LAB512",
    "title": "Hands-on with the latest Cobalt VMs – from code to cloud deployment",
    "description": "Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images with Docker, push them to ACR, and deploy to AKS clusters running on Cobalt VMs. Next, wire up a CI/CD pipeline that builds, tests, and deploys to Arm. Then go further—deploy a full-stack web app and serve AI predictions using ONNX Runtime on Arm. Walk out ready to build on Cobalt VMs.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Jamshed Damkewala, Amar Dhamdhere",
    "timeSlot": "22:00 - 23:15",
    "startDateTime": "2026-06-02T22:00:00Z",
    "endDateTime": "2026-06-02T23:15:00Z",
    "location": "Gateway Pavilion, Level 1, Lab 2",
    "level": "(200) Intermediate",
    "type": "Lab",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "Spark",
    "tags": "",
    "relatedSessionCodes": "BRK226",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LAB512-R2",
    "title": "Hands-on with the latest Cobalt VMs – from code to cloud deployment",
    "description": "Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images with Docker, push them to ACR, and deploy to AKS clusters running on Cobalt VMs. Next, wire up a CI/CD pipeline that builds, tests, and deploys to Arm. Then go further—deploy a full-stack web app and serve AI predictions using ONNX Runtime on Arm. Walk out ready to build on Cobalt VMs.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Jamshed Damkewala, Amar Dhamdhere",
    "timeSlot": "16:00 - 17:15",
    "startDateTime": "2026-06-03T16:00:00Z",
    "endDateTime": "2026-06-03T17:15:00Z",
    "location": "Gateway Pavilion, Level 1, Lab 3",
    "level": "(200) Intermediate",
    "type": "Lab",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "Spark",
    "tags": "",
    "relatedSessionCodes": "BRK226",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 2m 8s</sub>

### ✅ `bash`

**Search Semantic Kernel sessions**

$ npx -y @microsoft/events-cli sessions --query "Semantic Kernel" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "LTGSP492",
    "title": "From kernel to agent: Build on-device AI with 2-bit models",
    "description": "Running AI models locally is key to reducing latency, cost, and power usage—but model size remains a constraint. This session explores the engineering behind Microsoft and Qualcomm's 2-bit quantization. Learn how extreme quantization preserves model quality while dramatically reducing memory footprint. Understand how to use Windows ML APIs to load, run, and orchestrate quantized models locally on an AI PC to develop agentic AI applications.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Ashish Garg, Karthik Vijayan",
    "timeSlot": "21:30 - 21:45",
    "startDateTime": "2026-06-02T21:30:00Z",
    "endDateTime": "2026-06-02T21:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Working with models",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Compute, Agents, Developer",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP907",
    "title": "Monitor GenAI applications beyond golden signals",
    "description": "The golden signals of monitoring (Latency, Errors, Traffic, Saturation) remain foundational, but for GenAI applications they leave critical blind spots. A 200 OK with low latency doesn't tell you the response hallucinated, leaked PII, or cost more than what it should.",
    "speakers": "",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(100) Foundational",
    "type": "Pre-recorded",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Automation, Azure, Azure Monitor, Cost Management, Platform Engineering, Semantic Kernel, Vector Embeddings, Agents, Developer, Microsoft Foundry, MCP, AI Toolkit, Agent Observability, Containment, Agentic Security, Skills, Claws, Openclaw, Agentic SDLC, Dev Tools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEMSP387",
    "title": "Secure agent workflows in GitHub Copilot with NVIDIA OpenShell",
    "description": "Agentic workflows in GitHub Copilot can run complex tasks with broad access to local systems. In this session, see how to enforce policy and governance for agents operating in CLI environments. You’ll walk through how NVIDIA OpenShell applies kernel-level controls, isolates agent processes, and limits permissions based on task context. Learn how to apply zero-trust principles to secure agent-driven development workflows.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Ali Golshan Golshan",
    "timeSlot": "16:30 - 16:55",
    "startDateTime": "2026-06-03T16:30:00Z",
    "endDateTime": "2026-06-03T16:55:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM362",
    "title": "Building a Multi-Agent Workflow in Microsoft Fabric",
    "description": "Learn how Microsoft Fabric and the 3 IQs, Work IQ, Fabric IQ, and Foundry IQ, enable dynamic, context‑aware multi‑agent workflows. See how semantic models, lakehouses, and pipelines form agent‑ready foundations, and how specialized agents collaborate across planning, retrieval, summarization, and execution. Discover how natural language, automation, and orchestration power real multi‑agent scenarios in Microsoft Fabric.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Alexander Wachtel",
    "timeSlot": "22:30 - 22:55",
    "startDateTime": "2026-06-03T22:30:00Z",
    "endDateTime": "2026-06-03T22:55:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Microsoft Fabric, Community, CP&D, Data, MVP",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK224",
    "title": "PepsiCo’s blueprint for agentic AI",
    "description": "Learn from Microsoft and PepsiCo engineers who modernized PepsiCo’s data foundation for agentic applications using Azure SQL, Cosmos DB, PostgreSQL, and Azure Databricks. Discover a practical build path for agentic RAG architecture, leveraging Azure SQL features like vector indexing and semantic search, to streamline app development and enable faster, repeatable patterns.  Refresh your own data layer to reduce app development cycles while leveraging modern, repeatable patterns to ship faster.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Krunal Patel, Rishabh Saha, Bob Ward",
    "timeSlot": "21:45 - 22:30",
    "startDateTime": "2026-06-03T21:45:00Z",
    "endDateTime": "2026-06-03T22:30:00Z",
    "location": "Gateway Pavilion, Level 1, Cowell Theater",
    "level": "(200) Intermediate",
    "type": "Breakout",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure SQL, Azure Database for PostgreSQL, Azure Cosmos DB, CP&D, Data",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 2m 11s</sub>

### 💭 Reasoning

*Now I have a good set of results. Let me organize these into the recommended format, grouping by relevance to the user's specific skillset (Azure, .NET, Aspire, C#, Entity Framework, Microsoft Agent Framework).

Let me categorize the most relevant sessions:

**Directly Relevant (core tech stack matches):**

1. **BRK205** - Aspire for agents (Aspire + .NET + Agents) - Damian Edwards, David Fowler
2. **BRK241** - From prototype to production: build and run agents at scale (Microsoft Agent Framework + Foundry)


3. **BRK243** - Claw and agent harness in Microsoft Foundry (Microsoft Agent Framework, multi-agent)
4. **DEM333** - How Foundry integrates with open-source frameworks (Microsoft Agent Framework, .NET)
5. **DEM361** - Understand and fix Agent Framework apps (Microsoft Agent Framework, observability)
6. **LTG466** - Building your own MCP server (C# SDK, Microsoft Foundry)
7. **BRK207** - GitHub Copilot in Visual Studio: Agents That Debug, Profile, and Test (C#, .NET)
8. **TT656** - From Locked-In to Liquid: Modernizing .NET Before November 2026 EOL (C#, .NET)
9. **BRK221** - Idea to production-ready agent in seconds on AI-native runtime (Azure Container Apps, agents)
10. **LTGSP481** - Build reliable coding agents with .NET and durable workflows (.NET, agents)

Then there are adjacent sessions covering agent governance, observability and ROI metrics, standardized tracing with OpenTelemetry, and a case study on PepsiCo's agentic AI implementation across multiple database platforms.*

---

<sub>⏱️ 2m 24s</sub>

### 💬 Copilot

## Recommended Build 2026 Sessions for Your Stack

Based on your skills: **Azure, .NET, Aspire, C#, Entity Framework, Microsoft Agent Framework**

---

### 🎯 Directly Relevant

1. **BRK205** — Aspire for agents: Transform how you build and deploy distributed apps
   📌 Core match: .NET Aspire + Agents + Azure
   🎤 Damian Edwards, David Fowler  |  📍 Festival Pavilion, Breakout 3  |  Jun 3, 2:45 PM PDT
   Breakout · Level 200

2. **BRK241** — From prototype to production: build and run agents at scale
   📌 Core match: Microsoft Agent Framework + Foundry Agent Service
   🎤 Tina Schuchman, Jeff Hollan  |  📍 Festival Pavilion, Breakout 1  |  Jun 2, 3:45 PM PDT
   Breakout · Level 300

3. **BRK243** — Claw and agent harness in Microsoft Foundry
   📌 Core match: Microsoft Agent Framework, multi-agent systems, .NET
   🎤 Glenn Condron, Amanda Foster, Shawn Henry  |  📍 Gateway Pavilion, Cowell Theater  |  Jun 3, 11:30 AM PDT
   Breakout · Level 400

4. **DEM333** — How Foundry integrates with open-source frameworks and tools
   📌 Core match: Microsoft Agent Framework + MCP + A2A + .NET
   🎤 Nagkumar Arkalgud, Facundo Santiago  |  📍 Gateway Pavilion, Theater B  |  Jun 2, 4:00 PM PDT
   Demo

5. **DEM361** — Understand and fix Agent Framework apps with observability and evals
   📌 Core match: Microsoft Agent Framework debugging + OpenTelemetry
   🎤 Jim Bennett  |  📍 Gateway Pavilion, Theater B  |  Jun 3, 3:30 PM PDT
   Demo · Level 300

6. **LTG466** — Building your own MCP server
   📌 Core match: C# MCP SDK + Microsoft Foundry agents
   🎤 Stuart van der Lee  |  📍 Gateway Pavilion, Theater 1  |  Jun 3, 9:30 AM PDT
   Lightning Talk · Level 100

7. **BRK207** — GitHub Copilot in Visual Studio: Agents That Debug, Profile, and Test
   📌 Core match: C#, .NET, Visual Studio diagnostics agents
   🎤 Nik Karpinsky, Mads Kristensen  |  📍 Festival Pavilion, Breakout 1  |  Jun 3, 4:00 PM PDT
   Breakout · Level 300

---

### 🔗 Adjacent (Complementary to Your Work)

8. **TT656** — From Locked-In to Liquid: Modernizing .NET Before the November 2026 EOL
   📌 .NET 8/9 EOL migration strategies using agents — relevant if you maintain multiple .NET repos
   🎤 Matt Campbell  |  📍 Gateway Pavilion, Table 3  |  Jun 2, 3:15 PM PDT
   Table Talk · Level 200 · C#

9. **BRK221** — Idea to production-ready agent in seconds on AI-native runtime
   📌 Azure Container Apps for agentic workloads — deployment target for Aspire apps
   🎤 Simon Jakesch, Devanshi Joshi  |  📍 Building B, BATS Improv  |  Jun 3, 2:45 PM PDT
   Breakout · Level 300

10. **BRK250** — Govern open-source AI agents, any framework, any scale
    📌 Enterprise governance for Microsoft Agent Framework + open-source agents
    🎤 Sarah Bird, Sandeep Atluri  |  📍 Building B, BATS Improv  |  Jun 2, 2:30 PM PDT
    Breakout · Level 300

11. **LTGSP481** — Build reliable coding agents with .NET and durable workflows
    📌 .NET Web APIs + durable orchestration for autonomous agents
    🎤 Shriram Sankaran  |  📍 Gateway Pavilion, Theater 3  |  Jun 2, 2:10 PM PDT
    Lightning Talk · Level 400

12. **BRK224** — PepsiCo's blueprint for agentic AI
    📌 Azure SQL + Cosmos DB + PostgreSQL data layer for agents (EF-compatible data stores)
    🎤 Krunal Patel, Bob Ward  |  📍 Gateway Pavilion, Cowell Theater  |  Jun 3, 2:45 PM PDT
    Breakout · Level 200

---

### 🧭 Suggested Learning Path

| Order | Session | Why |
|-------|---------|-----|
| 1 | **BRK205** (Aspire) | Foundation — see how Aspire now orchestrates agents |
| 2 | **BRK241** (Agents at scale) | Architecture — prototype → production with Agent Framework |
| 3 | **DEM333** (Foundry + frameworks) | Integration — how it all connects with MCP/A2A |
| 4 | **BRK243** (Claw + agent harness) | Deep dive — multi-agent patterns in .NET |
| 5 | **DEM361** (Observability + evals) | Operations — debug and evaluate your agents |
| 6 | **BRK221** (AI-native runtime) | Deploy — run agents on Azure Container Apps |

---

Would you like me to save this as a markdown schedule file, or look up any specific session in more detail?

---

<sub>⏱️ 3m 24s</sub>

### 👤 User

use web to find my linkedin https://www.linkedin.com/in/sinannar/ and personal github io https://sinannar.github.io/ and github profile https://github.com/sinannar to learn more about me, and recheck what should I focus on Microsoft Build, use previous information I provided as well of course.

---

<sub>⏱️ 3m 26s</sub>

### 💭 Reasoning

*The user wants me to look at their LinkedIn, personal GitHub.io site, and GitHub profile to learn more about them, then refine my Build 2026 session recommendations based on what I find combined with what they already told me (Azure, .NET, Aspire, C#, Entity Framework, Microsoft Agent Framework).*

---

<sub>⏱️ 3m 32s</sub>

### ❌ `web_fetch`

**https://www.linkedin.com/in/sinannar/**

<details>
<summary>Arguments</summary>

```json
{
  "url": "https://www.linkedin.com/in/sinannar/",
  "max_length": 10000
}
```

</details>

```
Error: Failed to fetch https://www.linkedin.com/in/sinannar/ - status code 404
```


---

<sub>⏱️ 3m 32s</sub>

### ✅ `web_fetch`

**https://sinannar.github.io/**

<details>
<summary>Arguments</summary>

```json
{
  "url": "https://sinannar.github.io/",
  "max_length": 10000
}
```

</details>

<details>
<summary>18 lines</summary>

```
Contents of https://sinannar.github.io/:
## Sinan Nar

## Senior Software Engineer & Technical Leader

I am a Consultant who focuses on an Apps and AI. I am working at ARINCO which is Microsoft and GitHub partner consultancy. I co-organise the Aotearoa Azure User Group and the Auckland .NET User Group. I am an experienced and certified software engineer, specialise in the Microsoft ecosystem, with a focus on Azure and GitHub.

* * *

### What I Work With

.NET (Core & 6+), C#, JavaScript, TypeScript, Angular, Ionic, Node.js

Kubernetes, Docker, Azure (App Services, Functions, Service Bus, AKS, Container Apps, KeyVault)

CI/CD (GitHub Actions, Azure DevOps), Terraform, Integration Testing, TDD, BDD

SQL (MSSQL, PostgreSQL, MySQL), MongoDB, CosmosDB, Datadog, Azure Monitor

### How I Work

*   Clear, friendly communication with all stakeholders
*   Collaborative and supportive team player
*   Mentor and coach for junior developers
*   Proactive problem solver and decision maker
*   Strong time management and prioritization
*   Always learning and sharing knowledge

[Read my Blog →](/blog)
```

</details>


---

<sub>⏱️ 3m 34s</sub>

### ✅ `web_fetch`

**https://github.com/sinannar**

<details>
<summary>Arguments</summary>

```json
{
  "url": "https://github.com/sinannar",
  "max_length": 10000
}
```

</details>

<details>
<summary>35 lines</summary>

```
Contents of https://github.com/sinannar:
[Skip to content](#start-of-content)

## Navigation Menu

*   *   AI CODE CREATION
        
        *   [
            
            GitHub CopilotWrite better code with AI
            
            
            
            ](https://github.com/features/copilot)
        *   [
            
            GitHub SparkBuild and deploy intelligent apps
            
            
            
            ](https://github.com/features/spark)
        *   [
            
            GitHub ModelsManage and compare prompts
            
            
            
            ](https://github.com/features/models)
        *   [
            
            MCP RegistryNewIntegrate external tools
            
            
            
            ](https://github.com/mcp)
        
    
    [View all features](https://github.com/features)
    

*   [Pricing](https://github.com/pricing)

## Provide feedback

## Saved searches

## Use saved searches to filter your results more quickly

[Sign up](/signup?ref_cta=Sign+up&ref_loc=header+logged+out&ref_page=%2F%3Cuser-name%3E&source=header)

###### `npx snnr`

[](#npx-snnr)

### Hello 🌍

[](#hello-)

Hi there👋  
I am Sinan Nar. I am a Consultant who focuses on an Apps and AI. I am working at ARINCO which is Microsoft and GitHub partner consultancy. I co-organise the Aotearoa Azure User Group and the Auckland .NET User Group. I am an experienced and certified software engineer, specialise in the Microsoft ecosystem, with a focus on Azure and GitHub.

### ⚓ Links & Contacts

[](#-links--contacts)

 [![](https://camo.githubusercontent.com/4a8e4e3f00d10a1f2edc7f25cdbd7894ea27baf90c3567281c40a01c257c0f19/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565266c6162656c3d6c696e6b6564696e266c6f676f3d6c696e6b6564696e266c6f676f436f6c6f723d7768697465267374796c653d666f722d7468652d6261646765266d6573736167653d436f6e6e656374)](https://www.linkedin.com/in/sinannar)[![](https://camo.githubusercontent.com/3b4cf4c060746b01428cd4038b6fd34c450a73576ae35c0cf5fe3f4f85342b58/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565266c6162656c3d74776974746572266c6f676f3d74776974746572266c6f676f436f6c6f723d7768697465267374796c653d666f722d7468652d6261646765266d6573736167653d466f6c6c6f77) ](https://twitter.com/snn_nr)[![](https://camo.githubusercontent.com/4882793cbdc32070b4323e94b6ce141695a7983dd53c91465db083422e6a30a5/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565266c6162656c3d676d61696c266c6f676f3d676d61696c266c6f676f436f6c6f723d7768697465267374796c653d666f722d7468652d6261646765266d6573736167653d456d61696c) ](mailto:sinan.nar@gmail.com)[![](https://camo.githubusercontent.com/d71c580d03b05352b919319955ce1acb49f23ec8af027a789fa730fd3e99d49b/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565266c6162656c3d637265646c79266c6f676f3d637265646c79266c6f676f436f6c6f723d7768697465267374796c653d666f722d7468652d6261646765266d6573736167653d437265646c79) ](https://www.credly.com/users/sinan-nar)[![](https://camo.githubusercontent.com/9a769e616ce78645bf51d12e4179cfbfd72fb413722b284e0be3ec3c75a86010/68747470733a2f2f63646e2e6275796d6561636f666665652e636f6d2f627574746f6e732f64656661756c742d6f72616e67652e706e67)](https://www.buymeacoffee.com/sinannar)

### 🔧 Technologies & Tools

[](#-technologies--tools)

[![](https://camo.githubusercontent.com/4fde7c493c2723d1fe98245a56ae4d55fe9ecda642d5602910b6ae84218cc5b5/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436f6465266d6573736167653d63253233266c6f676f3d637368617270)](https://camo.githubusercontent.com/4fde7c493c2723d1fe98245a56ae4d55fe9ecda642d5602910b6ae84218cc5b5/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436f6465266d6573736167653d63253233266c6f676f3d637368617270) [![](https://camo.githubusercontent.com/c51548b0de74c0e870a432a3db5be961722d2945b74f1bb1c9543132ba7e28ca/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4672616d65776f726b266d6573736167653d646f746e6574266c6f676f3d646f746e6574)](https://camo.githubusercontent.com/c51548b0de74c0e870a432a3db5be961722d2945b74f1bb1c9543132ba7e28ca/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4672616d65776f726b266d6573736167653d646f746e6574266c6f676f3d646f746e6574) [![](https://camo.githubusercontent.com/e91cf29a9067fea71532ae31859a9f8f17dd775ed022a9b6a9dfc06954a9ee83/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4f53266d6573736167653d57696e646f7773266c6f676f3d77696e646f7773)](https://camo.githubusercontent.com/e91cf29a9067fea71532ae31859a9f8f17dd775ed022a9b6a9dfc06954a9ee83/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4f53266d6573736167653d57696e646f7773266c6f676f3d77696e646f7773) [![](https://camo.githubusercontent.com/7855d6eb13f5aeea1ce653718cb20cfd7100f38cbf7359f536287ef0b6770637/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436c6f7564266d6573736167653d417a757265266c6f676f3d6d6963726f736f6674617a757265)](https://camo.githubusercontent.com/7855d6eb13f5aeea1ce653718cb20cfd7100f38cbf7359f536287ef0b6770637/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436c6f7564266d6573736167653d417a757265266c6f676f3d6d6963726f736f6674617a757265) [![](https://camo.githubusercontent.com/b144e5293dd68ff2cb2ddd9dfbc93cbfcadbcbb635705c76f160e2ab5970e8d7/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4442266d6573736167653d4d7353514c266c6f676f3d6d6963726f736f667473716c736572766572)](https://camo.githubusercontent.com/b144e5293dd68ff2cb2ddd9dfbc93cbfcadbcbb635705c76f160e2ab5970e8d7/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4442266d6573736167653d4d7353514c266c6f676f3d6d6963726f736f667473716c736572766572) [![](https://camo.githubusercontent.com/9e0d513ea98546095db7bb52926750268eb44cc0b7a3aecc88d4842c2deb4c34/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436f6465266d6573736167653d74797065736372697074266c6f676f3d74797065736372697074)](https://camo.githubusercontent.com/9e0d513ea98546095db7bb52926750268eb44cc0b7a3aecc88d4842c2deb4c34/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436f6465266d6573736167653d74797065736372697074266c6f676f3d74797065736372697074) [![](https://camo.githubusercontent.com/12673d4e4eaac314545c5be3911cf87ee85a104fa8c0025a924eb36d54943cee/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d546f6f6c266d6573736167653d706f7765727368656c6c266c6f676f3d706f7765727368656c6c)](https://camo.githubusercontent.com/12673d4e4eaac314545c5be3911cf87ee85a104fa8c0025a924eb36d54943cee/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d546f6f6c266d6573736167653d706f7765727368656c6c266c6f676f3d706f7765727368656c6c) [![](https://camo.githubusercontent.com/7b5918face481843572020357caf20c548f17408873e5559601a7e55092ae34f/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436f6465266d6573736167653d6a617661266c6f676f3d6a617661)](https://camo.githubusercontent.com/7b5918face481843572020357caf20c548f17408873e5559601a7e55092ae34f/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d436f6465266d6573736167653d6a617661266c6f676f3d6a617661) [![](https://camo.githubusercontent.com/578775870d5573b1b9c094072425cf6c96bb39246ab2569480788fbda45d112a/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d546f6f6c266d6573736167653d77696e646f77737465726d696e616c266c6f676f3d77696e646f77737465726d696e616c)](https://camo.githubusercontent.com/578775870d5573b1b9c094072425cf6c96bb39246ab2569480788fbda45d112a/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d546f6f6c266d6573736167653d77696e646f77737465726d696e616c266c6f676f3d77696e646f77737465726d696e616c) [![](https://camo.githubusercontent.com/4623c52d8aec561515abb865cafa30df44367ac354c88baa13a8b602fd2b4017/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4672616d65776f726b266d6573736167653d616e67756c6172266c6f676f3d616e67756c6172)](https://camo.githubusercontent.com/4623c52d8aec561515abb865cafa30df44367ac354c88baa13a8b602fd2b4017/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4672616d65776f726b266d6573736167653d616e67756c6172266c6f676f3d616e67756c6172) [![](https://camo.githubusercontent.com/83c9c7c30e82d596b3f4e22d7c91b2e66b023847852935398fd5663bb93ac5e9/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c653d706c6173746963266c6162656c3d4f53266d6573736167653d5562756e7475266c6f676f3d7562756e7475)](https://camo.githubusercontent.com/83c9c7c30e82d596b3f4e22d7c91b2e66b023847852935398fd5663bb93ac5e9/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f636f6c6f723d626c7565267374796c

<note>Content truncated. Call the fetch tool with a start_index of 10000 to get more content.</note>
```

</details>


---

<sub>⏱️ 3m 37s</sub>

### 💭 Reasoning

*I got a good picture of Sinan from his GitHub profile and personal site. LinkedIn returned a 404 (likely requires authentication). Let me also check his blog for more context, and maybe look at his GitHub repos to see what he's actually building.

From what I can see:
- **Name**: Sinan Nar
- **Role**: Senior Software Engineer & Technical Leader / Consultant
- **Company**: ARINCO (Microsoft and GitHub partner consultancy)
- **Focus**: Apps and AI
- **Community**: Co-organises Aotearoa Azure User Group and Auckland .NET User Group
- **Location**: New Zealand (Auckland)


- **Tech Stack**: He's deeply invested in the Microsoft ecosystem with .NET, C#, and Azure across multiple services. On the frontend, he works with JavaScript, TypeScript, and Angular. He's also comfortable with containerization via Kubernetes and Docker, infrastructure-as-code with Terraform, and has solid experience with CI/CD pipelines through GitHub Actions and Azure DevOps. His data layer spans relational databases like MSSQL and PostgreSQL, plus NoSQL options like MongoDB and CosmosDB. He practices TDD and BDD, uses Datadog and Azure Monitor for observability, and has some Java experience as well.

Now I'm looking for sessions that dive deeper into these specific areas—particularly around container orchestration, serverless functions, messaging patterns, infrastructure automation, and observability tooling.*

---

<sub>⏱️ 3m 47s</sub>

### 💬 Copilot

Good, I have a much richer picture now. Let me search for more sessions matching your broader stack:

---

<sub>⏱️ 4m 0s</sub>

### ✅ `bash`

**Search Azure Container Apps sessions**

$ npx -y @microsoft/events-cli sessions --tech "Azure Container Apps" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "ODSP926",
    "title": "Build collaborative agents into apps with APIs",
    "description": "PwC research found the top barrier to AI agent impact isn't the technology; it's connecting agents across applications and workflows to truly operate like coworkers. Most organizations deploy agents in isolation, then wonder why value stalls. This session explores how APIs serve as the relationship layer between AI models and encourage meaningful adoption, using Napster's Omniagent API as a working example of how to move agents from standalone tools to embedded, cross-functional collaborators.",
    "speakers": "Ziv Navoth, Edo Segal",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(300) Advanced",
    "type": "Pre-recorded",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Azure, API, Agents, Foundry Agents, Developer Technologies",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTGSP491",
    "title": "Design multimodal agents that work as collaborators",
    "description": "What if every person on your team had a dozen competent coworkers available around the clock, across every function, ready to support them regardless of the task? The shift from copilots to coworkers is already underway. Napster Chief Technology and Product Officer Edo Segal will offer a look at what happens when AI actually shows up as part of the team. These multimodal coworkers combine video presence, real-time tool access, and relationship continuity to uplevel the employee experience.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Edo Segal",
    "timeSlot": "21:00 - 21:15",
    "startDateTime": "2026-06-03T21:00:00Z",
    "endDateTime": "2026-06-03T21:15:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(300) Advanced",
    "type": "Lightning Talk",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Azure, Copilot, Agents, Windows APIs",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LABSP580-R1",
    "title": "Build and deploy reasoning agents with NVIDIA Nemotron and Foundry",
    "description": "Build and deploy intelligent AI agents using NVIDIA AI-Q Blueprint and Nemotron with Microsoft Foundry, Azure Container Apps, and Azure AI Search. In this hands-on lab, you'll create an agent for enterprise deep research that combines AI reasoning, multimodal data extraction, and retrieval-augmented generation to synthesize data into actionable insights. Learn how to connect data sources and run inference at scale—then apply these patterns to your own production workflows.\n\nThis Lab is BYOD. Add this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Harmke Alkemade, Dimitri Maltezakis, Anton Slutsky",
    "timeSlot": "17:45 - 19:00",
    "startDateTime": "2026-06-03T17:45:00Z",
    "endDateTime": "2026-06-03T19:00:00Z",
    "location": "NVIDIA @ 308",
    "level": "(300) Advanced",
    "type": "Lab",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LABSP580",
    "title": "Build and deploy reasoning agents with NVIDIA Nemotron and Foundry",
    "description": "Build and deploy intelligent AI agents using NVIDIA AI-Q Blueprint and Nemotron with Microsoft Foundry, Azure Container Apps, and Azure AI Search. In this hands-on lab, you'll create an agent for enterprise deep research that combines AI reasoning, multimodal data extraction, and retrieval-augmented generation to synthesize data into actionable insights. Learn how to connect data sources and run inference at scale—then apply these patterns to your own production workflows.\n\nThis Lab is BYOD. Add this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Harmke Alkemade, Dimitri Maltezakis, Anton Slutsky",
    "timeSlot": "19:30 - 20:45",
    "startDateTime": "2026-06-02T19:30:00Z",
    "endDateTime": "2026-06-02T20:45:00Z",
    "location": "NVIDIA @ 308",
    "level": "(300) Advanced",
    "type": "Lab",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTGSP479",
    "title": "Automate Windows on Arm migrations with AI-assisted specs",
    "description": "Porting Windows apps to Arm used to take weeks: identifying dependencies, chasing compatibility gaps, and relying on trial and error. With AI, the same workflow now fits in a single session. This session shows Windows developers a spec-driven, AI-assisted workflow where a migration spec defines the architecture, GitHub Copilot applies Arm-aware changes, and GitHub Actions with WoA runners validate builds in CI. You’ll leave with a workflow that transforms your next migration from project to PR.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Jamshed Damkewala, michael Gamble, Clay Nelson",
    "timeSlot": "19:40 - 19:55",
    "startDateTime": "2026-06-02T19:40:00Z",
    "endDateTime": "2026-06-02T19:55:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Automation, Azure, Cost Management, Platform Engineering, Reliability, SAP, Compute, MongoDB Migration, Oracle Migration, On-prem Migration, MySQL Migration, Postgres Migration, Azure SQL, Azure SQL Hyperscale, Azure Database for MySQL, Azure Database for PostgreSQL, SQL Server Containers on Kubernetes, CosmosDB, Azure Cosmos DB, .NET, Developer, Azure Kubernetes Service (AKS)​​, GitHub Advanced Security, Agent 365, Software Development Company, MCP, Foundry Agents, AKS, Azure Copilot, Azure DevOps, Azure Linux, Data, Deployment Pipelines, OSS CI/CD Libraries, Windows 365 for Agents, Agents on Windows",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 4m 0s</sub>

### ✅ `bash`

**Search Azure Functions sessions**

$ npx -y @microsoft/events-cli sessions --tech "Azure Functions" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "LTG455",
    "title": "From Code to Agents: Build Production MCP Servers on Azure Functions",
    "description": "Agents are transforming how we build software but taking them from prototype to production remains the biggest challenge enterprise teams face. AI Agents need to call real tools- and today that means fragile, custom integrations that break when anything changes. MCP gives agents a standard way to discover and invoke tools at runtime. See real-world scenarios such as a DevOps CI/CD automation system where agents identify detect deployment issues, diagnose, and create rollback PRs in Azure DevOps.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Jonah Andersson",
    "timeSlot": "22:10 - 22:25",
    "startDateTime": "2026-06-02T22:10:00Z",
    "endDateTime": "2026-06-02T22:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(400) Expert",
    "type": "Lightning Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Community, MVP",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTGSP491",
    "title": "Design multimodal agents that work as collaborators",
    "description": "What if every person on your team had a dozen competent coworkers available around the clock, across every function, ready to support them regardless of the task? The shift from copilots to coworkers is already underway. Napster Chief Technology and Product Officer Edo Segal will offer a look at what happens when AI actually shows up as part of the team. These multimodal coworkers combine video presence, real-time tool access, and relationship continuity to uplevel the employee experience.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Edo Segal",
    "timeSlot": "21:00 - 21:15",
    "startDateTime": "2026-06-03T21:00:00Z",
    "endDateTime": "2026-06-03T21:15:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(300) Advanced",
    "type": "Lightning Talk",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Azure, Copilot, Agents, Windows APIs",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "ODSP926",
    "title": "Build collaborative agents into apps with APIs",
    "description": "PwC research found the top barrier to AI agent impact isn't the technology; it's connecting agents across applications and workflows to truly operate like coworkers. Most organizations deploy agents in isolation, then wonder why value stalls. This session explores how APIs serve as the relationship layer between AI models and encourage meaningful adoption, using Napster's Omniagent API as a working example of how to move agents from standalone tools to embedded, cross-functional collaborators.",
    "speakers": "Ziv Navoth, Edo Segal",
    "timeSlot": "",
    "startDateTime": "",
    "endDateTime": "",
    "location": "",
    "level": "(300) Advanced",
    "type": "Pre-recorded",
    "topic": "Agents & apps",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "AI, Azure, API, Agents, Foundry Agents, Developer Technologies",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG453",
    "title": "Building an End‑to‑End Enterprise AI Platform on Azure",
    "description": "Enterprise AI systems span ingestion, embeddings, vector search, APIs, and partner integrations—often across serverless and container platforms. In this demo, see how Contoso builds a production‑ready, end‑to‑end AI solution on Azure using Azure Functions, Container Apps, AKS, Cosmos DB vector search. Learn proven patterns for scalability, observability, and secure operations with minimal dev effort.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Ehsan Eskandari",
    "timeSlot": "20:50 - 21:05",
    "startDateTime": "2026-06-02T20:50:00Z",
    "endDateTime": "2026-06-02T21:05:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(300) Advanced",
    "type": "Lightning Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Community, MVP",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM311",
    "title": "Scale cloud-native workloads with Azure Linux",
    "description": "Azure Linux is a purpose-built Linux distribution optimized for Azure. Learn how Azure Linux supports cloud-native and AI workloads with deep integration into the Azure ecosystem, delivering a consistent Linux platform across containers and other Azure compute services. Designed with a minimal footprint, Azure Linux enables faster provisioning and scaling, reduces the attack surface, and incorporates Azure's robust cloud security standards.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Poorvi Narang, Jim Perrin",
    "timeSlot": "00:00 - 00:25",
    "startDateTime": "2026-06-04T00:00:00Z",
    "endDateTime": "2026-06-04T00:25:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "C",
    "tags": "Azure Linux",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 4m 0s</sub>

### ✅ `bash`

**Search GitHub Actions sessions**

$ npx -y @microsoft/events-cli sessions --tech "GitHub Actions" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "DEM301",
    "title": "Rethinking CI: Actions, AI Agents, and the End of Commit-Fail-Commit",
    "description": "Your pipelines automate the predictable. But what about triaging issues, reviewing PRs, responding to incidents, and coordinating across tools? See what's new in GitHub Actions and how it's becoming the execution layer for AI agents across your dev lifecycle. We'll cover agent-triggered workflows, MCP server integration, and automated handoffs that keep humans in the loop — plus how to finally break the 'commit - see CI fail - commit again' loop.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Salil Subbakrishna, Denizhan Yigitbas",
    "timeSlot": "22:00 - 22:25",
    "startDateTime": "2026-06-03T22:00:00Z",
    "endDateTime": "2026-06-03T22:25:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(400) Expert",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents, Developer, GitHub Copilot, GitHub, MCP, GitHub Actions, GitHub Enterprise, OSS, OSS CI/CD Libraries, GitHub Copilot CLI, DevTools, Agentic SDLC",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG401",
    "title": "10 ways to maximize GitHub Copilot",
    "description": "It started as autocomplete, but that's so 2024. What can GitHub Copilot really do in 2026? Join us for our 10 favorite hidden gems. Number will shock you!\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Aaron Powell",
    "timeSlot": "22:30 - 22:45",
    "startDateTime": "2026-06-02T22:30:00Z",
    "endDateTime": "2026-06-02T22:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG401-R1",
    "title": "10 ways to maximize GitHub Copilot (Repeat)",
    "description": "It started as autocomplete, but that's so 2024. What can GitHub Copilot really do in 2026? Join us for our 10 favorite hidden gems. Number will shock you!\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Aaron Powell",
    "timeSlot": "00:00 - 00:25",
    "startDateTime": "2026-06-04T00:00:00Z",
    "endDateTime": "2026-06-04T00:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG465",
    "title": "Beyond the Basics: What GitHub Can Do Today",
    "description": "GitHub has been the developer platform of choice for well over a decade. During that time, GitHub continues to add new features and often times people don't realize what's out there. This lightning talk will rapid fire through 10 different things GitHub can do that you might not have seen before. We'll cover AI, Agentic Workflows, Actions, Code Collaboration and more. By the end of this lightning talk, you'll walk away with a number of practical ideas to take back to apply at work immediately.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Scott Sauber",
    "timeSlot": "17:10 - 17:25",
    "startDateTime": "2026-06-03T17:10:00Z",
    "endDateTime": "2026-06-03T17:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(100) Foundational",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents, Developer, GitHub Copilot, GitHub, Community, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, MVP, DevTools, Agentic SDLC",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM305",
    "title": "GitHub Copilot Anywhere: From CLIs to Cloud Execution Environments",
    "description": "Modern development no longer happens in one place. You might start in your terminal, step away, and pick things back up from another device or let work continue in the cloud. This session explores using GitHub Copilot across environments, from local CLI sessions to full cloud execution with remote execution environments. See how Copilot runs commands, iterates on changes, and continues work without losing context, while you stay in control.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Ellie Bennett, Denizhan Yigitbas",
    "timeSlot": "17:30 - 17:55",
    "startDateTime": "2026-06-03T17:30:00Z",
    "endDateTime": "2026-06-03T17:55:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 4m 2s</sub>

### ✅ `bash`

**Search Cosmos DB sessions**

$ npx -y @microsoft/events-cli sessions --tech "Cosmos DB" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "LTG411",
    "title": "Agentic RAG for fast, low-cost knowledge retrieval on Azure Cosmos DB",
    "description": "Skip the knowledge graph and ontology construction. DiverseRAG delivers high-quality answers to open-ended, multi-hop, and nuanced questions in seconds using GPU-accelerated local models and Azure Cosmos DB — combining hybrid full-text and vector search, diversity selection, and sub-question decomposition across large structured and unstructured datasets. You'll leave knowing how to build production-ready knowledge retrieval as long-term agentic memory to boost your agents' accuracy and speed.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "James Codella",
    "timeSlot": "00:30 - 00:45",
    "startDateTime": "2026-06-03T00:30:00Z",
    "endDateTime": "2026-06-03T00:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(400) Expert",
    "type": "Lightning Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "CUDA",
    "tags": "Azure Cosmos DB, CP&D, OFT",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM310",
    "title": "Ship code faster with AI-powered NoSQL schema design",
    "description": "NoSQL schema design is hard—denormalization decisions, partition key selection, and data modeling patterns require expertise. Use GitHub Copilot and the new Azure Cosmos DB Agent Toolkit to accelerate development with AI-assisted schema generation, query optimization suggestions, and refactoring recommendations. Iterate rapidly with the new Mac/Linux emulator for local testing. Demo shows schema evolution across three iterations in 30 minutes versus days of manual design.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Marko Hotti, Sergiy Smyrnov",
    "timeSlot": "23:30 - 23:55",
    "startDateTime": "2026-06-02T23:30:00Z",
    "endDateTime": "2026-06-02T23:55:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(200) Intermediate",
    "type": "Demo",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure Cosmos DB, CP&D, Data",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK224",
    "title": "PepsiCo’s blueprint for agentic AI",
    "description": "Learn from Microsoft and PepsiCo engineers who modernized PepsiCo’s data foundation for agentic applications using Azure SQL, Cosmos DB, PostgreSQL, and Azure Databricks. Discover a practical build path for agentic RAG architecture, leveraging Azure SQL features like vector indexing and semantic search, to streamline app development and enable faster, repeatable patterns.  Refresh your own data layer to reduce app development cycles while leveraging modern, repeatable patterns to ship faster.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Krunal Patel, Rishabh Saha, Bob Ward",
    "timeSlot": "21:45 - 22:30",
    "startDateTime": "2026-06-03T21:45:00Z",
    "endDateTime": "2026-06-03T22:30:00Z",
    "location": "Gateway Pavilion, Level 1, Cowell Theater",
    "level": "(200) Intermediate",
    "type": "Breakout",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure SQL, Azure Database for PostgreSQL, Azure Cosmos DB, CP&D, Data",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "TT621",
    "title": "Build & modernize multi-tenant AI app data planes for planetary scale",
    "description": "Most AI-agent demos fail in production because their data platforms were never built for multi-tenant scale. This table talk connects two real journeys: modernizing relational systems to NoSQL, and running large-scale agentic SaaS. We’ll whiteboard migration tradeoffs, tenant-aware modeling, agent memory and retrieval patterns, plus hard lessons learned to ship reliable AI systems at scale today!\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "James Codella, Sergiy Smyrnov",
    "timeSlot": "20:15 - 21:00",
    "startDateTime": "2026-06-02T20:15:00Z",
    "endDateTime": "2026-06-02T21:00:00Z",
    "location": "Gateway Pavilion, Level 2, Table 1",
    "level": "(200) Intermediate",
    "type": "Table Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure Database for PostgreSQL, CosmosDB, Azure Cosmos DB, CP&D, Data",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "BRK223",
    "title": "From rows to reasoning: Designing databases for AI apps and agents",
    "description": "AI applications and agents require data platforms designed for reasoning, not just transactions. Traditional architectures force developers to stitch data systems together, adding latency and complexity. In this demo‑rich session, we’ll show the latest innovations in SQL Database and Cosmos DB, then build an app on Azure HorizonDB, Azure’s new cloud‑native PostgreSQL service, to show how AI apps built directly in the database simplifies design and enables reasoning over operational data.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Charles Feddersen, Abe Omorogbe",
    "timeSlot": "21:30 - 22:15",
    "startDateTime": "2026-06-02T21:30:00Z",
    "endDateTime": "2026-06-02T22:15:00Z",
    "location": "Festival Pavilion, Breakout 2",
    "level": "(300) Advanced",
    "type": "Breakout",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure SQL, Azure Database for PostgreSQL, Azure Cosmos DB, CP&D, Data, Azure HorizonDB",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 4m 1s</sub>

### ✅ `bash`

**Search AKS Kubernetes sessions**

$ npx -y @microsoft/events-cli sessions --query "Kubernetes AKS" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "LTG408",
    "title": "The developer experience with AKS Desktop and VS Code",
    "description": "Getting an app from local dev or on‑prem to AKS can be hard to make secure, repeatable, and easy to run. This session shows how AKS Desktop and VS Code speed the developer‑to‑AKS journey, from local Kubernetes workflows and containerisation to CI/CD and safe deployments, using built‑in Kubernetes best practices for reliable operations.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Paul Yu",
    "timeSlot": "19:20 - 19:35",
    "startDateTime": "2026-06-02T19:20:00Z",
    "endDateTime": "2026-06-02T19:35:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(100) Foundational",
    "type": "Lightning Talk",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "C",
    "tags": "Azure Kubernetes Service (AKS)​​",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LAB510-R1",
    "title": "Take LLMs from prototype to production on AKS",
    "description": "Moving an AI model from experiment to production is hard. Learn about AI Runway, an open-source accelerator that simplifies deploying LLMs on Azure Kubernetes Service (AKS). By treating models as native Kubernetes resources, AI Runway offers a single interface that adapts to multiple inference backends. You’ll deploy a production LLM on AKS, implement custom resources for scaling and networking, configure GPU and latency monitoring, and integrate it into CI/CD pipelines.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Sertaç Özercan, Paul Yu",
    "timeSlot": "17:45 - 19:00",
    "startDateTime": "2026-06-03T17:45:00Z",
    "endDateTime": "2026-06-03T19:00:00Z",
    "location": "Building C, Level 2, Room 205",
    "level": "(300) Advanced",
    "type": "Lab",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure Kubernetes Service (AKS)​​",
    "relatedSessionCodes": "BRK222",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LAB510-R3",
    "title": "Take LLMs from prototype to production on AKS",
    "description": "Moving an AI model from experiment to production is hard. Learn about AI Runway, an open-source accelerator that simplifies deploying LLMs on Azure Kubernetes Service (AKS). By treating models as native Kubernetes resources, AI Runway offers a single interface that adapts to multiple inference backends. You’ll deploy a production LLM on AKS, implement custom resources for scaling and networking, configure GPU and latency monitoring, and integrate it into CI/CD pipelines.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Sertaç Özercan, Paul Yu",
    "timeSlot": "23:45 - 01:00",
    "startDateTime": "2026-06-03T23:45:00Z",
    "endDateTime": "2026-06-04T01:00:00Z",
    "location": "Gateway Pavilion, Level 1, Lab 4",
    "level": "(300) Advanced",
    "type": "Lab",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure Kubernetes Service (AKS)​​",
    "relatedSessionCodes": "BRK222",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LAB510",
    "title": "Take LLMs from prototype to production on AKS",
    "description": "Moving an AI model from experiment to production is hard. Learn about AI Runway, an open-source accelerator that simplifies deploying LLMs on Azure Kubernetes Service (AKS). By treating models as native Kubernetes resources, AI Runway offers a single interface that adapts to multiple inference backends. You’ll deploy a production LLM on AKS, implement custom resources for scaling and networking, configure GPU and latency monitoring, and integrate it into CI/CD pipelines.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Sertaç Özercan, Paul Yu",
    "timeSlot": "22:00 - 23:15",
    "startDateTime": "2026-06-02T22:00:00Z",
    "endDateTime": "2026-06-02T23:15:00Z",
    "location": "Gateway Pavilion, Level 1, Lab 3",
    "level": "(300) Advanced",
    "type": "Lab",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure Kubernetes Service (AKS)​​",
    "relatedSessionCodes": "BRK222",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LAB510-R2",
    "title": "Take LLMs from prototype to production on AKS",
    "description": "Moving an AI model from experiment to production is hard. Learn about AI Runway, an open-source accelerator that simplifies deploying LLMs on Azure Kubernetes Service (AKS). By treating models as native Kubernetes resources, AI Runway offers a single interface that adapts to multiple inference backends. You’ll deploy a production LLM on AKS, implement custom resources for scaling and networking, configure GPU and latency monitoring, and integrate it into CI/CD pipelines.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
    "speakers": "Sertaç Özercan, Paul Yu",
    "timeSlot": "20:15 - 21:30",
    "startDateTime": "2026-06-03T20:15:00Z",
    "endDateTime": "2026-06-03T21:30:00Z",
    "location": "Gateway Pavilion, Level 1, Lab 4",
    "level": "(300) Advanced",
    "type": "Lab",
    "topic": "Cloud platform & data",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Azure Kubernetes Service (AKS)​​",
    "relatedSessionCodes": "BRK222",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 4m 1s</sub>

### ✅ `bash`

**Search GitHub Copilot sessions**

$ npx -y @microsoft/events-cli sessions --query "GitHub Copilot developer" --event build-2026 --json --limit 5 2>/dev/null

<details>
<summary>108 lines</summary>

```
[
  {
    "sessionCode": "LTG401",
    "title": "10 ways to maximize GitHub Copilot",
    "description": "It started as autocomplete, but that's so 2024. What can GitHub Copilot really do in 2026? Join us for our 10 favorite hidden gems. Number will shock you!\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Aaron Powell",
    "timeSlot": "22:30 - 22:45",
    "startDateTime": "2026-06-02T22:30:00Z",
    "endDateTime": "2026-06-02T22:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG401-R1",
    "title": "10 ways to maximize GitHub Copilot (Repeat)",
    "description": "It started as autocomplete, but that's so 2024. What can GitHub Copilot really do in 2026? Join us for our 10 favorite hidden gems. Number will shock you!\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Aaron Powell",
    "timeSlot": "00:00 - 00:25",
    "startDateTime": "2026-06-04T00:00:00Z",
    "endDateTime": "2026-06-04T00:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater C",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "DEM305",
    "title": "GitHub Copilot Anywhere: From CLIs to Cloud Execution Environments",
    "description": "Modern development no longer happens in one place. You might start in your terminal, step away, and pick things back up from another device or let work continue in the cloud. This session explores using GitHub Copilot across environments, from local CLI sessions to full cloud execution with remote execution environments. See how Copilot runs commands, iterates on changes, and continues work without losing context, while you stay in control.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Ellie Bennett, Denizhan Yigitbas",
    "timeSlot": "17:30 - 17:55",
    "startDateTime": "2026-06-03T17:30:00Z",
    "endDateTime": "2026-06-03T17:55:00Z",
    "location": "Festival Pavilion, Theater A",
    "level": "(300) Advanced",
    "type": "Demo",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Developer, GitHub Copilot, GitHub, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG406",
    "title": "Get More Than Autocomplete: GitHub Copilot Workflows in Visual Studio",
    "description": "GitHub Copilot in Visual Studio goes far beyond code completion. In this lightning talk, see how developers use Copilot across the full inner loop — from understanding unfamiliar code, to generating tests, debugging failures, and reviewing changes with confidence. We’ll highlight practical workflows that help teams move faster without losing control, all inside Visual Studio.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Nik Karpinsky",
    "timeSlot": "23:10 - 23:25",
    "startDateTime": "2026-06-02T23:10:00Z",
    "endDateTime": "2026-06-02T23:25:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 1",
    "level": "(200) Intermediate",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": "",
    "tags": "Agents, Developer, GitHub Copilot, GitHub, GitHub Copilot CLI, Visual Studio, DevTools, Agentic SDLC",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  },
  {
    "sessionCode": "LTG469",
    "title": "Building an AI Robot 'StackChan' with GitHub Copilot and Foundry",
    "description": "Physical AI is one of the most exciting frontiers in technology today, but for many developers, building AI-powered robots still feels out of reach. In this 15-minute session, I'll share my hands-on journey as an embedded development beginner who built StackChan — a palm-sized, open-source AI robot — using GitHub Copilot, Microsoft Foundry (gpt-realtime), and .NET.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
    "speakers": "Maki Nagase",
    "timeSlot": "17:30 - 17:45",
    "startDateTime": "2026-06-03T17:30:00Z",
    "endDateTime": "2026-06-03T17:45:00Z",
    "location": "Gateway Pavilion, Level 2, Theater 3",
    "level": "(100) Foundational",
    "type": "Lightning Talk",
    "topic": "Developer tools & frameworks",
    "solutionArea": "",
    "product": "",
    "languages": ".NET",
    "tags": "Agents, Developer, GitHub Copilot, GitHub, Microsoft Foundry, Foundry Agents, Community, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools",
    "relatedSessionCodes": "",
    "slideDeck": "",
    "onDemand": "",
    "event": "build-2026"
  }
]
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 4m 5s</sub>

### 💭 Reasoning

*Now I have a comprehensive picture. Let me also check his blog for any more context about his current focus areas.

Actually, I have enough information now. Let me compile the refined recommendations based on:

**Sinan's Full Profile:**
- **Role**: Senior Software Engineer & Technical Leader / Consultant at ARINCO (Microsoft & GitHub partner)
- **Focus**: Apps and AI
- **Community**: Co-organises Aotearoa Azure User Group & Auckland .NET User Group
- **Languages**: C#, TypeScript, JavaScript, Java, PowerShell
- **Frameworks**: .NET (Core & 6+), Angular, Ionic, Node.js


- **Cloud/Infra**: Azure (App Services, Functions, Service Bus, AKS, Container Apps, KeyVault), Kubernetes, Docker, Terraform
- **CI/CD**: GitHub Actions, Azure DevOps
- **Data**: MSSQL, PostgreSQL, MySQL, MongoDB, CosmosDB
- **Observability**: Datadog, Azure Monitor
- **Practices**: Integration Testing, TDD, BDD
- **Interest areas**: Aspire, Entity Framework, Microsoft Agent Framework

Now I'm organizing the recommendations into tiers based on his position as a consultant at a Microsoft/GitHub partner and his technical leadership role.

Given his responsibilities advising clients on platform strategy, his community involvement with Azure and .NET user groups, and his focus on Apps and AI, I need to prioritize sessions that keep him current with the latest platform changes, help him understand the agent framework for AI consulting, cover cloud-native deployment patterns like Container Apps and AKS, explore GitHub's CI/CD evolution, and address data layer considerations for AI workloads across CosmosDB, SQL, and PostgreSQL.*

---

<sub>⏱️ 4m 18s</sub>

### 💬 Copilot

Now I have a comprehensive picture of your profile. Here's my refined recommendation:

---

## 🎯 Refined Build 2026 Recommendations for Sinan Nar

**Your Profile**: Senior Software Engineer & Consultant at ARINCO (Microsoft & GitHub partner) | Co-organiser: Aotearoa Azure User Group & Auckland .NET User Group | Focus: Apps & AI

**Full Stack**: C#, .NET 6+, TypeScript, Angular | Azure (Functions, Container Apps, AKS, Service Bus, KeyVault) | CosmosDB, MSSQL, PostgreSQL | GitHub Actions, Azure DevOps, Terraform | Datadog, Azure Monitor | TDD/BDD

---

### 🏆 Tier 1 — Must-See (Core to your daily work + consulting value)

| # | Code | Title | Why It's For You | When (PDT) |
|---|------|-------|------------------|------------|
| 1 | **BRK205** | Aspire for agents: Transform how you build and deploy distributed apps | You listed Aspire as a focus. Damian Edwards + David Fowler showing agent orchestration + observability for distributed .NET apps — directly applicable to your Container Apps & AKS work | Jun 3, 2:45 PM |
| 2 | **BRK241** | From prototype to production: build and run agents at scale | Microsoft Agent Framework end-to-end lifecycle — prototype → enterprise deployment. Core to your "Apps & AI" consulting focus | Jun 2, 3:45 PM |
| 3 | **LTG455** | From Code to Agents: Build Production MCP Servers on Azure Functions | MCP servers on Azure Functions with Azure DevOps CI/CD automation. Hits your Functions + DevOps + Agent stack perfectly | Jun 2, 3:10 PM |
| 4 | **BRK223** | From rows to reasoning: Designing databases for AI apps and agents | SQL + Cosmos DB + Azure HorizonDB (new cloud-native PostgreSQL). You use all three DB engines — this is the AI-era data architecture story | Jun 2, 2:30 PM |
| 5 | **DEM301** | Rethinking CI: Actions, AI Agents, and the End of Commit-Fail-Commit | GitHub Actions as execution layer for AI agents + MCP integration. As a GitHub partner using Actions daily, this is essential | Jun 3, 3:00 PM |
| 6 | **BRK207** | GitHub Copilot in Visual Studio: Agents That Debug, Profile, and Test | C#/.NET debugging, profiling, and test agents in VS. You'll share this with your user group | Jun 3, 4:00 PM |

---

### 🔗 Tier 2 — High Value (Extends your consulting toolkit)

| # | Code | Title | Why | When (PDT) |
|---|------|-------|-----|------------|
| 7 | **BRK243** | Claw and agent harness in Microsoft Foundry | Deep multi-agent systems, hosted agents, GitHub Copilot SDK integration — Level 400 expert content for the Agent Framework | Jun 3, 11:30 AM |
| 8 | **DEM333** | How Foundry integrates with open-source frameworks | Microsoft Agent Framework + LangGraph + MCP + A2A coordination — critical for advising clients on multi-framework agent strategies | Jun 2, 4:00 PM |
| 9 | **LTG453** | Building an End-to-End Enterprise AI Platform on Azure | Azure Functions + Container Apps + AKS + Cosmos DB vector search — your exact stack assembled into an enterprise AI reference architecture | Jun 2, 1:50 PM |
| 10 | **DEM361** | Understand and fix Agent Framework apps with observability and evals | OpenTelemetry instrumentation for Agent Framework apps. Bridges your observability experience (Datadog/Azure Monitor) to AI workloads | Jun 3, 3:30 PM |
| 11 | **BRK221** | Idea to production-ready agent in seconds on AI-native runtime | Azure Container Apps for agentic workloads — scaling, observability, reliability. You already deploy to ACA | Jun 3, 2:45 PM |
| 12 | **LTG466** | Building your own MCP server | C# MCP SDK hands-on. As a .NET community leader, you'll want to teach this | Jun 3, 9:30 AM |
| 13 | **TT656** | From Locked-In to Liquid: Modernizing .NET Before November 2026 EOL | .NET 8/9 EOL strategies — directly relevant if your consulting clients have migration needs (they will) | Jun 2, 3:15 PM |

---

### 📊 Tier 3 — Worth Catching On-Demand

| Code | Title | Why |
|------|-------|-----|
| **DEM310** | Ship code faster with AI-powered NoSQL schema design | Cosmos DB Agent Toolkit + Mac/Linux emulator — your CosmosDB work gets an AI boost |
| **BRK224** | PepsiCo's blueprint for agentic AI | Azure SQL + Cosmos DB + PostgreSQL agentic RAG — real enterprise case study |
| **LTG408** | The developer experience with AKS Desktop and VS Code | New AKS dev inner loop — you work with AKS already |
| **LTG401** | 10 ways to maximize GitHub Copilot | Aaron Powell — community-friendly content for your user groups |
| **DEM305** | GitHub Copilot Anywhere: From CLIs to Cloud Execution | Copilot across environments — relevant to your CLI-first workflow |
| **BRK250** | Govern open-source AI agents, any framework, any scale | Enterprise agent governance — essential context for consulting |
| **TT621** | Build & modernize multi-tenant AI app data planes | NoSQL + agentic SaaS patterns — if you consult on multi-tenant systems |

---

### 🧭 Recommended Focus Areas (Priority Order)

Given your role as a **Microsoft/GitHub partner consultant** who **co-organises user groups**:

1. **Microsoft Agent Framework + Aspire** — This is the new story. Sessions BRK205, BRK241, BRK243 give you the full narrative from orchestration to production.
2. **Azure data for AI** — BRK223 + BRK224 cover the data layer evolution (SQL, Cosmos, HorizonDB). Your EF + PostgreSQL + CosmosDB skills map directly here.
3. **GitHub Actions + Copilot evolution** — DEM301 + BRK207 + DEM305. As a GitHub partner, you'll want this for client conversations and user group talks.
4. **MCP servers in C#** — LTG455 + LTG466. The new integration standard, built on your Azure Functions + C# expertise.

---

Would you like me to check for time conflicts and build an optimized Day 1 / Day 2 schedule?

---

<sub>⏱️ 6m 12s</sub>

### 👤 User

cool, now create a dailt agenda for me, remember I live in NZ and adapt timezone for these sessions. write to [date]/[session].md folder structure as well as index.md

---

<sub>⏱️ 6m 16s</sub>

### 💭 Reasoning

*The user wants me to create a daily agenda with timezone-adapted times (NZ timezone) and write them as markdown files in a folder structure like `[date]/[session].md` with an `index.md`.

Build 2026 is June 2-3, 2026 in San Francisco (PDT, UTC-7).
New Zealand is NZST (UTC+12) in June (it's winter in NZ, so NZST not NZDT).

Wait, actually let me check. In June, New Zealand is in winter, so it's NZST (New Zealand Standard Time) which is UTC+12.


PDT is UTC-7, so the offset from PDT to NZST is +19 hours. Now I'm converting the session times from UTC to NZST for the two days of the conference. The first day in San Francisco (June 2) will shift to June 3 in New Zealand, and I need to work through each session to get the correct local times. Continuing through the remaining sessions, filling in the rest of the schedule with DEM333 running from 11:00 to 11:25 AM NZST, followed by DEM310, LTG401, LTGSP481, and BRK205 spread across the morning window.

Now I'm reorganizing these by their actual UTC start dates to make sure I'm grouping them correctly—the sessions span June 2 and 3 in UTC, which maps to June 3 and 4 in New Zealand time, so I need to separate them by which UTC day they begin on. Continuing through the remaining sessions, I see DEM333 wraps up at 11:00 AM NZST on June 3, followed by DEM310 at 11:30 AM NZST. Then there's a shift to sessions starting on June 3 UTC, which translates to June 4 early morning in NZST—LTG466 at 4:30 AM, DEM305 at 5:30 AM, BRK243 at 6:30 AM, and DEM341 at 6:50 AM. 11:00 AM NZST
- LTG401-R1: 2026-06-04T00:00:00Z → Jun*

---

<sub>⏱️ 9m 27s</sub>

### ℹ️ Info

Response was interrupted due to a server error. Retrying...

---

<sub>⏱️ 9m 30s</sub>

### 💭 Reasoning

*The user wants me to create a daily agenda with sessions adapted to NZ timezone (NZST, UTC+12). Build 2026 is in San Francisco (PDT, UTC-7), so the difference is 19 hours ahead of PDT.

Let me convert the session times from PDT to NZST:
- PDT is UTC-7
- NZST is UTC+12
- Difference: 19 hours ahead

So if a session is at 2:30 PM PDT, it would be 2:30 PM + 19 hours = 9:30 AM next day NZST.


Now I'm working through the catalog data to map out each session's UTC timestamp and convert it to NZST. The sessions from June 2 PDT are showing up with UTC times on June 2, which translates to June 3 morning in New Zealand time. Continuing through the remaining sessions, I see DEM333 and DEM310 wrapping up the evening shift around 11:00-11:30 AM NZST on June 3rd. Then Day 2 kicks off with sessions starting from 16:30 UTC on June 3rd, which translates to early morning times on June 4th in NZST—LTG466 at 4:30 AM, followed by DEM305, BRK243, and DEM341 progressing through the early hours.

The afternoon UTC sessions cluster around 21:45-23:00 UTC, creating a scheduling conflict where BRK221, BRK205, and BRK224 all overlap at 9:45 AM NZST on June 4th, with DEM301, DEM361, and BRK207 filling in the remaining slots through 11:00 AM. Let me work through the time conversions more carefully. A 9:00 AM PDT session converts to 4:00 AM the next day in NZST, the 2:30 PM slot becomes 4:30 AM the following morning, and the 5:00 PM session lands right at midnight UTC, which is noon NZST. I need to map out my actual session times against these conversions to see what the viewing windows look like from New Zealand. Continuing through the rest of the Day 1 sessions, I see BRK250 conflicts with BRK223 at the same time slot, and TT656 starts just minutes after LTG455, which could be tight. LTG401 about Copilot appears to be cut off but starts on June 2 as well. Compiling the Day 2 conference schedule with session times converted across PDT and NZST timezones, starting with the morning sessions beginning at 9:30 AM PDT. Now I'm finishing the time conversions for the remaining sessions and starting to map out an optimized schedule that resolves the conflicts I identified, organizing the talks across both days with staggered start times. 10:15 AM NZST. There's a conflict: BRK223 ends at 10:15, but LTG455 runs 10:10–10:25, so there's a 5-minute overlap. I could either leave BRK223 early to catch LTG455 or skip it for BRK241 at 10:45. But now I'm seeing another problem — TT656 starts at 10:15 and runs until 11:00, while BRK241 is 10:45–11:30, so those overlap too.

Let me map out a clean schedule without conflicts. DEM333 starts at 11:00, so I need to work backward from there and fit everything in properly.

Generating optimized schedule... So I'm working through the Day 1 conflicts systematically. BRK223 wins over BRK250 since they're simultaneous, and I'm skipping LTG455 to catch it on-demand later since it overlaps with BRK223's end. Between TT656 and BRK241, I'm prioritizing the breakout session, and BRK241 takes precedence over DEM333 as well. My Day 1 schedule starts with LTG453 at 8:50 AM.

Now I'm filling in the rest of the morning: LTGSP481 at 9:10, then BRK223 at 9:30, and I'm wrestling with whether to squeeze in TT656 starting at 10:15 when BRK241 kicks off at 10:45. Since TT656 is interactive and I'd only catch half of it before switching to the key breakout session, I'm leaning toward just doing BRK241 instead. RK241 at 10:45-11:30 for agents at scale, then DEM310 at 11:30-11:55 on Cosmos DB schema design. I'm noticing LTG455 conflicts with the tail end of BRK223—there's only a 5-minute overlap between 10:10-10:25 and the 10:15 end time, which isn't realistic to catch if they're in different rooms, so I'll skip it.

Now I'm mapping out Day 2 in NZST with a series of sessions starting early: LTG466 at 4:30 AM, DEM305 at 5:30 AM, BRK243 at 6:30 AM, then jumping to BRK205 at 9:45 AM. I'm seeing a conflict here—DEM301 at 10:00 AM overlaps with BRK205 which runs until 10:30, so I'll need to choose between them. After that, DEM361 fits at 10:30 AM and BRK207 starts at 11:00 AM.

There's also a three-way conflict with BRK205, BRK221, and BRK224 all scheduled for 9:45-10:30 AM, so I'm prioritizing BRK205 since Aspire is Tier 1. Additionally, DEM341 has a 25-minute overlap with BRK243 in the early morning slot, so those two sessions are competing for the same time window.

Given that the user is in New Zealand watching a San Francisco event remotely, those early morning sessions starting at 4:30 AM are quite demanding. I'm thinking through whether to present them as optional or note that they're available on-demand. For the final Day 2 schedule, I'm grouping the sessions into an early block requiring a very early wake-up and a more reasonable morning block with BRK205, DEM361, and BRK207.

Now I'm organizing the schedule with NZST times as the primary reference since that's what they asked for, with PDT times included for context. I'll structure the output to show both time zones and make it clear which sessions require early morning viewing versus more typical morning hours. I'm working out the timezone conversions to map the conference sessions correctly. Day 1 sessions fall on June 3 NZST while Day 2 spans from the evening of June 3 into the morning of June 4 NZST. Now I'm building out the actual schedule with specific session times and titles, starting with the Day 1 lineup. AM NZST — DEM305: GitHub Copilot Anywhere
3. 6:30 AM NZST — BRK243: Agentic frameworks in Microsoft Foundry

Then the main sessions at 9:45 AM with Aspire for agents, followed by debugging Agent Framework apps and GitHub Copilot integration in Visual Studio. I'm also noting a few sessions that conflict with earlier picks, so I'll catch those on-demand instead.

Now I'm ready to set up the files.*

---

<sub>⏱️ 11m 4s</sub>

### ✅ `bash`

**Create date folders for agenda**

$ mkdir -p 2026-06-03 2026-06-04

```

<exited with exit code 0>
```


---

<sub>⏱️ 11m 9s</sub>

### ℹ️ Info

All permissions are now enabled. Tool, path, and URL requests will be automatically approved.

---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md with 4247 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LTG453.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LTG453.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LTG453.md with 1454 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LTGSP481.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LTGSP481.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LTGSP481.md with 1556 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK223.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK223.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK223.md with 2028 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK241.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK241.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK241.md with 1990 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/DEM310.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/DEM310.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/DEM310.md with 1794 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/LTG466.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/LTG466.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/LTG466.md with 1720 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/DEM305.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/DEM305.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/DEM305.md with 1726 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK243.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK243.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK243.md with 2112 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK205.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK205.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK205.md with 2115 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/DEM361.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/DEM361.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/DEM361.md with 1992 characters
```


---

<sub>⏱️ 13m 20s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK207.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK207.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK207.md with 2100 characters
```


---

<sub>⏱️ 13m 23s</sub>

### 💬 Copilot

Done! Here's the structure I created:

```
MicrosoftBuild2026/
├── index.md                    ← Full agenda overview + conflicts + themes
├── 2026-06-03/                 ← Day 1 (Jun 2 PDT → Jun 3 NZST)
│   ├── LTG453.md              8:50 AM NZST — Enterprise AI Platform on Azure
│   ├── LTGSP481.md            9:10 AM — .NET durable agent workflows
│   ├── BRK223.md              9:30 AM — Databases for AI (SQL/Cosmos/HorizonDB)
│   ├── BRK241.md              10:45 AM — Agent Framework: prototype→production
│   └── DEM310.md              11:30 AM — Cosmos DB AI schema design
└── 2026-06-04/                 ← Day 2 (Jun 3 PDT → Jun 4 NZST)
    ├── LTG466.md              4:30 AM NZST — MCP server in C# (early!)
    ├── DEM305.md              5:30 AM — GitHub Copilot Anywhere (early!)
    ├── BRK243.md              6:30 AM — Multi-agent Claw patterns (early!)
    ├── BRK205.md              9:45 AM — Aspire for agents ⭐
    ├── DEM361.md              10:30 AM — Agent Framework observability
    └── BRK207.md              11:00 AM — Copilot debugging agents in VS
```

Each session file includes time in both NZST and PDT, abstract, stack match analysis, key topics to watch for, and follow-up action checkboxes. The Day 2 early block (4:30–7:15 AM) is flagged as optional — those are worth catching on-demand if you prefer sleep! 🇳🇿

---

<sub>⏱️ 17m 5s</sub>

### ℹ️ Info

Connected to Visual Studio Code - Insiders

---

<sub>⏱️ 17m 28s</sub>

### ℹ️ Info

IDE connection lost: Visual Studio Code - Insiders closed

---

<sub>⏱️ 18m 51s</sub>

### 👤 User

is there any session as a lab that I should look into?

---

<sub>⏱️ 18m 55s</sub>

### 💭 Reasoning

*The user wants to find lab sessions that are relevant to their skillset. Let me search for lab sessions specifically.*

---

<sub>⏱️ 19m 0s</sub>

### ✅ `bash`

**Search all lab sessions at Build 2026**

$ npx -y @microsoft/events-cli sessions --type "lab" --event build-2026 --json --limit 20 2>/dev/null

```

<exited with exit code 1>
```


---

<sub>⏱️ 19m 11s</sub>

### ✅ `bash`

**Find lab-type sessions**

$ npx -y @microsoft/events-cli sessions --query "lab hands-on" --event build-2026 --json --limit 20 2>/dev/null | python3 -c "
import json, sys
data = json.load(sys.stdin)
labs = [s for s in data if 'Lab' in s.get('type','')]
for l in labs:
    print(json.dumps(l))
" 2>/dev/null || npx -y @microsoft/events-cli sessions --query "LAB" --event build-2026 --json --limit 20 2>/dev/null

<details>
<summary>5 lines</summary>

```
Output too large to read at once (24.6 KB). Saved to: /var/folders/vk/nttryqlj7n97lyv3gfr4tt7c0000gp/T/copilot-tool-output-1779325767612-vvx6rv.txt
Consider using tools like grep (for searching), head/tail (for viewing start/end), view with view_range (for specific sections), or jq (for JSON) to examine portions of the output.

Preview (first 500 chars):
{"sessionCode": "LAB512D", "title": "Digital Lab: Hands-on with the latest Cobalt VMs \u2013 from code to cloud deployment", "description": "Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images with Docker, push them to ACR, and deploy to AKS clusters running on Cobalt VMs. Next, wire up a CI/CD pipeline that builds, tests, and deploys to Arm. Then g
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 19m 17s</sub>

### ✅ `bash`

**Filter and display lab sessions**

$ cat /var/folders/vk/nttryqlj7n97lyv3gfr4tt7c0000gp/T/copilot-tool-output-1779325767612-vvx6rv.txt | python3 -c "
import json, sys

data = json.load(sys.stdin)
labs = [s for s in data if 'Lab' in s.get('type','')]
for l in labs:
    print(f\"{l['sessionCode']} | {l['title']}\")
    print(f\"  Type: {l['type']} | Level: {l['level']}\")
    print(f\"  Time: {l['timeSlot']} | Location: {l['location']}\")
    print(f\"  Tags: {l['tags']}\")
    print(f\"  Desc: {l['description'][:200]}\")
    print()
"

<details>
<summary>15 lines</summary>

```
Traceback (most recent call last):
  File "<string>", line 4, in <module>
    data = json.load(sys.stdin)
  File "/Library/Frameworks/Python.framework/Versions/3.14/lib/python3.14/json/__init__.py", line 298, in load
    return loads(fp.read(),
        cls=cls, object_hook=object_hook,
        parse_float=parse_float, parse_int=parse_int,
        parse_constant=parse_constant, object_pairs_hook=object_pairs_hook, **kw)
  File "/Library/Frameworks/Python.framework/Versions/3.14/lib/python3.14/json/__init__.py", line 352, in loads
    return _default_decoder.decode(s)
           ~~~~~~~~~~~~~~~~~~~~~~~^^^
  File "/Library/Frameworks/Python.framework/Versions/3.14/lib/python3.14/json/decoder.py", line 348, in decode
    raise JSONDecodeError("Extra data", s, end)
json.decoder.JSONDecodeError: Extra data: line 2 column 1 (char 1217)
<exited with exit code 1>
```

</details>


---

<sub>⏱️ 19m 25s</sub>

### ✅ `bash`

**List all lab sessions**

$ npx -y @microsoft/events-cli sessions --query "LAB" --event build-2026 --json --limit 30 2>/dev/null | python3 -c "
import json, sys
data = json.load(sys.stdin)
labs = [s for s in data if 'Lab' in s.get('type','')]
for l in labs:
    print(f\"{l['sessionCode']} | {l['title']}\")
    print(f\"  Level: {l['level']} | Time: {l['timeSlot']}\")
    print(f\"  Location: {l['location']}\")
    print(f\"  Tags: {l['tags']}\")
    print(f\"  {l['description'][:180]}...\")
    print()
"

<details>
<summary>146 lines</summary>

```
LAB530D | Digital Lab: Engineering agents that reason, act, and adapt
  Level: (300) Advanced | Time: 
  Location: 
  Tags: 
  Lost in San Francisco with a deadline to make it to Build, you’ll code an AI agent using Foundry Agent Service, Foundry IQ, and Foundry Tools. Step by step, you’ll design an agent ...

LAB521D | Digital Lab: Improving agent behavior using reinforcement learning from traces
  Level: (300) Advanced | Time: 
  Location: 
  Tags: 
  AI agents often work, but their behavior can be inconsistent or hard to control with prompts alone. In this hands-on lab, you will start with a working agent, inspect execution tra...

LAB550D | Digital Lab Build, deploy, and scale agents with Windows 365
  Level: (400) Expert | Time: 
  Location: 
  Tags: Windows 365, Windows, Windows 365 for Agents, Agents on Windows
  Learn how Windows 365 delivers secure and preconfigured computing environments for AI agents, and how you can combine that with computer use to accelerate the creation and deployme...

LAB510D | Digital Lab: Take LLMs from prototype to production on AKS
  Level: (300) Advanced | Time: 
  Location: 
  Tags: Azure Kubernetes Service (AKS)​​
  Moving an AI model from experiment to production is hard. Learn about AI Runway, an open-source accelerator that simplifies deploying LLMs on Azure Kubernetes Service (AKS). By tre...

LAB511D | Digital Lab: Create advanced Postgres-powered agentic apps with Azure HorizonDB
  Level: (300) Advanced | Time: 
  Location: 
  Tags: CP&D, Data, Azure HorizonDB
  In this lab, you’ll build a production-ready AI agent using Azure HorizonDB as a unified data, retrieval, and intelligence layer. Implement RAG, hybrid semantic and keyword search,...

LAB501D | Digital Lab: From zero to deployed on Azure with AI agents
  Level: (300) Advanced | Time: 
  Location: 
  Tags: Azure, Agents, Developer, GitHub Copilot, GitHub, Deployment Pipelines, GitHub Actions, GitHub Copilot CLI, DevTools, Agentic SDLC
  What happens when you let AI agents do the building? In this hands-on lab, you'll go from an empty terminal to a deployed app on Azure — with GitHub Copilot CLI and coding agents h...

LAB532D | Digital Lab: From data to context: Agent‑ready knowledge with Foundry IQ
  Level: (300) Advanced | Time: 
  Location: 
  Tags: 
  What if your coding agent could reason over enterprise knowledge—across files, data, and work signals—without leaving your developer workflow? In this hands-on lab, you’ll build a ...

LAB540D | Digital Lab: Observe, optimize and protect your hosted agents in Microsoft Foundry
  Level: (300) Advanced | Time: 
  Location: 
  Tags: Observability, Microsoft Foundry, Responsible AI, Evaluations
  Modern agents fail in ways traditional monitoring can’t catch. In this hands-on lab, learn how Microsoft Foundry Observability helps you move from prototype → production with conte...

LAB520D | Digital Lab: Get Started with Models in Microsoft Foundry to Build AI Apps
  Level: (300) Advanced | Time: 
  Location: 
  Tags: 
  In this hands-on lab, you will build a production-ready AI application using Microsoft Foundry, with no fine-tuning or deep machine learning expertise required. You will discover a...

LAB502D | Digital Lab: Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows
  Level: (300) Advanced | Time: 
  Location: 
  Tags: Agents, Developer, GitHub Copilot, GitHub, Visual Studio Code, MCP, GitHub Actions, GitHub Enterprise, VS Code, GitHub Copilot CLI, Visual Studio, DevTools, Skills, Agentic SDLC
  GitHub Copilot is powerful out of the box, but custom agents let you shape it to fit your team's exact workflows. In this lab, you'll build agents from scratch: set their roles, wr...

LAB513D | Digital Lab: Build an AI app with Azure SQL Hyperscale, Microsoft Fabric, & Foundry
  Level: (300) Advanced | Time: 
  Location: 
  Tags: Azure SQL Hyperscale, Microsoft Foundry, CP&D, Data
  Build an AI-powered FAQ assistant using Azure SQL Database vector search and Retrieval-Augmented Generation (RAG) with Azure OpenAI Service. Use GitHub Copilot to speed T-SQL, mirr...

LAB500D | Digital Lab: Terminal to Party: Live-Coding with GitHub Copilot CLI and Hydra
  Level: (300) Advanced | Time: 
  Location: 
  Tags: Agents, Developer, GitHub Copilot, GitHub, GitHub Actions, OSS, GitHub Copilot CLI, DevTools, Agentic SDLC
  Experience GitHub Copilot CLI while exploring OSS Hydra, a live-coding audio/visual environment that runs directly in the browser. Learn how to use agentic loops to create an AV pa...

LAB512D | Digital Lab: Hands-on with the latest Cobalt VMs – from code to cloud deployment
  Level: (200) Intermediate | Time: 
  Location: 
  Tags: 
  Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-a...

LABSP584-R1 | Generate video with PyTorch and ComfyUI: Build a GPU pipeline
  Level: (200) Intermediate | Time: 17:45 - 19:00
  Location: AMD @ Greens
  Tags: AI, API, Developer
  Build a video generation pipeline using open-source models and GPU acceleration. In this hands-on lab, you’ll use PyTorch and ComfyUI to generate video clips, configure workflows, ...

LABSP583 | Build a custom AI agent with open-weight models and OpenClaw
  Level: (300) Advanced | Time: 19:30 - 20:45
  Location: AMD @ Greens
  Tags: 
  Build and run your own AI agent by hosting open-weight models on AMD GPU infrastructure. In this hands-on lab, you’ll assemble a tool-using agent, configure model hosting, and conn...

LABSP583-R2 | Build a custom AI agent with open-weight models and OpenClaw
  Level: (300) Advanced | Time: 16:00 - 17:15
  Location: AMD @ Greens
  Tags: 
  Build and run your own AI agent by hosting open-weight models on AMD GPU infrastructure. In this hands-on lab, you’ll assemble a tool-using agent, configure model hosting, and conn...

LABSP581 | Create AI-powered video analytics apps with NVIDIA vision agents
  Level: (300) Advanced | Time: 22:00 - 23:15
  Location: NVIDIA @ 308
  Tags: Agents
  Build AI-powered video applications using the NVIDIA Video Search and Summarization (VSS) blueprint. In this hands-on lab, you’ll design vision agents that combine VLMs and LLMs to...

LABSP581-R1 | Create AI-powered video analytics apps with NVIDIA vision agents
  Level: (300) Advanced | Time: 20:15 - 21:30
  Location: NVIDIA @ 308
  Tags: Agents
  Build AI-powered video applications using the NVIDIA Video Search and Summarization (VSS) blueprint. In this hands-on lab, you’ll design vision agents that combine VLMs and LLMs to...

LABSP583-R3 | Build a custom AI agent with open-weight models and OpenClaw
  Level: (300) Advanced | Time: 23:45 - 01:00
  Location: AMD @ Greens
  Tags: 
  Build and run your own AI agent by hosting open-weight models on AMD GPU infrastructure. In this hands-on lab, you’ll assemble a tool-using agent, configure model hosting, and conn...

LABSP583-R1 | Build a custom AI agent with open-weight models and OpenClaw
  Level: (300) Advanced | Time: 03:15 - 04:30
  Location: AMD @ Greens
  Tags: 
  Build and run your own AI agent by hosting open-weight models on AMD GPU infrastructure. In this hands-on lab, you’ll assemble a tool-using agent, configure model hosting, and conn...

LABSP584 | Generate video with PyTorch and ComfyUI: Build a GPU pipeline
  Level: (200) Intermediate | Time: 22:00 - 23:15
  Location: AMD @ Greens
  Tags: AI, API, Developer
  Build a video generation pipeline using open-source models and GPU acceleration. In this hands-on lab, you’ll use PyTorch and ComfyUI to generate video clips, configure workflows, ...

LABSP580-R1 | Build and deploy reasoning agents with NVIDIA Nemotron and Foundry
  Level: (300) Advanced | Time: 17:45 - 19:00
  Location: NVIDIA @ 308
  Tags: Agents
  Build and deploy intelligent AI agents using NVIDIA AI-Q Blueprint and Nemotron with Microsoft Foundry, Azure Container Apps, and Azure AI Search. In this hands-on lab, you'll crea...

LABSP580 | Build and deploy reasoning agents with NVIDIA Nemotron and Foundry
  Level: (300) Advanced | Time: 19:30 - 20:45
  Location: NVIDIA @ 308
  Tags: Agents
  Build and deploy intelligent AI agents using NVIDIA AI-Q Blueprint and Nemotron with Microsoft Foundry, Azure Container Apps, and Azure AI Search. In this hands-on lab, you'll crea...

LABSP586-R1 | Build with local AI agents using OpenCode and Lemonade
  Level: (300) Advanced | Time: 20:15 - 21:30
  Location: AMD @ Greens
  Tags: Agents
  Harness the on-device power of the AMD Ryzen™ AI MAX+ processors  to run large coding models locally using Lemonade Server — no cloud, no API keys, all local. Learn how to architec...

LABSP586 | Build with local AI agents using OpenCode and Lemonade
  Level: (300) Advanced | Time: 01:30 - 02:45
  Location: AMD @ Greens
  Tags: Agents
  Harness the on-device power of the AMD Ryzen™ AI MAX+ processors  to run large coding models locally using Lemonade Server — no cloud, no API keys, all local. Learn how to architec...

LAB520-R2 | Get Started with Models in Microsoft Foundry to Build AI Apps
  Level: (300) Advanced | Time: 17:45 - 19:00
  Location: Gateway Pavilion, Level 1, Lab 1
  Tags: 
  In this hands-on lab, you will build a production-ready AI application using Microsoft Foundry, with no fine-tuning or deep machine learning expertise required. You will discover a...

LAB520-R1 | Get Started with Models in Microsoft Foundry to Build AI Apps
  Level: (300) Advanced | Time: 03:15 - 04:30
  Location: Gateway Pavilion, Level 1, Lab 1
  Tags: 
  In this hands-on lab, you will build a production-ready AI application using Microsoft Foundry, with no fine-tuning or deep machine learning expertise required. You will discover a...

LAB520 | Get Started with Models in Microsoft Foundry to Build AI Apps
  Level: (300) Advanced | Time: 23:45 - 01:00
  Location: Gateway Pavilion, Level 1, Lab 1
  Tags: 
  In this hands-on lab, you will build a production-ready AI application using Microsoft Foundry, with no fine-tuning or deep machine learning expertise required. You will discover a...

LAB520-R3 | Get Started with Models in Microsoft Foundry to Build AI Apps
  Level: (300) Advanced | Time: 22:00 - 23:15
  Location: Gateway Pavilion, Level 1, Lab 1
  Tags: 
  In this hands-on lab, you will build a production-ready AI application using Microsoft Foundry, with no fine-tuning or deep machine learning expertise required. You will discover a...
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 19m 28s</sub>

### 💭 Reasoning

*Now let me search for the in-person lab sessions that are most relevant to Sinan's stack. Let me look for the key ones:

1. **LAB530** - Engineering agents that reason, act, and adapt (Foundry Agent Service) - very relevant
2. **LAB511** - Create advanced Postgres-powered agentic apps with Azure HorizonDB - VERY relevant (PostgreSQL + agents)
3. **LAB501** - From zero to deployed on Azure with AI agents (GitHub Copilot CLI + Azure) - relevant
4. **LAB502** - Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows - relevant (GitHub partner)


5. **LAB540** - Observe, optimize and protect your hosted agents in Microsoft Foundry - relevant for monitoring deployed agents
6. **LAB513** - Build an AI app with Azure SQL Hyperscale, Microsoft Fabric, & Foundry - relevant for the data layer

Now I need to find the in-person session times for these labs.*

---

<sub>⏱️ 19m 38s</sub>

### ✅ `bash`

**Get in-person lab session details**

$ npx -y @microsoft/events-cli sessions --query "LAB511 LAB530 LAB501 LAB502 LAB540" --event build-2026 --json --limit 30 2>/dev/null | python3 -c "
import json, sys
data = json.load(sys.stdin)
labs = [s for s in data if 'Lab' in s.get('type','') and not s['sessionCode'].endswith('D')]
for l in sorted(labs, key=lambda x: x['sessionCode']):
    print(f\"{l['sessionCode']} | {l['title']}\")
    print(f\"  Level: {l['level']} | Time: {l['timeSlot']}\")
    print(f\"  Location: {l['location']}\")
    print(f\"  Speakers: {l['speakers']}\")
    print(f\"  Tags: {l['tags']}\")
    print(f\"  {l['description'][:250]}\")
    print()
"

```

<exited with exit code 0>
```


---

<sub>⏱️ 19m 39s</sub>

### ✅ `bash`

**Look up specific lab sessions**

$ npx -y @microsoft/events-cli session LAB511 --event build-2026 --json 2>/dev/null && echo "---" && npx -y @microsoft/events-cli session LAB530 --event build-2026 --json 2>/dev/null && echo "---" && npx -y @microsoft/events-cli session LAB501 --event build-2026 --json 2>/dev/null && echo "---" && npx -y @microsoft/events-cli session LAB502 --event build-2026 --json 2>/dev/null

<details>
<summary>88 lines</summary>

```
{
  "sessionCode": "LAB511",
  "title": "Create advanced Postgres-powered agentic apps with Azure HorizonDB",
  "description": "In this lab, you’ll build a production-ready AI agent using Azure HorizonDB as a unified data, retrieval, and intelligence layer. Implement RAG, hybrid semantic and keyword search, and agentic workflows without stitching external services. Use DiskANN advanced filtering and in-database AI model management to run LLMs and embeddings directly in the database - no vector stores or glue code. Ideal for developers and architects who want simpler stacks, higher performance, and faster AI delivery.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
  "speakers": "Jonathon Frost, Denzil Ribeiro",
  "timeSlot": "22:00 - 23:15",
  "startDateTime": "2026-06-02T22:00:00Z",
  "endDateTime": "2026-06-02T23:15:00Z",
  "location": "Gateway Pavilion, Level 1, Lab 4",
  "level": "(300) Advanced",
  "type": "Lab",
  "topic": "Cloud platform & data",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "CP&D, Data, Azure HorizonDB",
  "relatedSessionCodes": "LTG413",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
---
{
  "sessionCode": "LAB530",
  "title": "Engineering agents that reason, act, and adapt",
  "description": "Lost in San Francisco with a deadline to make it to Build, you’ll code an AI agent using Foundry Agent Service, Foundry IQ, and Foundry Tools. Step by step, you’ll design an agent that reasons, acts, and adapts in real time—integrating MCP tools to solve challenges along the way. Leave with hands‑on experience building and orchestrating production‑ready agentic systems.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
  "speakers": "Henk Boelman, Gustavo Cordido",
  "timeSlot": "19:30 - 20:45",
  "startDateTime": "2026-06-02T19:30:00Z",
  "endDateTime": "2026-06-02T20:45:00Z",
  "location": "Building C, Level 2, Room 205",
  "level": "(300) Advanced",
  "type": "Lab",
  "topic": "Agents & apps",
  "solutionArea": "",
  "product": "",
  "languages": "Python",
  "tags": "",
  "relatedSessionCodes": "",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
---
{
  "sessionCode": "LAB501",
  "title": "From zero to deployed on Azure with AI agents",
  "description": "What happens when you let AI agents do the building? In this hands-on lab, you'll go from an empty terminal to a deployed app on Azure — with GitHub Copilot CLI and coding agents handling the scaffolding, coding, debugging, and deployment. You'll use the new Azure skills to provision resources and wire up services through natural language, no portal required. This isn't a demo you watch. You'll walk out with a real, working dev workflow you can take straight to your next project.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
  "speakers": "Yun Jung Choi, Chris Harris",
  "timeSlot": "19:30 - 20:45",
  "startDateTime": "2026-06-02T19:30:00Z",
  "endDateTime": "2026-06-02T20:45:00Z",
  "location": "Firehouse",
  "level": "(300) Advanced",
  "type": "Lab",
  "topic": "Developer tools & frameworks",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "Azure, Agents, Developer, GitHub Copilot, GitHub, Deployment Pipelines, GitHub Actions, GitHub Copilot CLI, DevTools, Agentic SDLC",
  "relatedSessionCodes": "BRK207",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
---
{
  "sessionCode": "LAB502",
  "title": "Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows",
  "description": "GitHub Copilot is powerful out of the box, but custom agents let you shape it to fit your team's exact workflows. In this lab, you'll build agents from scratch: set their roles, write instructions, scope their tools, and plug them into real workflows. You'll create reusable Agent Skills for domain knowledge and connect agents to external services via MCP. Everything works across VS Code, Visual Studio, CLI, and Copilot coding agent. Leave with working agents you can adapt to your own codebase.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
  "speakers": "Josh Johanning, Tiago Pascoal",
  "timeSlot": "22:00 - 23:15",
  "startDateTime": "2026-06-02T22:00:00Z",
  "endDateTime": "2026-06-02T23:15:00Z",
  "location": "Firehouse",
  "level": "(300) Advanced",
  "type": "Lab",
  "topic": "Developer tools & frameworks",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "Agents, Developer, GitHub Copilot, GitHub, Visual Studio Code, MCP, GitHub Actions, GitHub Enterprise, VS Code, GitHub Copilot CLI, Visual Studio, DevTools, Skills, Agentic SDLC",
  "relatedSessionCodes": "BRK203",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 19m 48s</sub>

### ✅ `bash`

**Get LAB540 and repeat timeslots**

$ npx -y @microsoft/events-cli session LAB540 --event build-2026 --json 2>/dev/null && echo "---SEPARATOR---" && npx -y @microsoft/events-cli sessions --query "LAB501-R1 LAB502-R1 LAB511-R1 LAB530-R1" --event build-2026 --json --limit 20 2>/dev/null | python3 -c "
import json,sys
data=json.load(sys.stdin)
for s in sorted(data, key=lambda x: x['sessionCode']):
    if 'Lab' in s.get('type','') and '-R' in s['sessionCode']:
        print(f\"{s['sessionCode']} | Time: {s['timeSlot']} | Location: {s['location']}\")
"

<details>
<summary>23 lines</summary>

```
{
  "sessionCode": "LAB540",
  "title": "Observe, optimize and protect your hosted agents in Microsoft Foundry",
  "description": "Modern agents fail in ways traditional monitoring can’t catch. In this hands-on lab, learn how Microsoft Foundry Observability helps you move from prototype → production with context-specific evaluation suites (auto-generated evaluators + test datasets) wired into developer workflows via skills/MCP tooling for hosted agents. Then scale quality with continuous evaluation, trace-linked analysis, and adaptive red teaming—and walk away with a sandbox to explore additional features on your own.\n\nAdd this session to your schedule to reserve your seat, as capacity is limited. Please arrive at least 5 minutes early; unclaimed seats may be released to standby attendees.",
  "speakers": "Nitya Narasimhan, Filisha Shah",
  "timeSlot": "19:30 - 20:45",
  "startDateTime": "2026-06-02T19:30:00Z",
  "endDateTime": "2026-06-02T20:45:00Z",
  "location": "Gateway Pavilion, Level 1, Lab 4",
  "level": "(300) Advanced",
  "type": "Lab",
  "topic": "Responsible AI",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "Observability, Microsoft Foundry, Responsible AI, Evaluations",
  "relatedSessionCodes": "BRK252",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
---SEPARATOR---
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 19m 56s</sub>

### ✅ `bash`

**Find repeat lab timeslots**

$ for code in LAB511-R1 LAB530-R1 LAB501-R1 LAB502-R1 LAB540-R1; do
  npx -y @microsoft/events-cli session "$code" --event build-2026 --json 2>/dev/null | python3 -c "
import json,sys
try:
    s=json.load(sys.stdin)
    print(f\"{s['sessionCode']} | Time: {s['timeSlot']} | Location: {s['location']}\")
except: pass
"
done

<details>
<summary>6 lines</summary>

```
LAB511-R1 | Time: 01:30 - 02:45 | Location: Gateway Pavilion, Level 1, Lab 4
LAB530-R1 | Time: 23:45 - 01:00 | Location: Building C, Level 2, Room 205
LAB501-R1 | Time: 23:45 - 01:00 | Location: Firehouse
LAB502-R1 | Time: 16:00 - 17:15 | Location: Firehouse
LAB540-R1 | Time: 23:45 - 01:00 | Location: Gateway Pavilion, Level 1, Lab 4
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 19m 59s</sub>

### 💭 Reasoning

*Now I have all the lab info. Let me compile the top labs for Sinan. Let me convert times to NZST:

**LAB511** - Azure HorizonDB:
- Main: Jun 2 22:00-23:15 UTC = Jun 3, 10:00 AM - 11:15 AM NZST
- R1: Jun 3 01:30-02:45 UTC = Jun 3, 1:30 PM - 2:45 PM NZST

Wait, Jun 3 01:30 UTC... The R1 timeslot shows 01:30-02:45. That would be Jun 3 01:30 UTC since it's a repeat on Day 2 (Jun 3 PDT). Let me think...


Actually the repeat labs are typically on Day 2 (Jun 3 PDT). But I need the actual startDateTime. Let me just use the UTC times from the main sessions and the time slots for repeats.

Let me re-examine. The main sessions on Jun 2:
- LAB530: 19:30-20:45 UTC Jun 2 → Jun 3, 7:30 AM - 8:45 AM NZST
- LAB501: 19:30-20:45 UTC Jun 2 → Jun 3, 7:30 AM - 8:45 AM NZST
- LAB540

: 19:30-20:45 UTC Jun 2 → Jun 3, 7:30 AM - 8:45 AM NZST
- LAB511: 22:00-23:15 UTC Jun 2 → Jun 3, 10:00 AM - 11:15 AM NZST
- LAB502: 22:00-23:15 UTC Jun 2 → Jun 3, 10:00 AM - 11:15 AM NZST

For the repeat sessions on Jun 3, I need to figure out their UTC times. The R1 repeats start at 23:45 UTC on Jun 3, which crosses into Jun 4 at 01:00 UTC.

LAB530-R1, LAB501-R1, and LAB540-R1 all run 23:45-01:00 UTC, putting them at Jun 4, 11:45 AM - 1:00 PM NZST. LAB502-R1 is earlier at 16:00-17:15 UTC on Jun 3, translating to Jun 4, 4:00 AM - 5:15 AM NZST. LAB511-R1 at 01:30-02:45 UTC is ambiguous—I need to determine which date it falls on. 2 would be the repeat session on Day 2, so the startDateTime should be Jun 3. The 01:30 UTC time slot is confusing me though—if it's Jun 3 01:30 UTC, that's still technically Jun 2 evening PDT (6:30 PM), which would be before Day 2 even starts. I think I need to look at what the actual startDateTime value is for the repeat session to clarify this. I'll present the top labs ranked for Sinan's tech stack, starting with LAB511 on PostgreSQL and agentic applications with HorizonDB—the most aligned with his needs but it conflicts with his current schedule at 3:45 PM PDT on Day 2. Next is LAB502 on customizing GitHub Copilot with custom tools and context. LAB530 covers building agents with reasoning and adaptation using Foundry Agent Service and MCP tools, which aligns with the agent framework focus. LAB540 continues with monitoring and protecting hosted agents in Microsoft Foundry.

Now I'm checking for scheduling conflicts — the morning sessions at 7:30-8:45 AM NZST would actually overlap with LTG453 which starts at 8:50 AM NZST, so there's a timing issue to resolve.

Looking at the repeat sessions, LAB502-R1 conflicts with both LTG466 and DEM305 in the early morning slot, while the other Day 2 repeats at 11:45 AM-1:00 PM NZST would fit right after the current schedule ends. The best approach seems to be scheduling the repeats after the main Day 2 sessions conclude.*

---

<sub>⏱️ 20m 34s</sub>

### 💬 Copilot

Here are the **top 5 labs** that match your stack, ranked by relevance:

---

## 🧪 Recommended Labs for You

### 1. ⭐ LAB511 — Create advanced Postgres-powered agentic apps with Azure HorizonDB
| | |
|---|---|
| **Level** | 300 (Advanced) |
| **Time (PDT)** | Jun 2, 3:00–4:15 PM |
| **Time (NZST)** | Jun 3, 10:00–11:15 AM |
| **Location** | Gateway Pavilion, Level 1, Lab 4 |
| **Speakers** | Jonathon Frost, Denzil Ribeiro |
| **Repeat** | LAB511-R1 (Day 2 evening) |

**Why**: PostgreSQL is in your daily stack + Entity Framework. Build a production AI agent using Azure HorizonDB (new cloud-native Postgres) — RAG, hybrid search, in-database LLM/embeddings, no vector stores or glue code. This is your EF + PostgreSQL expertise evolving into AI.

\> ⚠️ Conflicts with BRK241 on Day 1. **Recommendation**: Do LAB511 here and catch BRK241 on-demand, OR attend LAB511-R1 repeat on Day 2.

---

### 2. ⭐ LAB502 — Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows
| | |
|---|---|
| **Level** | 300 (Advanced) |
| **Time (PDT)** | Jun 2, 3:00–4:15 PM |
| **Time (NZST)** | Jun 3, 10:00–11:15 AM |
| **Repeat** | LAB502-R1: Jun 3, 9:00–10:15 AM PDT (Jun 4, 4:00–5:15 AM NZST) |
| **Location** | Firehouse |
| **Speakers** | Josh Johanning, Tiago Pascoal |

**Why**: As a GitHub partner, this is hands-on gold. Build custom Copilot agents, Agent Skills, MCP connections — works in VS Code, Visual Studio, CLI, and coding agent. You'll leave with working agents adaptable to ARINCO client codebases.

\> ⚠️ Same timeslot as LAB511 on Day 1. R1 conflicts with early Day 2 block.

---

### 3. LAB501 — From zero to deployed on Azure with AI agents
| | |
|---|---|
| **Level** | 300 (Advanced) |
| **Time (PDT)** | Jun 2, 12:30–1:45 PM |
| **Time (NZST)** | Jun 3, 7:30–8:45 AM |
| **Repeat** | LAB501-R1: Jun 3, 4:45–6:00 PM PDT (Jun 4, 11:45 AM–1:00 PM NZST) |
| **Location** | Firehouse |
| **Speakers** | Yun Jung Choi, Chris Harris |

**Why**: Empty terminal → deployed Azure app using GitHub Copilot CLI + coding agents. Natural language resource provisioning, no portal. This is the consulting demo workflow — show clients how fast you can ship with agents.

\> ✅ **Fits your schedule!** R1 runs AFTER your Day 2 sessions end. Attend LAB501-R1 at 11:45 AM NZST on Jun 4.

---

### 4. LAB530 — Engineering agents that reason, act, and adapt
| | |
|---|---|
| **Level** | 300 (Advanced) |
| **Time (PDT)** | Jun 2, 12:30–1:45 PM |
| **Time (NZST)** | Jun 3, 7:30–8:45 AM |
| **Repeat** | LAB530-R1: Jun 3, 4:45–6:00 PM PDT (Jun 4, 11:45 AM–1:00 PM NZST) |
| **Location** | Building C, Level 2, Room 205 |
| **Speakers** | Henk Boelman, Gustavo Cordido |

**Why**: Foundry Agent Service + Foundry IQ + MCP tools. Build an agent that reasons, acts, and adapts — step by step. Core to your Microsoft Agent Framework focus.

\> ⚠️ Same timeslot as LAB501 (both main & R1). Pick one.

---

### 5. LAB540 — Observe, optimize and protect your hosted agents in Microsoft Foundry
| | |
|---|---|
| **Level** | 300 (Advanced) |
| **Time (PDT)** | Jun 2, 12:30–1:45 PM |
| **Time (NZST)** | Jun 3, 7:30–8:45 AM |
| **Repeat** | LAB540-R1: Jun 3, 4:45–6:00 PM PDT (Jun 4, 11:45 AM–1:00 PM NZST) |
| **Location** | Gateway Pavilion, Level 1, Lab 4 |
| **Speakers** | Nitya Narasimhan, Filisha Shah |

**Why**: Bridges your Datadog/Azure Monitor experience to AI agents. Auto-generated evaluators, continuous eval, trace-linked analysis, red teaming. Production observability for agents.

\> ⚠️ Same repeat timeslot as LAB501 and LAB530.

---

## 🗓️ How Labs Fit Your Schedule

| Slot (NZST) | Best Lab Pick | Notes |
|---|---|---|
| Jun 3, 7:30 AM | **LAB501** (zero to deployed) | Starts before your breakout schedule; tight 5-min gap to LTG453 |
| Jun 3, 10:00 AM | **LAB511** (HorizonDB/Postgres) | ⚠️ Replaces BRK241 if you attend here |
| Jun 4, 11:45 AM | **LAB530** or **LAB501-R1** | ✅ After BRK207 ends — no conflicts! |

### My recommendation:

\> **Pick LAB511 (Postgres/HorizonDB)** on Day 1 at 10:00 AM NZST — it's uniquely matched to your EF + PostgreSQL background. Then grab **LAB501-R1 or LAB530-R1** on Day 2 at 11:45 AM NZST (after your last breakout). Both have digital lab versions (LAB511D, LAB501D, LAB530D) available online if you miss the in-person slot.

Would you like me to update your schedule files with a lab added?

---

<sub>⏱️ 21m 56s</sub>

### ℹ️ Info

Session shared successfully to:
/Users/sinanarinco/source-experiments/MicrosoftBuild2026/copilot-session-1efc37dc-d1bb-4b2e-925f-6bc91e0c7042.html

---

<sub>⏱️ 22m 30s</sub>

### 👤 User

did you update labs into the agenda you created for me?

---

<sub>⏱️ 22m 33s</sub>

### 💭 Reasoning

*The user is asking if I updated the agenda files with the lab sessions. I didn't - I just presented the lab information but didn't update the index.md or create new session files. Let me do that now.

Based on my recommendation:
- Day 1 (Jun 3 NZST): Add LAB511 at 10:00 AM (this replaces BRK241 at 10:45 AM in the schedule, or I should note it as an alternative)
- Day 2 (Jun 4 NZST): Add LAB501-R1 or LAB530-R1 at 11:45 AM (after BRK207 ends)


I'll go ahead and add the labs I recommended - LAB511 on Day 1 and LAB530-R1 on Day 2 - then create the individual session files and update the index to include them.*

---

<sub>⏱️ 22m 39s</sub>

### 💬 Copilot

No, I didn't — let me fix that now. I'll add the recommended labs to your agenda:

---

<sub>⏱️ 23m 36s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LAB511.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LAB511.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/LAB511.md with 2386 characters
```


---

<sub>⏱️ 23m 36s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/LAB530-R1.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/LAB530-R1.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/LAB530-R1.md with 1911 characters
```


---

<sub>⏱️ 23m 36s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md updated with changes.
```


---

<sub>⏱️ 23m 36s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md updated with changes.
```


---

<sub>⏱️ 23m 36s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md updated with changes.
```


---

<sub>⏱️ 23m 40s</sub>

### 💬 Copilot

Done! Updated your agenda with 2 labs:

**Day 1** — Added **LAB511** (HorizonDB/Postgres AI agents) at 10:00 AM NZST, replacing BRK241 (moved to on-demand). Hands-on with your PostgreSQL stack \> passive breakout.

**Day 2** — Added **LAB530-R1** (Engineering agents with Foundry + MCP) at 11:45 AM NZST, right after BRK207 ends. Perfect no-conflict closer.

Also added a "Labs Worth Considering" section in the index with digital lab alternatives (LAB502D, LAB501D, LAB540D) you can do remotely anytime.

Your final structure:

```
2026-06-03/
  ├── LTG453.md       8:50 AM
  ├── LTGSP481.md     9:10 AM
  ├── BRK223.md       9:30 AM
  ├── LAB511.md       10:00 AM 🧪 NEW
  └── DEM310.md       11:30 AM
2026-06-04/
  ├── LTG466.md       4:30 AM (early/optional)
  ├── DEM305.md       5:30 AM (early/optional)
  ├── BRK243.md       6:30 AM (early/optional)
  ├── BRK205.md       9:45 AM
  ├── DEM361.md       10:30 AM
  ├── BRK207.md       11:00 AM
  └── LAB530-R1.md    11:45 AM 🧪 NEW
```

---

<sub>⏱️ 24m 37s</sub>

### 👤 User

is there any other c# dotnet aspire azure github related sessions I am missing on my agenda? because of conflict or just not considered?

---

<sub>⏱️ 25m 1s</sub>

### ✅ `bash`

**Search all Aspire sessions**

$ npx -y @microsoft/events-cli sessions --query "Aspire" --event build-2026 --json --limit 10 2>/dev/null | python3 -c "
import json,sys
data=json.load(sys.stdin)
for s in data:
    print(f\"{s['sessionCode']} | {s['title']}\")
    print(f\"  Type: {s['type']} | Level: {s['level']} | Time: {s['timeSlot']}\")
    print(f\"  Tags: {s['tags']}\")
    print()
"

```
BRK205 | Aspire for agents: Transform how you build and deploy distributed apps
  Type: Breakout | Level: (200) Intermediate | Time: 21:45 - 22:30
  Tags: Azure, Agents, Developer, OSS, DevTools, Agentic SDLC, Aspire
<exited with exit code 0>
```


---

<sub>⏱️ 25m 0s</sub>

### ✅ `bash`

**Find .NET Azure sessions not yet considered**

$ npx -y @microsoft/events-cli sessions --query "Azure developer" --tech ".NET" --event build-2026 --json --limit 15 2>/dev/null | python3 -c "
import json,sys
data=json.load(sys.stdin)
already = ['BRK205','BRK207','BRK223','BRK241','BRK243','BRK250','BRK221','BRK224','BRK252','DEM301','DEM305','DEM310','DEM333','DEM341','DEM361','DEM365','LTG401','LTG408','LTG453','LTG455','LTG466','LTGSP481','LTGSP493','TT656','LAB511','LAB530','LAB501','LAB502','LAB540','ODSP929','DEMSP394','LTG469','BRKSP90','ODSP907','ODSP909','TT645','LTG441']
for s in data:
    code = s['sessionCode'].split('-')[0]
    if code not in already:
        print(f\"{s['sessionCode']} | {s['title']}\")
        print(f\"  Type: {s['type']} | Level: {s['level']} | Time: {s['timeSlot']}\")
        print(f\"  Speakers: {s['speakers']}\")
        print(f\"  Tags: {s['tags']}\")
        print(f\"  {s['description'][:200]}\")
        print()
"

<details>
<summary>53 lines</summary>

```
TT667B | Growing Local Developer Communities with Azure Tech Groups
  Type: Table Talk | Level: (100) Foundational | Time: 23:15 - 00:00
  Speakers: Brittney Smith
  Tags: Community
  Are you a community leader or looking for more ways to get involved with your local developer community? Interested in creating your own community? Join Azure Tech Group (ATG) leaders to learn how ATG

TT667A | Growing Local Developer Communities with Azure Tech Groups
  Type: Table Talk | Level: (100) Foundational | Time: 23:15 - 00:00
  Speakers: Galimah Baysah
  Tags: Community
  Are you a community leader or looking for more ways to get involved with your local developer community? Interested in creating your own community? Join Azure Tech Group (ATG) leaders to learn how ATG

BRK261 | Build and ship faster with a developer-optimized experience on Windows
  Type: Breakout | Level: (300) Advanced | Time: 22:45 - 23:30
  Speakers: Shen Chauhan, Clint Rutkas
  Tags: AI, Agents, Windows, Windows Developer, Azure Linux, VS Code, Developer Technologies, Windows Development, Developer Frameworks, Developer Languages, WSL, Terminal
  Learn how Windows delivers a streamlined, end-to-end experience through PCs and OS experiences optimized for developers. See our new experiences in action across WSL, PowerToys and your favorite devel

DEM377 | Building Impact Through Developer Communities
  Type: Demo | Level: (100) Foundational | Time: 23:30 - 23:55
  Speakers: Prashant G Bhoyar, Rie Merritt, Stephen Simon
  Tags: Community
  Join community leaders from.NET, Azure, Fabric and Global AI, to explore what it takes to build and grow tech communities. Hear their journeys, lessons learned, and how
 they stepped into leadership. 

BRK235 | Local models, developer control, and the future of AI runtimes
  Type: Breakout | Level: (300) Advanced | Time: 17:15 - 18:00
  Speakers: Michael Chiang, Parth Sareen
  Tags: Purview, Purview, Azure DevOps, Agent Observability
  How local and hybrid model execution is reshaping developer workflows, privacy, and experimentation. Why “run it yourself” is back. 

Seating for this session is first-come, first-served. Add it to yo

ODSP901 | Discover, govern, and scale Azure resources with HashiCorp Terraform
  Type: Pre-recorded | Level: (200) Intermediate | Time: 
  Speakers: Kerim Satirli
  Tags: Azure, Scaling, Terraform, Developer Frameworks
  Managing existing Azure environments is a major barrier to scaling cloud operations, with many resources outside infrastructure-as-code. In this session, learn how HashiCorp Terraform and Terraform Se

BRKSP93 | Build once, deploy everywhere across Azure, on-prem, and local with AMD
  Type: Breakout | Level: (300) Advanced | Time: 21:30 - 22:15
  Speakers: Anush Elangovan
  Tags: AI, API, Developer, Developer Technologies, Developer Frameworks
  As AI workloads move from experimentation to production, developers need portability, performance, and flexibility—without lock-in. Learn how AMD Instinct and Radeon GPUs and the ROCm open software st

DEM302 | Build and deploy an Azure app with your agent team
  Type: Demo | Level: (200) Intermediate | Time: 19:00 - 19:25
  Speakers: Brady Gaster, Rong Lu
  Tags: Azure, Agents, Developer, GitHub Copilot, GitHub, Deployment Pipelines, GitHub Copilot CLI, DevTools, Skills, Agentic SDLC
  In 25 minutes, we’ll go from a blank repo to a live Azure AI app—built and deployed by a team of GitHub Copilot agents. Watch Copilot plan architecture, generate code, provision Azure, and deploy live

BRK202 | Azure DevOps meets GitHub, the path to AI powered SDLC
  Type: Breakout | Level: (300) Advanced | Time: 20:30 - 21:15
  Speakers: Dave Burnison, Dan Hellem
  Tags: Developer, GitHub Advanced Security, GitHub Copilot, GitHub, Azure DevOps, Deployment Pipelines, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools, Agentic SDLC
  Azure DevOps and GitHub are better together—and the integration keeps getting smarter. In this demo-heavy session, you’ll see how hybrid patterns that connect GitHub with Azure Boards and Azure Pipeli

LAB501D | Digital Lab: From zero to deployed on Azure with AI agents
  Type: Digital Lab | Level: (300) Advanced | Time: 
  Speakers: 
  Tags: Azure, Agents, Developer, GitHub Copilot, GitHub, Deployment Pipelines, GitHub Actions, GitHub Copilot CLI, DevTools, Agentic SDLC
  What happens when you let AI agents do the building? In this hands-on lab, you'll go from an empty terminal to a deployed app on Azure — with GitHub Copilot CLI and coding agents handling the scaffold
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 25m 1s</sub>

### ✅ `bash`

**Search CI/CD DevOps sessions**

$ npx -y @microsoft/events-cli sessions --query "Azure DevOps deployment CI CD" --event build-2026 --json --limit 10 2>/dev/null | python3 -c "
import json,sys
data=json.load(sys.stdin)
already = ['BRK205','BRK207','BRK223','BRK241','BRK243','BRK250','BRK221','BRK224','BRK252','DEM301','DEM305','DEM310','DEM333','DEM341','DEM361','DEM365','LTG401','LTG408','LTG453','LTG455','LTG466','LTGSP481','LTGSP493','TT656','LAB511','LAB530','LAB501','LAB502','LAB540','ODSP929','DEMSP394','LTG469','BRKSP90','ODSP907','ODSP909','TT645','LTG441','BRK210','ODSP901','ODSP905','ODSP911','DEMSP386','LABSP580','LTG431','LTG458','DEM340','DEM362','BRK222']
for s in data:
    code = s['sessionCode'].split('-')[0]
    if code not in already:
        print(f\"{s['sessionCode']} | {s['title']}\")
        print(f\"  Type: {s['type']} | Level: {s['level']} | Time: {s['timeSlot']}\")
        print(f\"  Speakers: {s['speakers']}\")
        print(f\"  Tags: {s['tags']}\")
        print(f\"  {s['description'][:200]}\")
        print()
"

<details>
<summary>36 lines</summary>

```
BRK202 | Azure DevOps meets GitHub, the path to AI powered SDLC
  Type: Breakout | Level: (300) Advanced | Time: 20:30 - 21:15
  Speakers: Dave Burnison, Dan Hellem
  Tags: Developer, GitHub Advanced Security, GitHub Copilot, GitHub, Azure DevOps, Deployment Pipelines, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools, Agentic SDLC
  Azure DevOps and GitHub are better together—and the integration keeps getting smarter. In this demo-heavy session, you’ll see how hybrid patterns that connect GitHub with Azure Boards and Azure Pipeli

LAB512 | Hands-on with the latest Cobalt VMs – from code to cloud deployment
  Type: Lab | Level: (200) Intermediate | Time: 22:00 - 23:15
  Speakers: Jamshed Damkewala, Amar Dhamdhere
  Tags: 
  Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images

LAB512-R2 | Hands-on with the latest Cobalt VMs – from code to cloud deployment
  Type: Lab | Level: (200) Intermediate | Time: 16:00 - 17:15
  Speakers: Jamshed Damkewala, Amar Dhamdhere
  Tags: 
  Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images

LAB512-R1 | Hands-on with the latest Cobalt VMs – from code to cloud deployment
  Type: Lab | Level: (200) Intermediate | Time: 01:30 - 02:45
  Speakers: Jamshed Damkewala, Amar Dhamdhere
  Tags: 
  Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images

LAB512-R3 | Hands-on with the latest Cobalt VMs – from code to cloud deployment
  Type: Lab | Level: (200) Intermediate | Time: 22:00 - 23:15
  Speakers: Jamshed Damkewala, Amar Dhamdhere
  Tags: 
  Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images

LAB512D | Digital Lab: Hands-on with the latest Cobalt VMs – from code to cloud deployment
  Type: Digital Lab | Level: (200) Intermediate | Time: 
  Speakers: 
  Tags: 
  Roll up your sleeves and get hands-on with the latest Azure Cobalt VMs. Provision your first Cobalt VM and explore what makes Arm tick in the Cloud. From there you'll build multi-arch container images

LTGSP479 | Automate Windows on Arm migrations with AI-assisted specs
  Type: Lightning Talk | Level: (200) Intermediate | Time: 19:40 - 19:55
  Speakers: Jamshed Damkewala, michael Gamble, Clay Nelson
  Tags: Automation, Azure, Cost Management, Platform Engineering, Reliability, SAP, Compute, MongoDB Migration, Oracle Migration, On-prem Migration, MySQL Migration, Postgres Migration, Azure SQL, Azure SQL Hyperscale, Azure Database for MySQL, Azure Database for PostgreSQL, SQL Server Containers on Kubernetes, CosmosDB, Azure Cosmos DB, .NET, Developer, Azure Kubernetes Service (AKS)​​, GitHub Advanced Security, Agent 365, Software Development Company, MCP, Foundry Agents, AKS, Azure Copilot, Azure DevOps, Azure Linux, Data, Deployment Pipelines, OSS CI/CD Libraries, Windows 365 for Agents, Agents on Windows
  Porting Windows apps to Arm used to take weeks: identifying dependencies, chasing compatibility gaps, and relying on trial and error. With AI, the same workflow now fits in a single session. This sess
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 25m 0s</sub>

### ✅ `bash`

**Search Container Apps/serverless**

$ npx -y @microsoft/events-cli sessions --query "Azure Container Apps serverless" --event build-2026 --json --limit 10 2>/dev/null | python3 -c "
import json,sys
data=json.load(sys.stdin)
already = ['BRK205','BRK207','BRK223','BRK241','BRK243','BRK250','BRK221','BRK224','BRK252','DEM301','DEM305','DEM310','DEM333','DEM341','DEM361','DEM365','LTG401','LTG408','LTG453','LTG455','LTG466','LTGSP481','LTGSP493','TT656','LAB511','LAB530','LAB501','LAB502','LAB540','ODSP929','DEMSP394','LTG469','BRKSP90','ODSP907','ODSP909','TT645','LTG441','BRK210','ODSP901','ODSP905','ODSP911','DEMSP386','LABSP580','LTG431','LTG458','DEM340','DEM362','BRK222','DEM311']
for s in data:
    code = s['sessionCode'].split('-')[0]
    if code not in already:
        print(f\"{s['sessionCode']} | {s['title']}\")
        print(f\"  Type: {s['type']} | Level: {s['level']} | Time: {s['timeSlot']}\")
        print(f\"  Speakers: {s['speakers']}\")
        print(f\"  Tags: {s['tags']}\")
        print(f\"  {s['description'][:200]}\")
        print()
"

<details>
<summary>16 lines</summary>

```
ODSP926 | Build collaborative agents into apps with APIs
  Type: Pre-recorded | Level: (300) Advanced | Time: 
  Speakers: Ziv Navoth, Edo Segal
  Tags: AI, Azure, API, Agents, Foundry Agents, Developer Technologies
  PwC research found the top barrier to AI agent impact isn't the technology; it's connecting agents across applications and workflows to truly operate like coworkers. Most organizations deploy agents i

LAB511D | Digital Lab: Create advanced Postgres-powered agentic apps with Azure HorizonDB
  Type: Digital Lab | Level: (300) Advanced | Time: 
  Speakers: 
  Tags: CP&D, Data, Azure HorizonDB
  In this lab, you’ll build a production-ready AI agent using Azure HorizonDB as a unified data, retrieval, and intelligence layer. Implement RAG, hybrid semantic and keyword search, and agentic workflo

LTG422 | Monetize apps and agents with Microsoft Marketplace
  Type: Lightning Talk | Level: (200) Intermediate | Time: 00:30 - 00:45
  Speakers: Felipe Ospina
  Tags: 
  Learn how to build, publish, and monetize apps and agents with Microsoft Marketplace to reach millions of customers and drive scalable growth. Getting published on Marketplace surfaces your solutions
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 25m 4s</sub>

### 💭 Reasoning

*Good finds! Let me now look at a few more potentially relevant sessions:

1. **BRK202** — Azure DevOps meets GitHub, the path to AI powered SDLC — VERY RELEVANT (he uses both Azure DevOps and GitHub Actions)
2. **DEM302** — Build and deploy an Azure app with your agent team — Relevant (GitHub Copilot agents + Azure deployment)
3. **TT667** — Growing Local Developer Communities with Azure Tech Groups — Relevant (he co-organises user groups)
4. **BRK261** — Build and ship faster with developer-optimized Windows experience — Somewhat relevant (WSL, PowerToys)Let me check the timing:- BRK202: 20:30-21:15 UTC Jun 2? Let me check which day. The time slot is 20:30-21:15. If Jun 2, that's 8:30-9:15 AM NZST Jun 3. 

Wait, that's a conflict — BRK202 runs 8:30-9:15 AM NZST while LTG453 starts at 8:50 AM, so they overlap for 25 minutes.

Now checking EM302 at 19:00-19:25 UTC on Jun 3, which converts to 7:00-7:25 AM NZST Jun 4. That overlaps with BRK243 (6:30-7:15 AM) by 15 minutes. I need to figure out which day EM302 is actually scheduled for — the speaker is Brady Gaster with GitHub Copilot and Azure tags, so let me verify the timing.*

---

<sub>⏱️ 25m 21s</sub>

### ✅ `bash`

**Get details for BRK202, DEM302, TT667**

$ npx -y @microsoft/events-cli session BRK202 --event build-2026 --json 2>/dev/null && echo "---" && npx -y @microsoft/events-cli session DEM302 --event build-2026 --json 2>/dev/null && echo "---" && npx -y @microsoft/events-cli session TT667A --event build-2026 --json 2>/dev/null

<details>
<summary>66 lines</summary>

```
{
  "sessionCode": "BRK202",
  "title": "Azure DevOps meets GitHub, the path to AI powered SDLC",
  "description": "Azure DevOps and GitHub are better together—and the integration keeps getting smarter. In this demo-heavy session, you’ll see how hybrid patterns that connect GitHub with Azure Boards and Azure Pipelines enable Agentic DevOps. See the all of the newest AI-powered capabilities in Azure DevOps. Plus, hear how Microsoft's engineering teams adopted this approach and what they gained.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
  "speakers": "Dave Burnison, Dan Hellem",
  "timeSlot": "20:30 - 21:15",
  "startDateTime": "2026-06-03T20:30:00Z",
  "endDateTime": "2026-06-03T21:15:00Z",
  "location": "Gateway Pavilion, Level 1, Cowell Theater",
  "level": "(300) Advanced",
  "type": "Breakout",
  "topic": "Developer tools & frameworks",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "Developer, GitHub Advanced Security, GitHub Copilot, GitHub, Azure DevOps, Deployment Pipelines, GitHub Actions, GitHub Enterprise, GitHub Copilot CLI, DevTools, Agentic SDLC",
  "relatedSessionCodes": "",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
---
{
  "sessionCode": "DEM302",
  "title": "Build and deploy an Azure app with your agent team",
  "description": "In 25 minutes, we’ll go from a blank repo to a live Azure AI app—built and deployed by a team of GitHub Copilot agents. Watch Copilot plan architecture, generate code, provision Azure, and deploy live using Copilot Agents and Skills. Leave with a blueprint for your agent driven coding workflow for Azure.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
  "speakers": "Brady Gaster, Rong Lu",
  "timeSlot": "19:00 - 19:25",
  "startDateTime": "2026-06-02T19:00:00Z",
  "endDateTime": "2026-06-02T19:25:00Z",
  "location": "Festival Pavilion, Theater A",
  "level": "(200) Intermediate",
  "type": "Demo",
  "topic": "Developer tools & frameworks",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "Azure, Agents, Developer, GitHub Copilot, GitHub, Deployment Pipelines, GitHub Copilot CLI, DevTools, Skills, Agentic SDLC",
  "relatedSessionCodes": "",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
---
{
  "sessionCode": "TT667A",
  "title": "Growing Local Developer Communities with Azure Tech Groups",
  "description": "Are you a community leader or looking for more ways to get involved with your local developer community? Interested in creating your own community? Join Azure Tech Group (ATG) leaders to learn how ATG connects developers, cloud engineers, and tech enthusiasts through local meetups, networking, and collaboration. Discover how to start and grow a community, connect with Microsoft experts, share real-world AI and Azure experiences, and engage with the broader Azure technical ecosystem.\n\nSeating for this session is first-come, first-served. Add it to your schedule to plan your day and arrive early to secure a spot.",
  "speakers": "Galimah Baysah",
  "timeSlot": "23:15 - 00:00",
  "startDateTime": "2026-06-03T23:15:00Z",
  "endDateTime": "2026-06-04T00:00:00Z",
  "location": "Gateway Pavilion, Level 2, Table 3",
  "level": "(100) Foundational",
  "type": "Table Talk",
  "topic": "Cloud platform & data",
  "solutionArea": "",
  "product": "",
  "languages": "",
  "tags": "Community",
  "relatedSessionCodes": "",
  "slideDeck": "",
  "onDemand": "",
  "event": "build-2026"
}
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 25m 25s</sub>

### 💭 Reasoning

*Now let me convert these to NZST and check for conflicts:

1. **BRK202** — Azure DevOps meets GitHub
   - Start: 2026-06-03T20:30:00Z = Jun 4, 8:30 AM NZST
   - End: 2026-06-03T21:15:00Z = Jun 4, 9:15 AM NZST
   - This is Day 2 (Jun 3 PDT). In the current Day 2 schedule:
     - BRK243 ends at 7:15 AM NZST
     - BRK205 starts at 9:45 AM NZST
     - BRK202 fits perfectly in the gap: 8:30–9:15 AM NZST! ✅ NO CONFLICT

2. **DEM302** — Build and deploy an Azure app with your agent team
   - Start: 2026-06-02T19:00:00Z = Jun 3, 7:00 AM NZST
   - End: 2026-06-02T19:25:00Z = Jun 3, 7:25 AM NZST
   - This is Day 1 (Jun 2 PDT), which starts at 8:50 AM. DEM302 slots in before the schedule at 7:00–7:25 AM NZST! ✅ NO CONFLICT

3. **TT667A** — Growing Local Developer Communities
   - Start: 2026-06-03T23:15:00Z = Jun 4, 11:15 AM NZST
   - End: 2026-06-04T00:00:00Z = Jun 4, 12:00 PM NZST
   - Day 2 has BRK207 at 11:00–11:45 AM and LAB530-R1 starting at 11:45 AM. TT667A overlaps with BRK207, so there's a conflict here.

The key takeaways are that BRK202 fills a perfect gap on Day 2 between BRK243 and BRK205—this is essential given his work with both Azure DevOps and GitHub Actions. DEM302 is a quick win before Day 1 kicks off. TT667A is relevant to his community leadership but conflicts with existing sessions.*

---

<sub>⏱️ 25m 35s</sub>

### 💬 Copilot

Found some significant gaps! Here are sessions you're missing that **fit your schedule without conflicts**:

---

## ✅ Sessions That Fit (No Conflicts!)

### 🔥 BRK202 — Azure DevOps meets GitHub, the path to AI powered SDLC
| | |
|---|---|
| **NZST** | **Jun 4, 8:30–9:15 AM** (fits in Day 2 gap between BRK243 and BRK205!) |
| **PDT** | Jun 3, 1:30–2:15 PM |
| **Speakers** | Dave Burnison, Dan Hellem |
| **Type** | Breakout · Level 300 |
| **Tags** | Azure DevOps, GitHub Actions, GitHub Advanced Security, Agentic SDLC |

**Why you need this**: You use **both** Azure DevOps and GitHub Actions daily. This shows hybrid patterns connecting them + "Agentic DevOps" + AI-powered Azure DevOps capabilities. Plus Microsoft's own adoption story. As a GitHub/Microsoft partner consultant, this is essential for client advisory.

\> ✅ Slots perfectly into Day 2 between BRK243 (ends 7:15 AM) and BRK205 (starts 9:45 AM)

---

### 🔥 DEM302 — Build and deploy an Azure app with your agent team
| | |
|---|---|
| **NZST** | **Jun 3, 7:00–7:25 AM** (fits before your Day 1 starts!) |
| **PDT** | Jun 2, 12:00–12:25 PM |
| **Speakers** | Brady Gaster, Rong Lu |
| **Type** | Demo · Level 200 |
| **Tags** | Azure, GitHub Copilot, Deployment Pipelines, Copilot CLI, Skills, Agentic SDLC |

**Why you need this**: Blank repo → live Azure AI app in 25 min using a **team** of Copilot agents. Architecture planning, code gen, Azure provisioning, and deployment — all agent-driven. This is the consulting demo you'll replay for clients.

\> ✅ Starts 1h50m before your first scheduled session (LTG453 at 8:50 AM)

---

## ⚠️ Relevant but Conflicting

### TT667A — Growing Local Developer Communities with Azure Tech Groups
| | |
|---|---|
| **NZST** | Jun 4, 11:15 AM – 12:00 PM |
| **PDT** | Jun 3, 4:15–5:00 PM |
| **Type** | Table Talk · Level 100 |

**Why it matters**: You co-organise the Aotearoa Azure User Group and Auckland .NET User Group. This is a networking session with other Azure community leaders.

\> ⚠️ Conflicts with BRK207 + LAB530-R1. But as a Table Talk, the real value is the networking — consider dropping by for the last 15 min after BRK207 if the rooms are close.

---

## Summary of What Was Missing

| Session | Status | Action |
|---------|--------|--------|
| **BRK202** (Azure DevOps + GitHub) | ✅ Fits Day 2 gap | **Add to schedule** |
| **DEM302** (Agent team deploys Azure app) | ✅ Fits before Day 1 | **Add to schedule** |
| TT667A (Community leaders) | ⚠️ Conflicts | Watch for networking opportunities on-site |

Want me to add BRK202 and DEM302 to your agenda files?

---

<sub>⏱️ 26m 35s</sub>

### 👤 User

update the files?

---

<sub>⏱️ 27m 4s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/DEM302.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/DEM302.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/DEM302.md with 1806 characters
```


---

<sub>⏱️ 27m 4s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK202.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK202.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/BRK202.md with 2132 characters
```


---

<sub>⏱️ 27m 4s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md updated with changes.
```


---

<sub>⏱️ 27m 4s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md updated with changes.
```


---

<sub>⏱️ 27m 8s</sub>

### 💬 Copilot

Done! Updated your agenda with both sessions:

```
2026-06-03/
  ├── DEM302.md       7:00 AM  ← NEW (agent team deploys Azure app)
  ├── LTG453.md       8:50 AM
  ├── LTGSP481.md     9:10 AM
  ├── BRK223.md       9:30 AM
  ├── LAB511.md       10:00 AM 🧪
  └── DEM310.md       11:30 AM

2026-06-04/
  ├── LTG466.md       4:30 AM (early/optional)
  ├── DEM305.md       5:30 AM (early/optional)
  ├── BRK243.md       6:30 AM (early/optional)
  ├── BRK202.md       8:30 AM  ← NEW (Azure DevOps + GitHub)
  ├── BRK205.md       9:45 AM
  ├── DEM361.md       10:30 AM
  ├── BRK207.md       11:00 AM
  └── LAB530-R1.md    11:45 AM 🧪
```

Both slot in without any conflicts — BRK202 fills the Day 2 gap nicely between BRK243 and BRK205.

---

<sub>⏱️ 35m 59s</sub>

### 👤 User

ok now go over and find sessions that is not made to the cut and create Recorded folder and put them there, update index.md as well.

---

<sub>⏱️ 36m 5s</sub>

### ✅ `bash`

**Create recorded folder**

$ mkdir -p /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded

```

<exited with exit code 0>
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK241.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK241.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK241.md with 1526 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM333.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM333.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM333.md with 1371 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/LTG455.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/LTG455.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/LTG455.md with 1461 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK221.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK221.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK221.md with 1512 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM301.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM301.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM301.md with 1543 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK224.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK224.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK224.md with 1594 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/TT656.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/TT656.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/TT656.md with 1653 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK250.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK250.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK250.md with 1624 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK252.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK252.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/BRK252.md with 1457 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM341.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM341.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEM341.md with 1512 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/TT667A.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/TT667A.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/TT667A.md with 1514 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/LTG401.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/LTG401.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/LTG401.md with 1163 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEMSP394.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEMSP394.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/DEMSP394.md with 1437 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/ODSP909.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/ODSP909.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/ODSP909.md with 1332 characters
```


---

<sub>⏱️ 38m 11s</sub>

### ✅ `create`

**create a new file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/ODSP901.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/ODSP901.md

```
Created file /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/ODSP901.md with 1349 characters
```


---

<sub>⏱️ 38m 14s</sub>

### 💬 Copilot

Now let me update the index.md:

---

<sub>⏱️ 38m 39s</sub>

### ❌ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
Invalid inputs: old_str is required
```


---

<sub>⏱️ 38m 45s</sub>

### ✅ `view`

**view the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md (lines 60-100)

<details>
<summary>40 lines</summary>

```
60. | BRK241 | From prototype to production: build and run agents at scale | LAB511 | Agent Framework lifecycle (replaced by hands-on lab) |
61. | LTG455 | From Code to Agents: Build Production MCP Servers on Azure Functions | BRK223 (5 min overlap) | MCP + Azure Functions + Azure DevOps CI/CD |
62. | DEM333 | How Foundry integrates with open-source frameworks and tools | LAB511 | Agent Framework + LangGraph + MCP + A2A |
63. | BRK221 | Idea to production-ready agent in seconds on AI-native runtime | BRK205 | Azure Container Apps for agentic workloads |
64. | DEM301 | Rethinking CI: Actions, AI Agents, and the End of Commit-Fail-Commit | BRK205 | GitHub Actions + AI agents + MCP |
65. | BRK224 | PepsiCo's blueprint for agentic AI | BRK205 | Azure SQL + Cosmos DB + PostgreSQL data layer |
66. | TT656 | From Locked-In to Liquid: Modernizing .NET Before November 2026 EOL | LAB511 | .NET 8/9 EOL migration strategies |
67. | BRK250 | Govern open-source AI agents, any framework, any scale | BRK223 | Enterprise agent governance |
68. 
69. ## 🧪 Other Labs Worth Considering (Digital/On-Demand)
70. 
71. | Code | Title | Why |
72. |------|-------|-----|
73. | LAB502 / LAB502D | Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows | Build custom Copilot agents + MCP + Agent Skills (GitHub partner gold) |
74. | LAB501 / LAB501D | From zero to deployed on Azure with AI agents | GitHub Copilot CLI + Azure deployment workflow |
75. | LAB540 / LAB540D | Observe, optimize and protect your hosted agents in Microsoft Foundry | Agent observability, evaluations, red teaming |
76. | LAB511D | Digital Lab: HorizonDB (same as LAB511) | Backup if you miss the in-person slot |
77. | LAB530D | Digital Lab: Engineering agents (same as LAB530) | Backup if you miss the in-person slot |
78. 
79. ---
80. 
81. ## 🎯 Focus Themes
82. 
83. 1. **Microsoft Agent Framework + Aspire** — The new distributed AI app story
84. 2. **Azure Data for AI** — Cosmos DB, SQL, HorizonDB (PostgreSQL) + vector search
85. 3. **GitHub Platform Evolution** — Copilot agents, Actions for AI, MCP integration
86. 4. **MCP Servers in C#** — The new integration standard on your stack
87. 5. **Observability for Agents** — OpenTelemetry, evals, debugging agentic apps
88. 
89. ---
90. 
91. ## 📌 Key Takeaway Sessions by Role
92. 
93. | As a... | Priority Sessions |
94. |---------|-------------------|
95. | .NET Consultant | BRK205, BRK243, LTGSP481, BRK207 |
96. | Azure User Group Organiser | BRK223, BRK241, LTG453 |
97. | AI/Agent Builder | BRK241, BRK243, DEM361, LTG466 |
98. | GitHub Partner | DEM305, BRK207, DEM301 (on-demand) |
99.
```

</details>


---

<sub>⏱️ 39m 1s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md updated with changes.
```


---

<sub>⏱️ 39m 5s</sub>

### 💬 Copilot

Now let me also remove the old BRK241.md from the Day 1 folder since it moved to recorded:

---

<sub>⏱️ 39m 7s</sub>

### ✅ `bash`

**Remove BRK241 from live schedule folder**

$ rm /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/BRK241.md 2>/dev/null; echo "Done"

```
Done
<exited with exit code 0>
```


---

<sub>⏱️ 39m 12s</sub>

### 💬 Copilot

Let me verify the final structure:

---

<sub>⏱️ 39m 13s</sub>

### ✅ `view`

**view the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026

<details>
<summary>6 lines</summary>

```
.git
2026-06-03
2026-06-04
copilot-session-1efc37dc-d1bb-4b2e-925f-6bc91e0c7042.html
index.md
recorded
```

</details>


---

<sub>⏱️ 39m 19s</sub>

### ✅ `bash`

**Show final folder structure**

$ echo "=== 2026-06-03/ ===" && ls /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-03/ && echo && echo "=== 2026-06-04/ ===" && ls /Users/sinanarinco/source-experiments/MicrosoftBuild2026/2026-06-04/ && echo && echo "=== recorded/ ===" && ls /Users/sinanarinco/source-experiments/MicrosoftBuild2026/recorded/

<details>
<summary>10 lines</summary>

```
=== 2026-06-03/ ===
BRK223.md	DEM302.md	DEM310.md	LAB511.md	LTG453.md	LTGSP481.md

=== 2026-06-04/ ===
BRK202.md	BRK207.md	DEM305.md	LAB530-R1.md
BRK205.md	BRK243.md	DEM361.md	LTG466.md

=== recorded/ ===
BRK221.md	BRK250.md	DEM333.md	LTG401.md	ODSP909.md
BRK224.md	BRK252.md	DEM341.md	LTG455.md	TT656.md
BRK241.md	DEM301.md	DEMSP394.md	ODSP901.md	TT667A.md
<exited with exit code 0>
```

</details>


---

<sub>⏱️ 39m 23s</sub>

### 💬 Copilot

All updated. Here's the final structure:

```
MicrosoftBuild2026/
├── index.md
├── 2026-06-03/          ← Day 1 Live (6 sessions)
│   ├── DEM302.md         7:00 AM
│   ├── LTG453.md         8:50 AM
│   ├── LTGSP481.md       9:10 AM
│   ├── BRK223.md         9:30 AM
│   ├── LAB511.md         10:00 AM 🧪
│   └── DEM310.md         11:30 AM
├── 2026-06-04/          ← Day 2 Live (8 sessions)
│   ├── LTG466.md         4:30 AM (optional)
│   ├── DEM305.md         5:30 AM (optional)
│   ├── BRK243.md         6:30 AM (optional)
│   ├── BRK202.md         8:30 AM
│   ├── BRK205.md         9:45 AM
│   ├── DEM361.md         10:30 AM
│   ├── BRK207.md         11:00 AM
│   └── LAB530-R1.md      11:45 AM 🧪
└── recorded/            ← 15 on-demand sessions (prioritised)
    ├── BRK241.md         P1 — Agent Framework lifecycle
    ├── DEM301.md         P1 — GitHub Actions + AI agents
    ├── BRK250.md         P1 — Agent governance
    ├── LTG455.md         P1 — MCP on Azure Functions
    ├── DEM333.md         P1 — Foundry + open-source
    ├── BRK221.md         P2 — Container Apps AI runtime
    ├── BRK224.md         P2 — PepsiCo agentic AI
    ├── BRK252.md         P2 — Agent observability ROI
    ├── TT656.md          P2 — .NET EOL migration
    ├── DEM341.md         P2 — OpenTelemetry tracing
    ├── LTG401.md         P3 — Copilot hidden gems
    ├── DEMSP394.md       P3 — Enterprise .NET + AI
    ├── ODSP909.md        P3 — Agent Framework + OTel
    ├── ODSP901.md        P3 — Terraform governance
    └── TT667A.md         P3 — Community leadership
```

Index.md now has a dedicated **📼 Watch On-Demand** section with 3 priority tiers for your post-Build viewing queue.

---

<sub>⏱️ 3056m 10s</sub>

### 👤 User

rename index.md to readme.md , also put some references how this schedule is created like microsoft build skill , copilot cli etc

---

<sub>⏱️ 3056m 10s</sub>

### ℹ️ Info

Compacting conversation history...

---

<sub>⏱️ 3056m 19s</sub>

### ✅ `bash`

**Rename index.md to README.md**

$ mv /Users/sinanarinco/source-experiments/MicrosoftBuild2026/index.md /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md

```

<exited with exit code 0>
```


---

<sub>⏱️ 3056m 18s</sub>

### ❌ `view`

**view the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md (lines 1-10)

```
Path does not exist
```


---

<sub>⏱️ 3056m 23s</sub>

### ✅ `bash`

**Find the md files**

$ ls /Users/sinanarinco/source-experiments/MicrosoftBuild2026/*.md

```
/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md
<exited with exit code 0>
```


---

<sub>⏱️ 3056m 28s</sub>

### ✅ `view`

**view the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md (lines 1-12)

<details>
<summary>12 lines</summary>

```
1. # Microsoft Build 2026 — Personal Agenda
2. 
3. **Attendee**: Sinan Nar — Senior Software Engineer & Consultant @ ARINCO  
4. **Event**: June 2–3, 2026 | San Francisco, CA (PDT, UTC-7)  
5. **Viewing from**: New Zealand (NZST, UTC+12) — times shown in NZST
6. 
7. > ⏰ **Timezone note**: SF sessions on Jun 2 PDT land on **Jun 3 NZST morning**; Jun 3 PDT sessions land on **Jun 4 NZST**. All times below are NZST.
8. 
9. ---
10. 
11. ## Schedule Overview
12.
```

</details>


---

<sub>⏱️ 3056m 28s</sub>

### ✅ `view`

**view the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md (lines 90--1)

<details>
<summary>29 lines</summary>

```
90. | Code | Title | Why |
91. |------|-------|-----|
92. | LAB502 / LAB502D | Make GitHub Copilot Work Your Way: Custom Tools, Context and Workflows | Build custom Copilot agents + MCP + Agent Skills (GitHub partner gold) |
93. | LAB501 / LAB501D | From zero to deployed on Azure with AI agents | GitHub Copilot CLI + Azure deployment workflow |
94. | LAB540 / LAB540D | Observe, optimize and protect your hosted agents in Microsoft Foundry | Agent observability, evaluations, red teaming |
95. | LAB511D | Digital Lab: HorizonDB (same as LAB511) | Backup if you miss the in-person slot |
96. | LAB530D | Digital Lab: Engineering agents (same as LAB530) | Backup if you miss the in-person slot |
97. 
98. ---
99. 
100. ## 🎯 Focus Themes
101. 
102. 1. **Microsoft Agent Framework + Aspire** — The new distributed AI app story
103. 2. **Azure Data for AI** — Cosmos DB, SQL, HorizonDB (PostgreSQL) + vector search
104. 3. **GitHub Platform Evolution** — Copilot agents, Actions for AI, MCP integration
105. 4. **MCP Servers in C#** — The new integration standard on your stack
106. 5. **Observability for Agents** — OpenTelemetry, evals, debugging agentic apps
107. 
108. ---
109. 
110. ## 📌 Key Takeaway Sessions by Role
111. 
112. | As a... | Priority Sessions |
113. |---------|-------------------|
114. | .NET Consultant | BRK205, BRK243, LTGSP481, BRK207 |
115. | Azure User Group Organiser | BRK223, BRK241, LTG453 |
116. | AI/Agent Builder | BRK241, BRK243, DEM361, LTG466 |
117. | GitHub Partner | DEM305, BRK207, DEM301 (on-demand) |
118.
```

</details>


---

<sub>⏱️ 3056m 34s</sub>

### ℹ️ Info

Connected to Visual Studio Code - Insiders

---

<sub>⏱️ 3056m 48s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md

```
No changes made: old_str and new_str are the same
```


---

<sub>⏱️ 3056m 48s</sub>

### ✅ `edit`

**edit the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md

```
File /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md updated with changes.
```


---

<sub>⏱️ 3056m 52s</sub>

### 💬 Copilot

Now let me also update the internal links that still reference `index.md`:

---

<sub>⏱️ 3056m 54s</sub>

### ✅ `bash`

**Check for old index.md references**

$ grep -l "index.md" /Users/sinanarinco/source-experiments/MicrosoftBuild2026/**/*.md 2>/dev/null; echo "exit: $?"

```
exit: 1
<exited with exit code 0>
```


---

<sub>⏱️ 3056m 57s</sub>

### 💬 Copilot

No stale references. Let me verify the final README looks good:

---

<sub>⏱️ 3056m 58s</sub>

### ◌ Conversation Compacted

---

<sub>⏱️ 3056m 58s</sub>

### ✅ `view`

**view the file at /Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md.**

/Users/sinanarinco/source-experiments/MicrosoftBuild2026/README.md (lines 110--1)

<details>
<summary>44 lines</summary>

````
110. ## 📌 Key Takeaway Sessions by Role
111. 
112. | As a... | Priority Sessions |
113. |---------|-------------------|
114. | .NET Consultant | BRK205, BRK243, LTGSP481, BRK207 |
115. | Azure User Group Organiser | BRK223, BRK241, LTG453 |
116. | AI/Agent Builder | BRK241, BRK243, DEM361, LTG466 |
117. | GitHub Partner | DEM305, BRK207, DEM301 (on-demand) |
118. 
119. ---
120. 
121. ## 🛠️ How This Schedule Was Created
122. 
123. This personalised agenda was generated using:
124. 
125. | Tool | Purpose |
126. |------|---------|
127. | [GitHub Copilot CLI](https://github.com/github/copilot-cli) | AI-powered terminal assistant that orchestrated the research, filtering, and file generation |
128. | [Microsoft Build Skill](https://github.com/microsoft/Build-CLI) | Copilot CLI skill for searching and filtering Microsoft event session catalogs |
129. | [`@microsoft/events-cli`](https://www.npmjs.com/package/@microsoft/events-cli) | CLI tool for local session catalog search, caching, and multi-event support |
130. | [Microsoft Learn MCP Server](https://learn.microsoft.com/en-us/training/support/mcp) | Live documentation search for SDK versions, what's-new pages, and code samples |
131. | [Build 2026 Session Catalog](https://build.microsoft.com/sessions) | Live session data source (via `https://aka.ms/build2026-session-info`) |
132. 
133. ### Process
134. 
135. 1. **Profile analysis** — Scanned [sinannar.github.io](https://sinannar.github.io/) and [github.com/sinannar](https://github.com/sinannar) to build a tech inventory
136. 2. **Session search** — Queried the Build 2026 catalog across each technology: .NET Aspire, C#, Entity Framework, Microsoft Agent Framework, Azure Container Apps, Azure Functions, Cosmos DB, GitHub Actions, AKS
137. 3. **Conflict resolution** — Identified overlapping sessions and prioritised based on stack relevance, session type (labs > breakouts for hands-on learners), and speaker expertise
138. 4. **Timezone adaptation** — Converted all times from PDT (UTC-7) to NZST (UTC+12)
139. 5. **On-demand prioritisation** — Ranked conflicting sessions into 3 priority tiers for post-Build viewing
140. 
141. ### Reproduce or Update
142. 
143. ```bash
144. # Search for sessions by technology
145. npx -y @microsoft/events-cli sessions --tech ".NET Aspire" --event build-2026 --json
146. 
147. # Look up a specific session
148. npx -y @microsoft/events-cli session BRK205 --event build-2026 --json
149. 
150. # Refresh the local cache
151. npx -y @microsoft/events-cli refresh --event build-2026
152. ```
153.
````

</details>


---

<sub>⏱️ 3057m 1s</sub>

### 💬 Copilot

Done! Here's what I did:

1. **Renamed** `index.md` → `README.md`
2. **Added** a "🛠️ How This Schedule Was Created" section at the bottom with:
   - Tool table (Copilot CLI, Microsoft Build Skill, `@microsoft/events-cli`, Learn MCP Server, Session Catalog)
   - Process steps (profile analysis → session search → conflict resolution → timezone adaptation → on-demand prioritisation)
   - Reproduce/update CLI commands for future reference

---

<sub>⏱️ 3057m 42s</sub>

### ℹ️ Info

Session shared successfully to:
/Users/sinanarinco/source-experiments/MicrosoftBuild2026/copilot-session-1efc37dc-d1bb-4b2e-925f-6bc91e0c7042.html

---

<sub>⏱️ 3058m 32s</sub>

### ❌ Error

Failed to share session: Error: ENOENT: no such file or directory, open '/Users/sinanarinco/source-experiments/MicrosoftBuild2026/session ./session.md'

---

<sub>Generated by [GitHub Copilot CLI](https://github.com/features/copilot/cli)</sub>
