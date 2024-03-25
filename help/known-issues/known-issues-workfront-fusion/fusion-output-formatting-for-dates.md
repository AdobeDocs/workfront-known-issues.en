---
title: 'Workfront Fusion: Output formatting for dates'
description: When Dates are output as Strings, the date may be output as a UTC or an ISO string. This depends on the logic within a mapping panel.
hidefromtoc: yes
feature: Workfront Fusion
exl-id: e01a2260-f230-4f72-a8c6-3dae56b22ff5
---
# Workfront Fusion: Output formatting for dates

When Dates are output as Strings, the date may be output as a UTC or an ISO string. This depends on the logic within a mapping panel:

* If a Date within a function is joined to a string, then the string will be output in **UTC** format.
* If the Date is not joined within a function it will be output as an **ISO string**. 

Customers should use the `toString` (for ISO) or `formatDate` functions to ensure outputs are in the format they need.
