---
author: "Brian Tang"
title: "Rearchitecting Classification Frameworks For Increased Robustness"
date: 2019-03-19
description: ""
tags: ["ML", "Security", "Preprint"]
thumbnail: /images/invariances-high-level.png
weight: 1
---

### Authors

[{{<param varun>}}]({{<param varunURL>}}), **Brian Tang**, [{{<param papernot>}}]({{<param papernotURL>}}), [{{<param kassem>}}]({{<param kassemURL>}}), [{{<param somesh>}}]({{<param someshURL>}}), [{{<param xi>}}]({{<param xiURL>}})

### Abstract

While generalizing well over natural inputs, neural networks are vulnerable to adversarial inputs. Existing defenses against adversarial inputs have largely been detached from the real world. These defenses also come at a cost to accuracy. Fortunately, there are invariances of an object that are its salient features; when we break them it will necessarily change the perception of the object. We find that applying invariants to the classification task makes robustness and accuracy feasible together. Two questions follow: how to extract and model these invariances? and how to design a classification paradigm that leverages these invariances to improve the robustness accuracy trade-off? The remainder of the paper discusses solutions to the aformenetioned questions.

### Figures

![](/images/invariances-signs.png)
![](/images/invariances-lidar.png)

### Relevant Links

[https://arxiv.org/abs/1905.10900](https://arxiv.org/abs/1905.10900)

[https://github.com/byron123t/3d-adv-pc](https://github.com/byron123t/3d-adv-pc)

[https://github.com/byron123t/YOPO-You-Only-Propagate-Once](https://github.com/byron123t/YOPO-You-Only-Propagate-Once)
