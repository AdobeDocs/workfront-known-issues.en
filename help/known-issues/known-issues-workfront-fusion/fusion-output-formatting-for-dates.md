---
title: 'Workfront Fusion: Output formatting for dates'
description: When Dates are output as Strings, the date may be output as a UTC or an ISO string. This depends on the logic within a mapping panel.
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
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
# Workfront Fusion: Output formatting for dates

When Dates are output as Strings, the date may be output as a UTC or an ISO string. This depends on the logic within a mapping panel:

* If a Date within a function is joined to a string, then the string will be output in **UTC** format.
* If the Date is not joined within a function it will be output as an **ISO string**. 

Customers should use the `toString` (for ISO) or `formatDate` functions to ensure outputs are in the format they need.
