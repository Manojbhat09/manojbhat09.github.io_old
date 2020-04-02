---
layout: archive
title: "CV"
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

### **Carnegie Mellon University** `2018 - 2020`
> Pittsburgh, PA, USA

- Master of Science - Research 
- Advised by [Dr. Ding Zhao](https://www.meche.engineering.cmu.edu/directory/bios/zhao-ding.html)
- Working on Robust Vision for Autonomous Vehicles

### **Manipal University** `2014 - 2018`

> Manipal, India


- B.Tech. in Mechanical, Major in Mechatronics
- Industriall Vision & Perception, Computer Graphics

----

## Experience

### **Carnegie Mellon University, Safe AI Lab** &nbsp;&nbsp;&nbsp; `Sept 2018 - Present`

_Research Assistant_<br>
 - Developing camera-LiDAR calibration in Kia-Soul vehicle, simulation in CARLA for testing traffic scenario primitives, 3D Object detection domain adaptation and Unsupervised learning Non-parametric Bayesian algorithms for rare event analysis under Dr. Ding Zhao.     
 - Extending dual HESAI-40p LIDAR sensor firmware, performing signal processing, calibration & Sensor Fusion to collect synchronized PCL-RGB rosbag data in Pittsburgh in Polysync-Drivekit enabled KIA Soul along with calibrated Swift GNSS loc. 
 - Performed Feature Engineering to analyze and design the inputs based on Importance sampling to the Object detection network for performance.

### **Robert Bosch Research and Technology Center Pitt** &nbsp;&nbsp;&nbsp; `May ~ Aug 19`

_Computer Vision Research Intern_<br>
  - Researching State-of-the-art 3D Deep-Learning detection methods with TensorRT(CUDA) and implemented classical 3D geometric methods for detection and tracking (State Estimation) with raw sensor data. Implemented PointRCNN and PointCNN on KItti-Argo dataset. Designed REST api Annotation tool. Added Kalman filter for state estimation in automatic annotation of Point-cloud 3D boxes. Supported Release to Production in developing online versions of tool. [CVPR 19 Paper](http://bit.ly/2TCdODU)
  - Developed business-goal oriented Constrained Decision tree to prune predictions by thresholding confidence at 97% Accuracy.
  - Evaluated Novel SafeAI lab developed PointCNN-XCRF (Tensorflow) for Region proposal and denoising in Segmentation.

### **Amazon Transportation & Supply chain Analytics** &nbsp;&nbsp;&nbsp; `Feb ~ Aug 18`

_Business Intelligence Engineer_<br>
- Developed recommender system algorithms and metrics to classify pincodes. Packages Used - SQL, redshift, Python-Tensor Flow packages.
- Explored SGD regression, SVM to evaluate Orders, Business Delivery-capability & Value decision made in contingencies. 

### **Ashva Electric Motorsports** &nbsp;&nbsp;&nbsp; `Nov 17 ~ Dec 18`

_Business Intelligence Engineer_<br>
- Headed a team on research topic Self-Balancing of One-wheeled vehicles and dynamics.    
- Worked on Reinforcement (Machine Learning) algorithm (TD and recently H-Experience replay method) for α-optimal control. Explored inverse reinforcement Model-free method for self-balancing to reach a goal position given current state and multiple pathway.    	

## Projects

<!-- ### **Neural Architecture Search for Sensor Fusion and SLAM** `Sept 2018 - Present` -->
### **LiDAR Curb Detection and Multi-Object Tracking** (CyLab CMU - Mobileye) &nbsp;&nbsp;&nbsp; `Oct 19 ~ Present`
 - Worked on State estimation problem (Extended Kalman filter) for tracking the curb line and the object location in 3D space using geometric methods.
 - Improving the Curb detection using single LiDAR data using VScan (NVIDIA Xavier). Tracker development & deployment (OpenCV – TF – CUDA C++) .
 - Extending to Multiple LiDAR & Ultrasonic sensor fusion general road boundary detection like Curb, Wall-like boundary. Deliverables include analysis and
comparison of methodologies for real-time tracking, evaluation with required metrics & Documentation.

### **Multi-Modal LIDAR-augmented Multi-Agent Trajectory Forecasting** (CyLab CMU - Mobileye) &nbsp;&nbsp;&nbsp; `Jan 20 ~ Present`
 - Improved multi-agent trajectory forecasting under dynamic scene contexts, by incorporating rich multimodal information involved in autonomous driving-namely, visual, map, and CARLA-simulated LiDAR data. Proposed attention based scene context module, tested baselines Vanilla MATF, PRECOG which utilizes Normalizing flow. Participated in utilizing Best Practices in Software Development. Project in Python.  [ECCV Paper](http://bit.ly/3aHqRtC).

### **Projects in Carnegie Mellon University courses**

- Developed Big-Data Spark app as project for building machine Pipeline using Pyspark with multiple nodes for deployment of a Decision Tree & SVM on Scale.
- Ranked in the top 5% of 206 participating teams in Kaggle face classification and verification assignment. Achieved an accuracy of 78% by using an ensemble of ResNeXt and MobileNet architecture. Implemented Mask R-CNN to calculate depth of vehicle positions. Work in Vision class: 3D reconstruction of colosseum using Bundle adjustment along with deep learning topics.
- Segmentation with MaskRCNN and depth estimation based on Sensor fused LiDAR point-cloud to estimate background and foreground object distance and pose in mapped space. Motion capture and estimation of vehicles in given point-cloud scene using KLT, Unscented Kalman Filter, DeepSORT on BEV.
- Performed verification and analysis of three Visual Inertial Odometry algorithms including VINS-Mono, Okvis, and MSCKF in conditions that match those of the Moon-Ranger rover (Project CubeRover of CMU) on Nvidia TX2 as SLAM course project.
- Proposed and implemented new approach: Point-cloud Convolutional-tower based One-Stage Object detection, a semi-supervised method to generate precise bounding box from LiDAR point-clouds in a single stage. A solution based on centerness for 3D bounding box detection for LiDAR Pointclouds as inputs. Achieved mAP of 96%(>SOTA) and mIOU of 0.8 on Car-class range. Trained on Argoverse dataset. (Submitted to ICCV)

## Skills

- Excellent in Python, good in C/C++ programming and problem-solving skills. 
- In-depth knowledge of ROS
- Solid understanding of linear algebra, geometry, image processing, Strong computer vision skills.

- Programming Language:  C++14, Python, Shell scripting.  
- Libraries & Tools: ROS, PCL, Tensorflow, MongoDB, SQL-server, Redshift, Spark, CUDA, OpenGL.

## Courses (Ask me about them!)
 - ML and AI for Engineers, Linear Algebra, Algorithms -F18
 - Computer Vision, Bayesian-statistics, Computer Systems(A)-S18
 - SLAM, Intro to Deep learning, Multimodal Machine Learning-F19
 - Visual Recognition and Learning, Reinforcement Learning


<!-- 
### **Columbia University, Computer Graphics and User Interfaces Lab** `2017.1 - 2017.5`

_Research Assistant_<br>
Worked with prof. Steven Feiner, on **Cyber Affordance Visualization in Augumented Reality** project. Developed a Microsoft Hololens application that visualizes the Columbia campus in AR environment.

### **AsiaInfo** `2015.6 - 2015.8`

_Software Engineering Intern_<br>
Worked on server-side web applications and server deployment tools.

## Mentoring

Max Krieger (CMU, independent research & [REUSE](https://www.cmu.edu/scs/isr/reuse/)) `CMU, 2018 - Now` <br>
Courtney Miller (New College of Florida, [REUSE](https://www.cmu.edu/scs/isr/reuse/)) `CMU, 2019` <br>
Anael Kuperwajs Cohen (Macalester College, [REUSE](https://www.cmu.edu/scs/isr/reuse/)) `CMU, 2019` <br>

## Teaching

Teaching Assistant, **Programming Languages and Translators (COMS 4115)** `Columbia, 2017 - 2018` <br>
Teaching Assistant, **Introduction to Java II (COMP 132)** `Dickinson, 2016` <br>
Peer Tutor, **Data Structures and Problem Solving (COMP 232)** `Dickinson, 2016` <br>
Computer Lab Consultant `Dickinson, 2014 - 2016` <br>

## Honors & Awards

CHI'20 Best Paper Honourable Mention Award `CMU, 2020` <br>
Phi Beta Kappa `Dickinson, 2018` <br>
Excellence in Computer Science Award `Columbia, 2018` <br>
Travel Award PL Mentoring Workshop (PLMW) `SPLASH, 2018` <br>
Tau Beta Pi, Engineering Honor Society `Columbia, 2017` <br>
Computer Science Departmental Honors `Dickinson, 2016` <br>
Pi Mu Epsilon, Mathematics Honor Society `Dickinson, 2016` <br>
Upsilon Pi Epsilon, Computer Science Honor Society `Dickinson, 2016` <br>
Alpha Lambda Delta, First year Honor Society `Dickinson, 2013`<br>
John Montgomery Scholarship `Dickinson, 2013` <br>

## Service

Research Experiences for Undergraduates in Software Engineering (REUSE) Admission Committee `CMU, 2019 - 2020` -->

<!-- Education
======
* B.S. in GitHub, GitHub University, 2012
* M.S. in Jekyll, GitHub University, 2014
* Ph.D in Version Control Theory, GitHub University, 2018 (expected)

Work experience
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub
  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
