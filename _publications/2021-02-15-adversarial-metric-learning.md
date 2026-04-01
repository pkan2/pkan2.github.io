---
title: "Exploring Adversarial Robustness of Deep Metric Learning"
collection: publications
permalink: /publication/adversarial-robustness-metric-learning
paper_image: publications/adversarial_metric_learning.png
excerpt: "Empirically studies how adversarial examples behave in deep metric learning and defenses to improve the robustness of deep metric learning."
authors: "Thomas Kobber Panum, Zi Wang, <strong>Pengyu Kan</strong>, Earlence Fernandes, Somesh Jha"
date: 2021-02-15
venue: "arXiv preprint"
paperurl: "https://arxiv.org/abs/2102.07265"
abstract: |
  Deep metric learning (DML) involves learning a distance metric between pairs of samples. DML uses deep neural architectures to learn semantic embeddings of the input, where the distance between similar examples is small while dissimilar ones are far apart. Although the underlying neural networks produce good accuracy on naturally occurring samples, they are vulnerable to adversarially perturbed samples that reduce performance. We take a first step towards training robust DML models and tackle the primary challenge of metric losses being dependent on the samples in a mini-batch, unlike standard losses that only depend on the specific input–output pair. We analyze this dependence effect and contribute a robust optimization formulation. Using experiments on three commonly used DML datasets, we demonstrate 5–76× increases in adversarial accuracy, and outperform an existing DML model that sought to be robust.
---
