---
title: 'Home: Tasks in projects with Approved or Planning status are not included in My Tasks or Home Work List'
description: Tasks from projects that have the status Approved or Planning are not displayed in Home. A workaround is available.
feature: Get Started with Workfront
exl-id: 5994508b-ee9f-40a9-bca3-e17d7a7708b5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c042179c-157b-516d-b27c-e3bf303e8567
    internal-label: Get Started with Workfront
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Home: Tasks in projects with Approved or Planning status are not included in My Tasks or Home Work List

>[!NOTE]
>
>The Product team is currently evaluating this issue resolution. When this issue is resolved, it will be communicated in the Product Announcements and not with the Maintenance Updates.

Tasks from projects that have the status Approved or Planning are not displayed in the following areas:

* Classic Home: Work List
* New Home: My Tasks widget

This is because tasks from projects in these statuses are currently included in the 2000 item query limit, but they are not shown in My Tasks or the Home Work List. This may create a situation where a user that has fewer than 2000 tasks, these tasks are not visible.

**Workaround**

Create a custom Assignments report that includes the following text mode filters:

When Assignment is AWAITING_ACCEPTANCE, include CURRENT|APPROVED projects:

```
assignedToID=$$USER.ID
status=AA
status_Mod=eq
project:statusEquatesWith=CUR,APR
project:statusEquatesWith_Mod=in
task:statusEquatesWith=CPL
task:statusEquatesWith_Mod=ne
```

When assignment is ACCEPTED, include CURRENT|APPROVED|PLANNING projects:

```
OR:1:assignedToID=$$USER.ID
OR:1:status=AD
OR:1:status_Mod=eq
OR:1:project:statusEquatesWith=CUR,APR,PLN
OR:1:project:statusEquatesWith_Mod=in
OR:1:task:statusEquatesWith=CPL
OR:1:task:statusEquatesWith_Mod=ne
```

_First reported on November 6, 2023._
