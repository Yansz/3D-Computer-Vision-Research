# 3D-Computer-Vision-Research :city_sunrise:
Computer vision tasks based on 3D data will develop rapidly in the foreseeable time. There is currently no fixed division of vision research tasks, many projects are multi-tasking fusions.


We collect some data sets and research papers about 3D computer vision, and If lucky, there will be open source related implemented repositories. Divided according to the needs of different tasks. It is expected to be supplemented by all interested in 3D computer vision research.

<p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/main1.jpg" /></p>

There are several forms of 3D data. It is possible to choose according to the needs of the task. Taking common point cloud data as an example, the tasks that can be performed on point cloud data include the following categories:

<p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/pointcloud1.jpg" /></p>


:heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign::heavy_minus_sign:

## Courses

* [Stanford CS231A: Computer Vision-From 3D Reconstruction to Recognition (Winter 2018)](http://web.stanford.edu/class/cs231a/)

* [UCSD CSE291-I00: Machine Learning for 3D Data (Winter 2018)](https://cse291-i.github.io/index.html)

* [Stanford CS468: Machine Learning for 3D Data (Spring 2017)](http://graphics.stanford.edu/courses/cs468-17-spring/)

* [MIT 6.838: Shape Analysis (Spring 2017)](http://groups.csail.mit.edu/gdpgroup/6838_spring_2017.html)

* [Princeton COS 526: Advanced Computer Graphics (Fall 2010)](https://www.cs.princeton.edu/courses/archive/fall10/cos526/syllabus.php)

* [Princeton CS597: Geometric Modeling and Analysis (Fall 2003)](https://www.cs.princeton.edu/courses/archive/fall03/cs597D/)

* [Geometric Deep Learning](http://geometricdeeplearning.com/)

* [Paper Collection for 3D Understanding](https://www.cs.princeton.edu/courses/archive/spring15/cos598A/cos598A.html#Estimating)

* [CreativeAI: Deep Learning for Graphics](http://geometry.cs.ucl.ac.uk/creativeai/)

## Software

- [MeshLab](http://meshlab.sourceforge.net/). Open-source, portable, and extensible system for the processing and editing of unstructured 3D triangular meshes, supports input/output in the following formats: PLY, STL, OFF, OBJ, 3DS, VRML 2.0, X3D and COLLADA.

  <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/meshlab.jpg" /></p>

- [CloudCompare](http://www.danielgm.net/cc/). Open-source, Manually editing and rendering 3D points clouds and triangular meshes, Support more I/O formats.

  <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/Cc.jpg" /></p>

- [OpenFlipper](http://www.openflipper.org/). An Open Source Geometry Processing and Rendering Framework,  Using OpenMesh a variety of file formats are supported ( off, obj, ply, ... ).

  <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/OF.png" /></p>

- [PotreeDesktop](https://github.com/potree/PotreeDesktop). A desktop/portable version of the web-based point cloud viewer [Potree](https://github.com/potree/potree)

  <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/potree.jpg" /></p>

- [Online LIDAR point cloud viewer](http://lidarview.com/). A simple online point cloud viewer

  <p align="center"><img width="50%" src="https://github.com/Yansz/3D-Computer-Vision-Research/blob/master/images/online.png" /></p>
 
## Awesome 3D paper collection work
1. [SoTA in CV tasks](https://paperswithcode.com/area/computer-vision):  Browse State-of-the-Art : papers, code and tasks. This website cooperates with facebook, it is a good tool for all deep learning researchers to keep up with the current status of the research field in time.

2. [Awesome-point-cloud-analysis](https://github.com/Yochengliu/awesome-point-cloud-analysis): Organized point cloud analysis work since 2017, with links and code.

3. [3D-Machine-Learning](https://github.com/timzhang642/3D-Machine-Learning): Interesting repo, collecting and sorting 3D data and papers from point cloud data, Multi-view Images and Volumetric etc.

4. [SoTA-Point-Cloud](https://github.com/QingyongHu/SoTA-Point-Cloud):Fllowing the Deep Learning research for 3D Point Clouds.

## Open source library
1. [PCL](https://pointclouds.org/) An open-source library of algorithms for point cloud processing tasks and 3D geometry processing, such as occur in three-dimensional computer vision.The library contains algorithms for feature estimation, surface reconstruction, 3D registration, model fitting, and segmentation. Written in C++, Written in C ++, the Python interface is still unfriendly.

2. [Open3D](http://www.open3d.org/) An open-source library that supports rapid development of software that deals with 3D data. The Open3D frontend exposes a set of carefully selected data structures and algorithms in both C++ and Python. The backend is highly optimized and is set up for parallelization.Because of its ease of use, popularity is rising, but some advanced features are still not better than PCL.

3. [PyTorch3D](https://github.com/facebookresearch/pytorch3d) From Facebook Research Team, to help accelerate research at the intersection of deep learning and 3D,including efficient 3D operators, heterogeneous batching capabilities, and a modular differentiable rendering API, to equip researchers in this field with a much needed toolkit to implement cutting-edge research with complex 3D inputs.Deep learning mainly based on Mesh data format, has been used to power research projects such as [Mesh R-CNN(2019)](https://arxiv.org/abs/1906.02739).

**Notes:** 

* Many 3D vision tasks are related and complementary, so it is difficult to distinguish them completely.
  My idea is to summarize the influential and innovative papers that have appeared in the field of 3D vision and extract their research tasks. For a framework that involves multiple research tasks, I will put an introduction in each related folder.
* Another way to quickly find the data sets we need is to follow the popular research papers in our research direction. We will learn which data sets are recommended for our similar tasks.

**Let's get the ball rolling ! ​**
[Back :arrow_heading_up:](https://github.com/Yansz/3D-Computer-Vision-Research#3D-Computer-Vision-Research-city_sunrise) 

