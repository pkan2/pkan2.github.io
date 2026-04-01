---
permalink: /
title: "About me"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a fifth-year Ph.D. student in Computer Science at Johns Hopkins University, fortunately advised by [Professor Kenichi Oishi](http://www.open-map.org/#member) and [Professor Craig Jones](https://imagingai.org/). Previously, I had the opportunity to collaborate with [Professor René Vidal](http://vision.jhu.edu/rvidal.html). 

My research lies at the intersection of deep learning and medical imaging, with a focus on brain MRI analysis. Specifically, I work on transformer-based models for brain age estimation and diffusion-based approaches for neonatal lesion inpainting. More broadly, my interests span multimodal representation learning, clinically informed model design, and improving the generalizability of medical imaging models.

My long-term research vision is to advance methods for multimodal information representation through the Vision-Language models and foundation models, and to leverage deep learning to bridge AI and clinical practice, with the goal of deepening our knowledge of brain cognition, neurodevelopment, and neurodegeneration.

Previously, I received my BS in Computer Science, Mathematics, and Economics, with a minor in Physics, from the University of Wisconsin - Madison, where I was advised by [Professor Vikas Singh](https://www.biostat.wisc.edu/~vsingh/).



Recent News
==========
- Our work *"Clinically Interpretable Transformer Model Reveals Neurodevelopmental Delay in Preterm and NICU Infants Using Diffusion MRI"* was accepted to the [**2026 ISMRM & ISMRT Annual Meeting & Exhibition**](https://www.ismrm.org/26m/) (Cape Town, South Africa, May 9–14, 2026).

- At the **150th Annual Meeting of the American Neurological Association** (ANA 2025, Baltimore, Sep 2025), our work *"Multiview Transformer for Brain Age Prediction"* received a **Poster Award**, was selected for an **oral presentation** (one of five talks chosen from hundreds of abstracts), and was named an **Abstract of Distinction**; I also received a **Travel Award** and presented as an **Emerging Scholar** ([speaker profile](https://2025.myana.org/cg_speakers/pengyu-kan/)). The Johns Hopkins Computer Science department [featured these recognitions](https://www.cs.jhu.edu/news/cs-phd-student-receives-distinctions-at-ana-2025/).

- I gave a guest lecture titled *"Introduction to Transformer in Computer Vision"* for the Fall 2023 Computer Vision course at Johns Hopkins University (Nov 2023).



Publications
=========

{% include base_path %}

<ul class="publication-list">
{% for post in site.publications reversed %}
  {% include archive-single-publication.html %}
{% endfor %}
</ul>

Teachings
=========
- Teaching Assistant, *EN 601.783 Vision as Bayesian Inference* - Spring 2024 (with [Prof. Alan Yuille](https://www.cs.jhu.edu/~ayuille/index.html))
- Teaching Assistant, *EN 601.661 Computer Vision* - Fall 2023 (with [Prof. Kapil D. Katyal](https://kdk132.github.io/))
