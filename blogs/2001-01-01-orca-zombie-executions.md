---
title: "Orca: Zombie Executions"
url: "/docs/guides/runbooks/orca-zombie-executions/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Aliases: orphaned execution A zombie Execution is one that has a status in the database of RUNNING but there are no messages in Orca’s work queue or unacked set—the pipeline or task is not doing anything. Diagnosis Logs will be emitted regularly for Executions that are currently running in Orca via the QueueProcessor class, which will look similar to the following example. If no logs have been emitted for over 10 minutes for a RUNNING Execution, it is very likely a zombie.
