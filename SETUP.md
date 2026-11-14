# Setup Guide: Grok Bot Aeon Derivative

This repository is a **starter configuration** for running an Aeon agent optimized for the Grok harness.

For full functionality (workflows, harness adapter, full skill catalog, dashboard, etc.), start from the upstream Aeon template and overlay these configs.

## Recommended Setup

1. **Create your own instance** (preferred):
   - Visit [Aeon Connect](https://www.aeon.fun/connect)
   - Sign in with GitHub
   - Create a new agent (public repo recommended for free Actions minutes)
   - Or: Use this template → fork `aeonfun/aeon` and copy relevant files from here

2. **Set Grok as the harness**:
   In `aeon.yml`:
   ```yaml
   harness: grok
   model: grok-4.7
   ```

3. **Authenticate Grok**:
   - Via Aeon dashboard / `./aeon auth --harness grok` (X account login for SuperGrok / X Premium+)
   - Or set `XAI_API_KEY` secret in GitHub Actions

4. **Enable skills**:
   Edit `aeon.yml` and set `enabled: true` for desired skills. Upstream has 90+ skills across packs.

5. **Channels** (optional):
   Connect Telegram, Discord, Slack, or email for notifications.

6. **Sync with upstream**:
   The `aeon-update` skill (enabled by default here) helps keep you current.

## What you get

- Owned runtime on your GitHub Actions
- Self-healing skills with scoring
- Grok models at normal token rates
- Full audit trail in your repo
- No $300/mo SuperGrok Heavy requirement for the agent runtime

## Limitations vs Grok Bot

You do **not** get:
- Dedicated cloud computers per agent
- GUI driving / screen automation
- Teach-by-demonstration
- Native multi-bot group chat coordination (Aeon has fleet features instead)

You **do** get ownership, open source, model choice, and self-repair.

---

Configure once, forget forever.
