---
title: "Towards Diffeomorphism Invariant Convolution Neural Networks"
collection: publications
permalink: /publication/2021-diffeomorphism_invariant_cnn_DiffCVML-6
paper_image: publications/diffeomorphism.png
excerpt: "Develops convolutional blocks through jacobian space whose outputs are stable under diffeomorphic deformations of the input domain."
authors: "<strong>Pengyu Kan</strong>, Rudrasis Chakraborty, Vishnu Suresh Lokhande, Vikas Singh"
date: 2021-03-01
venue: "Differential Geometry in Computer Vision and Machine Learning workshop, CVPR"
paperurl: "https://pkan2.github.io/files/diffeomorphism_invariant_cnn_DiffCVML-6.pdf"
abstract: |
  Most deep neural networks are not natively invariant or equivariant to transformations of the data, e.g., when data samples transformed by a group action, the prediction of the model may change in arbitrary ways. Often, one resorts to data augmentation to tackle this problem. A number of recent ideas show how the network can be modified and endowed with such capabilities, that are variously useful in many applications including robustness. This route avoids the need for explicit data augmentation. In this work, we explore whether performs convolution in the jacobian space of images can offer benefits. We propose DiffCNN, a model which mitigates the performance drop many networks often face when presented with warped versions of the images they were trained on. Our preliminary results show that DiffCNN can minimize the need for data augmentation as well as offers robustness on CIFAR10 dataset relative several alternatives from the literature.
---
