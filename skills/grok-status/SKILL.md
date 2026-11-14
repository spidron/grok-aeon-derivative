---
name: grok-status
description: Report the status of this Grok Aeon derivative instance
metadata:
  title: Grok Status
  mode: read-only
  category: basics
requires:
  - XAI_API_KEY?
---

# Grok Status

Check and report the health of this Grok-optimized Aeon derivative.

## Steps

1. Read `aeon.yml` and confirm `harness: grok` and model.
2. Summarize enabled skills.
3. Check recent logs in `memory/logs/` if present.
4. Note any issues or recommendations for keeping the Grok harness working.
5. Produce a concise status report.

## Output

A short Markdown report on the instance status, focused on Grok harness readiness.
