---
title: "OpenMAP-BrainAge: Generalizable and Interpretable Brain Age Predictor"
collection: publications
permalink: /publication/openmap-brainage
paper_image: publications/openmap_brainage.png
excerpt: "A multiview transformer framework with infomration fusion across different anatomical views and numerical brain volume features for brain age prediction in linear computational cost, which emphasizes generalization across sites and interpretability of imaging features."
authors: "<strong>Pengyu Kan</strong>, Craig Jones, Kenichi Oishi"
date: 2025-06-15
venue: "Radiology Advances"
paperurl: "https://arxiv.org/abs/2506.17597"
newsurl: "https://www.cs.jhu.edu/news/cs-phd-student-receives-distinctions-at-ana-2025/"
abstract: |
 **Background**: Accurately estimating brain age can help identify deviations linked to neurodegenerative diseases. Although prior models exhibit some generalization and explainability, their robustness across heterogeneous cohorts and acquisition protocols remains limited, underscoring the need for enhanced clinical readiness.
 
 **Purpose**: To develop an age prediction model that is interpretable and robust to demographic and technological variations in brain MRI scans.
 
 **Materials and Methods**: We propose a transformer-based brain age model that analyzes 3D T1-weighted MRI by summarizing information from three standard views and combining it with regional brain volumes. This design preserves key 3D features while a stem architecture greatly reduces computation, enabling fast, scalable processing of high‑resolution 3D scans. We trained our model on ADNI2 & 3 (N=1348) and OASIS3 (N=716) datasets (age range: 42 - 95) from North America, with an 8:1:1 split for train, validation, and test. Then, we validated it on the AIBL dataset (N=648, age range: 60 - 92) from Australia.
 
 **Results**: We achieved a mean absolute error (MAE) of 3.65 years on ADNI2 & 3 and OASIS3 test sets, and a high generalizability of MAE of 3.54 years on AIBL. There was a notable increase in BAG along with cognitive decline, with a mean of 0.15 years (95% CI: [-0.22, 0.51]) in CN, 2.55 years ([2.40, 2.70]) in MCI, and 6.12 years ([5.82, 6.43]) in dementia. Additionally, negative correlation between BAG and cognitive scores was observed conditioning on confounding variables, with r = -0.397 (p < 0.001) for MMSE and -0.393 (p < 0.001) for MoCA, where declining scores generally signify worsening cognitive performance. The saliency map highlighted white and deep gray matter structures as key regions influenced by brain aging.
 
 **Conclusion**: Our model effectively integrated multiview and volumetric information to achieve state-of-the-art brain age prediction, with improved generalizability and interpretability and association with cognitive function.

---
