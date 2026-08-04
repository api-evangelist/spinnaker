---
title: "Kubernetes CRD Extensions"
url: "/docs/community/contributing/code/developer-guides/extending/crd-extensions/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Spinnaker Extension Points for Custom Resource Definitions At Google, we’ve built extension points for deep CRD integrations within Spinnaker. This work has allowed us to support the following features within Spinnaker: Custom models for representing CRDs as spinnakerKinds Deploying CRDs with custom Spinnaker artifact types Custom Kubernetes API versions Custom Spinnaker naming strategies Per-account, custom Spinnaker UIs that can run alongside the existing Kubernetes UIs This guide is for developers who want to duplicate this functionality for their CRDs. It also exists as an explanation of c
