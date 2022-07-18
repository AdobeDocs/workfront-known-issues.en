---
title: Workfront Maintenance Updates for 2021
description: History of 2021 Maintenance Updates for Adobe Workfront
---

# 2021 Workfront Maintenance Updates

<https://one.workfront.com/s/article/Workfront-Maintenance-Updates-1882317350>

The following maintenance updates were made in 2021:

## Updates in December 2021

+++**Maintenance Update on December 23, 2021**

**New tasks default to incorrect task constraint**

_Tasks_

When a user creates a new task using the "New Task" button, and the New Task Default Start Date option is set to "Today," the task constraint of the created task is set to "As soon as possible" rather than "Start no earlier than." This can also occur when using project templates

**Opening schedule in Groups area leads to blank page**

_Setup_

When a user is viewing groups in the Setup area and attempts to open, edit, or copy a schedule, the schedule does not open and the user sees a blank page.

**Changes do not display when reordering left navigation**

_Navigation_

When a user attempts to reorder the left navigation panel by dragging an item, the item appears back in its previous place when the user drops it. If the user refreshes the page, the left panel displays the new order.

**Link to submit a requested document leads to blank page.**

_Documents_

When a user receives a request to submit a document, and clicks on the link to the object where the document was requested, the link leads to a blank page. This may occur when clicking a link in an email or in an in-app notification.

**Workload Balancer shows 0 hours allocated**

_Workload Balancer_

When a user is viewing the Workload Balancer and has the "Show projected dates" setting enabled, any dates in the future display 0 hours allocated.

**Proofs intermittently disappear from folders**

_Workfront Proof_

When a user who is logged into Workfront Proof views a folder, the folder appears empty. If the user checks back later, the proofs are visible.

+++

+++**Maintenance Update on December 16, 2021**

**Clicking announcement in notifications list leads to blank page**

_Notifications_

When a user opens their list of notifications from the notifications icon, then clicks on an announcement, they are taken to a blank page, and the announcement does not display.

**Summary panel shows "No selection" when task is selected**

_Tasks_

When a user opens a document summary in the documents area of a project, then goes to the task list, selects a task, and attempts to open the task summary, the task summary does not display, and the user sees the following message:

No selection. Select a document in the list to view details.

The message mentions documents even though the user is in the task list.

**Unassigned Work does not load**

_Workload Balancer_

When a user in the Workload Balancer creates a filter using the Assignment:Role ID field, the Unassigned Work area does not load. 

**Attaching template using "Customize and attach" option clears custom field values**

_Projects_

If a user attaches a template to a project using the "Customize and attach" option, and the project has a custom form attached to it already, the custom field values do not carry over and must be manually re-entered. This occurs even when the template includes the same custom form.

+++

+++**Maintenance Update (Hot Fix) on December 10, 2021**

**Whoops error when attaching template to existing project**

_Projects_

When a user attempts to attach a template to an existing project, the template does not attach, and the user sees the following error:

"Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it."

+++

+++**Maintenance Update on December 9, 2021**


**Collapsed left navigation panel expands on page load**

_Navigation_

When a user has set their left navigation to be collapsed, and then refreshed a page, the left navigation is expanded on the reloaded page. The left navigation is also expanded if the user opens a page in a new tab.

**Workload Balancer shows 0 hours allocated**

_Workload Balancer_

When a user is viewing the Workload Balancer and has the "Show projected dates" setting enabled, any dates in the future display 0 hours allocated.

+++

+++**Maintenance Update on December 8, 2021**

**Approval resets when an update is made**

_Approvals_

If a user makes a decision on an approval using the object header, then immediately makes an update on the object, the approval icons reappear in the header and the approval decision is not saved.

**Cannot inline edit an assignment in a report**

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

_Workload Balancer_

When a user in the Workload Balancer creates a filter using the Assignment:Role ID field, the Unassigned Work area does not load. 

**Pages not loading in certain browsers**

_Workfront_

When a user is working in Workfront, pages do not load and the user sees the following error message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This has been reported in

* Firefox
* Microsoft Edge

This error occurs randomly and may affect any area of Workfront.

+++


## Updates in November 2021

+++**Maintenance Update on November 18, 2021**

**Workfront for Jira "Invalid clientID or clientSecret" error on login**

_Workfront integrations_

Users have been logged out of the Jira for Workfront integration. When a user attempts to log into the Workfront for Jira integration, they cannot log in and they see the following error:

"Invalid clientID or clientSecret"

**Custom form attached to request does not update when new Queue Topic is selected**

_Requests_

When a user is creating a request and selects a Queue Topic that automatically attaches a custom form to the request, then selects a different Queue Topic, the custom form from the first Queue Topic remains attached to the request.

**Icons display incorrectly**

_Workfront_

Icon images are displaying incorrectly. This has been reported in many areas across Workfront.

**Tasks do not export to PDF when "Other Sizes" option is selected.**

_Tasks_

If a user attempts to export a task list to PDF, and selects the "Other Sizes" option, they can select a size and click Export, but the list does not export. There is no error message, and no other indication that the export was unsuccessful.

**Image indicator is not displaying in email notifications**

_Notifications_

When a user adds an image to an update, and an email notification is sent to the recipient of the update, the email does not include an indicator that there is an image in the update.

**Pages not loading in certain browsers**

_Workfront_

When a user is working in Workfront, pages do not load and the user sees the following error message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This has been reported in

* Firefox
* Microsoft Edge

This error occurs randomly and may affect any area of Workfront.

+++

+++**Maintenance Update on November 11, 2021**

**Issue with document integrations, blank page on document upload popup from GDrive**

_Documents_

When a user attempts to add a new document to Workfront from Google Drive by using Add New > From Google Drive, the upload popup screen remains blank.

**Cannot use more than one filter in the Workload Balancer**

_Workload Balancer_

When a user is attempting to use more than one filter in the Workload Balancer, they see the following issues:

* If the user selects two filters, only the bottom filter is applied.
* If the user selects more than two filters, no results display.

**"Project Folders" document header missing from project documents area**

_Projects_

When a user is in a project and views the project's documents, the heading "Project Folders" is missing from the left navigation. The dropdown arrow is still there, and the user can select a folder.

**Columns on Kanban board are too wide and cannot be adjusted**

_Agile_

When a user views a Kanban board with several columns, the columns are too wide, and the user must scroll to view or move cards to the rightmost columns. The column widths are not adjustable, so the user cannot make the columns smaller so they are all visible on the screen at the same time.

**Improved interface for creating a new team**

_Teams_

Creating teams is now more intuitive with new visual cues. When you select the Switch Teams icon on any team page, the Create New Team link has an icon to indicate "new," and the link is separated from the rest of the list so it does not look like a team name. This interface is the same for agile and non-agile teams.

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

_Workload Balancer_

When a user attempts to create a filter using a custom field, the value for that custom field do not display and cannot be entered into the filter.

**Pages not loading in Firefox browser**

_Workfront_

When a user is working in Workfront using a Firefox browser, pages do not load and the user sees the following error message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

This error occurs randomly and may affect any area of Workfront.

**Date-related error when creating project from template.**

_Templates_

If a user creates a project from a template, and sets the schedule mode to Start Date, then selects a task constraint, when the user attempts to create the project, the project is not created and the user sees an error message based on the task constraint. 

**Export Gantt Chart dialog is unresponsive**

_Gantt Chart_

If a user in the new Workfront experience attempts to export the Gantt Chart and selects the "What I See" option, the Gantt Chart does not export and the dialog box is unresponsive. The user is unable to close or click out of the dialog box.

**Icons display incorrectly**

_Workfront_

Icon images are displaying incorrectly. This has been reported situations including, but not limited to:

* Images for Job Roles or Groups when sharing an object
* Left and right icons on calendar reports
* Sort icons on report columns

**Add checkboxes to Requests in the Submitted section of the Requests area**

_Requests_

We have added checkboxes to the left of the request names in the Submitted list of the Requests area. This makes it easier to select a request and view additional information.

**Custom Quarters are now supported in the Workload Balancer filters**

_Workload Balancer_

The filters in the Workload Balancer now support custom quarters.

**Updated filter operator for the Duration field in the Workload Balancer Filters**

_Workload Balancer_

We have updated the filter operators when filtering the Workload Balancer areas by Duration.

+++


## Updates in October 2021

+++**Maintenance Update on October 28, 2021**

**Home and My Work displaying blank page**

_Home / My Work_

When a user navigates to Home or My Work, the page displays as blank.

**Cannot view or edit Topic Group details**

_Requests_

When a user attempts to view or edit the details of a Topic Group, the page that opens shows "Topic Group Detail" in the header but is otherwise blank

**Blank required radio buttons are filled out automatically**

_Requests_

When a user submits a request with a required radio button field, and the user has not selected a value for that field before submitting the request, the first value is automatically selected when the request is submitted.

+++

+++**Maintenance Update on October 21, 2021**

**Cannot add a filter in Workload Balancer**

_Workload Balancer_

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

When a user navigates to Home or My Work, the page displays as blank.

+++

+++**Maintenance Update on October 20, 2021**

**Workload Balancer set as the default scheduling option**

_Workload Balancer_

If a user who has the Scheduler set as the default goes to use it, they see that the Workload Balancer has been set as the default.

+++

+++**Maintenance Update (Hot Fix) on October 19, 2021**

**Unable to assign a request when creating it**

_Requests_

When a user in the new Workfront experience is creating a request and attempts to assign a user by typing their name in the Assignments field, the field does not display the drop-down list, and the user cannot select the assignee's name.

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

Previously, Workfront searched for job roles in the first 2000 roles in alphabetical order.

+++

+++**Maintenance Update on October 7, 2021**

**In-app notifications disappear from notifications center**

_Notifications_

When a user views the notification center, some previously visible notifications are no longer visible. In some cases, the notification may disappear before the user sees it.

**Announcements are not visible on the All Announcements page**

_Notifications_

When a user opens the All Announcements page from the Notifications area, there are no announcements visible in the following areas:

* Inbox
* Favorites
* Drafts
* Deleted

**Error when making assignment in the Workload Balancer**

_Workload Balancer_

When a user attempts to make an assignment from the Workload balancer, the work is not assigned and the user sees the following error: 

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

**Access Denied error when viewing tickets submitted to Workfront**

_Issues_

When a user has submitted a ticket to Workfront and attempts to view the ticket, they see the following error:

"Access Denied: Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it."

**Business Case Summary shows incorrect values**

_Projects_

When a user views the Business Case summary panel, the values displayed do not reflect the values in the individual Business Case sections.

**Column headers do not line up with columns in lists**
 
_Setup_

When a users is in the Setup area and views a list, such as Custom Forms or Access Levels, the column headers for that list do not line up with the columns in the list.

**Users without the proper sharing permissions can attach custom forms to objects**

_Custom Forms_

When a custom form in the new Adobe Workfront experience is set to be visible system-wide, all users are able to attach this custom form to an object. However, they should only be able to view the custom form and not be able to attach it to an object unless it has been shared specifically with them.

+++

+++**Maintenance Update on September 16, 2021**

**Cannot edit groups**

_Groups_

When a user attempts to edit or delete a group, the group is not edited or deleted, and the user sees the following message:

"Let's try that again. Group with primary key value(s) "\<Group's ID\>" not found"

**Portfolio Optimizer not displaying projects**

_Portfolios_

When a user attempts to view projects in the Portfolio Optimizer, the project list does not display and the user is therefore unable to interact with the projects.

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

When a user in the new Adobe Workfront experience selects an issue from the Work List, the preview in the right panel displays certain fields as having no values entered. However, if you navigate to the issue and view the Issue Details, these fields have values entered.

**Users need Contribute permissions to view the Approvals section in the new Workfront Experience**
 
_Approvals_

Users need Contribute permissions on an object to view the Approvals section in the new Workfront Experience. They should need only View permissions to view the Approvals tab when there is an approval process on the object. 

**Whoops error when using filters**
 
_Lists_

When a user attempts to use one of the following filters:

* All Projects
* Projects I'm On
* My Current Tasks

the list goes blank and the user sees the following error:

"Let's try that again."

**Tasks section goes blank when editing inline**

_Templates_

When a user attempts to inline edit tasks in a template using a view that includes the "Assign To: Name" field, and the assignment contains a user, the tasks section goes blank and the user is unable to edit the template tasks.

**Cannot export Portfolio Optimizer**

_Portfolios_

When a user attempts to export the Portfolio Optimizer and clicks any of the export options, the Portfolio Optimizer does not export.

**Notifications are not being sent for replies**

_Notifications_

When a user replies to an update in Workfront, other users in the comment thread are not receiving notifications.

**Changes to custom data cause lag**

_Custom fields_

When a user modifies custom data that triggers changes to other displayed data, the changes load slowly.

**Grouping "Collapse or Expand All" icon does not display**
 
_Reporting_

The "Collapse or Expand All" icon does not display in the header of a list or report when groupings are applied to the list or report.

**Check and Cancel options not visible when changing task allocations**

_Workload Balancer_

When a user attempts to change the task allocation for a task, and the time frame of that task extends to or beyond the edge of the visible page, the Check and Cancel buttons are not visible, and the user cannot save or cancel the allocation changes.

**Adding a custom field to Home causes missing field data**

_Home_

When a custom field is added to Home, other fields start missing data and showing incorrectly.

**Cannot view linked items when logged in as another user**

_Integrations_

If an administrator attempted to view linked items from an external provider while logged in as another user, they were not able to open the linked folders and could not view the items.

+++

+++**Maintenance Update on September 2, 2021**

**Cannot pin custom dashboard**

_Dashboards_

When a user attempts to pin a custom dashboard, the dashboard does not pin and the user sees the following error:

"Something went wrong while pinning. Please contact Workfront so we can fix this."

**Proof print summary is blank**

_Proof_

When a user opens the print summary to print a proof, the header appears but the summary itself is blank.

+++


## Updates in August 2021

+++**Maintenance Update on August 26, 2021**

+++

+++**Maintenance Update on August 19, 2021**

+++

+++**Maintenance Update on August 12, 2021**

+++

+++**Maintenance Update (Hot Fix) on August 6, 2021**

+++

+++**Maintenance Update on August 5, 2021**

+++


## Updates in July 2021

+++**Maintenance Update (Hot Fix) on July 29, 2021**

+++

+++**Maintenance Update on July 29, 2021**

+++

+++**Maintenance Update on July 22, 2021**

+++

+++**Maintenance Update (Hot Fix) on July 19, 2021**

+++

+++**Maintenance Update on July 15, 2021**

+++

+++**Adobe Workfront Fusion Maintenance Update on July 1, 2021**

+++

+++**Maintenance Update on July 1, 2021**

+++


## Updates in June 2021

+++**Maintenance Update on June 24, 2021**

+++

+++**Adobe Workfront Fusion Maintenance Update on June 23, 2021**

+++

+++**Maintenance Update on June 17, 2021**

+++

+++**Maintenance Update on June 10, 2021**

+++

+++**Maintenance Update on June 3, 2021**

+++


## Updates in May 2021

+++**Maintenance Update on May 27, 2021**

+++

+++**Maintenance Update on May 20, 2021**

+++

+++**Workfront Fusion Maintenance Update on May 17, 2021**

+++

+++**Maintenance Update on May 13, 2021**

+++

+++**Maintenance Update on May 6, 2021**

+++


## Updates in April 2021

+++**Maintenance Update on April 29, 2021**

+++

+++**Maintenance Update on April 22, 2021**

+++

+++**Workfront Fusion Maintenance Update on April 15, 2021**

+++

+++**Maintenance Update on April 15, 2021**

+++

+++**Maintenance Update on April 8, 2021**

+++

+++**Maintenance Update on April 1, 2021**

+++


## Updates in March 2021

+++**Maintenance Update on March 26, 2021**

+++

+++**Workfront Fusion Maintenance Update on March 25, 2021**

+++

+++**Workfront Fusion Maintenance Update on March 18, 2021**

+++

+++**Maintenance Update on March 18, 2021**

+++

+++**Maintenance Update (Hot Fix) on March 15, 2021**

+++

+++**Maintenance Update on March 11, 2021**

+++

+++**Maintenance Update on March 4, 2021**

+++

+++**Maintenance Update (Hot Fix) on March 1, 2021**

+++


## Updates in February 2021

+++**Maintenance Update on February 25, 2021**

+++

+++**Maintenance Update on February 18, 2021**

+++

+++**Workfront Fusion Maintenance Update on February 16, 2021**

+++

+++**Maintenance Update on February 11, 2021**

+++

+++**Maintenance Update on February 4, 2021**

+++


## Updates in January 2021

+++**Maintenance Update on January 28, 2021**

+++

+++**Maintenance Update on January 21, 2021**

+++

+++**Maintenance Update on January 14, 2021**

+++

+++**Maintenance Update on January 7, 2021**

+++

