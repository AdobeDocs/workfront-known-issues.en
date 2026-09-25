---
title: 'Workfront Fusion: Field is missing from module'
description: When a user is configuring a module in Workfront Fusion, they may notice that a field is missing from the available options. This may occur when a user updates their custom fields, and has used the scenario designer within the last hour.
feature: Workfront Fusion
exl-id: c5d2d11c-ff31-4189-a630-b0248c02134e
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c3a155b4-a54b-4a82-a3d2-c8f0f971673e
    internal-label: Workfront Fusion
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Workfront Fusion: Field is missing from module

When a user is configuring a module in Workfront Fusion, they may notice that a field is missing from the available options. This may occur when a user updates their custom fields, and has used the scenario designer within the last hour.

This has been reported in the Workfront > Watch fields module.

**Workaround**

This issue is due to caching in Workfront Fusion. Because the cache is refreshed every hour, wait an hour and then try again.

_First reported on February 2, 2024, 2024._
