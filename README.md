# Object Detection and Tracking
OBJECT DETECTION is a computer vision technique for locating instances of objects in images or videos. 
Given an image or a video, the goal of object detection is to recognize and locate objects of interest.

There is a variety of techniques to perform object detection. Popular approaches are deep learning–based approaches using convolutional neural networks (CNNs), such as R-CNN Model Family (R-CNN, Fast R-CNN, Faster R-CNN) and YOLO Model Family (YOLO, YOLOv2 or YOLO9000 and YOLOv3).

OBJECT TRACKING is the task of taking an initial set of object detections, creating a unique ID for each of the initial detections, and then tracking each of the objects as they move around frames in a video, maintaining the ID assignment.

![alt text](https://github.com/buropas/Object_Detection/blob/main/Obj_detect.png?raw=true)



## Folder content:
- Image Object Detection using YOLOv3 with pre-trained weights (Notebook)
- Video Object Detection using YOLOv3 with pre-trained weights (Notebook)
- Video Object Detection and Tracking using YOLOv3 with pre-trained weights (Notebook)
- yolov3.cfg (neural network model configuration file)
- coco.names (file with 80 object classes that the model will be able to detect)
- test.mp4 (test video to perform object detection)
- output.avi (output video from object detection task)
- output_track.avi (output video from object detection and tracking tasks)
- obj_detect.png (output image from object detection task)
- centroidtracker.py (file needed to perform object tracking)

## Technologies   
Object Detection Algorithm: YOLOv3   
Object Tracking Algorithm: Centroid Tracker      
Libraries: OpenCV, Numpy, Matplotlib   
Language: Python
