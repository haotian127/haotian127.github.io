---
title: "Natural Graph Wavelet Dictionaries: Methods and Applications"
collection: talks
type: "Talk"
permalink: /talks/PhD_Exit_Seminar
venue: "UC Davis"
date: 2021-06-07
location: "Davis, CA"
---

This is my PhD exit seminar! The graph Laplacian is widely used in the graph signal processing field. When attempting to design graph wavelet transforms, people have been using its eigenvalues and eigenvectors in place of the frequencies and complex exponentials that are the backbone of the Fourier theory on Euclidean domains. However, this viewpoint could be misleading since the Laplacian eigenvalues cannot be interpreted as the frequencies of the eigenvectors on a general graph. Instead, we introduce and review several "natural" metrics of graph Laplacian eigenvectors, and propose a new way to naturally organize the eigenvectors by incorporating these metrics into a "dual" graph. We then introduce a set of novel multiscale basis transforms for graph signals fully utilizing this dual graph, rather than simply using the eigenvalue ordering. These basis dictionaries can be seen as generalizations of the classical Shannon/Meyer wavelet packet dictionary to arbitrary graphs, and do not rely on the frequency interpretation of Laplacian eigenvalues. We describe the algorithms (involving vector rotations, or orthogonalizations, or lapped orthogonal projections) to efficiently approximate and compress signals through the best-basis algorithm, and demonstrate the strengths of these basis dictionaries for graph signals on sunflower graphs and road traffic networks. Lastly, we propose a way to modify the spectral filters in the spectral graph wavelet transform by utilizing the structure of the dual graph instead of using the eigenvalue-dependent smooth functions. By doing so, we generate a redundant wavelet frame, propose a way to reduce its redundancy, and discuss its potential for applications. 

[Get the Slides](https://haotian127.github.io/files/PhD_Exit_Seminar.pdf)
