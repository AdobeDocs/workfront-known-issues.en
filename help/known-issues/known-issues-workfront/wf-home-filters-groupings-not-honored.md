---
title: 'New Home: Widget filter and grouping defaults do not follow layout template'
description: When a user views the My Projects, My Tasks, or My Issues widget in the new Home experience, the default filter and grouping for that widget are not the default setting in the layout template assigned to that user.
feature: Get Started with Workfront
exl-id: d7038535-98ff-405b-9c2b-d6474dc568c9
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: c042179c-157b-516d-b27c-e3bf303e8567
    internal-label: Get Started with Workfront
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# New [!UICONTROL Home]: Widget filter and grouping defaults do not follow layout template

>[!NOTE]
>
>This issue has been closed because it is working as designed.

When a user views the [!UICONTROL My Projects], [!UICONTROL My Tasks], or [!UICONTROL My Issues] widget in the new [!UICONTROL Home] experience, the default filter and grouping for that widget are not the default setting in the layout template assigned to that user.

**Workaround**:

When using New Home, it's important to remember that user settings (preferences) are prioritized. As a result, if you set a default filter or grouping for a specific widget using a layout template, it may not take effect immediately due to existing user preferences. To apply the new filter or grouping, either you or the user may need to reset the preferences. This can be done by appending `/resetUser` to your URL.

_First reported on January 3 2024._
