---
title: "DCCD: Reducing Neural Network Redundancy via Distillation"
collection: publications
permalink: /publication/tnnls2023
excerpt: ''
date: 2023-1-30
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: ''
citation: 'Yuang Liu*, <b>Jun Chen*</b> and Yong Liu. &quot; DCCD: Reducing Neural Network Redundancy via Distillation. &quot; <i>IEEE Transactions on Neural Networks and Learning Systems</i>. 2023.'
---
## Abstract

Deep neural models have achieved remarkable performance on various supervised and unsupervised learning tasks, but it is a challenge to deploy these large-size networks on resource-limited devices. As a representative type of model compression and acceleration methods, knowledge distillation (KD) solves this problem by transferring knowledge from heavy teachers to lightweight students. However, most distillation methods focus on imitating the responses of teacher networks but ignore the information redundancy of student networks. In this article, we propose a novel distillation framework difference-based channel contrastive distillation (DCCD), which introduces channel contrastive knowledge and dynamic difference knowledge into student networks for redundancy reduction. At the feature level, we construct an efficient contrastive objective that broadens student networks’ feature expression space and preserves richer information in the feature extraction stage. At the final output level, more detailed knowledge is extracted from teacher networks by making a difference between multiview augmented responses of the same instance. We enhance student networks to be more sensitive to minor dynamic changes. With the improvement of two aspects of DCCD, the student network gains contrastive and difference knowledge and reduces its overfitting and redundancy. Finally, we achieve surprising results that the student approaches and even outperforms the teacher in test accuracy on CIFAR-100. We reduce the top-1 error to 28.16% on ImageNet classification and 24.15% for cross-model transfer with ResNet-18. Empirical experiments and ablation studies on popular datasets show that our proposed method can achieve state-of-the-art accuracy compared with other distillation methods.


[Download paper here](http://junc-hen.github.io/files/tnnls2023.pdf)