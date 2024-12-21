---
title: 'Proofs: Webcapture proofs do not generate'
description: When a user attempts to create a webcapture proof, the proof is not generated successfully.
hidefromtoc: yes
feature: Digital Content and Documents
exl-id: 339c5a0a-cfc8-4cfc-946d-b87d760f9106
---
# Proofs: Webcapture proofs do not generate

>[!NOTE]
>
>This issue has been closed because it is working as designed. See workaround below.

When a user attempts to create a webcapture proof, the proof is not generated successfully.

**Workaround**

This issue is caused by long proof generation times for certain PDF files. To increase the generation timeout from the default 30 seconds, edit the below property in Processing settings on the account level in Proof Admin:

`WebCaptureNavigationTimeout -> 120`

_First reported on October 3, 2024._
