---
title: "Pruning by Training: A Novel Deep Neural Network Compression Framework for Image Processing"
collection: publications
permalink: /publication/spl
excerpt: ''
date: 2021-1-25
venue: 'IEEE Signal Processing Letters'
paperurl: ''
citation: 'Guanzhong Tian*, <b>Jun Chen*</b>, Xianfang Zeng and Yong Liu. &quot; Pruning by Training: A Novel Deep Neural Network Compression Framework for Image Processing. &quot; <i>IEEE Signal Processing Letters</i>. 2021.'
---
## Abstract

Filter pruning for a pre-trained convolutional neural network is most normally performed through human-made constraints or criteria such as norms, ranks, etc. Typically, the pruning pipeline comprises two-stage: first learn a sparse structure from the original model, then optimize the weights in the new prune model. One disadvantage of using human-made criteria to prune filters is that the design and selection of threshold criteria depend on complicated prior knowledge. Besides, the pruning process is less robust due to the impact of directly regularizing on filters. To address the problems mentioned, we propose an effective one-stage pruning framework: introducing a trainable collaborative layer to jointly prune and learn neural networks in one go. In our framework, we first add a binary collaborative layer for each original filter. Then, a new type of gradient estimator - asymptotic gradient estimator is first introduced to pass the gradient in the binary collaborative layer. Finally, we simultaneously learn the sparse structure and optimize the weights from the original model in the training process. Our evaluation results on typical benchmarks, CIFAR and ImageNet, demonstrate very promising results against other state-of-the-art filter pruning methods.


[Download paper here](http://junc-hen.github.io/files/spl.pdf)