---
title: "Optimal Randomized Approximations for Matrix-based Rényi's Entropy"
collection: talks
type: "Poster"
permalink: /talks/2023-VALSE-Optimal
venue: "Vision and Learning Seminar"
date: 2023-06-10
location: "Wuxi, China"
link: "http://valser.org/2023/#/poster"
---

## Abstract

The Matrix-based Rényi's entropy enables us to directly measure information quantities from given data without the costly probability density estimation of underlying distributions, thus has been widely adopted in numerous statistical learning and inference tasks. However, exactly calculating this new information quantity requires access to the eigenspectrum of a semi-positive definite (SPD) matrix $A$ which grows linearly with the number of samples $n$, resulting in a $O(n^3)$ time complexity that is prohibitive for large-scale applications. To address this issue, this paper takes advantage of stochastic trace approximations for matrix-based Rényi's entropy with arbitrary $\alpha \in \mathbb{R}^+$ orders, lowering the complexity by converting the entropy approximation to a matrix-vector multiplication problem. Specifically, we develop random approximations for integer-order $\alpha$ cases and polynomial series approximations (Taylor and Chebyshev) for fractional $\alpha$ cases, leading to a $O(n^2sm)$ overall time complexity, where $s, m \ll n$ denote the number of vector queries and the polynomial order respectively. We theoretically establish statistical guarantees for all approximation algorithms and give explicit order of $s$ and $m$ with respect to the approximation error $\epsilon$, showing optimal convergence rate for both parameters up to a logarithmic factor. Large-scale simulations and real-world applications validate the effectiveness of the developed approximations, demonstrating remarkable speedup with negligible loss in accuracy.

## Poster

![]({{ site.url }}{{ site.baseurl }}/images/2023-TIT-Optimal.jpg)
