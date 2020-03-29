# Multiple Objects Detection
## Description: 

> Accurate detection of objects in 3D point clouds is a central problem in many applications, such as autonomous navigation, housekeeping robots, and augmented/virtual reality. 



## 2018

1.  [CVPR](https://arxiv.org/abs/1901.11153v2)  Frustum PointNets for 3D Object Detection from RGB-D Data 

   3D object detection from RGB-D data in both indoor and outdoor scenes. While previous methods focus on images or 3D voxels, often obscuring natural 3D patterns and invariances of 3D data, we directly operate on raw point clouds by popping up RGB-D scans. However, a key challenge of this approach is how to efficiently localize objects in point clouds of large-scale scenes (region proposal). Instead of solely relying on 3D proposals, our method leverages both mature 2D object detectors and advanced 3D deep learning for object localization, achieving efficiency as well as high recall for even small objects. Benefited from learning directly in raw point clouds, our method is also able to precisely estimate 3D bounding boxes even under strong occlusion or with very sparse points. Evaluated on KITTI and SUN RGB-D 3D detection benchmarks, our method outperforms the state of the art by remarkable margins while having real-time capability.

   ![](/3D-Computer-Vision-Research/images/5_0.jpg)

   ![](/3D-Computer-Vision-Research/images/5_1.png)

   **[Code]: [PyTorch](https://github.com/hzxie/Pix2Vox)**  

   **Datasets:** Object Localization on KITTI Cyclists Easy  :trophy:

2. [CVPR](https://arxiv.org/abs/1711.06396v1) VoxelNet: End-to-End Learning for Point Cloud Based 3D Object Detection

   In this work, they remove the need of manual feature engineering for 3D point clouds and propose VoxelNet, a generic 3D detection network that unifies feature extraction and bounding box prediction into a single stage, end-to-end trainable deep network. Specifically, VoxelNet divides a point cloud into equally spaced 3D voxels and transforms a group of points within each voxel into a unified feature representation through the newly introduced voxel feature encoding (VFE) layer. In this way, the point cloud is encoded as a descriptive volumetric representation, which is then connected to a RPN to generate detections. Experiments on the KITTI car detection benchmark show that VoxelNet outperforms the state-of-the-art LiDAR based 3D detection methods by a large margin. Furthermore, our network learns an effective discriminative representation of objects with various geometries, leading to encouraging results in 3D detection of pedestrians and cyclists, based on only LiDAR.

   ![](/3D-Computer-Vision-Research/images/3_0.png)

   ![](/3D-Computer-Vision-Research/images/3_1.jpg)

   **Datasets:** Object Localization on KITTI Cars Easy

## 2017

1. 