---
title: "OpenMAP-HIE: Pathology Informed Score-based Diffusion Model for Unsupervised Neonatal Hypoxic-Ischemic Encephalopathy Lesion Segmentation"
collection: publications
permalink: /publication/openmap-hie
paper_image: publications/openmap_hie.png
excerpt: "A pathology-informed score-based diffusion model that localizes neonatal HIE lesions on ADC maps without voxel-wise lesion supervision."
authors: "<strong>Pengyu Kan</strong>, Craig Jones, Kenichi Oishi"
date: 2026-10-08
venue: "Preprint"
paperurl: "https://pkan2.github.io/files/Unsupervised_Diffusion_HIE_Detection.pdf"
abstract: |
  Accurate localization of neonatal hypoxic–ischemic encephalopathy (HIE) lesions on apparent diffusion coefficient (ADC) images is clinically important but is limited by scarce expert annotations and substantial variation in lesion appearance. We propose OpenMAP-HIE, a pathology-informed score-based diffusion model for unsupervised HIE lesion localization without voxel-wise lesion supervision. A denoising diffusion model learns the healthy neonatal ADC distribution, while a ControlNet-based conditional branch preserves patient-specific anatomy. At inference, anomaly evidence is derived directly from differences between conditional and unconditioned noise predictions at independently evaluated diffusion noise levels, avoiding dependence on a final pseudo-healthy reconstruction or sequential reverse-diffusion chain. Based on the characteristic ADC reduction associated with acute HIE, only discrepancies consistent with the expected pathological direction are retained and aggregated across noise levels using a geometric mean. Spatial mean filtering further suppresses isolated responses. The framework was evaluated on the BONBID-HIE dataset. The ADC-only method achieved a Dice score of 0.283 ± 0.097, average precision of 0.505, Hausdorff distance of 25.45 ± 15.63 mm, mean average surface distance of 9.40 ± 8.49 mm, and normalized surface Dice of 0.355 ± 0.236, providing the best overlap and surface-distance performance among the evaluated unsupervised methods and Dice performance comparable to supervised ADC-only models. Optional population-derived ADC Z-map refinement further increased Dice to 0.602 ± 0.055. These findings support pathology-informed score discrepancies as a useful signal for neonatal HIE lesion localization, while highlighting remaining challenges in detecting small and low-contrast lesions.
---
