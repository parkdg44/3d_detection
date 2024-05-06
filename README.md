# DBSCAN and Yolov5 Based 3D Object Detection and its Adaptation to a Mobile Platform

## Abstract

This study presents a 3D object detection technology for mobile platforms and its application. 
Rather than an innovative high-performance model, we proposed a “useable” model for the robot industry 
at the current technology stage by combining various techniques. To reduce computation time, a 2D region 
proposal was obtained using a RGB image-based CNN model. By applying the DBSCAN clustering technique to 
the point cloud corresponding to the 2D region proposal, a method of obtaining a 3D region proposal was 
proposed. This allowed for 3D object detection using an RGB image dataset, which has been widely researched, 
while reducing the computation load to a level suitable for use in mobile robots. Furthermore, the 3D object 
detection was integrated into a ROS 2-based mobile platform, which was used to perform pedestrian recognition
and response tasks and elevator button operation tasks. The performance was confirmed through experiments.

## Videos

https://github.com/parkdg44/3d_detection/raw/main/videos/object_detection/object%20detection%201.mkv

https://github.com/parkdg44/3d_detection/raw/main/videos/pedestrian_safe_avoidance/robot%20arm(real)%201.mp4