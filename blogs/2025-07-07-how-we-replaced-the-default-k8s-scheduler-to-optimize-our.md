---
title: "How we replaced the default K8s scheduler to optimize our Continuous Integration builds"
url: "https://codefresh.io/blog/custom-k8s-scheduler-continuous-integration/"
date: "2025-07-07"
author: "Vadim Gusev"
feed_url: "https://codefresh.io/feed/"
---
The default Kubernetes scheduler works great when your cluster is destined for long running applications. At Codefresh we use our Kubernetes clusters for running Continuous Integration pipelines which means our workloads are ephemeral (they are discarded when a pipeline has finished). This allowed us to look at the Kubernetes scheduler from a different perspective and […]
