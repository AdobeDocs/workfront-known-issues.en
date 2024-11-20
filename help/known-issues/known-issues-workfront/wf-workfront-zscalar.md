---
title: "Workfront: ZScalar settings can cause reduced performance"
description: "ZScalar's web service uses http/1.1 by default, which can cause reduced performance in Workfront."
hidefromtoc: yes
feature: System Setup and Administration
---

# Workfront: ZScalar settings can cause reduced performance

>[!NOTE]
>
>This is an issue with ZScalar, and will not be fixed by Workfront.

ZScalar's web service uses `http/1.1` by default, which can cause reduced performance in Workfront.

**Workaround**

Configure your ZScalar software to use `http/2`. This cannot be configured in Workfront.

You can find information about `http/2` in the ZScalar documentation.

_First reported on November 18, 2024._
