# YOLO7
This repository is about YOLO7 a machine learning, deep learning, AI algorithm that detects things in real time.


**YOLO** (**Y**ou **O**nly **L**ook **O**nce) Model is a Single Stage Detector. It can be applied to thousands of interesting use cases that are the currently used for the most sought after AI jobs. The applications that are most noteworthy include Autonomous Driving, like for the Tesla cars, vehicle detection and intelligent video analytics.

### What can YOLO Do for you?

Let's take a picture on a road and find out what is detected.
![zebra_crossing](https://user-images.githubusercontent.com/20040679/189314947-1df02448-b0ea-4a19-bb03-62eafa5aea3a.jpeg)

![pedestrain](https://user-images.githubusercontent.com/20040679/189334520-0a48dd64-a3c6-4a6d-ab13-92100de9fd27.jpg)

Here's an amusing video 

<!-- [![Watch the video](https://user-images.githubusercontent.com/20040679/189306825-deeae945-f087-4289-b4fe-4892c9a1c431.png)](https://youtu.be/lxLyLIL7OsU) -->

A serious video on a busy road, detecting various objects found on a road scene

[![BusyRoad](https://user-images.githubusercontent.com/20040679/189608757-155a852e-8e8f-4a66-a180-cc5456dd3287.png)](https://youtu.be/POqahsUFefE)




<!-- [![Watch the video](https://user-images.githubusercontent.com/20040679/189310695-f697081b-4c03-4cbb-a265-538e5a635e0d.png)](https://youtu.be/POqahsUFefE) -->

### Advantages

YOLO achieves state-of-the-art results beating other real-time object detection by a large margin.

### Limitations

As compared to other algorithms such as RCNN, YOLO struggles to detect and segregate smaller objects in images that appear in groups. Eg An line of ants.

### Files you can download


### How to use for both image and video
python detect.py --weights yolov7.pt --conf 0.4 --img-size 640 --source.jpg

### Acknowledgements
https://github.com/WongKinYiu/yolov7 

