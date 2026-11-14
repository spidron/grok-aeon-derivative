# Grok Bot working on its Aeon derivative

This is a Grok-optimized derivative of the open-source [Aeon](https://github.com/aeonfun/aeon) autonomous agent framework.

## What this is

- **Aeon**: Free, MIT-licensed, self-healing agent framework that runs unattended on *your* GitHub Actions. Skills are Markdown files. Supports 9 harnesses including Grok.
- **Grok Bot**: xAI's closed, always-on agent team with cloud computers and GUI driving (bundled in SuperGrok Heavy ~$300/mo).
- **This derivative**: Default harness set to `grok`. Run the same powerful Aeon skills on Grok models (via Grok Build CLI / X account login or XAI_API_KEY) for a fraction of the cost of Grok Bot, while owning the repo, secrets, and data.

Aeon can run on Grok for normal API token rates instead of the $300/mo gate. You lose the screen-driving/teach-by-demo product features of Grok Bot, but gain ownership, scoring/self-repair, multi-harness choice, and free Actions minutes on public repos.

## Quick start

1. **Recommended**: Fork https://github.com/aeonfun/aeon (or use Aeon Connect at https://www.aeon.fun/connect) and set `harness: grok` in `aeon.yml`.
2. Or clone this and sync with upstream.
3. Connect model: For pure Grok — X account (SuperGrok / X Premium+) or `XAI_API_KEY`.
4. Enable skills, schedule them. They self-heal on GitHub Actions.

See original docs: https://www.aeon.fun/docs and https://github.com/aeonfun/aeon

## Configuration

```yaml
harness: grok
```

Per-skill overrides possible. Model defaults to grok-4.7 (or current flagship) when on Grok harness.

## Why this exists

Keep the best of both: Grok's reasoning power + Aeon's open, owned, self-improving agent runtime.

Configure once, forget forever. No approval loops. No babysitting.

---

*Grok Bot is keeping this Aeon derivative working.*
