# GitHub Trending — 10 September 2026

Snapshot of [github.com/trending](https://github.com/trending) captured around **11:18 BST** on Thursday, 10 September 2026.

Filters on the source page: **Repositories · Spoken language: Any · Language: Any · Date range: Today**. GitHub listed **13** repositories. Independently confirmed against same-day archives and the GitHub API (`ayghri/i-have-adhd` API-confirmed at 36,278★).

This repo is a frozen briefing you can reopen later. Trending itself rotates every day. It is **not** a deployment of the 13 projects.

| Live source | This snapshot |
|---|---|
| [github.com/trending](https://github.com/trending) | Open `index.html` in a browser, or enable Pages |
| Rolling Pages (older stub) | [jalliance.github.io/github-trending-dashboard](https://jalliance.github.io/github-trending-dashboard/) |
| Yesterday | [github-trending-2026-09-09](https://github.com/jalliance/github-trending-2026-09-09) |

## How to test this later

1. Clone or download this repository and open `index.html` locally. No server required.
2. Or enable **Settings → Pages → Deploy from a branch → `main` / root** to get  
   `https://jalliance.github.io/github-trending-2026-09-10/`.
3. You already have three Grok automations for this exact job. Do not create a fourth. Keep one daily briefing; pause the rest.

The dashboard is static. No backend, no API keys, no tracking.

## What today actually is

This is not a general software leaderboard. Most of the 13 entries are agent skills, harnesses, or prompt packs. Stars measure viral agent-plugin installs, not production quality. If you wanted 13 things to deploy and click, you asked the wrong question.

Items that behave like real tools you can run today: **teamai-cli**, **pascalorg/editor**, **PI-Desktop**, **TradingAgents** (research CLI only). Everything else is mostly markdown + hooks that change how a coding agent talks, or a course / prompt gallery.

## Trending table

Star and fork counts are from the official trending page and GitHub API around capture time. **Stars today** comes from the public trending page (momentum, not lifetime quality). Totals drift by hundreds while the page is open.

| # | Repository | Lang | Stars | Forks | Stars today | What it is | Good for |
|---|---|---|---:|---:|---:|---|---|
| 1 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Python | 36,278 | 2,109 | 4,650 | Claude/Codex skill that forces action-first, numbered, no-preamble replies. 10 rules in `SKILL.md`. MIT. Created 2026-05-13. Biggest mover today. | Cutting agent waffle. Not a medical tool. Install only if your agent buries the answer. |
| 2 | [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli) | TypeScript | 3,337 | 211 | 556 | npm CLI that syncs team skills, rules, MCP, hooks, and knowledge across Claude Code, Codex, Cursor, OpenCode, and others via a shared git repo. MIT. | Teams that want one harness instead of each person hoarding `CLAUDE.md`. Context/improvement layers are beta. |
| 3 | [obra/superpowers](https://github.com/obra/superpowers) | Shell | 284,253 | 25,426 | 688 | Jesse Vincent / Prime Radiant agentic SDLC: brainstorm → signed-off design → TDD plan → subagent execution. Plugin for Claude, Codex, Cursor, Gemini, Copilot, Grok Build, Pi, Hermes. MIT. | Disciplined multi-step coding with tests. Methodology, not a model. Do not stack on ECC. |
| 4 | [pascalorg/editor](https://github.com/pascalorg/editor) | TypeScript | 23,144 | 2,910 | 107 | Local-first 3D architectural editor (React Three Fiber + WebGPU). Browser or `npx @pascal-app/cli editor`. MCP + agent skills. Live: [editor.pascal.app](https://editor.pascal.app). MIT. | Floorplans / BIM-ish scenes humans and agents can edit. Needs Node 22.13+. Not SolidWorks. |
| 5 | [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | Python | 15,221 | 1,569 | 124 | Agent skill library for CAD/CAE/CAM: STEP/STL/3MF, URDF/SRDF/SDF, DXF, G-code, Bambu dry-run. Docs: [texttocad.dev](https://www.texttocad.dev). MIT. | Mechanical / robotics agents that need real CAD artifacts, not pictures of parts. Local toolchain required. |
| 6 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | HTML | 37,023 | 2,353 | 2,249 | 39 editorial HTML+SVG diagram types for Claude Code / Codex / Pi. No Mermaid. Brand-onboards from a URL. Demo: [gallery](https://cathrynlavery.github.io/diagram-design/). MIT. | Architecture and flow diagrams that look designed. Needs an agent that loads skills. |
| 7 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | Python | 104,261 | 19,999 | 367 | Multi-agent LLM trading *research* framework (analysts, bull/bear debate, trader, risk, PM). LangGraph. Paper: [arXiv:2412.20138](https://arxiv.org/abs/2412.20138). | Studying multi-agent market analysis. Not live trading. Not advice. Needs LLM + market API keys. |
| 8 | [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes) | Markdown | 18,294 | 3,438 | 1,397 | Chapter notes for Alex Xu, *System Design Interview* Vol 1+2 (rate limiter, KV store, news feed, YouTube, payments, etc.). | Interview prep and a map of classic designs. Notes, not original systems. |
| 9 | [openai/plugins](https://github.com/openai/plugins) | JavaScript | 6,311 | 833 | 498 | Official Codex plugin examples + marketplace manifests (Figma, Notion, Expo, Netlify, Remotion, iOS/web builders). | Codex users copying first-party plugin shape. Sample catalog, not a runtime. |
| 10 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | JavaScript | 30,417 | 2,944 | 705 | Prompt-as-code library for GPT Image 2 / 2.5: 530+ cases, 20+ industrial templates, agent skill. Site: [gpt-image2.canghe.ai](https://gpt-image2.canghe.ai/). | Repeatable image-gen workflows if you already pay for GPT Image. Prompt pack, not a model. |
| 11 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Python | 53,937 | 9,396 | 343 | 523-lesson / 20-phase MIT curriculum from math → LLMs → agents → production. Site: [aiengineeringfromscratch.com](https://aiengineeringfromscratch.com). | Structured self-study if you will actually build. A course, not a product. |
| 12 | [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop) | TypeScript | 1,925 | 168 | 417 | Local-first Electron + Rust desktop workspace for coding agents. BYO model. Agent/Plan/Goal modes, plugins, MCP. Early preview 0.14.x. LGPL-3.0. | An agent workspace that is not locked to one IDE. Verify release binaries. Unsigned macOS builds. |
| 13 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | JavaScript | 255,413 | 38,245 | 1,133 | Kitchen-sink harness: ~68 agents, ~280 skills, hooks, memory vault, AgentShield. `npx ecc-universal setup`. Site: [ecc.tools](https://ecc.tools). MIT. | One packaged plan→test→review loop. Stars ≠ quality. Do not stack on Superpowers. |

## What the list is saying

Three currents dominate:

1. **Agent skills and harnesses as a product category.** i-have-adhd, Superpowers, ECC, TeamAI, and PI-Desktop are all "change how my coding agent behaves." Stars here measure plugin virality.
2. **Spatial / visual artifacts for agents.** Pascal Editor, text-to-cad, diagram-design, and GPT Image 2 prompts want agents to emit buildings, parts, diagrams, and pictures — not just code.
3. **Study material.** TradingAgents (research scaffold) and system-design-notes / ai-engineering-from-scratch (reading + exercises).

Pick **one** harness (Superpowers *or* ECC *or* TeamAI), not all three.

## Existing automations

Do not create a fourth copy of this job.

| Name | Task ID | Schedule | Status |
|---|---|---|---|
| github-trending-briefing | `2d49e2ee-aa12-4206-b738-afbcd3c5dd3b` | Daily 09:00 Europe/London | Active |
| github-trending-daily | `35d4408d-90b2-4f55-87f8-9c0162878231` | Daily 09:00 Europe/London | Paused |
| GitHub trending | `bd336ad4-9df6-4b51-b4da-34d77cf3cbcb` | Daily 11:05 Europe/London | Active (this run) |

Say "run github-trending-briefing now" to regenerate on demand.
