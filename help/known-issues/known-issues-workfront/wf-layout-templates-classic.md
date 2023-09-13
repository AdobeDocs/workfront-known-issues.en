---
title: "Layout templates: Layout templates causing inconsistencies in reports"
description: "Layout templates from the Classic Workfront experience are not longer available in the Workfront interface, but may still affect Workfront data. This can cause inconsistencies in fields affected by layout templates (such as Shared with) on reports or dashboards."
hidefromtoc: yes
feature: System Setup and Administration
---

# Layout templates: Layout templates causing inconsistencies in reports

Layout templates from the Classic [!DNL Workfront] experience are not longer available in the [!DNL Workfront] interface, but may still affect [!DNL Workfront] data. This can cause inconsistencies in fields affected by layout templates (such as [!UICONTROL Shared with]) on reports or dashboards.

**Workaround**

Delete the Classic layout templates using an API call. You must be logged into Workfront.

>[!NOTE]
>
>Global and System layout templates cannot be deleted.

1. Locate the layout template you want to delete using the following API call:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL/search`
1. Make note of the ID of the layout template you want to delete. 
1. Locate your session ID using the following API call:
   `https://{yourDomain}.com/attask/api/v16.0/session`

   >[!IMPORTANT]
   >
   >Never share your session ID with anyone. 

1. Insert the layout template ID and the session ID into the following API call:
   `https://{yourDomain}.com/attask/api/v16.0/LYTMPL?ID={layoutTemplateID}&method=delete&sessionID={yourSessionID}`
1. Paste the API call from step 4 into the URL bar of your browser and press Enter.

   This deletes the layout template.

