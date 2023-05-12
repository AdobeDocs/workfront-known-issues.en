---
title: 'Documents: Permissions are not inherited when a document is moved to a new project'
description: 'When a user moves a document to a different project, the document does not inherit sharing permissions from the new project. The document is not shared to the users that the project is shared to. '
hidefromtoc: yes
exl-id: 56dfaf55-7438-4569-b9a1-b62fbdd3f4d9
---
# Documents: Permissions are not inherited when a document is moved to a new project

<!-- This Known Issue is on the TOC for both Workfront and Workfront Proof-->

<!--Won't fix tab: Valid issue, won't fix.-->

When a user moves a document to a different project, the document does not inherit sharing permissions from the new project. The document is not shared to the users that the project is shared to. 

**Workaround:**

1. Navigate to the document's parent object such as Project, Task, or Issue.

1. Remove inherited permissions from the parent object's share list by clicking the "x" next to inherited permissions, then click **[!UICONTROL Save]**.

1. Re-add inherited permissions by navigating back to the parent object's share list and clicking **[!UICONTROL Undo]** next to inherited permissions, then click **[!UICONTROL Save]**.

Alternatively, you can make note of the document's ID (found in the URL of the [!UICONTROL Document Details] page) and contact [!DNL Workfront] customer support.

_First reported on January 6, 2023._
