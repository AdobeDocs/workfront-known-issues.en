---
title: 'Portfolios: User cannot set portfolio'
description: Users cannot change portfolios on a project if they do not have access to the portfolio.
feature: Work Management
exl-id: 38ad277a-2087-486c-8715-93e275488697
product_v2:
  - id: c4a86a5d-6562-4fc6-aa00-bfa25833aed9
    internal-label: Workfront
feature_v2:
  - id: a0dacc9f-0e23-495b-8e9f-a77c2e60b40c
    internal-label: Work management
role_v2:
  - id: b69b2659-1057-424e-8fc5-ed9e016dc554
    internal-label: User
---
# Portfolios: User cannot set portfolio

>[!NOTE]
>
>This issue has been closed because it is working as designed.

Users cannot change portfolios on a project if they do not have access to the portfolio.

This has been reported in the following scenarios:

* If a user does not have access to an assigned portfolio on a project, that user is unable to change the portfolio as needed even if they have access to the portfolio they are trying to move the project to.
* When attempting to create a project using a project template, if the user who is creating the project does not have access to the portfolio or program on the template, the project will not be created with those assigned objects, and the project will show as independent (no portfolio or project assignment).

**Workaround**

Admins can give access or make adjustments as needed.

_First reported on June 26, 2024._
