# INSIGHT: Interpretable Semantic Hierarchies in Vision-Language Encoders

<a href="https://explainablemachines.com/members/kai-wittenmayer.html">Kai Wittenmayer</a>,
<a href="https://sukrutrao.github.io">Sukrut Rao</a>,
<a href="https://m-parchami.github.io">Amin Parchami-Araghi</a>,
<a href="https://www.mpi-inf.mpg.de/departments/computer-vision-and-machine-learning/people/bernt-schiele">Bernt Schiele</a>,
<a href="https://explainablemachines.com/members/jonas-fischer.html">Jonas Fischer</a>

Max Planck Institute for Informatics, Saarland Informatics Campus, Saarbrücken, Germany  

<p align="center">
  <a href="assets/teaser.pdf">
    <img src="assets/teaser.svg" width="90%">
  </a>
</p>

---

[![arXiv](https://img.shields.io/badge/arXiv-XXXX.XXXXX-b31b1b.svg)](https://arxiv.org/abs/XXXX.XXXXX)

---

## News
- arXiv preprint available.

---

## Contents
- [Abstract](#abstract)
- [Code](#code)
- [Citation](#citation)

## Abstract

Language-aligned vision foundation models perform strongly across diverse downstream tasks. Yet, their learned representations remain opaque, making interpreting their decision-making hard. 
Recent works decompose these representations into human-interpretable concepts, but provide poor spatial grounding and are limited to image classification tasks.
In this work, we propose INSIGHT, a language-aligned concept foundation model that provides fine-grained concepts, which are human-interpretable and spatially grounded in the input image.
We leverage a hierarchical sparse autoencoder and a foundation model with strong semantic representations to automatically extract concepts at various granularities. Examining local co-occurrence dependencies of concepts allows us to define concept relationships. Through these relations we further improve concept naming and obtain richer explanations.
On benchmark data, we show that INSIGHT provides performance on classification and segmentation that is competitive with opaque foundation models while providing fine-grained, high quality concept-based explanations.

---
## Code

This repository serves as a **placeholder** for the INSIGHT project.  
Code is available soon, stay tuned!

---
## Citation

If you find this work useful, please cite the arXiv preprint:

```tex
@article{wittenmayer2026insight,
  title  = {INSIGHT: Interpretable Semantic Hierarchies in Vision-Language Encoders},
  author = {Wittenmayer, Kai and Rao, Sukrut and Parchami-Araghi, Amin and Schiele, Bernt and Fischer, Jonas},
  journal= {arXiv},
  year   = {2026}
}
```
