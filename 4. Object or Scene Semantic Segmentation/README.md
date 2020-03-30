# Object or Scene Semantic Segmentation
## Description: 

> Recovering the 3D representation of an object from single-view or multi-view RGB images by deep neural networks has attracted increasing attention in the past few years. 

![](/3D-Computer-Vision-Research/images/4_seg2.png)

<p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/4_seg2.png" /></p>

![](/3D-Computer-Vision-Research/images/4_seg2.png)

<p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/4_seg2.png" /></p>

## 2019

1.  [CVPR](https://arxiv.org/abs/1911.11236v1)  RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds :trophy:

   In this paper, we introduce RandLA-Net, an efficient and lightweight neural architecture to directly infer per-point semantics for large-scale point clouds. The key to our approach is to use random point sampling instead of more complex point selection approaches. Although remarkably computation and memory efficient, random sampling can discard key features by chance. To overcome this, we introduce a novel local feature aggregation module to progressively increase the receptive field for each 3D point, thereby effectively preserving geometric details. Extensive experiments show that our RandLA-Net can process 1 million points in a single pass with up to 200X faster than existing approaches. Moreover, our RandLA-Net clearly surpasses state-of-the-art approaches for semantic segmentation on two large-scale benchmarks Semantic3D and SemanticKITTI.

   [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/191111236/semantic-segmentation-on-semantic3d)](https://paperswithcode.com/sota/semantic-segmentation-on-semantic3d?p=191111236)

   [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/191111236/3d-semantic-segmentation-on-semantickitti)](https://paperswithcode.com/sota/3d-semantic-segmentation-on-semantickitti?p=191111236)

   **[Code]: [TensorFlow](https://github.com/QingyongHu/RandLA-Net)**  

   **Datasets:** ShapeNet, Pix3D



## 2018

1. 