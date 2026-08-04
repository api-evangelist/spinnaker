---
title: "Service Accounts"
url: "/docs/setup/other_config/security/authorization/service-accounts/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Service Accounts enable the ability for automatically triggered pipelines to modify resources in protected accounts or applications. Practically speaking, this means that a Git commit could trigger a Jenkins build that could then kick off a pipeline to deploy the newly built image in your access-controlled QA environment. The pipeline would run utilizing the permissions of the service account.
