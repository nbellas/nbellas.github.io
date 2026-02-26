---
title: "Research"
permalink: /research/
layout: single
author_profile: true
classes:
  - research-small
  - wide
---

<div class="research-small" markdown="1">

<h2 style="color: #f00f28;">Current Research</h2>

<h3>Machine Learning for Autonomic System Operation in the Heterogeneous Edge-Cloud Continuum (MLSysOps)</h3>

We are working on the design, implementation and evaluation of a complete framework for autonomic end-to-end system management across the full cloud-edge continuum. The framework employs a hierarchical agent-based AI architecture to interface with the underlying resource management and application deployment/orchestration mechanisms of the continuum. Adaptivity is achieved through continual ML model learning in conjunction with intelligent retraining concurrently to application execution, while openness and extensibility will be supported through explainable ML methods and an API for pluggable ML models. Flexible/efficient application execution on heterogeneous infrastructures and nodes will be enabled through innovative portable container-based technology. Energy efficiency, performance, low latency, efficient, resilient and trusted tier-less storage, cross-layer orchestration including resource-constrained devices, resilience to imperfections of physical networks, trust and security, are key elements of MLSysOps addressed using ML models. The framework architecture disassociates management from control and seamlessly interfaces with popular control frameworks for different layers of the continuum. The framework is evaluated using research testbeds as well as two real-world application-specific testbeds in the domain of smart cities and smart agriculture, which is also used to collect the system-level data necessary to train and validate the ML models, while realistic system simulators will be used to conduct scale-out experiments. ([Github](https://github.com/mlsysops-eu))

In this line of work we have focused on efficient on-device DNN training. We proposed the [TMModel](/files/2025_ICS_TMModel.pdf), a performance model that captures the impacts of memory, and especially the texture cache, on the performance of embedded GPUs for different access patterns. In a follow-up work, this modeling guides compiler-level optimizations for on-device DNN training by quickly characterizing the effects of operator fusion, data layout synthesis and selection, and sub-batch size selection and performing global co-optimization across the entire computational graph. Experimentalresults show that CoopTrain consistently outperforms baselines, achieving speedups of 1.44×–74.5× over the vendor-optimized CLML kernel library and 8.9×–204× over the MNN framework.

We have also worked on ML inference on FPGAs by introduced [DPUconfig](/files/DATE_2026.pdf), a novel runtime management framework, based on a custom Reinforcement Learning (RL) agent, that dynamically selects
optimal DPU configurations by leveraging real-time telemetry data monitoring, system utilization, power consumption, and application performance to inform its configuration selection decisions. 

<h3 style="color: #f00f28;">Uniserver</h3>
**Software:** EDA tools for architectural synthesis; system software for reliable and approximate computing; multimedia.

<h2 style="color: #f00f28;">Prior Research</h2>


</div>
