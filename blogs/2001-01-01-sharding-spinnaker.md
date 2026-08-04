---
title: "Sharding Spinnaker"
url: "/docs/guides/runbooks/sharding-spinnaker/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Intro This document shows you how to shard traffic to different Spinnaker services based upon configured criteria. The general pattern is to define a selector class in your configuration. Endpoints will then be selected based upon the criteria specified in the selectors.
