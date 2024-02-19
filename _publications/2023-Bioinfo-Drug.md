---
title: "Dual Attention and Patient Similarity Network for Drug Recommendation"
collection: publications
permalink: /publication/2023-Bioinfo-Drug
year: 2023
venue: Bioinformatics
link: "https://academic.oup.com/bioinformatics/article-abstract/39/1/btad003/6972773"
author: "Jialun Wu, <strong>Yuxin Dong</strong>, Zeyu Gao, Tieliang Gong, and Chen Li"
pdf: "2023-Bioinfo-Drug.pdf"
code: "https://github.com/andylun96/DAPSNet"
---

## Abstract

**Motivation**: Artificially making clinical decisions for patients with multi-morbidity has long been considered a thorny problem due to the complexity of the disease. Drug recommendations can assist doctors in automatically providing effective and safe drug combinations conducive to treatment and reducing adverse reactions. However, the existing drug recommendation works ignored two critical information. (i) Different types of medical information and their interrelationships in the patient’s visit history can be used to construct a comprehensive patient representation. (ii) Patients with similar disease characteristics and their corresponding medication information can be used as a reference for predicting drug combinations.

**Results**: To address these limitations, we propose DAPSNet, which encodes multi-type medical codes into patient representations through code- and visit-level attention mechanisms, while integrating drug information corresponding to similar patient states to improve the performance of drug recommendation. Specifically, our DAPSNet is enlightened by the decision-making process of human doctors. Given a patient, DAPSNet first learns the importance of patient history records between diagnosis, procedure and drug in different visits, then retrieves the drug information corresponding to similar patient disease states for assisting drug combination prediction. Moreover, in the training stage, we introduce a novel information constraint loss function based on the information bottleneck principle to constrain the learned representation and enhance the robustness of DAPSNet. We evaluate the proposed DAPSNet on the public MIMIC-III dataset, our model achieves relative improvements of 1.33%, 1.20% and 2.03% in Jaccard, F1 and PR-AUC scores, respectively, compared to state-of-the-art methods.

**Availability and implementation** The source code is available at the [Github repository](https://github.com/andylun96/DAPSNet).

## Cite

```bibtex
@article{wu2023dual,
  title={Dual Attention and Patient Similarity Network for Drug Recommendation},
  author={Wu, Jialun and Dong, Yuxin and Gao, Zeyu and Gong, Tieliang and Li, Chen},
  journal={Bioinformatics},
  volume={39},
  number={1},
  pages={btad003},
  year={2023},
  publisher={Oxford University Press}
}
```
