---
layout: archive
title: "Projects"
permalink: /publications/
author_profile: true
---

![](itsc1.PNG | width=100)
## CurbScan: Curb Detection and Tracking Using Multi-Sensor Fusion

_ITSC 2020_


Reliable curb detection is critical for safe autonomous driving in urban contexts. Curb detection and tracking are also useful in vehicle localization and path planning. Past work utilized a 3D LiDAR sensor to determine accurate distance information and the geometric attributes of curbs. However, such an approach requires dense point cloud data and is also vulnerable to false positives from obstacles present on both road and off-road areas. In this paper, we propose an approach to detect and track curbs by fusing together data from multiple sensors: sparse LiDAR data, a mono camera and low-cost ultrasonic sensors. The detection algorithm is based on a single 3D LiDAR and a mono camera sensor used to detect candidate curb features and it effectively removes false positives arising from surrounding static and moving obstacles. The detection accuracy of the tracking algorithm is boosted by using Kalman filter-based prediction and fusion with lateral distance information from low-cost ultrasonic sensors. We next propose a line-fitting algorithm that yields robust results for curb locations. Finally, we demonstrate the practical feasibility of our solution by testing in different road environments and evaluating our implementation in a real vehicle Demo video clips demonstrating our algorithm have been uploaded to Youtube. Our algorithm maintains over 90\% accuracy within 4.5-22 meters and 0-14 meters for the KITTI dataset and our dataset respectively, and its average processing time per frame is approximately 10 ms on Intel i7 x86 and 100ms on NVIDIA Xavier board.

[Youtube demo 1](https://www.youtube.com/watch?v=Gd506RklfG8)

[Youtube demo 2](https://www.youtube.com/watch?v=w5MwsdWhcy4)

_Coming soon ..._

## Diverse and Admissible Trajectory Forecasting through Multimodal Context Understanding
_2020 IEEE European Conference on Computer Vision (ECCV)_


Multi-agent trajectory forecasting in autonomous driving requires an agent to accurately anticipate the behaviors of the surrounding vehicles and pedestrians, for safe and reliable decision-making. Due to partial observability over the goals, contexts, and interactions of agents in these dynamical scenes, directly obtaining the posterior distribution over future agent trajectories remains a challenging problem. In realistic embodied environments, each agent's future trajectories should be diverse since multiple plausible sequences of actions can be used to reach its intended goals, and they should be admissible since they must obey physical constraints and stay in drivable areas. In this paper, we propose a model that fully synthesizes multiple input signals from the multimodal world the environment's scene context and interactions between multiple surrounding agents to best model all diverse and admissible trajectories. We offer new metrics to evaluate the diversity of trajectory predictions, while ensuring admissibility of each trajectory. Based on our new metrics as well as those used in prior work, we compare our model with strong baselines and ablations across two datasets and show a 35% performance-improvement over the state-of-the-art.

[Read More](https://arxiv.org/abs/2003.03212)


## Density-adaptive Sampling for Heterogeneous Point Cloud Object Segmentation in Autonomous Vehicle Applications  
_2019 Computer Vision and Pattern Recognition Conference (CVPR)._

Robust understanding of the driving scene is among the key steps for accurate object detection and reliable autonomous driving. Accomplishing these tasks with a high level of precision, however, is not trivial. One of the challenges come from dealing with the heterogeneous density distribution and massively imbalanced class representation in the point cloud data, making the crude implementation of deep learning architectures for point cloud data from other domains less effective. In this paper, we propose a densityadaptive sampling method that can deal with the point density problem while preserving point-object representation. The method works by balancing the point density of pregridded point cloud data using oversampling, and then empirically sample points from the balanced grid. Using the KITTI Vision 3D Benchmark dataset for point cloud segmentation and PointCNN as the classifier of choice, our proposal provides superior results compared to the original PointCNN implementation, improving the performance from 82.73% using voxel-based sampling to 92.25% using our proposed density-adaptive sampling in terms of per class accuracy.

[Read More](http://openaccess.thecvf.com/content_CVPRW_2019/html/UG2_Prize_Challenge/Arief_Density-Adaptive_Sampling_for_Heterogeneous_Point_Cloud_Object_Segmentation_in_Autonomous_CVPRW_2019_paper.html)


## Intelligent Platoon Operating Slot Optimization Method based on Drivers’ Overtaking Behavior
_2019 IEEE Intelligent Transportation Systems Conference (ITSC)_

Vehicles were operating as platoon is a fundamental approach to solve the problem of road traffic efficiency. When a vehicle travels in the two-lane highway, it could overtake only by using the opposing lane. The platoon makes the ego vehicle face the problem of overtaking, which not only interfering with the traffic efficiency improving but also adding the risk of collision. In order to solve this problem, a step-by-step VOPDS (vehicle overtakes the platoon based on driving style) algorithm was proposed, in which an optimal speed matching scheme by researching the relationship between the speed of vehicles before the slot, the speed of vehicles behind the slot, the speed of vehicle joining a platoon and the required safety slot was designed. Also, a Hierarchical Constrained Multi-objective Optimization Method Based on Improved Particle Swarm Optimization is proposed, which provides the optimized speed guidance strategy for the vehicle overtaking a platoon model. In order to make the speed guidance information be accepted by drivers, this paper got driver behavior characteristics statistics by using open-source driving-simulation tool CARLA, through experiments. The algorithm-simulation results imply that the improved particle swarm optimization algorithm has stronger robustness and faster convergence than the traditional algorithms, optimized results which be more in line with drivers' driving style showed an improved both overall operating efficiency and comfortable for single vehicle overtaking a platoon scenario. 

[Read More](https://ieeexplore.ieee.org/abstract/document/8917393)



