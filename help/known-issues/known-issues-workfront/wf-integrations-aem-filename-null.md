---
title: 'Integrations: Filename is null when sent to AEM via integration'
description: 'When a large file (over 100 MB) is sent to Adobe Experience Manager via the Workfront integration, the filename in AEM is null. '
hidefromtoc: yes
feature: Workfront Integrations and Apps, Digital Content and Documents
exl-id: c2d15424-ae04-414f-9384-a7b083212313
---
# Integrations: Filename is "null" when sent to document integration

When a large file (over 100 MB) is sent to a document provider via a Workfront integration, the filename in the document provider is "null." 

This has been reported with both ZIP and TIF files.

**Workaround**

Do one of the following:

* Map the document name to the title in the document provider.
* Enter the filename directly in the document provider.

_First reported on April 23, 2024._

