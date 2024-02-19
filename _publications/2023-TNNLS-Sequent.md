---
title: "Efficient Approximations for Matrix-Based Rényi’s Entropy on Sequential Data"
collection: publications
permalink: /publication/2023-TNNLS-Sequent
year: 2023
venue: IEEE Transactions on Neural Networks and Learning Systems
link: "https://ieeexplore.ieee.org/abstract/document/10255374/"
author: "<strong>Yuxin Dong</strong>, Tieliang Gong, Hong Chen, Chen Li"
pdf: "2023-TNNLS-Sequent.pdf"
---

## Abstract

The matrix-based Rényi’s entropy has recently been introduced as a substitute for the original Rényi’s entropy that could be directly obtained from data samples, avoiding the expensive intermediate step of density estimation. Despite its remarkable success in a broad of information-related tasks, the computational cost of matrix-based Rényi’s entropy however becomes a bottleneck for large-scale applications. The challenge, when facing sequential data, is further amplified due to the requirement of large-scale eigenvalue decomposition on multiple dense kernel matrices constructed by sliding windows in the region of interest, resulting in $O(mn^3)$ overall time complexity where $m, n$ denote the number and the size of windows respectively. To overcome this issue, we adopt the static matrix-based Rényi’s entropy estimator together with a variance reduction criterion to develop randomized approximations for the target entropy, leading to high accuracy with substantially lower query complexity by utilizing the historical estimation results. Specifically, assuming that the changes of adjacent sliding windows are bounded by $\beta \ll 1$ which is a trivial case in domains e.g. time series analysis, we lower the complexity by a factor of $\sqrt{\beta}$. Polynomial approximation techniques are further adopted to support arbitrary $\alpha$ orders. In general, our algorithms achieve $O(mn^2\sqrt{\beta}st)$ total computational complexity, where $s, t \ll n$ denote the number of vector queries and the polynomial degrees respectively. Theoretical upper and lower bounds are established in terms of the convergence rate for both $s$ and $t$, and large-scale experiments on both simulation and real-world data are conducted to validate the effectiveness of our algorithms. The results show that our methods achieve promising speedup with only a trivial loss in performance.

## Cite

```bibtex
@article{dong2023efficient,
  title={Efficient Approximations for Matrix-Based R{\'e}nyi’s Entropy on Sequential Data},
  author={Dong, Yuxin and Gong, Tieliang and Chen, Hong and Li, Chen},
  journal={IEEE Transactions on Neural Networks and Learning Systems},
  year={2023},
  publisher={IEEE}
}
```
