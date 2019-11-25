---
title: 'Graph Neural Networks'
date: 2019-11-21
permalink: /posts/2019/11/Graph-Neural-Networks/
tags:
  - graph neural networks
  - graph convolutional networks
  - graph wavelet neural networks
---

Two interesting GitHub repositories about graph neural networks:

* Graph Convolution Networks: [https://github.com/tkipf/gcn](https://github.com/tkipf/gcn)

* Graph Wavelet Neural Networks: [https://github.com/Eilene/GWNN](https://github.com/Eilene/GWNN)

A nice review paper: [Graph Neural Networks: A Review of Methods and Applications](https://arxiv.org/pdf/1812.08434.pdf)

Abstract
-------
Lots of learning tasks require dealing with graph data which contains rich relation information among elements. Modeling physics system, learning molecular fingerprints, predicting protein interface, and classifying diseases require a model to learn from graph inputs. In other domains such as learning from non-structural data like texts and images, reasoning on extracted structures, like the dependency tree of sentences and the scene graph of images, is an important research topic which also needs graph reasoning models. Graph neural networks (GNNs) are connectionist models that capture the dependence of graphs via message passing between the nodes of graphs. Unlike standard neural networks, graph neural networks retain a state that can represent information from its neighborhood with arbitrary depth. Although the primitive GNNs have been found difficult to train for a fixed point, recent advances in network architectures, optimization techniques, and parallel computation have enabled successful learning with them. In recent years, systems based on variants of graph neural networks such as graph convolutional network (GCN), graph attention network (GAT), gated graph neural network (GGNN) have demonstrated ground-breaking performance on many tasks mentioned above. In this survey, we provide a detailed review over existing graph neural network models, systematically categorize the applications, and propose four open problems for future research.
