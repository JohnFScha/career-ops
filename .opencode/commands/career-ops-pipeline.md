---
description: Process pending URLs from the inbox (data/pipeline.md)
---

# Run career-ops pipeline

Process job URLs stored in `data/pipeline.md` (the URL inbox / second brain). Runs a liveness sweep and evaluates each live URL.

Pass any options (e.g., limit, skip-liveness):

$ARGUMENTS

Load the career-ops skill in `pipeline` mode:

```javascript
skill({ name: "career-ops" })
```
