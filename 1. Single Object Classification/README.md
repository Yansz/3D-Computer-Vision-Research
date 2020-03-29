# Object Classification/Recognition
## Description: 

> 3D object Classification refers to the task of extracting information classes from 3D data. Recognition is the task of recognising objects from 3D data. I think they have a progressive and complementary relationship, so I will put them together for analysis.



## 2017

1. **[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Qi_PointNet_Deep_Learning_CVPR_2017_paper.pdf) [cls. seg.  det.]** PointNet: Deep Learning on Point Sets for 3D Classification and Segmentation 

   **A seminal paper in 3D perception** 

   Point cloud is an important type of geometric data structure. Due to its irregular format, most researchers transform such data to regular 3D voxel grids or collections of images. This, however, renders data unnecessarily voluminous and causes issues. In this paper, we design a novel type of neural network that directly consumes point clouds and well respects the permutation invariance of points in the input. PointNet provides a unified architecture for applications ranging from object classification, part segmentation, to scene semantic parsing. Though simple, PointNet is highly efficient and effective. Empirically, it shows strong performance on par or even better than state of the art. Theoretically, they provide analysis towards understanding of what the network has learnt and why the network is robust with respect to input perturbation and corruption.

   ![](/3D-Computer-Vision-Research/images/pointnet.png)

   **[Code]: [TensorFlow](https://github.com/charlesq34/pointnet),   [PyTorch](https://github.com/fxia22/pointnet.pytorch)**  

   **Datasets:** ModelNet40

2. **[CVPR](http://openaccess.thecvf.com/content_cvpr_2017/papers/Riegler_OctNet_Learning_Deep_CVPR_2017_paper.pdf) [cls. seg.  det.] **OctNet: Learning Deep 3D Representations at High Resolutions. 

   The author proposes OctNet, a representation for deep learning with sparse 3D data. In contrast to existing models, representation enables 3D convolutional networks which are both deep and high resolution. Towards this goal, they exploit the sparsity in the input data to hierarchically partition the space using a set of unbalanced octrees where each leaf node stores a pooled feature representation. This allows to focus memory allocation and computation to the relevant dense regions and enables deeper networks without compromising resolution. They demonstrate the utility of the OctNet representation by analyzing the impact of resolution on several 3D tasks including 3D object classification, orientation estimation and point cloud labeling.

   ![](/3D-Computer-Vision-Research/images/octree.png)

   **[Code]:  [PyTorch](https://github.com/griegler/octnet)** 

   **Datasets:** ModelNet10

3. 

