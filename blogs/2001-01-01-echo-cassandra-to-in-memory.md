---
title: "Echo: Cassandra to In-Memory"
url: "/docs/guides/operator/echo-cassandra-to-in-memory/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Echo’s scheduler can be run completely in-memory. On startup or redeploy, echo will check cron schedules to see if it needs to retroactively execute any missed triggers. This migration only requires configuration changes.
