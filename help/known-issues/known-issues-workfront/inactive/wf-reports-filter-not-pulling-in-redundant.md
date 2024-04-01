---
title: "Reports: Report filter does not return expected results"
description: "A filter in a report may not return all of the expected results. A workaround is available."
hidefromtoc: yes
feature: Reports and Dashboards
---

# Reports: Report filter does not return expected results

>[!NOTE]
>
>This issue has been closed.

A filter in a report may not return all of the expected results. 

This can occur when the filter is configured to return results with certain criteria, and includes an OR rule that returns results that are a subset of that same criteria. 

**Workaround**

Ensure that your filter's OR blocks do not include identical evaluation criteria.

_First reported on March 11, 2024._
 