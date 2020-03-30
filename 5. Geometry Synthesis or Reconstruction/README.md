# Geometry Synthesis or Reconstruction
## Description: 

> 3D reconstruction is the process of capturing the shape and appearance of real objects. This process can be accomplished either by active or passive methods. If the model is allowed to change its shape in time, this is referred to as non-rigid or spatio-temporal reconstruction.



## 2019

1.  [ICCV](https://arxiv.org/abs/1901.11153v2)  Pix2Vox: Context-aware 3D Reconstruction from Single and Multi-view Images :trophy:

   Several mainstream works (e.g., 3D-R2N2) use recurrent neural networks (RNNs) to fuse multiple feature maps extracted from input images sequentially. However, when given the same set of input images with different orders, RNN-based approaches are unable to produce consistent reconstruction results. Moreover, due to long-term memory loss, RNNs cannot fully exploit input images to refine reconstruction results. To solve these problems, they propose a novel framework for single-view and multi-view 3D reconstruction, named Pix2Vox. By using a well-designed encoder-decoder, it generates a coarse 3D volume from each input image. Then, a context-aware fusion module is introduced to adaptively select high-quality reconstructions for each part (e.g., table legs) from different coarse 3D volumes to obtain a fused 3D volume. Finally, a refiner further refines the fused 3D volume to generate the final output. Experimental results on the ShapeNet and Pix3D benchmarks indicate that the proposed Pix2Vox outperforms state-of-the-arts by a large margin. 

   <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/5_0.jpg" /></p>

   <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/5_1.png" /></p>

   **[Code]: [PyTorch](https://github.com/hzxie/Pix2Vox)**  

   **Datasets:** ShapeNet, Pix3D

## 2018

1. 