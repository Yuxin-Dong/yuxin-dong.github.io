---
title: "LibMI: An Open Source Library for Efficient Histopathological Image Processing"
collection: publications
permalink: /publication/2020-JPI-LibMI
year: 2020
venue: Journal of Pathology Informatics
link: "https://www.sciencedirect.com/science/article/pii/S2153353922002553"
author: "<strong>Yuxin Dong</strong>, Pargorn Puttapirat, Jingyi Deng, Xiangrong Zhang, Chen Li"
code: "https://gitlab.com/BioAI/libMI"
pdf: "2020-JPI-LibMI.pdf"
---

## Abstract

**Background**: Whole-slide images (WSIs) as a kind of image data are rapidly growing in the digital pathology domain. With unusual high resolution, these images make them hard to be supported by conventional tools or file formats. Thus, it obstructs data sharing and automated analysis. Here, we propose a library, LibMI, along with its open and standardized image file format. They can be used together to efficiently read, write, modify, and annotate large images. 

**Materials and Methods**: LibMI utilizes the concept of pyramid image structure and lazy propagation from a segment tree algorithm to support reading and modifying and to guarantee that both operations have linear time complexity. Further, a cache mechanism was introduced to speed up the program. 

**Results**: LibMI is an open and efficient library for histopathological image processing. To demonstrate its functions, we applied it to several tasks including image thresholding, microscopic color correction, and storing pixel-wise information on WSIs. The result shows that libMI is particularly suitable for modifying large images. Furthermore, compared with congeneric libraries and file formats, libMI and modifiable multiscale image (MMSI) run 18.237 times faster on read-only tasks. 

**Conclusions**: The combination of libMI library and MMSI file format enables developers to efficiently read and modify WSIs, thus can assist in pixel-wise image processing on extremely large images to promote building image processing pipeline. The library together with the data schema is freely available on [GitLab](https://gitlab.com/BioAI/libMI).

## Cite

```bibtex
@article{dong2020libmi,
  title={LibMI: An Open Source Library for Efficient Histopathological Image Processing},
  author={Dong, Yuxin and Puttapirat, Pargorn and Deng, Jingyi and Zhang, Xiangrong and Li, Chen},
  journal={Journal of Pathology Informatics},
  volume={11},
  number={1},
  pages={26},
  year={2020},
  publisher={Elsevier}
}
```
