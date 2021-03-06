![image](../images/confluent-logo-300-2.png)

# Overview

The Pageviews demo is the automated version of the [Confluent Platform 4.1 Quickstart](https://docs.confluent.io/current/quickstart.html)

# Prerequisites

* [Common demo prerequisites](https://github.com/confluentinc/quickstart-demos#prerequisites)
* [Confluent Platform 4.1](https://www.confluent.io/download/)

# What Should I see?

After you run `./start.sh`:

* If you are running Confluent Enterprise, open your browser and navigate to the Control Center web interface Monitoring -> Data streams tab at http://localhost:9021/monitoring/streams to see throughput and latency performance of the KSQL queries
* Run `ksql http://localhost:8088` to view and create queries, or open your browser and navigate to the KSQL UI at http://localhost:8088
