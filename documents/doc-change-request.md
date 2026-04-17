---
type: document
id: doc-change-request
title: "Change Request — {{TITLE}}"
description: "Change request template for formal approval workflows"
tags: [Production, Template]
connections: []
metadata:
  template_category: "Release & Change"
---

## Change Request

**ID**: CR-{{ID}}
**Title**: {{TITLE}}
**Requestor**: {{REQUESTOR}}
**Date**: {{DATE}}
**Priority**: Critical / High / Medium / Low

## Description of Change
{{DESCRIPTION}}

## Reason for Change
{{REASON}}

## Impact Assessment
- **Systems affected**: {{SYSTEMS}}
- **Users affected**: {{USERS}}
- **Risk level**: High / Medium / Low
- **Rollback plan**: {{ROLLBACK}}

## Implementation Plan
1. {{STEP_1}}
2. {{STEP_2}}
3. {{STEP_3}}

## Testing Plan
- {{TEST_1}}
- {{TEST_2}}

## Schedule
- **Planned date**: {{DATE}}
- **Maintenance window**: {{WINDOW}}
- **Expected duration**: {{DURATION}}

## Approvals
| Role | Name | Status | Date |
| --- | --- | --- | --- |
| {{ROLE}} | {{NAME}} | Pending | |
