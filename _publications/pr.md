---
title: "A Data-Free Quantization via Mixed-Precision Compensation without Fine-Tuning"
collection: publications
permalink: /publication/pr
excerpt: ''
date: 2023-6-26
venue: 'Pattern Recognition'
paperurl: ''
citation: '<b>Jun Chen</b>, Shipeng Bai, Tianxin Huang, Mengmeng Wang, Guanzhong Tian and Yong Liu. &quot; A Data-Free Quantization via Mixed-Precision Compensation without Fine-Tuning. &quot; <i>Pattern Recognition</i>. 2023.'
---
## Abstract

Neural network quantization is a very promising solution in the field of model compression, but its resulting accuracy highly depends on a training/fine-tuning process and requires the original data. This not only brings heavy computation and time costs but also is not conducive to privacy and sensitive information protection. Therefore, a few recent works are starting to focus on data-free quantization. However, data-free quantization does not perform well while dealing with ultra-low precision quantization. Although researchers utilize generative methods of synthetic data to address this problem partially, data synthesis needs to take a lot of computation and time. In this paper, we propose a data-free mixed-precision compensation (DF-MPC) method to recover the performance of an ultra-low precision quantized model without any data and fine-tuning process. By assuming the quantized error caused by a low-precision quantized layer can be restored via the reconstruction of a high-precision quantized layer, we mathematically formulate the reconstruction loss between the pre-trained full-precision model and its layer-wise mixed-precision quantized model. Based on our formulation, we theoretically deduce the closed-form solution by minimizing the reconstruction loss of the feature maps. Since DF-MPC does not require any original/synthetic data, it is a more efficient method to approximate the full-precision model. Experimentally, our DF-MPC is able to achieve higher accuracy for an ultra-low precision quantized model compared to the recent methods without any data and fine-tuning process.


[Download paper here](http://junc-hen.github.io/files/pr.pdf)