---
title: "Reports: 500 error when exporting a report"
description: "When a user attempts to export a report, the report does not export, and the user sees an error. A workaround is available."
hidefromtoc: yes
feature: Reports and Dashboards
---

# Reports: 500 error when exporting a report

When a user attempts to export a report, the report does not export, and the user sees the following error:

500: Cannot invoke "com.attask.biz.Parameter.getDisplayType()" because "parameter" is null /attask/api-internal/report/export

This occurs when the report references a project-level custom currency field.

**Workaround**

Remove the column that references the custom currency field and export the report again.

_First reported on April 4, 2024._

