---
title: 'Custom forms: External lookup fields do not return results'
description: When an external lookup field references a multi-select field that has only one value selected, the field does not return the value.
hidefromtoc: yes
feature: Custom Forms
exl-id: b65c8870-e915-4ca5-a93b-5431440f9140
---
# Custom forms: External lookup fields do not return results

>[!NOTE]
>
>This issue was fixed on April 18, 2024.

When an external lookup field references a multi-select field that has only one value selected, the field does not return the value. 

For example, if an external lookup field references a multi-select field that has both "red" and "blue" values selected, the field functions as expected. If the field has only "red" selected, the external lookup field returns no value.

_First reported on April 2, 2024._
