---
title: Workfront Maintenance Updates
description: Maintenance Updates for [!DNL Adobe Workfront]
exl-id: 886db617-4120-4577-968a-052d2acf3454
feature: Get Started with Workfront
---
# [!DNL Workfront] Maintenance Updates

The following maintenance updates have been made in 2024.

>[!NOTE]
>
>These updates also include other minor or less prominent bug fixes. [!DNL Workfront] Support will notify you when an issue you submitted is fixed.

For maintenance updates prior to 2024, see [Previous Maintenance Updates](#previous-maintenance-updates)

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
