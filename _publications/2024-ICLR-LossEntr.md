---
title: "Rethinking Information-theoretic Generalization: Loss Entropy Induced PAC Bounds"
collection: publications
permalink: /publication/2024-ICLR-LossEntr
year: 2024
venue: International Conference on Learning Representations
link: "https://openreview.net/forum?id=GWSIo2MzuH"
author: "<strong>Yuxin Dong</strong>, Tieliang Gong, Hong Chen, Shujian Yu, Chen Li"
pdf: "2024-ICLR-LossEntr.pdf"
code: "https://github.com/Yuxin-Dong/Loss-Entropy"
---

## Abstract

Information-theoretic generalization analysis has achieved astonishing success in characterizing the generalization capabilities of noisy and iterative learning algorithms. However, current advancements are mostly restricted to average-case scenarios and necessitate the stringent bounded loss assumption, leaving a gap with regard to computationally tractable PAC generalization analysis, especially for long-tailed loss distributions. In this paper, we bridge this gap by introducing a novel class of PAC bounds through leveraging loss entropies. These bounds simplify the computation of key information metrics in previous PAC information-theoretic bounds to one-dimensional variables, thereby enhancing computational tractability. Moreover, our data-independent bounds provide novel insights into the generalization behavior of the minimum error entropy criterion, while our data-dependent bounds improve over previous results by alleviating the bounded loss assumption under both leave-one-out and supersample settings. Extensive numerical studies indicate strong correlations between the generalization error and the induced loss entropy, showing that the presented bounds adeptly capture the patterns of the true generalization gap under various learning scenarios.

## Slides

<div class="responsive-wrap">
  <iframe src="https://docs.google.com/gview?url={{ site.url }}{{ site.baseurl }}/files/LossEntropy_Slides.pdf&embedded=true" style="width:800px; height:480px;" frameborder="0"></iframe>
</div>

## Poster

![]({{ site.url }}{{ site.baseurl }}/images/2024-ICLR-LossEntr.png)

## Cite

```bibtex
@inproceedings{dong2024rethinking,
  title={Rethinking Information-theoretic Generalization: Loss Entropy Induced {PAC} Bounds},
  author={Yuxin Dong and Tieliang Gong and Hong Chen and Shujian Yu and Chen Li},
  booktitle={The Twelfth International Conference on Learning Representations},
  year={2024},
  url={https://openreview.net/forum?id=GWSIo2MzuH}
}
```
