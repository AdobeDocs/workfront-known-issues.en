---
title: 'Reports: 500 error when exporting a report'
description: When a user attempts to export a report, the export fails with a 500 error.
hidefromtoc: yes
feature: Reports and Dashboards
exl-id: 5275a4f4-4786-4a87-970f-774dcd526a39
---
# Reports: 500 error when exporting a report

>[!NOTE]
>
>This issue was fixed on November 30, 2023.

When a user attempts to export a report, the export fails with the following error:

```
500: Cannot invoke "Object.getClass()" because "parentObj" is null /attask/api-internal/report/export
```

This has been reported in reports that use a `valueexpression` to reference the `lastNote` note text. 

_First reported on Novmeber 8, 2023._
