---
title: 'Workfront: ZScaler settings can cause reduced performance'
description: ZScaler's web service uses http/1.1 by default, which can cause reduced performance in Workfront.
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: d5896d07-2812-5418-8b18-8957a0d7f0fb
    internal-label: System Setup and Administration
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Workfront: ZScaler settings can cause reduced performance

>[!NOTE]
>
>This is an issue with ZScaler, and will not be fixed by Workfront.

ZScaler's web service uses `http/1.1` by default, which can cause reduced performance in Workfront.

**Workaround**

Configure your ZScaler software to use `http/2`. This cannot be configured in Workfront.

You can find information about `http/2` in the ZScaler documentation.

_First reported on November 18, 2024._
