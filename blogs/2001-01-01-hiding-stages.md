---
title: "Hiding Stages"
url: "/docs/guides/operator/hiding-stages/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Stages that are not provider-specific will be available by default. To hide specific stages from end-users, set the hiddenStages property in Deck’s settings-local.js to a list of the keys of stages you wish to hide. For example, to hide the Gremlin and Travis stages, include the following in settings-local.js : window .
