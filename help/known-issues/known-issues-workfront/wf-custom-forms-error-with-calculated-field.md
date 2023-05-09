---
title: 'Custom forms: Whoops error when setting up a calculated field'
description: When a user is creating or editing a calculated field on a custom form, and includes a custom field in the calculated field's expression, the expression is considered invalid. The Save button is disabled, and the user cannot navigate away from the custom field. In addition, the user sees a Whoops message below the field.
hidefromtoc: yes
exl-id: e499c680-2fdf-40cb-a1fa-b0d4ae799ad2
---
# Custom forms: "[!UICONTROL Whoops]" error when setting up a calculated field

>[!NOTE]
>
>This issue was fixed on January 12, 2023

When a user is creating or editing a calculated field on a custom form, and includes a custom field in the calculated field's expression, the expression is considered invalid. The [!UICONTROL Save] button is disabled, and the user cannot navigate away from the custom field. In addition, the user sees the following message below the field:

"[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"

Removing the custom field from the expression allows the user to save and navigate away from the field.

_First reported on October 11, 2022._