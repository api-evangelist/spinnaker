---
title: "Google Compute Engine - Bakery"
url: "/docs/setup/other_config/bakery/google/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
The GCE bakery configuration allows you to set the default network and zone and whether to use the public IP address of the VM used for baking the image. For example, to set the default zone, add to the rosco-local.yml the following configuration google : enabled : true bakery-defaults : zone : network : networkProjectId : projectId subnetwork : subnetwork useInternalIp : templateFile : gce.json baseImages : - id : unique-bake-id shortDescription : shortUI Description (aka precise) detailedDescription : Ubuntu precise packageType : rpm templateFile : gce.json osType : customRepository : custom
