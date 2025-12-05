# Coarse-to-Fine Task-Relevant Tokens Identification for Retail Product Recognition

<p align="center">
  <img src="assets/cfvit_overview.png" width="800">
</p>

## 📢 News

- **[2025]** Paper submitted for review.
- **Code will be released upon paper acceptance.**

## 📝 Abstract

We propose CF-ViT (Coarse-to-Fine Vision Transformer), a novel approach for efficient retail product recognition. Our method identifies task-relevant tokens through a two-stage coarse-to-fine selection process, significantly reducing computational costs while maintaining high accuracy.

## 🔑 Key Features

- **Coarse-to-Fine Token Selection**: Two-stage token pruning strategy that first identifies informative coarse regions, then refines with fine-grained subdivision
- **Attention-Guided Selection**: Leverages CLS token attention to identify task-relevant image regions
- **Computational Efficiency**: Achieves competitive accuracy with significantly reduced GFLOPs
- **Retail-Focused**: Specifically designed for retail product recognition tasks

## 🏗️ Method Overview

<p align="center">
  <img src="assets/method.png" width="700">
</p>

1. **Coarse Stage**: Select top-k% informative patches based on attention scores
2. **Fine Stage**: Subdivide selected coarse patches into finer tokens (2×2)
3. **Classification**: Process selected tokens through transformer blocks

## 📊 Results

| Method | Dataset | Top-1 Acc | GFLOPs | Params |
|--------|---------|-----------|--------|--------|
| DeiT-S | Retail-1K | - | 4.6 | 22M |
| CF-ViT (Ours) | Retail-1K | **96.39%** | **2.1** | 22M |

*More results will be added upon publication.*

## 🗂️ Datasets

- [Retail Product Checkout (RPC)](https://www.kaggle.com/datasets/diyer22/retail-product-checkout-dataset)
- [RP2K](https://www.pinlandata.com/rp2k_dataset)
- [Products-10K](https://products-10k.github.io/)

## 📦 Code Release

> ⏳ **The code, pretrained models, and training scripts will be made publicly available after the paper is accepted for publication.**

The release will include:
- [ ] Training code
- [ ] Evaluation scripts
- [ ] Pretrained models
- [ ] Visualization tools
- [ ] Inference demo

## 📧 Contact

For questions, please open an issue or contact: [your-email@example.com]

## 📄 Citation

If you find this work useful, please consider citing:

```bibtex
@article{cfvit2025,
  title={Coarse-to-Fine Task-Relevant Tokens Identification for Retail Product Recognition},
  author={Author Names},
  journal={Journal/Conference Name},
  year={2025}
}
```

## 🙏 Acknowledgements

This work builds upon:
- [DeiT](https://github.com/facebookresearch/deit)
- [timm](https://github.com/huggingface/pytorch-image-models)

## 📜 License

This project will be released under the [MIT License](LICENSE).

---

<p align="center">
  ⭐ Star this repository to get notified when the code is released!
</p>
