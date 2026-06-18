---
title: BRAVE-O
date: 2024-01-01
links:
  - type: site
    url: "https://github.com/bessalacedric/brave-o"  # EDIT
tags:
  - O-RAN
  - Deep Reinforcement Learning
  - Energy Optimization
  - 5G
---

A Multi-Agent Deep Reinforcement Learning framework for joint PRB blanking and VNF
(DU/CU) placement, targeting energy efficiency in disaggregated 5G O-RAN deployments.

<!--more-->

Each RU agent controls PRB blanking, a placement agent controls VNF activation
across O-Cloud nodes, and agents are trained with Deep Q-Networks using soft
Polyak target updates and gradient clipping for stability. Validated on a
5-node SLICES-RI deployment running a full OpenAirInterface 5G stack, against
an ILP-optimal (Pyomo/Branch-and-Cut) and a greedy baseline.
