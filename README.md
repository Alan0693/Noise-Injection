# Noise Injection - Official PyTorch Implementation

<img src="doc_images/Teaser.png" width="96%" height="96%">

This repository provides the discription for the following paper:

**On the Analysis of GAN-based Image-to-Image Translation using Gaussian Noise Injection**<br>
Chaohua Shi, Kexin Huang, [Lu Gan](https://scholar.google.com/citations?hl=zh-CN&user=zFHPoMYAAAAJ&view_op=list_works&sortby=pubdate), [Hongqing Liu](https://scholar.google.com/citations?hl=zh-CN&user=04nXyUQAAAAJ&view_op=list_works&sortby=pubdate), [Mingrui Zhu](https://scholar.google.com/citations?user=a8FXS1UAAAAJ&hl=zh-CN&oi=ao), [Nannan Wang](https://scholar.google.com/citations?hl=zh-CN&user=SRBn7oUAAAAJ) and [Xinbo Gao](https://scholar.google.com/citations?user=VZVTOOIAAAAJ&hl=zh-CN&oi=ao)<br>
In ICLR 2024.<br>
[**Paper Page**](https://openreview.net/forum?id=sLregLuXpn) 
> **Abstract:** *Image-to-image (I2I) translation is vital in computer vision tasks like style transfer and domain adaptation. While recent advances in GAN have enabled high-quality sample generation, real-world challenges such as noise and distortion remain significant obstacles. Although Gaussian noise injection during training has been utilized, its theoretical underpinnings have been unclear. This work provides a robust theoretical framework elucidating the role of Gaussian noise injection in I2I translation models. We address critical questions on the influence of noise variance on distribution divergence, resilience to unseen noise types, and optimal noise intensity selection. Our contributions include connecting f-divergence and score matching, unveiling insights into the impact of Gaussian noise on aligning probability distributions, and demonstrating generalized robustness implications. We also explore choosing an optimal training noise level for consistent performance in noisy environments. Extensive experiments validate our theoretical findings, showing substantial improvements over various I2I baseline models in noisy settings. Our research rigorously grounds Gaussian noise injection for I2I translation, offering a sophisticated theoretical understanding beyond heuristic applications.*

<img src="doc_images/result.png" width="96%" height="96%">

**Dependencies:**

We have tested on:
- CUDA 10.1
- PyTorch 1.7.0
- Pillow 8.0.1; Matplotlib 3.3.3; opencv-python 4.4.0; Faiss 1.7.0; tqdm 4.54.0

All dependencies for defining the environment are provided in `environment/noise_injection_env.yaml`.
We recommend running this repository using [Anaconda](https://docs.anaconda.com/anaconda/install/):
```bash
conda env create -f ./environment/noise_injection_env.yaml
```
