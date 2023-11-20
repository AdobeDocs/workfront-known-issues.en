---
title: "Reports: 500 error when exporting a report"
description: "When a user attempts to export a report, the export fails with a 500 error."
hidefromtoc: yes
feature: Reports and Dashboards
---

# Reports: 500 error when exporting a report

When a user attempts to export a report, the export fails with the following error:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

This has been reported in reports that use a `valueexpression` to reference the `lastNote` note text. 

_First reported on Novmeber 8, 2023._
