---
description: Follow-up cadence tracker -- flag overdue, generate drafts
---

# Run career-ops followup

Track follow-up cadence: flag overdue follow-ups and generate drafted outreach. Reads `voice-dna.md` directly (standalone mode) and applies the full conversational guardrail to every draft.

Pass any filter (company, status, date range):

$ARGUMENTS

Load the career-ops skill in `followup` mode:

```javascript
skill({ name: "career-ops" })
```
