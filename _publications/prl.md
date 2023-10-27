---
title: "Multi-Dimension Compression of Feed-Forward Network in Vision Transformers"
collection: publications
permalink: /publication/prl
excerpt: ''
date: 2023-10-20
venue: 'Pattern Recognition Letters'
paperurl: ''
citation: 'Shipeng Bai*, <b>Jun Chen*</b>, Yu Yang and Yong Liu. &quot; Multi-Dimension Compression of Feed-Forward Network in Vision Transformers. &quot; <i>Pattern Recognition Letters</i>. 2023.'
---
## Abstract

Vision Transformers (ViTs) have recently made a splash in computer vision domain and achieved state-of-the-art in many vision tasks. Nevertheless, due to their vast model size and high computational costs, rare transformer-based models are adopted in real-world applications. Since the computational costs of attention operation is the square of the input size, some compression methods for the Multi-Head Self-Attention (MHSA) module have been proposed, reducing its FLOPs successfully but almost without parameters reduction. Meanwhile, the number of parameters and computational costs in the Feed-Forward Network (FFN) module exceeds the MHSA larger, while its compression technologies have not been delved deeper. Consequently, we focus our insight on the compression of FFN layer and present a pruning method named Multi-Dimension Compression of Feed-Forward Network in Vision Transformers(MCF), which greatly reduces the model’s parameters and computational costs. Firstly, we identify the critical elements in the output of the FFN module and then employ them to guide the irregular sparsity of this layer, recognizing insignificant elements of FFN layer that have less impact on the output. Successively, to discard the insignificant elements, we transform the irregular sparsity into regular sparsity and prune them, thus reducing the models’ parameters and getting a substantial speed-up during inference. Extensive results on ImageNet-1K validate the effectiveness of our proposed method, which obtains significant parameters and computational costs reduction with almost unimpaired generalization. For example, we compress DeiT-Tiny with 42% reduction in FLOPs and 33% reduction in parameters, almost without losing accuracy on the ImageNet dataset. Further, we verify the effectiveness of our method in the downstream task, using the pruned DeiT-Small as the backbone for the object detection task on the COCO dataset, gaining revenue without compromising its performance.


[Download paper here](http://junc-hen.github.io/files/prl.pdf)