---
type: document
id: doc-travel-itinerary
title: "Travel — {{DESTINATION}}"
description: "Travel itinerary with flights, accommodation, and daily schedule"
tags: [Production, Template]
connections: []
metadata:
  template_category: "Personal Productivity"
---

## Travel Itinerary: {{DESTINATION}}

**Dates**: {{START_DATE}} — {{END_DATE}}
**Traveller**: {{TRAVELLER_NAME}}

## Flights
| Route | Flight | Date | Time | Confirmation |
| --- | --- | --- | --- | --- |
| {{ORIGIN}} → {{DESTINATION}} | {{FLIGHT_NO}} | {{DATE}} | {{TIME}} | {{CONF_NO}} |
| {{DESTINATION}} → {{ORIGIN}} | {{FLIGHT_NO}} | {{DATE}} | {{TIME}} | {{CONF_NO}} |

## Accommodation
- **Hotel**: {{HOTEL_NAME}}
- **Address**: {{ADDRESS}}
- **Check-in**: {{DATE}} {{TIME}}
- **Check-out**: {{DATE}} {{TIME}}
- **Confirmation**: {{CONF_NO}}

## Daily Schedule

### Day 1 — {{DATE}}
- {{ACTIVITY_1}}
- {{ACTIVITY_2}}

### Day 2 — {{DATE}}
- {{ACTIVITY_1}}
- {{ACTIVITY_2}}

## Important Contacts
- {{CONTACT_NAME}}: {{PHONE}}

## Packing List
- [ ] {{ITEM_1}}
- [ ] {{ITEM_2}}
- [ ] {{ITEM_3}}

## Budget
| Category | Estimated |
| --- | --- |
| Flights | {{AMOUNT}} |
| Accommodation | {{AMOUNT}} |
| Food | {{AMOUNT}} |
| Transport | {{AMOUNT}} |
| **Total** | **{{TOTAL}}** |
