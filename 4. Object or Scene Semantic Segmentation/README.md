# Object or Scene Semantic Segmentation
## Description: 

> Recovering the 3D representation of an object from single-view or multi-view RGB images by deep neural networks has attracted increasing attention in the past few years. 

<p align="center"><img width="80%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/4_kitti3D.png" /></p>

## 2020

1. 3D-MiniNet: Learning a 2D Representation from Point Clouds for Fast and Efficient 3D LIDAR Semantic Segmentation

   LIDAR semantic segmentation, which assigns a semantic label to each 3D point measured by the LIDAR, is becoming an essential task for many robotic applications such as autonomous driving. Fast and efficient semantic segmentation methods are needed to match the strong computational and temporal restrictions of many of these real-world applications. This work presents 3D-MiniNet, a novel approach for LIDAR semantic segmentation that combines 3D and 2D learning layers. It first learns a 2D representation from the raw points through a novel projection which extracts local and global information from the 3D data. This representation is fed to an efficient 2D Fully Convolutional Neural Network (FCNN) that produces a 2D semantic segmentation. These 2D semantic labels are re-projected back to the 3D space and enhanced through a post-processing module. The main novelty in our strategy relies on the projection learning module. Our detailed ablation study shows how each component contributes to the final performance of 3D-MiniNet. We validate our approach on well known public benchmarks (SemanticKITTI and KITTI), where 3D-MiniNet gets state-of-the-art results while being faster and more parameter-efficient than previous methods. 

   [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-mininet-learning-a-2d-representation-from/real-time-3d-semantic-segmentation-on)](https://paperswithcode.com/sota/real-time-3d-semantic-segmentation-on?p=3d-mininet-learning-a-2d-representation-from):trophy:

   [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/3d-mininet-learning-a-2d-representation-from/3d-semantic-segmentation-on-semantickitti)](https://paperswithcode.com/sota/3d-semantic-segmentation-on-semantickitti?p=3d-mininet-learning-a-2d-representation-from):trophy:

   [![Paper](https://camo.githubusercontent.com/813416847fa19ef4e50c23665afb58b81adc6b93/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50617065722d5044462d726564)](https://arxiv.org/pdf/2002.10893.pdf)

   <p align="center"><img width="80%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/3D-MiniNet.png" /></p>

   

## 2019

1.  [CVPR](https://arxiv.org/abs/1911.11236v1)  RandLA-Net: Efficient Semantic Segmentation of Large-Scale Point Clouds 

   In this paper, we introduce RandLA-Net, an efficient and lightweight neural architecture to directly infer per-point semantics for large-scale point clouds. The key to our approach is to use random point sampling instead of more complex point selection approaches. Although remarkably computation and memory efficient, random sampling can discard key features by chance. To overcome this, we introduce a novel local feature aggregation module to progressively increase the receptive field for each 3D point, thereby effectively preserving geometric details. Extensive experiments show that our RandLA-Net can process 1 million points in a single pass with up to 200X faster than existing approaches. Moreover, our RandLA-Net clearly surpasses state-of-the-art approaches for semantic segmentation on two large-scale benchmarks Semantic3D and SemanticKITTI.

   [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/191111236/semantic-segmentation-on-semantic3d)](https://paperswithcode.com/sota/semantic-segmentation-on-semantic3d?p=191111236):trophy:

   [![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/191111236/3d-semantic-segmentation-on-semantickitti)](https://paperswithcode.com/sota/3d-semantic-segmentation-on-semantickitti?p=191111236)

   <p align="center"><img width="80%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/RandLA-Net.png" /></p>

   **[Code]: [TensorFlow](https://github.com/QingyongHu/RandLA-Net)**  
   
   **Datasets:** S3DIS, Semantic3D, SemanticKITTI
