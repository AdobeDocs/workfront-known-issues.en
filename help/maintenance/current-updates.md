---
title: Workfront Maintenance Updates
description: Maintenance Updates for [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
---
# [!DNL Workfront] Maintenance Updates

The following maintenance updates have been made in 2023.

>[!NOTE]
>
>These updates also include other minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

For maintenance updates prior to 2023, see [Previous Maintenance Updates](#previous-maintenance-updates)

## Updates in March 2023

+++**(Planned) Maintenance Update on March 23, 2023**

**Cannot switch proof version when viewing proof**

_Proofs_

When a user is viewing a proof in the [!UICONTROL Proofing Viewer], and switches to another version, the version dropdown becomes disables, and the user cannot switch back to the original version they were viewing, or to another version of the proof.

**504 error when exporting reports**

_Reports_

When a user attempts to export a report with a high number of items, they see a 504 error and cannot export the report.

+++

+++**Maintenance Update on March 23, 2023**

**[!UICONTROL Summary] panel contents are too wide for the panel**

_Documents_

When a user views the [!UICONTROL Summary] panel for a document, the contents are too wide to be seen in the panel. The panel now has a horizontal scrollbar, and the user must scroll horizontally to see the [!UICONTROL Summary] panel contents. This occurs because the filename of the document does not wrap. This issue is limited to file where the filename has an HTML file extension.

**New [!UICONTROL Desktop Proofing Viewer] version**

_Proofing_

To fix a commenting issue in the [!UICONTROL Desktop Proofing Viewe]r, we've deployed a new version of the desktop proofing viewer.

Users who already have the [!UICONTROL Desktop Proofing Viewer] installed will get this update automatically.

Users can also manually down the latest version. For more information, see [Install the [!UICONTROL Desktop Proofing Viewer]](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html).

* Previous version: 2.1.22
* New version: 2.1.23

+++

+++**Maintenance Update on March 16, 2023**

**Checklist items not copied when copying a card**

_Boards_

When copying an ad hoc card (connected cards cannot be copied), checklist items are not copied to the new card.

**Custom field is missing when issue is converted to project**

_Projects_

When a user converts an issue to a project using a template, a custom field that was on the issue does not display on the project. This issue affects only non-admins.

**Custom messages not appearing in email notifications**

_Proofs_

When a user shares a proof and adds a custom message, that custom message does not appear in the notification email to the recipient. The subject is the proof name, and the message does not appear in the email.

+++

+++**Maintenance Update on March 9, 2023**

**Access level is not assigned when reactivating user**

_Users_

When a user is reactivating a deactivated user, and attempts to assign them an access level in the [!UICONTROL Reactivate User] window, the access level dropdown does not populate as the user types, and the user cannot select an access level. If the user types in the access level and saves, that access level is not assigned to the reactivated user.

**Save the draft of a comment in the [!DNL Goals] area**

_[!DNL Workfront Goals]_

Now, when you navigate away from the [!UICONTROL Updates] page of a goal while in the middle of composing a message, the message is preserved when you navigate back. Before this update, the unsubmitted comment would have been deleted.

+++

+++**Maintenance Update on March 2, 2023**

**Cannot add cards when grouping is applied**

_Boards_

When a user is viewing a board that has a grouping applies, and attempts to add a card, the user can only enter the name of the card. The rest of the card fields are disabled, including the [!UICONTROL Save] button.

If the user changes the grouping to [!UICONTROL None], the issue remains. The user must change the grouping to [!UICONTROL None] and then refresh the page to restore the ability to add a card.

**Connected cards not added to columns based on status**

_Boards_

Even though column policies are applied for status, new connected cards appear in the leftmost column and not in the column that corresponds to their status.


**Link to a comment redirects to [!UICONTROL Details] page**

_Updates_

When a user follows a link to a comment on an object in Workfront, the update stream loads briefly, and then the user is redirected to the object's [!UICONTROL Details] area. This may occur if the user clicks the link from an email or pastes the link into their browser.

This currently affects only Document objects.

**Print Summary does not load**

_[!UICONTROL Workfront Proof]_

When a user attempts to load the Print Summary page, the page appears to be loading, but never loads.

+++

## Updates in February 2023

+++**Maintenance Update on February 23, 2023**

**Link to a comment redirects to [!UICONTROL Details] page**

_Updates_

When a user follows a link to a comment on an object in Workfront, the update stream loads briefly, and then the user is redirected to the object's [!UICONTROL Details] area. This may occur if the user clicks the link from an email or pastes the link into their browser.

This currently affects only Document objects.

**User cannot edit their own notification settings**

_Users_

When a user with a [!UICONTROL Worker] licence attempts to edit their own notification settings, the [!UICONTROL Notifications] options are not visible in the [!UICONTROL Edit] window, and the user cannot edit the settings.

+++

+++**Maintenance Update on February 16, 2023**

**Multiple team assignments on boards**

_Boards_

You can now assign multiple teams to a task or issue on a board, and to the board itself.

**Card falloff limit increase**

_Boards_

The card falloff time limits have been increased to 8 weeks / 60 days instead of 4 weeks / 30 days.

**Scheduled deactivation does not deactivate user**

_Users_

When a user is scheduled to be deactivated, and the scheduled date and time passes, the user is not deactivated.

+++

+++**Maintenance Update on February 9, 2023**

**[!UICONTROL Story Points] field added to task and issue lists and reports**

_Reports_

The [!UICONTROL Story Points] field is now available to add to lists and reports for tasks or issues. It is an editable, free form field that is not tied to planned hours or team assignments.

+++

+++**Maintenance Update on February 8, 2023**

**Filter button in intake column**

_Boards_

The intake column on a board now includes an **[!UICONTROL Add a filter]** button when the column is empty and no filters have been created. The button opens the configuration area, where you can add filters to bring tasks and issues into the intake column.

+++

+++**Maintenance Update on February 2, 2023**

**[!UICONTROL Boards] icon appears in [!UICONTROL Main Menu] by default**

_Boards_

The [!UICONTROL Boards] icon now appears in the [!UICONTROL Main Menu] for users who do not have a layout template. Boards is also included in the Main Menu by default for any new layout templates that are created. Existing layout templates have not changed.

**Cannot save email templates**

_Setup_

When a user attempts to create or edit an email template, the [!UICONTROL Save] button is unresponsive, and the user cannot save the template.

+++

## Updates In January 2023

+++**Maintenance Update on January 30, 2023**

**Keyboard shortcuts added for common timesheet actions**

_Timesheets_

We have introduced the following keyboard shortcuts for the following commonly-performed actions inside a timesheet: 

* Add row (Cmd+Option++ / Ctrl+Option++)  
* Delete row (Cmd+Option+- / Ctrl+Option+-)  
* Pin or Unpin a work item (Option+P / Option+P) 
* Open comment (Shift+F2 / Shift+F2) 
* Save comment (Cmd+Enter / Ctrl+Enter) 
* Expand (Shift+Option+Up arrow/ Shift+Alt+Up arrow) 
* Collapse (Shift+Option+Down arrow/ Shift+Alt+Down arrow)

The area where these actions are performed must be highlighted in order for them to apply.

**New information icons for timesheets, timesheet profiles, and timesheet preferences**

_Timesheets_

>[!NOTE]
>
>This update was released only to the Preview environment on November 3, 2022 and it is now available in Production.

We have added several information icons to the following settings:  

* "[!UICONTROL Can edit time]" checkbox when creating or editing a timesheet or a timesheet profile to indicate that when enabled, approvers can also submit, reopen, or edit the timesheet, unless your administrator restricts these actions in the [!UICONTROL Timesheet Preferences] area of [!UICONTROL Setup]. 
* "[!UICONTROL Restrict timesheet editing to owners and admins]" in the [!UICONTROL Timesheet & Hour Preferences] area of [!UICONTROL Setup] to indicate that when disabled, the following users can also edit the timesheets: users with administrative access to timesheets and hours, timesheet approvers allowed to edit time, and timesheet owners' managers. 

Notice that the functionality of these settings has not changed and only the information icons have been added to add clarity to the scope of the settings.

+++

+++**Maintenance Update on January 26, 2023**

**Error when submitting request from [!DNL Outlook]**

_Integrations_

When a user attempts to submit a request with attachments from an [!DNL Outlook] email, one or more attachments do not upload, and the user sees the following error:

"[!UICONTROL The following error occurred: File with handle xxxx does not exist.]"

This occurs only when an assignment is made for the new request, either through the request queue or manually when creating the request.

**New Desktop Proofing Viewer version**

_Proofing_

To fix a freezing issue in the Desktop Proofing Viewer, we've deployed a new version of the desktop proofing viewer. Users who already have the Desktop Proofing Viewer installed will get this update automatically.

Users can also manually down the latest version. For more information, see [Install the Desktop Proofing Viewer](https://experienceleague.adobe.com/docs/workfront/using/review-and-approve-work/proofing/use-the-desktop-proofing-viewer/installing-desktop-proofing-viewer.html?lang=en).

* Previous version: 2.1.19
* New version: 2.1.20

**User cannot edit their own user setting**

_Users_

When a user with a license of Work, Review, or Request attempts to edit their own user settings, the popup that opens is blank, and the user cannot make any edits. To exit the popup, the user must refresh the page.

+++

+++**Maintenance Update on January 19, 2023**

**Intake column filters can now be shared**

_Boards_

When the intake column feature was released to Boards, the filters for setting up the intake column could only be seen by the person who created those filters. Now the creator can share the filters with other users or teams.

**Pin functionality available in [!UICONTROL More] menu**

_Navigation_

The following features are now available in the [!UICONTROL More] menu for pins, in the Production environment:

* Renaming pins
* Reordering pins within the [!UICONTROL More] menu
* Moving a pin out of the [!UICONTROL More] menu (when you do this, the last pin in the top navigation bar is moved to the [!UICONTROL More] menu)

+++

+++**Maintenance Update on January 18, 2023**

**Expressions with wildcards are not valid in custom fields**

_Custom Forms_

When a user uses a wildcard such as \$$TODAY or $$NOW along with a modifier (such as "-30d") in a custom field, the validator does not accept the wildcard as valid. Wildcards without modifiers are seen as valid.

**[!UICONTROL Workload Balancer] shows hours not associated with a project/task/issue**

_[!UICONTROL Workload Balancer]_

When a user views the [!UICONTROL Workload Balancer], they see hours logged for a user that are not associated with any project, task, or issue, nor are they logged as [!UICONTROL General] hours. These hours may display only in the 4 Week or 6 Week view.

+++

+++**[!DNL Adobe Workfront Fusion] Maintenance Update (Hot Fix) on January 12, 2023**

**404 errors on [!DNL Workfront] modules**

_Workfront Fusion_

When a scenario runs, a [!DNL Workfront] module returns a 404 error.

This has been reported in the following modules:

* [!UICONTROL Read a record]

+++

+++**Maintenance Update (Hot Fix) on January 12, 2023**

**"[!UICONTROL Whoops]" error when setting up a calculated field**

_Custom Forms_

When a user is creating or editing a calculated field on a custom form, and includes a custom field in the calculated field's expression, the expression is considered invalid. The [!UICONTROL Save] button is disabled, and the user cannot navigate away from the custom field. In addition, the user sees the following message below the field:

"[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"

Removing the custom field from the expression allows the user to save and navigate away from the field.

**Cannot set access levels**

_Users_

When a user attempts to change the access level of another user, the access levels are grayed out and the user cannot change them. This occurs even when the user attempting the change is a system administrator.

+++

+++**Maintenance Update on January 12, 2023**

**Ctrl+F or Cmd+F does not work as expected in dropdown fields**

_Custom Forms_

When a user is filling out a custom form and searches a dropdown list using Ctrl+F or Cmd+F, then attempts to jump to the next instance of that search, the dropdown list returns to the top of the list rather than jumping to the next instance of the search. This occurs when a dropdown is set to allow multiple selections.

**[!UICONTROL Edit Report] screen is blank**

_Reports_

When a user is viewing a report and attempts to edit the report, the user is taken to a blank screen and cannot edit the report.

**Indented tasks do not remain indented**

_Tasks_

When a user is viewing a task list and indents a task, the task immediately returns to its original (outdented) state.

+++

+++**Maintenance Update on January 5, 2023**

**Pin functionality available in [!UICONTROL More] menu**

_Navigation_

The following features are now available in the [!UICONTROL More] menu for pins, in the Preview environment only:

* Renaming pins
* Reordering pins within the [!UICONTROL More] menu
* Moving a pin out of the [!UICONTROL More] menu (when you do this, the last pin in the top navigation bar is moved to the [!UICONTROL More] menu)

**Removed the project Group limitation from adding users to the project team**

_Teams_

We have removed the limitation that required that the users that need to be added to a project team must be in the Group associated with the project. Now, you can add any active user to a project team, regardless of what groups they belong to.

**New information icons for timesheets, timesheet profiles, and timesheet preferences**

>[!NOTE]
>
>This update has been released to the Preview environment on November 3, 2022 and it is now available in Production

_Workfront_

We have added several information icons to the following settings:  

* "Can edit time" checkbox when creating or editing a timesheet or a timesheet profile to indicate that when enabled, approvers can also submit, reopen, or edit the timesheet, unless your administrator restricts these actions in the Timesheet Preferences area of Setup. 
* "Restrict timesheet editing to owners and admins" in the Timesheet & Hour Preferences area of Setup to indicate that when disabled, the following users can also edit the timesheets: users with administrative access to timesheets and hours, timesheet approvers allowed to edit time, and timesheet owners' managers. 

Notice that the functionality of these settings has not changed and only the information icons have been added to add clarity to the scope of the settings.

+++

## Previous maintenance updates

Information regarding previous maintenance updates is available here:

* [[!DNL Workfront] Maintenance Updates Archive - 2022](2022-updates.md)
* [[!DNL Workfront] Maintenance Updates Archive - 2021](2021-updates.md)
