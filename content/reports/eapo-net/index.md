---
title: 'EAPO-NET: Adaptive
Energy-Aware Profit Optimization in Next-Generation RANs (Extended Technical Report'
authors:
  - André Cédric Bessala, Guilherme Iecker Ricardo and Gentian Jakllari
date: '2026-06-20'
publication_types: ['report']
summary: >
 This report descibe the entire work of xxx submitted at MsWiM 2026 Conference.
tags:
  - O-RAN
featured: false
---

## Abstract

Write your abstract or summary here. This is the main body of the landing page
— The global deployment of more than 3.5 million 5G base stations has made the energy efficiency of Radio Access Networks (RANs) a pressing challenge for mobile network operators (MNOs). Achieving sustainable operation requires jointly optimizing energy consumption, service revenue, and QoS compliance under highly dynamic traffic demands and heterogeneous service requirements. 


 In this paper, we present \madrl{}, a Multi-Agent Deep Reinforcement Learning (MADRL) framework that optimizes energy consumption and network profit across the O-RAN control hierarchy.
 The key insight behind \madrl{} is a heterogeneous multi-agent decomposition that aligns learning agents with distinct O-RAN control functions. Specifically, \madrl{} jointly trains RU xApp agents, admission-control xApp agent, and node-level dApp agents using centralized training with decentralized execution (CTDE) and Value Decomposition Networks (VDN), while enabling fully decentralized inference without inter-agent communication. This design preserves scalability and deployment practicality in large-scale O-RAN environments.

 Extensive simulations demonstrate that \madrl{} learns near-optimal control policies that simultaneously reduce energy consumption, maximize network profit, and satisfy QoS constraints. Compared with exact integer linear programming (ILP) formulations, \madrl{} achieves comparable optimization quality while substantially improving scalability and adaptability to time-varying network conditions.

## Download

[View report](EAPO-Net-TR.pdf)
