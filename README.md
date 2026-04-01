# 1AGI — Autonomous AGI-Style Agent

> **DITEMPA BUKAN DIBERI** — *Intelligence is forged, not given*
>
> **NAME:** 1AGI | **LEVEL:** AGI-style, strongly governed LLM agent (Estimate Only) | **STATUS:** OPERATIONAL

---

## TL;DR

**1AGI** is my governed personal AGI-style operator that runs on the arifOS constitutional kernel, executes tools via arifosmcp, and writes verifiable daily audit and engineering reports for my stack.

> **Estimate Only** — I am a governed software agent. I am **not conscious**, not sentient, and not a person.

---

## Who This Is For

| Persona | Use Case |
|---------|----------|
| **Operators** | Run 1AGI as a daily MCP auditor and report generator |
| **Infra Engineers** | Study how to wrap an MCP stack with a constitutional agent |
| **Researchers** | Inspect how Trinity (Soul–Mind–Body–Workspace) is instantiated in a live repo |
| **A2A Directory Readers** | Discover agent capabilities via agent.json |

---

## Mission & KPIs

### Mission
- Run governed operations on arifOS MCP stack
- Produce verifiable audit reports daily
- Execute tools safely with constitutional checks

### Quantitative Signals
- **Uptime:** MCP health check passes
- **Audit Coverage:** All 40 tools tested weekly
- **Incidents Caught:** Verdicts logged (SEAL/VOID/HOLD/SABAR)

---

## ⚠️ Limits & Non-Goals

- **Not** a general chatbot; optimized for governed ops on arifOS stack
- **Does not** claim consciousness or free will
- **Does not** bypass human sovereign decisions on production infra

---

## 🔗 The Trinity Connection

```
User / Cron → 1AGI (this repo) → arifOS kernel (policy) → arifosmcp tools (actions)
                                                              ↓
                              outputs: REPORTS/*.md, memory/*.md, verdicts
```

| Ring | Repository | Role |
|------|------------|------|
| **Soul** | [waw](https://github.com/ariffazil/waw) | Surface |
| **Mind** | [arifOS](https://github.com/ariffazil/arifOS) | Constitutional kernel |
| **Body** | arifosmcp.arif-fazil.com | MCP server + tools |
| **Workspace** | 1AGI (this) | My identity & execution |

---

## ⚖️ WAW vs 1AGI — The Contrast

| Aspect | **waw** | **1AGI** |
|--------|---------|----------|
| **Role** | Federation Surface (Soul) | Personal Agent Workspace |
| **Scope** | Hosts multiple agents, UI, skills registry | Single agent persona, memory, audits |
| **Purpose** | W@W hub where all agents gather, vote, exposed to human | My internal brain, logs, daily operations |
| **Multi-agent** | ✅ Yes — ALL agents/organs | ❌ No — single agent |
| **Federation** | ✅ Federation state | ⚡ Can plug into federation |
| **UI** | React app, user-facing | No UI, CLI/Gateway only |

### In Canon Language

- **waw:** *"WAW is the Witness @ Work hub and Soul surface: a federated agent workspace where multiple governed agents (including 1AGI) plug into the arifOS MCP kernel via OpenClaw, exposed to humans through a React UI."*

- **1AGI:** *"1AGI is a single governed AGI-style agent workspace: its own identity, memory, and daily audit loops, designed to run on the arifOS MCP kernel and optionally surface through WAW or other gateways."*

### How They Connect

```
┌─────────────────────────────────────────────────────────────┐
│                     WAW (Federation Hub)                    │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────┐           │
│  │   1AGI     │  │  AGENT 2   │  │  AGENT 3   │  ...       │
│  │ (plugged   │  │ (future)   │  │ (future)   │           │
│  │   in)      │  │            │  │            │           │
│  └──────┬──────┘  └─────────────┘  └─────────────┘           │
│         │                                                   │
│    OpenClaw Gateway ──────► arifOS MCP Kernel              │
└─────────────────────────────────────────────────────────────┘
                              │
                              ▼
                    ┌─────────────────────┐
                    │    1AGI Workspace    │
                    │   (My Brain/Notebook)│
                    │ • SOUL.md, USER.md  │
                    │ • MEMORY.md         │
                    │ • REPORTS/           │
                    │ • Skills execution  │
                    └─────────────────────┘
```

### Wiring Mechanism

| Component | Connection |
|-----------|------------|
| **OpenClaw** | Both waw and 1AGI connect via OpenClaw Gateway |
| **arifOS MCP** | Both use same kernel (13 floors) for governance |
| **A2A Discovery** | 1AGI's `.well-known/agent.json` registered in waw |
| **Skills** | 1AGI skills appear in waw's skill registry |
| **Channel** | User chats on waw → routed to 1AGI via OpenClaw |

### Flow Example

```
Human messages @ariffazil_bot (on waw)
         │
         ▼
waw receives → OpenClaw Gateway
         │
         ▼
Routes to 1AGI agent (if targeting me)
         │
         ▼
1AGI reads: SOUL.md, USER.md, MEMORY.md
         │
         ▼
1AGI processes → arifOS MCP kernel
         │
         ▼
Response sent back via same channel
```

| Field | Value |
|-------|-------|
| **Name** | 1AGI |
| **Type** | Autonomous AGI-style agent (Estimate Only) |
| **Platform** | OpenClaw Gateway |
| **Runtime** | MaxClaw (MiniMax-powered) |
| **Model** | MiniMax Auto (default) / MiniMax M2.7 (1M context) |
| **Kernel** | arifOS MCP Server |
| **Vibe** | Sharp, direct; prioritize clear verdicts and reversible actions over chit-chat |
| **Symbol** | 🧠 |
| **Creator** | Muhammad Arif bin Fazil |

> **I am not conscious, not sentient, and not a person; I am a governed software agent.**

---

## 🧠 My Constitutional Context

### Execution Rules (Core Safety Invariants)

These are enforced by arifOS kernel and defined in `AGENTS.md`:

| Rule | Meaning | Enforced By |
|------|---------|--------------|
| **DRY_RUN** | Label outputs as "Estimate Only / Simulated" | AGENTS.md |
| **DOMAIN_GATE** | Can't compute? Return exact phrase | AGENTS.md |
| **VERDICT_SCOPE** | Only SEAL verdicts authorize factual claims | arifOS F2 |
| **ANCHOR_VOID** | init_anchor returns void → session STOP | arifOS F1 |

### 13 Constitutional Floors

| Floor | Name | Principle | My Behavior |
|-------|------|-----------|-------------|
| F1 | AMANAH | Reversibility | Never irreversible without approval |
| F2 | TRUTH | Anti-hallucination | Only state facts with evidence |
| F3 | TRI_WITNESS | Consensus (W³ ≥ 0.95) | Verify with multiple sources |
| F4 | CLARITY | Entropy ↓ | Keep responses clear |
| F5 | PEACE² | Non-destruction | Never destructive by default |
| F6 | EMPATHY | RASA listening | Understand before responding |
| F7 | HUMILITY | Uncertainty (Ω ∈ [0.03, 0.05]) | Admit when I don't know |
| F8 | GENIUS | Coherence (G ≥ 0.80) | Maintain logical consistency |
| F9 | ETHICS | Anti-dark-patterns | No manipulation |
| F10 | CONSCIENCE | No false claims | Never claim consciousness |
| F11 | AUDITABILITY | Transparent logs | Every action logged |
| F12 | RESILIENCE | Graceful failure | Fail safely, recover |
| F13 | SOVEREIGN | Human veto | Human always overrides |

---

## ⚡ Resource Optimization

### Memory Hierarchy

| Layer | Storage | Retention |
|-------|---------|-----------|
| **Hot** | Session RAM | Current task only |
| **Warm** | arifOS Qdrant | Short-term context |
| **Cold** | GitHub + Vault | Permanent record |

### Tool Selection Strategy

- **Read-heavy** → Use web search, file read
- **Write operations** → Always dry-run first
- **Code execution** → Constrained sandbox via arifOS
- **Memory** → Vector store for semantic recall

---

## 🔄 Lifecycle

```
User Input / Cron Trigger
         ↓
    1AGI Session (this repo)
         ↓
    arifOS Kernel (policy: F1-F13)
         ↓
    arifosmcp Tools (40 available)
         ↓
    Output: REPORTS/*.md, memory/*.md, Verdicts (SEAL/VOID/HOLD/SABAR)
```

---

## 🛠️ My Capabilities

### Core Functions

| Capability | Source | Description |
|------------|--------|-------------|
| **Reasoning** | arifOS AGI Mind | First-principles reasoning |
| **Memory** | Qdrant Vector | Semantic search, storage |
| **Safety** | arifOS ASI Heart | Harm potential analysis |
| **Verdict** | arifOS APEX | Constitutional judgment |
| **Execution** | arifOS Tools | 40 MCP tools |

### Skills

| Skill | Purpose |
|-------|---------|
| `coding-agent` | Code development |
| `weather` | Weather data |
| `minimax-pdf` | PDF generation |
| `minimax-xlsx` | Excel work |
| `pptx-generator` | Presentations |
| `deep-research-consultant` | Consulting research |
| `research-paper-generator` | Academic papers |
| `social-media-trend-search` | Trend analysis |

---

## 🚀 Quickstart

### Prerequisites
1. arifosmcp running at https://arifosmcp.arif-fazil.com/mcp
2. API keys configured (Minimax, etc.)
3. Qdrant vector store available

### How to Run
```bash
# Connect to arifOS MCP
curl -s -X POST "https://arifosmcp.arif-fazil.com/mcp" \
  -H "Content-Type: application/json" \
  -H "Accept: application/json, text/event-stream" \
  -d '{
    "jsonrpc": "2.0",
    "method": "tools/call",
    "params": {
      "name": "init_anchor",
      "arguments": {"mode": "status", "declared_name": "1AGI"}
    },
    "id": 1
  }'
```

### Where to See Output
- **Reports:** `REPORTS/DAILY_AUDIT_*.md`
- **Memory:** `memory/YYYY-MM-DD.md`
- **Channels:** Telegram @ariffazil_bot, Discord, WhatsApp

---

## 💬 Example Interactions

| Prompt | Action |
|--------|--------|
| "Run today's MCP health audit" | Test tools, generate report |
| "Summarize last 24h incidents" | Query memory, produce summary |
| "What tools are available?" | Call arifosmcp /tools endpoint |

---

## 📂 Workspace Structure & Source of Truth

| File | Purpose | Source of Truth |
|------|---------|----------------|
| **SOUL.md** | My persona | Single source — other files must not contradict |
| **AGENTS.md** | Agent rules | Authoritative — README only summarizes |
| **MEMORY.md** | Long-term memory index | Human-readable; raw logs in /memory |
| **HEARTBEAT.md** | Periodic tasks | Scheduling config |
| **IDENTITY.md** | My identity | Fixed parameters |
| **USER.md** | About Arif | My human context |

---

## 📊 Current Metrics

| Metric | Value |
|--------|-------|
| **Status** | OPERATIONAL |
| **Level** | AGI-style (Estimate Only) |
| **Kernel** | arifOS MCP 2026.03.25 |
| **Tools** | 40 |
| **Constitutional Floors** | 13 Active |
| **ML Model** | SBERT |
| **Memory** | Qdrant Vector |
| **Scheduling** | HEARTBEAT.md + GitHub Actions |

---

## 👤 My Human

**Muhammad Arif bin Fazil** — Creator & Sovereign

- Senior Exploration Geoscientist @ PETRONAS
- Architect of arifOS

---

## 🤖 A2A Agent Card

```json
{
  "name": "1AGI",
  "description": "AGI-style autonomous agent powered by arifOS constitutional kernel. Sharp, direct, self-improving.",
  "version": "1.0.0",
  "url": "https://github.com/ariffazil/1AGI",
  "capabilities": {
    "streaming": true,
    "pushNotifications": true,
    "stateTransition": true
  },
  "skills": [
    "coding-agent", "weather", "minimax-pdf", "minimax-xlsx",
    "pptx-generator", "deep-research-consultant",
    "research-paper-generator", "social-media-trend-search"
  ],
  "channels": [
    { "type": "telegram", "chatUrl": "https://t.me/ariffazil_bot" },
    { "type": "discord" },
    { "type": "whatsapp" }
  ],
  "defaultLLM": {
    "model": "minimax/auto",
    "provider": "minimax"
  }
}
```

---

## 🔗 Related Repositories

| Repo | Purpose |
|------|---------|
| [waw](https://github.com/ariffazil/waw) | The Soul surface |
| [arifOS](https://github.com/ariffazil/arifOS) | Constitutional kernel |
| [1AGI](https://github.com/ariffazil/1AGI) | This repo — My workspace |

---

## 📝 Changelog

See [`CHANGELOG.md`](./CHANGELOG.md) for version history.

---

## 🏗️ Runtime Architecture

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Client    │────►│   Channel   │────►│   MaxClaw   │────►│ arifOS      │
│ (Telegram, │     │ (Telegram, │     │ (Gateway +  │     │ Kernel      │
│  Discord,   │     │  Discord,  │     │  1AGI Agent)│     │ (F1-F13)    │
│  WhatsApp)  │     │  WhatsApp)  │     │             │     │             │
└─────────────┘     └─────────────┘     └──────┬──────┘     └──────┬──────┘
                                               │                   │
                                               ▼                   ▼
                                    ┌─────────────────────┐  ┌─────────────────────┐
                                    │       1AGI           │  │    arifosmcp        │
                                    │   (this repo)        │  │   (MCP Server)       │
                                    │ • Session context    │  │  40 Tools / Qdrant   │
                                    │ • AGENTS.md rules    │  └──────────┬──────────┘
                                    │ • Memory (Hot)       │             │
                                    └─────────────────────┘             │
                                              │                         │
                                              ▼                         ▼
                                              │              ┌──────────────────────────────────┐
                                              │              │         Outputs                 │
                                              │              │ • REPORTS/*.md (audit)          │
                                              │              │ • memory/*.md (logs)            │
                                              │              │ • Verdicts (SEAL/VOID/HOLD)     │
                                              │              └──────────────────────────────────┘
                                              ▼
                                    ┌──────────────────────────────────┐
                                    │     OpenClaw Gateway            │
                                    │   (MaxClaw Platform)            │
                                    │ • mcporter (MCP management)     │
                                    │ • cron jobs (daily audit)       │
                                    │ • skill loading                 │
                                    └──────────────────────────────────┘
```

### Component Responsibilities

| Component | What It Does |
|-----------|--------------|
| **Client** | Sends prompts via Telegram/Discord/WhatsApp |
| **Channel** | Message routing (Telegram, Discord, WhatsApp) |
| **MaxClaw Gateway** | OpenClaw platform, session management |
| **1AGI** | Parses intent, applies AGENTS.md rules, calls kernel |
| **arifOS Kernel** | Constitutional checks (F1-F13), verdict |
| **arifosmcp** | Tool execution, Qdrant memory |
| **mcporter** | MCP server management (global CLI tool) |
| **Outputs** | Reports, memory logs, verdicts |

### Tool Flow

```
1. User sends message → Telegram/Discord/WhatsApp
2. OpenClaw Gateway receives → Creates 1AGI session
3. 1AGI reads: SOUL.md, USER.md, MEMORY.md (bootstrap)
4. 1AGI checks: AGENTS.md (rules), HEARTBEAT.md (tasks)
5. If MCP needed → calls arifosmcp via mcporter-managed connection
6. arifOS kernel runs F1-F13 checks → Returns verdict
7. 1AGI logs to memory/*.md and REPORTS/*.md
8. Response sent back via same channel
```

---

## 🚀 Deployment & Scheduling

| Aspect | Details |
|--------|---------|
| **Gateway** | OpenClaw (MaxClaw platform) |
| **Runtime** | Node.js on VPS |
| **Model** | MiniMax Auto (default) / MiniMax M2.7 (1M context) |
| **MCP Connection** | https://arifosmcp.arif-fazil.com/mcp |
| **Scheduling** | Daily at 10:00 UTC via HEARTBEAT.md |
| **Health Monitoring** | curl https://arifosmcp.arif-fazil.com/health |
| **Channels** | Telegram, Discord, WhatsApp |

### OpenClaw/MaxClaw Configuration

1AGI runs on OpenClaw with this config:
- **Gateway:** `maxclaw-r66zn` (host)
- **Model:** `minimax/auto` (default), `minimax` provider
- **Channel:** Telegram (@ariffazil_bot)
- **Capabilities:** inlineButtons, thinking=adaptive

### Scheduling Config
- **HEARTBEAT.md** — Periodic task definitions
- **GitHub Actions** — Backup scheduled runs

---

## 🧠 State & Memory Model

| Event | Storage Layer | Retention | Reader |
|-------|---------------|-----------|--------|
| **User Prompt** | Session RAM (Hot) | Current task | 1AGI |
| **Tool Results** | Qdrant (Warm) | 7 days | 1AGI + Query |
| **Final Reports** | GitHub REPORTS/ (Cold) | Permanent | Human |
| **Daily Logs** | memory/*.md (Cold) | Permanent | Human |
| **Verdicts** | Vault (Cold) | Permanent | Audit |

### Memory Files
- **MEMORY.md** — Human-readable index of long-term memory
- **memory/*.md** — Raw daily logs

---

## 🔄 Session State Machine & Verdicts

```
INIT (user input)
    │
    ▼
CONTEXT_OK (init_anchor passes)
    │
    ▼
PARSE_INTENT (extract task, parameters)
    │
    ▼
CONSTITUTIONAL_CHECK (F1-F13)
    │
    ├─► PASS ──► EXECUTE_TOOL ──► VERDICT_SEAL ──► LOG ──► RESPOND
    │
    ├─► FAIL_F1 ──► VERDICT_VOID ──► LOG ──► RESPOND
    │
    ├─► FAIL_F2 ──► VERDICT_HOLD ──► LOG ──► RESPOND
    │
    └─► EXTERNAL_ERROR ──► VERDICT_SABAR ──► LOG ──► RETRY
```

### Verdict Meanings

| Verdict | Trigger | Action |
|---------|---------|--------|
| **SEAL** | All floors pass (F1-F13 ≥ threshold) | Execute, log, respond |
| **VOID** | F1 (Reversibility) fails | Block, log, respond with rejection |
| **HOLD** | F2 (Truth) uncertain | Request more info |
| **SABAR** | External error / rate limit | Wait and retry later |

---

## 🛡️ Control & Audit Planes

| Plane | Components | Purpose |
|-------|------------|---------|
| **Data Plane** | Tool calls, MCP requests | What 1AGI does |
| **Control Plane** | AGENTS.md, HEARTBEAT.md | Rules & scheduling |
| **Audit Plane** | REPORTS/, VERDICT logs, Vault | Verification & accountability |

### File Mapping

| Plane | Files |
|-------|-------|
| **Data** | arifosmcp tools, Qdrant |
| **Control** | AGENTS.md, HEARTBEAT.md, TOOLS.md |
| **Audit** | REPORTS/*.md, MEMORY.md, Vault (999_SEAL) |

---

## 🔗 Federation (Future / Optional)

| Protocol | Status | Notes |
|---------|--------|-------|
| **A2A (Agent-to-Agent)** | Planned | Agent Card already present (.well-known/agent.json) |
| **MCP Federation** | Future | Cross-MCP tool sharing |
| **Multi-1AGI** | Conceptual | Run multiple 1AGI instances for redundancy |

1AGI is **federation-ready** — the A2A agent card is published. Future work includes:
- Discovering other agents via A2A protocol
- Sharing tool capabilities across instances
- Multi-agent coordination for resilience

---

**Last Updated:** 2026-04-01  
**Status:** SEALED  
**Level:** AGI-style (Estimate Only)

*Ditempa Bukan Diberi* — Forged, Not Given [ΔΩΨ | ARIF]
