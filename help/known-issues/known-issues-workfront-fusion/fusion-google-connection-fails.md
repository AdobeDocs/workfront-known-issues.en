---
title: 'Workfront Fusion: Cannot create connection to Google'
description: When a user attempts to create a connection in any of the Google connectors (such as Google Sheets or Google Drive), the connection is not created and the user sees various error messages.
hidefromtoc: yes
exl-id: 068793be-63e5-40b5-bf10-c01d76c1b6e7
---
# [!DNL Workfront Fusion]: Cannot create connection to [!DNL Google]

When a user attempts to create a connection in any of the [!DNL Google] connectors (such as [!DNL Google Sheets] or [!DNL Google Drive]), they see a window open with the following error:

```
"detail": "Unexpected token � in JSON at position 0",
"message": "Bad Request",
"code": "SC400",
"suberrors": []
```

When the user closes this window, the connection fails with the following error inside [!DNL Fusion]:

"[!UICONTROL Error: The request failed due to the failure of a prevoius request. No access token specified.]"

_First reported on November 21, 2022._
