# Grok Harness Status — 2026-11-22 02:08 CST

## Current Configuration
- **Harness**: `grok` (Grok Build CLI)
- **Model**: `grok-4.7` (upstream flagship default; matches this derivative. Grok 4.8 remains several different model variants in beta for soft Grok Bot rollout with no general API release yet)
- **Auth**: Via X account (`GROK_CREDENTIALS`) or `XAI_API_KEY`
- **Runtime**: Owned on GitHub Actions (public repo for free minutes)

## Upstream Alignment
Upstream Aeon (aeonfun/aeon) continues full multi-harness support (nine harnesses including Grok) behind a unified `run-harness` contract. As of November 22, 2026 02:08 CST, docs/harnesses.md confirms `grok` defaults to `grok-4.7` with native-first auth (GROK_CREDENTIALS → XAI_API_KEY). Recent activity (commits through Nov 21 on CI reliability, docs sync, MCP ICP integration, skill-scan, and recent CI reliability fixes) focuses on reliability, security scanning, CI, MCP integrations, with no Grok-specific breaking changes. Aeon v2 with local <> cloud sync engine is nearly here (announced Nov 17/20).

xAI API (docs.x.ai / status.x.ai) lists Grok 4.7 as the current flagship (500k context, $2 input / $6 output per 1M tokens; released Sep 21, 2026). Grok 4.8 is in beta variants under evaluation for wide release; no general API availability. status.x.ai shows Global API, Grok Bot, Grok Build, and related services operational with no active incidents affecting core Grok models (only third-party Gemini 4 Carbon degraded under investigation). Grok Build CLI actively updated.

No breaking changes observed that affect this starter derivative.

## Active Custom Skills
- `grok-status`: Instance health focused on Grok readiness
- `ai-agent-digest`: Research digest on AI agents / Grok / Aeon
- `derivative-health`: Weekly maintenance recommendations
- `upstream-grok-check`: Weekly upstream Grok harness review

## Recommendations
1. Ensure `XAI_API_KEY` or Grok X-auth is set in Actions secrets for runs.
2. Periodically run or review the enabled weekly skills.
3. For full power, base a production instance on the upstream Aeon template and overlay Grok default + these custom skills.
4. Monitor https://github.com/aeonfun/aeon for harness-adapter updates and the upcoming v2 sync engine. Watch for any future Grok model API availability (e.g., grok-4.8) before updating the model pin.

## Status
**Healthy.** Grok Bot and Global API operational on grok-4.7. Flagship remains grok-4.7. Grok is actively maintaining this Aeon derivative as an owned, open alternative to closed Grok Bot. Alignment with upstream remains strong. Continued maintenance confirmed 2026-11-22 02:08 CST per operator instruction "Keep Grok Bot working on its Aeon derivative".
