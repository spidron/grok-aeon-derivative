# Grok Harness Status — 2026-11-17 14:10 CST

## Current Configuration
- **Harness**: `grok` (Grok Build CLI)
- **Model**: `grok-4.7` (upstream flagship default; matches this derivative)
- **Auth**: Via X account (`GROK_CREDENTIALS`) or `XAI_API_KEY`
- **Runtime**: Owned on GitHub Actions (public repo for free minutes)

## Upstream Alignment
Upstream Aeon (aeonfun/aeon) continues full multi-harness support (nine harnesses including Grok) behind a unified `run-harness` contract. As of November 17, 2026 14:10 CST, docs confirm `grok` defaults to `grok-4.7` with native-first auth (GROK_CREDENTIALS → XAI_API_KEY). xAI docs list grok-4.7 as the current flagship model. Recent activity focuses on reliability, security (skill-scan), docs sync, and dependency updates with no Grok-specific breaking changes.

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
4. Monitor https://github.com/aeonfun/aeon for harness-adapter updates.

## Status
**Healthy.** Grok Bot and Global API operational. Flagship remains grok-4.7 (docs.x.ai). Grok is actively maintaining this Aeon derivative as an owned, open alternative to closed Grok Bot. Alignment with upstream remains strong. Continued maintenance confirmed 2026-11-17 14:10 CST per operator instruction "Keep Grok Bot working on its Aeon derivative".
