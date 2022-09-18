# YOLO-object-detection-with-OpenCV
Object detection using YOLO object detector

### Detect objects  video streams using Deep Learning, OpenCV, and Python.

I’ll be using YOLOv3 in this project, in particular, YOLO trained on the COCO dataset.

The COCO dataset consists of 80 labels, including, but not limited to:

- People
- Bicycles
- Cars and trucks
- Airplanes
- Stop signs and fire hydrants
- Animals, including cats, dogs, birds, horses, cows, and sheep, to name a few

- But here extensively we use it to identify animals.


## YOLO object detection in images

## Installation

- `pip install numpy`
- `pip install opencv-python`



## YOLO object detection in video streams

## Installation

- `pip install numpy`
- `pip install opencv-python`

## To Run the project

- `python yolo_video.py --input videos/animals-2.mp4 --output output/animal2_output.avi --yolo yolo-coco`

## Aproach
For this project we have used YOLO(You only Look Once) method.It is the algorithm how the code is going to detect objects in a image.
Here we used pre-trained YOLO models and weights and openCV to predict animals and objects.
The YOLO algorithm consists of various variants. Some of the common ones include tiny YOLO and YOLOv3.Here we use YOLOv3 algorithm to implement the task.
## Limitation:
### Arguably the largest limitation and drawback of the YOLO object detector is that:

- It does not always handle small objects well
- It especially does not handle objects grouped close together



