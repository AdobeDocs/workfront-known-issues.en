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

+++

+++**Maintenance Update (Hot Fix) on March 29, 2022**

+++

+++**Maintenance Update on March 24, 2022**

+++

+++**Maintenance Update on March 17, 2022**

+++

+++**Maintenance Update (Hot Fix) on March 14, 2022**

+++

+++**Maintenance Update on March 10, 2022**

+++

+++**Maintenance Update on March 3, 2022**

+++


## Updates in February 2022

+++**Maintenance Update (Hot Fix) on February 24, 2022**

+++

+++**Maintenance Update on February 24, 2022**

+++

+++**Workfront Fusion Maintenance Update on February 18, 2022**

+++

+++**Maintenance Update on February 17, 2022**

+++

+++**Maintenance Update on February 10, 2022**

+++

+++**Maintenance Update on February 3, 2022**

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
