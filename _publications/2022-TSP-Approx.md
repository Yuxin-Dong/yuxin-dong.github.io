---
title: "Computationally Efficient Approximations for Matrix-Based Rényi's Entropy"
collection: publications
permalink: /publication/2022-TSP-Approx
year: 2022
venue: IEEE Transactions on Signal Processing
link: "https://ieeexplore.ieee.org/abstract/document/10005826/"
author: "Tieliang Gong<sup>*</sup>, <strong>Yuxin Dong</strong><sup>*</sup>, Shujian Yu, Bo Dong"
pdf: "2022-TSP-Approx.pdf"
---

## Abstract

The recently developed matrix-based Rényi's $\alpha$-order entropy enables measurement of information in data simply using the eigenspectrum of symmetric positive semi-definite (PSD) matrices in reproducing kernel Hilbert space, without estimation of the underlying data distribution. This intriguing property makes this new information measurement widely adopted in multiple statistical inference and learning tasks. However, the computation of such quantity involves the trace operator on a PSD matrix $G$ to power $\alpha$ (i.e., $\mathrm{tr}(G^\alpha)$), with a normal complexity of nearly $\mathcal{O}(n^3)$, which severely hampers its practical usage when the number of samples (i.e., $n$) is large. In this work, we present computationally efficient approximations to this new entropy functional that can reduce its complexity to even significantly less than $\mathcal{O}(n^2)$. To this end, we leverage the recent progress on Randomized Numerical Linear Algebra, developing Taylor, Chebyshev and Lanczos approximations to $\mathrm{tr}(G^\alpha)$ for arbitrary values of $\alpha$ by converting it into a matrix-vector multiplication problem. We also establish the connection between the matrix-based Rényi's entropy and PSD matrix approximation, which enables exploiting both clustering and block low-rank structure of $G$ to further reduce the computational cost. We theoretically provide approximation accuracy guarantees and illustrate the properties for different approximations. Large-scale experimental evaluations on both synthetic and real-world data corroborate our theoretical findings, showing promising speedup with negligible loss in accuracy.

## Cite

```bibtex
@article{gong2022computationally,
  title={Computationally Efficient Approximations for Matrix-Based R{\'e}nyi's Entropy},
  author={Gong, Tieliang and Dong, Yuxin and Yu, Shujian and Dong, Bo},
  journal={IEEE Transactions on Signal Processing},
  volume={70},
  pages={6170--6184},
  year={2022},
  publisher={IEEE}
}
```
