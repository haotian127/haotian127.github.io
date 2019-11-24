---
title: "Metrics of graph Laplacian eigenvectors"
collection: talks
type: "Talk"
permalink: /talks/Metrics_of_graph_Laplacian_eigenvectors
venue: "SPIE conference: Wavelets and Sparsity XVIII"
date: 2019-08-15
location: "San Diego, CA"
---

The application of graph Laplacian eigenvectors has been quite popular in the graph signal processing field: one can use them as ingredients to design smooth multiscale basis. Our long-term goal is to study and understand the dual geometry of graph Laplacian eigenvectors. In order to do that, it is necessary to define a certain metric to measure the behavioral differences between each pair of the eigenvectors. Saito (2018) considered the ramified optimal transportation (ROT) cost between the square of the eigenvectors as such a metric. Clonginger and Steinerberger (2018) proposed a way to measure the affinity (or ‘similarity’) between the eigenvectors based on their Hadamard (HAD) product. In this article, we propose a simplified ROT metric that is more computational efficient and introduce two more ways to define the distance between the eigenvectors, i.e., the time-stepping diffusion (TSD) metric and the difference of absolute gradient (DAG) pseudometric. The TSD metric measures the cost of “flattening” the initial graph signal via diffusion process up to certain time, hence it can be viewed as a time-dependent version of the ROT metric. The DAG pseudometric is the $l_2$-distance between the feature vectors derived from the eigenvectors, in particular, the absolute gradients of the eigenvectors. We then compare the performance of ROT, HAD and the two new “metrics” on different kinds of graphs. Finally, we investigate their relationship as well as their pros and cons.

[Get the Slides](https://haotian127.github.io/files/SPIE_Slides__Metrics_of_graph_Laplacian_eigenvectors.pdf)
