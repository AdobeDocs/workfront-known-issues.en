---
title: Workfront Maintenance Updates
description: Maintenance Updates for [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
---
# [!DNL Workfront] Maintenance Updates

The following maintenance updates have been made in 2023.

>[!NOTE]
>
>These updates also include other minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

For maintenance updates prior to 2023, see [Previous Maintenance Updates](#previous-maintenance-updates)

## Updates in August 2023

+++**(Planned) Maintenance Update on August 3, 2023**

**Project does not correctly resolve issue**

_Projects / Issues_

When a user changes the status of a project that is the resolving object for an issue, the issue status is changed to a status that does not match the same key as the status on the project.

**"Whoops" error on matrix reports**

_Reports_

When a user attempts to view a matrix report, the report does not load, and the user sees the following error:

"[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"

This has been reported for users in EMEA.

+++

## Updates in July 2023

+++**Maintenance Update on July 27, 2023**

**Tags and checklist items not working correctly in the project board view**

_Boards_

Tags and checklist items have been removed from the board view of projects, because they are not part of the Workfront tasks and cannot be shared between users.

**"[!UICONTROL Enable system-wide]" and "[!UICONTROL View system-wide]" represent different functionality**

_Filters_

If a user shares a filter and enables the "[!UICONTROL View system-wide]" option, the filter is shared with every user in the system. However, if an admin then views this filter in [!UICONTROL Setup], they see that this filter displays "[!UICONTROL false]" in the "[!UICONTROL Visible System-Wide]" column. To make this filter a system default, the admin must enable the "[!UICONTROL Enable system-wide]" option in [!UICONTROL Setup]. This may cause some confusion due to the similarity of wording.

+++

+++**Maintenance Update on July 20, 2023**

This update includes only minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

+++

+++**Maintenance Update on July 13, 2023**

**Timeline does not recalculate**

_Projects / Tasks / Issues_

When an even occurs that should trigger a timeline calculation, the timeline does not recalculate. This affects recalculations that occur on changes, and scheduled recalculations. This can affect accuracy of the Workload Balancer.

**Locked proof approvals still show in Work List**

_Proofs_

Proof approvals that have passed their deadline and are locked are still showing on the approver's Home Work List, instead of dropping off the list when the deadline passed.

**Utilization report does not load**

_Reports_

When a customer attempts to view a utilization report, the user sees a spinning loading indicator, but the report does not load. The report has returned a 500 error, but the user sees no indication that the report has failed.

**Edit User page is blank**

<!--no article-->

_Users_

When a user attempts to edit another user, the Edit User page, is blank, and the user cannot edit the other user.

+++

## Updates in June 2023

+++**Maintenance Update on June 29, 2023**

This update includes only minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

+++

+++**Maintenance Update on June 22, 2023**

**"[!UICONTROL Whoops]" error when viewing matrix report**

_Reports_

When a user views a matrix report, they see the following error:

"[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"

This has been reported when the report is sorted by date and the "[!UICONTROL Show weeks with no results]" option is enabled.

**Dates display incorrectly in matrix reports**

_Reports_

When a chart or matrix report is grouped by date, dates near the edges of the grouping may appear in the correct grouping, the previous / next grouping, or both.

+++

+++**Maintenance Update on June 15, 2023**

This update includes only minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

+++

+++**Maintenance Update on June 8, 2023**

This update includes only minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

+++

+++**[!DNL Adobe Workfront Fusion] Maintenance Update on June 8, 2023**

[!DNL Fusion] has deployed a fix that prevents a user's connections from being removed when the user is removed or deactivated in the [!UICONTROL Adobe Admin Console].

[!DNL Fusion] team administrators are still able to remove unneeded connections from the [!UICONTROL Connections] page in [!DNL Fusion].

+++

+++**Maintenance Update on June 1, 2023**

**No error message when reordering task in [!UICONTROL Pending approval] status**

_Tasks_

When a user attempts to reorder a task in a task list, and the task is in [!UICONTROL Pending approval] status, the task appears to move in the task list. Upon refresh, the user sees that the item has not moved. The item cannot move because it is in [!UICONTROL Pending approval] status, but there is no message telling the user that the item cannot move, which may lead to confusion.

**No error message when moving predecessor task under dependent task**

_Tasks_

When a user attempts to reorder a task in a task list, and the task is in [!UICONTROL Pending approval] status, the task appears to move in the task list. Upon refresh, the user sees that the item has not moved. The item cannot move because a predecessor task cannot be moved under a task it is the predecessor for, but there is no message telling the user that the item cannot move, which may lead to confusion.

+++

## Updates in May 2023

+++**Maintenance Update on May 25, 2023**

**[!UICONTROL Kanban] board goes blank when editing cards**

_Agile_

When a user changes something about a card on the [!UICONTROL Kanban] board, the [!UICONTROL Kanban] board goes blank instead of refreshing with the change. If the user refreshes the page manually, the [!UICONTROL Kanban] board returns, showing the correct change.

This has been reported in the following circumstances:

* Editing a card
* Moving a card


+++

+++**Maintenance Update on May 22, 2023**

**Cannot adjust the size of descriptive text**

_Custom forms_

When the custom form designer was released in beta, the functionality to adjust the size of descriptive text was not available. This issue has been fixed and users can now adjust the size of descriptive text.

+++

+++**Maintenance Update on May 18, 2023**

**Report does not sort correctly when sorting by custom field**

_Reports_
When a user runs a task report, the report appears to sort correctly when it is loading, but when it finishes loading the user sees that the report is not sorted correctly. 

This seems to occur if all the following circumstances are met:

* The report is a task report
* The report is sorted by a custom field
* The report has a grouping applied

+++

+++**Maintenance Update on May 11, 2023**

**Cannot switch proof version when viewing proof**

_Proofs_

When a user is viewing a proof in the [!UICONTROL Proofing Viewer], and switches to another version, the version dropdown becomes disabled, and the user cannot switch back to the original version they were viewing, or to another version of the proof.

**[!DNL Workfront] Search times out**

_Search_

[!DNL Workfront] search is timing out. The search may return a few results, or none at all.

This issue also affects the functionality of the [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search] module.

+++

+++**[!DNL Adobe Workfront Fusion] Maintenance Update on May 11, 2023**

**Timeout errors in [!DNL Workfront Fusion]**

_Adobe Workfront Fusion_

When a scenario is running, it may have a timeout error. The information from the module with the error does not reach its destination.

**[!DNL Workfront] Search times out**

_Search_

[!DNL Workfront] search is timing out. The search may return a few results, or none at all.

This issue also affects the functionality of the [!DNL Workfront Fusion] > [!DNL Workfront] > [!UICONTROL Search] module.

+++

+++**Maintenance Update on May 9, 2023**

**Saved filters available in board intake column**

_Boards_

You can now use existing Workfront task and issue filters when configuring the intake column for a board. However, existing intake column filters are now read-only in the configuration panel. The existing filters are still applied to the intake column, but you must recreate the filters if you want to edit them.

+++

+++**Maintenance Update on May 4, 2023**

**Cannot select template from [!UICONTROL Favorite templates]**

_Templates_

When a user attempts to select a template from the Actions (three dot) menu, the list of templates disappears when the user moves their mouse to the list, and the user cannot select a template. This is because the scrollbar is between the menu and the list of templates, and the mouse focuses on the scrollbar as it moves to the list of templates.

+++

## Updates in April 2023

+++**Maintenance Update on April 27, 2023**

**Cannot switch between proofs in [!UICONTROL Proof Viewer]**

_Proofs_

When a user is viewing a proof in the [!UICONTROL Proofing Viewer], and switches to another proof, the switch proof button becomes unresponsive. The user cannot switch back to the original proof they were viewing, or to another proof.

**Edit attached images when editing a comment**

_Updates_

You can now edit the image attached to a comment when you are editing a comment. This is available in the Updates section for Workfront Goals and in that of issues when enabling the commenting beta experience.

+++

+++**[!DNL Adobe Workfront Fusion] Maintenance Update on April 25, 2023**

**[!DNL Fusion] in-app help links do not lead to specific help pages**

_[!DNL Workfront Fusion]_

When a user is viewing a proof in the [!UICONTROL Proofing Viewer], and switches to another proof, the switch proof button becomes unresponsive. The user cannot switch back to the original proof they were viewing, or to another proof.

+++

+++**Maintenance Update on April 20, 2023**

**Issues in custom dropdown fields**

_Custom forms_

Custom dropdown fields that are enabled as multi-select fields may display the following issues:

* The "+[!UICONTROL Add]" button is not present when the form is not in edit mode.
* Fields that do not have values show a "--[!UICONTROL no label]--" option.

**Cannot use Polyline tool when making a comment on a proof**

_Proofs_

When a user is viewing a proof in the Proofing Viewer and attemps to make a comment using the Polyline tool, the tool does not mark up the proof. 

**Text options box shows "textAnnotations"**

_Proofs_

When a user is viewing a proof, begins to add a comment, and opens the Text tool, the word "textAnnotation" appears next to the options in the tool. The Text tool still functions as expected, and "textAnnotation" disappears after the comment is posted.

**Keep images as a draft when moving away from an update for goals and for issues in the commenting beta experience**
 
>[!NOTE]
>
>This feature released to Preview on April 19, 2023 and released to production on April 20, 2023.

_Updates_
 
Now, when you navigate away from the Updates page while in the middle of composing a message where you have attached an image, the message and the image are preserved when you navigate back. Before this update, the unsubmitted comment was preserved but the image was deleted. This is available in the Updates section for goals and in that of issues when enabling the commenting beta experience.

**Real-time updates and deleted comments in the Updates section**
 
>[!NOTE]
>
>This feature released to Preview on April 19, 2023 and released to production on April 20, 2023.

_Updates_

Now, when someone adds a comment or reply, or deletes a comment from the Updates area, you can see the new comment or an indication that the a comment was removed in real time, without a delay. This is available in the Updates section for goals and in that of issues when enabling the commenting beta experience. 

**Access level changed by system without a record of the change**

_Users_

A user's access level may be unpredictably changed by the system. When this occurs, there is no visible update, and the change does not appear in the audit log.

+++

+++**Maintenance Update on April 17, 2023**

**Show new comments outside of the visible screen area in the [!UICONTROL Updates] section of issues (new commenting Beta experience) and [!UICONTROL Goals]**

_Updates_

We have added a notification banner for the [!UICONTROL Updates] section to inform users when there are newer comments on an item that might be outside of the visible area on the screen. This update is currently available in the [!UICONTROL Updates] section of goals and that of issues when the new commenting beta experience has been enabled for issues.

+++

+++**Maintenance Update on April 13, 2023**

**Filters are not applied to requests list**

_Requests_

When a user views a list of requests that has a filter applied, the list includes requests that the filter should exclude.

**Cannot select [!UICONTROL Default Hour Type] or [!UICONTROL Available Hour Types]**

_Users_

When an admin is editing a user and attempts to select a [!UICONTROL Default Hour Type] or [!UICONTROL Available Hour Type], they see that the dropdowns for those fields are disabled, and the they cannot select hour types.

+++

+++**Maintenance Update on April 6, 2023**

**Dropdowns are not opening when a user is added to a proof**

_Proofs_

When a user adds another user to a proof in the [!UICONTROL Proofing Viewer], the "[!UICONTROL Proof role]" and "[!UICONTROL Email alerts]" dropdowns cannot open. The user cannot assign a proof rold or email alert. This may occur when adding a user through a comment, or when sharing the proof with the user.

+++

## Updates in March 2023

+++**Maintenance Update on March 30, 2023**

**Cannot switch proof version when viewing proof**

_Proofs_

When a user is viewing a proof in the [!UICONTROL Proofing Viewer], and switches to another version, the version dropdown becomes disabled, and the user cannot switch back to the original version they were viewing, or to another version of the proof.

**504 error when exporting reports**

_Reports_

When a user attempts to export a report with a high number of items, they see a 504 error and cannot export the report.

**Update made in behalf of a user displays as directly from the user**

_Updates_

When an admin is logged in as a user and makes a comment, that comment displays as directly from the user, instead of from the admin on behalf of the user.

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
