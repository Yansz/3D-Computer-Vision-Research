# 3D-Computer-Vision-Research
# Datasets

1. **[ASL Datasets Repository(ETH)](https://projects.asl.ethz.ch/datasets/doku.php?id=home)  (2012).  [`cls.` `match.` `reg.` `det`]**

   This group of datasets was recorded with the aim to test point cloud registration algorithms in specific environments and conditions. Special care is taken regarding the precision of the "ground truth" positions of the scanner, which is in the millimeter range, using a theodolite. Some examples of the recorded environments can be seen bellow.

![](/3D-Computer-Vision-Research/images/asldataset_weblarge.jpg)



2. **[SYDNEY URBAN OBJECTS DATASET](http://www.acfr.usyd.edu.au/papers/SydneyUrbanObjectsDataset.shtml)  (2013). ** [__`Cls.`__ __`Match.`__]

   This dataset contains a variety of common urban road objects scanned with a Velodyne HDL-64E LIDAR, collected in the CBD of Sydney, Australia. There are 631 individual scans of objects across classes of vehicles, pedestrians, signs and trees. 

![](/3D-Computer-Vision-Research/images/arranged.png)



3. **[PASCAL3D+](http://cvgl.stanford.edu/projects/pascal3d.html)  (2014).  [__`Pos.`__ __`Det.`__]**

   Beyond PASCAL: A Benchmark for 3D Object Detection in the Wild. 12 categories, on average 3k+ objects per category, for 3D object detection and pose estimation.

![](/3D-Computer-Vision-Research/images/cads.png)



4. **[ModelNet](http://modelnet.cs.princeton.edu/)  (2015).  [`Cls.`]**

   The Princeton ModelNet , including 127915 3D CAD models from 662 categories 

* ModelNet10: 4899 models from 10 categories 
* ModelNet40: 12311 models from 40 categories, all are uniformly orientate

![](/3D-Computer-Vision-Research/images/modelnet.jpg)



5. **[ShapeNet](https://www.shapenet.org/)  (2015).   [`Seg.`]**

   Including 3Million+ models and 4K+ categories. A collaborative dataset between researchers at Princeton, Stanford and TTIC.

* [PartNet](https://shapenet.org/download/parts) The PartNet dataset provides fine grained part annotation of objects in ShapeNetCore.

![](/3D-Computer-Vision-Research/images/shapenet.jpg)



6. **[Semantic3D](http://www.semantic3d.net/)  (2016).  [`Cls.` `Seg.`]**

   They have created a framework for the fair evaluation of semantic classification in 3D space. In this framework we provide:

* A large set of point clouds with over **four billion** of labelled points. It covers a range of diverse urban scenes: churches, streets, railroad tracks, squares, villages, soccer fields, castles to name just a few.
* Ground truth, hand-labelled by professional assessors. 
* A common evaluation tool providing the established intersection-union measure along with the full confusion matrix.

![](/3D-Computer-Vision-Research/images/sg.jpg)



7. **[3D MNIST](https://www.kaggle.com/daavoo/3d-mnist)  (2017).  [`Cls.`]**

   The aim of this dataset is to provide a simple way to get started with 3D computer vision problems such as 3D shape recognition. 

![](/3D-Computer-Vision-Research/images/dataset-original.png)



8. **[SceneNN](http://www.scenenn.net/)   (2016).  [`Cls.` `Seg.`]**

   RGB-D scene meshes dataset consisting of more than 100 indoor scenes, captured at various places, e.g., offices, dormitory, classrooms, pantry, etc. All scenes are reconstructed into triangle meshes and have per-vertex and per-pixel annotation. 

![](/3D-Computer-Vision-Research/images/segmented.png)



9. **[S3DIS](http://buildingparser.stanford.edu/dataset.html#Download)   (2017).  [ `Seg.`]**

   The Stanford Large-Scale 3D Indoor Spaces Dataset. The dataset is collected in 6 large-scale indoor areas that originate from 3 different buildings of mainly educational and office use. It contains colored point clouds and textured meshes for each scanned area. 3D semantic annotations for objects and scenes are offered for both modalities, with point-level and face-level labels correspondingly. 

![](/3D-Computer-Vision-Research/images/S3DIS.png)



10. **[ScanNet](http://www.scan-net.org/)  (2017).  [__`Cls.`__ __`Seg.`__]**

    Richly-annotated 3D Reconstructions of Indoor Scenes. An RGB-D video dataset containing 2.5 million views in more than 1500 scans, annotated with 3D camera poses, surface reconstructions, and instance-level semantic segmentations.

![](/3D-Computer-Vision-Research/images/scannet_benchmark.jpg)



11. **[NPM3D](http://npm3d.fr/paris-lille-3d)  (2017) .  [__`Cls.`__ __`Seg.`__]**

     The Paris-Lille-3D  has been produced by a Mobile Laser System (MLS) in two different cities in France (Paris and Lille). The Point Cloud has been labeled entirely by hand with 50 different classes to help the research community on automatic point cloud segmentation and classification algorithms.

![](/3D-Computer-Vision-Research/images/Paris_Lille_3D_GT7.jpg)



12. **[[UWA Dataset](http://staffhome.ecm.uwa.edu.au/~00053650/databases.html)]  (2006-2018).  [`Cls.` `Seg.` `Reg.`]**

    Organized 15 datasets, including these:

* Database for 3D object recognition in cluttered scenes: There are 50 different scenes scanned with the Minolta scanner.
* Database for 3D surface registration (3D modeling) 
* Database for  FACE DATABASE (3D scans and 2D images under different illuminations): Frontal face images under varying illumination (from an LCD) and the corresponding 3D face model (acquired with Minolta laser scanner).
* ....

13. **[KITTI](http://www.cvlibs.net/datasets/kitti/)  (2015).  [`Seg.`  `Det.`]** 

    The KITTI Vision Benchmark Suite.

* **[SemanticKITTI](http://semantic-kitti.org/dataset.html)  (2019).**  [__`Seg.`__  __`Aut.`__]

   A Dataset for Semantic Scene Understanding using LiDAR Sequences, 28 classes, for autonomous driving. All sequences of KITTI odometry labeled.

![](/3D-Computer-Vision-Research/images/semantic-ptcl.gif)

14. **[Canadian Planetary Emulation Terrain 3D Mapping Dataset](http://asrl.utias.utoronto.ca/datasets/3dmap/)  [`SLAM.`]**

    The Canadian Planetary Emulation Terrain 3D Mapping Dataset is a collection of three-dimensional laser scans gathered at two unique planetary analogue rover test facilities in Canada. These test facilities offer emulated planetary terrain in controlled environments, as well as at manageable scales for algorithmic development. This dataset is subdivided into four individual subsets, gathered using panning laser rangefinders mounted on mobile rover platforms. All of the data are presented in human-readable text files, and are accompanied by Matlab parsing scripts to facilitate use thereof.

![](/3D-Computer-Vision-Research/images/canadian.png)

15. **[Robotic 3D Scan Repository](http://asrl.utias.utoronto.ca/datasets/3dmap/) (2017).  [__`SLAM.`__  `Aut.`]**

    There are 27 date sets available now, This repository provides:

- 3D point clouds from robotic experiments

- log files of robot runs

- standard 3D data sets for the robotics community

  ![](/3D-Computer-Vision-Research/images/thermotownhall.jpg)

16. **[Matterport3D](https://niessner.github.io/Matterport/)  (2018).   [`Cls.` `Seg.` `Reg.`]**

    RGB-D: 10,800 panoramic views from 194,400 RGB-D images. Annotations: surface reconstructions, camera poses, and 2D and 3D semantic segmentations. Keypoint matching, view overlap prediction, normal prediction from color, semantic segmentation, and scene classification. 

![](/3D-Computer-Vision-Research/images/teaser.png)



17. **[PedX](https://arxiv.org/abs/1809.03605)  (2018)   [`Pos.` `Aut.`]** 

    3D Pose Estimation of Pedestrians, more than 5,000 pairs of high-resolution (12MP) stereo images and LiDAR data along with providing 2D and 3D labels of pedestrians.

    ![](/3D-Computer-Vision-Research/images/pedx.png)

    

18. **[Lyft Level 5](https://level5.lyft.com/dataset/?source=post_page)   (2019).  [`Det.` `Seg.` `Aut.`]**

    A large-scale dataset featuring the raw sensor camera and LiDAR inputs as perceived by a fleet of multiple, high-end, autonomous vehicles in a bounded geographic area. This dataset also includes high quality, human-labelled 3D bounding boxes of traffic agents, an underlying HD spatial semantic map. 

![](/3D-Computer-Vision-Research/images/LYFT.png)



19. **[Argoverse BY ARGO AI](https://www.argoverse.org/)  (2019).  [`Tra.` `Aut.`]**

    The data in Argoverse comes from a subset of the area in which Argo AI’s self-driving test vehicles are operating in Miami and Pittsburgh, Two public datasets (3D Tracking and Motion Forecasting) supported by highly detailed maps to test, experiment, and teach self-driving vehicles how to understand the world around them.

![](/3D-Computer-Vision-Research/images/ARGOVERSE.png)



20. **[H3D](https://usa.honda-ri.com/H3D)  (2019).  [`Det.` `Tra.` `Aut.`]**

    The H3D is a large scale full-surround 3D multi-object detection and tracking dataset. It is gathered from HDD dataset, a large scale naturalistic driving dataset collected in San Francisco Bay Area.  

![](/3D-Computer-Vision-Research/images/h3D.png)

21. **[[WAD](http://wad.ai/2019/challenge.html)] [[ApolloScape](http://apolloscape.auto/tracking.html)]  (2019).  [ `Seg.` `Det.` `Aut.`]**  

    The datasets are provided by Baidu Inc. They use an acquisition car to collect traffic data, including camera-based images and LiDAR-based point clouds, and trajectories of traffic-agents in the range of LiDAR. The new dataset with about 150min sequential data is a large-scale dataset for urban streets, which focuses on heterogeneous traffic-agents for 3D detection, tracking, trajectory prediction, motion planning, and simulation tasks.

![](/3D-Computer-Vision-Research/images/APOLLO.gif)



22. **[[nuScenes](https://d3u7q4379vrm7e.cloudfront.net/object-detection)]  (2019).  [`Det.`  `Aut.`]**

    The nuScenes dataset is a large-scale autonomous driving dataset. 

![](/3D-Computer-Vision-Research/images/NUtasks.png)



23. **[Waymo Open Dataset](https://waymo.com/open/) (2020). [`Det.`  `Aut.`]**

    The Waymo Open Dataset is comprised of high resolution sensor data collected by Waymo self-driving cars in a wide variety of conditions. It currently contains 1,950 segments. 

![](/3D-Computer-Vision-Research/images/waymo.gif)



24. **[PreSIL](https://uwaterloo.ca/waterloo-intelligent-systems-engineering-lab/projects/precise-synthetic-image-and-lidar-presil-dataset-autonomous)  (2020).  [`Det.` `Aut.`]** 

    The Precise Synthetic Image and LiDAR (PreSIL) dataset for autonomous vehicle perception.Depth information, semantic segmentation (images), point-wise segmentation (point clouds), ground point labels (point clouds), and detailed annotations for all vehicles and people. 

![PRESIL2](/3D-Computer-Vision-Research/images/PRESIL2.png)

