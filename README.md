# object detection for safer self driving
object detection for safer self driving with YOLOv4, YOLOv8

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

## Dataset
class      | training labels   | testing labels
:---------:|------------------:|---------------:
car        | 101,314 labels    | 22,000 labels
truck      | 6,313 labels      | 1,009 labels
pedestrian | 10,637 labels     | 4,903 labels
bicyclist  | 1,442 labels      | 234 labels
light      | 12,700 labels     | 4,553 labels
pothole    | 4,443 labels      | 314 labels
**total**  | **136,849 labels**| **33,013 labels**

- car ~ light dataset: https://www.kaggle.com/alincijov/self-driving-cars
- pothole dataset: https://data.mendeley.com/datasets/5ty2wb6gvg/1

## Weight
YOLOv8      | YOLOv4                
:---------:|------------------:
[yolo-v8_final.pt](https://drive.google.com/file/d/1YpE9QYyYh0E6tqAeeZDBLqAAgs5iz1uF/view?usp=sharing) | [yolo-obj_final.weights](https://drive.google.com/file/d/1jtZO5RLuvYka0aUJkGpRMrK-DY1QNP7i/view?usp=sharing)    


## Result


## References
- https://github.com/AlexeyAB/darknet
- https://github.com/dec880126/Self-driving-with-YOLO
- https://github.com/adnankarol/Yolov4_Road_Damage_Detection
