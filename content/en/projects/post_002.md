---
author: "Brian Tang"
title: "Face-Off: Adversarial Face Obfuscation"
date: 2021-07-11
description: ""
tags: ["ML", "Security", "Privacy", "Conference"]
thumbnail: /images/face-off-teaser.png
weight: 8
---

### Authors

[{{<param varun>}}]({{<param varunURL>}}), [{{<param chuhan>}}]({{<param chuhanURL>}}), **Brian Tang**, [{{<param kassem>}}]({{<param kassemURL>}}), [{{<param somesh>}}]({{<param someshURL>}}), [{{<param suman>}}]({{<param sumanURL>}})

### Conference

21st Symposium Privacy Enhancing Technologies (2021)

### Presentation

{{< youtube id="xvoZFQTc8iM" autoplay="true" color="white" yt_start="0" yt_end="1000">}}

### Abstract

Advances in deep learning have made face recognition technologies pervasive. While useful to social media platforms and users, this technology carries significant privacy threats. Coupled with the abundant information they have about users, service providers can associate users with social interactions, visited places, activities, and preferences--some of which the user may not want to share. Additionally, facial recognition models used by various agencies are trained by data scraped from social media platforms. Existing approaches to mitigate these privacy risks from unwanted face recognition result in an imbalanced privacy-utility trade-off to users. In this paper, we address this trade-off by proposing Face-Off, a privacy-preserving framework that introduces strategic perturbations to the user's face to prevent it from being correctly recognized. To realize Face-Off, we overcome a set of challenges related to the black-box nature of commercial face recognition services, and the scarcity of literature for adversarial attacks on metric networks. We implement and evaluate Face-Off to find that it deceives three commercial face recognition services from Microsoft, Amazon, and Face++. Our user study with 423 participants further shows that the perturbations come at an acceptable cost for the users. 

### Figures

![](/images/face-off-pipeline.png)
![](/images/face-off-apis.png)

### Relevant Links

[https://arxiv.org/abs/2003.08861](https://arxiv.org/abs/2003.08861)

[https://github.com/wi-pi/face-off](https://github.com/wi-pi/face-off)

[https://github.com/byron123t/faceoff](https://github.com/byron123t/faceoff)