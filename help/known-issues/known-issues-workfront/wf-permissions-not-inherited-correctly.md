---
title: 'Permissions: Object permissions are not inherited correctly'
description: Inherited permissions are not correctly being applied to objects. This may occur because of the complexity of the inherited permissions.
feature: Projects, Tasks, Work Management
exl-id: 589733a7-2bd6-4b73-afb8-a14cc1f5076a
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
subfeature_v2:
  - id: f0dd7b45-76b5-49d4-afe3-39f436b6fbd3
    internal-label: Projects
  - id: b91c0848-76c4-4da4-8b81-3aade0518dd0
    internal-label: Tasks
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Permissions: Object permissions are not inherited correctly

>[!NOTE]
>
>The Product team is currently evaluating this issue resolution, which might require product enhancements. Product enhancements are communicated in the Product Announcements and not with the Maintenance Updates.

Inherited permissions are not correctly being applied to objects. This may occur because of the complexity of the inherited permissions, which can be affected by the following:

* The object is shared with a large number of people
* A large number of objects are affected by an inherited permission change

**Workaround**

Limiting the size or complexity of the objects can help avoid this issue. We recommend that you have no more than 10,000 child objects under any parent object.

_First reported on March 21, 2025._
