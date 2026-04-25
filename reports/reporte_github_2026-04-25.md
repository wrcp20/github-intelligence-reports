# GitHub Intelligence Report — CLI AI Agents & LLM Frameworks
**Date:** 2026-04-25  
**Focus:** CLI AI Agents, LLM Frameworks, OpenClaw/ClawPanel, Hermes Agent Ecosystem

---

## Executive Summary

The CLI AI agent and LLM framework space continues its rapid growth. Hermes Agent shipped its biggest release in months (v0.11.0), featuring a full React/Ink TUI rewrite. OpenClaw's management panel (ClawPanel) hit v0.14.0 the same day. LangChain and LangGraph remain the dominant framework layer, while openai-agents-python and mastra are the fastest-rising challengers. Gemini CLI is the breakout star of the week with over 102K stars.

---

## 1. Hermes Agent Ecosystem

### NousResearch/hermes-agent
| Metric | Value |
|--------|-------|
| Stars | 116,574 |
| Forks | 17,184 |
| Language | Python |
| Last Updated | 2026-04-25 |
| Latest Release | **v0.11.0** (2026-04-23) |

**Release Highlights — v0.11.0 "The Interface Release"**  
_1,556 commits · 761 merged PRs · 1,314 files changed · 224,174 insertions since v0.9.0_

- **New Ink-based TUI** — `hermes --tui` is a full React/Ink rewrite of the interactive CLI, with a Python JSON-RPC backend (`tui_gateway`). Includes sticky composer, live streaming with OSC-52 clipboard support, stable picker keys, a status bar with per-turn stopwatch and git branch, `/clear` confirm, light-theme preset, and a subagent spawn observability overlay.
- **Transport ABC + Native AWS Bedrock** — New pluggable transport architecture under every provider, with native AWS Bedrock support added.
- **5 new inference paths** including GPT-5.5 via Codex OAuth.
- **17th messaging platform support** — QQBot integration.
- **Dramatically expanded plugin surface** — This release also folds in highlights deferred from v0.10.0 (which shipped only the Nous Tool Gateway).

**Topics:** `ai-agent`, `llm`, `claude`, `claude-code`, `openai`, `openclaw`, `hermes`, `nous-research`, `codex`

---

### qingchencloud/clawpanel (OpenClaw Panel)
| Metric | Value |
|--------|-------|
| Stars | 2,534 |
| Forks | 324 |
| Language | JavaScript (Tauri v2) |
| Last Updated | 2026-04-25 |
| Latest Release | **v0.14.0** (2026-04-25) |

Multi-engine AI management panel for **OpenClaw & Hermes Agent**. Built as a cross-platform desktop app (Tauri v2) with support for 11 languages. Features built-in AI assistant with tool calling, image recognition, and multimodal support, plus one-click install of both OpenClaw and Hermes Agent engines.

**v0.14.0** shipped today with builds for macOS (Apple Silicon + Intel), Windows, and Linux.

---

### jnMetaCode/agency-agents-zh
| Metric | Value |
|--------|-------|
| Stars | 8,390 |
| Description | 211 plug-and-play AI expert roles — supports Hermes Agent / Claude Code / Cursor / Copilot and 16 other tools |

---

## 2. LLM Frameworks — Top Repositories

| Repository | Stars | Latest Release | Released |
|------------|-------|---------------|----------|
| langchain-ai/langchain | 134,891 | `langchain-core==1.3.2` | 2026-04-24 |
| FoundationAgents/MetaGPT | 67,418 | — | — |
| TauricResearch/TradingAgents | 52,922 | — | — |
| run-llama/llama_index | 48,926 | — | — |
| langchain-ai/langgraph | 30,361 | `langgraph-prebuilt==1.0.11` | 2026-04-24 |
| openai/openai-agents-python | 25,124 | `v0.14.6` | 2026-04-25 |
| deepset-ai/haystack | 24,990 | — | — |
| mastra-ai/mastra | 23,319 | `@mastra/core@1.27.0` | 2026-04-24 |
| humanlayer/12-factor-agents | 19,482 | — | — |
| TransformerOptimus/SuperAGI | 17,476 | — | — |

**LangChain** (`langchain-core==1.3.2`) and **LangGraph** (`langgraph-prebuilt==1.0.11`) both released yesterday, continuing their cadence of near-daily micro-releases. **openai-agents-python** `v0.14.6` shipped today — its rapid 0.x versioning reflects heavy active development since launch. **Mastra** `@mastra/core@1.27.0` also released yesterday ("April 23, 2026" edition).

---

## 3. CLI AI Agents — Top Repositories

| Repository | Stars | Description |
|------------|-------|-------------|
| google-gemini/gemini-cli | 102,391 | Open-source AI agent bringing Gemini into your terminal |
| OpenHands/OpenHands | 72,072 | AI-Driven Development (release: 1.6.0 / 2026-03-30) |
| badlogic/pi-mono | 40,021 | AI agent toolkit: coding agent CLI, unified LLM API, TUI & web UI |
| continuedev/continue | 32,791 | Source-controlled AI checks, enforceable in CI. Open-source Continue CLI |
| plandex-ai/plandex | 15,291 | Open source AI coding agent for large projects (release: cli/v2.2.1) |
| superset-sh/superset | 10,007 | Code editor for the AI agents era — run Claude Code, Codex, etc. |
| sigoden/aichat | 9,887 | All-in-one LLM CLI tool: Shell Assistant, Chat-REPL, RAG, AI Agents |
| campfirein/byterover-cli | 4,641 | ByteRover CLI (brv) — portable memory layer for autonomous coding agents |

**gemini-cli** is the dominant new entrant with 102K stars — the fastest-growing CLI AI agent in recent weeks. **badlogic/pi-mono** at 40K stars is notable as an integrated toolkit covering CLI agents, unified LLM API, TUI/web UI libraries, and Slack bot in a mono-repo. **sigoden/aichat** (`v0.30.0`) remains the most feature-complete all-in-one LLM CLI tool for power users.

---

## 4. Notable Releases This Week

| Project | Version | Date | Key Change |
|---------|---------|------|------------|
| NousResearch/hermes-agent | v0.11.0 | 2026-04-23 | Full React/Ink TUI rewrite, AWS Bedrock, GPT-5.5 |
| qingchencloud/clawpanel | v0.14.0 | 2026-04-25 | Cross-platform builds, OpenClaw + Hermes engine support |
| openai/openai-agents-python | v0.14.6 | 2026-04-25 | Multi-agent workflow framework update |
| langchain-ai/langchain | langchain-core==1.3.2 | 2026-04-24 | Core library patch |
| langchain-ai/langgraph | langgraph-prebuilt==1.0.11 | 2026-04-24 | Prebuilt node update |
| mastra-ai/mastra | @mastra/core@1.27.0 | 2026-04-24 | Core framework release |

---

## 5. Ecosystem Signals

- **Hermes Agent** has become a cross-ecosystem standard: its topics include `claude-code`, `openai`, `codex`, `openclaw` — positioning it as a multi-provider agent hub rather than a single-vendor tool.
- **OpenClaw** surfaces primarily as a management panel engine (`clawpanel`) rather than a standalone framework; the real development activity is in the Hermes Agent core.
- **"Paperclip LLM"** — no significant GitHub repositories found under this name. May refer to a private project or a different naming convention.
- **Gemini CLI** at 102K stars in just weeks signals Google's aggressive push into the terminal-native AI space, directly competing with Claude Code, OpenHands, and Plandex.
- The **LangChain ecosystem** (LangChain + LangGraph) remains the most-starred LLM framework stack with 165K+ combined stars and near-daily release cadence.

---

*Report generated automatically via GitHub API on 2026-04-25.*
