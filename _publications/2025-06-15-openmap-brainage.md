---
title: "OpenMAP-BrainAge: Generalizable and Interpretable Brain Age Predictor"
collection: publications
permalink: /publication/openmap-brainage
paper_image: publications/openmap_brainage.png
excerpt: "A multiview transformer framework with infomration fusion across different anatomical views and numerical brain volume features for brain age prediction in linear computational cost, which emphasizes generalization across sites and interpretability of imaging features."
authors: "<strong>Pengyu Kan</strong>, Craig Jones, Kenichi Oishi"
date: 2025-06-15
venue: "To Be Published"
paperurl: "https://arxiv.org/abs/2506.17597"
newsurl: "https://www.cs.jhu.edu/news/cs-phd-student-receives-distinctions-at-ana-2025/"
abstract: |
  **Purpose:** To develop an age prediction model which is interpretable and robust to demographic and technological variances in brain MRI scans.

  **Materials and Methods:** We propose a transformer-based architecture that leverages self-supervised pre-training on large-scale datasets. Our model processes pseudo-3D T1-weighted MRI scans from three anatomical views and incorporates brain volumetric information. By introducing a stem architecture, we reduce the conventional quadratic complexity of transformer models to linear complexity, enabling scalability for high-dimensional MRI data. We trained our model on ADNI2 and 3 (N=1348) and OASIS3 (N=716) datasets (age range: 42–95) from North America, with an 8:1:1 split for train, validation, and test. We then validated it on the AIBL dataset (N=768, age range: 60–92) from Australia.

  **Results:** We achieved an MAE of 3.65 years on the ADNI2 and 3 and OASIS3 test set and strong generalization with MAE of 3.54 years on AIBL. There was a notable increase in brain age gap (BAG) across cognitive groups, with mean of 0.15 years (95% CI: [-0.22, 0.51]) in CN, 2.55 years ([2.40, 2.70]) in MCI, and 6.12 years ([5.82, 6.43]) in AD. Additionally, significant negative correlation between BAG and cognitive scores was observed, with correlation coefficient of -0.185 for MoCA and -0.231 for MMSE (both significant at the 0.001 level). Gradient-based feature attribution highlighted ventricles and white matter structures as key regions influenced by brain aging.

  **Conclusion:** Our model effectively fused information from different views and volumetric information to achieve state-of-the-art brain age prediction accuracy, improved generalizability and interpretability with association to neurodegenerative disorders.
---
