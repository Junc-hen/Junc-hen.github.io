---
title: "Propagating asymptotic-estimated gradients for low bitwidth quantized neural networks"
collection: publications
permalink: /publication/jstsp
excerpt: ''
date: 2020-1-13
venue: 'IEEE Journal of Selected Topics in Signal Processing'
paperurl: ''
citation: '<b>Jun Chen</b>, Yong Liu, Hao Zhang, Shengnan Hou and Jian Yang. &quot;Propagating asymptotic-estimated gradients for low bitwidth quantized neural networks. &quot; <i>IEEE Journal of Selected Topics in Signal Processing</i>. 2020.'
---
## Abstract

The quantized neural networks (QNNs) can be useful for neural network acceleration and compression, but during the training process they pose a challenge: how to propagate the gradient of loss function through the graph flow with a derivative of 0 almost everywhere. In response to this non-differentiable situation, we propose a novel Asymptotic-Quantized Estimator (AQE) to estimate the gradient. In particular, during back-propagation, the graph that relates inputs to output remains smoothness and differentiability. At the end of training, the weights and activations have been quantized to low-precision because of the asymptotic behaviour of AQE. Meanwhile, we propose a M-bit Inputs and N-bit Weights Network (MINW-Net) trained by AQE, a quantized neural network with 1-3 bits weights and activations. In the inference phase, we can use XNOR or SHIFT operations instead of convolution operations to accelerate the MINW-Net. Our experiments on CIFAR datasets demonstrate that our AQE is well defined, and the QNNs with AQE perform better than that with Straight-Through Estimator (STE). For example, in the case of the same ConvNet that has 1-bit weights and activations, our MINW-Net with AQE can achieve a prediction accuracy 1.5% higher than the Binarized Neural Network (BNN) with STE. The MINW-Net, which is trained from scratch by AQE, can achieve comparable classification accuracy as 32-bit counterparts on CIFAR test sets. Extensive experimental results on ImageNet dataset show great superiority of the proposed AQE and our MINW-Net achieves comparable results with other state-of-the-art QNNs.


[Download paper here](http://junc-hen.github.io/files/jstsp.pdf)