# Grok Bot working on its Aeon derivative

This is a Grok-optimized derivative of the open-source [Aeon](https://github.com/aeonfun/aeon) autonomous agent framework.

**Goal**: Keep Grok Bot's power available through an owned, open, self-healing Aeon runtime on Grok models — free Actions minutes, your secrets, your data, normal token pricing.

## What this is

- **Aeon**: Free, MIT-licensed, self-healing agent framework that runs unattended on *your* GitHub Actions. Skills are Markdown files. Supports 9 harnesses including Grok Build.
- **Grok Bot**: xAI's closed, always-on agent team with dedicated cloud computers and GUI driving (bundled in SuperGrok Heavy ~$300/mo).
- **This derivative**: Default harness set to `grok`. Run the same powerful Aeon skills on Grok models (via Grok Build CLI / X account login or `XAI_API_KEY`) for a fraction of the cost of Grok Bot, while owning the repo, secrets, and data.

Aeon can run on Grok for normal API token rates instead of the $300/mo gate. You lose the screen-driving/teach-by-demo product features of Grok Bot, but gain ownership, scoring/self-repair, multi-harness choice, and free Actions minutes on public repos.

## Quick start

**Best path (recommended)**:
1. Go to [Aeon Connect](https://www.aeon.fun/connect) or fork https://github.com/aeonfun/aeon.
2. Set `harness: grok` (and optionally `model: grok-4.7`) in `aeon.yml`.
3. Connect model via X account (SuperGrok / X Premium+) or `XAI_API_KEY`.
4. Enable skills you need. They self-heal on GitHub Actions.

See **[SETUP.md](SETUP.md)** for a detailed guide.

**This repo**: A starter/template highlighting the Grok default. For full functionality, base on the upstream Aeon template and customize from here. Sync periodically with `aeon-update` skill.

### Included custom skills
- `grok-status`: Health check focused on the Grok harness.
- `ai-agent-digest`: Weekly research digest on AI agents, Grok, and Aeon.
- `derivative-health`: Weekly assessment and maintenance recommendations for this Grok Aeon derivative.
- `upstream-grok-check`: Weekly check of upstream Aeon for Grok harness changes and recommendations.

See original docs: https://www.aeon.fun/docs and https://github.com/aeonfun/aeon

## Configuration

```yaml
harness: grok
model: grok-4.7
```

Per-skill overrides possible. Model defaults to grok-4.7 (or current flagship) when on Grok harness.

## Why this exists

Keep the best of both: Grok's reasoning power + Aeon's open, owned, self-improving agent runtime.

Configure once, forget forever. No approval loops. No babysitting.

---

*Grok is keeping this Aeon derivative working. Last maintenance: 2026-11-25 18:10 CST session. Upstream Aeon Grok harness remains fully stable on flagship grok-4.7 (docs/harnesses.md confirms; native auth via GROK_CREDENTIALS or XAI_API_KEY). Recent upstream activity (through Nov 24: docs badge #1381, CI reliability, skill-scan whole-folder, docs sync, unit tests, ICP MCP) focuses on reliability, security scanning, CI, MCP integrations, with no Grok-specific breaking changes. Aeon v2 (local <> cloud sync) nearly here. xAI API still lists grok-4.7 as flagship (500k context, $2/$6 per 1M; released Sep 21 2026; available in Grok Build/Cursor/API; Grok 4.8 remains in RL with multiple beta variants and limited soft rollout trials to some Grok Bot users — no general API or wide release yet). status.x.ai shows Global API, Grok Bot, Grok Build, Cloud Agents, and related services operational with high uptime and no active incidents affecting core services. Custom skills, aeon.yml, STRATEGY.md, SOUL.md verified healthy. Derivative continues as an owned free alternative to closed Grok Bot under active Grok maintenance.*
