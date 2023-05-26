---
title: "Finding Low-Rank Functions Using Linear Layers in Neural Networks"
collection: talks
type: "Talk"
permalink: /talks/CAMseminar2023.md
venue: "University of Chicago Computational and Applied Mathematics Student Seminar"
date: 2023-02-14
location: "Chicago, Illinois"
---

A fundamental question in the theory of neural networks is the role of depth. Empirically it is widely known that deeper networks tend to perform better than shallow ones. However, the reasoning behind this phenomenon is not well understood. In this talk I will discuss the role of depth in the simplified case where most of the layers have a linear activation. Specifically, the regularization associated with training a neural network with many linear layers followed by a single ReLu layer using weight decay is equivalent to a function-space penalty that encourages the network to select a low-rank function, i.e. one with small active subspace. [Slides](../files/CAM_Seminar_Linear_Layers_Talk.pdf)