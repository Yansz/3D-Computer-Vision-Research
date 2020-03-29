# Geometry Synthesis or Reconstruction
## Description: 

> Recovering the 3D representation of an object from single-view or multi-view RGB images by deep neural networks has attracted increasing attention in the past few years. 



## 2019

1.  [ICCV](https://arxiv.org/abs/1901.11153v2)  Pix2Vox: Context-aware 3D Reconstruction from Single and Multi-view Images :trophy:

   Several mainstream works (e.g., 3D-R2N2) use recurrent neural networks (RNNs) to fuse multiple feature maps extracted from input images sequentially. However, when given the same set of input images with different orders, RNN-based approaches are unable to produce consistent reconstruction results. Moreover, due to long-term memory loss, RNNs cannot fully exploit input images to refine reconstruction results. To solve these problems, they propose a novel framework for single-view and multi-view 3D reconstruction, named Pix2Vox. By using a well-designed encoder-decoder, it generates a coarse 3D volume from each input image. Then, a context-aware fusion module is introduced to adaptively select high-quality reconstructions for each part (e.g., table legs) from different coarse 3D volumes to obtain a fused 3D volume. Finally, a refiner further refines the fused 3D volume to generate the final output. Experimental results on the ShapeNet and Pix3D benchmarks indicate that the proposed Pix2Vox outperforms state-of-the-arts by a large margin. 

   ![](/3D-Computer-Vision-Research/images/5_0.jpg)

   ![](/3D-Computer-Vision-Research/images/5_1.png)

   **[Code]: [PyTorch](https://github.com/hzxie/Pix2Vox)**  

   **Datasets:** ShapeNet, Pix3D



## 2018

1. 