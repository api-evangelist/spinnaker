---
title: "Configure a canary"
url: "/docs/guides/user/canary/config/canary-config/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Before you can add a canary stage to a pipeline, you need to configure what the canary consists of, including: A name by which a canary stage can choose this config The specific metrics to evaluate, and a logical grouping of those metrics Default scoring thresholds (which can be overridden in the canary stage) Optionally, one or more filter templates Canary configuration is done per Spinnaker application . For each application set up to support canary, you create one or more configs.
