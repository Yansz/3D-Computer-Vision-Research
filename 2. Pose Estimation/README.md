# Pose Estimation
## Description: 

> Pose Estimation is a general problem in Computer Vision where we detect the position and orientation of an object.



## 2018

2. [ NeurIPS](https://arxiv.org/pdf/1807.03146v2.pdf)  Discovery of Latent 3D Keypoints via End-to-end Geometric Reasoning

   This paper presents KeypointNet, an end-to-end geometric reasoning framework to learn an optimal set of category-specific 3D keypoints, along with their detectors. Given a single image, KeypointNet extracts 3D keypoints that are optimized for a downstream task. We demonstrate this framework on 3D pose estimation by proposing a differentiable objective that seeks the optimal set of keypoints for recovering the relative pose between two views of an object. Our model discovers geometrically and semantically consistent keypoints across viewing angles and instances of an object category. Importantly, we find that our end-to-end framework using no ground-truth keypoint annotations outperforms a fully supervised baseline using the same neural network architecture on the task of pose estimation. The discovered 3D keypoints on the car, chair, and plane categories of ShapeNet are visualized at http://keypointnet.github.io/. 

   <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/chair_spin.gif" /></p>

   **[Code]:  [TensorFlow](https://github.com/tensorflow/models/tree/master/research/keypointnet)** 

   **Datasets:** ShapeNet


