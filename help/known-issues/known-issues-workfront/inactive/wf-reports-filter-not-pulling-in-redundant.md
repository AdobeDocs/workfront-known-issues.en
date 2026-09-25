---
title: 'Reports: Report filter does not return expected results'
description: A filter in a report may not return all of the expected results. A workaround is available.
feature: Reports and Dashboards
exl-id: d9ca1eac-1478-4ee0-a713-24743c1487c5
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c6dd2ac5-f5bd-4e59-9101-25b156918623
    internal-label: Reports and dashboards
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
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
