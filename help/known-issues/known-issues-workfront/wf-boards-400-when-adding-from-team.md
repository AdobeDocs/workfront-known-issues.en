---
title: 'Boards: 400 error when adding a task to a board from a team page'
description: When a user is viewing a project and attempts to add a task to a board, the task is not added, and the user sees the an error. A workaround is available.
hidefromtoc: yes
feature: Agile
exl-id: 6630fc4a-241b-4699-a076-f04768099372
---
# Boards: 400 error when adding a task to a board from a Kanban board

>[!NOTE]
>
>This issue was fixed on March 28, 2024.

When a user is viewing a team's Kanban board page and attempts to add a task to a board in Boards, the task is not added, and the user sees the following error:

Error: "400: undefined /boards-service/graphql"

**Workaround**

Create a connected card on the board, and connect it to the task.

_First reported on March 13, 2024._
