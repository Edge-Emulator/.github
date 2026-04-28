# EMULATE Edge Emulation Platform

Welcome to the official GitHub organization for **Edge-Emulator**, the emulation platform developed as part of the [EMULATE Project](https://www.fh-dortmund.de/microsite/smartedgelab/projekte/emulate.php). EMULATE develops methods, tools, and reference implementations for measuring, analyzing, and optimizing edge service performance across Europe's emerging cloud-edge continuum.

## About EMULATE

Real-time applications such as autonomous driving, augmented reality, smart grid management, and drone operations increasingly depend on edge computing, where data is processed close to its source instead of in distant cloud data centers.

EMULATE addresses a critical adoption challenge in edge computing: the need to evaluate distributed applications, networks, and infrastructure under realistic conditions before deployment. The project combines emulation, diagnostics, and performance analysis to support reproducible research and practical experimentation.

## Emulation Platform

The Emulation Platform enables the creation of digital twins of real-world edge environments, including infrastructure, applications, network topologies, and operational scenarios. It allows developers and researchers to test deployment strategies, evaluate edge architectures, and study system behavior under controlled, repeatable conditions.

Key capabilities include:

- Network emulation based on Containerlab
- Lightweight Kubernetes clusters with K3s
- Workload simulation using Kubernetes WithOut Kubelet (KWOK)
- Multi-cluster federation with LIQO
- 5G Standalone (SA) network emulation using Open5GS and UERANSIM
- User mobility simulation between cells through Xn-based handover between gNBs

## Diagnostic Capabilities

The Diagnostic Platform complements the Emulation Platform with analysis workflows and performance metrics. It helps identify bottlenecks, assess quality of service, and support the optimization of latency-sensitive edge applications.

## Reference Architecture

A representative implementation of the project is shown below.

![Architecture Diagram](assets/architecture.png)

## European Funding Framework

The EMULATE project is part of the European [Important Project of Common European Interest on Next Generation Cloud Infrastructure and Services (IPCEI-CIS)](https://www.bundeswirtschaftsministerium.de/Redaktion/EN/Artikel/Industry/ipcei-cis.html), aimed at developing a unified, multi-provider cloud-edge continuum branded as **8ra (ORA)**.

EMULATE is funded by the European Union and the German Federal Ministry for Economic Affairs and Climate Action under research grant **13IPC012**.

<p align="center">
  <img src="assets/ipcei-cis-support.png" alt="Funded by the European Union and supported by the German Federal Ministry for Economic Affairs and Climate Action" width="360">
</p>

## Research and Industry Engagement

EMULATE actively collaborates with academic and industrial partners across telecommunications, automotive systems, embedded electronics, and cloud-edge infrastructure to ensure real-world relevance and practical applicability. The project welcomes engagement from communities working on edge computing performance, digital twins, 5G/6G experimentation, and distributed application optimization.

## Publications

- Urwah Muslim and Stephan Recker. "A Comparative Analysis of Digital Twins for Advanced Networks." IEEE 7th International Conference and Workshop Óbuda on Electrical and Power Engineering (CANDO-EPE), pp. 281-286, 2024. [DOI: 10.1109/CANDO-EPE65072.2024.10772762](https://doi.org/10.1109/CANDO-EPE65072.2024.10772762)
- Urwah Muslim and Stephan Recker. "Demo: Emulation Platform to Build Digital Twins of Edge Computing Environments." IEEE/ACM Symposium on Edge Computing (SEC), pp. 512-514, 2024. [DOI: 10.1109/SEC62691.2024.00062](https://doi.org/10.1109/SEC62691.2024.00062)

For comprehensive information and project updates, visit the [official EMULATE project page](https://www.fh-dortmund.de/microsite/smartedgelab/projekte/emulate.php).
