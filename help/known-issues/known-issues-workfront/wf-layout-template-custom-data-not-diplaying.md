---
title: 'Layout templates: Custom data fields not displaying when added to Task Summary through Layout Template'
description: When an administrator adds a custom data field to the Task Summary section through a Layout Template, the field displays as empty for users looking at a Task's Summary section.
feature: System Setup and Administration
exl-id: f37ecfc5-30b9-4fe2-9e76-a97be0ae969f
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Layout templates: Custom data fields not displaying when added to Task Summary through Layout Template

>[!NOTE]
>
>This issue has been closed because it is working as designed. See the workaround below.

When an administrator adds a custom data field to the Task Summary section through a Layout Template, the field displays as empty for users looking at a Task's Summary section.

**Workaround**

Avoid using periods "." in custom field names to avoid this issue. You can relabel the custom field in the Summary section and include a period if desired.

_First reported on October 2, 2024._
