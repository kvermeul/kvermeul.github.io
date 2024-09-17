---
layout: page
permalink: /software/
title: software
description: Contributions to the community with software, systems, and datasets.
nav: true
nav_order: 8
---

I attach a particular importance to share the code and the data collected during my research to enable replicability and reproducibility, which have been recognized by my community with artifact evaluation badges and artifact award. In addition to these objectives, I actively participate in the development and the maintenance of long-running measurement systems for the community. 

Diamond-Miner: The Diamond-Miner system runs on the Iris platform [https://iris.dioptra.io](https://iris.dioptra.io) and has been running Internet topology multipath measurements for multiple years now, and the data have been used by multiple papers. The code has been refactored since by Matthieu Gouel and Maxime Mouchet and is available on github [https://github.com/dioptra-io](https://github.com/dioptra-io). The dioptra group at Sorbonne Université are the current maintainers of the system. Also, although I am not involved in that project, a new implementation of the Diamond-Miner algorithm is currently tested to replace the scamper implementation of multipath tracing on the M-Lab traceroutes following each NDT speedtest [https://www.measurementlab.net/blog/jun24-community-call/#testing-fast-mda-traceroute](https://www.measurementlab.net/blog/jun24-community-call/#testing-fast-mda-traceroute). 

Internet Scale Reverse Traceroute: The Internet Scale Reverse Traceroute system has different components, which are deployed at Northeastern University for the controller and the M-Lab platform for the distributed vantage points [https://www.measurementlab.net](https://www.measurementlab.net), which is sponsored by Google. The platform is open to operators and researchers, and has served for different research projects. It has also enabled an internship at Google for a PhD student at Columbia University to evaluate the benefit of Reverse Traceroute for helping Google at troubleshooting problems.  

Moreover, we have deployed a “revtr-sidecar”, which performs reverse path measurement for a fraction (25%) of the M-Lab NDT speedtests (>1M reverse path measurements per day). The data are available to the community on the M-Lab Big Query, which can be accessed on this link [https://console.cloud.google.com/bigquery?project=measurement-lab&ws=!1m4!1m3!3m2!1smeasurement-lab!2srevtr_raw](https://console.cloud.google.com/bigquery?project=measurement-lab&ws=!1m4!1m3!3m2!1smeasurement-lab!2srevtr_raw).  You may need an (free) M-Lab account to access the data [https://www.measurementlab.net/data/docs/bq/quickstart/](https://www.measurementlab.net/data/docs/bq/quickstart/). I am the current maintainer of the Internet Scale Reverse Traceroute system.  

