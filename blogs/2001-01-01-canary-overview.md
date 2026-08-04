---
title: "Canary Overview"
url: "/docs/guides/user/canary/canary-overview/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Canary is a deployment process in which a change is partially rolled out, then evaluated against the current deployment (baseline) to ensure that the new deployment is operating at least as well as the old. This evaluation is done using key metrics that are chosen when the canary is configured. Canaries are usually run against deployments containing changes to code, but they can also be used for operational changes, including changes to configuration.
