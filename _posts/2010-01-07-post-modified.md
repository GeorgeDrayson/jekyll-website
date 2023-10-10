---
title: "CC-SGG: Corner Case Scenario Generation using Learned Scene Graphs"
categories:
  - Blog
tags:
---

[CC-SGG: Corner Case Scenario Generation using Learned Scene Graphs](https://arxiv.org/abs/2309.09844)

George Drayson, Efimia Panagiotaki, Daniel Omeiza, Lars Kunze

Corner case scenarios are an essential tool for testing and validating the safety of autonomous vehicles (AVs). As these scenarios are often insufficiently present in naturalistic driving datasets, augmenting the data with synthetic corner cases greatly enhances the safe operation of AVs in unique situations. However, the generation of synthetic, yet realistic, corner cases poses a significant challenge. In this work, we introduce a novel approach based on Heterogeneous Graph Neural Networks (HGNNs) to transform regular driving scenarios into corner cases. To achieve this, we first generate concise representations of regular driving scenes as scene graphs, minimally manipulating their structure and properties. Our model then learns to perturb those graphs to generate corner cases using attention and triple embeddings. The input and perturbed graphs are then imported back into the simulation to generate corner case scenarios. Our model successfully learned to produce corner cases from input scene graphs, achieving 89.9% prediction accuracy on our testing dataset. We further validate the generated scenarios on baseline autonomous driving methods, demonstrating our model's ability to effectively create critical situations for the baselines.

Download [here](https://arxiv.org/abs/2309.09844)