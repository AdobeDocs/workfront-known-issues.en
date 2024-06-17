---
title: 'Timesheets: Pinned timesheet goes to blank page'
description: When a user clicks a pin in Workfront that is intended to go to their timesheet, the pin instead goes to a blank page. A workaround is available.
hidefromtoc: yes
feature: Timesheets
exl-id: 684ccdfa-f419-451e-836a-11831fbc1816
---
# Timesheets: Pinned timesheet goes to blank page

When a user clicks a pin in Workfront that is intended to go to their timesheet, the pin instead goes to a blank page.

This is because the URL of the timesheet has changed. The `/own` at the end of the URL is no longer the correct URL. If the user has pinned a URL that includes `/own`, that pin leads to a blank page.

**Workaround**

1. Unpin the timesheet.
1. Remove `/own` from the end of the URL
1. Re-pin the timesheet.

_First reported on May 7, 2024._
