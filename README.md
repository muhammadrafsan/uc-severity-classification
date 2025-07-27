<h1 align="center">
A triple pronged approach for ulcerative colitis severity classification using multimodal, meta, and transformer based learning
</h1>

<p align="center">
  <a href="https://creativecommons.org/licenses/by/4.0/">
    <img src="https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg" alt="License: CC BY 4.0">
  </a>
  <a href="https://doi.org/10.1038/s41598-025-12827-5">
    <img src="https://img.shields.io/badge/Published%20in-Scientific%20Reports-blue.svg" alt="Published in Scientific Reports">
  </a>
</p>

## 📌 Overview

This repository contains the official implementation for the paper:

> ***A triple pronged approach for ulcerative colitis severity classification using multimodal, meta, and transformer based learning***
> Md. Nasim Ahmed*, Dipta Neogi*, Muhammad Rafsan Kabir*, Shafin Rahman, Sifat Momen, Nabeel Mohammed
> Published in *Scientific Reports (Nature)*, 2025. [[DOI:10.1038/s41598-025-12827-5]](https://doi.org/10.1038/s41598-025-12827-5)

We propose a **triple-pronged framework** combining:
1. **Multimodal learning** (CLIP, BLIP, FLAVA)
2. **Few-shot meta-learning** (Matching Networks, Prototypical Networks)
3. **Vision Transformer ensembles** (ViT, DeiT, Swin)  
for binary classification (mild vs severe) of ulcerative colitis severity using the **HyperKvasir dataset**.

---

## 🧠 Key Highlights

- **ViT Soft Voting Ensemble** achieves **93% accuracy**, surpassing prior SOTA methods.
- **Multimodal Pre-trained Models** perform efficient classification without model training.
- **Few-Shot Learning** achieves 83% accuracy with just 5 examples/class using Matching Networks.
- **Explainable AI** integration using **SHAP** improves clinical trust and interpretability.

---

## 🗃️ Dataset

We use the **HyperKvasir** dataset for severity classification. It can be accessed at https://datasets.simula.no/hyper-kvasir/

<img width="575" height="253" alt="image" src="https://github.com/user-attachments/assets/7da69046-d562-4ab6-b641-e670f5921f5f" />


---

## Citation

If you wish to cite this work, feel free to use this [BibTeX](http://www.bibtex.org/) reference:

```bibtex
@article{ahmed2025triple,
  title        = {A triple pronged approach for ulcerative colitis severity classification using multimodal, meta, and transformer based learning},
  author       = {Ahmed, Md. Nasim and Neogi, Dipta and Kabir, Muhammad Rafsan and Rahman, Shafin and Momen, Sifat and Mohammed, Nabeel},
  journal      = {Scientific Reports},
  volume       = {15},
  number       = {27205},
  year         = {2025},
  publisher    = {Nature Publishing Group},
  doi          = {10.1038/s41598-025-12827-5},
  url          = {https://doi.org/10.1038/s41598-025-12827-5}
}
