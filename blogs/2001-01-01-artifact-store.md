---
title: "Artifact Store"
url: "/docs/guides/runbooks/artifact-store/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Overview Spinnaker records everything an execution did in the pipeline context. Whenever a stage uses an artifact, the artifact’s full content is copied into that context, so a single artifact used by several stages is stored many times over. For pipelines with large artifacts this dominates the size of the execution.
