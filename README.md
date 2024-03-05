# Noise Injection - Official PyTorch Implementation

<img src="doc_images/Teaser.png" width="96%" height="96%">

This repository provides the discription for the following paper:

**On the Analysis of GAN-based Image-to-Image Translation using Gaussian Noise Injection**<br>
[Chaohua Shi], [Kexin Huang], [Lu Gan](https://scholar.google.com/citations?hl=zh-CN&user=zFHPoMYAAAAJ&view_op=list_works&sortby=pubdate), [Hongqing Liu]<br>
In CVPR 2022, TPAMI 2023.<br>
[**Project Page**](https://www.mmlab-ntu.com/project/gpunit/) | [**CVPR Paper**](https://arxiv.org/abs/2204.03641) | [**TPAMI Paper**](https://arxiv.org/abs/2306.04636) | [**Supplementary Video**](https://www.youtube.com/watch?v=dDApWs_oDrM)
> **Abstract:** *Unsupervised image-to-image translation aims to learn the translation between two visual domains without paired data. Despite the recent progress in image translation models, it remains challenging to build mappings between complex domains with drastic visual discrepancies. In this work, we present a novel framework, Generative Prior-guided UNsupervised Image-to-image Translation (GP-UNIT), to improve the overall quality and applicability of the translation algorithm. Our key insight is to leverage the generative prior from pre-trained class-conditional GANs (e.g., BigGAN) to learn rich content correspondences across various domains. We propose a novel coarse-to-fine scheme: we first distill the generative prior to capture a robust coarse-level content representation that can link objects at an abstract semantic level, based on which fine-level content features are adaptively learned for more accurate multi-level content correspondences. Extensive experiments demonstrate the superiority of our versatile framework over state-of-the-art methods in robust, high-quality and diversified translations, even for challenging and distant domains.*
