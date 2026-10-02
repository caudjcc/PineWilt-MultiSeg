# PineWilt-MultiSeg

**PineWilt-MultiSeg: Joint spatial–spectral learning enables precise detection of pine wilt disease**

This repository provides the dataset and code associated with the published paper.

---

## Overview

PineWilt-MultiSeg is the **a publicly available multimodal high-resolution dataset for pine wilt disease (PWD)**. It contains:

- **3,938 pairs of RGB and multispectral images**
- **Pixel-level semantic annotations** for middle and late disease stages
- High-resolution imagery: 2–4 cm spatial resolution for RGB, 10 spectral bands (444–842 nm) for multispectral

The dataset enables the development and benchmarking of **multimodal deep learning models** for precise detection and segmentation of diseased pines.

---



## Dataset Download

The PineWilt-MultiSeg dataset is now publicly available for research purposes.

**Google Drive:**

- **Download Link:** https://drive.google.com/file/d/1o-9eX8ornC_0WUuTqGhv21Tro-bz8Msz/view?usp=sharing

**Baidu Netdisk:**

- **Download Link:** https://pan.baidu.com/s/1fEDcA8-oAREaCnLvdP0HYg
- **Extraction Code:** `4jci`
- **Shared Folder:** PineWilt-MultiSeg


---

## Features

- Provides **RGB + multispectral multimodal data** for improved detection accuracy
- Supports **benchmark experiments** with mainstream semantic segmentation models (SegFormer, PSPNet, Twins-PCPVT, DeepLabv3+, EncNet)
- Supports **CMX multimodal feature-level fusion**
- Enables analysis of **spatial and spectral resolution effects** on model performance

---

## Citation

If you use PineWilt-MultiSeg in your research, please cite our paper:

**Direct citation:**

Liu, G., Sun, H., Xiong, Y., Tang, W., Cheng, X., Wang, M., & Deng, J. (2026). PineWilt-MultiSeg: Joint spatial–spectral learning enables precise detection of pine wilt disease. *Computers and Electronics in Agriculture*, 112480. https://doi.org/10.1016/j.compag.2026.112480

**BibTeX:**

```bibtex
@article{Liu2026PineWilt,
  title   = {PineWilt-MultiSeg: Joint spatial--spectral learning enables precise detection of pine wilt disease},
  journal = {Computers and Electronics in Agriculture},
  pages   = {112480},
  year    = {2026},
  issn    = {0168-1699},
  doi     = {10.1016/j.compag.2026.112480},
  url     = {https://www.sciencedirect.com/science/article/pii/S0168169926010781},
  author  = {Guanghua Liu and Hanbing Sun and Yilin Xiong and Weidong Tang and Xin Cheng and Menghui Wang and Jie Deng}
}
```

---

## Contact

For questions regarding the dataset or code, please open an issue in this repository.
