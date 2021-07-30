---
layout: post
title: Metastatic Disease Classification
# subtitle: Digest 4
# share-description: A brief description of the page. If not provided, then subtitle will be used, and if that's missing then an excerpt from the page content is used.
# cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/blog/radiology1.jpeg
# share-img: /assets/img/path.jpg
# The image to show. If not provided, then cover-img or thumbnail-img will be used if one of them is provided.
tags: [radiology, project, NLP]
comments: true
---

Building on earlier successes, we decided to dive into detecting metastatic disease from radiology reports.

Our annotators annotated each report with 13 types of organ-metastases, as well as their sizes and comparisons. We then applied deep learning models, namely BERT and RoBERTa, to detect the presence of metastatic diseases. We first annotated and trained models on a report basis, and slowly transitioned to a patient basis to benefit from the full medical history of these patients. We were able to achieve accuracies higher than 90% in all organ-metastases.

<p align="center">
  <img src="https://github.mskcc.org/pages/nguyenh/nlp_blog/assets/img/blog/radiology1.jpeg" alt="photo4" width="600"/>
</p>

Our next step is to leverage a time-series approach to detect metastases, as each patient has multiple reports performed at different stages on his or her treatment journey. We have high hopes that this approach will not only inform metastatic disease research, but also help predict metastatic disease at specific points during the course of treatment of our patients and improve clinical care.
