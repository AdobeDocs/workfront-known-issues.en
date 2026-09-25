---
title: 'Workfront Proof: 500 error when accessing Workfront Proof through API or Workfront Fusion'
description: 'When a user accesses the Proof API getAllProofs action, the Workfront Proof server returns the  message: 500 Internal Server Error'
feature: Workfront Proof
exl-id: 3c968354-58e2-43fc-8c27-2670683ac862
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: e14a7f57-c82c-4874-a495-5d036cbbdc3d
    internal-label: Resource management
subfeature_v2:
  - id: b18b693b-6d59-4359-95fd-a386b7a615fe
    internal-label: Workfront Proof
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# [!DNL Workfront Proof]: 500 error when accessing [!DNL Workfront Proof] through API or [!DNL Workfront Fusion]

>[!NOTE]
>
>The Product team is currently evaluating this issue resolution, which might require product enhancements. Product enhancements are communicated in the Product Announcements and not with the Maintenance Updates.

<!--This article is on Proof and Fusion TOCs-->

When a user accesses the [!DNL Workfront Proof] API [!UICONTROL `getAllProofs`] action, the server returns the following message:

[!UICONTROL 500 Internal Server Error]

Because [!DNL Workfront Fusion] uses the [!DNL Workfront Proof] API for [!DNL Workfront Proof] modules, this error may be returned to a module, halting a scenario.

_First reported on April 28, 2023._
