---
title: "Decentralized Riemannian Conjugate Gradient Method on the Stiefel Manifold"
collection: talks
type: "Talk"
permalink: /talks/drcgd
venue: "ArXiv"
date: 2023-8-21
citation: '<b>Jun Chen</b>, Haishan Ye, Mengmeng Wang, Tianxin Huang, Guang Dai, Ivor W.Tsang and Yong Liu. &quot; Decentralized Riemannian Conjugate Gradient Method on the Stiefel Manifold. &quot; <i>ArXiv</i>. 2023.'
---
## Abstract

The conjugate gradient method is a crucial first-order optimization method that generally converges faster than the steepest descent method, and its computational cost is much lower than the second-order methods. However, while various types of conjugate gradient methods have been studied in Euclidean spaces and on Riemannian manifolds, there has little study for those in distributed scenarios. This paper proposes a decentralized Riemannian conjugate gradient descent (DRCGD) method that aims at minimizing a global function over the Stiefel manifold. The optimization problem is distributed among a network of agents, where each agent is associated with a local function, and communication between agents occurs over an undirected connected graph. Since the Stiefel manifold is a non-convex set, a global function is represented as a finite sum of possibly non-convex (but smooth) local functions. The proposed method is free from expensive Riemannian geometric operations such as retractions, exponential maps, and vector transports, thereby reducing the computational complexity required by each agent. To the best of our knowledge, DRCGD is the first decentralized Riemannian conjugate gradient algorithm to achieve global convergence over the Stiefel manifold.


[Download paper here](http://junc-hen.github.io/files/drcgd.pdf)