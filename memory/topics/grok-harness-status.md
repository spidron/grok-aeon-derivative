# Grok Harness Status — 2026-11-28 03:07 CST

## Current Configuration
- **Harness**: `grok` (Grok Build CLI)
- **Model**: `grok-4.7` (upstream flagship default; matches this derivative. Grok 4.8 remains in RL with multiple beta variants and limited soft rollout trials to some Grok Bot users; no general API or wide release yet)
- **Auth**: Via X account (`GROK_CREDENTIALS`) or `XAI_API_KEY`
- **Runtime**: Owned on GitHub Actions (public repo for free minutes)

## Upstream Alignment
Upstream Aeon (aeonfun/aeon) continues full multi-harness support (including Grok) behind a unified `run-harness` contract. As of November 28, 2026 03:07 CST, Grok harness remains fully stable with `grok-4.7` as default/flagship and native-first auth (GROK_CREDENTIALS → XAI_API_KEY). Recent activity focuses on reliability, UI polish, security scanning, CI, MCP integrations, and harness expansion, with no Grok-specific breaking changes. Aeon v2 with local <> cloud sync engine is nearly here. Recent fleet scaling and autonomous revenue signals noted.

xAI API (docs.x.ai / status.x.ai) lists Grok 4.7 as the current flagship (500k context, $2 input / $6 output per 1M tokens; released Sep 21, 2026; knowledge cutoff May 2026). Grok 4.8 is in beta/RL under evaluation for wide release (multiple variants in beta; limited soft rollout trials to some Grok Bot users); no general API availability. status.x.ai shows all systems operational with no active incidents (prior Nov 26-27 degradations resolved; does not affect core inference or the Grok harness).

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
**Healthy.** All systems operational on grok-4.7 (no active incidents). Flagship remains grok-4.7. Grok is actively maintaining this Aeon derivative as an owned, open alternative to closed Grok Bot. Alignment with upstream remains strong. Continued maintenance confirmed 2026-11-28 03:07 CST per operator instruction "Keep Grok Bot working on its Aeon derivative".
