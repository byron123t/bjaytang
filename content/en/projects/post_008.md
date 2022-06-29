---
author: "Brian Tang"
title: "Real-Time Protection of Mobile Device Screen Information from Shoulder Surfing"
date: 2022-06-28
description: ""
tags: ["Mobile", "Privacy", "Security", "Preprint", "HCI"]
thumbnail: /images/shouldersurf-teaser.png
weight: 6
---

### Authors

**Brian Tang**, [{{<param shin>}}]({{<param shinURL>}})

### Conference

Under review at 32nd USENIX Security Symposium (2023)

### Abstract

People use mobile devices ubiquitously for computing, communication, storage, web browsing, and more. As a result, the information accessed and stored within mobile devices, such as financial and health information, text messages, and emails, can often be sensitive. Despite this, people frequently use their mobile devices in public areas, becoming susceptible to a simple yet effective attack – shoulder surfing. Shoulder surfing occurs when a person near a mobile user peeks at the user’s mobile device, potentially acquiring passcodes, PINs, browsing behavior, or other personal information. We propose a novel solution, called EYE-SHIELD, to prevent shoulder surfers from accessing/stealing sensitive on-screen information. EYE-SHIELD is designed to protect all types of on-screen information in real time, without any serious impediment to users’ interactions with their mobile devices. In particular, EYE-SHIELD generates images that appear readable and interpretable at close distances, but appear blurry or pixelated at farther distances and wider angles. It is capable of protecting on-screen information from shoulder surfers, operating in real time, and being minimally intrusive to the intended users. EYE-SHIELD protects images and text from shoulder surfers by reducing recognition rates to 25.00% and 18.78%. Our implementations of EYE-SHIELD achieved high frame rates for 1440 × 3088 screen resolutions (24 FPS for Android and 43 FPS for iOS). EYE-SHIELD also incurs acceptably low memory usage, CPU utilization, and energy overhead. Finally, our MTurk and in-person user studies indicate that EYE-SHIELD protects on-screen information at an acceptable cost for privacy-conscious users and is easy to use.

### Figures

![](/images/shouldersurf-camera.png)
![](/images/shouldersurf-performance.png)
![](/images/shouldersurf-prototype.png)

### Relevant Links

[https://osf.io/haxzb/?view_only=8629a44c79d74b71b603be3830f60583](https://osf.io/haxzb/?view_only=8629a44c79d74b71b603be3830f60583)
