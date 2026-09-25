---
title: 'Timesheets: Pinned timesheet goes to blank page'
description: When a user clicks a pin in Workfront that is intended to go to their timesheet, the pin instead goes to a blank page. A workaround is available.
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: ce22a157-dd2c-405f-b740-c2f204bb4c1a
    internal-label: Timesheets
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Timesheets: Pinned timesheet goes to blank page

<!--article live for workaround-->

When a user clicks a pin in Workfront that is intended to go to their timesheet, the pin instead goes to a blank page.

This is because the URL of the timesheet has changed. The `/own` at the end of the URL is no longer the correct URL. If the user has pinned a URL that includes `/own`, that pin leads to a blank page.

**Workaround**

1. Unpin the timesheet.
1. Remove `/own` from the end of the URL
1. Re-pin the timesheet.

_First reported on May 7, 2024._
