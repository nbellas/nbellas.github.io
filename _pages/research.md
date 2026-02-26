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

In the context of this work, we presented LACE-RL, a latency-aware and carbon-efficient management framework that formulates serverless pod retention as a sequential decision problem. LACE-RL uses deep
reinforcement learning to dynamically tune keep-alive durations, jointly modeling cold-start probability, function-specific latency
costs, and real-time carbon intensity. Using the Huawei Public Cloud Trace, we show that LACE-RL reduces cold starts by 51.69% and idle keep-alive carbon emissions by 77.08% compared to Huawei’s static policy, while achieving better latency–carbon trade-offs than state-of-the-art heuristic and single- objective baselines, approaching Oracle performance.

In this line of work we have also focused on efficient on-device DNN training. We proposed the [TMModel](/files/2025_ICS_TMModel.pdf), a performance model that captures the impacts of memory, and especially the texture cache, on the performance of embedded GPUs (e.g. in high-end cell phones) for different access patterns. In a follow-up work, this modeling guides compiler-level optimizations for on-device DNN training by quickly characterizing the effects of operator fusion, data layout synthesis and selection, and sub-batch size selection and performing global co-optimization across the entire computational graph. Experimental results show that our methodology consistently outperforms baselines, achieving speedups of 1.44×–74.5× over the vendor-optimized CLML kernel library and 8.9×–204× over the MNN framework.

We have also worked on ML inference on FPGAs by introduced [DPUconfig](/files/DATE_2026.pdf), a novel runtime management framework, based on a custom Reinforcement Learning (RL) agent, that dynamically selects
optimal DPU (Data Processing Units) configurations by leveraging real-time telemetry data monitoring, system utilization, power consumption, and application performance to inform its configuration selection decisions. 


<h2 style="color: #f00f28;">Prior Research</h2>

<h3>Universal Micro-Server Ecosystem by Exceeding the Energy and Performance Scaling Boundaries (Uniserver)</h3>

The project developed aggressive hardware and software methodologies to increase energy efficiency of the current state-of-the-art micro-servers by exposing the intrinsic hardware heterogeneity caused by process variations, harness it and use it to its advantage for improving energy efficiency or performance. Lightweight software-based mechanisms were embedded for exposing to the system software the pessimistic voltage/frequency margins currently adopted in commercial processor and memory, which are enhanced with new margin/fault-aware runtime and resource management policies. This technology was ported on the world-first 64-bit ARM based Server-on-Chip and was evaluated using state-of-the-art applications deployed in classical cloud business data-centres as well as in newer edge environments. ([1](/files/TACO_2017.pdf)) ([2](/files/TSUSC_2022.pdf))
</div>
