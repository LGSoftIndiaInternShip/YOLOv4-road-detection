# object detection for safer self driving
object detection for safer self driving with YOLOv4, YOLOv8

## Table of Contents
* [Environment](#environment)
* [Classes](#classes)
* [Datasets](#datasets)
* [Weights](#weights)
* [Results](#results)
* [References](#references)

## Environment
- VM: Google Colaboratory
- GPU: Tesla T4
- CUDA: 12.0

## Classes
1. car
2. truck
3. pedestrian
4. bicyclist
5. light
6. pothole

## Datasets
- car ~ light dataset: https://www.kaggle.com/alincijov/self-driving-cars
- pothole dataset: https://data.mendeley.com/datasets/5ty2wb6gvg/1

**[YOLOv4]**
class      | labels for training  | labels for validation
:---------:|---------------------:|----------------:
car        | 101,314 labels       | 22,000 labels
truck      | 6,313 labels         | 1,009 labels
pedestrian | 10,637 labels        | 4,903 labels
bicyclist  | 1,442 labels         | 234 labels
light      | 12,700 labels        | 4,553 labels
pothole    | 4,443 labels         | 314 labels
**total**  | **136,849 labels**   | **33,013 labels**

**[YOLOv8]**
class      | labels for training  | labels for validation
:---------:|---------------------:|----------------:
car        | 36,910 labels       | 9,025 labels
truck      | 3,296 labels         | 874 labels
pedestrian | 6,951 labels        | 1,640 labels
bicyclist  | 804 labels         | 151 labels
light      | 6,979 labels        | 1,748 labels
pothole    | 8,187 labels         | 2,000 labels
**total**  | **63,127 labels**   | **15,438 labels**

## Weights
YOLOv4 | YOLOv8
:-----:|:------:
[yolov4_best.weights](https://drive.google.com/file/d/1jtZO5RLuvYka0aUJkGpRMrK-DY1QNP7i/view?usp=sharing) | [yolov8_best.pt](https://drive.google.com/file/d/1YpE9QYyYh0E6tqAeeZDBLqAAgs5iz1uF/view?usp=sharing)

## Results
**[Summary]**

![mAP](https://github.com/LGSoftIndiaInternShip/object-detection-for-safer-self-driving/assets/96642871/bd33d94a-d249-42b0-944e-f2b892a610ba)
![AP of each classes](https://github.com/LGSoftIndiaInternShip/object-detection-for-safer-self-driving/assets/96642871/31dc424d-d8fe-4984-8f7c-d045f0bdb327)

**[YOLOv4]**

<img src="https://github.com/LGSoftIndiaInternShip/object-detection-for-safer-self-driving/assets/96642871/39819cb0-e0dd-418b-8f87-3769e1a9cbc6" width="400" height="400"/>

## References
- https://github.com/AlexeyAB/darknet
- https://github.com/dec880126/Self-driving-with-YOLO
- https://github.com/adnankarol/Yolov4_Road_Damage_Detection
