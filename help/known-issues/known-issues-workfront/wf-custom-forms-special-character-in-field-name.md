---
title: "Custom forms: Cannot use field in calculation if field name contains quotation marks or an apostrophe"
description: "When a user is creating a calcualted field expression, and attempts to include a typeahead field that has a name with an apostrophe or quotation mark, the calculation is not accepted, and the user sees the message This is an invalid custom expression, please try again."
hidefromtoc: yes
---

# Custom forms: Cannot use field in calculation if field name contains apostrophes or quotation marks

When a user is creating a calculated field expression, and attempts to include a typeahead field that has a name with a `'` or `"`, the calculation is not accepted, and the user sees the message "[!UICONTROL This is an invalid custom expression, please try again.]"

This issue exists only with typeahead fields. Text fields with `'` or `"` in the name can be used in calculated field expressions with no issue.

_First reported on November 10, 2022._

