---
title: "Anatomy of a Pull Request Generator"
url: "https://codefresh.io/blog/anatomy-of-a-pull-request-generator/"
date: "2025-10-02"
author: "Shawn Sesna"
feed_url: "https://codefresh.io/feed/"
---
Argo CD has built a number of Generators to support various scenarios that developers need when using Argo CD and Kubernetes. In this post, I’ll be discussing the Pull Request Generator. A Pull Request Generator is an Argo CD Application Set deployment type that is configured to “watch” a Git repository for Pull Requests (PRs).
