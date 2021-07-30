---
layout: post
title: Progression of Disease (PoD)
# subtitle: Digest 2
# cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/blog/medical.jpeg
share-img: /assets/img/path.jpg
tags: [radiology, project, NLP]
comments: true
---

This work originates from the need to gather enough retrospective patient’s data so to eliminate the need for a control arm in clinical research. A control arm (aka placebo group) is the group of patients that the underlying experiment is compared against. They typically get the traditional care during the course of the clinical trial. The big idea is that if we have enough information about our patients, such as tumor growth throughout the term of the experiment, we will ideally not have to “waste” half of the patients, and we can let all the trial’s patients experiment with the examined care. This is beneficial to both the trial’s significance and also the patients’ requests.

Given the objective, we sought to extract signals for PoD from radiology reports using text processing and machine learning methods. We were able to achieve meaningful accuracy and gained insight into which words or n-grams infer PoD.

<p align="center">
  <img src="/anlpablog/assets/img/blog/pod_text_eng.png" alt="drawing" width="600"/>
</p>

We learned valuable lessons from this experiment. First, we gained confidence that NLP could meaningfully detect and leverage signals in radiology report’s free texts; second, text processing steps, such as stop-word removal and lemmatization, should be carefully customized to the healthcare field and radiology conventions. This work has paved ways to many subsequent projects that we are carrying out to unlock the power of free text in EHRs.
