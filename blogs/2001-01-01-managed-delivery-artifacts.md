---
title: "Managed Delivery Artifacts"
url: "/docs/guides/user/managed-delivery/artifacts/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Managed Delivery supports two types of delivery artifacts: debians and Docker images . Delivery artifacts are meant to provide Spinnaker information about: Where to locate the available versions of an artifact you care about How to choose the latest version from a list of versions Spinnaker needs this information to make decisions about when and how to roll out new versions as they become available. Artifacts are defined with name, type, and version strategy information.
