---
title: "Custom CAs for Webhooks"
url: "/docs/guides/operator/webhook-custom-trust-store/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
Overview Webhook stages enable Spinnaker to make HTTP(S) calls to external web services. If the configured webhook URL has the https:// scheme, Spinnaker will use TLS to communicate with the external server. Spinnaker will attempt to validate the certificate presented by the server by building a chain of trust back to a trusted certification authority (CA) and will refuse to connect if the certificate cannot be validated.
