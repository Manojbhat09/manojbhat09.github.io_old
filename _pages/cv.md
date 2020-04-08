---
layout: archive
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<!--
include contact information from the front matter
Supported arguments:
    - homepage: url, text
    - phone
    - email
-->


## Education

### **Carnegie Mellon University** 
`2018 - 2020`
> Pittsburgh, PA, USA

- Master of Science - Research 
- Advised by [Dr. Ding Zhao](https://www.meche.engineering.cmu.edu/directory/bios/zhao-ding.html)
- Working on Robust Vision for Autonomous Vehicles

### **Manipal University** 
`2014 - 2018`

> Manipal, India


- B.Tech. in Mechanical, Major in Mechatronics
- Industrial Vision & Perception, Computer Graphics

----

## Experience

### **Carnegie Mellon University, Safe AI Lab & CyLab ** 
`Sept 2018 - Present`

_Research Assistant_<br>
 - Developing camera-LiDAR calibration in Kia-Soul vehicle, simulation in CARLA for testing traffic scenario primitives, 3D Object detection domain adaptation and Unsupervised learning Non-parametric Bayesian algorithms for rare event analysis under Dr. Ding Zhao.     
 - Extending dual HESAI-40p LIDAR sensor firmware, performing signal processing, calibration & Sensor Fusion to collect synchronized PCL-RGB rosbag data in Pittsburgh in Polysync-Drivekit enabled KIA Soul along with calibrated Swift GNSS loc. 
 - Performed Feature Engineering to analyze and design the inputs based on Importance sampling to the Object detection network for performance.
 

### **Robert Bosch Research and Technology Center Pitt**
 `May ~ Aug 19`

_Computer Vision Research Intern_<br>
  - Researching State-of-the-art 3D Deep-Learning detection methods with TensorRT(CUDA) and implemented classical 3D geometric methods for detection and tracking (State Estimation) with raw sensor data. Implemented PointRCNN and PointCNN on KItti-Argo dataset. Designed REST api Annotation tool. Added Kalman filter for state estimation in automatic annotation of Point-cloud 3D boxes. Supported Release to Production in developing online versions of tool. [CVPR 19 Paper](http://bit.ly/2TCdODU)
  - Developed business-goal oriented Constrained Decision tree to prune predictions by thresholding confidence at 97% Accuracy.
  - Evaluated Novel SafeAI lab developed PointCNN-XCRF (Tensorflow) for Region proposal and denoising in Segmentation.

### **Amazon Transportation & Supply chain Analytics** 
`Feb ~ Aug 18`

_Business Intelligence Engineer_<br>
- Developed recommender system algorithms and metrics to classify pincodes. Packages Used - SQL, redshift, Python-Tensor Flow packages.
- Explored SGD regression, SVM to evaluate Orders, Business Delivery-capability & Value decision made in contingencies. 

### **Ashva Electric Motorsports**
`Aug 17 ~ Feb 18`

_Research Engineer_<br>
- Headed a team on research topic Self-Balancing of One-wheeled vehicles and dynamics.    
- Worked on Reinforcement (Machine Learning) algorithm (TD and recently H-Experience replay method) for α-optimal control. Explored inverse reinforcement Model-free method for self-balancing to reach a goal position given current state and multiple pathway.    	
- Worked on Developing a complete control system, a hybrid of model-based and PID control for set-point augmentation to prevent gyroscopic locking. Simulation of the same with Kinematic mechanical modeling was done in matlab (with and without contact forces were compared).
- A pure python script was used to interface with raspberry pi in later development stages for control mechanism including RPM, voltage, Torque and current variable interfaced with hall encoders; and IMU based sensor detection for calibration orientation configuration.

## Projects

### **RoboDutchman (Mechatronic Robot Design)** 
 - Developing a Shipbot robot for Mechatronic Design course. The goal is to fulfill missions in autonomously operating valves of different kind on a ship. The whole software system is developed in ROS.
 - Worked primarily on Vision in Jetson Nano, on Custom dataset. Worked in a team on Hardware component placement design and Software Integration & Inverse Kinematics for Arm design.
 - Working on SLAM on ROS using, 2D lidar, MSCKF with loop closure. Successfully completed Vision localizer, 98% accuracy with Few shot method. Find more at [FlyingDutchman Presents: Mr. Robodutchman](https://sites.google.com/view/flyingdutchman/home)

<!-- ### **Neural Architecture Search for Sensor Fusion and SLAM** `Sept 2018 - Present` -->
### **LiDAR Curb Detection and Multi-Object Tracking** (CyLab CMU - Mobileye) 
`Oct 19 ~ Present`
 - Worked on State estimation problem (Extended Kalman filter) for tracking the curb line and the object location in 3D space using geometric methods.
 - Improving the Curb detection using single LiDAR data using VScan (NVIDIA Xavier). Tracker development & deployment (OpenCV – TF – CUDA C++) .
 - Extending to Multiple LiDAR & Ultrasonic sensor fusion general road boundary detection like Curb, Wall-like boundary. Deliverables include analysis and
comparison of methodologies for real-time tracking, evaluation with required metrics & Documentation.

### **Multi-Modal LIDAR-augmented Multi-Agent Trajectory Forecasting** (CyLab CMU - Mobileye)
 `Jan 20 ~ Present`
 - Improved multi-agent trajectory forecasting under dynamic scene contexts, by incorporating rich multimodal information involved in autonomous driving-namely, visual, map, and CARLA-simulated LiDAR data. Proposed attention based scene context module, tested baselines Vanilla MATF, PRECOG which utilizes Normalizing flow. Participated in utilizing Best Practices in Software Development. Project in Python.  [ECCV Paper](http://bit.ly/3aHqRtC).

### **Projects in Carnegie Mellon University courses**

- Proposed and implemented new approach: Point-cloud Convolutional-tower based One-Stage Object detection, a semi-supervised method to generate precise bounding box from LiDAR point-clouds in a single stage. A solution based on centerness for 3D bounding box detection for LiDAR Pointclouds as inputs. Achieved mAP of 91%(**near State of the art!**) and mIOU of 0.7 on Car-class range. Trained on Argoverse dataset. (Submitted to ICCV)
- Developed Big-Data Spark app as project for building machine Pipeline using Pyspark with multiple nodes for deployment of a Decision Tree & SVM on Scale.
- Ranked in the top 5% of 206 participating teams in Kaggle face classification and verification assignment. Achieved an accuracy of 96% by using an ensemble of ResNeXt and MobileNet architecture. Implemented Mask R-CNN to calculate depth of vehicle positions. Work in Vision class: 3D reconstruction of colosseum using Bundle adjustment along with deep learning topics. Worked on writing Lukas Kanade Image Tracking & SURF, SIFT from scratch.
- Segmentation with MaskRCNN and depth estimation based on Sensor fused LiDAR point-cloud to estimate background and foreground object distance and pose in mapped space. Motion capture and estimation of vehicles in given point-cloud scene using KLT, Unscented Kalman Filter, DeepSORT on BEV.
- Performed verification and analysis of three Visual Inertial Odometry algorithms including VINS-Mono, Okvis, and MSCKF in conditions that match those of the Moon-Ranger rover (Project CubeRover of CMU) on Nvidia TX2 as SLAM course project.


## Skills

- Excellent in Python, good in C/C++ programming and problem-solving skills. 
- In-depth knowledge of ROS
- Solid understanding of linear algebra, geometry, image processing, Strong computer vision skills.

- Programming Language:  C++14, Python, Shell scripting.  
- Libraries & Tools: ROS, PCL, Tensorflow, MongoDB, SQL-server, Redshift, Spark, CUDA, OpenGL, Arduino, CAD, Linux, AWS, S3, UE4.

## Courses (Ask me about them!)
 - ML and AI for Engineers, Linear Algebra, Algorithms -F18
 - Computer Vision, Bayesian-statistics, Computer Systems(A) -S18
 - Robot Localization & Mapping (SLAM) , Introduction to Deep learning, Multimodal Machine Learning -F19
 - Visual Recognition and Learning, Reinforcement Learning

