---
description: Batch processing with parallel workers
---

# Run career-ops batch

Mass-process jobs in batch mode. Supports a conductor (navigates portals in real time) or standalone processing of URLs already collected.

Pass any batch instructions or file references:

$ARGUMENTS

Load the career-ops skill in `batch` mode:

```javascript
skill({ name: "career-ops" })
```
