---
title: Workfront Maintenance Updates
description: Maintenance Updates for [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
---
# [!DNL Workfront] Maintenance Updates

The following maintenance updates have been made in 2022.

>[!NOTE]
>
>These updates also include other minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

<!--
* [July 2022](#updates-in-july-2022)
* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)
-->

For maintenance updates prior to 2022, see [Previous Maintenance Updates](#previous-maintenance-updates)

## Updates in October 2022

+++**Maintenance Update on October 6, 2022**

**New blueprint type**

*Blueprints*

The blueprint type "Dashboard" has been added to the catalog of blueprints. Previously, only Project Template and Organizational Structure blueprints were available.

**Elements overlapping in left panel**

*Custom forms*

When a user is working in the form builder, and the form has more than 100 fields, the message notifying the user about the field limit causes elements in the left panel to overlap.

**Date picker no longer automatically opens on input focus or click**

*Navigation*

When a user navigates by keyboard, date pickers are no longer automatically opened upon the date input receiving keyboard focus. Instead, keyboard users should tab to the date picker icon and press Enter to open the date picker. When a user navigates by mouse, date pickers are no longer automatically opened upon the date input being clicked. Instead, mouse users should click the date picker icon to open the date picker.

This change was made to better conform with standard date picker UX patterns and to create a more accessible experience for keyboard and screen reader users.

**Assigning multiple teams results in only one team assigned**

*Teams*

>[!NOTE]
>
>This issue exists only in the Preview environment.

When a user assigns multiple teams to a task or issue, only one team appears in the assignments list. This issue also affects reporting. Reports showing team assignments are inaccurate because only one team appears as assigned to the task or issue.

**"[!UICONTROL Your recent changes were not saved]" error when autosaving changes on a timesheet**

*Timesheets*

When a user attempts to edit a timesheet in a way that would trigger an autosave the changes are not saved and the user sees the following message:

"[!UICONTROL Your recent changes were not saved. Refresh the page to view.]"

This has been reported when editing the following:

* Hours
* Tasks

**Email notifications are delayed**

*Workfront Proof*

When an event occurs in [!DNL Workfront Proof] that triggers an email notification, the user does not receive the notification immediately. The notification may be delayed by several hours.

+++

+++**Maintenance Update on October 3, 2022**

**Manually save your timesheet when previous job roles have changed**

*Timesheets*

If a job role for which you logged time has changed and the [!UICONTROL Assign job roles to hour entries manually] setting has been disabled, you must manually save your time entries until hours are no longer logged for the job role that has changed.

+++

## Updates in September 2022

+++**Maintenance Update on September 29, 2022**

**User does not return to previous page when closing proof**

*Proofs*

When a user who is viewing a proof within [!DNL Workfront] closes the proof, they do not return the page they were on before they opened the proof. Instead, they are redirected to another page in [!DNL Workfront]. 

**Cannot open proof in [!DNL Workfront]**

*Proofs*

When a user is viewing a document in [!DNL Workfront] and attempts to open the proof, the proof does not open and the user is returned to the [!UICONTROL Document Details] page.

**Hours do not save when using [!UICONTROL Tab] key**

*Timesheets*

When a user is filling out a time sheet and navigating between cells with the [!UICONTROL Tab] key, the hours are not saved. The [!UICONTROL Auto-save] notification does not appear at the bottom of the screen, and if the user refreshes the page, they can see the the hours were not saved.

**Blank pages when viewing a proof with multiple pages**

*[!DNL Workfront Proof]*

When a user views a proof with multiple pages, the user can see thumbnails of the pages, but the pages do not open in the main viewer.



+++

+++**Maintenance Update on September 22, 2022**

**Cannot close user card in update stream**

*Updates*

When a user is viewing updates and hovers over a name, a card with details about the user whose name it is opens and does not close automatically. The page is unresponsive until the card is manually closed by clicking the X in the upper-right corner.

+++

+++**Maintenance Update on September 15, 2022**

**"[!UICONTROL Someone else tried to save this project]" error when entering hours**

*Timesheets*

When a user attempts to log hours to a task on their timesheet, the hours do not autosave, and the user sees the following error:

"[!UICONTROL We're sorry, but your save failed because someone else tried to save this project at the same time. Please try to save again.]"

**Cannot close user card in update stream**

*Updates*

When a user is viewing updates and hovers over a name, a card with details about the user whose name it is opens and does not close automatically. The page is unresponsive until the card is manually closed by clicking the X in the upper-right corner.

**The "[!UICONTROL Task role assignment]" field has been renamed to "[!UICONTROL Role assignment]" when assigning work in bulk using the [!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]* 

To reflect the new functionality of being able to assign both tasks and issues in bulk  from the [!UICONTROL Unassigned Work] area, we have renamed the "[!UICONTROL Task role assignment]" field to "[!UICONTROL Role assignment]" in the [!UICONTROL Workload Balancer]. The field refers to job roles that have been assigned to either tasks or issues and it displays when assigning users to items in the [!UICONTROL Bulk Assignments] box.

+++

+++**[!DNL Workfront Scenario Planner] Maintenance Update on September 15, 2022**

**Filter shared with a Group now displays in the [!DNL Scenario Planner]'s  [!UICONTROL Import Projects] list for  members of the all Subgroups**

*[!DNL Workfront Scenario Planner]*

Now, when you share a project filter with a group that has additional subgroups, the filter is visible to all group and subgroup members that view projects in the [!UICONTROL Import Projects] box of a plan in the [!DNL Scenario Planner].

+++

+++**Maintenance Update on September 8, 2022**

**Updated names reverted for the user- and role-assignment fields**

*Assignments*

The assignment fields temporarily renamed last week have been reverted to their original names:

* [!UICONTROL Assignment Users]
* [!UICONTROL Assignment Roles]

**Error when removing the Project Owner from the header**

*Projects*

When a user attempts to remove a [!UICONTROL Project Owner] from the header of a project, the [!UICONTROL Project Owner] is not removed, and the user sees the following error message:

`422: Invalid Parameter: ownerID value "null" /attask/api-internal/PROJ/<project ID>`

**Resized [!UICONTROL Description] box goes back to original size**

*Projects, tasks, and issues*

When a user resizes the [!UICONTROL Description] box in the details area of a work item to make it bigger, then begins typing in the box, the box returns to its original size. The user can still type in the box, and the contents save as expected

**Inadvertent exit when creating tasks or issues**

*Tasks and issues*

When a user is creating a task or issue in a project and clicks outside of the creation pop-up, the pop-up closes without warning and all previously entered information is lost.

**Removed ability to email a proof to a dropzone**

*[!DNL Workfront Proof]*

As of Thursday, September 8, 2022, we have removed the ability to email a proof to a dropzone in the standalone [!DNL Workfront Proof] product.

You can still use dropzones in other ways to submit new proofs and new versions of proofs to your account without having to log in to your account. See [The Dropzone](https://experienceleague.adobe.com/docs/workfront/using/workfront-proof/work-with-proofs-in-wf-proof/create-proofs-and-files/dropzone.html) for more information.

+++

+++**Maintenance Update on September 6, 2022**

**Projected dates added to the list of fields for customizable project headers**

*Projects*

We have added the [!UICONTROL Projected Start Date] and [!UICONTROL Projected Completion Date] to the list of fields for customizable project headers when using a layout template.

**New limit with a confirmation message that displays the number of items added to a timesheet**

*Timesheets*

When you select more than 50 items to add to a timesheet, you now receive a confirmation message that displays the number of items to be added to the timesheet and gives you the opportunity to change course and not add all the items. All items added become automatically pinned to the timesheet and will need to be manually removed from the current and all future timesheets.

+++

+++**Maintenance Update on September 2, 2022**

Add the [!UICONTROL Integrations] field to the project custom header

*Integrations*

You can now add the [!UICONTROL Integrations] field to the custom header of a project when you use a layout template. Once added, the field will display a link to an external item linked to the project which is located in [!DNL Salesforce] or [!DNL Anaplan], depending on your integration.

>[!NOTE]
>
>This maintenance update was previously released to the Preview environment on August 25, 2022 and it is now in Production.

+++

+++**Maintenance Update on September 1, 2022**

**Completed items removed from delegation**

*Delegations*

Now, only incomplete items whose dates match the dates of a delegation will be delegated to other users when the delegation of work items starts. If items were completed before the delegation started, they will not be delegated. Items that are completed during the delegation time frame will stay on the Work List of the Home area for both the delegate and the assignee for two weeks before they are automatically removed, if the delegation has not ended during these weeks.

**Metadata updates for the [!DNL Adobe Workfront] for [!DNL Experience Manager Assets] and [!DNL Assets Essentials] integrations**

*Integrations*

Metadata automatically pushes when you add an asset to a linked folder.

Previously, metadata would push only when you added an asset using the [!UICONTROL Add new] drop-down menu.

**Cannot approve or reject hours on an issue**

*Issues*

When a user attempts to approve or reject hours on the [!UICONTROL Hours] tab of an issue, the [!UICONTROL Approve] and [!UICONTROL Reject] buttons are missing.

**Converting an issue to a project using a template displays an incorrect error message**

*Issues*

When converting an issue to a project using a template and an error is encountered, the user is shown a page with the message "[!UICONTROL The Project no longer exists]" instead of the correct error message that explains the cause of the failed conversion.

**Cannot create proof for files over 1.5GB**

*[!DNL Workfront Proof]*

When creating a new proof, if a user uploads a file larger than 1.5GB then filename will turn red and the proof is prevented from being created.

+++

## Updates in August 2022

+++**Maintenance Update on August 25, 2022**

**Workload Balancer links display incorrectly in dashboards**

*Dashboards*

Shareable Workload Balancer links display incorrectly when added to a dashboard as an external page. Instead of using the unique view/filters associated with the link, the dashboard uses the most recently applied view/filters to the Workload Balancer.

**Add the [!UICONTROL Integrations] field to the project custom header**

*Projects*

You can now add the [!UICONTROL Integrations] field to the custom header of a project when you use a layout template. Once added, the field will display a link to an external item linked to the project which is located in [!DNL Salesforce] or [!DNL Anaplan], depending on your integration.

>[!NOTE]
>
>This maintenance update is currently only in the Preview environment. It will be released to Production a week after the Preview release.

**Custom data is not preserved when converting an issue to a blank project**

*Projects*

When a user converts an issue to a blank project (without a template), data in calculated fields is not transferred to the new project.

**"Timeline Planning mode" error when changing a date on a project**

*Projects*

When a user attempts to change a date on a project that has the [!UICONTROL Plan Mode] set to [!UICONTROL Manual save] &gt; [!UICONTROL Timeline Planning], the date does not change and the user sees the an error.

"[!UICONTROL Timeline Planning mode is available only when timelineDate is loaded. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]"

**Consistency when opening the Workload Balancer using the Month view**

*Workload Balancer*

Now, the Workload Balancer displays the users' assigned items expanded when displaying them in the [!UICONTROL Day], [!UICONTROL Week], or [!UICONTROL Month] views. Prior to this update, the assigned items were displaying expanded for the [!UICONTROL Day] and [!UICONTROL Week] views, and collapsed for the [!UICONTROL Month] view.


+++

+++**Maintenance Update on August 18, 2022**

**"[!UICONTROL Add to Iteration]" and "[!UICONTROL Add to Kanban Board]" options not available when inline editing tasks in a report**

*Reports*

When a user is viewing a list of tasks in a report and opens the [!UICONTROL More] (three-dot) menu, the "[!UICONTROL Add to Iteration]" and "[!UICONTROL Add to Kanban Board]" options are not available in the dropdown. If the report is viewed in a dashboard, the "[!UICONTROL Add to Iteration]" and "[!UICONTROL Add to Kanban Board]" options are available in the dropdown.

**Matrix reports display incorrectly when scrolling**

*Reports*

When a user is viewing a Matrix report and scrolls, some visual elements of the report may overlap or duplicate.

**[!UICONTROL Milestone] view removed from the Timesheets project list**

*Timesheets*

The [!UICONTROL Milestone] view has been removed from the timesheet project list when adding a project.

**Hyperlinks in an interactive proof are not active**

*[!DNL Workfront Proof]*

When a user is viewing an interactive proof and clicks on a link or a button that contains a link, the user is not taken to the page that the link or button links to.

**New Proof Page Missing Text Fields**

*[!DNL Workfront Proof]*

On the [!DNL New Proof] page, many text fields are not displayed (including feld labels, dropdown options, and checkbox names).

**Users do not receive notifications when tagged in a proof**

*[!DNL Workfront Proof]*

When a user is tagged in a proof comment, they do not receive an email notification about the comment.

+++

+++**Maintenance Update on August 12, 2022**

**New customizable header field added to the beginning of the header**

*Headers*

When you add a new field to a customizable header, the field is now added as the first field on the left in the header, or immediately after the [!UICONTROL Search] box inside the Layout Template. Prior to this change, the field was added as the last field in the header.

+++

+++**Maintenance Update on August 11, 2022**

**Cannot edit custom forms due to incorrect character limit on Descriptive text fields**

*Custom forms*

When a user attempts to edit a custom form, and that custom form has a [!UICONTROL Descriptive text] field that currently contains more than 512 characters, the user cannot save the edits to the custom form, and sees the following error:

"The following fields are invalid: (Field) is too long, max 512"

This affects [!UICONTROL Descriptive text] fields that have previously functioned well despite having more than 512 characters.

**Data in fields hidden by section break is not preserved when converting an issue to a project**

*Custom forms*

When a user is converting an issue to a project, and the issue includes a custom form with data in a section break that can be hidden using display logic, the data in that section is not carried to the new project.

**Data in fields hidden by section break is not preserved when converting a request to a project**

*Custom forms*

When a user is converting a request to a project, and the request includes a custom form with data in a section break that can be hidden using display logic, the data in that section is not carried to the new project.

**Cannot edit custom forms due to Descriptive Text field**

*Custom forms*

When a user attempts to edit a custom form that includes a Descriptive Text field, the field's label does not populate. The user sees the error "[!UICONTROL This field is required]" under the label field, and the user cannot edit the custom form due to this error.

**Cannot remove instructions from a custom field in the custom form builder**

*Custom forms*

When a user is editing a custom field and attempts to remove existing text in the [!UICONTROL Instructions] area, the text is not removed when the field is saved. The user can edit text, but cannot remove it entirely.

**Team assignment when creating request does not appear on new request**

*Requests*

When a user creates a request and assigns a team to the request, then submits the request, the team is not assigned to the request that is created. This affects only team assignment. User assignments function as expected.

+++

+++**Maintenance Update on August 4, 2022**

These issues were fixed only in the new [!DNL Workfront] experience.

All [!DNL Workfront Classic] functionality was removed on July 14, 2022.

**Error when changing the Planned Completion Date in the header of a task or issue**

*Tasks and Issues*

When a user attempts to change the [!UICONTROL Planned Completion Date] in the header of a task or issue, the date does not change and the user sees an error similar to the following:

`500: (Date that user is attempting to change to)/attask/api-internal/(object type)/(object ID)`

+++

## Updates in July 2022

+++**Maintenance Update on July 28, 2022**

These issues were fixed only in the new [!DNL Workfront] experience.

All [!DNL Workfront Classic] functionality was removed on July 14, 2022.

**Error when opening an item from the [!UICONTROL Home Work List]**

*[!UICONTROL Home]*

When a user attempts to open an item on their [!UICONTROL Home Work List], the item does not open, and the user sees the following message:

"[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work try refreshing this browser page.]"

**Tasks and issues delegated to a user do not appear in the user's Home Work List**

*[!UICONTROL Home]*

When user views their [!UICONTROL Home Work List], any tasks or issues delegated to the user do not appear in the list, and the user may not be aware of the delegations.

**Scheduled reports are not sent to all recipients**

*Reports*

When a scheduled report is sent, it is not sent to all of the users in the "[!UICONTROL Send to]" section. The omitted users are random, and may vary each time the report is sent.

**[!UICONTROL Cannot deselect tasks when attaching template]**

*Templates*

When a user is attaching and customizing a template, they are asked to deselect tasks that they do not want to include. However, none of the tasks display as selected, and the user cannot deselect them.

**"Locale" fields now have more specific labels**

*Terminology*

To make the function of the "[!UICONTROL Locale]" fields more clear, we've updated their labels.

* The "[!UICONTROL Locale]" field on the user profile is now labeled "[!UICONTROL Email Locale]"
* The "[!UICONTROL Locale]" field found in the [!UICONTROL Setup] >[!UICONTROL System] >[!UICONTROL Customer Info] area is now labeled "[!UICONTROL Default Email Locale]"

The functionality of these fields has not changed.

**Issues when creating timesheets**

*Timesheets*

The following issues have been reported regarding the creation of timesheets:

* When a user attempts to create a timesheet for a Role, the timesheet is not created and the user sees the error "[!UICONTROL User with primary key values 'XXXXXXXXXXX' not found.]"
* When a user attempts to create a timesheet for a Team, The [!UICONTROL typeahead] field does not populate with teams and the [!UICONTROL Create timesheet] button is disabled.


**Areas of [!DNL Workfront Proof] do not update when a proof is created, moved, or archived**

*[!DNL Workfront] Proof*

Proof is currently experiencing indexing delays. This may affect the user experience in ways including the following:

* Dashboards do not show the correct number of proofs
* Folders are not updated when a proof is created or moved
* Archived proofs remain on active proof lists.

+++

+++**Maintenance update (Hot Fix) on July 26, 2022**

These issues were fixed only in the new [!DNL Workfront] experience.

All [!DNL Workfront Classic] functionality was removed on July 14, 2022.

**Hours shown on timesheet are different from Timesheets list**

*Timesheets*

When a user opens a timesheet to view it, the hours shown are different from when the user views the same timesheet in a timesheet list.


**Request converted to project with template shows group from request queue, not group from template**

*Requests*

When a user converts a request to a project using a template, the newly created project is associated with the group that owns the request queue, not the group that is assigned on the template. This occurs even though when the project is being created, the group associated with the template is populated in the [!UICONTROL Group] field.

+++

+++**Maintenance Update on July 21, 2022**

These issues were fixed only in the new [!DNL Workfront] experience.

All [!DNL Workfront Classic] functionality was removed on July 14, 2022.

**Rejection status associated with an approval honors the approval workflow**

**NOTE: This functionality released on July 22, 2022.**

*Approvals*

If you select a status associated with an approval process as the rejection status for an approval path, the rejected object moves to the selected status, and it will be marked as "[!UICONTROL Pending approval]". For example, if you select [!UICONTROL On Hold] for the rejection status and the [!UICONTROL On Hold] status is associated with an approval process, the rejected object is placed in the status of "[!UICONTROL On Hold- Pending approval]", requiring the approval.

Before this update, the object bypassed the approval process for the rejection status, and it was placed in the [!UICONTROL On Hold] status.

**Configure a custom help URL**

*[!UICONTROL Main Menu]*

If your organization has a custom internal help site, you can configure the [!UICONTROL Main Menu] [!UICONTROL Help] icon to go to that site. This is useful if the help site contains information about how your organization uses [!DNL Workfront].
This custom URL does not affect the main Help link in the top area of [!DNL Workfront], nor the context-sensitive help links throughout [!DNL Workfront], which take users to the [!DNL Workfront] Help site.

**Cannot select Elapsed time when inline editing [!UICONTROL Task Duration]**

*Tasks*

When a user is viewing a task list and attempts to edit the [!UICONTROL Task Duration], the following duration units are not available:

* [!UICONTROL Elapsed Minutes]
* [!UICONTROL Elapsed Hours]
* [!UICONTROL Elapsed Days]
* [!UICONTROL Elapsed Weeks]
* [!UICONTROL Elapsed Months]

**[!UICONTROL My Updates] page is blank**

*Updates*

When a user attempts to view their [!UICONTROL My Updates] page, the page does not load. The user can see only the [!DNL Workfront] navigation header.

**"[!UICONTROL Only Allow SAML 2.0 Authentication]" setting is missing when copying a user**

*Users*

When a group administrator copies a user and deselects the "[!UICONTROL Send an invite email to this person]" option, the "O[!UICONTROL nly Allow SAML 2.0 Authentication]" checkbox does not appear as expected. This can occur even when all access and permission requirements for this action are met.

+++

+++**Maintenance Update on July 14, 2022**

These issues were fixed only in the new [!DNL Workfront] experience.

All [!DNL Workfront Classic] functionality was removed on July 14, 2022.

**Error when resetting password**

*Login*

When a user attempts to reset their password, they cannot reset it, and they see a message telling them they don't have access. The user cannot log in to Workfront.

**Cannot request more access to a report**

*Reports*

When a user with limited access to a report attempts to request more access to a report, the option to request more access is not available under the [!UICONTROL report actions] menu.

**Updated confirmation message when deleting a request draft**

*Requests*

When discarding a drafted request, the confirmation message that displays after clicking "[!UICONTROL Discard draft]" displays the following:

* [!UICONTROL Draft was discarded] (this is a notification to let you know that your draft was discarded)
* [!UICONTROL Undo] (this is a link you can click to revert the action of deleting the draft. This will keep the draft instead of deleting it.)

Prior to this change, the options were:

* [!UICONTROL Draft will be discarded]
* [!UICONTROL Cancel]

**Date values for Journal Entry fields incorrect when accessed through the API**

*Updates*

When a user changes a date value on an object, and then the Journal Entry that represents that date change is accessed through the API, the date values for [!UICONTROL oldDateVal] and [!UICONTROL newDateVal] returned by the API are incorrect.

**Error when attempting to undo comment**

*Updates*

When a user attempts to undo a comment, the comment does not undo and the user sees the following error:

[!UICONTROL Error 403: You do not have sufficient access to delete this Note /attask/api-internal/NOTE]

**New limitation to the number of characters in an update in Preview**

*Updates*

To improve the performance of the [!UICONTROL Updates] area, we have introduced a  new limit to the number of characters that you can enter in an update or a reply to an existing update. The new limit is 15,000 characters. This update did not change the number of characters allowed when using the API. The API character limit for updates is 4,000.

**Error when uploading attachment from [!DNL Workfront] for Outlook integration**

*Workfront Integrations*

When a user attempts to upload an attachment using the [!DNL Workfront for Outlook] integration, the attachment does not upload, and the user sees the following message:

[!UICONTROL Some attachments have not been uploaded. Reason: Something went wrong with uploading attachments.]

**Proof email notification update**

*[!DNL Workfront] Proof*

Earlier this month, as part of a patch to the [!DNL Workfront] Production environment, we made some bug fixed to the proof email notification system. This change was not communicated in the maintenance update when it was released. We've added the following information to the [Maintenance Update on June 2, 2022](#maintenance-update-on-june-2-2022) :

As a result of those bug fixes, the email address that is used to send proof notifications has changed.

Previously, proof email addresses contained your organization's subdomain. For example, notifications@[company domain].my.workfront.com

Now, proofiing email addresses no longer contain an organization subdomain. All proof email notifications will come from the following address: notification@my.workfront.com

As a result, we recommend you take the following actions if you haven't already:

* Update your spam filters to accept emails from notification@my.workfront.com
* Update your allowlists to accept emails from notification@my.workfront.com

**User options cannot be modified after initial configuration in Workflow Templates**

*[!DNL Workfront Proof]*

When a user is adding a user to a Workflow Template, they can configure options. However, after the initial configuration is complete, the user can no longer modify the following:

* "[!UICONTROL Resolve comments and apply actions]" ability
* [!UICONTROL "Share proof by tagging]" ability
* Proof role ([!UICONTROL Reviewer], [!UICONTROL Approver], etc.)

**"[!UICONTROL This project's work items]" filter has been restored in the project [!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

We have restored the "This project's work items" filter in the [!UICONTROL Assigned] area when you access the [!UICONTROL Workload Balancer] from a project.

This filter is now listed under the "[!UICONTROL Suggested]" section of the filters for the [!UICONTROL Assigned Work] area of a project's [!UICONTROL Workload Balancer].

+++

## Updates in June 2022

+++**Maintenance Update on June 30, 2022**

**Display the [!UICONTROL Workload Balancer] for one week**

*[!UICONTROL Workload Balancer]*

Based on the feedback we have received from many customers, we have now added an option to display the [!UICONTROL Workload Balancer] for one week. Prior to this update, you could display the [!UICONTROL Workload Balancer] for 4, 6, and 12 weeks. With this update, we have also changed the 12 week option to 3 months.

**Delegate panel is now available from the Workload Balancer**

*[!UICONTROL Workload Balancer]*

NOTE: This update exists only in the Preview environment. The functionality associated with this update will be available in Production with the 22.3 release.

You can now view the delegates of a task or issue from the Workload Balancer. When assigning a task or an issue from the Workload Balancer, you can view a list of assignments as well as a list of delegates for the task or issue, if they are currently delegated.

**Cannot open endpoint information in API Explorer**

*API*

When a user is viewing the [!DNL API Explorer] and clicks on an endpoint, the endpoint information does not display.

**Issues with [!UICONTROL Details] button when using the [!UICONTROL Home Calendar]**

*Home*

When a user is using the [!UICONTROL Home Calendar] and clicks on a task, one of the following may occur:

* The [!UICONTROL Details] button appears briefly, then disappears. The user cannot access the details.
* The [!UICONTROL Details] button does not appear. The user cannot access the details.
* The [!UICONTROL Details] button appears, but is not in the correct location. The user can click the button to access the details.

+++

+++**Maintenance Update (Hot Fix) on June 24, 2022**

**Date picker does not close when editing Custom Form**

*Custom Forms*

When a user is editing a custom form and attempts to change a date, the date picker does not close when the date is selected. The user cannot close the date picker by saving, canceling, or clicking away from the date picker.

This has been reported in the following areas:

* [!UICONTROL Updates] area
* [!UICONTROL Home]

**User cannot move self to another stage of a proof**

*Proofs*

When a user is viewing the [!UICONTROL Proof Workflow] of a proof and attempts to drag themself to a different stage of the proof, the user's name snaps back to the original stage, and they are not added to the desired stage.

+++

+++**Maintenance Update on June 23, 2022**

**[!UICONTROL Cannot add new request through dashboard]**

*Dashboards*

When a user is viewing a dashboard on a project and attempts to add a new request by clicking the [!UICONTROL +New Request] button, the button is unresponsive and the user cannot add a new request.

**Error when viewing items in Home Worklist**

*[!UICONTROL Home]*

When a user is viewing their [!UICONTROL Home Work List] and clicks on an item in the [!UICONTROL Approvals I've Submitted] section, the page displays the following error:

"[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]"

If the user refreshes the page, then clicks on any item in the [!UICONTROL Work List], the error appears. The issue no longer affects only items in the [!UICONTROL Approvals I've Submitted] section.

**Custom section on an object includes results not in that object**

*Objects*

When a user is viewing a [!UICONTROL custom] section on an object, the custom section displays items that are not part of that object. This has been reported when the custom section is added directly to the object, and when a custom section is added through a layout template.

**Tasks are moved to incorrect project**

*Tasks*

When a user moves tasks from Project A to Project B, then moves more tasks from Project A to Project C, the tasks originally moved to Project B appear on Project C.

**Some buttons/icons do not work when accessing [!UICONTROL Workload Balancer] from a shared link or dashboard**

*[!UICONTROL Workload Balancer]*

When a user goes to the [!UICONTROL Workload Balancer] via a shared link or a link in a dashboard and attempts to use the element at the top of the screen, the elements do not function. This has been reported for the following elements:

* [!UICONTROL Today]
* Back and Forward arrows
* [!UICONTROL Weeks]
* Calendar icon (date picker)

+++

+++**[!DNL Workfront] Scenario Planner Maintenance Update on June 23, 2022**

**Users with [!UICONTROL Manage] permissions to a plan can share it with others**

As a user with [!UICONTROL Manage] permissions to a plan in the [!DNL Scenario Planner], you can now share it with other users. Prior to this update, only the creator of the plan could share the plan with other users.

+++

+++**Maintenance Update on June 16, 2022**

**Group administrator cannot add members to group**

*Groups*

When a group administrator attempts to add a user to a group, the dropdown to select the user does not populate. The group administrator cannot select any users, and therefore cannot add any users to the group.

**Custom quarters not appearing when setting a filter**

*Filters*

When a user is creating a filter and filters by a date field, the dropdown of available operators for the date field does not include any recently added custom quarters.

**"Whoops" error when converting an issue to a project via a template**

*Projects*

When a user attempts to convert an issue to a project via a template, and the issue has a custom form that contains an admin-only section, the issue does not convert and the user sees the following error:

"[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]"

**Requests are submitted without required fields filled out**

*Requests*

When a user creates a request and does not fill in required fields, then submits the request, the request is submitted without data in the required fields. Expected behavior is that the request would not be submitted and that the user would be notified that they need to fill in the required fields before submitting the request.

**New custom quarters do not appear to save**

*Setup*

When a user is adding a new custom quarter from the Projects area of Setup and clicks [!UICONTROL Save], there is no visual indication of the save. The user does not see a success message, and the [!UICONTROL Save] button in still present and active. However, if the user refreshes the page, they can see that the new quarters appear in the list of custom quarters.

If the user adds a new quarter, clicks [!UICONTROL Save], receives no indication of the save, adds another quarter without refreshing the page, and clicks [!UICONTROL Save] again, the second added quarter may not be saved.

**[!UICONTROL Team Work Requests] page is blank**

*Teams*

NOTE: This issue exists only in the Preview environment.

When a user attempts to open the [!UICONTROL Work Requests] area on a team page, the page is blank. The user can see the top navigation bar, but no page content.

+++

+++**Maintenance Update on June 9, 2022**

**Cannot select objects to filter in [!UICONTROL Portfolio Optimizer] preferences**

*Portfolios*

When a user is in the [!UICONTROL Portfolio Optimizer] and views the [!UICONTROL Project Filters] tab in the [!UICONTROL Preferences] area, the checkboxes next to the objects are absent. The user cannot check or uncheck boxes, and therefore cannot select objects to filter.

**Cannot change [!UICONTROL Planned Start Date] or [!UICONTROL Planned Completion Date] when "[!UICONTROL Schedule From]" is not checked**

*Projects*

When a user attempts to edit the [!UICONTROL Planned Start Date] or [!UICONTROL Planned Completion Date] of a project, and the "[!UICONTROL Schedule From]" option for that project is not checked, the [!UICONTROL Planned Start Date] and [!UICONTROL Planned Completion Date] areas are disabled, and the user cannot edit those dates.

**Cannot edit access level of users**

*Users*

When a user who has Planner access that includes User Admin (Group Users) access attempts to edit users in the group they are an admin for, the [!UICONTROL Access] level field is disabled, and the user is unable to edit the access level.

+++

+++**[!DNL Workfront Scenario Planner] Maintenance Update on June 9, 2022**

**Resizable left panel in the [!DNL Scenario Planner]**

*[!DNL Workfront Scenario Planner]*

You can now resize the left panel on a Plan, in the [!DNL Scenario Planner]. This allows longer initiative names to display fully. Prior to this update, longer initiative names were truncated.

+++

+++**[!DNL Workfront Fusion] Maintenance Update on June 9, 2022**

**Data from custom forms not available in [!DNL Workfront Fusion] [!DNL Workfront] modules**

*[!DNL Workfront Fusion]*

When a user is configuring a [!DNL Workfront] module in [!DNL Workfront Fusion], and attempts to select outputs for the module, fields from custom forms are not visible. This occurs when the custom form was created for one type of [!DNL Workfront] object and then another type was added to it. [!DNL Workfront Fusion] displays only fields from custom forms originally created for the selected object type.

**Cannot scroll to view all scenario executions**

*[!DNL Workfront Fusion]*

When a user is viewing a scenario's execution history and attempts to scroll down to view more executions, the executions stop loading and the user is unable to view them. Additionally, the user cannot scroll back up to the most recent executions.

+++

+++**Maintenance Update on June 2, 2022**

**[!UICONTROL Portfolio Optimizer] shows a score of 0 when using language other than English**

*Portfolios*

When a user is using [!DNL Workfront] in a language other than English and views the [!UICONTROL Portfolio Optimizer], the score displays as 0. This may occur even when the business case is not complete.

**Calculated field values incorrect when creating project from template**

*Projects*

When a user is creating a project from a template that includes calculated fields, the field values that appear on the new project are incorrect.

**Cannot edit [!UICONTROL Conditions] in [!UICONTROL Project Preferences] area of [!UICONTROL Setup]**

*[!UICONTROL Setup]*

When a user attempts to edit [!UICONTROL Conditions] in the [!UICONTROL Project Preferences] area of [!UICONTROL Setup], the page is blank.

**New limitation to the number of characters in an update in Preview**

*[!UICONTROL Workload Balancer]*

>[!NOTE]
>
>This update applies only to the Preview environment.

To improve the performance of the Updates area, we have introduced a  new limit to the number of characters that you can enter in an update or a reply to an existing update. The new limit is 15,000 characters. This update did not change the number of characters allowed when using the API. The API character limit for updates is 4,000. Updates
Support for Typehead type custom fields in Workload Balancer filters

We are now supporting filters based on the [!UICONTROL Typeahead] type custom fields in the Workload Balancer. Prior to this patch, filtering for this type of custom fields was not possible in the Workload Balancer.

**Cannot edit permissions on a user's role**

*[!DNL Workfront Proof]*

When a user attempts to edit the "[!UICONTROL Resolve comments and apply actions]" or "[!UICONTROL Share a proof by tagging]" permissions on a user's role in [!DNL Workfront Proof], the changes are not saved. The user gets a notification that the template has been updated, but if the user opens the role permissions again they can see that the changes were not saved.

+++


## Updates in May 2022

+++**Maintenance Update on May 26, 2022**

These issues were fixed only in the new [!DNL Workfront] experience. [!DNL Adobe Workfront Classic] is no longer supported.

All [!DNL Workfront Classic] functionality will be removed in July 2022. Please transition to the new experience as soon as possible.

**Updated breadcrumb separators**

*[!DNL Workfront]*

NOTE: This update was released on May 24, 2022.

We have updated the breadcrumb separators in all areas where breadcrumbs are available. Now, the objects in the breadcrumbs are separated by pipes (|). Prior to this update, they were separated by forward slashes (/).

**Cannot edit custom forms with section breaks**

*Custom Forms*

When a user attempts to edit a custom form that has a section break, they cannot edit the form, and they see the following message:

[!UICONTROL Specified section break security cannot be applied on all object types]

**Issues when printing Dashboards to PDF**

*Dashboards*

The following issues have been reported when printing a dashboard to a PDF:
The PDF does not print every row in the report. Where lines are missing, only blank space displays.
The PDF includes blank spaces between the column headers and the first row of the report.

**[!DNL Portfolio Optimizer] shows a score of 0 when using language other than English**

*Portfolios*

When a user is using [!DNL Workfront] in a language other than English and views the [!UICONTROL Portfolio Optimizer], the score displays as 0. This may occur even when the business case is not complete.

**Some custom forms do not display when editing a template**

*Templates*

When a user attempts to edit the custom forms on a template by clicking [!UICONTROL Edit] in the template's header, the [!UICONTROL Edit Template] window only displays one of the custom forms attached to the template.

**Shared link to Workload Balancer displays assigned work incorrectly**

*[!UICONTROL Workload Balancer]*

When a user views the [!UICONTROL Workload Balancer] using a shared link, the [!DNL Workload Balancer] includes [!UICONTROL Assigned Work] in the [!UICONTROL Unassigned Work] section. [!UICONTROL Assigned Work] does not have a separate section. When the user views the [!UICONTROL Workload Balancer] without using the shared link, [!UICONTROL Assigned Work] displays as expected.

+++

+++**Maintenance Update on May 19, 2022**

**Cannot create a proof from a [!DNL PowerPoint]**

*[!DNL Workfront Proof]*

When a user attempts to create a proof from a [!DNL PowerPoint] that includes a chart, the proof creation fails.

**Cannot create a proof from a [!UICONTROL Word] document**

*[!DNL Workfront Proof]*

When a user attempts to create a proof from a [!DNL Word] document that includes a chart, the proof creation fails.

**Cannot add custom message when sharing a proof**

*[!DNL Workfront Proof]*

When a user is viewing a proof, opens the [!UICONTROL Share proof] area, and selects the [!UICONTROL Add custom message] button, the user cannot type into the text box that opens. When the user attempts to type in this box, the box immediately disappears.

**Cannot close proof**

*[!DNL Workfront Proof]*

When a user is viewing a proof and attempts to close it, the X to close the proof is missing from the upper-right corner of the proof.

**Cannot add or remove group administrator**

*Groups*

If a user is viewing a [!UICONTROL Group] page and attempts to add or remove a group administrator by using the [!UICONTROL Group Administrators] area in the header, the changes are not saved and the user sees the following error:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Horizontal scroll bar blocks item at end of list**

*Projects*

When a user is viewing a list using a view that extends off the side of the screen, the horizontal scroll bar blocks the user's view of the last item on the list.

**"[!UICONTROL Unexpected error]" when converting an issue to a project using a template**

*Lists*

When a user attempts to convert an issue to a project using a template, the issue does not convert and the user sees the following message:

[!UICONTROL An unexpected error happened]

**The [!UICONTROL Status] field in a timesheet view is now read-only**

*Timesheets*

We have changed the [!UICONTROL Status] field in a timesheet view to be read-only. Prior to this change, users could inline edit the status of a timesheet which allowed them to override the decision of the timesheet approvers.

+++

+++**Maintenance Update on May 12, 2022**

**[!UICONTROL Save] button does not stop loading when editing a project**

*Projects*

When a user is editing a project and attempts to save, they notice that the [!UICONTROL Save] button displays the word "[!UICONTROL Loading]." If the user clicks on this button to save the changes to the project, the button is unresponsive and the changes do not save.

**Field labels not appearing when viewing an object in [!UICONTROL Home]**

*Home*

When a user selects an object from their [!UICONTROL Home Work List], the area to the right of the [!UICONTROL Home Work List] that displays the object does not include field labels. The field values are present.

**Quick Filter does not automatically focus on search bar**

*Lists*

When a user is in a list and clicks the magnifying glass to quick filter, then begins typing, the text does not appear. This is because the focus remains on the magnifying glass icon rather than transferring to the search bar.

Clicking on the search bar transfers the focus and allows the user to enter the text of their search.

**Users unable to inline edit fields in a report**

*Reports*

When a user attempts to edit a field in a report, and that field is pulled from a custom form, the user is not able to edit the field. This occurs when the custom form was originally created for an object type other than the object it is attached to.

**Label and button text not visible when creating a proof**

*[!DNL Workfront Proof]*

NOTE: This issue exists only in the Preview environment.

When a user attempts to create a proof, the text is not visible for options or buttons. Therefore, the user does not know what each option or button represents, and cannot configure the proof.

+++

+++**Maintenance Update on May 5, 2022**

**Cannot add a new Billing Record**

*Projects*

When a user is in the [!UICONTROL Billing Records] area of a project and is using the [!UICONTROL New Billing Record] View, if the user attempts to add a new Billing Record, the fields for a new Billing Record do not appear and the Billing Record cannot be created.

**Error when making bulk assignment in [!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

When a user attempts to make assignments in the [!DNL Workload Balancer] of a project, the user is redirected to a page with the following message:

"[!UICONTROL An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page.]"

The user cannot navigate away from this page until they refresh the page.

**Updated navigation to open the [!UICONTROL Summary] panel for tasks and issues in the [!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

Now, simply clicking a task or issue bar in the [!UICONTROL Workload Balancer] opens the Summary Panel. Prior to this update, you had to click the [!UICONTROL Open Summary] icon in the toolbar and then click on the task or issue. This had proven a confusing experience that is now corrected. Alternatively, you can click the [!UICONTROL More] menu next to the task or issue name, then click [!UICONTROL Open Summary].

**Group administrator cannot view details of users in the group**

*Users*

When a user who is assigned to an access level that includes the [!UICONTROL User Admin (Group Users)] access setting attempts to view details of a user in their group, they see the following error:

"[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]"

**Cannot delete custom group status**

*Groups*

When a user attempts to delete a custom group status from the [!UICONTROL Group] page, the page goes blank and the status is not deleted.

**Email alert settings are inconsistent between Contacts area and User Details**

*[!DNL Workfront Proof]*

Email alert settings displayed in the [!UICONTROL Contacts] area of [!DNL Workfront Proof] for a given user are different from the email alert setting set in the user's [!UICONTROL User Details].

**Cannot use Text tool when making a comment on a proof**

*[!DNL Workfront Proof]*

When a user is making a comment on a proof and attempts to open the [!UICONTROL Text] tool, the tool does not open and the user sees the following message:

"[!UICONTROL Text data for this page is still downloading. Please wait.]"

**Proof emails will go to the user's primary email**

*[!DNL Workfront Proof]*

We're making adjustments to how proof email notifications are sent. Now, notifications will go to the user's primary email address rather than the alias email generated by the system.

For more information on why the system generates alias emails, see User synchronization between Adobe [!DNL Workfront] and [!DNL Workfront Proof].

+++

## Updates in April 2022

+++**Maintenance Update on April 28, 2022**

**Cannot scroll to [!UICONTROL Save] button when editing a timesheet**

*Timesheets*

When a user is editing a timesheet, they cannot scroll the edit window far enough to see the [!UICONTROL Save] button, and therefore cannot edit the timesheet.

**Electronic signature now checks Federation ID**

*Proofs*

When signing a proof electronically, the system now checks the Federation ID, if you have SSO set up in [!DNL Workfront Proof], in addition to your email in [!DNL Workfront].

Previously, the system checked only your email in Workfront.

+++

+++**Maintenance Update (Hot Fix) on April 25, 2022**

**[!UICONTROL Workload Balancer] does not load**

*[!UICONTROL Workload Balancer]*

When a user attempts to open the [!UICONTROL Workload Balancer], the header and left navigation load, but the content of the Workload Balancer does not load. The user sees flashing gray squares instead of data. Occasionally, part of the content loads, but the user still sees flashing gray squares where the missing data would be.

+++

+++**Maintenance Update on April 21, 2022**

**Adding a task causes page to jump down**

*Tasks*

When a user adds a task below an existing task in a list, the page jumps to lower in the list. Although the new task is in the correct place, the user must scroll back up to locate it.

**Users added to a proof cannot access the proof's work item in [!DNL Workfront]**

*Proofs*

If a user is added to a stage in a proof's workflow, the user is not added to the Document sharing and does not get permissions to the proof's work item in [!DNL Workfront]. When the user is in [!DNL Workfront] and attempts to open the work item the proof is attached to, they see the following message:

"[!UICONTROL You do not have sufficient access to view this (object)]"

This issue is specific to proofs already created and users being added after the fact. Adding users to the Workflow before proof creation works as expected.

**Cannot send password reset email from [!DNL Workfront]**

*Users*

When a user attempts to send a password reset email from a user list in [!DNL Workfront], the option to send the email is not available.

**Button displays "[!UICONTROL Start Issue]" rather than "[!UICONTROL Start Request]"**

*Requests*

When a user views a request assigned to their team, they see a "[!UICONTROL Start Issue]" button in the header rather than a "[!UICONTROL Start Request]" button.

**"[!UICONTROL Undo comment]" option removes tagged users**

*Updates*

When a user tags another user in a comment, posts the comment, and then selects the "[!UICONTROL Undo comment]" option, the comment appears in an update box as usual, but the tagged user is not in the [!UICONTROL Tagged users] box.

**Cannot scroll when using [!UICONTROL Milestone] view in a report**

*Reports*

When a user is viewing a report and selects the [!UICONTROL Milestone] view, the page displays the Milestone view but no longer scrolls, and the user cannot view any Milestones that would be further down the page.

**Incorrect currency when report is displayed in dashboard**

*Reports*

When a user views a report in a dashboard, the currency used in the report is incorrect. When the user views the report outside of the dashboard, the currency is correct.

**Completed filter is not displaying Completed work item**&#x200B;s

*[!UICONTROL Home]*

When a user views their [!UICONTROL Home Work List] with the [!UICONTROL Completed] filter selected, Completed work items do not display in the list. When the [!UICONTROL All] filter is selected, Completed items are included in the list, showing that the Completed items exist.

**[!DNL Workfront] does not load**

*[!DNL Workfront]*

When a user attempts to log into [!DNL Workfront], the page appears to be stuck in a loop of redirects or refreshes, and does not load.

+++

+++**Maintenance Update on April 14, 2022**

**Cannot add a task from a report on a custom section on a task**

*Tasks*

When a user is viewing a custom section on a task, and the section contains a task report, the user cannot add a task from that report. The [!UICONTROL Add Task] button highlights the report, but does not open a window for the user to add a task.

**Done button in wrong location when editing a view**

*Views*

When a user is editing a view, the [!UICONTROL Done] button appears higher on the screen, and may overlap text.

The user can edit the view as usual. Functionality is not affected.

**Cannot scroll when using [!UICONTROL Milestone] view in a report**

*Reports*

When a user is viewing a report and selects the [!UICONTROL Milestone] view, the page displays the Milestone view but no longer scrolls, and the user cannot view any Milestones that would be further down the page.

**Blank screen when viewing updates**

*Updates*

When a user is viewing updates and scrolls the screen to view updates further down, the screen becomes blank and the user can not see any updates.

**Error when bulk assigning user to task that is not assigned to User's role**

*[!UICONTROL Workload Balancer]*

When a user in the [!UICONTROL Workload Balancer] attempts to assign tasks to a user whose Job Role does not match the Job role assigned to the tasks, the user sees a message that the task will be assigned using the primary Job Role of the assigned user. However, when the user clicks "[!UICONTROL Assign]," the tasks are not assigned and the user sees the following error:

"[!UICONTROL Error. The server encountered an unknown error.]"

+++

+++**Maintenance Update on April 7, 2022**

**Users added to proofs have incorrect roles**

*Proofs*

When a user adds another user to a proof, that user's role on the proof is set as "[!UICONTROL Read-only]" despite the user's actual proof role.

**Cannot send password reset email to user**

*Users*

When a user attempts to send a password reset to another user, they see that the [!UICONTROL Send Forgot Password Email] option is not available in the [!UICONTROL More] menu.

**[!UICONTROL Update All] sends updates to user profiles instead of project**

*Updates*

When a user is viewing the [!UICONTROL People] area of a Project and selects the [!UICONTROL Update All] option, then enters an update, the update is not posted to the project itself. Instead, it is posted to the individual user profiles of each user on the project.

**Excessive number of pages when printing updates**

*Updates*

When a user is viewing an update stream that would be more than one printed page, and attempts to print the page, the print screen shows that the number of pages is far above the actual number of pages needed to print the updates. If the user then attempts to print to PDF, the PDF creation fails.

**Users are unable to see the entire list of entities shared with a report when the "[!UICONTROL Visible System-Wide]" setting is enabled**

*Reports*

When sharing reports with multiple entities displaying in the [!UICONTROL Report Access] box, users are unable to scroll to the bottom of the list to see the entire list when the "[!UICONTROL Visible System-Wide]" setting enabled.

**Incorrect currency used in reports**

*Reports*

If a user sets the currency of a project to be different than the default currency, then views a report on that project, the currency appears as the default currency instead of the project's currency.

**Last Viewed information not updating in [!UICONTROL Report Usage] reports**

*Reports*

When a user is viewing a report that displays information regarding the last time the report was viewed, that information may be blank or may be old data. This issue affects fields including the following:

* [!UICONTROL Last Viewed By]
* [!UICONTROL Last Viewed Data]
* [!UICONTROL Last X Viewers]
* [!UICONTROL Views This Month / Quarter / Year]

**Completed tasks displaying in [!UICONTROL Home Work List]**

*[!UICONTROL Home]*

When a user is viewing their [!UICONTROL Home Work List], they see Complete tasks in the list, even when the option to display Completed tasks is not selected.

**Schedule button not visible to schedule Sandbox refresh**

*Sandbox Environment*

The [!UICONTROL Schedule] button used to schedule a sandbox refresh is not visible in the top banner of the sandbox environment.

**Changes to a calculated field affect all calculated fields on a form**

*Custom Forms*

When a user is in the Custom Form Builder and changes the value of a calculated form, all calculated fields on the form show the new value. This can affect new or existing calculated fields.

**Colors flickering on custom form builder**

*Custom Forms*

When a user is working with calculated fields on the custom form builder, the colors of the fields and expressions flicker.

**[!UICONTROL Cannot reject an approval]**

*Approvals*

When a user attempts to reject an approval, the [!UICONTROL Reject] button is unresponsive, and the approval is not rejected.

**[!UICONTROL Projects] tab defaults to All Project section despite previous selection**

*Projects*

When a user goes to a Projects page via a tab that has been pinned as part of the layout template, the page defaults to the [!UICONTROL All Projects] area of the left navigation. This occurs even when the user chooses another area of the left navigation, then navigates away from the Projects page and back.

+++


## Updates in March 2022

+++**Maintenance Update on March 31, 2022**

**Timezones not consistent between [!DNL Workfront] and [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

When a user's profile is set to a specific timezone in [!DNL Workfront], the user's timezone in [!DNL Workfront Proof] is set to a different timezone.

**Link to submit a requested document leads to blank page**

*Documents*

When a user receives a request to submit a document, and clicks on the link to the object where the document was requested, the link leads to a blank page. This may occur when clicking a link in an email or in an in-app notification.

**Group is assigned incorrectly when converting issue to project**

Groups

When a user converts an issue to a project using a template, the functionality is:

* If the template has a group assigned, that group displays in the issue conversion window as the group for the new project.
* If the template has no group assigned, the default group of the user who is converting the issue displays in the issue conversion window as the group for the new project.
* If the template has no group, the new project should inherit the group from the issue's project.

**Cannot attach cross-object custom form to request queue**

Requests

When a user attempts to add a cross-object custom form to a queue's details page, the cross-object form does not appear in the dropdown list of available forms, and the user cannot select it to add to the queue details.

**Users cannot be assigned with secondary job role on [!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

When a user attempts to assign another user to a task on the [!UICONTROL Workload Balancer], and the task is assigned to a job role other than the assigned user's primary job role, the user is assigned to the task by their primary job role, and the following message displays:

"\<Name\> does not match the role of \<Task role assignment\>. 1 work item currently assigned to the role of <\Task role assignment\> will be assigned to \<Name\> in the role of \<Primary job role\>."

This occurs even if the user does have the Task role assignment's job role as a secondary job role.

**Issue with Scrum Board "Show more work items" b**&#x200B;ar

*Agile*

When a user clicks the [!UICONTROL Show more work items] bar on a Scrum Board, then scrolls to see the new items, the [!UICONTROL Show more work items] bar sticks to the Scrum Board and moves with it when scrolled. This can make the cards hard to read.

**Red dots appear on required fields in custom forms**

Custom Forms

When a user views a required field on a custom form, they see two red dots below the asterisk that indicates that the field is required.

**Time dropdown cut off in prompts**

*Reports*

When a user is filling out the prompts for a report and encounters a date picker, the time selector at the bottom of the date picker does not display hours beyond 2, and the user cannot select any hour value besides 1 or 2.

+++

+++**Maintenance Update (Hot Fix) on March 29, 2022**

**Unable to modify or save calculations in the Custom Form builder**

*Custom forms*

If a user manually enters a calculation into a calculation field on the Custom Form builder and saves the form, the calculation is not saved. If the user reopens the custom form, that field is blank.

If a user enters a calculation into a calculation field on the Custom Form builder by using the dropdowns and saves the form, that value is saved. However, if the user reopens the custom form, they cannot edit this field or remove the value, either manually or with the dropdown.

NOTE: This issue fix included additional functionality. Now, when you begin typing in a calculated field, possible expressions or calculations display in a dropdown below, the same way they do in the Calculation Editor. Click an item in the dropdown to add it to the calculated field.

+++

+++**Maintenance Update on March 24, 2022**

**Timezones not consistent between [!DNL Workfront] and [!DNL Workfront Proof]**

*[!DNL Workfront Proof]*

When a user's profile is set to a specific timezone in [!DNL Workfront], the user's timezone in [!DNL Workfront Proof] is set to a different timezone.

**Required field error for filled-in custom fields when attaching a template**

*Projects*

When attaching a template with required custom fields to a project where the field already exists and is filled out, users see the following error: "[!UICONTROL There are incomplete fields. Enter values for required fields before you can continue.]"
Clicking "[!UICONTROL Take me there]" allows them to see that the fields are filled out and they can attach the template successfully.

**The [!UICONTROL Workload Balancer] flashes when you toggle between dates**

*[!UICONTROL Workload Balancer]*

The hours of the user listed first in the [!UICONTROL Workload Balancer] do not display when you update the timeline. The user and their hours display with all grey boxes that just blink. This happens if you move forward and backwards on the timeline.

Updating the filter does seem to reset the display. However, moving backwards and forwards on the timeline causes the display flash again and the user hours to not display.

**Custom terminology is inconsistent**

*Layout Templates*

Users are reporting that when the [!DNL Workfront] administrator customizes the terminology for some objects using a Layout Template, the new object name displays inconsistently in the interface.

For example, on the [!UICONTROL Projects] page, you can still see the page title displayed as "[!UICONTROL Projects]", even though the [!DNL Workfront] administrator changed the name for "[!UICONTROL Projects]" to something else.

This causes confusion for end users.

+++

+++**Maintenance Update on March 17, 2022**

**Thumbnail and main images are blank when viewing multipage files using [!DNL Safari] browser**

*[!DNL Workfront Proof]*

When a user attempts to view a file with multiple pages in the [!DNL Safari] browser, the thumbnail page images are blank. Occasionally, the main image may also be blank.

**Incorrect user list when making bulk assignments in the [!UICONTROL Workload Balancer]**

*[!UICONTROL Workload Balancer]*

When a user is making a bulk assignment in the [!UICONTROL Workload Balancer] and selects a Project and Job Role, the list of users available is incorrect. It may show users without the Job Role or Project permissions, and users with the Job Role and Project permissions do not appear in the list.

**[!UICONTROL Sorting is not working in reports]**

*Reports*

When a user clicks on a column to sort by it, the sort appears to work but instantly the results revert to the original sorting as it displayed before clicking the column. The sorting on any column is not retained.

**Selecting "[!UICONTROL Nothing]" reverts to the [!UICONTROL Report Default] grouping**

*Reports*

When a report has a built-in grouping and the user attempts to select "[!UICONTROL Nothing]" in the [!UICONTROL Grouping] drop-down menu, the report displays shortly with no grouping and then revert to the [!UICONTROL Report Default] grouping.

**Removed "[!UICONTROL Blueprints access]" tab from Blueprints preferences**

*Blueprints*

NOTE: This issue exists only in the Preview environment.

The [!UICONTROL Blueprints access] tab has been removed from the Blueprints preferences modal. No functionality has been removed from the Blueprints preferences.

+++

+++**Maintenance Update (Hot Fix) on March 14, 2022**

**Cannot scroll down user list when making assignment on Kanban board**

*Agile*

When a user is viewing a [!DNL Kanban] board and attempts to make an assignment, the user list that appears when they type keeps jumping back to the top as they scroll down. The user is unable to select a user that is not near the top of the list, and cannot save the assignment change.

**[!UICONTROL Milestone] View in project report causes error**

*Reports*

When displaying a project report using the [!UICONTROL Milestone] View, users get a "[!UICONTROL APIModel INTERNAL does not support namedQuery TILE:milestone-view (UIVW)]" error.

**Custom terminology is inconsistent**

*Layout Templates*

Users are reporting that when the [!DNL Workfront] administrator customizes the terminology for some objects using a Layout Template, the new object name displays inconsistently in the interface.

For example, on the [!UICONTROL Projects] page, you can still see the page title displayed as "[!UICONTROL Projects]", even though the [!DNL Workfront] administrator changed the name for "[!UICONTROL Projects]" to something else.

This causes confusion for end users.

**Unable to update calculations for existing calculated fields**

*Custom Forms*

Users are unable to update/ change the calculations in calculated fields. If the field was created and saved with without a calculation, every time you try to add an expression and save/apply, the builder reverts back to being blank.

If you create a calculated field with a certain expression and save it, every time you try to change the calculation, it reverts back to its previous value.

**[!UICONTROL Invalid Parameter] error when resetting passwords**

*Login*

Users are unable to reset their passwords in any environment. When they enter their email and try to proceed they see an error.

[!UICONTROL Error: Invalid Parameter: Search Parameter value "domain"].

+++

+++**Maintenance Update on March 10, 2022**

**Issues logging in to Preview environment**

*Login*

The following issues with logging in to the Preview environment have been reported.

When a user attempts to log in to the Preview environment, a message appears indicating that they put in the wrong ID or password.

When a user attempts to reset their password, they see the error "[!UICONTROL ?Multiple users were found with the email address <example@example.com>?]"

**Custom forms load slowly in [!UICONTROL Project Details] area**

*Projects*

When a user attempts to view a project's [!UICONTROL Project Details] area, any custom forms that are attached to the project load only after a delay of 15 seconds or more. The [!UICONTROL Add custom forms] option is also affected by this delay.

**Custom form field values not saved in document summary panel**

*Documents*

When a user updates custom form fields in the document summary panel, and one or more of them is a typeahead field, then saves the changes and navigates away from the summary panel, the updates are not saved. This occurs only when a typeahead field is edited, although all fields are affected.

**Data not preserved when converting templates due to template sharing access levels**

*Projects*

When a user who has View access on a shared template attempts to convert an issue to a project, any data in custom form sections that require [!UICONTROL Conrtibute] or higher access to view is not transferred to the created project.

**Error when uploading new document version**

*Documents*

When a user attempts to upload a new version of a document from the document list, the document does not upload and the user sees the following error:

[!UICONTROL Error Cannot invoke "com.attask.boz.Document.getCurrentVersion()" because "document" is null]

**Unable to edit billing rates**

*Projects*

When a user attempts to edit a billing rate on the [!UICONTROL Billing Rates] tab of a project, clicking the [!UICONTROL Edit] button opens the [!UICONTROL Edit] window briefly, but it closes before the user can edit the billing rate. Clicking the button again does not open the edit window.

**Public link for document leads to blank page**

*Documents*

When a user attempts to open a document using a public link, the link leads to a blank page. This occurs when the link is opened in a window where an active [!DNL Workfront] session is open.

**Whoops error when adding task or issue to list**

*Tasks and Issues*

When a user who is not an admin attempts to add a task or issue to a list, and fills in custom fields, the task or issue is not created and the user sees the following error:

[!UICONTROL Error Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Leaving an update after a status change reverts the object to a previous state**

Projects, tasks, and issues

Changing the status of a project, task, or issue and then immediately starting typing an update without refreshing the page causes the update box to show the previous status. If the update is posted, the object is reverted to the previous status.

**Users added to proofs have incorrect roles**

*Proofs*

When a user adds another user to a proof, that user's role on the proof is set as "[!UICONTROL Read-only]" despite the user's actual proof role.

Workaround:
Set the user's proof role in their profile to something else, then reset to the correct role.

**Custom form does not load when converting issue to project using template**

*Custom forms*

When a user attempts to convert an issue to a project using a template, one or more of the custom forms attached to the template may not load. When the user configures the template for the new project, instead of the custom forms they see the following message:

"[!UICONTROL Something went wrong, could not load form]."

**User unable to add issue inline with custom drop-down field displaying in the view**

*Lists*

When a user is adding an issue from inline and there is a custom view with custom drop-down fields applied to the list, there is an error when they fill out the drop-down field only. The user has access to edit custom form and is the project owner with manage rights to the project.

[!UICONTROL Error: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it!]

**Permissions to add tasks to a project are not required to move or copy a task to the project**

*Tasks*

You now can move or copy a task to another task in a project without having  permissions to add tasks to the destination project. You must have permissions to add tasks to at least one of the destination project's tasks. Prior to this update, you were required to have permissions to add tasks to the project to move or copy a task to the project or to any of its tasks.  This update is now available in the Production environment. It has been available in the Preview environment starting with the March 24, 2022 maintenance update.

NOTE: This update will be available in the Production environment when copying or moving issues after the 22.2 Production release. For more information about the current release, see workfront.com/release.

**Prompt drop-down menu is cut off**

*Reports*

When using a prompt  in a report, the drop-down menus that allow you to select the filtering criteria for the report are cut off. As a result, the criteria at the bottom of the selection drop-down menu does not display.

**Work item reverts to previous status when an update is made**

*Updates*

When a user changes the status of a work item in the header, the status does not update in the [!UICONTROL Update] area. If the user then makes a update, the dropdown still shows the previous status. When the update is saved, this previous, incorrect status overwrites the status that was set in the header.

+++

+++**Maintenance Update on March 3, 2022**

**Cannot add document from [!DNL Google Drive]**

*Documents*

When a user attempts to add a document from [!DNL Google Drive], the selection is unresponsive, and the user is unable to select documents to add.

**Tagged users are not added to update thread**

*Updates*

When a user is tagged in an update, they are not shown in the "[!UICONTROL To]" area of the update or its replies.

**Proof user has two separate proofing accounts**

*[!DNL Workfront Proof]*

A user's email address in [!DNL Workfront Proof] may be in two separate accounts with separate IDs, giving the user two accounts. This may make it difficult to locate the correct account.

**Whoops error displaying in report headers**

*Reports*

When a user views a report, the following error displays in the report header:

"[!UICONTROL Let's try that again. Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]"

If the user is viewing a dashboard, the error may appear in the header for all the reports on the dashboard.

**Data in Admin-edit-only fields of custom form is not preserved when converting issues to projects**

*Projects*

When a non-admin user attempts to convert an issue to a project using a template, and the issue contains data in fields that can only be edited by an admin, the data in those fields does not carry over to the new project.

When an admin converts the issue, the data is carried to the new project as expected.

**[!DNL XLS] and [!DNL XLSX] file size limit temporarily decreased to 100 MB for proofs**

*Proofing*

In order to address a security issue, we've temporarily limited the maximum file size for [!DNL XLS] and [!DNL XLSX] files to 100 MB when creating a proof.

NOTE: This update was in the Preview environment on February 24, and will be in the Production environment on March 3.

**Update to Workfront Search**

Search

A phased rollout began this week to update the infrastructure for the [!DNL Workfront] Search functionality. The update will make future improvements to Search easier and more reliable. With these changes, items added to [!DNL Workfront] will be indexed more quickly and therefore will return in search results sooner.

The phased rollout will continue for 2 weeks.

**Updated toolbars for reports within dashboards**

Reports

Reports within dashboards now show a new toolbar. This toolbar is part of the updates to lists and reports that are happening throughout [!DNL Workfront].

+++


## Updates in February 2022

+++**Maintenance Update (Hot Fix) on February 24, 2022**

**Data not preserved when converting issues to projects if field is hidden on template**

*Projects*

When a user converts an issue to a template, and the template includes a custom form that displays or hides fields based on the values in other fields, any data in fields that are hidden on the (dataless) template at the time of conversion is not carried into the new project.

**Cannot export resource planner by Role**

*Resource Planner*

When a user attempts to export the [!DNL Resource Planner] when using the [!UICONTROL View by Role] option, the export does not succeed and the user receives an email with the following message:

An error occurred while exporting your [!DNL Resource Planner] data.

**Copy request button not working**

*Requests*

When a user attempts to copy a request, the [!UICONTROL Copy Request] button does not work if the user does not have View access to the queue topic.

+++

+++**Maintenance Update on February 24, 2022**

**Custom form data disappears when other form fields are filled out**

*Custom forms*

When a user is filling out a custom form as part of converting an issue to a project, filling out one custom field may cause data in another custom field to disappear. If the user enters the missing data again, when they try to create the project, they see the following error message:

"[!UICONTROL You must be a system admin to change this custom data parameter value]"

**"[!UICONTROL This approval process can be used by...]" field missing**

*Approvals*

When a user is creating or editing an approval process in the [!UICONTROL Setup] area, the "[!UICONTROL This approval process can be used by...]" field is missing. This can occur when creating an approval process or when editing an existing one.

**System admin cannot reassign users when deleting a group**

*Groups*

When a system administrator deletes a group, they will only have the option to reassign that group's users to groups that the system administrator is a group administrator for. Other groups do not appear in the dropdown, and the admin cannot select them.

**Whoops error when converting issue to project**

*Projects*

When a user attempts to convert an issue to a project using a template, and adds or removes custom forms from the template, the issue does not convert and the user sees the following message:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Cannot open proof; page refreshes**

*Proofs*

When a user attempts to open a proof, the proof is unable to open. Eventually, the page refreshes.

**[!DNL XLS] and [!DNL XLSX] file size limit temporarily decreased to 100 MB for proofs**

*Proofing*

In order to address a security issue, we've temporarily limited the maximum file size for [!DNL XLS] and [!DNL XLSX] files to 100 MB when creating a proof.

NOTE: This update will be in the Preview environment on February 24, and in the Production environment on March 3.

**Permissions to add tasks or issues to a project are not required to move or copy a task or an issue to the project**

*Projects*

You now can move or copy a task or an issue to another task in a project without having permissions to add tasks or issues to the destination project. You must have permissions to add tasks or issues to at least one of the destination project's tasks. Prior to this update, you were required to have permissions to add tasks or issues to the project to move or copy a task or an issue to the project or to any of its tasks. This update is available only in the Preview environment.

NOTE: This update will be available in the Production environment when coping or moving tasks on March 10th. This update will be available in the Production environment when copying or moving issues with the 22.2 Production release. For more information about the current release see workfront.com/release.

**Update to Workfront Search**

*Search*

A phased rollout began this week to update the infrastructure for the [!DNL Workfront] Search functionality. The update will make future improvements to Search easier and more reliable. With these changes, items added to [!DNL Workfront] will be indexed more quickly and therefore will return in search results sooner.

The phased rollout will continue for 2 weeks.

+++

+++**[!DNL Workfront Fusion] Maintenance Update on February 18, 2022**

**Field value type validation added to [!DNL Anaplan] list items properties**

*[!DNL Adobe Workfront Fusion]*

An issue has been fixed that allowed users to put the incorrect data type into fields for List Item properties. Validation of the property type allows [!DNL Fusion] to ensure that the correct data type is sent to Anaplan, eliminating errors caused by incorrect data types.

+++

+++**Maintenance Update on February 17, 2022**

**Error when deleting predecessor from Predecessors tab**

*Tasks*

When a user attempts to delete a predecessor from the [!UICONTROL Predecessors] tab on a task, the task does not delete, and the user sees the following error:

[!UICONTROL Task with primary key value(s) "" not found]

**Whoops error when opening users page**

*Users*

When a user attempts to open the [!UICONTROL Users] page, the page does not open and the user sees the following error:

[!UICONTROL Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.]

**Overlapping elements in the header of a report on a dashboard**

*Dashboards*

When a user views a report on a dashboard, they see that the groupings icon and label overlaps the links to [!UICONTROL Details] and [!UICONTROL Summary].

**Issues with "[!UICONTROL More]" menu for documents and proofs**

*Documents*

When a user selects a document or proof on a [!DNL Workfront Classic] document list, then clicks "[!UICONTROL More]," they may see one of the following issues:
The button is unresponsive
All options under the button are labeled "[!UICONTROL object Object]" and cannot be used.

**"You must be a system admin" error when creating a project**

*Projects*

When a user who is not an administrator attempts to create a project, and attaches a custom form that has a section available only to administrators, they cannot create the project and they see the following error:

"You must be a system admin to change this custom data parameter value"

**Data in admin-only section of custom form is not preserved when converting issues to projects**

*Projects*

When a user converts an issue to a project using a template that has a custom form with an admin-only section, any data in the admin-only section is not carried over to the new project. This occurs even if an admin is converting the issue.

+++

+++**Maintenance Update on February 10, 2022**

**"[!UICONTROL You must be a system admin]" error when creating a project**

*Projects*

When a user who is not an administrator attempts to create a project, and attaches a custom form that has a section available only to administrators, they cannot create the project and they see the following error:

"[!UICONTROL You must be a system admin to change this custom data parameter value]"

**Users who have been deactivated and reactivated do not appear in [!UICONTROL Proof contacts]**

*[!DNL Workfront Proof]*

When a user views their contacts list in [!DNL Workfront Proof], users who have been deactivated and reactivated do not appear in the list.

**"Something went wrong" message when converting an issue to a project using a template**

*Projects*

When a user who is not an admin attempts to convert an issue to a project using a template, custom form fields that are visible only to admins show the following message:

"[!UICONTROL Something went wrong, could not load form]"

**"Cannot load page content" error when viewing project preferences**

*Setup*

When an admin user attempts to view projects, tasks, or issues under [!UICONTROL Project Preferences] in the [!UICONTROL Setup] area, the page does not load and the user sees the following error:

"[!UICONTROL Cannot load page content. Please try refreshing the page.]"

+++

+++**Maintenance Update on February 3, 2022**

**[!UICONTROL BizContext] error when logging in**

*Login*

When a user is attempting to log in to [!DNL Workfront], the login is unsuccessful, and the following message displays:

"[!UICONTROL Let's try that again. Database error: BizContext commit failed!]"

This has been reported in the Preview environment.

**Issue update stream disappears if issue is pending approval**

*Updates*

When a user clicks into the [!UICONTROL New update] box in the update stream of an issue that is pending approval, the entire update stream disappears.

**Error when uploading new version of a document**

*Documents*

When a user attempts to upload a new version of a document, the new version does not upload and the user sees one of the following errors:

* [!UICONTROL documentID cannot be null]
* [!UICONTROL Error: Invalid Parameter: documentID value "undefined"]

**Public link for document leads to blank page**

*Documents*

When a user attempts to open a document using a public link, the link leads to a blank page. This occurs when the link is opened in a window where an active [!DNL Workfront] session is open.

**List controls do not work on reports in dashboards**

*Dashboards*

When a user is viewing a report in a dashboard and attempts to change the filter, grouping, or view of the report, the filter, grouping, or view does not change.

**"[!UICONTROL You must be a system admin]" error when creating a project**

*Projects*

When a user who is not an administrator attempts to create a project, and attaches a custom form that has a section available only to administrators, they cannot create the project and they see the following error:

"[!UICONTROL You must be a system admin to change this custom data parameter value]"

**Custom data not preserved when converting issue to project**

*Projects*

When a user converts an issue to a project using a template, data from a custom form on the issue is not transferred to the comparable custom form on the project. This happens to data that is in custom fields that may be hidden based on the values of other custom fields.

**Error when converting issue to project**

*Projects*

When a user attempts to convert an issue to a project, the issue does not convert and they see the following error:

"[!UICONTROL An unexpected error occurred]"

+++


## Updates in January 2022

+++**Maintenance Update on January 27, 2022**

**Custom data not preserved when converting issue to project**

*Projects*

When a user converts an issue to a project using a template, data from a custom form on the issue is not transferred to the comparable custom form on the project. This happens to data that is in custom fields that may be hidden based on the values of other custom fields.

**User list on agile board is not alphabetical**

*Agile*

When a user views the user list on an agile board, the users are not displayed in alphabetical order. Instead, the users with the most assignments are listed first.

**Updated links for copying and moving issues**

*Issues*

In the Preview environment, the links for copying and moving issues have been updated to "[!UICONTROL Copy to]" and "[!UICONTROL Move to]" both on the issue page as well as in an issue list.

**Add up to 45 IP addresses to your [!DNL Workfront] allowlist**

*Setup*

The limit for IP addresses added to your [!DNL Workfront] allowlist has increased from 30 to 45.

+++

+++**Maintenance Update on January 20, 2022**

**"[!UICONTROL Invalid Parameter]" error when creating project from template**

*Projects*

When a user attempts to create a project from a template, and removes a custom form from the template when creating the project, the project is not created and the user sees an "[!UICONTROL Invalid Parameter]" error message that mentions a required field on the removed custom form.

**User list does not load in [!DNL Safari] browser**

*Users*

When a user goes to the [!UICONTROL Users] area, the header appears but the list of users does not load.

**Lag when dragging tasks in a list causes task to move to wrong location**

*Lists*

When a user attempts to move a task in a list by dragging it, the blue line that indicates where the task will be moved to moves much more slowly than the cursor. When the user releases the task, it will move to where the blue line is, even if the cursor is pointing to a different location in the list.

+++

+++**[!DNL Workfront Fusion] Maintenance Update on January 14, 2022**

**Some mapped fields reset when selecting [!UICONTROL new field to map]**

*[!DNL Workfront Fusion]*

When at least one field in the [!DNL Workfront] [!UICONTROL Create] or [!UICONTROL Update] modules has map enabled and a user selects a new field to map, the previously mapped fields that are map enabled lose mapping values.

+++

+++**Maintenance Update on January 13, 2022**

**Unable to add a hyperlink to a comment in the Summary panel**

*Tasks*

When a user is making a comment in the summary panel of a task and attempts to add a hyperlink to the comment, the hyperlink window opens, but as soon as the user clicks into the window it closes and the user cannot add a hyperlink. If a user tabs into the window, they can type or paste a link into the field, but the hyperlink does not save. In both cases, the task becomes deselected.

**Edit Team page does not close**

*Teams*

When a user attempts to edit a team, the [!DNL Edit team] page does not close. The user cannot close the page by clicking either button, clicking the X, or navigating away from the page.

**Email and in-app notifications are not being sent**

*Notifications*

When an event that should trigger a notification occurs, the notification is not sent. This may occur for email or in-app notifications, and may occur even though other notifications are being sent.

**[!UICONTROL My Work] list appears empty**

*[!UICONTROL My Work]*

When a user views their [!UICONTROL My Work] list, and the layout template for their [!UICONTROL My Work] list includes a numerical value such as [!UICONTROL Percent Complete], the [!UICONTROL My Work] list does not display.

**[!UICONTROL Percent Complete] and [!UICONTROL Hours Complete] cannot be modified on Agile Board**

*Agile*

When a user selects "[!UICONTROL Show more work items]" on the Agile Board, then attempts to change the [!UICONTROL Percent Complete] or [!UICONTROL Hours Complete] on one of the newly loaded work items, they cannot change the Percent Complete or Hours Complete. The [!UICONTROL Percent Complete] button is also gray, indicating that it is inactive.

+++

+++**Maintenance Update on January 6, 2022**

**"[!UICONTROL Invalid Parameter]" error when attaching templates or custom forms to projects**

*Projects*

When a user attempts to attach a custom form or a template to an existing project, then fills out the required fields on the custom form or template and saves the changes to the project, the changes do not save and the user sees an "[!UICONTROL Invalid Parameter]" error at the top of the project details page.

**Proof comments do not display in Document updates**

*Proofs*

When a user views a proof in the [!UICONTROL Documents] area, any comments made on the proof itself do not display in the [!UICONTROL updates] area of the document.

**[!UICONTROL Workload Balancer]: "[!UICONTROL ?[object Object]?]" displays in overallocation information**

*[!UICONTROL Workload Balancer]*

If a user shows as overallocated in the [!UICONTROL Workload Balancer] due to a task overlapping the user's time off, and another user views their overallocation, the "[!UICONTROL Capacity]" area of the overallocation information displays "[!UICONTROL ?[object Object]?]" instead of the actual capacity of the user.

+++

## Previous maintenance updates

Information regarding previous maintenance updates is available here:

* [[!DNL Workfront] Maintenance Updates Archive - 2021](2021-updates.md)
