---
title: "Workfront Fusion: Jira Search module returns an error"
description: "The search module used by the legacy Jira connector may result in an error. A workaround is available"
hidefromtoc: yes
feature: Workfront Fusion
---

# Workfront Fusion: Jira Search module returns an error

>[!NOTE]
>
>This issue is due to a change that Jira made in their product.

The search module used by the legacy Jira connector may result in the following error:

`[410] The requested API has been removed. Please migrate to the /rest/api/3/search/jql API. A full migration guideline is available at https://developer.atlassian.com/changelog/#CHANGE-2046` 

This is due to a deprecation on the Jira side. 

Note that:

* Only the Search module is affected. At this time, other Jira API endpoints used by the Fusion connector are not impacted by this deprecation. 

* Geographic rollout may cause inconsistencies. Atlassian is rolling out this change regionally, which means some Jira Cloud instances may still temporarily support older endpoints. This can lead to inconsistent behavior across environments.  

**Workaround**

If you encounter this error, you can replace the search module of the legacy Jira connector with the search module of the new connector. Note that the new connector allows you to select the API version used. Be sure to select **V3** in the **API Version** field when creating the connection.

_First reported on September 15, 2025._

