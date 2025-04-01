---
title: "Towards Generalization beyond Pointwise Learning: A Unified Information-theoretic Perspective"
collection: publications
permalink: /publication/2024-ICML-Pairwise
year: 2024
venue: International Conference on Machine Learning
link: "https://proceedings.mlr.press/v235/dong24a.html"
author: "<strong>Yuxin Dong</strong>, Tieliang Gong, Hong Chen, Mengxiang Li, Zhongjiang He, Shuangyong Song, Chen Li"
pdf: "2024-ICML-Pairwise.pdf"
code: "https://github.com/Yuxin-Dong/Pairwise"
---

## Abstract

Information-theoretic generalization analysis has achieved astonishing success in characterizing the generalization capabilities of noisy and iterative learning algorithms. However, current advancements are mostly restricted to average-case scenarios and necessitate the stringent bounded loss assumption, leaving a gap with regard to computationally tractable PAC generalization analysis, especially for long-tailed loss distributions. In this paper, we bridge this gap by introducing a novel class of PAC bounds through leveraging loss entropies. These bounds simplify the computation of key information metrics in previous PAC information-theoretic bounds to one-dimensional variables, thereby enhancing computational tractability. Moreover, our data-independent bounds provide novel insights into the generalization behavior of the minimum error entropy criterion, while our data-dependent bounds improve over previous results by alleviating the bounded loss assumption under both leave-one-out and supersample settings. Extensive numerical studies indicate strong correlations between the generalization error and the induced loss entropy, showing that the presented bounds adeptly capture the patterns of the true generalization gap under various learning scenarios.

## Cite

```bibtex
@inproceedings{dong2024towards,
  title={Towards Generalization beyond Pointwise Learning: A Unified Information-theoretic Perspective},
  author={Yuxin Dong and Tieliang Gong and Hong Chen and Mengxiang Li and Zhongjiang He and Shuangyong Song and Chen Li},
  booktitle={International Conference on Machine Learning},
  year={2024},
  organization={PMLR}
}
```
