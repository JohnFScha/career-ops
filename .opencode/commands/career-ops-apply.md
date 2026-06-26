---
description: Live application assistant -- reads a form and generates answers
---

# Run career-ops apply

Interactive assistant for filling out an application form in Chrome. Reads what is on the screen, loads prior job context, and generates personalized responses for each form question. Applies `voice-dna.md` if present.

Pass any context (URL, slug, or instructions):

$ARGUMENTS

Load the career-ops skill in `apply` mode:

```javascript
skill({ name: "career-ops" })
```
