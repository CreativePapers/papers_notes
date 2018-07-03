# papers_notes


Below are the links, notes and thoughts about the most interesting medical papers, challenges and workshops that I came across. Though, you probably may want to form your own notion of the progress in medical imaging and computer vision by reviewing all recent accepted papers and walking through the content of all tutorials and related workshops:

NOTE: The categories and tags of the papers are very soft and often one paper can be in different topics but I select one that to my best knowledge suits better and will be easier for me to find later.



# Weakly-Supervised Learning.

Most current solutions to range of medical imaging tasks from segmentation to classification rely on methods based on convolutional neural networks (CNNs). With networks becoming ever more sophisticated, the main bottleneck now is the  availability of sufficiently large training datasets, which typically require a large annotation effort. Weakly-supervised methods that reduce the amount of annotation required to achieve a desired level of performance are therefore valuable.


* __Iterative Attention Mining for Weakly Supervised Thoracic Disease Pattern Localization in Chest X-Rays__. Jinzheng et al, [[pdf]](http://www.cs.jhu.edu/%7Elelu/publication/MICCAI2018_ChestXRay_IAM.pdf)
(_MICCAI_, _2018_)

* [DeepGlobe: A Challenge for Parsing the Earth through Satellite Images](	DeepGlobe: A Challenge for Parsing the Earth through Satellite Images), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W4.py)

## Generative Adversarial Networks (GANs)

Challenges related to the autonomous driving at CVPR 2018:

* [Autonomous Driving Challenge](http://wad.ai/challenge.html), CVPR 2018
* [Robust Vision Challenge](http://www.robustvision.net/), CVPR 2018

Future autonomous driving challenges:

* [Scene Understanding for Autonomous Navigation in Unstructured Environments](http://cvit.iiit.ac.in/autonue2018/), ECCV 2018
* [ApolloScape: Vision-based Navigation for Autonomous Driving](http://apolloscape.auto/ECCV/challenge.html), ECCV 2018


## Autonomous Driving Datasets

Most mentioned datasets related to the self-driving car space:
* [KITTI Vision Benchmark Suite](http://www.cvlibs.net/datasets/kitti/)
* [ApolloScape Dataset](http://apolloscape.auto/)
* [Berkeley DeepDrive (BDD100K)](https://deepdrive.berkeley.edu/)
* [Oxford RobotCar Dataset](http://robotcar-dataset.robots.ox.ac.uk/)
* [Cityscapes Dataset](https://www.cityscapes-dataset.com/)
* [HD1K Dataset](http://hci-benchmark.org/)
* [WildDash Dataset](http://www.wilddash.cc/)
* [DAVIS Driving Dataset](https://docs.google.com/document/d/1HM0CSmjO8nOpUeTvmPjopcBcVCk7KXvLUuiZFS6TWSg/pub), and other [datasets](http://sensors.ini.uzh.ch/databases.html) from INI Zurich
* [TorontoCity Dataset](https://arxiv.org/abs/1612.00423) (didn't find a link to the dataset page)


## Autonomous driving related workshops/tutorials

Mentioned workshops and tutorials cover the most frequent topics related to the self-driving car development space.

* [Workshop on Autonomous Driving](http://www.wad.ai/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W14.py)
* [Robust Vision Challenge](http://www.robustvision.net/)
* [Embedded Vision Workshop](https://embeddedvisionworkshop.wordpress.com/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W12.py)
* [Workshop on Visual Odometry and Computer Vision Applications Based on Location Clues](http://www.cis.rit.edu/~glpci/vocvalc2018/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W30.py)
* [Beyond Supervised Learning](http://www.beyond-supervised.ai/)
* [Computational Imaging for Self-Driving Vehicles](http://imagingav.media.mit.edu/)
* [Computer Vision for Robotics and Driving](https://sites.google.com/view/visionroboticsdriving)
* [Deep Learning for Visual SLAM](http://visualslam.ai/), [[papers]](http://openaccess.thecvf.com/CVPR2018_workshops/CVPR2018_W9.py)




## Autonomous Driving Papers

Here the papers that I've noticed during oral or spotlight sessions, or as a poster. Some of they directly related to the autonomous cars and from companies like Uber/Lyft, but some of them cover broader topic or direction that can be used for self-driving car development.

* __Semantic Binary Segmentation Using Convolutional Networks Without Decoders__. Shubhra Aich, William van der Kamp, Ian Stavness, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Aich_Semantic_Binary_Segmentation_CVPR_2018_paper.pdf) (_road extraction_)

* __D-LinkNet: LinkNet With Pretrained Encoder and Dilated Convolution for High Resolution Satellite Imagery Road Extraction__
Lichen Zhou, Chuang Zhang, Ming Wu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Zhou_D-LinkNet_LinkNet_With_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Stacked U-Nets With Multi-Output for Road Extraction__
Tao Sun, Zehui Chen, Wenxiang Yang, Yin Wang,
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Sun_Stacked_U-Nets_With_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Fully Convolutional Network for Automatic Road Extraction From Satellite Imagery__. Alexander Buslaev, Selim Seferbekov, Vladimir Iglovikov, Alexey Shvets
[[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Buslaev_Fully_Convolutional_Network_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Road Detection With EOSResUNet and Post Vectorizing Algorithm__.
Oleksandr Filin, Anton Zapara, Serhii Panchenko, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Filin_Road_Detection_With_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Residual Inception Skip Network for Binary Segmentation__. Jigar Doshi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Doshi_Residual_Inception_Skip_CVPR_2018_paper.pdf) (_road extraction_)

* __Roadmap Generation Using a Multi-Stage Ensemble of Deep Neural Networks With Smoothing-Based Optimization__. Dragos Costea, Alina Marcu, Emil Slusanschi, Marius Leordeanu, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Costea_Roadmap_Generation_Using_CVPR_2018_paper.pdf) (_road extraction_, _segmentation_)

* __Rotated Rectangles for Symbolized Building Footprint Extraction__. Matt Dickenson, Lionel Gueguen, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Dickenson_Rotated_Rectangles_for_CVPR_2018_paper.pdf) (_building detection_, _segmentation_, _Uber_)

* __Feature Pyramid Network for Multi-Class Land Segmentation__. Selim Seferbekov, Vladimir Iglovikov, Alexander Buslaev, Alexey Shvets, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w4/Seferbekov_Feature_Pyramid_Network_CVPR_2018_paper.pdf) (_land segmentation_, _Lyft_)

* __The ApolloScape Dataset for Autonomous Driving__.
Xinyu Huang, Xinjing Cheng, Qichuan Geng, Binbin Cao, Dingfu Zhou, Peng Wang, Yuanqing Lin, Ruigang Yang, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Huang_The_ApolloScape_Dataset_CVPR_2018_paper.pdf) (_dataset_, _detection_, _segmentation_, _localization_, _Baidu_)

* __Scene Understanding Networks for Autonomous Driving Based on Around View Monitoring System__. Jeong Yeol Baek, Ioana Veronica Chelu, Livia Iordache, Vlad Paunescu, HyunJoo Ryu, Alexandru Ghiuta, Andrei Petreanu, YunSung Soh, Andrei Leica, ByeongMoon Jeon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Baek_Scene_Understanding_Networks_CVPR_2018_paper.pdf) (_detection_)

* __Training Deep Networks With Synthetic Data: Bridging the Reality Gap by Domain Randomization__. Jonathan Tremblay, Aayush Prakash, David Acuna, Mark Brophy, Varun Jampani, Cem Anil, Thang To, Eric Cameracci, Shaad Boochoon, Stan Birchfield, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tremblay_Training_Deep_Networks_CVPR_2018_paper.pdf) (_detection_, _NVidia_)

* __On the Iterative Refinement of Densely Connected Representation Levels for Semantic Segmentation__. Arantxa Casanova, Guillem Cucurull, Michal Drozdzal, Adriana Romero, Yoshua Bengio, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Casanova_On_the_Iterative_CVPR_2018_paper.pdf)

* __Minimizing Supervision for Free-Space Segmentation__. Satoshi Tsutsui, Tommi Kerola, Shunta Saito, David J. Crandall, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Tsutsui_Minimizing_Supervision_for_CVPR_2018_paper.pdf)

* __On the Importance of Stereo for Accurate Depth Estimation: An Efficient Semi-Supervised Deep Neural Network Approach__. Nikolai Smolyanskiy, Alexey Kamenev, Stan Birchfield, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Smolyanskiy_On_the_Importance_CVPR_2018_paper.pdf) (_depth estimation_, _NVidia_)

* __Accurate Deep Direct Geo-Localization From Ground Imagery and Phone-Grade GPS__. Shaohui Sun, Ramesh Sarukkai, Jack Kwok, Vinay Shet, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Sun_Accurate_Deep_Direct_CVPR_2018_paper.pdf) (_Lyft_)

* __Efficient and Safe Vehicle Navigation Based on Driver Behavior Classification__. Ernest Cheung, Aniket Bera, Dinesh Manocha, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Cheung_Efficient_and_Safe_CVPR_2018_paper.pdf)

* __Detection of Distracted Driver Using Convolutional Neural Network__. Bhakti Baheti, Suhas Gajre, Sanjay Talbar, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Baheti_Detection_of_Distracted_CVPR_2018_paper.pdf)

* __Classifying Group Emotions for Socially-Aware Autonomous Vehicle Navigation__. Aniket Bera, Tanmay Randhavane, Austin Wang, Dinesh Manocha, Emily Kubin, Kurt Gray, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Bera_Classifying_Group_Emotions_CVPR_2018_paper.pdf)

* __AutonoVi-Sim: Autonomous Vehicle Simulation Platform With Weather, Sensing, and Traffic Control__. Andrew Best, Sahil Narang, Lucas Pasqualin, Daniel Barber, Dinesh Manocha, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Best_AutonoVi-Sim_Autonomous_Vehicle_CVPR_2018_paper.pdf)

* __Subset Replay Based Continual Learning for Scalable Improvement of Autonomous Systems__. Pratik Prabhanjan Brahma, Adrienne Othon, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Brahma_Subset_Replay_Based_CVPR_2018_paper.pdf) (_Volkswagen_)

* __Deep Parametric Continuous Convolutional Neural Networks__. Shenlong Wang, Simon Suo, Wei-Chiu Ma, Andrei Pokrovsky, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_Deep_Parametric_Continuous_CVPR_2018_paper.pdf) (_point cloud_, _segmentation_, _motion estimation_, _Uber_)

* __Hierarchical Recurrent Attention Networks for Structured Online Maps__. Namdar Homayounfar, Wei-Chiu Ma, Shrinidhi Kowshika Lakshmikanth, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Homayounfar_Hierarchical_Recurrent_Attention_CVPR_2018_paper.pdf) (_point cloud_, _road extraction_, _Uber_)

* __DeepVoting: A Robust and Explainable Deep Network for Semantic Part Detection Under Partial Occlusion__. Zhishuai Zhang, Cihang Xie, Jianyu Wang, Lingxi Xie, Alan L. Yuille, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_DeepVoting_A_Robust_CVPR_2018_paper.pdf) (_Baidu_)

* __ICE-BA: Incremental, Consistent and Efficient Bundle Adjustment for Visual-Inertial SLAM__. Haomin Liu, Mingyu Chen, Guofeng Zhang, Hujun Bao, Yingze Bao, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Liu_ICE-BA_Incremental_Consistent_CVPR_2018_paper.pdf) [[source code]](https://github.com/baidu/ICE-BA) (_SLAM_, _Baidu_)

* __Social GAN: Socially Acceptable Trajectories With Generative Adversarial Networks__. Agrim Gupta, Justin Johnson, Li Fei-Fei, Silvio Savarese, Alexandre Alahi, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gupta_Social_GAN_Socially_CVPR_2018_paper.pdf) (_trajectory prediction_, _Stanford_)

* __Fast and Furious: Real Time End-to-End 3D Detection, Tracking and Motion Forecasting With a Single Convolutional Net__. Wenjie Luo, Bin Yang, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Luo_Fast_and_Furious_CVPR_2018_paper.pdf)
(_detection_, _tracking_, _prediction_, _Uber_)

* __DeLS-3D: Deep Localization and Segmentation With a 3D Semantic Map__. Peng Wang, Ruigang Yang, Binbin Cao, Wei Xu, Yuanqing Lin, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Wang_DeLS-3D_Deep_Localization_CVPR_2018_paper.pdf)
(_Baidu_)

* __Multi-Task Learning Using Uncertainty to Weigh Losses for Scene Geometry and Semantics__. Alex Kendall, Yarin Gal, Roberto Cipolla, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kendall_Multi-Task_Learning_Using_CVPR_2018_paper.pdf)
(_depth estimation_)

* __Matching Adversarial Networks__. Gellért Máttyus, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mattyus_Matching_Adversarial_Networks_CVPR_2018_paper.pdf)
(_segmentation_, _Uber_)


### 3D Reconstruction & 3D Vision

* __Learning Hierarchical Models for Class-Specific Reconstruction From Natural Data__. Arun CS Kumar, Suchendra M. Bhandarkar, Mukta Prasad, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018_workshops/papers/w14/Kumar_Learning_Hierarchical_Models_CVPR_2018_paper.pdf)
(_detection_, _pose estimation_, _3d reconstruction_)

* __PointFusion: Deep Sensor Fusion for 3D Bounding Box Estimation__. Danfei Xu, Dragomir Anguelov, Ashesh Jain, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Xu_PointFusion_Deep_Sensor_CVPR_2018_paper.pdf)
(_3d detection_, _Zoox_)

* __Frustum PointNets for 3D Object Detection From RGB-D Data__. Charles R. Qi, Wei Liu, Chenxia Wu, Hao Su, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Qi_Frustum_PointNets_for_CVPR_2018_paper.pdf)
(_3d detection_, _Nuro_)

* __3D-RCNN: Instance-Level 3D Object Reconstruction via Render-and-Compare__. Abhijit Kundu, Yin Li, James M. Rehg, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Kundu_3D-RCNN_Instance-Level_3D_CVPR_2018_paper.pdf)
[[project page]](http://abhijitkundu.info/projects/3D-RCNN/)

* __LEGO: Learning Edge With Geometry All at Once by Watching Videos__. Zhenheng Yang, Peng Wang, Yang Wang, Wei Xu, Ram Nevatia, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_LEGO_Learning_Edge_CVPR_2018_paper.pdf)
(_3d reconstruction_, _Baidu_)

* __SurfConv: Bridging 3D and 2D Convolution for RGBD Images__. Hang Chu, Wei-Chiu Ma, Kaustav Kundu, Raquel Urtasun, Sanja Fidler, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chu_SurfConv_Bridging_3D_CVPR_2018_paper.pdf)
(_3d segmentation_, _Uber_)

* __PIXOR: Real-Time 3D Object Detection From Point Clouds__. Bin Yang, Wenjie Luo, Raquel Urtasun, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Yang_PIXOR_Real-Time_3D_CVPR_2018_paper.pdf)
(_Uber_)

Below are papers from other topics that are not always related to the autonomous driving.

# Context/Geometry Awareness

Context aware papers:
* __COCO-Stuff: Thing and Stuff Classes in Context__. Holger Caesar, Jasper Uijlings, Vittorio Ferrari, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Caesar_COCO-Stuff_Thing_and_CVPR_2018_paper.pdf) (_context_, _segmentation_, _Google_)

* __Finding "It": Weakly-Supervised Reference-Aware Visual Grounding in Instructional Videos__. De-An Huang, Shyamal Buch, Lucio Dery, Animesh Garg, Li Fei-Fei, Juan Carlos Niebles, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Huang_Finding_It_Weakly-Supervised_CVPR_2018_paper.pdf)
(_Stanford_)

* __Context Encoding for Semantic Segmentation__. Hang Zhang, Kristin Dana, Jianping Shi, Zhongyue Zhang, Xiaogang Wang, Ambrish Tyagi, Amit Agrawal, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Context_Encoding_for_CVPR_2018_paper.pdf)
(_Amazon_)

Geometry awareness:
* __Geometry-Aware Learning of Maps for Camera Localization__. Samarth Brahmbhatt, Jinwei Gu, Kihwan Kim, James Hays, Jan Kautz, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Brahmbhatt_Geometry-Aware_Learning_of_CVPR_2018_paper.pdf) [[project page]](http://research.nvidia.com/publication/2018-06_Geometry-Aware-Learning-of)
[[code]](https://github.com/NVlabs/geomapnet)
(_localization_, _SLAM_, _NVidia_)

* __Geometry Guided Convolutional Neural Networks for Self-Supervised Video Representation Learning__. Chuang Gan, Boqing Gong, Kun Liu, Hao Su, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Gan_Geometry_Guided_Convolutional_CVPR_2018_paper.pdf)
(_Stanford_, _MIT_)

* __Unsupervised Learning of Depth and Ego-Motion From Monocular Video Using 3D Geometric Constraints__. Reza Mahjourian, Martin Wicke, Anelia Angelova, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Mahjourian_Unsupervised_Learning_of_CVPR_2018_paper.pdf)
(_Google_)



# Graph Based, Structure discovery

* __Image Generation From Scene Graphs__. Justin Johnson, Agrim Gupta, Li Fei-Fei, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Johnson_Image_Generation_From_CVPR_2018_paper.pdf)

* __Unsupervised Discovery of Object Landmarks as Structural Representations__. Yuting Zhang, Yijie Guo, Yixin Jin, Yijun Luo, Zhiyuan He, Honglak Lee [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Zhang_Unsupervised_Discovery_of_CVPR_2018_paper.pdf) (_unsupervised_, _GAN_, _Google_)

* __Distributable Consistent Multi-Object Matching__. Nan Hu, Qixing Huang, Boris Thibert, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Hu_Distributable_Consistent_Multi-Object_CVPR_2018_paper.pdf) (_matching_, _Stanford_)

* __Referring Relationships__. Ranjay Krishna, Ines Chami, Michael Bernstein, Li Fei-Fei, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Krishna_Referring_Relationships_CVPR_2018_paper.pdf)
(_detection_, _Stanford_)

* __Beyond Holistic Object Recognition: Enriching Image Understanding With Part States__. Cewu Lu, Hao Su, Yonglu Li, Yongyi Lu, Li Yi, Chi-Keung Tang, Leonidas J. Guibas, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Lu_Beyond_Holistic_Object_CVPR_2018_paper.pdf)

* __Iterative Visual Reasoning Beyond Convolutions__. Xinlei Chen, Li-Jia Li, Li Fei-Fei, Abhinav Gupta, [[pdf]](http://openaccess.thecvf.com/content_cvpr_2018/papers/Chen_Iterative_Visual_Reasoning_CVPR_2018_paper.pdf)
[[code]](https://github.com/endernewton/iter-reason)
(_Stanford_)



