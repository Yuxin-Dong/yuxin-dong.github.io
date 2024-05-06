---
permalink: /
title: "About Me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a Ph.D. student at the School of Computer Science and Technology, Xi’an Jiaotong University, advised by Prof. [Chen Li](https://chenli.group/) and Prof. [Tieliang Gong](https://gong-tl.github.io/). I obtained my bachelor's degree at Xi’an Jiaotong University, majoring in Computer Science and Technology.

My research interests lie in machine learning and statistical learning theory. Recently, I have been focusing on **information-theoretic generalization analysis and algorithm design** in supervised learning, contrastive learning, and domain generalization. These works shed light on understanding the success of existing algorithms or inspire new algorithm designs that are provably more effective. My research areas include:

* Analyzing the generalization ability of randomized learning algorithms through the lens of information theory.
* Designing effective and robust learning algorithms based on information-theoretic measurements and analysis.
* Developing computationally efficient approximations for information-theoretic quantities and measurements.

## Selected Publications

{%- assign post = site.publications | where: "title", "Towards Generalization beyond Pointwise Learning: A Unified Information-theoretic Perspective" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Rethinking Information-theoretic Generalization: Loss Entropy Induced PAC Bounds" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Optimal Randomized Approximations for Matrix-based Rényi's Entropy" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Understanding the Generalization Ability of Deep Learning Algorithms: A Kernelized Rényi’s Entropy Perspective" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Robust and Fast Measure of Information via Low-Rank Representation" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Efficient Approximations for Matrix-Based Rényi’s Entropy on Sequential Data" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Computationally Efficient Approximations for Matrix-Based Rényi's Entropy" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Regularized Modal Regression on Markov-Dependent Observations: A Theoretical Assessment" | first-%}
{% include archive-single.html %}

{%- assign post = site.publications | where: "title", "Markov Subsampling Based on Huber Criterion" | first-%}
{% include archive-single.html %}
