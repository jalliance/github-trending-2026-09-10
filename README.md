# GitHub Trending — 10 September 2026

Snapshot of [github.com/trending](https://github.com/trending) captured around **11:18 BST** on Thursday, 10 September 2026.

Filters on the source page: **Repositories · Spoken language: Any · Language: Any · Date range: Today**. GitHub listed **13** repositories. Independently confirmed against same-day archives (JackEasons, SnailDev/github-hot-hub) and the GitHub API.

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

Runnable today without an agent skill host: **teamai-cli**, **pascalorg/editor**, **TradingAgents** (research only), **PI-Desktop** installer, and the two learning repos. Everything else is mostly `SKILL.md` + hooks.

## Trending table

Star and fork counts are from the GitHub API / official trending page around capture time. **Stars today** comes from the public trending page (momentum, not lifetime quality).

| # | Repository | Lang | Stars | Forks | Stars today | What it is | Good for |
|---|---|---|---:|---:|---:|---|---|
| 1 | [ayghri/i-have-adhd](https://github.com/ayghri/i-have-adhd) | Python | 36,278 | 2,109 | 4,650 | Agent skill that forces action-first, numbered, no-preamble replies. 10 rules in `SKILL.md`. MIT. Created 2026-05-13. | Cutting coding-agent waffle. Not a medical tool. |
| 2 | [Tencent/teamai-cli](https://github.com/Tencent/teamai-cli) | TypeScript | 3,426 | 216 | 556 | npm CLI that syncs team skills, rules, MCP, hooks, and knowledge across Claude Code, Codex, Cursor, CodeBuddy, OpenCode, and others via a shared git repo. MIT. | Teams that want one harness instead of everyone maintaining CLAUDE.md by hand. |
| 3 | [obra/superpowers](https://github.com/obra/superpowers) | Shell | 284,341 | 25,431 | 688 | Jesse Vincent / Prime Radiant agentic SDLC: brainstorm → signed-off design → TDD plan → subagent execution. Plugin for Claude, Codex, Cursor, Copilot, Gemini, Grok Build, Pi, Hermes. MIT. | Disciplined multi-step coding with tests. Methodology, not a model. Do not stack on ECC. |
| 4 | [pascalorg/editor](https://github.com/pascalorg/editor) | TypeScript | 23,207 | 2,912 | 107 | Local-first 3D architectural editor (React Three Fiber + WebGPU). Browser or `npx @pascal-app/cli editor`. MCP + agent skills. Live: [editor.pascal.app](https://editor.pascal.app). MIT. | Floorplans / BIM-ish scenes you can edit locally and drive from an agent. |
| 5 | [earthtojake/text-to-cad](https://github.com/earthtojake/text-to-cad) | Python | 15,267 | 1,571 | 124 | Agent skill library for CAD/CAE/CAM: text/image → STEP/STL/3MF, plus URDF/SRDF/SDF, DXF, G-code, DfAM checks. Docs: [texttocad.dev](https://www.texttocad.dev). MIT. | Mechanical / robotics agents that need real CAD artifacts, not pictures of parts. |
| 6 | [cathrynlavery/diagram-design](https://github.com/cathrynlavery/diagram-design) | HTML | 37,166 | 2,361 | 2,249 | 38–39 editorial HTML+SVG diagram types for Claude Code / Codex / Pi. No Mermaid. Demo: [cathrynlavery.github.io/diagram-design](https://cathrynlavery.github.io/diagram-design/). MIT. | Architecture and flow diagrams that look designed. Needs an agent that loads skills. |
| 7 | [TauricResearch/TradingAgents](https://github.com/TauricResearch/TradingAgents) | Python | 104,358 | 20,000 | 367 | LangGraph multi-agent trading research framework (analysts, bull/bear debate, trader, risk, PM). Simulated execution only. Apache-2.0. Paper: arXiv:2412.20138. | Studying multi-agent market analysis. Not live money, not advice. |
| 8 | [liquidslr/system-design-notes](https://github.com/liquidslr/system-design-notes) | Markdown | 18,377 | 3,448 | 1,397 | Chapter notes for Alex Xu, *System Design Interview – An Insider’s Guide* (rate limiter, KV store, news feed, YouTube, payments, stock exchange, 28 topics). | Interview prep and a fast map of classic designs. Notes, not original research. |
| 9 | [openai/plugins](https://github.com/openai/plugins) | JavaScript | 6,336 | 834 | 498 | Official Codex plugin examples + marketplace manifests (Figma, Notion, Expo, Netlify, Remotion, iOS/web app builders). This is the 2026 Codex plugin system, not the dead 2023 ChatGPT Plugins store. | Codex users who want first-party plugin shapes to copy. |
| 10 | [freestylefly/awesome-gpt-image-2](https://github.com/freestylefly/awesome-gpt-image-2) | JavaScript | 30,544 | 2,955 | 705 | Prompt-as-code library for GPT Image 2 / 2.5: 530+ cases, 20+ industrial templates, agent skills, 2.5 same-prompt comparison. MIT. | Repeatable image-gen workflows if you already pay for GPT Image. Prompt pack, not a model. |
| 11 | [rohitg00/ai-engineering-from-scratch](https://github.com/rohitg00/ai-engineering-from-scratch) | Python | 54,011 | 9,400 | 343 | 20-phase / 500+ lesson open curriculum (math → LLMs → agents → production). Site: [aiengineeringfromscratch.com](https://aiengineeringfromscratch.com). MIT. | Structured self-study if you will actually do the work. A course, not a product. |
| 12 | [vastsa/PI-Desktop](https://github.com/vastsa/PI-Desktop) | TypeScript | 2,002 | 174 | 417 | Local-first Electron + Rust desktop workspace for coding agents. BYO model, no account required. Agent/Plan/Goal modes, plugins, MCP. Early preview 0.14.x. | People who want an agent workspace that is not locked to one IDE. Unsigned macOS builds; verify releases. |
| 13 | [affaan-m/ECC](https://github.com/affaan-m/ECC) | JavaScript | 255,484 | 38,252 | 1,133 | Kitchen-sink harness: claimed ~68 agents, ~286 skills, hooks, Memory Vault, AgentShield. `npx ecc-universal setup`. Site: [ecc.tools](https://ecc.tools). MIT. | One packaged plan→test→review loop across Claude Code / Codex / Cursor. Stars ≠ quality. Do not stack on Superpowers. |

## Themes

Agent skills and harnesses own the board again: i-have-adhd, TeamAI, Superpowers, ECC, PI-Desktop. Parallel track is spatial/visual artifacts for agents: Pascal editor, text-to-cad, diagram-design, GPT Image 2. Outliers: TradingAgents (research trading) and system-design-notes (interview notes).

Pick **one** harness (Superpowers *or* ECC *or* TeamAI), not all three.
