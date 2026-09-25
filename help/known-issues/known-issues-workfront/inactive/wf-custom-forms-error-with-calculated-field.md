---
title: 'Custom forms: Whoops error when setting up a calculated field'
description: When a user is creating or editing a calculated field on a custom form, and includes a custom field in the calculated field's expression, the expression is considered invalid. The Save button is disabled, and the user cannot navigate away from the custom field. In addition, the user sees a Whoops message below the field.
feature: Custom Forms
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
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
# Custom forms: "[!UICONTROL Whoops]" error when setting up a calculated field

<!--Requested: Do not delete without approval from Alex Beach-->

>[!NOTE]
>
>This issue was fixed on January 12, 2023

When a user is creating or editing a calculated field on a custom form, and includes a custom field in the calculated field's expression, the expression is considered invalid. The [!UICONTROL Save] button is disabled, and the user cannot navigate away from the custom field. In addition, the user sees the following message below the field:

"[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"

Removing the custom field from the expression allows the user to save and navigate away from the field.

_First reported on October 11, 2022._
