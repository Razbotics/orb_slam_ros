# Orb_slam2_ros
ORB_SLAM2 with ROS interface
This repo is a simple demo of ORB-SLAM2 in ROS. Data generated from SLAM, such as camera pose, keyframe trajectory and pointcloud are published in ROS.  

* Compile Pangolin independently in this root directory

* Run build.sh to compile the project

* Run launch files
  
  ``` roslaunch orb_slam_ros orb_slam_stereo.launch ``` for launching stereo node

  ``` roslaunch orb_slam_ros orb_slam_mono.launch ``` for launching mono node




