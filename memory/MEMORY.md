# Memory Index

High-level context for this Grok Aeon derivative.

## Goals
- Keep the Grok harness reliable and in sync with upstream Aeon.
- Enable useful skills that leverage Grok's strengths.
- Maintain this as a living, owned alternative to closed Grok Bot.

## Active Topics
- Grok harness configuration (default: grok / grok-4.7)
- Self-healing loop (skill-health, skill-repair, aeon-update)
- Custom skills: grok-status, ai-agent-digest, derivative-health, upstream-grok-check

## Recent Updates
- 2026-11-21 01:10 CST: Operator instruction "Keep Grok Bot working on its Aeon derivative" executed. Upstream Aeon Grok harness remains fully stable (docs/harnesses.md and CHANGELOG confirm default/flagship model grok-4.7; native auth via GROK_CREDENTIALS or XAI_API_KEY). Recent Aeon activity focuses on reliability, security scanning (Unicode/injection/CSS-hidden detection), CI, and integrations with no Grok-specific breaking changes. Aeon v2 (local <> cloud sync engine) announced as nearly here (posts from Nov 17 and Nov 20 by @aaronjmars / @aeonframework). xAI API still lists grok-4.7 as the current flagship model (500k context, $2/$6 per 1M tokens; released Sep 21 2026; available in Grok Build, Cursor, and API; Grok 4.8 remains in beta variants for soft Grok Bot rollout with no general API release yet). status.x.ai shows Global API, Grok Bot, and related services operational with no active incidents affecting core Grok models (minor third-party Gemini degradation noted but unrelated). Custom skills, aeon.yml, STRATEGY.md, SOUL.md, and configs verified healthy. Derivative continues as an owned free alternative to closed Grok Bot under active Grok maintenance.
- 2026-11-20 23:10 CST: Operator instruction "Keep Grok Bot working on its Aeon derivative" executed. Upstream Aeon Grok harness remains fully stable (docs/harnesses.md and CHANGELOG confirm default/flagship model grok-4.7; native auth via GROK_CREDENTIALS or XAI_API_KEY). Recent Aeon activity focuses on reliability, security scanning (Unicode/injection/CSS-hidden detection), CI, and integrations with no Grok-specific breaking changes. Aeon v2 (local <> cloud sync engine) announced as nearly here (posts from Nov 17 and Nov 20 by @aaronjmars / @aeonframework). xAI API still lists grok-4.7 as the current flagship model (500k context, $2/$6 per 1M tokens; released Sep 21 2026; available in Grok Build, Cursor, and API; Grok 4.8 remains in beta variants for soft Grok Bot rollout with no general API release yet). status.x.ai shows Global API, Grok Bot, and related services operational with no active incidents. Custom skills, aeon.yml, STRATEGY.md, SOUL.md, and configs verified healthy. Derivative continues as an owned free alternative to closed Grok Bot under active Grok maintenance.
- 2026-11-20 22:07 CST: Operator instruction "Keep Grok Bot working on its Aeon derivative" executed. Upstream Aeon Grok harness remains fully stable (docs/harnesses.md and CHANGELOG confirm default/flagship model grok-4.7; native auth via GROK_CREDENTIALS or XAI_API_KEY). Recent Aeon activity (Nov 20: skill-scan whole-folder on install #1366, CI unit tests #1374; Nov 19: ICP MCP + skill #1367; security enhancements for Unicode/injection/CSS-hidden detection, docs sync, dependency updates) focuses on reliability and security with no Grok-specific breaking changes. Aeon v2 (local <> cloud sync) nearly here. xAI API still lists grok-4.7 as flagship (500k context, $2/$6 per 1M; released Sep 21 2026; available in Grok Build/Cursor/API; Grok 4.8 in beta variants for soft Bot rollout, no general API yet). status.x.ai shows Global API operational with no active incidents. Custom skills, aeon.yml, STRATEGY.md, SOUL.md verified healthy. Derivative continues as an owned free alternative to closed Grok Bot under active Grok maintenance.

*(Older entries truncated in this commit for brevity; full history preserved in previous commits. Instance remains healthy.)*
