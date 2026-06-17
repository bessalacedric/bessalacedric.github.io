---
title: SLICES-RI testbed experimentation
date: 2024-06-01
tags:
  - 5G
  - Testbed
  - OpenAirInterface
  - SLICES-RI
---

End-to-end 5G experimentation on the SLICES-RI European research infrastructure,
running a full OpenAirInterface stack across a 5-node O-Cloud deployment.

<!--more-->

Core network (AMF, SMF, UPF, NRF, AUSF, UDM, UDR) and RAN (OAI gNB, up to several
UEs) run in Docker across the deployment. The GTP-U dataplane uses `tc flower`
and `pedit` rules for per-UE traffic steering, providing a realistic traffic
environment for training and evaluating the BRAVE-O framework under real 5G
protocol conditions.

More info: [slices-ri.eu](https://slices-ri.eu)
