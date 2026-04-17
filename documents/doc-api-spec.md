---
type: document
id: doc-api-spec
title: "API Specification"
description: "API endpoint specification with request/response schemas and authentication"
tags: [Production, Template]
connections: []
metadata:
  template_category: "Product & Strategy"
---

## API Specification: {{API_NAME}}

### Base URL
`{{BASE_URL}}`

### Authentication
{{AUTH_METHOD}}

### Endpoints

#### {{METHOD_1}} {{PATH_1}}

**Description:** {{DESCRIPTION_1}}

**Request:**
```json
{{REQUEST_BODY_1}}
```

**Response (200):**
```json
{{RESPONSE_BODY_1}}
```

**Error responses:**
| Code | Description |
|------|-------------|
| 400 | {{ERROR_400}} |
| 401 | {{ERROR_401}} |
| 404 | {{ERROR_404}} |

### Rate Limits
{{RATE_LIMITS}}

### Versioning
{{VERSIONING}}
