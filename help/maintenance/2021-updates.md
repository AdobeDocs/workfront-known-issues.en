---
title: Workfront Maintenance Updates for 2021
description: History of 2021 Maintenance Updates for [!DNL Adobe Workfront]
exl-id: 57a3636e-fd01-4ee6-bc96-df535b62d4f7
---
# 2021 [!DNL Workfront] Maintenance Updates

The following maintenance updates were made in 2021:

## Updates in December 2021

+++**Maintenance Update on December 23, 2021**

**New tasks default to incorrect task constraint**

_Tasks_

When a user creates a new task using the "New Task" button, and the New Task Default Start Date option is set to "Today," the task constraint of the created task is set to "As soon as possible" rather than "Start no earlier than." This can also occur when using project templates

**Opening schedule in Groups area leads to blank page**

_Setup_

When a user is viewing groups in the [!UICONTROL Setup] area and attempts to open, edit, or copy a schedule, the schedule does not open and the user sees a blank page.

**Changes do not display when reordering left navigation**

_Navigation_

When a user attempts to reorder the left navigation panel by dragging an item, the item appears back in its previous place when the user drops it. If the user refreshes the page, the left panel displays the new order.

**Link to submit a requested document leads to blank page.**

_Documents_

When a user receives a request to submit a document, and clicks on the link to the object where the document was requested, the link leads to a blank page. This may occur when clicking a link in an email or in an in-app notification.

**[!DNL Workload Balancer] shows 0 hours allocated**

_[!DNL Workload Balancer]_

When a user is viewing the [!DNL Workload Balancer] and has the "Show projected dates" setting enabled, any dates in the future display 0 hours allocated.

**Proofs intermittently disappear from folders**

_[!DNL Workfront] Proof_

When a user who is logged into [!DNL Workfront] Proof views a folder, the folder appears empty. If the user checks back later, the proofs are visible.

+++

+++**Maintenance Update on December 16, 2021**

**Clicking announcement in notifications list leads to blank page**

_Notifications_

When a user opens their list of [!UICONTROL notifications] from the notifications icon, then clicks on an announcement, they are taken to a blank page, and the announcement does not display.

**Summary panel shows "No selection" when task is selected**

_Tasks_

When a user opens a document summary in the [!UICONTROL documents] area of a project, then goes to the [!UICONTROL task] list, selects a task, and attempts to open the task summary, the task summary does not display, and the user sees the following message:

No selection. Select a document in the list to view details.

The message mentions documents even though the user is in the task list.

**Unassigned Work does not load**

_[!DNL Workload Balancer]_

When a user in the [!DNL Workload Balancer] creates a filter using the [!UICONTROL Assignment:Role ID] field, the Unassigned Work area does not load.

**Attaching template using "Customize and attach" option clears custom field values**

_Projects_

If a user attaches a template to a project using the "Customize and attach" option, and the project has a custom form attached to it already, the custom field values do not carry over and must be manually re-entered. This occurs even when the template includes the same custom form.

+++

+++**Maintenance Update (Hot Fix) on December 10, 2021**

**Whoops error when attaching template to existing project**

_Projects_

When a user attempts to attach a template to an existing project, the template does not attach, and the user sees the following error:

"Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it."

+++

+++**Maintenance Update on December 9, 2021**


**Collapsed left navigation panel expands on page load**

_Navigation_

When a user has set their left navigation to be collapsed, and then refreshed a page, the left navigation is expanded on the [!UICONTROL reloaded] page. The left navigation is also expanded if the user opens a page in a new tab.

**[!DNL Workload Balancer] shows 0 hours allocated**

_[!DNL Workload Balancer]_

When a user is viewing the [!DNL Workload Balancer] and has the "Show projected dates" setting enabled, any dates in the future display 0 hours allocated.

+++

+++**Maintenance Update on December 8, 2021**

**Approval resets when an update is made**

_Approvals_

If a user makes a decision on an approval using the object header, then immediately makes an update on the object, the approval icons reappear in the header and the approval decision is not saved.

**[!UICONTROL Cannot inline edit an assignment in a report]**

_Reports_

When a user attempts to inline edit an assignment in a report, the field value does not change, and the edit is not saved.


+++

+++**Maintenance Update on December 2, 2021**

**Extra slash added when manually typing URL**

_Requests_

When a user is filling out a request and manually begins typing in a URL, an extra slash is added at some point near the beginning of the URL. The user cannot delete the slash.

**Custom sections cannot be removed from left navigation panel**

_Navigation_

When a user attempts to remove a custom section from the left navigation panel by clicking the X next to the section, the section is not removed.

**Unassigned Work does not load**

_[!DNL Workload Balancer]_

When a user in the [!DNL Workload Balancer] creates a filter using the [!UICONTROL Assignment:Role ID] field, the Unassigned Work area does not load.

**Pages not loading in certain browsers**

_[!DNL Workfront]_

When a user is working in [!DNL Workfront], pages do not load and the user sees the following error message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This has been reported in

* Firefox
* Microsoft Edge

This error occurs randomly and may affect any area of Workfront.

+++


## Updates in November 2021

+++**Maintenance Update on November 18, 2021**

**[!DNL Workfront] for [!DNL Jira] "Invalid clientID or clientSecret" error on login**

_Workfront integrations_

Users have been logged out of the [!DNL Jira] for Workfront integration. When a user attempts to log into the [!DNL Workfront for Jira] integration, they cannot log in and they see the following error:

"Invalid clientID or clientSecret"

**Custom form attached to request does not update when new Queue Topic is selected**

_Requests_

When a user is creating a request and selects a Queue Topic that automatically attaches a custom form to the request, then selects a different Queue Topic, the custom form from the first Queue Topic remains attached to the request.

**Icons display incorrectly**

_[!DNL Workfront]_

Icon images are displaying incorrectly. This has been reported in many areas across Workfront.

**Tasks do not export to PDF when "Other Sizes" option is selected.**

_Tasks_

If a user attempts to export a task list to PDF, and selects the "Other Sizes" option, they can select a size and click [!UICONTROL Export], but the list does not export. There is no error message, and no other indication that the export was unsuccessful.

**Image indicator is not displaying in email notifications**

_Notifications_

When a user adds an image to an update, and an email notification is sent to the recipient of the update, the email does not include an indicator that there is an image in the update.

**Pages not loading in certain browsers**

_[!DNL Workfront]_

When a user is working in [!DNL Workfront], pages do not load and the user sees the following error message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This has been reported in

* Firefox
* Microsoft Edge

This error occurs randomly and may affect any area of Workfront.

+++

+++**Maintenance Update on November 11, 2021**

**Issue with document integrations, blank page on document upload popup from GDrive**

_Documents_

When a user attempts to add a new document to [!DNL Workfront] from Google Drive by using [!UICONTROL Add New] >[!UICONTROL From Google Drive], the upload popup screen remains blank.

**Cannot use more than one filter in the Workload Balancer**

_[!DNL Workload Balancer]_

When a user is attempting to use more than one filter in the Workload Balancer, they see the following issues:

* If the user selects two filters, only the bottom filter is applied.
* If the user selects more than two filters, no results display.

**"Project Folders" document header missing from [!UICONTROL project documents] area**

_Projects_

When a user is in a project and views the project's documents, the heading "Project Folders" is missing from the left navigation. The dropdown arrow is still there, and the user can select a folder.

**Columns on Kanban board are too wide and cannot be adjusted**

_Agile_

When a user views a Kanban board with several columns, the columns are too wide, and the user must scroll to view or move cards to the rightmost columns. The column widths are not adjustable, so the user cannot make the columns smaller so they are all visible on the screen at the same time.

**Improved interface for creating a new team**

_Teams_

Creating teams is now more intuitive with new visual cues. When you select the [!UICONTROL Switch Teams] icon on any team page, the [!UICONTROL Create New Team] link has an icon to indicate "new," and the link is separated from the rest of the list so it does not look like a team name. This interface is the same for agile and non-agile teams.

+++

+++**Maintenance Update on November 4, 2021**

**New tasks default to incorrect task constraint**

_Tasks_

When a user creates a new task using the "New Task" button, and the New Task Default Start Date option is set to "Today," the task constraint of the created task is set to "As soon as possible" rather than "Start no earlier than."

**Fields do not display on Agile story cards**

_Agile_

When a user views an Agile storyboard, the cards display only the description and status fields. Any other fields, including any custom fields, do not display.

**Cards return to original column before moving to new column**

_Agile_

When a user drags a card into a new column on the storyboard, the user can see the card being dragged. However, when the user drops the card into the new column, the card briefly appears in the original column before it displays in the new column.

**Values not available for custom field in filter**

_[!DNL Workload Balancer]_

When a user attempts to create a filter using a custom field, the value for that custom field do not display and cannot be entered into the filter.

**Pages not loading in Firefox browser**

_[!DNL Workfront]_

When a user is working in [!DNL Workfront] using a Firefox browser, pages do not load and the user sees the following error message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This error occurs randomly and may affect any area of Workfront.

**Date-related error when creating project from template.**

_Templates_

If a user creates a project from a template, and sets the schedule mode to Start Date, then selects a task constraint, when the user attempts to create the project, the project is not created and the user sees an error message based on the task constraint.

**[!UICONTROL Export Gantt Chart] dialog is unresponsive**

_Gantt Chart_

If a user in the new [!DNL Workfront] experience attempts to export the [!UICONTROL Gantt] Chart and selects the "What I See" option, the [!UICONTROL Gantt] Chart does not export and the dialog box is unresponsive. The user is unable to close or click out of the dialog box.

**Icons display incorrectly**

_[!DNL Workfront]_

Icon images are displaying incorrectly. This has been reported situations including, but not limited to:

* Images for Job Roles or Groups when sharing an object
* Left and right icons on calendar reports
* Sort icons on report columns

**Add checkboxes to Requests in the [!UICONTROL Submitted] section of the [!UICONTROL Requests] area**

_Requests_

We have added checkboxes to the left of the request names in the [!UICONTROL Submitted list] of the [!UICONTROL Requests] area. This makes it easier to select a request and view additional information.

**Custom Quarters are now supported in the Workload Balancer filters**

_[!DNL Workload Balancer]_

The filters in the [!DNL Workload Balancer] now support custom quarters.

**Updated filter operator for the Duration field in the Workload Balancer Filters**

_[!DNL Workload Balancer]_

We have updated the filter operators when filtering the Workload Balancer areas by Duration.

+++


## Updates in October 2021

+++**Maintenance Update on October 28, 2021**

**Home and My Work displaying blank page**

_Home / My Work_

When a user navigates to [!UICONTROL Home] or My Work, the page displays as blank.

**Cannot view or edit Topic Group details**

_Requests_

When a user attempts to view or edit the details of a Topic Group, the page that opens shows "Topic Group Detail" in the header but is otherwise blank

**Blank required radio buttons are filled out automatically**

_Requests_

When a user submits a request with a required radio button field, and the user has not selected a value for that field before submitting the request, the first value is automatically selected when the request is submitted.

+++

+++**Maintenance Update on October 21, 2021**

**Cannot add a filter in Workload Balancer**

_[!DNL Workload Balancer]_

When a user in the Workload Balancer attempts to add a filter, the Add filter panel opens, but the contents of the panel do not load, and the user cannot add the filter.

**Agile Scrum board not displaying stories**

_Agile_

When a user attempts to view the Scrum board in a team's iteration, the scrum board displays as blank.

**Scrum story board is blank when using filters**

_Agile_

When a user attempts to view a Scrum story board using any filter but the "All Team" filter, a blank screen displays. The user is unable to switch back to the "All Team" filter.

**Lists are visible only on a small area of the screen**

_Lists_

When a user attempts to view a list while using a Safari browser on a Mac using the Big Sur OS, the list appears only on a small area of the screen. The user can scroll through the list, but the area may be so small that the list is difficult or impossible to read.

**Blank required radio buttons are filled out automatically**

_Requests_

When a user submits a request with a required radio button field, and the user has not selected a value for that field before submitting the request, the first value is automatically selected when the request is submitted.

+++

+++**Maintenance Update (Hot Fix) on October 21, 2021**

**Home and My Work displaying blank page**

_Home / My Work_

When a user navigates to [!UICONTROL Home] or My Work, the page displays as blank.

+++

+++**Maintenance Update on October 20, 2021**

**Workload Balancer set as the default scheduling option**

_[!DNL Workload Balancer]_

If a user who has the [!UICONTROL Scheduler] set as the default goes to use it, they see that the [!DNL Workload] Balancer has been set as the default.

+++

+++**Maintenance Update (Hot Fix) on October 19, 2021**

**Unable to assign a request when creating it**

_Requests_

When a user in the new [!DNL Workfront] experience is creating a request and attempts to assign a user by typing their name in the [!UICONTROL Assignments] field, the field does not display the drop-down list, and the user cannot select the assignee's name.

**Scrum story board is blank when using filters**

_Agile_

When a user attempts to view a Scrum story board using any filter but the "All Team" filter, a blank screen displays. The user is unable to switch back to the "All Team" filter.

+++

+++**Maintenance Update on October 14, 2021**

**Templates that are shared system-wide are not visible**

_Templates_

When a user is creating a project and attempts to use a template that has been shared system-wide, the user cannot see the template in the list of available templates, and cannot use the template.

**Error when creating projects from templates**

_Templates_

When a user attempts to create a project from a template that include a custom form with a section visible only to administrators, the user cannot create the project and the following message displays:

"Category with primary key value(s) "xxxxxxxxxxxxxxxx" not found"

**Updated links for copying and moving tasks**

_Tasks_

The links for copying and moving tasks have been updated to "Copy to" and "Move to" both on the task page as well as in a task list.

**Remove limit to job role search when overriding billing rates for a project**

Job Roles

NOTE: This update is currently on the Preview environment and it will be on Production with the 22.1 Production release. For more information, see "22.1 Release overview."

Overriding billing rates for job roles in a project now searches for all job roles in the system.

Previously, [!DNL Workfront] searched for job roles in the first 2000 roles in alphabetical order.

+++

+++**Maintenance Update on October 7, 2021**

**[!UICONTROL In-app notifications disappear from] notifications center**

_Notifications_

When a user views the notification center, some previously visible notifications are no longer visible. In some cases, the notification may disappear before the user sees it.

**Announcements are not visible on the [!UICONTROL All Announcements] page**

_Notifications_

When a user opens the [!UICONTROL All Announcements] page from the Notifications area, there are no announcements visible in the following areas:

* Inbox
* Favorites
* Drafts
* Deleted

**Error when making assignment in the [!DNL Workload Balancer]**

_[!DNL Workload Balancer]_

When a user attempts to make an assignment from the [!DNL Workload balancer], the work is not assigned and the user sees the following error:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

+++


## Updates in September 2021

+++**Maintenance Update on September 30, 2021**

**Error when navigating quickly to or away from Home**

_Home_

When a user quickly navigates to or away from Home, the page does not load and the user sees the following error:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This can also occur when navigating to Home via a pin.

+++

+++**Maintenance Update on September 23, 2021**

**Access Denied error when viewing tickets submitted to [!DNL Workfront]**

_Issues_

When a user has submitted a ticket to [!DNL Workfront] and attempts to view the ticket, they see the following error:

"Access Denied: Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it."

**Business Case Summary shows incorrect values**

_Projects_

When a user views the [!UICONTROL Business Case] summary panel, the values displayed do not reflect the values in the individual [!UICONTROL Business] Case sections.

**Column headers do not line up with columns in lists**

_Setup_

When a users is in the [!UICONTROL Setup] area and views a list, such as Custom Forms or Access Levels, the column headers for that list do not line up with the columns in the list.

**Users without the proper sharing permissions can attach custom forms to objects**

_Custom Forms_

When a custom form in the new [!DNL Adobe Workfront] experience is set to be visible system-wide, all users are able to attach this custom form to an object. However, they should only be able to view the custom form and not be able to attach it to an object unless it has been shared specifically with them.

+++

+++**Maintenance Update on September 16, 2021**

**[!UICONTROL Cannot edit groups]**

_Groups_

When a user attempts to edit or delete a group, the group is not edited or deleted, and the user sees the following message:

"Let's try that again. Group with primary key value(s) "\<Group's ID\>" not found"

**Portfolio Optimizer not displaying projects**

_Portfolios_

When a user attempts to view projects in the [!UICONTROL Portfolio Optimizer], the project list does not display and the user is therefore unable to interact with the projects.

+++

+++**Maintenance Update (Hot Fix) on September 10, 2021**

**Date and Time marked as UTC when editing inline**

_Lists_

When a user edits a date or time inline (in a list of objects), the date and time are marked as UTC. The date and time are not set in UTC in Workfront. This issue affects only the display, not the actual data.

**Text color not displaying correctly when conditional formatting is applied**

_Reports_

When a user views a report that has conditional formatting that alters the text color, the text color displays as unaltered.

+++

+++**Maintenance Update on September 9, 2021**

**Issues are not displaying issue details**

_Home_

When a user in the new [!DNL Adobe Workfront] experience selects an issue from the [!UICONTROL Work List], the [!UICONTROL preview] in the right panel displays certain fields as having no values entered. However, if you navigate to the issue and view the Issue Details, these fields have values entered.

**Users need Contribute permissions to view the [!UICONTROL Approvals] section in the new Workfront Experience**

_Approvals_

Users need Contribute permissions on an object to view the [!UICONTROL Approvals] section in the new [!DNL Workfront] Experience. They should need only View permissions to view the [!UICONTROL Approvals] tab when there is an approval process on the object.

**Whoops error when using filters**

_Lists_

When a user attempts to use one of the following filters:

* All Projects
* Projects I'm On
* My Current Tasks

the list goes blank and the user sees the following error:

"Let's try that again."

**[!UICONTROL Tasks] section goes blank when editing inline**

_Templates_

When a user attempts to inline edit [!UICONTROL tasks] in a template using a view that includes the "Assign To: Name" field, and the assignment contains a user, the tasks section goes blank and the user is unable to edit the template tasks.

**Cannot export Portfolio Optimizer**

_Portfolios_

When a user attempts to export the [!DNL Portfolio Optimizer] and clicks any of the export options, the Portfolio Optimizer does not export.

**Notifications are not being sent for replies**

_Notifications_

When a user replies to an update in [!DNL Workfront], other users in the comment thread are not receiving notifications.

**Changes to custom data cause lag**

_Custom fields_

When a user modifies custom data that triggers changes to other displayed data, the changes load slowly.

**Grouping "Collapse or Expand All" icon does not display**

_Reporting_

The "Collapse or Expand All" icon does not display in the header of a list or report when groupings are applied to the list or report.

**Check and Cancel options not visible when changing task allocations**

_[!DNL Workload Balancer]_

When a user attempts to change the task allocation for a task, and the time frame of that task extends to or beyond the edge of the visible page, the [!UICONTROL Check] and [!UICONTROL Cancel] buttons are not visible, and the user cannot save or cancel the allocation changes.

**Adding a custom field to [!UICONTROL Home] causes missing field data**

_Home_

When a custom field is added to [!UICONTROL Home], other fields start missing data and showing incorrectly.

**Cannot view linked items when logged in as another user**

_Integrations_

If an administrator attempted to view linked items from an external provider while logged in as another user, they were not able to open the linked folders and could not view the items.

+++

+++**Maintenance Update on September 2, 2021**

**Cannot pin custom dashboard**

_Dashboards_

When a user attempts to pin a custom dashboard, the dashboard does not pin and the user sees the following error:

"Something went wrong while pinning. Please contact [!DNL Workfront] so we can fix this."

**Proof print summary is blank**

_Proof_

When a user opens the print summary to print a proof, the header appears but the summary itself is blank.

+++


## Updates in August 2021

+++**Maintenance Update on August 26, 2021**

**In Safari there is a dark grey background on column headers' text**

_Lists_

In the Safari browser, there is a dark grey background on column headers, highlighting the text. This is not an issue with any other supported browsers.

**Unexpected error when setting predecessors**

_Tasks_

When a user attempts to set a task as a predecessor using [!UICONTROL inline edit], the predecessor is not set and the user sees the following message:

"An unexpected error happened"

+++

+++**Maintenance Update on August 19, 2021**

**Saved filters missing after selecting a filter that displays no issues**

_Lists_

Saved filters are missing in a list of issues after selecting a filter that displays no results.

**Issues are not displaying issue details**

_[!UICONTROL Home] summary_

When a user in [!DNL Adobe Workfront Classic] selects an issue from the [!UICONTROL Work List], the [!UICONTROL preview] in the right panel displays certain fields as having no values entered. However, if you navigate to the issue and view the Issue Details, these fields have values entered.

+++

+++**Maintenance Update on August 12, 2021**

**Cannot customize agile view on project**

_Agile_

When a user attempts to customize a previously existing [!DNL agile] view on a project, the window closes and the user is unable to edit the view.

**Name doesn't change on new document versions**

_Documents_

When a user uploads a new version of a document, the name of the document doesn't update to match the newest version's name.

**Predecessor icon does not turn green when predecessor is complete.**

_Tasks_

When a task has a [!UICONTROL predecessor] task, and that predecessor task is complete, the predecessor icon in the dependent task does not turn green.

When a custom form in the new [!DNL Adobe Workfront] experience is set to be visible system-wide, all users are able to attach this custom form to an object. However, they should only be able to view the custom form and not be able to attach it to an object unless it has been shared specifically with them.

+++

+++**Maintenance Update (Hot Fix) on August 6, 2021**

**Unable to select calendars in Outlook Calendar settings**

_Home_

When a user in the new [!DNL Workfront] experience is viewing their [!DNL Outlook] Calendar in home, and opens the settings, the checkboxes to select calendars are missing. If the user clicks on where the checkbox would be, the calendar responds as if the checkbox was there.

**Unable to reauthorize or verify connection to Webdam**

_Fusion_

Adobe Workfront Fusion users with scenarios connecting to Webdam should be aware that Webdam connections require manual reauthentication every 14 days. The Webdam API doesn't currently support automatic reauthorization.

+++

+++**Maintenance Update on August 5, 2021**

**Unable to interact with document in Summary panel or More menu**

_Documents_

When a user in the new [!DNL Workfront] experience is viewing a document and attempts to make a selection in the [!UICONTROL Summary panel] or the [!UICONTROL More] menu, the document is deselected, causing the [!UICONTROL Summary panel] or [!UICONTROL More] menu to go blank.

**New Request button missing**

_Requests_

When a user in the new [!DNL Adobe Workfront] experience goes to the [!UICONTROL Requests] page, the [!UICONTROL New Request] button does not display and they are unable to submit a request.

**Users without the proper sharing permissions can attach custom forms to objects**

_Custom Forms_

When a custom form in the new [!DNL Adobe Workfront] experience is set to be visible system-wide, all users are able to attach this custom form to an object. However, they should only be able to view the custom form and not be able to attach it to an object unless it has been shared specifically with them.

**Can not change proof settings when creating a new proof**

_Proof_

When a user creates a new proof and attempts to change settings, the setting reverts to a previous setting.

**Story Board not loading properly**

_Agile_

When a user in the new [!DNL Adobe Workfront] experience navigates to a Story Board, it can take up to 10 seconds to load the board. The delay in loading is due to the system loading all cards when it should only be loading 50 cards at a time.

+++


## Updates in July 2021

+++**Maintenance Update (Hot Fix) on July 29, 2021**

**Unable to upload new proof or new proof version**

_Proof_

When a user attempts to upload a new proof or a new version of a proof in the classic [!DNL Workfront] experience, the new proof or new version page is blank, and the user is unable to upload the proof or version.

+++

+++**Maintenance Update on July 29, 2021**

**[!UICONTROL Proof Activity] and [!UICONTROL Proof Viewer] Settings pages always available**

_Proof_

The [!UICONTROL Proof Activity] and Proof Viewer Settings pages are now always visible, even if the user doesn’t have access to update those pages.

Previously, when a user with a custom Proof Permission Profile navigated to a document, the [!UICONTROL Proof Activity] and [!UICONTROL Proof Viewer Settings] pages on the left were not always visible.

**Error message when using Percentage option for Allocated hours**

_[!DNL Workload Balancer]_

When a user selects the [!UICONTROL Percentage] option for Allocated hours, and there is work listed in the [!UICONTROL Unassigned work] section, the user sees the following error:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

+++

+++**Maintenance Update on July 22, 2021**

**New proof version names being cut off**

_Proof_

When a user in [!DNL Adobe Workfront Classic] uploads a new version of a proof that contains a period in the filename, the filename is cut off at the end.

+++

+++**Maintenance Update (Hot Fix) on July 19, 2021**

**Error while trying to navigate to projects, timesheets, tasks, or programs**

In the new [!DNL Adobe Workfront] experience, when a user tries to navigate to projects, timesheets, tasks, or programs, they see the error message "Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it."

+++

+++**Maintenance Update on July 15, 2021**

**Default priority on new requests is incorrect**

_Requests_

When a user in the new [!DNL Adobe Workfront] experience creates a request, the request does not respect the default priority set in Project Preferences and they are unable to adjust the priority before submitting the request.

**[!UICONTROL Go to proof link does not direct to comment]**

_Email Notifications_

When a user receives an email notification for a proof comment and they click [!UICONTROL Go to proof], they are directed to the wrong comment in the proof or they are not directed to any comment at all.

**Rich Text field values not carried over after converting an issue to a task**

_Custom Forms_

When a user converts an issue to a task and the issue has an attached custom form with a value entered in a text field with Rich Text formatting, the value in the text field does not carry over after conversion.

**Custom field values are changing after selection**

_Proof_

When a user in the new [!DNL Adobe Workfront] experience is creating a new proof and they enter a value in some custom fields on a proof, the value of some previous fields revert to the default values instead of the value the user entered.

**Assign to [!UICONTROL typeahead] does not work**

_Home_

When a user in [!DNL Adobe Workfront Classic] creates a project, task, or request from the Home area, the [!UICONTROL Assign to typeahead] field does not populate user names.

**Hours rounding incorrectly**

_Timesheets_

When a user in the new [!DNL Adobe Workfront] experience navigates to [!UICONTROL Timesheets] >[!UICONTROL All Timesheets], they see that the total hours numbers for some timesheets are rounding to one decimal place instead of in .25 increments, but the total hours display correctly in the individual timesheet. For example, in the All Timesheets area, a timesheet shows 44.8 total hours, but when opening the timesheet, it shows 44.75 total hours.

**Unable to delegate approvals**

_Home_

When a user in [!DNL Adobe Workfront Classic] clicks [!UICONTROL Delegate My Approvals] in the [!UICONTROL Home] area and they start typing the name of the user they're trying to delegate to, no results display in the [!UICONTROL typeahead] list and they can't select a user.

**[!UICONTROL Gantt] Chart view is not available for Task reports**

_Reports_

NOTE: This is also affecting Project reports.

When a user in the new [!DNL Adobe Workfront] experience opens a Task report, the option to select a [!UICONTROL Gantt] Chart view is missing from the report toolbar. If the [!UICONTROL Gantt] Chart view is selected to display by default in the report, a list format displays instead.

**Clicking [!UICONTROL See More on report] doesn't load anything**

_Dashboards_

When a user in the new [!DNL Adobe Workfront] experience is viewing a report on a dashboard and they click the [!UICONTROL See More] button, nothing happens and they are unable to view all items in the report.

+++

+++**[!DNL Adobe Workfront] Fusion Maintenance Update on July 1, 2021**

**Fusion: Copying modules does not work**

_Adobe Workfront Fusion_

When a user selects multiple modules and attempts to copy and paste them, the modules do not paste.

+++

+++**Maintenance Update on July 1, 2021**

**Color set for cards not respected**

_Kanban_

When a user in the new [!DNL Adobe Workfront] experience sets specific card colors in the team settings, those colors are not reflected on the Kanban cards.

**Unable to paste text in custom message field**

_[!DNL Workfront] Proof_

When a user is creating a new proof in the Web Proofing Viewer and they attempt to paste text into the Message field in the Email notification section, they are unable to paste the text. This only seems to happen when the text has paragraph formatting and there is a paragraph break.

**Requests are submitted with blank required fields**

_Requests_

When a user makes a request and submits it, information in required fields is not submitted with the request.

**New Request button missing**

_Requests_

When a user in the new [!DNL Adobe Workfront] experience goes to the [!UICONTROL Requests] page, the [!UICONTROL New Request] button does not display and they are unable to submit a request.

**Error when expanding a custom form**

_Projects_

When a user in the new [!DNL Adobe Workfront] experience attempts to expand a custom form attached to a project, they are unable to open the custom form and see the error message "An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page." Refreshing the page does not resolve the issue.

**[!DNL Adobe Workfront] branding now appears on announcement center emails**

Emails

As the [!DNL Adobe Workfront] branding is rolled out across the application, the following updates have been made to announcement center emails:

* The [!DNL Adobe Workfront] lion was added to the main content area.
* The [!DNL Adobe Workfront] logo was added to the footer.

In the future, this branding will be shown on additional types of emails from Workfront.

+++


## Updates in June 2021

+++**Maintenance Update on June 24, 2021**

**Can't edit a team**

_Agile_

When a user in the new [!DNL Adobe Workfront] experience clicks [!UICONTROL Edit] to open the [!DNL Edit] Team page for an Agile team, the page loads initially, then the settings disappear and it goes blank.

**Data removed from submitted request**

_Requests_

When a user in the new [!DNL Adobe Workfront] experience fills out a request, the submitted request is missing the entered values for some custom fields, sometimes including fields that are required.

**Columns are not displaying**

_Kanban_

When a user in the new [!DNL Adobe Workfront] experience adds a custom-made [!UICONTROL Additional Fields] column to a Kanban Board, all column headers stop displaying on the board.

+++

+++**[!DNL Adobe Workfront] Fusion Maintenance Update on June 23, 2021**

**Removed broken link in notification emails**

_Adobe Workfront Fusion_

We've removed the link to notification settings from [!DNL Adobe Workfront] Fusion notification emails.
For information on changing notification settings, see [!DNL Adobe Workfront] Fusion organizations and teams.

+++

+++**Maintenance Update on June 17, 2021**

**[!UICONTROL Gantt] Chart view is not available for Task report**

_Reports_

When a user in the new [!DNL Adobe Workfront] experience opens a Task report, the option to select a [!UICONTROL Gantt] Chart view is missing from the report toolbar. If the [!UICONTROL Gantt] Chart view is selected to display by default in the report, a list format displays instead.

**Character limit error not occurring on request submissions**

_Requests_

When a user in the new [!DNL Adobe Workfront] experience attempts to submit a request and they exceed the character limit for a field, they are unable to submit the request and no error message displays. In [!DNL Adobe Workfront Classic], the user sees the warning "[number] characters over" and when they attempt to submit the request, they see the error message "Please check the following: Please enter no more than 2000 characters (you entered [number] characters)."

+++

+++**Maintenance Update on June 10, 2021**

**Reordered template tasks do not move**

_Templates_

When a user in the new [!DNL Adobe Workfront] experience drags a template task to a new location in a list, the number of the template task updates, but it does not reorder.

**Child tasks not selected with parent tasks**

_Templates_

When a user selects a parent task on a project created from a template, the children tasks are not selected automatically.

**Inline editing milestones on a task list displays all milestones**

_Projects_

When a project has a milestone path added to it and a user in the new [!DNL Adobe Workfront] experience inline edits the [!UICONTROL Milestone: Name] column on that task list, all milestone paths appear in the drop-down menu, rather than just the milestone paths that have been attached to that project.

+++

+++**Maintenance Update on June 3, 2021**

**Prompt causes page to shak**&#x200B;e

_Reports_

When a user in the new [!DNL Adobe Workfront] experience runs a report with a prompt, the columns in the report rapidly move left to right.

**Some phrases on the New proof page are not translating properly**

_Proof_

When a user navigates to the [!UICONTROL New proof creation] page in [!DNL Workfront] Proof and the content is being translated to a language other than English, some phrases still display in English.

**Deactivated and Deleted labels added to users Workfront Proof**

_Proof_

Deactivated/Deleted user labels have been added to the following areas in [!DNL Workfront] Proof:

* Proof details page
* Proofing views
* Proofing viewer
* Proofing workflows
* Print comments page
* User page

+++


## Updates in May 2021

+++**Maintenance Update on May 27, 2021**

**Commit Date calendar displays for updates**

_Tasks_

When a user in the new [!DNL Adobe Workfront] experience is entering an update on a task, the [!UICONTROL Commit Date] calendar displays without the user selecting the [!UICONTROL Commit Date] field.

**More menu missing from filters, views, and groupings**

_Lists_

When a user in the new [!DNL Adobe Workfront] experience views the filters, views, or groupings for a list, the [!UICONTROL More] menu icon is missing, which prevents them from sharing or—if they have access—removing filters, views, or groupings.

**Copying and Pasting a project Reference Number adds "This"**

_Projects_

When a user in the new [!DNL Workfront] experience navigates to a project, copies the Reference Number from the [!UICONTROL Overview] area, then pastes it, the word "This" is added to the end of the number.

**Daily Digest emails are sending when they are disabled**

_Email Notifications_

Some users are receiving Daily Digest email notifications when they have not been enabled in their user settings.

**The object no longer exists error**

_Objects_

When a user in the new [!DNL Workfront] experience attempts to open certain objects, they see the error message "The \<object\> no longer exists: You may have mistyped the web address. Double check it and try entering the address again." The object link still appears in lists, recents, favorites, search results, etc., but they are unable to access it and it does not appear in the Recycle Bin with deleted objects.



+++

+++**Maintenance Update on May 20, 2021**

**Proof options are missing**

_Proof_

When a user uploads another version of a proof in [!DNL Workfront], the Open Proof and Proofing Workflow links are missing, making it seem like it is a document instead of a proof. When theses links are missing, the label [!UICONTROL Pending] also displays and other users are unable to generate the proof while it is in this [!UICONTROL Pending] status.

**Users not receiving scheduled report deliveries**

_Reports_

When some reports are scheduled for report delivery, the users sometimes don't receive the reports.

**Unable to remove access for Layout Template**

_Dashboards_

When a user opens [!UICONTROL Sharing options] for a dashboard to remove access for a Layout Template, no Delete icon appears next to the Layout Template and they are unable to remove access.

+++

+++**Workfront Fusion Maintenance Update on May 17, 2021**

**Organization Dashboard now correctly displays the number of active scenarios**

_Workfront Fusion_

The Organization Dashboard previously showed a blank field instead of the number of scenarios that are being utilized.

**Data store browsing now shows column labels**

_Workfront Fusion_

Data structures that utilized column labels previously displayed the column name in the [!UICONTROL data store browsing] view.  Now, the column label displays.  If no label is identified for the column, the column name is displayed.

**Scenario initialization error no longer affects webhook data**

_Workfront Fusion_

Previously, a webhook-initiated scenario (including those that are using a real time events to trigger) that encountered an error during scenario initialization would potentially result in losing access to that webhook data.  Now, if an error occurs during scenario initialization (such as not being able to verify a connection), the webhook data will be maintained in the webhook queue and the execution is automatically retried.  After three unsuccessful attempts, the scenario is deactivated and the information will still remain in the queue.

**Records in webhook queues are now processed in smaller batches**

_Workfront Fusion_

Previously, if a user activated an inactive scenario that had an associated webhook queue of many records, Workfront Fusion would attempt to process the entire queue in a single execution (albeit multiple cycles).  Depending on the amount of records processed, this could sometimes cause the single execution to exceed the maximum amount of execution time (40 minutes).  Now, when you activate an inactive scenario that has an associated webhook queue of records, Workfront Fusion will process up to the maximum number of records identified in a single execution (usually 2 records per execution).

**Data stores now display "0" values correctly**

_Workfront Fusion_

Previously, data store values of 0 were displayed as empty. <...>

+++

+++**Maintenance Update on May 13, 2021**

**Drop-down calendar appears behind the [!UICONTROL Unassigned Work] header**

_[!DNL Workload Balancer]_

When a user navigates to the [!DNL Workload Balancer] in [!DNL Workfront Classic], the top of the datepicker is hidden behind the Unassigned Work header, which prevents the user from navigating to different months.

**Unable to paste text in custom message field**

_[!DNL Workfront] Proof_

Note: This issue seems to be affecting only the Google Chrome web browser at this time.

When a user is creating a new proof in [!DNL Workfront] Proof and they attempt to paste text from an email into the Message field in the [!UICONTROL Email notification] section, they are unable to paste the text.

**Unsupported fields are displaying in the [!UICONTROL builder]**

_Custom Forms_

When a user is building a Custom Form and they attempt to create a calculated field using a dynamic field—such as Number of Open Risks—the calculation box highlights red and does not allow you to save your changes. Dynamic fields should not display in the picker for calculated fields.

**Preview for tasks in Work List won't load**

_Home_

When a user in the new [!DNL Workfront] experience is assigned to a Layout Template that includes custom fields on Home, the page is unresponsive and won't load tasks from the [!UICONTROL Work List] if the users selects them.

**[!UICONTROL Objects in Work List not] loading in Home**

_Home_

When a user clicks on an object in the Home Work List, the object's header appears in the right panel, but the details of the object do not appear. Eventually the user sees the message "Pages Unresponsive."

**Rich text field issues in [!DNL Microsoft] Outlook**

_Workfront Integrations_

When a user is updating a rich text field with the [!DNL Workfront for Outlook] integration, they are unable to:

* Backspace
* Copy text
* Paste text
* Submit a request when all fields are filled out

+++

+++**Maintenance Update on May 6, 2021**

**Currency field not working as expected**

_Lists_

When a user tries to inline edit the Currency field in a list, they are unable to save changes due to the following issues:

* Task and Issue lists not allowing input of currency symbols
* Lists not allowing input of currency abbreviations when using a locale other than English
* Subtask and Issue lists allowing only the currency abbreviation of USD, regardless of the set project currency

**Name not updating to match new proof name**

_Documents_

When a user creates a new version of a proof and they update the proof name, the document object in [!DNL Workfront] retains the original name instead of matching the new proof name.

**[!UICONTROL Business Case] buttons are not working when custom forms are attached**

_Projects_

When a project in the new [!DNL Workfront] experience is created from a project template and there is a custom form attached, users are unable to submit, reject, or approve a business case.

**Archived proofs displaying on lists and reports**

_Proofs_

When a user views their work list in [!UICONTROL Home] or [!UICONTROL My Work], proofs that have already been archived appear in the list. Archived proofs also appear on reports and dashboards.

**Project created from template have incorrect access settings**

_Projects_

When a user creates a project from a template, the template's access settings do not carry over to the new created project.

**[!UICONTROL Objects in Work List not] loading in Home**

_Home_

When a user clicks on an object in the Home Work List, the object's header appears in the right panel, but the details of the object do not appear. Eventually the user sees the message "Pages Unresponsive."

+++


## Updates in April 2021

+++**Maintenance Update on April 29, 2021**

**[!DNL SharePoint] integration authenticates using credentials from a separate integration**

_Workfront Integrations_

When a user has more than one [!DNL SharePoint] integration, one [!DNL SharePoint] authentication attempts to authenticate using the credentials of another SharePoint integration.

**Cannot upload or export files from Adobe products**

_Workfront Integrations_

When a user attempts to upload or export files using the [!DNL Workfront for Adobe Creative Cloud] integration, they see the error message "Cannot read property 'stages' of undefined" and are unable to upload or export the files.

**Files are not visible in Internet Explorer**

_Documents_

When a user with an Internet Explorer browser navigates to the [!UICONTROL Documents] area of an object, the [!UICONTROL Documents] screen is blank and does not load the files. For some users, the screen does load some files, but the number of files that appear do not match the number displayed next to the Documents section.

+++

+++**Maintenance Update on April 22, 2021**

**Tasks added in the wrong order**

_Templates_

When a user adds a task to a template, the task does not receive the task number they expect and the task is added in the wrong place.

**Proofs are now combined into a single email**

_Proofs_

Workfront now sends one email for combined proofs rather than sending an email for each file included.
+++

+++**Workfront Fusion Maintenance Update on April 15, 2021**

**"Scenario rejected" error when running a scenario**

_Workfront Fusion_

When a user attempts to run a scenario, the scenario does not execute and the user receives the message "Scenario rejected."

+++

+++**Maintenance Update on April 15, 2021**

**[!DNL Workload Balancer] displays incorrect planned hours**

_[!DNL Workload Balancer]_

When a user views a task's planned hours in the [!DNL Workload Balancer] the value of the planned hours does not match the planned hours assigned to the task.

**Top navigation bar is not visible in [!DNL Workfront] Proof**

_[!DNL Workfront] Proof_

When a user navigates to any [!DNL Workfront] Proof page other than the Dashboard page, the top navigation bar disappears. The user is unable to access the functionality in the navigation bar, such as their account settings or profile.

**Custom forms enhancement**

_Custom forms_

For a better experience when you fill out a custom form, we have improved the way the long custom field labels display. When there is enough horizontal space to show them in their entirety, these labels are no longer truncated.

+++

+++**Maintenance Update on April 8, 2021**

**Cannot create proofs in Adobe Creative Cloud integration**

_Workfront Integrations_

When a user attempts to create a proof directly from the [!DNL Adobe Creative Cloud], the proof is not generated.

+++

+++**Maintenance Update on April 1, 2021**

**Issues viewing summary panel in Chrome**

_Summary_

When a user opens the summary panel while using the Chrome browser, the summary panel UI does not behave as expected. The user is unable to scroll, the icons may disappear, and the content may overlap other content.

**Teams area in Setup not displaying all teams**

_Setup_

When an admin goes to the [!UICONTROL Teams] area of Setup, they can view only teams that they created. Teams created by other admins are not visible.

**Cannot add updates to project in Pending Approval status**

_Projects_

If a user attempts to add an update to a project in [!UICONTROL Pending Approval] status, and they are not the user that is assigned to approve the project, the update is not added and they see the following notice:

A project with a 'Pending Approval' status cannot be edited. You can modify the project by changing the status.

+++


## Updates in March 2021

+++**Maintenance Update on March 26, 2021**

**Buttons in a business case display incorrectly**

_Projects_

When a user is viewing a business case, and the window is in full screen mode, the [!UICONTROL Save] and [!UICONTROL Cancel] buttons appear near the middle of the screen, overlapping business case elements.

**[!UICONTROL Cannot change sorting of a report]**

_Reports_

When a user attempts to change the sorting of a report in the new [!DNL Workfront] experience, the sorting does not change from the sorting selected when the report was created.

**Sharing disabled on new proofs**

_Proof_

When a user who has Public Sharing enabled in their default proof settings creates a proof, the proof is created with sharing disabled. Other users cannot see the Share button or share the proof.

**"Proof failed to generate" error when creating proof**

_Proof_

When a user attempts to create a proof, the proof is not created, and the user sees the following error message:

"Proof failed to generate -- internal error"

+++

+++**Workfront Fusion Maintenance Update on March 25, 2021**

**Removed redundant collection or reference field from mapping panel**

_[!DNL Workfront] Fusion 2.0_

When a user uses a term from the [!DNL Workfront] API to select a collection or reference field to include in the output of a [!DNL Workfront] module, the output for that module shows that field with a colon (such as owner:name), and also in the attributes (name is a field under owner). The field labeled with a colon does not contain data, and provides incorrect data if mapped to a module later in the scenario.

+++

+++**Workfront Fusion Maintenance Update on March 18, 2021**

**Project template settings now apply to projects created through [!DNL Workfront Fusion] 2.0**

_[!DNL Workfront] Fusion 2.0_

When creating a project from a template using the [!DNL Workfront] Fusion 2.0, the template settings are applied to the new project. This behavior is the same when creating a project from a template in the Workfront application.

+++

+++**Maintenance Update on March 18, 2021**

**Project template settings now apply to projects created through the API**

_[!DNL Workfront] API_

When creating a project from a template using the [!DNL Workfront] API, the template settings are applied to the new project. This behavior is the same when creating a project from a template in the [!DNL Workfront] application.

+++

+++**Maintenance Update (Hot Fix) on March 15, 2021**

**Shared component not functioning as expected**

_Proof_

If standalone Proof accounts are moved to a shared component, the following functionality may occur when a user adds a new version of a proof or document:

* The user is unable to delete the user Studio Proof.
* The default message does not appear on the new version.

**Public link sharing not enabled on new version of a proof**

_Documents_

When a user enables public link sharing on a proof and then uploads a new version of the proof, public link sharing is not automatically enabled on the new version of the proof.

**Approve, Changes, Reject buttons missing from proof**

_Proof_

When a user views a proof in the Proof Viewer, the [!UICONTROL Approve], [!UICONTROL Changes], and [!UICONTROL Reject] buttons are missing from the top of the screen.

**[!UICONTROL Cannot change sorting of a report]**

_Reports_

When a user attempts to change the sorting of a report in the new [!DNL Workfront] experience, the sorting does not change from the sorting selected when the report was created.

**Custom message on proof not carrying over to new version**

_Proof_

When a user attaches a custom message to a proof, and then uploads a new version of that proof, the custom message does not appear on the new proof.

**User list does not display**

_Lists_

When a user attempts to view a User list, and the view includes the "Status Icons" column, the list does not display.

**"Notify recipients about this proof" option disabled regardless of workflow settings**

_Proof_

When a user creates a new proof, and does not manually turn on the "Notify recipients about this proof" option, the intended recipient is not notified. This is true even if the option is enabled in workflow settings.

**Unable to change time frame**

_Enhanced Analytics_

When a user views Enhanced analytics and clicks on the calendar to adjust the date range, the dates do not change.

**Cannot download publicly shared document**

_Documents_

When a user clicks on a shared link to download a document, the document does not download, and the user sees an error from the browser saying that the page does not exist.

+++

+++**Maintenance Update on March 11, 2021**

**Section of custom form not exporting for non-admins**

_Custom Forms_

If a custom form attached to an object has a section break requiring anything above "View" access needed to view the contents of the section, the section's contents cannot be exported by anyone other than an Admin.

**Downloaded document has incorrect name**

_Proof_

When a users downloads a document from the Proof viewer, the document's has the name of a previous version of the document, not the version that was downloaded.

+++

+++**Maintenance Update on March 4, 2021**

**Error when accessing Layout Template**

_Layout Templates_

When a user enrolled in the new [!DNL Workfront] experience switches to the Classic experience and attempts to access a Classic layout template, they see the error "That Page does not exist."

**Cannot edit filters in the Workload Balancer**

_[!DNL Workload Balancer]_

When a user attempts to edit a filter in the [!DNL Workload Balancer], the filter builder does not open.

**"See All Notifications" link in email notification redirects to incorrect page**

_Email Notifications_

When a user clicks on the "See All Notifications" link in an email notification, they are redirected to a page with the following message:

"The User no longer exists. You may have mistyped the web address. Double check it and try entering the address again."

**User is not directed to the proof comment they are tagged in**

_Email Notifications_

When a user is tagged in a proof comment and they click the [!UICONTROL Go To Proof] link in an email notification, they are directed to the proof but not to the specific comment. If the user is in [!DNL Workfront Classic], they are directed to the document Details page instead of the comment in the proof.

**Users added to [!DNL Workfront] stage receiving email notifications**

_Proof_

When a user who is not on the workflow opens a proof from [!DNL Workfront], the system automatically creates a stage, adds this user to the proof, and sends a New Proof email notification.

**Document summary panel darkens, making actions unavailable**

_Documents_

When a user is on a document page and hovers over the document summary panel, the panel darkens and may show other buttons. The user cannot click on the actions in the summary panel.

**Update stream performance changes**

_Update Stream_

We’ve reduced the number of user updates displayed in the [!UICONTROL Updates] tab from 50 to 25 at a time to improve performance.Update Stream

+++

+++**Maintenance Update (Hot Fix) on March 1, 2021**

**New proof emails are not being sent**

_Proof_

NOTE: This issue was fixed in the new [!DNL Workfront] experience on February 26, 2021.
It was fixed in the Classic experience on March 1, 2021.

When a user creates a new proof and enables the option [!UICONTROL Notify recipients about this proof], there is no email sent to notify the recipient.

+++


## Updates in February 2021

+++**Maintenance Update on February 25, 2021**

**Scheduling tool won't load in any area**

_Resource Management_

When a user with an apostrophe in their username tries to access the Scheduling tool in [!DNL Workfront Classic], the page is blank and the tool never loads.

**Name doesn't change on new proof versions**

_Documents_

When a user in the new [!DNL Workfront] experience uploads a new version of a document with a different name, the name doesn't update to match the newest version's name.

**Document Share error when deleting projects**

_Projects_

When a System administrator user has a access to a project that has been copied and they try to delete it or delete a document in the project, they are unable to delete the object and they see the error "Document Share with primary key value(s) not found."

**User report is not applying all filters**

_Reports_

When a user in the new [!DNL Workfront] experience creates a User report with a filter rule that includes the [!UICONTROL Top Parent ID] field, any other filter rules in the report are not being applied.

**Calculated fields not recalculating after edits**

_Custom Forms_

When a user in the new [!DNL Workfront] experience edits and saves a Custom Form that contains calculated fields, these fields do not update.

**Documents deleting when custom form is deleted**

_Custom Forms_

When a user in the new [!DNL Workfront] experience deletes a Documents custom form that is attached to documents, those documents are deleted as well.
Custom Forms

+++

+++**Maintenance Update on February 18, 2021**

**Unnecessary checkbox removed from Requests area**

_Requests_

We have removed the checkbox to the left of the request names in the Submitted list of the [!UICONTROL Requests] area. This checkbox was not connected with any functionality, so we removed it to eliminate a confusing experience.

**[!UICONTROL Unable to access documents from links]**

_Documents_

When a user in the new [!DNL Workfront] experience clicks some document links, they are unable to access the document and they see the error message "The Document no longer exists: You may have mistyped the web address. Double check it and try entering the address again." This same error occurs with the [!UICONTROL View Details] link in proof email notifications.

+++

+++**Workfront Fusion Maintenance Update on February 16, 2021**

**[!DNL Workfront Fusion] 2.0 shows inaccurate time zones**

_Scenarios_

This update fixed an issue where Fusion 2.0 was displaying user time zones inaccurately. Users can now see their time zone displayed under input fields for dates.

+++

+++**Maintenance Update on February 11, 2021**

**Proofs aren't uploading to selected folder**

_Proof_

When a user opens a folder and adds a new proof, the proof uploads to the [!UICONTROL general Documents] area of the object instead of within the folder.

**Too many pinned pages causes Top Navigation to disappear**

_Navigation_

When a user has more than 60 pinned pages, the Top Navigation stops displaying, preventing the user from accessing Search, the Main Menu, Notifications, and more.

**User cannot type text into rich text field**

_Lists_

When a user attempts to inline-edit a rich text field, they can only type a single character.

+++

+++**Maintenance Update on February 4, 2021**

**Exported report shows [!DNL Workfront] Classic branding**

_Reports_

When a user in the new Workfront experience exports a report, the logo that displays in the exported report matches the Workfront Classic settings found under Setup > System > Branding.

+++


## Updates in January 2021

+++**Maintenance Update on January 28, 2021**

**Comments not displaying "on behalf of"**

_Updates_

When a [!DNL Workfront] administrator logs in as another user and they reply to a comment in the [!UICONTROL Updates] area of an object, the text "on behalf of" does not display before the username.

**Unable to attach a document**

_Requests_

When a user in the new [!DNL Workfront] experience tries to add a document to a new request from an external document provider, the Documents list does not load, which prevents the user from selecting the document and completing the request.

**Screen width expanding to the right, causing navigation issues**

_Home Calendar_

When a user in the new [!DNL Workfront] experience opens the Home Calendar and they have items due on some weeks, the screen expands to the right, preventing them from viewing the full week at once. If the user selects an item to open the Details panel in this state and they want to view details for another item, they need to scroll to the left, which closes the Details panel.

**Single-use approval process label corrected**

_Projects_

When using a single-use approval process for a project in the new [!DNL Workfront] experience, it now displays as “Single-use approval process” instead of “\<Custom\>” in the [!UICONTROL Edit Project] box. This is not yet available for tasks and issues.

**Improved look and feel for custom forms**

_Projects_

We have improved the look and feel of working with custom forms in the new [!DNL Workfront] experience for projects.

**API functionality for project currency now matches in-app functionality**

_Projects_

You cannot change the currency of a project when there is financial information already on the project. With the latest maintenance update, the API functionality for this case now matches the experience in the [!DNL Workfront] interface.

**Not automatically generating the following week**

_Timesheets_

When a user navigates to the [!UICONTROL Timesheets] area, they only see the timesheet for the current week. The timesheet for upcoming weeks are not automatically generating.

+++

+++**Maintenance Update on January 21, 2021**

**Manually sorting by a column displays all results**

_Reports_

When a user in the new [!DNL Workfront] experience clicks a bar in the chart of a report, then clicks a column header to manually sort results for that grouping, all report results display, not just results for the originally selected grouping.

**"Allow sharing proof via URL or embed code" setting changes**

_Proof_

When a user creates a proof and unchecks the setting [!UICONTROL Allow sharing proof via URL or embed code], the setting is checked again after the proof is generated. If the user leaves the setting checked, it is unchecked after generating the proof.

**Mac users are unable to paste into text fields in proof viewer**

_Proof_

When a user attempts to paste text into certain fields in the proof viewer, the text does not appear in the field.

+++

+++**Maintenance Update on January 14, 2021**

**Unable to update Email Notifications settings**

_Setup_

When a user tries to update settings for email notifications, they are unable to access the [!UICONTROL Email Notifications] area and see the error message "Let's try that again.
Whoops! Something went wrong. Please contact [!DNL Workfront] so we can figure out what went wrong and fix it.."

**[!UICONTROL Gantt] chart causes some fields to truncate**

_Lists_

When a user opens the [!UICONTROL Gantt] chart in some list areas, certain fields—such as [!UICONTROL Description—truncate] the text. The user has to double-click the field to see the full text.

**[!UICONTROL Unable to send files from Document Details]**

_Documents_

When a user in the new [!DNL Workfront] experience tries to send a document from the Document Details page, they see the error message "An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

+++

+++**Maintenance Update on January 7, 2021**

**Delegate Approvals dialog closes**

_Home_

When a user tries to delegate approvals in [!UICONTROL Home] and they click any date, the dialog closes without selecting the date or allowing the user to complete the user delegation.

**Issue with moving a document to a task**

_Documents_

When a user tries to move a document or proof in the new [!DNL Workfront experience], some tasks outside the project do not list the parent project as expected.

**Downloaded PDF has incorrect name**

_Proof_

When a user receives a download link via email (Proof > Print Comments > PDF) and they export the file, the downloaded file is titled with random numbers instead of the Proof ID.

+++
