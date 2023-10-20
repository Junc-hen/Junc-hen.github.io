---
title: "A Learning Framework for n-Bit Quantized Neural Networks Toward FPGAs"
collection: publications
permalink: /publication/tnnls2020
excerpt: ''
date: 2020-4-3
venue: 'IEEE Transactions on Neural Networks and Learning Systems'
paperurl: ''
citation: '<b>Jun Chen</b>, Liang Liu, Yong Liu and Xianfang Zeng. &quot; A Learning Framework for n-Bit Quantized Neural Networks Toward FPGAs. &quot; <i>IEEE Transactions on Neural Networks and Learning Systems</i>. 2020.'
---
## Abstract

The quantized neural network (QNN) is an efficient approach for network compression and can be widely used in the implementation of field-programmable gate arrays (FPGAs). This article proposes a novel learning framework for n-bit QNNs, whose weights are constrained to the power of two. To solve the gradient vanishing problem, we propose a reconstructed gradient function for QNNs in the back-propagation algorithm that can directly get the real gradient rather than estimating an approximate gradient of the expected loss. We also propose a novel QNN structure named n-BQ-NN, which uses shift operation to replace the multiply operation and is more suitable for the inference on FPGAs. Furthermore, we also design a shift vector processing element (SVPE) array to replace all 16-bit multiplications with SHIFT operations in convolution operation on FPGAs. We also carry out comparable experiments to evaluate our framework. The experimental results show that the quantized models of ResNet, DenseNet, and AlexNet through our learning framework can achieve almost the same accuracies with the original fullprecision models. Moreover, when using our learning framework to train our n-BQ-NN from scratch, it can achieve state-of-the-art results compared with typical low-precision QNNs. Experiments on Xilinx ZCU102 platform show that our n-BQ-NN with our SVPE can execute 2.9 times faster than that with the vector processing element (VPE) in inference. As the SHIFT operation in our SVPE array will not consume digital signal processing (DSP) resources on FPGAs, the experiments have shown that the use of SVPE array also reduces average energy consumption to 68.7% of the VPE array with 16 bit.


[Download paper here](http://junc-hen.github.io/files/tnnls2020.pdf)