---
title: "Understanding the Generalization Ability of Deep Learning Algorithms: A Kernelized Rényi’s Entropy Perspective"
collection: publications
permalink: /publication/2023-IJCAI-KRE
year: 2023
venue: International Joint Conference on Artificial Intelligence
link: "https://www.ijcai.org/proceedings/2023/405"
author: "<strong>Yuxin Dong</strong>, Tieliang Gong, Hong Chen, Chen Li"
pdf: "2023-IJCAI-KRE.pdf"
code: "https://github.com/Yuxin-Dong/KRE"
---

## Abstract

Recently, information-theoretic analysis has become a popular framework for understanding the generalization behavior of deep neural networks. It allows a direct analysis for stochastic gradient / Langevin descent (SGD/SGLD) learning algorithms without strong assumptions such as Lipschitz or convexity conditions. However, the current generalization error bounds within this framework are still far from optimal, while substantial improvements on these bounds are quite challenging due to the intractability of high-dimensional information quantities. To address this issue, we first propose a novel information theoretical measure: kernelized Rényi's entropy, by utilizing operator representation in Hilbert space. It inherits the properties of Shannon's entropy and can be effectively calculated via simple random sampling, while remaining independent of the input dimension. We then establish the generalization error bounds for SGD/SGLD under kernelized Rényi's entropy, where the mutual information quantities can be directly calculated, enabling evaluation of the tightness of each intermediate step. We show that our information-theoretical bounds depend on the statistics of the stochastic gradients evaluated along with the iterates, and are rigorously tighter than the current state-of-the-art (SOTA) results. The theoretical findings are also supported by large-scale empirical studies.

## Slides

<div class="responsive-wrap">
  <iframe src="https://docs.google.com/presentation/d/e/2PACX-1vSJXy5lu1AR7wvGHOJ7r9_RjEh2wYhbnWJAmySmayS5rVmYubV6T1oGWsaIC8ZMLTAFJHFXB_H0-shf/embed?start=false&loop=false&delayms=3000" frameborder="0" width="800" height="480" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>
</div>

## Poster

![]({{ site.url }}{{ site.baseurl }}/images/2023-IJCAI-KRE.png)

## Cite

```bibtex
@inproceedings{dong2023understanding,
  title={Understanding the Generalization Ability of Deep Learning Algorithms: A Kernelized Rényi's Entropy Perspective},
  author={Dong, Yuxin and Gong, Tieliang and Chen, Hong and Li, Chen},
  booktitle={Proceedings of the International Joint Conference on Artificial Intelligence},
  pages={3642--3650},
  year={2023},
  month={8}
}
```
