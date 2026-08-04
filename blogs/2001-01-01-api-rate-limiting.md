---
title: "API Rate Limiting"
url: "/docs/guides/runbooks/api-rate-limiting/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
If your Spinnaker deployment has API clients interacting with it, enabling and knowing how to operate the API rate limiter can help keep Spinnaker reliable through spikes of heavy traffic or rogue clients. Intro The API Rate Limiter currently supports limiting individual authenticated and anonymous principals, bucketing requests into windows that are refreshed every interval as well as global & per-principal learning mode. Both the capacity, as well as the window size, are configurable globally and per-principal.
