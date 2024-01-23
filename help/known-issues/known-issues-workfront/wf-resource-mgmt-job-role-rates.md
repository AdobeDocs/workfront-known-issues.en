---
title: "Resource Management: Incorrect finance calculations due to Job Role issues"
description: "Hours and finance calculations may be incorrect, showing a cost of 0 even though hours are logged in a job role that has a cost rate."
hidefromtoc: yes
feature: Resource Management
---

# Resource Management: Incorrect finance calculations due to Job Role issues

Hours and finance calculations may be incorrect, showing a cost of 0 even though hours are logged in a job role that has a cost rate. 

This is because Job Roles are automatically creating duplicate rates with no start or end dates. Because they have no start or end dates, they are treated as a value of 0 when finance calculations are run.

**Workaround**

1. Ensure that your past correct data is saved.
1. Delete the duplicate rates with no start or end dates.
1. Recalculate the finances.

_First reported on January 18, 2023._
