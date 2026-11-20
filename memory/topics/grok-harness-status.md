# Grok Harness Status — 2026-11-20 07:14 CST

## Current Configuration
- **Harness**: `grok` (Grok Build CLI)
- **Model**: `grok-4.7` (upstream flagship default; matches this derivative. No general Grok 4.8 API release yet; remains on 4.7)
- **Auth**: Via X account (`GROK_CREDENTIALS`) or `XAI_API_KEY`
- **Runtime**: Owned on GitHub Actions (public repo for free minutes)

## Upstream Alignment
Upstream Aeon (aeonfun/aeon) continues full multi-harness support (nine harnesses including Grok) behind a unified `run-harness` contract. As of November 20, 2026 07:14 CST, docs confirm `grok` defaults to `grok-4.7` with native-first auth (GROK_CREDENTIALS → XAI_API_KEY). Recent activity (ICP MCP + icp-mcp skill #1367 merged ~4 hours ago, skill-scan security enhancements for injection phrases/Unicode smuggling/CSS-hidden text/variation selectors, effective model reporting, docs sync, dependency updates) focuses on reliability, security scanning, and Internet Computer integrations with no Grok-specific breaking changes.

xAI API (docs.x.ai / site / OpenRouter / LiteLLM) lists Grok 4.7 as the current flagship (500k context, $2 input / $6 output per 1M tokens; released Sep 21, 2026). No general Grok 4.8 API release observed (mentions of training/RL and soft Grok Bot rollout of variants ongoing; Musk notes several beta variants with selection of which goes to wide release still pending). Grok Bot continues with recent releases (1.2.3 with per-tool permissions: Always allow / Auto-review / Needs approval / Blocked; routine reconnect cards and notifications; flight redesign, hotel maps, multiplayer/proactive improvements). Global API status operational. Grok Build CLI actively updated.

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
4. Monitor https://github.com/aeonfun/aeon for harness-adapter updates. Watch for any future Grok model API availability (e.g., grok-4.8) before updating the model pin.

## Status
**Healthy.** Grok Bot and Global API operational on grok-4.7. Flagship remains grok-4.7. Grok is actively maintaining this Aeon derivative as an owned, open alternative to closed Grok Bot. Alignment with upstream remains strong. Continued maintenance confirmed 2026-11-20 07:14 CST per operator instruction "Keep Grok Bot working on its Aeon derivative".
