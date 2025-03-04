---
title: "Integrations: outlookIdentityToken error when using Workfront for Outlook"
description: "When a user is using the Workfront for Outlook integration, they may see an error."
hidefromtoc: yes
feature: Workfront Integrations and Apps
---

# Integrations: outlookIdentityToken error when using Workfront for Outlook

When a user is using the Workfront for Outlook integration, they may see the following error:

```
Unexpected error
Unable to get the outlookIdentityToken
```

**Workaround**


To resolve this error, you must enable Microsoft 365 legacy tokens for for your organization. Because this must be done in Microsoft 365, Workfront cannot enable these tokens for your organization.

For instructions on enabling Microsoft 365 legacy tokens, see [Turn legacy Exchange Online tokens on or off](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/turn-exchange-tokens-on-off) in the Microsoft documentation.

For more information on legacy tokens, see [Can I turn Exchange Online legacy tokens back on?](https://learn.microsoft.com/en-us/office/dev/add-ins/outlook/faq-nested-app-auth-outlook-legacy-tokens#can-i-turn-exchange-online-legacy-tokens-back-on) in the Microsoft documentation.


_First reported on March 3, 2025, 2024._
