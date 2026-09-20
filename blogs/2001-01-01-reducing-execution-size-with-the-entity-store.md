---
title: "Reducing Execution Size with the Entity Store"
url: "/docs/guides/runbooks/entity-store/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Overview The artifact store moves artifact content out of the execution context and leaves a reference behind. The entity store, added in Spinnaker 2026.0.0 ( spinnaker#7072 ), generalises that mechanism so it is no longer limited to Spinnaker’s Artifact class: any object in the context can be stored the same way. The case that matters most in practice is manifests.
