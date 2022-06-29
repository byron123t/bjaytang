---
author: "Brian Tang"
title: "Fairness Properties of Face Recognition and Obfuscation Systems"
date: 2022-06-28
description: ""
tags: ["ML", "Security", "Privacy", "Fairness", "Preprint"]
thumbnail: /images/fairness-tsne.png
weight: 5
---

### Authors

[{{<param harrison>}}]({{<param harrisonURL>}}), **Brian Tang**, [{{<param kassem>}}]({{<param kassemURL>}}), [{{<param somesh>}}]({{<param someshURL>}})

### Conference

Under review at 32nd USENIX Security Symposium (2023)

### Abstract

The proliferation of automated face recognition in various commercial and government sectors has caused significant privacy concerns for individuals. A recent, popular approach to address these privacy concerns is to employ evasion attacks against the metric embedding networks powering face recognition systems. Face obfuscation systems generate imperceptible perturbations, when added to an image, cause the face recognition system to misidentify the user. The key to these approaches is the generation of perturbations using a pre-trained metric embedding network followed by their application to an online system, whose model might be proprietary. This dependence of face obfuscation on metric embedding networks, which are known to be unfair in the context of face recognition, surfaces the question of demographic fairness -- \textit{are there demographic disparities in the performance of face obfuscation systems?} To address this question, we perform an analytical and empirical exploration of the performance of recent face obfuscation systems that rely on deep embedding networks. We find that metric embedding networks are demographically aware; they cluster faces in the embedding space based on their demographic attributes. We observe that this effect carries through to face obfuscation systems: faces belonging to minority groups incur reduced utility compared to those from majority groups. For example, the disparity in average obfuscation success rate on the online Face++ API can reach up to 20 percentage points. We present an intuitive analytical model to provide insights into these phenomena. 

### Figures

![](/images/fairness-whitebox.png)
![](/images/fairness-blackbox.png)

### Relevant Links

[https://arxiv.org/abs/2108.02707](https://arxiv.org/abs/2108.02707)
