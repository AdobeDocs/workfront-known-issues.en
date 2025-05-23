---
title: "Users: Pending approval badge displays on new users"
description: ""
hidefromtoc: yes
feature: 
---

# Users: "Pending approval" badge displays on new users

>[!NOTE]
>
>This issue may be present in organizations that have been migrated to the Adobe Admin Console.

New users in Workfront may display in the user list with a "Pending approval" badge. The badge persists for more than a few minutes, and is still present when the page is refreshed.

This issue is exacerbated when users are uploaded in large batches, such as from a spreadsheet or a Workfront Kick-Start.

Expected behavior is that the badge disappears after a few minutes, and is not present when the page is refreshed.

## Workarounds

This occurs when users added to Workfront do not sync to the Adobe Admin Console. 

We recommend the following workarounds:

### Resolve individual users

You can resolve individual users in the Users list.

1. Select the user or users in the Users list.
1. Click the three-dot menu in the list header.
1. Select **Approve**.
1. After a few minutes, refresh the page.

### Resolve users added in a large batch

To resolve users that were added in a large batch, you can add the batch of users to the Adobe Admin Console directly.

For instructions, see [Manage multiple users | Bulk CSV upload](https://helpx.adobe.com/enterprise/using/bulk-upload-users.html) in the Adobe documentation.


_First reported on May 8, 2025._
