---
title: "Learning Discretized Neural Networks under Ricci Flow"
collection: talks
type: ""
permalink: /talks/jmlr
date: 2023-4-25
venue: <b>Jun Chen</b>, Hanwen Chen, Mengmeng Wang, Guang Dai, Ivor W.Tsang and Yong Liu. &quot; Learning Discretized Neural Networks under Ricci Flow. &quot; <i>ArXiv</i>. 2023.
description: "<b>Jun Chen</b>, Hanwen Chen, Mengmeng Wang, Guang Dai, Ivor W.Tsang and Yong Liu. &quot; Learning Discretized Neural Networks under Ricci Flow. &quot; <i>ArXiv</i>. 2023."
---
## Abstract

In this paper, we consider Discretized Neural Networks (DNNs) consisting of low-precision weights and activations, which suffer from either infinite or zero gradients due to the non-differentiable discrete function in the training process. In this case, most training-based DNNs employ the standard Straight-Through Estimator (STE) to approximate the gradient w.r.t. discrete values. However, the STE gives rise to the problem of gradient mismatch, due to the perturbations of the approximated gradient. To address this problem, this paper reveals that this mismatch can be viewed as a metric perturbation in a Riemannian manifold through the lens of duality theory. Further, on the basis of the information geometry, we construct the Linearly Nearly Euclidean (LNE) manifold for DNNs as a background to deal with perturbations. By introducing a partial differential equation on metrics, i.e., the Ricci flow, we prove the dynamical stability and convergence of the LNE metric with the L2-norm perturbation. Unlike the previous perturbation theory whose convergence rate is the fractional powers, the metric perturbation under the Ricci flow can be exponentially decayed in the LNE manifold. The experimental results on various datasets demonstrate that our method achieves better and more stable performance for DNNs than other representative training-based methods.


[Download paper here](http://junc-hen.github.io/files/jmlr.pdf)