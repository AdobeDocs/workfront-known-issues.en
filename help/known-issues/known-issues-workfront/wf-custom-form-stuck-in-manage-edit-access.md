---
title: "Custom forms: Cross-object custom forms require Manage or Edit access to edit fields"
description: "When a user creates a form with cross objects that only allow Manage or Edit access, and then removes that object type, the custom form continues to require Manage or Edit access to edit the fields. There is no visual indication the the fields require Manage or Edit access, and no way to reset the form."
hidefromtoc: yes
---

# Custom forms: Cross-object custom forms require [!UICONTROL Manage] or [!UICONTROL Edit] access to edit fields

>[!NOTE]
>
>This issue has been closed

When a user creates a form with cross objects that only allow [!UICONTROL Manage] or [!UICONTROL Edit] access, and then removes that object type, the custom form continues to require [!UICONTROL Manage] or [!UICONTROL Edit] access to edit the fields. There is no visual indication the the fields require Manage or Edit access, and no way to reset the form.

**Workaround**

1. Add a section break to the form with default values if populates with.
2. Move the section break to the top of the form.
3. Save the form.
4. Remove the section break just added and resave the form.

_First reported on November 9, 2022._

