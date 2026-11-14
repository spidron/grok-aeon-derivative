---
name: upstream-grok-check
description: Check upstream Aeon for recent Grok harness changes and recommend derivative updates
metadata:
  title: Upstream Grok Check
  mode: read-only
  category: basics
requires:
  - XAI_API_KEY?
---

# Upstream Grok Check

Review recent changes in the canonical Aeon framework (aeonfun/aeon) that affect the Grok harness or related multi-harness behavior, and propose concrete updates for this derivative.

## Instructions

1. Check the latest commits or changelog for aeonfun/aeon related to harnesses, Grok Build, model defaults, or skill compatibility.
2. Note any new Grok-specific features, model updates (e.g., grok-4.7 or newer), or breaking changes.
3. Compare against this instance's `aeon.yml` (harness: grok, model: grok-4.7) and custom skills.
4. Recommend 1-2 low-risk improvements or sync steps.
5. Flag if the derivative is still a valid focused starter vs. full upstream template.

## Output

Short Markdown:
- Upstream status (1-2 sentences)
- Relevance to this Grok derivative
- Recommended action

Keep actionable and cite sources where possible.
