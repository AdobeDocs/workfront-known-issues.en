---
title: 'Documents: 404 error when accessing document linked from SharePoint'
description: When a user attempts to access a document linked through SharePoint, they are taken to a page with a 404 error.
feature: Digital Content and Documents, Workfront Integrations and Apps
exl-id: b86ec92b-a27f-4ec3-acc2-0f0118014760
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a1f87682-0525-5459-aa06-3560bb4c3b2a
    internal-label: Workfront Integrations and Apps
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b70a979b-965d-47a9-a360-e7ec2a19b8c1
    internal-label: Digital content and documents
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Documents: 404 error when accessing document linked from [!DNL SharePoint]

<!--Requested article. This issue is on the WF and WFP TOCs.-->

When a user attempts to access a document linked through [!DNL SharePoint], they are taken to a page with the following error:

"[!UICONTROL Error 404: Page not found. This page isn't available. Try checking the URL or visit a different page.]"

This is a known [!DNL SharePoint] issue that occurs when the site has an "@" symbol in the link.

**Workaround**

[!DNL SharePoint] recommends generating a short URL, and using that for the link.

_First reported on March 14, 2023._
