---
title: Workfront Maintenance Updates in 2024
description: Maintenance Updates for [!DNL Adobe Workfront]
feature: Get Started with Workfront
exl-id: 8a8ade95-d940-4773-8032-724bc2d8301e
---
# [!DNL Workfront] Maintenance Updates

>[!NOTE] 
>
>For information about maintenance outages for all Adobe products, including Workfront, see the [Adobe Status page](https://status.adobe.com/).

This page describes the issues fixed in the weekly Workfront updates.

These updates also include other minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

For maintenance updates prior to 2024, see [Previous Maintenance Updates](#previous-maintenance-updates)

The following maintenance updates have been made in 2024.

## Updates in December 2024

+++**Maintenance Update on December 19, 2024**

### Maintenance Update on December 19, 2024

This update includes only minor or less prominent bug fixes. Workfront Support will notify you when an issue you submitted is fixed.

+++

+++**Maintenance Update on December 12, 2024**

### Maintenance Update on December 12, 2024

#### Dashboards

**Column disappears when used for sorting in a dashboard report**

When sorting a report placed in a dashboard by a column, the column disappears and the content is not sorted.

#### Reports

**Group column under chart option causes error**

When enabling the "Group column under chart" option in a report with a chart, the following error message displays: "An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."

**Bulk Edit and Delete icons missing from reports**

When attempting to edit or delete multiple report items in bulk, the Edit and Deletes icons occasionally do not appear.

**Errors in Project (Financial Data) reports**

A whoops error appears intermittently for Project (Financial Data) reports, in both the details page and the matrix page.

As part of correcting this issue, projects in this report type are no longer automatically recalculated before loading the data. Users must manually recalculate the finances on individual projects to update the data in a financial data report.

+++

+++**Maintenance Update on December 5, 2024**

### Maintenance Update on December 5, 2024

#### Custom forms

**Cannot add "estimateByHours" or "hoursPerPoint" task fields**

When a user attempts to add the fields "estimateByHours" or "hoursPerPoint" to a custom form in the form builder, an error message is displayed: "This is an invalid custom expression, please try again."

**Display logic not working in custom forms**

When a user is enter information into a custom form with display logic, fields that should appear based on the display logic do not appear.

#### Home

**Contributors shown nonfunctional "Work on it" button**

Contributor users have access to a nonfunctional "Work on it" button in the My Work widget in Home.

#### Reports

**Custom quarters do not appear in report prompts**

When a user is running a report with a date-based prompt, customized quarters do not appear in the list of selections for the prompt.

+++

## Updates in November 2024

+++**Maintenance Update on November 28, 2024**

### Maintenance Update on November 28, 2024

#### Projects

**Cannot share projects due to "access to delete" error**

When attempting to share a project, the user receives an error: "You do no have sufficient access to delete this project". This occurs despite the user not trying to delete the project, as well as the user being the Project Owner and having Sharing and Manage access to the project.

#### Reports

**Category Name field not linking to custom form**

When viewing a list in a report containing a Category Name field, the contents of the Category Name column cannot be clicked to open the corresponding custom form.

**Group custom colors in reports not working**

When assigning a custom color to a group in the report builder, the color selection does not appear when running the report.

**Long load times for reports**

Reports take an extended amount of time to load. This affects viewing reports, and editing and creating reports in the report builder.

**Time field missing for calculated Date/Time fields in report prompts**

When running a report has a custom Date/Time field used as a prompt, the time selection field is missing from the prompt interface.

**Unable to view shared reports/dashboards**

When a user attempts to access a report or dashboard that has been shared with them, the report or dashboard cannot be accessed.

#### Timesheets

**Contributor users have a "Submit for approval" button**

Despite being unable to enter hours in timesheets, users with the Contributor access level have a "Submit for approval" button that they can click.

+++

+++**Maintenance Update on November 21, 2024**

### Maintenance Update on November 21, 2024

#### Dashboards

**Cannot interact with bar chart report bars in dashboards**

When attempting to click or mouseover a bar in a bar chart report within a dashboard, the details menu does not open or no tooltip is displayed, respectively.

#### Projects

**Projects fail to load**

When navigating to a project, the page occasionally fails to load any content.

#### Reports

**Bulk editing in chart lists is unresponsive**

When a user is viewing a chart in a report and selects multiple items in the list to bulk edit, the cursor disappears and the text boxes for the bulk edit become unresponsive.

**Edit and Delete buttons unresponsive in timesheet reports**

When attempting to click the Edit or Delete icons in a timesheet report, there is no response.

**Reports containing typeahead fields fail to load**

When opening a report that contains custom typeahead fields, the report occasionally fails to load and displays an error message.

+++

+++**Maintenance Update on November 14, 2024**

### Maintenance Update on November 14, 2024

#### Home

**To-Do widget errors for new and completed to-dos**

When attempting to create a new to-do or completing an existing one in the Home To-Do widget, users encounter an error and are unable to create or complete the to-do.

#### Users

**"Send invite emails to these people" checkbox missing**

When importing new users into Workfront, the "Send invite emails to these people" checkbox is missing from the dialog window.

+++

+++**Maintenance Update on November 7, 2024**

### Maintenance Update on November 7, 2024

This update includes only minor or less prominent bug fixes. Workfront Support will notify you when an issue you submitted is fixed.

+++

## Updates in October 2024

+++**Maintenance Update on October 31, 2024**

### Maintenance Update on October 31, 2024

This update includes only minor or less prominent bug fixes. Workfront Support will notify you when an issue you submitted is fixed.

+++

+++**Maintenance Update on October 24, 2024**

### Maintenance Update on October 24, 2024

#### Assignments

**Time off icon does not appear when assigning tasks**

When a user is assigning a task and begins typing the name of the assignee who has time off scheduled during the task, the user icons under the Suggested Assignments area do not display the time off (airplane) icon. If the user continues typing so that the name displays under the Users and Teams area, the icon does display.

#### Custom forms 

**Cannot update custom data in completed projects**

When a user attempts to update custom data in a project that is complete, they cannot update the data, and they see the following message:

"Unable to complete operation for a project of status Complete."

#### Projects

**Cannot add issues to completed project**

When a user attempts to add an issue to a project in Complete status, the user cannot add the issue. This may occur even though the "Add and Edit Issues" option is enabled

**Gantt chart is not accurate**

When a user views the Gantt chart and switches views, the Gantt chart does not show accurate data, or may not show any data. 

+++

+++**Maintenance Update on October 17, 2024**

### Maintenance Update on October 17, 2024

#### Proofs

**Proofs show inaccurate date**

Dates listed in the documents list are showing the date that the first version of the document was created, instead of the date the newest version was created.

#### Timesheets

When a user attempts to log time on a timesheet that is in Submitted or Closed status, they cannot log the time. 

This is the expected behavior, and should not be considered an issue.

Previously, users were able to log time on submitted or closed timesheets through the Workfront API or Workfront Fusion.

+++

+++**Maintenance Update on October 10, 2024**

### Maintenance Update on October 10, 2024

#### Boards

**Error when moving cards or assigning users**

When moving cards or assigning users, occasionally the action does not go through and instead produces the error "Response not successful: Received status code 502" after a delay.

**Error when loading a board**

When a user attempts to load a board, the board does not load, and the user sees the following message:

"Error loading board"

"Something went wrong while loading this board. Refresh the page to try again, or contact support with the error ID below if the problem persists."

#### Home

**"Mark as Done" closes the summary pane for My Issues widget**

When attempting to use the "Mark as Done" button in the summary pane of an issue opened through the My Issues widget, the summary pane unexpectedly closes.

**Layout Template widget settings fails to add column**

When selecting a field to add to a widget through Layout Template widget settings, a field can be selected but the corresponding column does not appear in the widget.

#### Tasks

**Issues with timeline recalculation**

The following issues have been reported regarding timeline recalculation:

* When updating the duration of a timeline task, the system takes a significant amount of time to recalculate. 
* When the recalculation is complete, the dates may remain disabled or become disabled, as if the timeline is still recalculating.

**Task expenses not displayed**

After adding an expense to a task, the expense dose not appear in the task information despite API confirmation it was entered.

+++

+++**Maintenance Update on October 3, 2024**

### Maintenance Update on October 3, 2024

#### Boards

**Archived connected cards not synced**

To address performance issues, connected cards that are archived are no longer synced. Changes made to the Workfront task or issue are not reflected on the archived cards. If you restore a card, it will sync again.

#### Custom forms

**Display type conversions error on custom forms**

Rich text fields are causing the following error to appear on custom forms:

"Error: Display Type conversions between Text to Rich Text are not allowed."

This can occur in the following conditions:

* The user begins to edit the forms but clicks Apply without making any changes.
* The user is creating a custom form.

In both cases, rich text fields are causing the issues.

#### Notifications

**Contributor users do not receive email notifications**

Users with a Contributor license are not receiving notification emails. This can affect both instant notification emails and Daily Digest emails.

#### Proofs

**Electronic signatures cannot be added when using SSO for Proof**

When using SSO to log into Proof, users cannot set a proof to require electronic signatures.

+++

## Updates in September 2024

+++**Maintenance Update on September 26, 2024**

### Maintenance Update on September 26, 2024

#### Agile

**Add to Iteration option listed twice when assigning scrum team**

When assigning a task or issue to an agile scrum team, the "Add to Iteration" option appears twice in the More menu. This does not impact the ability to assign the team, and does not appear for non-scrum agile teams. 

#### Custom Forms

**Calculation Editor field list limited to 200 items**

In the Calculation Editor for calculated fields on custom forms, the field list for an object is now limited to 200 items to improve system performance. If you know the field name, you can search for it using the typeahead option instead of scrolling through the list.

#### Reports

**Report deliveries are delayed or missing**

Reports with scheduled deliveries are not being delivered as expected. They may be late, or they may not be delivered at all. 

+++

+++**Maintenance Update on September 19, 2024**

### Maintenance Update on September 19, 2024

#### Dashboards

**Selecting Export button in a report scrolls to top of page**

When clicking the Export button for a report in a dashboard, the window scrolls to the top of the page and requires scrolling back down to find the opened export options menu. 

+++

+++**Maintenance Update on September 12, 2024**

### Maintenance Update on September 12, 2024

#### Integrations

**Error when creating a request from Outlook**

When a user attempts to create a request from the Workfront for Outlook integration, and adds an attachment. The user sees the message "Something went wrong. Try again later."

The request is created, and there is a folder for email attachments in the request, but the folder is empty, and the attachment was not added to the request.

+++

+++**Maintenance Update on September 5, 2024**

### Maintenance Update on September 5, 2024

#### Groups

**Subgroups do not display correctly**

When a user is viewing the Groups list in the Setup area, they see that subgroups are not listed correctly under the parent group. The subgroup is correctly saved under the parent group, but the list may cause confusion.

If the user opens the subgroup, they can see in the breadcrumbs that the subgroup is saved correctly under the parent group.

#### Users

**Cannot reactivate user**

When a user attempts to reactivate a user using the "Reactivate user" option in the More menu, they can select an access level for the user, but the change is not save. Instead, the user sees the following error:

"homeGroupID cannot be null"

+++

## Updates in August 2024

+++**Maintenance Update on August 29, 2024**

### Maintenance Update on August 29, 2024

#### Custom forms

**Forms defaults to Project forms**

When a user is creating a custom form and selects an object type for the form, the object type is ignored, and the form is created as a Project custom form.

#### Documents

**Clicking a document name leads to blank page**

When a user attempts to view document details by clicking the document's name in a document list, the list disappears, and the user is not directed to the document details.

#### Home

**Pending approvals widget shows deleted documents**

When a user is viewing their Home Pending approvals widget, they see documents that have been deleted. If the user clicks on one of these documents, they are taken to a blank page.

#### Users

**The user profile Email Locale field has been disabled**

For organizations on IMS, language preferences are stored in each user's Adobe Experience Cloud profile. The Email Locale field in the Workfront user profile has been disabled (for IMS organizations only) and a tooltip on that field provides instructions on how to access language settings in the Adobe profile.

This addresses an issue that when an admin attempts to change the Email locale setting for a user, it reverts to English.

+++

+++**Maintenance Update on August 22, 2024**

### Maintenance Update on August 22, 2024

#### Reports

**Cannot click on a report from Custom Fields area of Setup**

When a user is viewing the Custom Forms > Fields area of setup, and the view includes the native Reports field, links to the reports are not working. The user should be able to click on the name of a report and be taken to the report, but clicking the name of the report is ineffective.

+++

+++**Maintenance Update on August 15, 2024**

### Maintenance Update on August 15, 2024

#### Boards

**Issues regarding duplicate cards**

The following issues have been reported regarding duplicate cards in Boards:

* A card displays twice. This may be resolved by refreshing the page.
* If a user deletes one of the duplicate cards, all instances of that duplicated card are deleted.

#### Notifications

**Whoops error when setting notification preferences**

When a user attempts to view notification preferences, they see the following error:

"[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"

This has been reported in the following areas:

* Notification settings on a user profile
* Event Notifications area in Setup

#### Projects

**Currency symbol is incorrect when exporting** 

When a user exports an issue, the currency symbol in the export does not match the currency set in the project or the issue.

#### Proofs

**Proof markups are inaccurate**

Proof markups are misaligned on PDF printouts received via email from the Proof Print feature.


+++

+++**Maintenance Update on August 8, 2024**

### Maintenance Update on August 8, 2024

#### Boards

**Card does not include subtasks**

When a user is viewing a card for a task that is a parent task, the subtasks of that parent task do not display on the card. Instead, the card shows that there are 0 subtasks.

### Reports

**Report deliveries are delayed or missing**

Reports with scheduled deliveries are not being delivered as expected. They may be late, or they may not be delivered at all.

#### Setup

**"Log in as" leads to blank screen**

When an admin logs in as another user, instead of seeing that user's account, the admin sees a blank screen.

+++

+++**Maintenance Update on August 1, 2024**

### Maintenance Update on August 1, 2024

#### Documents

**Cannot create view for Documents list**

When a user attempts to create a new view on a Documents list, the screen goes blank, and the user cannot create the view. 

Existing views work as expected.

#### Integrations

**Issues with Dropbox integration**

The following issues have been reported regarding the Dropbox integration:

* When a user attempts to search for a file in the Dropbox file selector, they see an authorization error message, and the file selector does not retrieve the file from Dropbox.
* When a user attempts to open a linked folder, the user sees an error stating that the files or folder no longer exist in Dropbox.

These issues are due to issues with Dropbox, not Workfront.

+++

## Updates in July 2024

+++**Maintenance Update on July 25, 2024**

### Maintenance Update on July 25, 2024

#### Custom forms

**Dropdown closes when selecting multiple values**

When a user attempts to select multiple values on a custom form field, the dropdown closes after the first value is selected. 

This occurs when the field is associated with display logic in the custom form.

#### Notifications

**Thumbnails not visible in email notifications**

When a user views an email notification regarding a document approval, the document thumbnail is not visible in the email.

This has been reported in Gmail.

+++

+++**Maintenance Update on July 18, 2024**

### Maintenance Update on July 18, 2024

#### Agile

**Story board goes blank when adding a subtask**

When a user attempts to add a subtask to a story board while a filter is selected, the screen goes blank, and the user cannot add the subtask.

#### Home

**Cannot open items from [!UICONTROL Home Calendar] or [!UICONTROL Work List]**

When a user attempts to open a work item or proof from their [!UICONTROL Home Calendar] or [!UICONTROL Home Work List], the item does not open.

**Admin's own Home displays when logged in as another user**

When an admin is logged in as another user and views that user's Home, the admin's own Home displays.

#### Proofs

**Closing a proof leads to Product Documents page**

When a user is viewing a proof and closes the proof, the user is directed to the Project Documents page instead of the page that the proof was opened from.

#### Workfront

**Custom terminology is not applied**

Custom terminology set in the layout template does not appear in some areas of Workfront. Instead, the default non-custom terminology appears. 

This has been reported in the following areas:

* Menu tabs
* Page headers
* Descriptions where projects are listed


+++

+++**Maintenance Update on July 11, 2024**

### Maintenance Update on July 11, 2024

#### Issues

**Error when making an advanced assignment to an issue**

When a user attempts to make an advanced assignment to an issue in Workfront, the issue is not assigned, and the user sees the following error message:

"[!UICONTROL APIModel INTERNAL does not support field duration (OpTask)]"

#### Reports

**Whoops error when setting matrix settings on Hour report**

When a user attempts to set the matrix settings on an Hour report, they cannot set the settings, and they see the following error:

* "[!UICONTROL Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it.]"


+++

+++**Maintenance Update on July 4, 2024**

### Maintenance Update on July 4, 2024

#### Home

**Three dot menu is ineffective**

When a user clicks the three-dot More menu in the legacy Home Worlkist, no action is triggered.

#### Reports

**"No data to display" when grouping name has forward or back slash**

When a user is viewing a chart in a report and clicks a grouping on the chart, and that grouping has a / or \ in the name, the details that open do not display the items in the grouping, and the user sees a "No data to display" message.

#### Tasks

**Job role does not disappear from list when user is assigned to task**

When a job role is assigned to a task, and that task is assigned to a user that has the job role, the job role does not disappear from the list of assignments.


+++

## Updates in June 2024

+++**Maintenance Update on June 27, 2024**

### Maintenance Update on June 27, 2024

#### Boards

**Only board owner can update configuration filters**

For security reasons, only the owner of a board can change the board filters in the Configure panel.

#### Reports

**Report does not load when default currency is USD**

When a user attempts to view a report that has the default currency as USD, the report does not load.

#### Updates

**Copied link does not paste correctly**

If a user copies a link from an update by right-clicking and selecting "[!UICONTROL Copy link address]", then pastes the link in an update, the link does not paste correctly. Only the first part of the link is a link, and the rest of the URL is ignored.

Copying the link using a method other "[!UICONTROL Copy link address]" allows the link to paste as expected.

+++

+++**Maintenance Update on June 20, 2024**

### Maintenance Update on June 20, 2024

#### Navigation

**Back button does not go back to previous page**

When a user in Workfront clicks the Back button of their browser, one of the following may occur.

* The name of the browser tab changes, but the page does not change. Clicking the back button again may resolve the issue.
* The user is taken to their browser landing page.

#### Proofs

**Cannot close proof viewer**

When a user is viewing a proof in the proofing viewer and attempts to close the proof by clicking the X in the upper-right corner, the proof does not close.

+++

+++**Maintenance Update on June 13, 2024**

### **Maintenance Update on June 13, 2024**

#### Groups

**Cannot add subgroup**

When a user attempts to add an existing subgroup to a group, the Save button is ineffective, and the subgroup is not added.

+++

+++ **Maintenance Update on June 6, 2024**

### Maintenance Update on June 6, 2024

#### Custom forms

**Limitation on native fields in the form designer**

Multiple native fields are now supported on custom forms created in the form designer. Previously the limit was one native field per form.

+++

## Updates in May 2024

+++ **Maintenance Update on May 30, 2024**

### Maintenance Update on May 30, 2024

#### Custom forms

Error when editing descriptive text fields

When a user attempts to edit the descriptive text on a custom form, the text does not save, and the user sees the following error:

"Duplicate key value violates unique constraint"

This has been reported in the legacy form builder.

#### Updates

**Copying and pasting a mention does not notify the mentioned user**

When a user copies a comment that includes a mention in @ format, then pastes that comment into the Updates area of another object, the mentioned user is not notified about the pasted comment.

+++

+++ **Maintenance Update on May 23, 2024**

### Maintenance Update on May 23, 2024

#### Reports

When a user is viewing a report and clicks the browser's Back button, one of the following may occur:

* The user remains on the Report page.
* The user is directed to the browser's landing page.
* The user is directed to the Login page.

This has been reported with the Chrome browser.

#### Updates

**Tagged user cannot see who tagged them**

When a user is tagged in an update, they cannot see who tagged them. This occurs when the setting "People in other companies should only view users from..." is set to "Their company." 

**Tagging a user with @ in Summary panel is ineffective**

When a user attempts to tag another user by using @ in the Updates area of a Summary panel, clicking on the user's name in the dropdown is ineffective. Attempting to tag the user a second time works as expected.

+++

+++**Maintenance Update on May 16, 2024**

### Maintenance Update on May 16, 2024

#### Setup

**Default issue statuses missing from some issue types in Setup**

When a user is viewing issue statuses in Setup, they see that the default statuses for issues (New, In Progress, and Complete) are missing from some types of issues. Default statuses do not have the option to change the issue type, so the user cannot reconfigure the statuses to display for the affected issue types. 

#### Users

**Cannot delete users**

When a user attempts to delete users, the users are not deleted. This has been reported in organizations that have migrated to the Adobe Admin Console.

+++

+++**Maintenance Update on May 9, 2024**

### Maintenance Update on May 9, 2024

This update includes only minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

+++

+++**Maintenance Update on May 2, 2024**

### Maintenance Update on May 2, 2024

#### Logging time

**Cannot edit hours on tasks or issues**

When a user attempts to edit hours on a task or issue, the changes are not saved.

+++

## Updates in April 2024

+++**Maintenance Update on April 25, 2024**

### Maintenance Update on April 25, 2024

#### Updates

**Numbered lists are not numbered correctly**

When a user submits a comment that includes a numbered list, that list shows incorrect numbering in the update.

This has been reported in the new commenting experience.

**Text is not preserved when navigating away and back to comment**

When a user is writing a comment that includes an @mention, then navigates away from and back to the comment before submitting it, any text that was entered after the @mention is missing from the comment draft.

This has been reported in the new commenting experience.

+++

+++**Maintenance Update on April 18, 2024**

### Maintenance Update on April 18, 2024

#### Agile

**Kanban cards do not display custom fields**

When a user is viewing a Kanban board that has been configured to include custom fields, those custom fields may not display.

#### Calendars

**Error when refreshing calendar**

When a user is viewing a calendar and refreshes the page a "Whoops" error displays. The data on the calendar displays as expected, but may be obscured by the error message.

#### Custom forms

**External lookup fields do not return results**

When an external lookup field references a multi-select field that has only one value selected, the field does not return the value. 

For example, if an external lookup field references a multi-select field that has both "red" and "blue" values selected, the field functions as expected. If the field has only "red" selected, the external lookup field returns no value.

#### Projects

**Cannot convert issue to project if web proof is attached**

When an issue has a web proof attached (a URL proof using a link from an external document provider such as SharePoint), and a user attempts to convert that issue to a project, the conversion fails and the project is not created. The user sees the following error:

"There was a problem copying the file (File GUID). Please remove the file or contact support and try again."

+++

+++**Maintenance Update on April 11, 2024**

### Maintenance Update on April 11, 2024

#### Search

**Cannot edit from Search**

When a user is using Advanced Search and attempts to edit or bulk edit the search results, the Edit icon is unresponsive.

#### Updates

**Preview of image in updates is blurry**

When a user is viewing updates and clicks the magnifying glass on an image to preview the image, the preview that opens is extremely pixelated blurry.

If the user downloads the image, the image appears at the expected resolution.

**"[!UICONTROL We're unable to post your comment]" message when replying**

When a user attempts to reply to a message in the new commenting experience, the reply is not saved and the user sees the following message:

"[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]"

+++

+++**Maintenance Update on April 4, 2024**

### Maintenance Update on April 4, 2024

#### Search

**Cannot edit from Search**

When a user is using Advanced Search and attempts to edit or bulk edit the search results, the Edit icon is unresponsive.

#### Updates

**Preview of image in updates is blurry**

When a user is viewing updates and clicks the magnifying glass on an image to preview the image, the preview that opens is extremely pixelated blurry.

If the user downloads the image, the image appears at the expected resolution.

**"[!UICONTROL We're unable to post your comment]" message when replying**

When a user attempts to reply to a message in the new commenting experience, the reply is not saved and the user sees the following message:

"[!UICONTROL We're unable to post your comment right now. Please wait a moment then try again.]"

+++

+++**Maintenance Update on April 4, 2024**

### Maintenance Update on April 4, 2024

#### Integrations

**Documents not attached when creating a request from [!DNL Outlook]**

When a user creates a request from [!DNL Outlook], the documents attached to the email are not attached to the request.

This has been reported for the following attachment types:

XLS
PDF

#### Logging time

**User cannot log time for current day**

When a user attempts to log time in the Updates area, the current day is greyed out, and the user cannot log time for the current day.

#### Updates

<!--no article-->

**Error when viewing comments**

When a user attempts to view comments in the new commenting experience, they cannot see the comments, and instead see the following error:

"Something went wrong. Please try again later."

The legacy commenting experience works as expected.

+++

## Updates in March 2024

+++**Maintenance Update on March 28, 2024**

### Maintenance Update on March 28, 2024

#### Integrations

**Documents not attached when creating a request from [!DNL Outlook]**

When a user creates a request from [!DNL Outlook], the documents attached to the email are not attached to the request.

This has been reported for the following attachment types:

XLS
PDF

#### Proofs

**Proofs remain on My Approvals widget**

A proof that should disappear from the My Approvals widget remains on the widget. This may occur when multiple users make decisions on a proof at the same time, or one user makes a decision and quickly changes it.

#### Resource Management

**Discrepancy in Budgeted Hours**

Budgeted hours displayed in one of the following areas may not match those displayed in another of these areas:

* Business Case
* Reports
* Resource Budgeting tool

#### Tasks

**Predecessor tooltip does not display task name**

When a user is viewing a task list and hovers over a predecessor icon to get more information, the tooltip that appears does not display the name of the predecessor task.

#### Updates

**Document comments do not appear in updates of parent object**

When a user makes a comment on a document, that comment does not immediately appear in the Updates area of the document's parent object.

This issue has been reported in the new Commenting experience. Comments appear in the legacy commenting experience as expected.

**Tagging a user is ineffective**

When a user is tagged in a comment, that comment is not visible to the tagged user, Also, the tagged user is not notified about the comment, either by email or through an in-app notification.

This has been reported in the legacy commenting experience.

+++

+++**Workfront Fusion Maintenance Update on March 28, 2024**

### Workfront Fusion Maintenance Update on March 28, 2024

**RuntimeError with 200 response from Workfront module**

A Workfront module can return a `RuntimeError [200]` response. The 200 implies a successful response, but the error shows that the request was unsuccessful.

This may occur if the response is extremely long. The data is returned to Fusion, but cannot be processed by Fusion.

+++

+++**Maintenance Update on March 21, 2024**

### Maintenance Update on March 21, 2024

#### Updates

**Large spaces between lines**

When a user types an update with multiple lines using the Return or Enter key, or pastes multiple lines into an update, the update appears as expected. However, if a user then views that update in a report, there are large spaces between the lines.

This has been reported in the new commenting experience.

**Tagging a user with @ is ineffective**

When a user tags another user with @ in a comment, the user is not added to the tagged users area, and does not receive a notification about the comment. 

This fix applies only to the new commenting experience.

+++

+++**Maintenance Update on March 14, 2024**

### Maintenance Update on March 14, 2024

#### Proofs

**Proofs created from linked documents do not have proof template applied**

When a user creates a proof from a linked document, the proof template is not correctly applied, and the proof may be missing information such as the workflow.

This also applies to proofs created through the API and through Workfront Fusion.

#### Users

**Lower access levels not available when creating a user**

When a user is creating another user, only the first user's access level is available to the newly created user. All access levels with lower permissions than those of the creating user should be available to assign to the new user.

+++

+++**Maintenance Update on March 7, 2024**

### Maintenance Update on March 7, 2024

#### Boards

**400 error when adding a task to a board**

When a user is viewing a project and attempts to add a task to a board, the task is not added, and the user sees the following error:

Error: "400: undefined /boards-service/graphql"

#### Home

**Error when inline editing a task in the My Task widget**

When a user attempts to inline edit a task in the My Tasks widget, they see the following error: 

"An error has occurred and we are working to resolve the issue. To continue with your work, try refreshing this browser page."


#### Workload Balancer

**Planned hours are not updated in Workload Balancer**

When the planned hours on a project are updated, they are not updated in the Workload Balancer. This may occur even though the change is accurately reflected in the project.

+++

+++**Workfront Fusion Maintenance Update on March 7, 2024

**Workfront Proof > Watch Proof module times out**

Scenarios that use the Workfront Proof > Watch Proof module may deactivate due to the Watch Proof module timing out.

+++

## Updates in February 2024

+++**Maintenance Update on February 29, 2024**

### Maintenance Update on February 29, 2024

#### Updates

**Updates: Screen goes blank when replying to a user from another company**

When a user attempts to reply to a comment by a user in another company, the screen goes blank.

This is because the user does not have permission to see users from other companies.

+++

+++**Maintenance Update on February 22, 2024**

### Maintenance Update on February 22, 2024

#### Home

**[!UICONTROL Home]: [!UICONTROL Workspace] and pins do not load**

When a user logs in, the following may occur:

* The user's new [!UICONTROL Home Workspace] does not load, and they see the error "[!UICONTROL We are unable to load your Workspace information. Please contact Workfront so we can figure out what went wrong and fix it.]"
* The user's pins do not load, and they see the error "[!UICONTROL Your pins are unavailable because of a system error. Try refreshing your browser to fix the problem.]"

#### Users

**Group administrator cannot set or change a user's access level**

<!--no article-->

When a group administrator attempts to change the access level of a user, one of the following may occur:

* The access level field is disabled.
* The group administrator is unable to choose a lower access level.

#### Workload Balancer

**Label for non-working hours**

The Workload Balancer and personal time off calendar now show "[!UICONTROL Non-working Hours]" for time that a user is taking off. Previously the display showed "[!UICONTROL Working Hours]" for non-working time.

+++

+++**Maintenance Update on February 15, 2024**

### Maintenance Update on February 15, 2024

#### Issues

**Time fields save incorrect time when bulk editing issues**

When a user is bulk editing issues and selects a date and time for a date field and saves, the time that is saved to this field in the issue is not the time that the user selected. Instead, the time appears to be converted to UTC when the user saves.

#### Tasks

**User is unassigned from one or more tasks**

A user may be automatically unassigned from a task that they are assigned to. This may occur for one or more tasks. The unassignment does not display in the System Updates area of the tasks, althout it does display in the Update feeds section of the setup menu. 

#### Updates

**Disabled image option is available when editing a comment**

After a [!DNL Workfront] administrator has disabled the option to add images to comments, that option is not available when creating a comment. However, if a user edits an existing comment, the image option is available.

+++

+++**Maintenance Update on February 8, 2024**

### Maintenance Update on February 8, 2024

#### Boards

**Cannot move a card in a column by using [!UICONTROL Move] options**

When a user attempts to move a card in a column by using the "[!UICONTROL Top of column]" or "[!UICONTROL Bottom of column]" options in the three-dot menu, the card does not move.

**Cards persist when changing iteration**

When a user is viewing an iteration on a board and then changes the iteration, the cards displaying for the new iteration are the cards from an iteration the user was viewing previously.

#### Reports

**"No value" column displays no results**

When a chart report has a "[!DNL No value]" column, the column shows no data, even though data should be present.

#### Resource Management

**Incorrect finance calculations due to Job Role issues**

Hours and finance calculations may be incorrect, showing a cost of 0 even though hours are logged in a job role that has a cost rate. 

This is because Job Roles are automatically creating duplicate rates with no start or end dates. Because they have no start or end dates, they are treated as a value of 0 when finance calculations are run.

+++

+++**Maintenance Update on February 1, 2024**

### Maintenance Update on February 1, 2024

#### Login

**Users using SSO are not redirected to original location when logging in**

When a user is on a page in [!DNL Workfront] and logs in with SSO, when login is complete they are directed to [!UICONTROL Home] instead of the page they were on before logging in.

#### Templates

**Error when copying templates**

When a user attempts to copy a new or existing template, the template does not copy, and the user sees the following error:

"[!UICONTROL ID Cannot be Null]"

+++

## Updates in January 2024

+++**Maintenance Update (Hot Fix) on January 30, 2024**

### Maintenance Update (Hot Fix) on January 30, 2024

#### Reports

**External API field does not show all available values in lists and reports**

Previously, users could see the selected value (and edit the value) for an external lookup field in lists and reports, but would not see the dropdown with the options coming from the API.

Now, when an external lookup custom field is used in a list or report, the dropdown with all options from the external API is available.

+++

+++**Maintenance Update on January 25, 2024**

### Maintenance Update on January 25, 2024

#### Boards

**Cards not moving to appropriate column when status is changed**

When the status of a connected card's linked object is changed directly on the object, the card does not move to the appropriate column. If the object status is changed on the card, or the card is dragged to the new column, the card behaves as expected.

#### Notifications

**Marking notifications as seen does not persist** 

When a user marks their notifications as seen and then navigates to a different page within [!DNL Workfront], the notifications icon still shows the number of unread notifications that existed before the user marked them as seen, and the notifications still list when the user clicks the icon. This continues if the user marks them as seen and navigates to another page or back to the original page.

#### Updates

**Issues with tagging in legacy commenting experience**

When a user is tagged in a comment in the legacy commenting experience, the following issues occur:

* Only the user's first name is present in the comment
* The user's name is not marked with an @ symbol
* The user's name is not blue
* The user's name is not a link to that user's profile

The user does receive an email notification regarding the tag, as expected.

+++

+++**Maintenance Update on January 18, 2024**

### Maintenance Update on January 18, 2024

#### Boards

**Cannot attach a document to a card**

When a user attempts to attach a document to a connected card, the user can select the document to attach, but the document does not appear in the document area of the card, and the document is not attached to the object that the card is connected to.

This has been reported in cards connected to issues.

**Card appears on multiple sprints**

When a user is viewing a sprint on Boards, cards that are in different sprints appear on the board. This issue is intermittent.

**Card doesn't close when using Boards view in a Project**

When a user is viewing the Boards view on a task list in a project, and creates a card, the card does not close or save. This prevents the user from returning to the project.

To close the card, the user must edit the URL to remove "board" and anything to the right of "board."

**Cards persist when changing iteration**

When a user is viewing an iteration on a board and then changes the iteration, the cards displaying for the new iteration are the cards from an iteration the user was viewing previously. 

**Error in [!UICONTROL Comments] section of cards**

When a user is viewing a card and scrolls to the [!UICONTROL Comments], section, comments are not displayed, and the user sees the following error:

"[!UICONTROL Something went wrong. Please try again later.]"

**Issues when viewing subtask status**

The following issues have been reported regarding viewing subtask status on a card in Boards:

* The status is shown as "Select status" even when the task already has a status. This status can be seen when viewing the task directly.
* If the user attempts to select a status, the screen goes blank and must be refreshed.

**"[!UICONTROL You have no access]" when viewing comments on a card**

When a user attempts to view comments on a card that is not connected to a [!DNL Workfront] object, they see the following message: 

"[!UICONTROL You have no access to view comments on this object]"

This may occur even when the user could previously see comments on the card.

#### Custom forms

**Cannot bulk add or bulk remove custom forms on template tasks**

If a user attempts to bulk add or bulk remove a custom form on a template task, the form is not added or removed, and the user sees the following error:

[!UICONTROL Let's try that again. Invalid Parameter: templateID value "XXXXXXXXXXXXXXXX"]

If the user locates the template with the specified GUID, then attempts to add or remove custom forms on the remainder of the template tasks, the error will reoccur using another templateID.

Custom forms can be added or removed on a single template task. This error applies only to bulk addition or removal.

#### Portfolios

**Custom terminology does not apply to group page**

When a user sets custom terminology at the Portfolio level, the terminology does not apply to the group level page.

#### Setup

**Cannot hide optional statuses**

When a user attempts to hide optional statuses on a system and group level, the status is not hidden. If the user views the status, the option to hide the status is not enable, even though the user did enable it and save the changes.

**Default issue statuses missing from some issue types in Setup**

When a user is viewing issue statuses in Setup, they see that the default statuses for issues (New, In Progress, and Complete) are missing from some types of issues. Default statuses do not have the option to change the issue type, so the user cannot reconfigure the statuses to display for the affected issue types. 

#### Teams

**Issues with setting team statuses for [!UICONTROL Done] button** 

The following issues have been reported regarding statuses for the [!UICONTROL Done] button when editing or creating a team:

* Some statuses may be missing from the Done button area of the [!UICONTROL New team] window or the [!UICONTROL Team Settings] area of an existing team.
* If the user attempts to save the team, they may see the error "You must select at least one status in each category."

#### Templates

**Error when attaching template to project**

When a user attempts to attach a template to a project, they receive the following error: 

"Whoops! Something went wrong. Please contact Workfront so we can figure out what went wrong and fix it."

This occurs when the user does not have View permission to a custom form attached to the template.

#### Updates

**Comments do not transfer between old and new experience**

A comment made in the legacy commenting experience may not be visible in the new commenting experience. The reverse may also occur.

+++

+++**Maintenance Update on January 11, 2024**

### Maintenance Update on January 11, 2024

#### Boards

**Completed cards not loading properly on dynamic boards**

Previously, the only way to include completed work on a dynamic board was to load the cards as archived cards. Otherwise, completed cards were not loaded on the board at all. This caused issues with being able to locate cards.

Now, when creating a dynamic board, completed cards are loaded by default as archived cards, but you can select Do not archive completed cards to load all completed cards on the board as visible cards in the Completed column.

+++

## Previous maintenance updates

Information regarding previous maintenance updates is available here:

* [[!DNL Workfront] Maintenance Updates Archive - 2023](2023-updates.md)
* [[!DNL Workfront] Maintenance Updates Archive - 2022](2022-updates.md)
* [[!DNL Workfront] Maintenance Updates Archive - 2021](2021-updates.md)
