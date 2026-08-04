---
title: "Orca: Redis to SQL Migration"
url: "/docs/guides/operator/orca-redis-to-sql/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
If you are not migrating an existing Orca deployment, refer to Orca SQL Setup instead. Migrate from Redis to SQL Migrating without downtime from Redis to SQL is a three-step process: Deploy Orca with the DualExecutionRepository writing to both Redis and SQL. Deploy a new Orca cluster with migrators enabled and queue processing disabled.
