---
title: "Optimal Randomized Approximations for Matrix-based Rényi's Entropy"
collection: publications
permalink: /publication/2023-TIT-Optimal
year: 2023
venue: IEEE Transactions on Information Theory
link: "https://ieeexplore.ieee.org/abstract/document/10077595/"
author: "<strong>Yuxin Dong</strong>, Tieliang Gong, Shujian Yu, Chen Li"
pdf: "2023-TIT-Optimal.pdf"
---

## Abstract

The Matrix-based Rényi's entropy enables us to directly measure information quantities from given data without the costly probability density estimation of underlying distributions, thus has been widely adopted in numerous statistical learning and inference tasks. However, exactly calculating this new information quantity requires access to the eigenspectrum of a semi-positive definite (SPD) matrix $A$ which grows linearly with the number of samples $n$, resulting in a $O(n^3)$ time complexity that is prohibitive for large-scale applications. To address this issue, this paper takes advantage of stochastic trace approximations for matrix-based Rényi's entropy with arbitrary $\alpha \in \mathbb{R}^+$ orders, lowering the complexity by converting the entropy approximation to a matrix-vector multiplication problem. Specifically, we develop random approximations for integer-order $\alpha$ cases and polynomial series approximations (Taylor and Chebyshev) for fractional $\alpha$ cases, leading to a $O(n^2sm)$ overall time complexity, where $s, m \ll n$ denote the number of vector queries and the polynomial order respectively. We theoretically establish statistical guarantees for all approximation algorithms and give explicit order of $s$ and $m$ with respect to the approximation error $\epsilon$, showing optimal convergence rate for both parameters up to a logarithmic factor. Large-scale simulations and real-world applications validate the effectiveness of the developed approximations, demonstrating remarkable speedup with negligible loss in accuracy.

## Poster

![]({{ site.url }}{{ site.baseurl }}/images/2023-TIT-Optimal.jpg)

## Cite

```bibtex
@article{dong2023optimal,
  title={Optimal Randomized Approximations for Matrix-based R{\'e}nyi’s Entropy},
  author={Dong, Yuxin and Gong, Tieliang and Yu, Shujian and Li, Chen},
  journal={IEEE Transactions on Information Theory},
  year={2023},
  publisher={IEEE}
}
```
