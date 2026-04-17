---
type: document
id: doc-risk-register
title: "Risk Register"
description: "Project risk register with probability, impact, and mitigation strategies"
tags: [Production, Template]
connections: []
metadata:
  template_category: "Project Management"
---

## Risk Register — {{PROJECT_NAME}}

**Last Updated**: {{DATE}}

## Risk Matrix

| ID | Risk | Probability | Impact | Score | Owner | Mitigation | Status |
| --- | --- | --- | --- | --- | --- | --- | --- |
| R1 | {{RISK_1}} | High/Med/Low | High/Med/Low | {{SCORE}} | {{OWNER}} | {{MITIGATION}} | Open |
| R2 | {{RISK_2}} | High/Med/Low | High/Med/Low | {{SCORE}} | {{OWNER}} | {{MITIGATION}} | Open |
| R3 | {{RISK_3}} | High/Med/Low | High/Med/Low | {{SCORE}} | {{OWNER}} | {{MITIGATION}} | Open |

## Scoring Guide
- **Probability**: High (>70%), Medium (30-70%), Low (<30%)
- **Impact**: High (critical path), Medium (workaround exists), Low (minor inconvenience)

## Escalation Criteria
- Any risk scored High/High must be escalated to {{ESCALATION_TARGET}}
