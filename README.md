
# ViT vs CNN: The Clash of Architectures ⚔️

[![YouTube](https://img.shields.io/badge/Watch-Webinar_Recording-FF0000?style=flat&logo=youtube&logoColor=white)](https://youtu.be/qYBmiQ-TEWk)
[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/1hPQA-kpdvFgX-OdXR4Ext0s0cLxeAEHp?usp=sharing)
[![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)](https://pytorch.org/)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

> **"Is Convolution Dead? The Rise of Attention in Computer Vision."**

This repository contains the official slides, code, and resources for the webinar **"ViT vs CNN: The Clash of Architectures"**, hosted on **December 22, 2025** by Rumah Coding.

📺 **Watch the full recording here:** [https://youtu.be/qYBmiQ-TEWk](https://youtu.be/qYBmiQ-TEWk)

## 📅 Webinar Overview

The landscape of Computer Vision has shifted dramatically. For a decade, Convolutional Neural Networks (CNNs) were the undisputed kings. Then came the **Vision Transformer (ViT)**, challenging the status quo by treating images as sequences of patches.

In this session, we deep dive into the mechanics of both architectures, explore their trade-offs, and implement a ViT from scratch using PyTorch.

### 📚 Topics Covered

1.  **The Decade of Convolutions**
    * From AlexNet to ResNet: The evolution of Inductive Bias.
    * Why CNNs dominated computer vision for so long.
2.  **Deconstructing Vision Transformer (ViT)**
    * "An Image is Worth 16x16 Words": Understanding Patch Embeddings.
    * The role of Self-Attention and the [CLS] token.
    * Positional Embeddings: 1D vs 2D.
3.  **The Clash: CNN vs. ViT**
    * **Local vs. Global Context:** Visualizing Receptive Fields.
    * **Data Hunger:** Why ViT needs massive datasets (JFT-300M) to beat CNNs.
    * Inductive Bias vs. Model Capacity.
4.  **The Verdict & The Future**
    * Is Convolution dead? (Spoiler: No, look at ConvNeXt).
    * The Hybrid Era: Swin Transformers and the best of both worlds.
5.  **Implementation Walkthrough**
    * Coding `PatchEmbed` using the `Conv2d` trick.
    * Building the Transformer Encoder Block.
    * Using `timm` (PyTorch Image Models) for production-ready inference.

---

## 🚀 Quick Start (Code Demo)

You can run the full implementation demo directly in your browser using Google Colab. No installation required.

[**Click here to launch the Notebook**](https://colab.research.google.com/drive/1hPQA-kpdvFgX-OdXR4Ext0s0cLxeAEHp?usp=sharing)


---

## 👤 About the Author

**Lhuqita Fazry**

* *Machine Learning & Deep Learning Enthusiast*
* *Focus: Computer Vision, Large Language Models, and AI Education.*

---

## 📄 How to Cite

If you find this repository or the webinar materials useful for your research or study, please cite it using the following BibTeX entry:

```bibtex
@misc{fazry2025vitvscnn,
  author       = {Fazry, Lhuqita},
  title        = {ViT vs CNN: The Clash of Architectures},
  year         = {2025},
  month        = {December},
  howpublished = {GitHub Repository},
  url          = {[https://github.com/lhfazry/vit-vs-cnn](https://github.com/lhfazry/vit-vs-cnn)},
  note         = {Webinar Material}
}

```

**Alternative Citation Format:**

> Fazry, L. (2025). *ViT vs CNN: The Clash of Architectures* [Webinar Materials]. GitHub. https://github.com/lhfazry/vit-vs-cnn

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](https://www.google.com/search?q=LICENSE) file for details.
