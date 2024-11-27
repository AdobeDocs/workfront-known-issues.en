---
title: 'Workfront: ZScaler settings can cause reduced performance'
description: ZScaler's web service uses http/1.1 by default, which can cause reduced performance in Workfront.
hidefromtoc: yes
feature: System Setup and Administration
exl-id: 35588d30-3290-4522-b66f-a38a1f0d7237
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
