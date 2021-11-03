# Deep Learning for Autonomous Driving
This repository DOES NOT contain the code of the projects but only their description. The code cannot be shared due to privacy purposes expressed by the professor of this course.

The topics covered in the projects are the following:
<ul>
  <li>sensor fusion of LiDAR, cameras, and IMU data;</li>
  <li>deep learning networks for semantic segmentation and depth estimation from 2D images;</li>
  <li>deep learning network for 3D object detection from point clouds.</li>
</ul>


#

Overall rating of the projects: 114% (bonus points thanks to optional assignments).

#

## Project 1: Understanding Multimodal Driving Data
The goal of the first project is to visualize the outputs of common autonomous driving tasks such as 3D object detection and point cloud semantic segmentation given a LiDAR point cloud, the corresponding RGB camera image, the ground truth semantic labels and the network bounding box predictions.  
  
Additional tasks were about identifying each laser ID directly from the point cloud, and dealing with the point cloud distortion caused by the vehicle motion with the aid of GPS/IMU data.  
  
Further info: [Assignment_Project1.pdf](Project1_Understanding_Multimodal_Driving_Data/Assignment_Project1.pdf)

<p align="center">
<img height=250 src="https://user-images.githubusercontent.com/79461707/139320268-0e07f613-a7d2-4919-b8ab-6c22c8054f14.png"/>
</p>
  
## Project 2: Multi-task learning for semantics and depth
The goal of the second project is to build Multi-Task Learning (MTL) architectures for dense prediction tasks, i.e. semantic segmentation and monocular depth estimation, exploiting joint architectures, branched architectures, and task distillation.  
  
Bonus task was to improve the network with personal ideas or refer to existing papers to enhance the predictions.  
  
Further info: [Assignment_Project2.pdf](Project2_Multitask_learning_for_semantics_and_depth/Assignment_Project2.pdf)

<p align="center">
<img height=300 src="https://user-images.githubusercontent.com/79461707/139322864-12a3f909-8474-480e-8ed3-1cf57c369fe5.png"/>
</p>  

## Project 3: 3D Object Detection from Lidar Point Clouds

<img align="right" height=140 src="https://user-images.githubusercontent.com/79461707/139320317-a9b324a4-e655-447a-996e-e0e6473b1edf.png"/>

The goal of the third project is to build a 2-stage 3D object detector to detect vehicles in autonomous driving scenes, i.e. drawing 3D bounding boxes around each vehicle. 
While Project 2 was based on 2D images, in this case irregular 3D point cloud data are exploited to detect vehicles.

The first stage, which is often referred to as the Region Proposal Network (RPN), is used to create coarse detection results from the irregular point cloud data. These initial detections are later refined in the second stage network to generate the final predictions.  
  
Further info: [Assignment_Project3.pdf](Project3_3D_Object_Detection_from_Lidar_Point_Clouds/Assignment_Project3.pdf)
<p align="center">
<img height=350 src="https://user-images.githubusercontent.com/79461707/139320646-bf18aa5e-66aa-4575-81ba-c8d613ad2f62.png"/>
</p>
