---
author: "Brian Tang"
title: "Automatic Detection of Cookie Consent Violations"
date: 2022-06-28
description: ""
tags: ["ML", "Privacy", "NLP", "Preprint"]
thumbnail: /images/consentchk-teaser.png
weight: 3
---

### Authors

[{{<param duc>}}]({{<param ducURL>}}), **Brian Tang**, [{{<param shin>}}]({{<param shinURL>}})

### Conference

Under review at 32nd USENIX Security Symposium (2023)

### Abstract

Online services increasingly provide users with cookie consent settings to accept/reject the cookies placed on their web browsers. Unlike other GDPR-specific requirements, using cookies without user consent would violate consumer protection laws anywhere in the world. However, little has been done to understand the violations of users’ cookie consent/rejection from a global standpoint. To remedy this important oversight, we propose an end-to-end automated system, called ConsentChk, that analyzes and detects inconsistencies between a website’s cookie usage and users’ cookie consent preferences. ConsentChk detects and analyzes the cookie usage and consent preferences even on the websites that do not display cookie banners for new visitors. We design a machine-learning-based classifier to detect/locate cookie preference buttons to activate cookie setting menus with an 85.96% top-3 score. We build a formal model to systematically categorize the types of cookie consent violations. Our in-depth evaluation demonstrates a high precision of > 91% of ConsentChk’s end-to-end violation detection performance. In a large-scale study on 101,703 top global websites, we find 82.20% and 81.86% of the websites with detected cookie settings to use user-rejected cookies when accessing them from inside and outside of the EU, respectively. Our measurement of rejected cookie usage violations covers cookie management platforms with a 3X more market share than state-of-the-art studies. Our findings indicate the prevalence of misleading, or even deceptive, cookie consent management, raising their awareness among all stakeholders — end-users, website owners and developers as well as regulators

### Figures

![](/images/consentchk-example.png)
![](/images/consentchk-distribution.png)
![](/images/consentchk-pipeline.png)

### Relevant Links

