---
title: Workfront Maintenance Updates
description: Maintenance Updates for Adobe Workfront
---

# Workfront Maintenance Updates

<https://one.workfront.com/s/article/Workfront-Maintenance-Updates-1882317350>

The following maintenance updates have been made in 2022.

>[!NOTE]
>
>These updates also include other minor or less prominent bug fixes. Workfront Support will notify you when an issue you submitted is fixed.

* [June 2022](#updates-in-june-2022)
* [May 2022](#updates-in-may-2022)
* [April 2022](#updates-in-april-2022)
* [March 2022](#updates-in-march-2022)
* [February 2022](#updates-in-february-2022)
* [January 2022](#updates-in-january-2022)

For maintenance updates prior to 2022, see [Previous Maintenance Updates](#previous-maintenance-updates)

## Updates in June 2022

These issues were fixed only in the new Workfront experience. Adobe Workfront Classic is no longer supported. 

All Workfront Classic functionality will be removed in July 2022. Please transition to the new experience as soon as possible.

* [Maintenance Update on June 9, 2022](#maintenance-update-on-june-9-2022)
* [Workfront Scenario Planner Maintenance Update on June 9, 2022](#workfront-scenario-planner-maintenance-update-on-june-9-2022)
* [Workfront Fusion Maintenance Update on June 9, 2022](#workfront-fusion-maintenance-update-on-june-9-2022)
* [Maintenance Update on June 2, 2022](#maintenance-update-on-june-2-2022)

### **Maintenance Update on June 9, 2022**

The following customer-reported issues were fixed on June 9, 2022.

**Cannot select objects to filter in Portfolio Optimizer preferences**

*Portfolios*

When a user is in the Portfolio Optimizer and views the Project Filters tab in the Preferences area, the checkboxes next to the objects are absent. The user cannot check or uncheck boxes, and therefore cannot select objects to filter.

**Cannot change Planned Start or Completion Dates when "Schedule From" is not checked**

*Projects*

When a user attempts to edit the Planned Start Date or Planned Completion Date of a project, and the "Schedule From" option for that project is not checked, the Planned Start Date and Planned Completion Date areas are disabled, and the user cannot edit those dates.

**Cannot edit access level of users**

*Users*

When a user who has Planner access that includes User Admin (Group Users) access attempts to edit users in the group they are an admin for, the Access level field is disables, and the user is unable to edit the access level.

### **Workfront Scenario Planner Maintenance Update on June 9, 2022**

**Resizable left panel in the Scenario Planner**

*Workfront Scenario Planner*

You can now resize the left panel on a Plan, in the Scenario Planner. This allows longer initiative names to display fully. Prior to this update, longer initiative names were truncated. 

### **Workfront Fusion Maintenance Update on June 9, 2022**

**Data from custom forms not available in Workfront Fusion Workfront modules**

*Workfront Fusion*

When a user is configuring a Workfront module in Workfront Fusion, and attempts to select outputs for the module, fields from custom forms are not visible. This occurs when the custom form was created for one type of Workfront object and then another type was added to it. Workfront Fusion displays only fields from custom forms originally created for the selected object type.

**Cannot scroll to view all scenario executions**

*Workfront Fusion*

When a user is viewing a scenario's execution history and attempts to scroll down to view more executions, the executions stop loading and the user is unable to view them. Additionally, the user cannot scroll back up to the most recent executions.

### **Maintenance Update on June 2, 2022**

**Portfolio Optimizer shows a score of 0 when using language other than English**

*Portfolios*

When a user is using Workfront in a language other than English and views the Portfolio Optimizer, the score displays as 0. This may occur even when the business case is not complete.

**Calculated field values incorrect when creating project from template**

*Projects*

When a user is creating a project from a template that includes calculated fields, the field values that appear on the new project are incorrect. 

**Cannot edit Conditions in Project Preferences are of Setup**

*Setup*

When a user attempts to edit Conditions in the Project Preferences area of Setup, the page is blank.

**New limitation to the number of characters in an update in Preview** 

*Workload Balancer*

>[!NOTE]
>
>This update applies only to the Preview environment.

To improve the performance of the Updates area, we have introduced a  new limit to the number of characters that you can enter in an update or a reply to an existing update. The new limit is 15,000 characters. This update did not change the number of characters allowed when using the API. The API character limit for updates is 4,000. Updates
Support for Typehead type custom fields in Workload Balancer filters 

We are now supporting filters based on the Typeahead type custom fields in the Workload Balancer. Prior to this patch, filtering for this type of custom fields was not possible in the Workload Balancer.

**Cannot edit permissions on a user's role**

*Workfront Proof*

When a user attempts to edit the "Resolve comments and apply actions" or "Share a proof by tagging" permissions on a user's role in Workfront Proof, the changes are not saved. The user gets a notification that the template has been updated, but if the user opens the role permissions again they can see that the changes were not saved.

+++


## Updates in May 2022

+++**Maintenance Update on May 26, 2022**

These issues were fixed only in the new Workfront experience. Adobe Workfront Classic is no longer supported. 

All Workfront Classic functionality will be removed in July 2022. Please transition to the new experience as soon as possible.

**Updated breadcrumb separators**

*Workfront*

NOTE: This update was released on May 24, 2022.

We have updated the breadcrumb separators in all areas where breadcrumbs are available. Now, the objects in the breadcrumbs are separated by pipes (|). Prior to this update, they were separated by forward slashes (/).

**Cannot edit custom forms with section breaks**

*Custom Forms*

When a user attempts to edit a custom form that has a section break, they cannot edit the form, and they see the following message: 

Specified section break security cannot be applied on all object types

**Issues when printing Dashboards to PDF**

*Dashboards*

The following issues have been reported when printing a dashboard to a PDF:
The PDF does not print every row in the report. Where lines are missing, only blank space displays.
The PDF includes blank spaces between the column headers and the first row of the report.

**Portfolio Optimizer shows a score of 0 when using language other than English**

*Portfolios*

When a user is using Workfront in a language other than English and views the Portfolio Optimizer, the score displays as 0. This may occur even when the business case is not complete.

**Some custom forms do not display when editing a template**

*Templates*

When a user attempts to edit the custom forms on a template by clicking Edit in the template's header, the Edit Template window only displays one of the custom forms attached to the template.

**Shared link to Workload Balancer displays assigned work incorrectly**

*Workload Balancer*

When a user views the Workload Balancer using a shared link, the Workload Balancer includes Assigned Work in the Unassigned Work section. Assigned Work does not have a separate section. When the user views the Workload Balancer without using the shared link, Assigned Work displays as expected.

+++

+++**Maintenance Update on May 19, 2022**

**Cannot create a proof from a PowerPoint**

*Workfront Proof*

When a user attempts to create a proof from a PowerPoint that includes a chart, the proof creation fails.

**Cannot create a proof from a Word document**

*Workfront Proof*

When a user attempts to create a proof from a Word document that includes a chart, the proof creation fails.

**Cannot add custom message when sharing a proof**

*Workfront Proof*

When a user is viewing a proof, opens the Share proof area, and selects the Add custom message button, the user cannot type into the text box that opens. When the user attempts to type in this box, the box immediately disappears. 

**Cannot close proof**

*Workfront Proof*

When a user is viewing a proof and attempts to close it, the X to close the proof is missing from the upper-right corner of the proof.

**Cannot add or remove group administrator**

*Groups*

If a user is viewing a Group page and attempts to add or remove a group administrator by using the Group Administrators area in the header, the changes are not saved and the user sees the following error:

Error

Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.


**Horizontal scroll bar blocks item at end of list**

*Projects*

When a user is viewing a list using a view that extends off the side of the screen, the horizontal scroll bar blocks the user's view of the last item on the list.

**"Unexpected error" when converting an issue to a project using a template**

*Lists*

When a user attempts to convert an issue to a project using a template, the issue does not convert and the user sees the following message:

An unexpected error happened

**The Status field in a timesheet view is now read-only**

*Timesheets*

We have changed the Status field in a timesheet view to be read-only. Prior to this change, users could inline edit the status of a timesheet which allowed them to override the decision of the timesheet approvers.

+++

+++**Maintenance Update on May 12, 2022**

**Save button does not stop loading when editing a project**

*Projects*

When a user is editing a project and attempts to save, they notice that the Save button displays the word "Loading." If the user clicks on this button to save the changes to the project, the button is unresponsive and the changes do not save.

**Field labels not appearing when viewing an object in Home**

*Home*

When a user selects an object from their Home Work List, the area to the right of the Home Work List that displays the object does not include field labels. The field values are present.

**Quick Filter does not automatically focus on search bar**

*Lists*

When a user is in a list and clicks the magnifying glass to quick filter, then begins typing, the text does not appear. This is because the focus remains on the magnifying glass icon rather than transferring to the search bar.

Clicking on the search bar transfers the focus and allows the user to enter the text of their search.

**Users unable to inline edit fields in a report**

*Reports*

When a user attempts to edit a field in a report, and that field is pulled from a custom form, the user is not able to edit the field. This occurs when the custom form was originally created for an object type other than the object it is attached to.

**Label and button text not visible when creating a proof**

*Workfront Proof*

NOTE: This issue exists only in the Preview environment.

When a user attempts to create a proof, the text is not visible for options or buttons. Therefore, the user does not know what each option or button represents, and cannot configure the proof.

+++

+++**Maintenance Update on May 5, 2022**

**Cannot add a new Billing Record**

*Projects*

When a user is in the Billing Records area of a project and is using the New Billing Record View, if the user attempts to add a new Billing Record, the fields for a new Billing Record do not appear and the Billing Record cannot be created.

**Error when making bulk assignment in Workload Balancer**

*Workload Balancer*

When a user attempts to make assignments in the Workload Balancer of a project, the user is redirected to a page with the following message:

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

The user cannot navigate away from this page until they refresh the page.

**Updated navigation to open the Summary panel for tasks and issues in the Workload Balancer**

*Workload Balancer*

Now, simply clicking a task or issue bar in the Workload Balancer opens the Summary Panel. Prior to this update, you had to click the Open Summary icon in the toolbar and then click on the task or issue. This had proven a confusing experience that is now corrected. Alternatively, you can click the More menu next to the task or issue name, then click Open Summary.

**Group administrator cannot view details of users in the group**

*Users*

When a user who is assigned to an access level that includes the User Admin (Group Users) access setting attempts to view details of a user in their group, they see the following error:

"Let's try that again
Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it."

**Cannot delete custom group status**

*Groups*

When a user attempts to delete a custom group status from the Group page, the page goes blank and the status is not deleted.

**Email alert settings are inconsistent between Contacts area and User Details**

*Workfront Proof*

Email alert settings displayed in the Contacts area of Workfront Proof for a given user are different from the email alert setting set in the user's User Details.

**Cannot use Text tool when making a comment on a proof**

*Workfront Proof*

When a user is making a comment on a proof and attempts to open the Text tool, the tool does not open and the user sees the following message: 

"Text data for this page is still downloading. Please wait."

**Proof emails will go to the user's primary email**

*Workfront Proof*

We're making adjustments to how proof email notifications are sent. Now, notifications will go to the user's primary email address rather than the alias email generated by the system.

For more information on why the system generates alias emails, see User synchronization between Adobe Workfront and Workfront Proof.

+++

## Updates in April 2022

+++**Maintenance Update on April 28, 2022**

**Cannot scroll to Save button when editing a timesheet**

*Timesheets*

When a user is editing a timesheet, they cannot scroll the edit window far enough to see the Save button, and therefore cannot edit the timesheet.

**Electronic signature now checks Federation ID**

*Proofs*

When signing a proof electronically, the system now checks the Federation ID, if you have SSO set up in Workfront Proof, in addition to your email in Workfront.

Previously, the system checked only your email in Workfront.

+++

+++**Maintenance Update (Hot Fix) on April 25, 2022**

**Workload Balancer does not load**

*Workload Balancer*

When a user attempts to open the Workload Balancer, the header and left navigation load, but the content of the Workload Balancer does not load. The user sees flashing gray squares instead of data. Occasionally, part of the content loads, but the user still sees flashing gray squares where the missing data would be.

+++

+++**Maintenance Update on April 21, 2022**

**Adding a task causes page to jump down**

*Tasks*

When a user adds a task below an existing task in a list, the page jumps to lower in the list. Although the new task is in the correct place, the user must scroll back up to locate it.

**Users added to a proof cannot access the proof's work item in Workfront**

*Proofs*

If a user is added to a stage in a proof's workflow, the user is not added to the Document sharing and does not get permissions to the proof's work item in Workfront. When the user is in Workfront and attempts to open the work item the proof is attached to, they see the following message:

"You do not have sufficient access to view this \<object\>"
 
This issue is specific to proofs already created and users being added after the fact. Adding users to the Workflow before proof creation works as expected.

**Cannot send password reset email from Workfront**

*Users*

When a user attempts to send a password reset email from a user list in Workfront, the option to send the email is not available.

**Button displays "Start Issue" rather than "Start Request"**

*Requests*

When a user views a request assigned to their team, they see a "Start Issue" button in the header rather than a "Start Request" button. 

**"Undo comment" option removes tagged users**

*Updates*

When a user tags another user in a comment, posts the comment, and then selects the "Undo comment" option, the comment appears in an update box as usual, but the tagged user is not in the Tagged users box.

**Cannot scroll when using Milestone view in a report**

*Reports*

When a user is viewing a report and selects the Milestone view, the page displays the Milestone view but no longer scrolls, and the user cannot view any Milestones that would be further down the page.

**Incorrect currency when report is displayed in dashboard**

*Reports*

When a user views a report in a dashboard, the currency used in the report is incorrect. When the user views the report outside of the dashboard, the currency is correct.

**Completed filter is not displaying Completed work item**s

*Home*

When a user views their Home Work List with the Completed filter selected, Completed work items do not display in the list. When the All filter is selected, Completed items are included in the list, showing that the Completed items exist.

**Workfront does not load**

*Workfront*

When a user attempts to log into Workfront, the page appears to be stuck in a loop of redirects or refreshes, and does not load.

+++

+++**Maintenance Update on April 14, 2022**

**Cannot add a task from a report on a custom section on a task**

*Tasks*

When a user is viewing a custom section on a task, and the section contains a task report, the user cannot add a task from that report. The Add Task button highlights the report, but does not open a window for the user to add a task.

**Done button in wrong location when editing a view**

*Views*

When a user is editing a view, the Done button appears higher on the screen, and may overlap text.

The user can edit the view as usual. Functionality is not affected.

**Cannot scroll when using Milestone view in a report**

*Reports*

When a user is viewing a report and selects the Milestone view, the page displays the Milestone view but no longer scrolls, and the user cannot view any Milestones that would be further down the page.

**Blank screen when viewing updates**

*Updates*

When a user is viewing updates and scrolls the screen to view updates further down, the screen becomes blank and the user can not see any updates.

**Error when bulk assigning user to task that is not assigned to User's role**

*Workload Balancer*

When a user in the Workload Balancer attempts to assign tasks to a user whose Job Role does not match the Job role assigned to the tasks, the user sees a message that the task will be assigned using the primary Job Role of the assigned user. However, when the user clicks "Assign," the tasks are not assigned and the user sees the following error:

"Error
The server encountered an unknown error."

+++

+++**Maintenance Update on April 7, 2022**

**Users added to proofs have incorrect roles**
 
*Proofs*

When a user adds another user to a proof, that user's role on the proof is set as "Read-only" despite the user's actual proof role.

**Cannot send password reset email to user**

*Users*

When a user attempts to send a password reset to another user, they see that the Send Forgot Password Email option is not available in the More menu.

**Update All sends updates to user profiles instead of project**

*Updates*

When a user is viewing the People area of a Project and selects the Update All option, then enters an update, the update is not posted to the project itself. Instead, it is posted to the individual user profiles of each user on the project.

**Excessive number of pages when printing updates**

*Updates*

When a user is viewing an update stream that would be more than one printed page, and attempts to print the page, the print screen shows that the number of pages is far above the actual number of pages needed to print the updates. If the user then attempts to print to PDF, the PDF creation fails.

**Users are unable to see the entire list of entities shared with a report when the "Visible System-Wide" setting is enabled**

*Reports*

When sharing reports with multiple entities displaying in the Report Access box, users are unable to scroll to the bottom of the list to see the entire list when the “Visible System-Wide” setting enabled. 

**Incorrect currency used in reports**

*Reports*

If a user sets the currency of a project to be different than the default currency, then views a report on that project, the currency appears as the default currency instead of the project's currency.

**Last Viewed information not updating in Report Usage reports**

*Reports*

When a user is viewing a report that displays information regarding the last time the report was viewed, that information may be blank or may be old data. This issue affects fields including the following:

* Last Viewed By
* Last Viewed Data
* Last X Viewers
* Views This Month / Quarter / Year

**Completed tasks displaying in Home Work List**

*Home*

When a user is viewing their Home Work List, they see Complete tasks in the list, even when the option to display Completed tasks is not selected.

**Schedule button not visible to schedule Sandbox refresh**

*Sandbox Environment*

The Schedule button used to schedule a sandbox refresh is not visible in the top banner of the sandbox environment.

**Changes to a calculated field affect all calculated fields on a form**

*Custom Forms*

When a user is in the Custom Form Builder and changes the value of a calculated form, all calculated fields on the form show the new value. This can affect new or existing calculated fields.

**Colors flickering on custom form builder**

*Custom Forms*

When a user is working with calculated fields on the custom form builder, the colors of the fields and expressions flicker.

**Cannot reject an approval**

*Approvals*

When a user attempts to reject an approval, the Reject button is unresponsive, and the approval is not rejected.

**Projects tab defaults to All Project section despite previous selection**

*Projects*

When a user goes to a Projects page via a tab that has been pinned as part of the layout template, the page defaults to the All Projects area of the left navigation. This occurs even when the user chooses another area of the left navigation, then navigates away from the Projects page and back.

+++


## Updates in March 2022

+++**Maintenance Update on March 31, 2022**

**Timezones not consistent between Workfront and Workfront Proof**

*Proof*

When a user's profile is set to a specific timezone in Workfront, the user's timezone in Workfront Proof is set to a different timezone. 

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

**Users cannot be assigned with secondary job role on Workload Balancer**

*Workload Balancer*

When a user attempts to assign another user to a task on the Workload Balancer, and the task is assigned to a job role other than the assigned user's primary job role, the user is assigned to the task by their primary job role, and the following message displays:

"\<Name\> does not match the role of \<Task role assignment\>. 1 work item currently assigned to the role of <\Task role assignment\> will be assigned to \<Name\> in the role of \<Primary job role\>."

This occurs even if the user does have the Task role assignment's job role as a secondary job role.

**Issue with Scrum Board "Show more work items" b**ar

*Agile*

When a user clicks the Show more work items bar on a Scrum Board, then scrolls to see the new items, the Show more work items bar sticks to the Scrum Board and moves with it when scrolled. This can make the cards hard to read.

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

**Timezones not consistent between Workfront and Workfront Proof**

*Proof*

When a user's profile is set to a specific timezone in Workfront, the user's timezone in Workfront Proof is set to a different timezone. 

**Required field error for filled-in custom fields when attaching a template**

*Projects*

When attaching a template with required custom fields to a project where the field already exists and is filled out, users see the following error: "There are incomplete fields. Enter values for required fields before you can continue."
Clicking "Take me there" allows them to see that the fields are filled out and they can attach the template successfully. 

**The Workload Balancer flashes when you toggle between dates**

*Workload Balancer*

The hours of the user listed first in the Workload Balancer do not display when you update the timeline. The user and their hours display with all grey boxes that just blink. This happens if you move forward and backwards on the timeline. 

Updating the filter does seem to reset the display. However, moving backwards and forwards on the timeline causes the display flash again and the user hours to not display. 

**Custom terminology is inconsistent**

*Layout Templates*

Users are reporting that when the Workfront administrator customizes the terminology for some objects using a Layout Template, the new object name displays inconsistently in the interface. 

For example, on the Projects page, you can still see the page title displayed as "Projects", even though the Workfront administrator changed the name for "Projects" to something else.

This causes confusion for end users.

+++

+++**Maintenance Update on March 17, 2022**

**Thumbnail and main images are blank when viewing multipage files using Safari browser**

*Proof*

When a user attempts to view a file with multiple pages in the Safari browser, the thumbnail page images are blank. Occasionally, the main image may also be blank.

**Incorrect user list when making bulk assignments in the Workload Balancer**

*Workload Balancer*

When a user is making a bulk assignment in the Workload Balancer and selects a Project and Job Role, the list of users available is incorrect. It may show users without the Job Role or Project permissions, and users with the Job Role and Project permissions do not appear in the list.

**Sorting is not working in reports**

*Reports*

When a user clicks on a column to sort by it, the sort appears to work but instantly the results revert to the original sorting as it displayed before clicking the column. The sorting on any column is not retained. 

**Selecting "Nothing" reverts to the Report Default grouping**

*Reports*

When a report has a built-in grouping and the user attempts to select "Nothing" in the Grouping drop-down menu, the report displays shortly with no grouping and then revert to the Report Default grouping.

**Removed "Blueprints access" tab from Blueprints preferences**

*Blueprints*

NOTE: This issue exists only in the Preview environment.

The Blueprints access tab has been removed from the Blueprints preferences modal. No functionality has been removed from the Blueprints preferences.

+++

+++**Maintenance Update (Hot Fix) on March 14, 2022**

**Cannot scroll down user list when making assignment on Kanban board**

*Agile*

When a user is viewing a Kanban board and attempts to make an assignment, the user list that appears when they type keeps jumping back to the top as they scroll down. The user is unable to select a user that is not near the top of the list, and cannot save the assignment change.

**Milestone View in project report causes error**

*Reports*

When displaying a project report using the Milestone View, users get a "APIModel INTERNAL does not support namedQuery TILE:milestone-view (UIVW)" error. 

**Custom terminology is inconsistent**

*Layout Templates*

Users are reporting that when the Workfront administrator customizes the terminology for some objects using a Layout Template, the new object name displays inconsistently in the interface. 

For example, on the Projects page, you can still see the page title displayed as "Projects", even though the Workfront administrator changed the name for "Projects" to something else.

This causes confusion for end users.

**Unable to update calculations for existing calculated fields**

*Custom Forms*

Users are unable to update/ change the calculations in calculated fields. If the field was created and saved with without a calculation, every time you try to add an expression and save/apply, the builder reverts back to being blank. 

If you create a calculated field with a certain expression and save it, every time you try to change the calculation, it reverts back to its previous value. 

**Invalid Parameter error when resetting passwords**

*Login*

Users are unable to reset their passwords in any environment. When they enter their email and try to proceed they see an error. 

Error: Invalid Parameter: Search Parameter value "domain".

+++

+++**Maintenance Update on March 10, 2022**

**Issues logging in to Preview environment**

*Login*

The following issues with logging in to the Preview environment have been reported.

When a user attempts to log in to the Preview environment, a message appears indicating that they put in the wrong ID or password.

When a user attempts to reset their password, they see the error "?Multiple users were found with the email address <example@example.com>?"

**Custom forms load slowly in Project Details area**

*Projects*

When a user attempts to view a project's Project Details area, any custom forms that are attached to the project load only after a delay of 15 seconds or more. The Add custom forms option is also affected by this delay.

**Custom form field values not saved in document summary panel**

*Documents*

When a user updates custom form fields in the document summary panel, and one or more of them is a typeahead field, then saves the changes and navigates away from the summary panel, the updates are not saved. This occurs only when a typeahead field is edited, although all fields are affected.

**Data not preserved when converting templates due to template sharing access levels**

*Projects*

When a user who has View access on a shared template attempts to convert an issue to a project, any data in custom form sections that require Contribute or higher access to view is not transferred to the created project.

**Error when uploading new document version**

*Documents*

When a user attempts to upload a new version of a document from the document list, the document does not upload and the user sees the following error: 

Error
Cannot invoke "com.attask.boz.Document.getCurrentVersion()" because "document" is null

**Unable to edit billing rates**

*Projects*

When a user attempts to edit a billing rate on the Billing Rates tab of a project, clicking the Edit button opens the Edit window briefly, but it closes before the user can edit the billing rate. Clicking the button again does not open the edit window.

**Public link for document leads to blank page**

*Documents*

When a user attempts to open a document using a public link, the link leads to a blank page. This occurs when the link is opened in a window where an active Workfront session is open.

**Whoops error when adding task or issue to list**

*Tasks and Issues*

When a user who is not an admin attempts to add a task or issue to a list, and fills in custom fields, the task or issue is not created and the user sees the following error:

Error
Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.

**Leaving an update after a status change reverts the object to a previous state**

Projects, tasks, and issues

Changing the status of a project, task, or issue and then immediately starting typing an update without refreshing the page causes the update box to show the previous status. If the update is posted, the object is reverted to the previous status.

**Users added to proofs have incorrect roles**

*Proofs*

When a user adds another user to a proof, that user's role on the proof is set as "Read-only" despite the user's actual proof role.

Workaround:
Set the user's proof role in their profile to something else, then reset to the correct role.

**Custom form does not load when converting issue to project using template**

*Custom forms*

When a user attempts to convert an issue to a project using a template, one or more of the custom forms attached to the template may not load. When the user configures the template for the new project, instead of the custom forms they see the following message:

"Something went wrong, could not load form."

**User unable to add issue inline with custom drop-down field displaying in the view**

*Lists*

When a user is adding an issue from inline and there is a custom view with custom drop-down fields applied to the list, there is an error when they fill out the drop-down field only. The user has access to edit custom form and is the project owner with manage rights to the project. 

Error: Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it!

**Permissions to add tasks to a project are not required to move or copy a task to the project**

*Tasks* 

You now can move or copy a task to another task in a project without having  permissions to add tasks to the destination project. You must have permissions to add tasks to at least one of the destination project’s tasks. Prior to this update, you were required to have permissions to add tasks to the project to move or copy a task to the project or to any of its tasks.  This update is now available in the Production environment. It has been available in the Preview environment starting with the March 24, 2022 maintenance update. 

NOTE: This update will be available in the Production environment when copying or moving issues after the 22.2 Production release. For more information about the current release, see workfront.com/release. 

**Prompt drop-down menu is cut off**

*Reports*

When using a prompt  in a report, the drop-down menus that allow you to select the filtering criteria for the report are cut off. As a result, the criteria at the bottom of the selection drop-down menu does not display.

**Work item reverts to previous status when an update is made**

*Updates*

When a user changes the status of a work item in the header, the status does not update in the Update area. If the user then makes a update, the dropdown still shows the previous status. When the update is saved, this previous, incorrect status overwrites the status that was set in the header.

+++

+++**Maintenance Update on March 3, 2022**

**Cannot add document from Google Drive**

*Documents*

When a user attempts to add a document from Google Drive, the selection is unresponsive, and the user is unable to select documents to add.

**Tagged users are not added to update thread**

*Updates*

When a user is tagged in an update, they are not shown in the "to" area of the update or its replies.

**Proof user has two separate proofing accounts**

*Proof*

A user's email address in Workfront Proof may be in two separate accounts with separate IDs, giving the user two accounts. This may make it difficult to locate the correct account.

**Whoops error displaying in report headers**

*Reports*

When a user views a report, the following error displays in the report header:

"Let's try that again. Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it."

If the user is viewing a dashboard, the error may appear in the header for all the reports on the dashboard.

**Data in Admin-edit-only fields of custom form is not preserved when converting issues to projects**

*Projects*

When a non-admin user attempts to convert an issue to a project using a template, and the issue contains data in fields that can only be edited by an admin, the data in those fields does not carry over to the new project.

When an admin converts the issue, the data is carried to the new project as expected.

**XLS and XLSX file size limit temporarily decreased to 100 MB for proofs**

*Proofing*

In order to address a security issue, we’ve temporarily limited the maximum file size for XLS and XLSX files to 100 MB when creating a proof.

NOTE: This update was in the Preview environment on February 24, and will be in the Production environment on March 3.

**Update to Workfront Search**

Search

A phased rollout began this week to update the infrastructure for the Workfront Search functionality. The update will make future improvements to Search easier and more reliable. With these changes, items added to Workfront will be indexed more quickly and therefore will return in search results sooner.

The phased rollout will continue for 2 weeks.

**Updated toolbars for reports within dashboards**

Reports

Reports within dashboards now show a new toolbar. This toolbar is part of the updates to lists and reports that are happening throughout Workfront.

+++


## Updates in February 2022

+++**Maintenance Update (Hot Fix) on February 24, 2022**

**Data not preserved when converting issues to projects if field is hidden on template**

*Projects*

When a user converts an issue to a template, and the template includes a custom form that displays or hides fields based on the values in other fields, any data in fields that are hidden on the (dataless) template at the time of conversion is not carried into the new project.

**Cannot export resource planner by Role**

*Resource Planner*

When a user attempts to export the Resource Planner when using the View by Role option, the export does not succeed and the user receives an email with the following message:

An error occurred while exporting your Resource Planner data.

**Copy request button not working**

*Requests*

When a user attempts to copy a request, the copy request button does not work if the user does not have View access to the queue topic. 

+++

+++**Maintenance Update on February 24, 2022**

**Custom form data disappears when other form fields are filled out**

*Custom forms*

When a user is filling out a custom form as part of converting an issue to a project, filling out one custom field may cause data in another custom field to disappear. If the user enters the missing data again, when they try to create the project, they see the following error message:

"You must be a system admin to change this custom data parameter value"

**"This approval process can be used by..." field missing**

*Approvals*

When a user is creating or editing an approval process in the Setup area, the "This approval process can be used by..." field is missing. This can occur when creating an approval process or when editing an existing one.

**System admin cannot reassign users when deleting a group**

*Groups*

When a system administrator deletes a group, they will only have the option to reassign that group's users to groups that the system administrator is a group administrator for. Other groups do not appear in the dropdown, and the admin cannot select them.

**Whoops error when converting issue to project**

*Projects*

When a user attempts to convert an issue to a project using a template, and adds or removes custom forms from the template, the issue does not convert and the user sees the following message:

Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.

**Cannot open proof; page refreshes**

*Proofs*

When a user attempts to open a proof, the proof is unable to open. Eventually, the page refreshes.

**XLS and XLSX file size limit temporarily decreased to 100 MB for proofs**

*Proofing*

In order to address a security issue, we’ve temporarily limited the maximum file size for XLS and XLSX files to 100 MB when creating a proof.

NOTE: This update will be in the Preview environment on February 24, and in the Production environment on March 3.

**Permissions to add tasks or issues to a project are not required to move or copy a task or an issue to the project**

*Projects*

You now can move or copy a task or an issue to another task in a project without having permissions to add tasks or issues to the destination project. You must have permissions to add tasks or issues to at least one of the destination project’s tasks. Prior to this update, you were required to have permissions to add tasks or issues to the project to move or copy a task or an issue to the project or to any of its tasks. This update is available only in the Preview environment.

NOTE: This update will be available in the Production environment when coping or moving tasks on March 10th. This update will be available in the Production environment when copying or moving issues with the 22.2 Production release. For more information about the current release see workfront.com/release.

**Update to Workfront Search**

*Search*

A phased rollout began this week to update the infrastructure for the Workfront Search functionality. The update will make future improvements to Search easier and more reliable. With these changes, items added to Workfront will be indexed more quickly and therefore will return in search results sooner.

The phased rollout will continue for 2 weeks.

+++

+++**Workfront Fusion Maintenance Update on February 18, 2022**

**Field value type validation added to Anaplan list items properties**

*Adobe Workfront Fusion*

An issue has been fixed that allowed users to put the incorrect data type into fields for List Item properties. Validation of the property type allows Fusion to ensure that the correct data type is sent to Anaplan, eliminating errors caused by incorrect data types.

+++

+++**Maintenance Update on February 17, 2022**

**Error when deleting predecessor from Predecessors tab**

*Tasks*

When a user attempts to delete a predecessor from the Predecessors tab on a task, the task does not delete, and the user sees the following error: 

Task with primary key value(s) "" not found

**Whoops error when opening users page**

*Users*

When a user attempts to open the Users page, the page does not open and the user sees the following error: 

Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.

**Overlapping elements in the header of a report on a dashboard**

*Dashboards*

When a user views a report on a dashboard, they see that the groupings icon and label overlaps the links to Details and Summary. 

**Issues with "More" menu for documents and proofs**

*Documents*

When a user selects a document or proof on a Workfront Classic document list, then clicks "More," they may see one of the following issues:
The button is unresponsive
All options under the button are labeled "object Object" and cannot be used.

**"You must be a system admin" error when creating a project**

*Projects*

When a user who is not an administrator attempts to create a project, and attaches a custom form that has a section available only to administrators, they cannot create the project and they see the following error:

"You must be a system admin to change this custom data parameter value"

**Data in admin-only section of custom form is not preserved when converting issues to projects**

*Projects*

When a user converts an issue to a project using a template that has a custom form with an admin-only section, any data in the admin-only section is not carried over to the new project. This occurs even if an admin is converting the issue.

+++

+++**Maintenance Update on February 10, 2022**

**"You must be a system admin" error when creating a project**

*Projects*

When a user who is not an administrator attempts to create a project, and attaches a custom form that has a section available only to administrators, they cannot create the project and they see the following error:

"You must be a system admin to change this custom data parameter value"

**Users who have been deactivated and reactivated do not appear in Proof contacts**

*Proof*

When a user views their contacts list in Proof, users who have been deactivated and reactivated do not appear in the list.

**"Something went wrong" message when converting an issue to a project using a template**

*Projects*

When a user who is not an admin attempts to convert an issue to a project using a template, custom form fields that are visible only to admins show the following message:

"Something went wrong, could not load form"

**"Cannot load page content" error when viewing project preferences**

*Setup*

When an admin user attempts to view projects, tasks, or issues under Project Preferences in the Setup area, the page does not load and the user sees the following error:

"Cannot load page content. Please try refreshing the page."

+++

+++**Maintenance Update on February 3, 2022**

**BizContext error when logging in**

*Login*

When a user is attempting to log in to Workfront, the login is unsuccessful, and the following message displays:

"Let's try that again.
Database error: BizContext commit failed!"

This has been reported in the Preview environment.

**Issue update stream disappears if issue is pending approval**

*Updates*

When a user clicks into the New update box in the update stream of an issue that is pending approval, the entire update stream disappears.

**Error when uploading new version of a document**

*Documents*

When a user attempts to upload a new version of a document, the new version does not upload and the user sees one of the following errors: 

* documentID cannot be null
* Error: Invalid Parameter: documentID value "undefined"

**Public link for document leads to blank page**

*Documents*

When a user attempts to open a document using a public link, the link leads to a blank page. This occurs when the link is opened in a window where an active Workfront session is open.

**List controls do not work on reports in dashboards**

Das*hboards

When a user is viewing a report in a dashboard and attempts to change the filter, grouping, or view of the report, the filter, grouping, or view does not change.

**"You must be a system admin" error when creating a project**

*Projects*

When a user who is not an administrator attempts to create a project, and attaches a custom form that has a section available only to administrators, they cannot create the project and they see the following error:

"You must be a system admin to change this custom data parameter value"

**Custom data not preserved when converting issue to project**

*Projects*

When a user converts an issue to a project using a template, data from a custom form on the issue is not transferred to the comparable custom form on the project. This happens to data that is in custom fields that may be hidden based on the values of other custom fields.

**Error when converting issue to project**

*Projects*

When a user attempts to convert an issue to a project, the issue does not convert and they see the following error:

"An unexpected error occurred"

+++


## Updates in January 2022

+++**Maintenance Update on January 27, 2022**

+++

+++**Maintenance Update on January 20, 2022**

+++

+++**Workfront Fusion Maintenance Update on January 14, 2022**

+++

+++**Maintenance Update on January 13, 2022**

+++

+++**Maintenance Update on January 6, 2022**

+++

## Previous maintenance updates

Information regarding previous maintenance updates is available here:

* [Workfront Maintenance Updates Archive - 2021](2021-updates.md)
