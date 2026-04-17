---
type: document
id: doc-status-report
title: "Status Report — {{DATE}}"
description: "Project status report with progress, blockers, and next steps"
tags: [Production, Template]
connections: []
metadata:
  template_category: "Project Management"
---

## Status Report — {{DATE}}

**Project**: {{PROJECT_NAME}}
**Period**: {{PERIOD}}
**Overall Status**: 🟢 On Track / 🟡 At Risk / 🔴 Blocked

## Summary
Brief overview of progress this period.

## Completed This Period
- [x] {{COMPLETED_ITEM_1}}
- [x] {{COMPLETED_ITEM_2}}

## In Progress
- [ ] {{IN_PROGRESS_1}} — {{PERCENT}}% complete
- [ ] {{IN_PROGRESS_2}} — {{PERCENT}}% complete

## Blockers & Risks
| Blocker | Impact | Owner | Action |
| --- | --- | --- | --- |
| {{BLOCKER}} | {{IMPACT}} | {{OWNER}} | {{ACTION}} |

## Next Period
- [ ] {{NEXT_ITEM_1}}
- [ ] {{NEXT_ITEM_2}}

## Key Decisions Needed
- {{DECISION}}
