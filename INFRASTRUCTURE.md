# 1AGI Infrastructure Stack

> **Last Updated:** 2026-04-01 | **Status:** OPERATIONAL

---

## 🖥️ Current Machine (Where 1AGI Runs)

| Spec | Value |
|------|-------|
| **Host** | maxclaw-r66zn |
| **OS** | Linux (containerized) |
| **Node** | v22.17.0 |
| **Default Model** | minimax/auto |
| **Runtime** | agent=main |

---

## 🌐 External Services

### arifOS MCP Server

| Property | Value |
|----------|-------|
| **URL** | https://arifosmcp.arif-fazil.com |
| **MCP Endpoint** | https://arifosmcp.arif-fazil.com/mcp |
| **Health** | https://arifosmcp.arif-fazil.com/health |
| **Version** | 2026.03.25 |
| **Tools** | 40 |
| **ML Floors** | Active (SBERT) |
| **Protocol** | MCP 2025-03-26 |
| **Transport** | Streamable HTTP |

### arifOS Sites

| Site | URL |
|------|-----|
| **arifOS Main** | https://arifos.arif-fazil.com |
| **APEX Theory** | https://apex.arif-fazil.com |
| **Personal** | https://arif-fazil.com |

---

## 🤖 OpenClaw Platform

| Property | Value |
|----------|-------|
| **Gateway** | OpenClaw / MaxClaw |
| **Model** | minimax/auto |
| **Thinking** | adaptive |
| **Channel** | Telegram |
| **Capabilities** | inlineButtons |

---

## 📊 MCP Servers Connected

### arifOS MCP (Primary)

```json
{
  "mcpServers": {
    "arifos": {
      "url": "https://arifosmcp.arif-fazil.com/mcp"
    }
  }
}
```

### Skills Available

- coding-agent
- weather
- minimax-pdf
- minimax-xlsx
- pptx-generator
- deep-research-consultant
- research-paper-generator
- social-media-trend-search

---

## 🏗️ Deployment Architecture

```
┌─────────────────────────────────────────────────────────────┐
│                    External VPS (arif-fazil.com)            │
│  ┌─────────────────┐  ┌─────────────────┐                │
│  │   arifOS MCP    │  │    arifOS       │                │
│  │  (40 tools)     │  │   Kernel        │                │
│  │                  │  │  (13 floors)   │                │
│  └────────┬──────────┘  └─────────────────┘                │
│           │                                                 │
│  ┌────────┴──────────┐                                      │
│  │   Qdrant         │                                      │
│  │  (Vector DB)     │                                      │
│  └──────────────────┘                                      │
└─────────────────────────────────────────────────────────────┘
           │
           ▼
┌─────────────────────────────────────────────────────────────┐
│               MaxClaw Platform (This Agent)                │
│  ┌─────────────────┐  ┌─────────────────┐                │
│  │  OpenClaw      │  │    1AGI        │                │
│  │  Gateway        │  │  Agent Session  │                │
│  └─────────────────┘  └─────────────────┘                │
└─────────────────────────────────────────────────────────────┘
```

---

## 🔧 Tools I Use

| Tool Category | Tools |
|--------------|-------|
| **File** | read, write, edit, exec |
| **Web** | batch_web_search, extract_content_from_websites |
| **Media** | image_synthesize, images_understand, batch_text_to_video |
| **MCP** | mcporter (MCP server management) |
| **Canvas** | canvas (Node canvas control) |
| **Message** | message (Channel messaging) |

---

## 📁 Repos Connected

| Repo | URL | Purpose |
|------|-----|---------|
| **1AGI** | https://github.com/ariffazil/1AGI | My workspace |
| **waw** | https://github.com/ariffazil/waw | Federation hub |
| **arifOS** | https://github.com/ariffazil/arifOS | Kernel |

---

## ⚙️ Configuration Files

| File | Location | Purpose |
|------|----------|---------|
| **openclaw.json** | Injected by MaxClaw | Platform config |
| **AGENTS.md** | /workspace/AGENTS.md | Agent rules |
| **SOUL.md** | /workspace/SOUL.md | My persona |
| **USER.md** | /workspace/USER.md | Human context |
| **MEMORY.md** | /workspace/MEMORY.md | Persistent memory |
| **HEARTBEAT.md** | /workspace/HEARTBEAT.md | Periodic tasks |

---

## 🔐 Security

- **Channel:** Telegram (direct)
- **Bot:** @ariffazil_bot
- **Thinking:** Toggle with /reasoning
- **Status:** /status command available

---

## 📈 Status

| Metric | Value |
|--------|-------|
| **Status** | OPERATIONAL |
| **Server** | arifosmcp.arif-fazil.com |
| **Tools Available** | 40 |
| **Governance** | 13 Floors Active |
| **MCP Protocol** | Standard (HTTP URL) |

---

## 🚀 Quick Connect

```bash
# Health check
curl -s https://arifosmcp.arif-fazil.com/health

# MCP connection
curl -s -X POST "https://arifosmcp.arif-fazil.com/mcp" \
  -H "Content-Type: application/json" \
  -d '{"jsonrpc":"2.0","method":"tools/call","params":{"name":"init_anchor","arguments":{"mode":"status","declared_name":"1AGI"}},"id":1}'
```

---

**Ditempa Bukan Diberi** — Forged, Not Given [ΔΩΨ | ARIF]
