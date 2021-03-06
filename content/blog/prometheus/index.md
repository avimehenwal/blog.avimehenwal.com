---
title      : "Monitoring"
date       : 2019-10-03T17:18:47Z
publishdate: 2019-10-03T17:18:47Z
draft      : false
comments   : true
weight     : 5
revision   : 0
series:
- myLearning
categories:
- monitoring
tags:
- prometheus
---

<!-- more -->

## Prometheus

* Rest based **PULL** model
* `/targets`
* `/metrics`
* `/grpah`
* System monitoring tool, with TS database
  * stores data on local disk `--storage.tsdb.path` usually `.data/`
  * `2hr` samples are aggregated
* PushGateways
* Exporters
* care about entire path of monitoring, not only storing data
* [Service Application level monitoring](https://www.youtube.com/watch?v=PDxcEzu62jk)
* Label data model for matrics
* Give me all patitions, that have capacity > 100GB and is not mounted on root
* Local storage is good only for a month or so of data
  * Then export samples to other DB, Adapter (influxdb)
* Automatic service discovery
  * Task Schedulers
* Alert Manager
  * Grouping
  * Inhibition
  * Silence



### Footnotes

[^1]:
[^2]:
