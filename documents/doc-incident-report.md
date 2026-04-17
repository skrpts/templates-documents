---
type: document
id: doc-incident-report
title: "Incident Report"
description: "Post-incident report with timeline, root cause, and corrective actions"
tags: [Production, Template]
connections: []
metadata:
  template_category: "Release & Change"
---

## Incident Report: {{INCIDENT_TITLE}}

### Summary
- **Severity:** {{SEVERITY}} (P1 / P2 / P3 / P4)
- **Duration:** {{DURATION}}
- **Impact:** {{IMPACT}}
- **Date:** {{DATE}}

### Timeline

| Time | Event |
|------|-------|
| {{TIME_1}} | {{EVENT_1}} |
| {{TIME_2}} | {{EVENT_2}} |
| {{TIME_3}} | {{EVENT_3}} |

### Root Cause
{{ROOT_CAUSE}}

### Contributing Factors
- {{FACTOR_1}}
- {{FACTOR_2}}

### Resolution
{{RESOLUTION}}

### Corrective Actions

| Action | Owner | Deadline | Status |
|--------|-------|----------|--------|
| {{ACTION_1}} | {{OWNER_1}} | {{DEADLINE_1}} | Open |
| {{ACTION_2}} | {{OWNER_2}} | {{DEADLINE_2}} | Open |

### Lessons Learned
{{LESSONS}}
