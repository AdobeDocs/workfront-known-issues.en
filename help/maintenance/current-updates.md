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

## Updates in February 2023

+++**Maintenance Update on February 2, 2023**

**Boards icon appears in Main Menu by default**

_Boards_

The Boards icon now appears in the Main Menu for users who do not have a layout template. Boards is also included in the Main Menu by default for any new layout templates that are created. Existing layout templates have not changed.**Cannot save email templates**

_Setup_

When a user attempts to create or edit an email template, the [!UICONTROL Save] button is unresponsive, and the user cannot save the template.

+++

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
