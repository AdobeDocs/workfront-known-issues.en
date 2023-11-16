---
title: "Updates: Extra lines in comment made through API or Workfront Fusion"
description: "When a user submits a comment through the API or through Workfront Fusion, the comment displayed in the Updates area shows extra lines. At times there are so many lines that the user must scroll down to see the comment content."
hidefromtoc: yes
feature: Updates and Notifications
---

# Updates: Extra lines in comment made through API or [!DNL Workfront Fusion]

>[!NOTE]
>
>This issue was fixed on November 16, 2023.

When a user submits a comment through the API or through [!DNL Workfront Fusion], the comment displayed in the Updates area shows extra lines. At times there are so many lines that the user must scroll down to see the comment content.

This has been reported in the new commenting experience.

**Workaround**

This issue is caused by spaces or line breaks in the HTML submitted in the comment. 

To avoid this issue, ensure that all of the HTML is on one line, without spaces or line breaks between the HTML elements.

To view affected comments without the extra lines, switch to the classic commenting experience.

_First reported on October 27, 2023._
