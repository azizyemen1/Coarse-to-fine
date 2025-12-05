# Coarse-to-Fine Task-Relevant Tokens Identification for Retail Product Recognition

<p align="center">
  <img src="assets/cfvit_overview.png" width="800">
</p>

## 📢 News

- **Code will be released upon paper acceptance.**

## 📝 Abstract

We propose CF-ViT (Coarse-to-Fine Vision Transformer), a novel approach for efficient retail product recognition. Our method identifies task-relevant tokens through a two-stage coarse-to-fine selection process, significantly reducing computational costs while maintaining high accuracy.

## 🔑 Key Features

- **Coarse-to-Fine Token Selection**: Two-stage token pruning strategy that first identifies informative coarse regions, then refines with fine-grained subdivision
- **Computational Efficiency**: Achieves competitive accuracy with significantly reduced GFLOPs
- **Retail-Focused**: Specifically designed for retail product recognition tasks

## 🏗️ Method Overview

<p align="center">
  <img src="assets/method.png" width="700">
</p>

1. **Coarse Stage**: Select top-k% informative patches based on attention scores
2. **Fine Stage**: Subdivide selected coarse patches into finer tokens (2×2)
3. **Classification**: Process selected tokens through transformer blocks




@article{cfvit2025,
  title={Coarse-to-Fine Task-Relevant Tokens Identification for Retail Product Recognition},
  author={Author Names},
  journal={Journal/Conference Name},
  year={2025}
}

<p align="center">
  ⭐ Star this repository to get notified when the code is released!
</p>
