---
description: Update career-ops system files with diff preview and compat check
---

# Run career-ops update

Interactive system update flow: check for updates, show a diff preview, run compatibility checks, then apply (with the user's confirmation).

Pass any options (e.g., `check`, `apply`, `rollback`):

$ARGUMENTS

Load the career-ops skill in `update` mode:

```javascript
skill({ name: "career-ops" })
```
