---
title: "A Representation Model for Biological Entities by Fusing Structured Axioms with Unstructured Texts"
collection: publications
permalink: /publication/2021-Bioinfo-ERBK
year: 2021
venue: Bioinformatics
link: "https://academic.oup.com/bioinformatics/article-abstract/37/8/1156/5941463"
author: "Peiliang Lou, <strong>Yuxin Dong</strong>, Antonio Jimeno Yepes, Chen Li"
code: "https://gitlab.com/BioAI/erbk"
pdf: "2021-Bioinfo-ERBK.pdf"
---

## Abstract

**Motivation**: Structured semantic resources, for example, biological knowledge bases and ontologies, formally define biological concepts, entities and their semantic relationships, manifested as structured axioms and unstructured texts (e.g. textual definitions). The resources contain accurate expressions of biological reality and have been used by machine-learning models to assist intelligent applications like knowledge discovery. The current methods use both the axioms and definitions as plain texts in representation learning (RL). However, since the axioms are machine-readable while the natural language is human-understandable, difference in meaning of token and structure impedes the representations to encode desirable biological knowledge.

**Results**: We propose ERBK, a RL model of bio-entities. Instead of using the axioms and definitions as a textual corpus, our method uses knowledge graph embedding method and deep convolutional neural models to encode the axioms and definitions respectively. The representations could not only encode more underlying biological knowledge but also be further applied to zero-shot circumstance where existing approaches fall short. Experimental evaluations show that ERBK outperforms the existing methods for predicting protein–protein interactions and gene–disease associations. Moreover, it shows that ERBK still maintains promising performance under the zero-shot circumstance. We believe the representations and the method have certain generality and could extend to other types of bio-relation.

## Cite

```bibtex
@article{lou2021representation,
  title={A representation model for biological entities by fusing structured axioms with unstructured texts},
  author={Lou, Peiliang and Dong, Yuxin and Jimeno Yepes, Antonio and Li, Chen},
  journal={Bioinformatics},
  volume={37},
  number={8},
  pages={1156--1163},
  year={2021},
  publisher={Oxford University Press}
}
```
