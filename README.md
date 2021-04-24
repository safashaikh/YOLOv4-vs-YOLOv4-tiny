# YOLOv4-vs-YOLOv4-tiny
#### About
YOLO is a state of the art object detection model and object detection methods are constantly improving  since  the  introduction  of  convolutional  neural  networks  and  deep  learning. YOLOv4 has come out in 2020 and so has the compressed model YOLOv4-tiny.  It is important to study the performance and tradeoffs between the two models because object detection is in high demand, especially for use on edge devices where a model needs to provide inferences in real-time.  Object detection is used by major companies in many applications such as tailoring recommendations basedon image searches or social media activity, and the realm of applications for this technology are vast. To determine what YOLO model works best,  we compare YOLOv4 vs YOLOv4-tiny, comparing architectures and training and test performance. We want to answer the question of whether the smaller model reduces accuracy and if there is a significant or negligible difference.

#### Reproduce Results
There are two primary jupyter notebooks in the root folder containing all code and instructions to run YOLOv4 and YOLOv4-tiny on a dataset from roboflow. 

The notebook corresponding to YOLOV4 is: Masks_YOLOv4.ipynb 
The notebook corresponding to YOLOV4-tiny is: Masks_YOLOv4_tiny.ipynb 

We have also added a few functions to use your webcam to capture real-time object detection.

#### Dataset
We have used Roboflow's public mask wearing dataset for the purpose of this project: https://public.roboflow.com/object-detection/mask-wearing/1. In case if you want to use the same dataset please create an account on https://roboflow.com/ and get a download link for your dataset and replace it with the dummy link in the Python notebook. The code inherently supports images of any size(courtesy of Spatial Pyramid Pooling and similar techniques), so you can use any image dataset to run training and detection.

#### Sample Results
The videos folder contains videos of YOLOv4 trained on masks and applied to a recent news video covering coronavirus.
