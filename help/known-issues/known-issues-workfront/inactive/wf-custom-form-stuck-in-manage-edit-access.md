---
title: 'Custom forms: Cross-object custom forms require Manage or Edit access to edit fields'
description: When a user creates a form with cross objects that only allow Manage or Edit access, and then removes that object type, the custom form continues to require Manage or Edit access to edit the fields. There is no visual indication the the fields require Manage or Edit access, and no way to reset the form.
feature: Custom Forms
exl-id: 3f7ad4f5-1480-4514-8543-7e699743a8ef
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d968a1bc-9a90-4926-a531-bcf272c32aad
    internal-label: Administration
subfeature_v2:
  - id: d87de1f9-8e24-4c4d-aa4c-a403075091a1
    internal-label: Custom forms
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Custom forms: Cross-object custom forms require [!UICONTROL Manage] or [!UICONTROL Edit] access to edit fields

<!--Won't fix, live for workaround-->

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
