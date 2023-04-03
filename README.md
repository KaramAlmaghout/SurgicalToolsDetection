# SurgicalToolsDetection


AML Course - Course Project


## Introduction

In this project, we aim to train YOLOv8 model to detect surgical tools, which can be further used to detect and track these tools during operations. 

Applications of this project:

  1. Robotizing surgical operation.
  2. Tracking tools during tele surgical operations.
  3. Tracking tools for mentoring and assessment purposes.

## Dataset

[m2cai16-tool-locations](http://ai.stanford.edu/~syyeung/resources/m2cai16-tool-locations.zip)

The m2cai16-tool-locations dataset has 2,532 frames from the first 10 out of 15 videos in the m2cai16-tool dataset. The dataset has 7 different types of surgical instruments.

![image](https://user-images.githubusercontent.com/94979970/229603941-36d19b1d-54c3-42aa-bf73-78c689fab954.png)


### Dataset Annotation:

The images are annotated using Roboflow platform

![image](https://user-images.githubusercontent.com/94979970/229608878-56e8fa82-b25f-4a2d-826f-ec9cbd2d6f23.png)


## YOLOv8 

YOLOv8, developed by Ultralytics, is a cutting-edge, state-of-the-art (SOTA) model that builds upon the success of previous YOLO versions and introduces new features and improvements to further boost performance and flexibility. YOLOv8 is designed to be fast, accurate, and easy to use, making it an excellent choice for a wide range of object detection, image segmentation and image classification tasks.

Aamong other YOLO versions, YOLOv8 shows better performance in the speed and accuracy manner

![image](https://user-images.githubusercontent.com/94979970/229612017-d943a29f-1de9-4a91-b548-22d7f553d521.png)

Tables 1 and 2 show comparison among YOLOv8 distributions in detection and segmentation, respectively.

Table 1 ![image](https://user-images.githubusercontent.com/94979970/229612692-dbb59e3f-f3fc-464e-8919-70e999985f15.png)


Table 2 ![image](https://user-images.githubusercontent.com/94979970/229612875-8e8c0c7f-a853-41ad-b428-8f46866a6768.png)





