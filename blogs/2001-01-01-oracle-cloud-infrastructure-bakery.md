---
title: "Oracle Cloud Infrastructure - Bakery"
url: "/docs/setup/other_config/bakery/oracle/"
date: "2001-01-01"
feed_url: "https://spinnaker.io/index.xml"
---
The Oracle Cloud Infrastructure (OCI) bakery configuration allows for setting the default availability domain, network, and instance shape of the VM used for baking the image. Add the following to rosco-local.yml to enable oracle account baking. oracle : enabled : true bakery-defaults : availabilityDomain : subnetId : instanceShape : templateFile : oracle.json baseImages : baseImageId : sshUserName : packageType : rpm These images are used to dynamically populate the bake stage UI:
