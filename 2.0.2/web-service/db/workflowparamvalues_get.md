---
title: GET /workflowparamvalues
uri: /workflowparamvalues
method: GET
summary: Retrieves a list of workflow parameter values.
layout: page
www-bit: db
---

{% include_relative resource-template.md summary=page.summary method=page.method uri=page.uri %}


* id
: Returns the WorkflowParamValue with the given id (primary key, not SWID, since workflow parameter values do not have SWIDs).
