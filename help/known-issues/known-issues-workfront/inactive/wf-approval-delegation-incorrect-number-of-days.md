---
title: 'Approvals: Approval delegation is set for the incorrect number of days'
description: When a user schedules Personal Time Off and delegates their approvals for that time, the approval delegation may include days before or after the scheduled time off.
exl-id: 8d978983-b663-442b-9935-75ecbd359a43
feature: Approvals
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: b04e3dc0-3a59-45b1-aa02-b0b6d5f87eff
    internal-label: Approvals
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Approvals: Approval delegation is set for the incorrect number of days

<!--Live for workaround-->

>[!NOTE]
>
>This issue has been closed because it is not an issue.

When a user schedules personal time off and delegates their approvals for that time, the approval delegation may include days before or after the scheduled time off.

**Workaround**

This discrepancy results from a difference between the timezone in a user's profile and the timezone of the user's assigned schedule.

We recommend creating a unique schedule for each timezone that users work from, and assigning each user to the schedule that matches the timezone in their user profile.

_First reported on March 24, 2022._
