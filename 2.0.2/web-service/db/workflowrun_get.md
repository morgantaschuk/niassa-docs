---
title: GET a workflow run
uri: /workflowruns/(workflowRunSWID)
method: GET
summary: Retrieves a workflow run by SWID
layout: page
www-bit: db
---

{% include_relative resource-template.md summary=page.summary method=page.method uri=page.uri %}


* show
: lanes - return the workflow run with all of its lanes
: ius - return the workflow run with all of its IUSes
: processes - return the workflow run with all of its processing events
