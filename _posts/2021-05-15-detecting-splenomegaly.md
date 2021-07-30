---
layout: post
title: Detecting Splenomegaly as NLP Proof of Concept
# subtitle: Digest 3
# share-description: A brief description of the page. If not provided, then subtitle will be used, and if that's missing then an excerpt from the page content is used.
# cover-img: /assets/img/path.jpg
thumbnail-img: /assets/img/blog/radiology2.jpeg
# share-img: /assets/img/path.jpg
tags: [radiology, project, NLP]
comments: true
---

This work was our first proof of concept for an end-to-end machine learning NLP pipeline in the realm of radiology reports.

By the time we started this project in the summer of 2019, we had developed a strong belief that machine learning and NLP could unlock powerful clinical insights from free and semi-structured texts. Our aim was to build a minimum viable product (MVP) that can prove this to our stakeholders and partners.

We recruited medical fellows and radiologists to annotate a set of radiology reports using an R-based tool to detect splenomegaly (the enlargement of the spleen, characteristic of several cancers). We then trained these reports using TF-IDF and a machine learning ensemble model. We were able to achieve substantial results that match the expectations of radiologists and our management.

<p align="center">
  <img src="https://github.com/msk-nlp/anlpablog/blob/main/assets/img/blog/radiology2.jpeg" alt="photo4" width="600"/>
</p>

With these results, we were able to come up with valuable use cases. For example, medical professionals can now quickly explore survival probability associated with splenomegaly in patients with any primary cancer disease. This proof of concept has empowered us to tackle tougher problems with more novel models and solutions.
