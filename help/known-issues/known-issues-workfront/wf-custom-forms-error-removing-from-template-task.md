---
title: "Custom forms: Cannot bulk add or bulk remove custom forms on template tasks"
description: "If a user attempts to bulk add or bulk remove a custom form on a template task, the form is not added or removed, and the user sees an error."
hidefromtoc: yes
feature: Custom Forms
---

# Custom forms: Cannot bulk add or bulk remove custom forms on template tasks

If a user attempts to bulk add or bulk remove a custom form on a template task, the form is not added or removed, and the user sees the following error:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

If the user locates the template with the specified GUID, then attempts to add or remove custom forms on the remainder of the template tasks, the error will reoccur using another templateID.

Custom forms can be added or removed on a single template task. This error applies only to bulk addition or removal.

_First reported on November 10, 2023._
