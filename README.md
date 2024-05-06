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

<details>
<summary>Object Detection</summary>

<!-- summary 아래 한칸 공백 두어야함 -->
https://github.com/parkdg44/3d_detection/assets/61260130/409f585b-9788-4537-84c0-c5749f07014b

https://github.com/parkdg44/3d_detection/assets/61260130/50180a18-a527-4626-955d-aaa3633b6baf
</details>

<details>
<summary>Pedestrian-safe avoidance</summary>

<!-- summary 아래 한칸 공백 두어야함 -->


https://github.com/parkdg44/3d_detection/assets/61260130/08204c94-6982-49ec-9a11-b615adc2ca88

https://github.com/parkdg44/3d_detection/assets/61260130/cd737350-ffe8-4e48-808e-2efb480283cf
</details>

<details>
<summary>Autonomous elevator button operation</summary>

<!-- summary 아래 한칸 공백 두어야함 -->


https://github.com/parkdg44/3d_detection/assets/61260130/37938fb2-81fe-443c-a0be-e51d476cf8dd

https://github.com/parkdg44/3d_detection/assets/61260130/e58d5549-ceab-4ce8-8f7f-45f326b3aa16

https://github.com/parkdg44/3d_detection/assets/61260130/d5e5ef69-7c03-44fd-88d3-88c745c0a98b

https://github.com/parkdg44/3d_detection/assets/61260130/7d55d2f7-79a1-4e37-b029-21386eea6624
</details>
