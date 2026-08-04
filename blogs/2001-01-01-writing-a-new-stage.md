---
title: "Writing a New Stage"
url: "/docs/community/contributing/code/developer-guides/extending/new-stage/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Overview To create a new stage, you need to make changes in the monorepo to orca to implement the logic of the stage, and the front-end changes in deck to implement the UI. Depending on what the stage does, you may need to implement new cloud provider-specific logic in clouddriver and/or expose new APIs in gate as well. This doc currently only covers the backend changes made to orca.
