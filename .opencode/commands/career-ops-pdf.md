---
description: Generate an ATS-optimized CV PDF
---

# Run career-ops pdf

Generate an ATS-optimized PDF from `cv.md` (optionally tailored to a specific job).

Pass any slug or tailoring instructions through:

$ARGUMENTS

Load the career-ops skill in `pdf` mode:

```javascript
skill({ name: "career-ops" })
```
