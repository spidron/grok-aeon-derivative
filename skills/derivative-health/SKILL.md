---
name: derivative-health
description: Check health of this Grok Aeon derivative and recommend next maintenance actions
metadata:
  title: Derivative Health
  mode: read-only
  category: basics
requires:
  - XAI_API_KEY?
---

# Derivative Health

Assess the current state of this Grok-optimized Aeon derivative and propose concrete next steps to keep it working well.

## Steps

1. Read `aeon.yml`, `STRATEGY.md`, and `memory/MEMORY.md`.
2. Confirm harness is `grok` and model is current (grok-4.7 or newer).
3. List enabled skills and note any that are Grok-specific.
4. Check if the instance is reasonably in sync with upstream Aeon concepts (self-healing, scoring, owned runtime).
5. Recommend 1-3 high-leverage improvements (new skill, config tweak, documentation update, or upstream sync).
6. Note any risks (missing secrets, stale model, missing Actions enablement).

## Output

A short Markdown report:
- Current status (1-2 sentences)
- Recommendations (bulleted)
- Priority next action

Keep it actionable for the operator or for subsequent Grok runs.
