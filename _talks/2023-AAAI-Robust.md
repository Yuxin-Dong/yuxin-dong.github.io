---
title: "Robust and Fast Measure of Information via Low-Rank Representation"
collection: talks
type: "Conference Talk"
permalink: /talks/2023-AAAI-Robust
venue: "AAAI Conference on Artificial Intelligence"
date: 2023-02-07
location: "Washington, D.C., USA"
---

## Abstract

The matrix-based Rényi’s entropy allows us to directly quantify information measures from given data, without explicit estimation of the underlying probability distribution. This intriguing property makes it widely applied in statistical inference and machine learning tasks. However, this information theoretical quantity is not robust against noise in the data, and is computationally prohibitive in large-scale applications. To address these issues, we propose a novel measure of information, termed low-rank matrix-based Rényi’s entropy, based on low-rank representations of infinitely divisible kernel matrices. The proposed entropy functional inherits the specialty of of the original definition to directly quantify information from data, but enjoys additional advantages including robustness and effective calculation. Specifically, our low-rank variant is more sensitive to informative perturbations induced by changes in underlying distributions, while being insensitive to uninformative ones caused by noises. Moreover, low-rank Rényi’s entropy can be efficiently approximated by random projection and Lanczos iteration techniques, reducing the overall complexity from $\mathcal{O}(n^3)$ to $\mathcal{O}(n^2 s)$ or even $\mathcal{O}(ns^2)$, where $n$ is the number of data samples and $s \ll n$. We conduct large-scale experiments to evaluate the effectiveness of this new information measure, demonstrating superior results compared to matrix-based Rényi’s entropy in terms of both performance and computational efficiency.

## Slides

<div class="responsive-wrap">
  <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vRDTMclMC6lZe5X_L1uH2FtnjbZ4mzmiqH0z7SVyDVgxM9JCemBzYO2Ja_0k7BGzOMcqH89746ZZNFA/embed?start=false&loop=false&delayms=3000" frameborder="0" width="800" height="480" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

## Poster

![]({{ site.url }}{{ site.baseurl }}/images/2023-AAAI-Robust.png)
