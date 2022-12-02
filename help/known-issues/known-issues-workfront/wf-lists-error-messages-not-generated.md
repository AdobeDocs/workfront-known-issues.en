---
title: "Lists: Inline editing errors by user do not cause error messages"
description: "When a user is inline editing an object and makes an error that should create an error message, no error message appears. The error itself is not saved into Workfront, so the data is not affected, but the lack of an error message may cause confusion."
hidefromtoc: yes
---

# Lists: Inline editing errors by user do not cause error messages

>[!NOTE]
>
>This issue was fixed on December 1, 2022.

When a user is inline editing an object and makes an error that should create an error message, no error message appears. The error itself is not saved into Workfront, so the data is not affected, but the lack of an error message may cause confusion.

This has been reported for the following situations:

* Predecessors: A predecessor loop is created, such as assigning a task to itself
* Dates: An impossible date is set, such as a Completion Date that is prior to the Start Date or that is beyond the Project Completion Date

_First reported on October 26, 2022._

