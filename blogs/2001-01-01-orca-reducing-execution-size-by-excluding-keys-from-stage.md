---
title: "Orca: Reducing Execution Size by Excluding Keys from Stage Outputs"
url: "/docs/guides/runbooks/orca-reduce-execution-size-stage-outputs/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Overview Every stage in an Orca execution has a context and an outputs map: context is scoped to the stage. It holds whatever the stage’s tasks need in order to do their own work. outputs is promoted to the execution and made visible to downstream stages, so anything a task writes there is stored with the execution and travels with it for the remainder of the pipeline.
