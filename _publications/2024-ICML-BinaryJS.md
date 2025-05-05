---
title: "Exactly Tight Information-theoretic Generalization Bounds via Binary Jensen-Shannon Divergence"
collection: publications
permalink: /publication/2024-ICML-BinaryJS
year: 2025
venue: International Conference on Machine Learning
link: "https://openreview.net/forum?id=qfgtBeBLsD"
author: "<strong>Yuxin Dong</strong>, Haoran Guo, Tieliang Gong, Wen Wen, Chen Li"
pdf: "2024-ICML-BinaryJS.pdf"
code: "https://github.com/Yuxin-Dong/BinaryJS"
---

## Abstract

Information-theoretic bounds, while achieving significant success in analyzing the generalization of randomized learning algorithms, have been criticized for their slow convergence rates and overestimation. This paper presents novel bounds that bridge the expected empirical and population risks through a binarized variant of the Jensen-Shannon divergence. Leveraging our foundational lemma that characterizes the interaction between an arbitrary and a binary variable, we derive hypothesis-based bounds that enhance existing conditional mutual information bounds by reducing the number of conditioned samples from 2 to 1. We additionally establish prediction-based bounds that surpass prior bounds based on evaluated loss mutual information measures. Thereafter, through a new binarization technique for the evaluated loss variables, we obtain exactly tight generalization bounds broadly applicable to general randomized learning algorithms for any bounded loss functions. Our results effectively address key limitations of previous results in analyzing certain stochastic convex optimization problems, without requiring additional stability or compressibility assumptions about the learning algorithm.

## Cite

```bibtex
@inproceedings{dong2025exactly,
  title={Exactly Tight Information-theoretic Generalization Bounds via Binary Jensen-Shannon Divergence},
  author={Yuxin Dong and Haoran Guo and Tieliang Gong and Wen Wen and Chen Li},
  booktitle={International Conference on Machine Learning},
  year={2025},
  organization={PMLR}
}
```
