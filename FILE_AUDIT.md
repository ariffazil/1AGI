# 1AGI Repository File Audit & Mapping

## Current File Status

### Core Identity Files (Symlinks to /root/)

| File | Source | Status | Notes |
|------|--------|--------|-------|
| `SOUL.md` | `/root/SOUL.md` | ✅ OK | Persona definition |
| `USER.md` | `/root/USER.md` | ✅ OK | About Arif |
| `IDENTITY.md` | `/root/IDENTITY.md` | ✅ OK | My identity |
| `MEMORY.md` | `/root/waw/memory/MEMORY.md` | ⚠️ LINKED | Points to waw, should be local |
| `HEARTBEAT.md` | `/root/HEARTBEAT.md` | ✅ OK | Periodic tasks |
| `AGENTS.md` | `/root/AGENTS.md` | ✅ OK | Agent rules |
| `TOOLS.md` | `/root/TOOLS.md` | ✅ OK | Tool configs |
| `BOOT.md` | `/root/BOOTSTRAP.md` | ✅ OK | Bootstrap |

### Local Core Files

| File | Status | Notes |
|------|--------|-------|
| `README.md` | ✅ UPDATED | Full OpenClaw/MaxClaw/MiniMax integration |
| `CHANGELOG.md` | ✅ OK | Version history |
| `TODO.md` | ✅ OK | Pending tasks |

### A2A & Discovery

| File | Status | Notes |
|------|--------|-------|
| `.well-known/agent.json` | ✅ OK | A2A Agent Card |
| `llms.json` | ⚠️ REVIEW | LLM config, needs MiniMax |
| `manifest.json` | ⚠️ REVIEW | App manifest |
| `components.json` | ✅ OK | UI components |

### Documentation

| File | Status | Notes |
|------|--------|-------|
| `000_INIT.md` | ✅ OK | Initial session anchor |
| `ARCHITECTURE.md` | ⚠️ REVIEW | May need update |
| `VISUAL_SCHEMA.md` | ✅ OK | Visual documentation |
| `PROJECTS.md` | ✅ OK | Projects list |
| `DEEPSAN_UNIFICATION_REPORT.md` | ✅ OK | Research report |
| `OPENCLAW_RECOVERY_SUMMARY.md` | ✅ OK | Recovery docs |

### Skills

| Skill | Status | Notes |
|-------|--------|-------|
| `apex-quantum-analysis` | ✅ OK | Available |
| `claude-code` | ✅ OK | Available |
| `csv-analyzer` | ✅ OK | Available |
| `deepresearchwork` | ✅ OK | Available |
| `github-pro` | ✅ OK | Available |
| `markdown-formatter` | ✅ OK | Available |
| `secops-by-joes` | ✅ OK | Available |
| `slk` | ✅ OK | Available |
| `web-scraper` | ✅ OK | Available |
| `workflow-automation` | ✅ OK | Available |

### Application

| File | Status | Notes |
|------|--------|-------|
| `src/App.tsx` | ✅ OK | React app |
| `src/components/` | ✅ OK | UI components |
| `src/hooks/` | ✅ OK | React hooks |
| `src/lib/` | ✅ OK | Libraries |
| `package.json` | ✅ OK | Dependencies |
| `Dockerfile` | ✅ OK | Container config |
| `railway.json` | ✅ OK | Railway deploy |

---

## Updates Required

### Priority 1: Fix Broken Links

| File | Fix |
|------|-----|
| `MEMORY.md` | Should point to local memory/, not `/root/waw/memory/MEMORY.md` |

### Priority 2: Update Config Files

| File | Update |
|------|--------|
| `llms.json` | Add MiniMax as default provider |
| `manifest.json` | Verify OpenClaw platform reference |

### Priority 3: Add New Docs

| File | Create |
|------|--------|
| `ARCHITECTURE.md` | Update with MaxClaw runtime diagram |
| `DEPLOY.md` | Add OpenClaw deployment guide |

---

## Platform Mapping

| Component | Where Defined |
|-----------|---------------|
| **Gateway** | OpenClaw (not in repo) |
| **Model** | `llms.json` (MiniMax) |
| **Skills** | `/workspace/repos/1AGI/skills/` |
| **MCP** | mcporter (global) |
| **Channel** | Telegram via OpenClaw |

---

## Next Steps

1. Fix `MEMORY.md` symlink → create local memory/ structure
2. Update `llms.json` with MiniMax config
3. Update `ARCHITECTURE.md` with new runtime diagram
4. Verify all symlinks point to correct locations

---

**Audit Date:** 2026-04-01  
**Auditor:** 1AGI
