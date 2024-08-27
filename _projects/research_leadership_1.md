---
layout: page
title: "Faster Large Language Model Training Using SSD-Based Activation Offloading"
redirect: https://arxiv.org/abs/2408.10013
enable_hyperlink: true
description: |
 · Designed and implemented the framework to offload activations in LLM training to NVMe SSDs.
 · Demonstrated the viability on large-scale systems by modeling the performance, estimated SSD lifespan and the required per-GPU PCIe bandwidth.
 · To overlap the data transfer fully with computation, several optimization techniques were introduced, including tensor deduplication, tensor forwarding, and adaptive offloading algorithm.
 · Achieves almost the same training time per step as the original system without offloading while reducing the activations peak memory use by up to 47%.
 · Introduced the recompute-offload-keep (ROK) curve to compare our offloading with two other tensor placement strategies, keeping activations in memory and layerwise full recomputation. 
importance: 1
category: research_leadership
---