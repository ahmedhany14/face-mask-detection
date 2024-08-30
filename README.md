<br />
<p align="center">

  <h3 align="center"> face mask detection with YOLOv8 </h3>
</p>

## Table of Contents

- [Table of Contents](#table-of-contents)
- [Description](#description)
- [Model](#model)
- [Dataset](#Dataset)
- [Packages and frameworks i used](#packages-and-frameworks-i-used)
- [Installing packages](#installing-packages)

## Description

This project implements a Face Mask Detection system using the YOLOv8 object detection model. The system can detect whether a person is wearing a face mask, not wearing a mask, or wearing the mask improperly in real-time from video feeds or images.

## Model

This project uses a pre-trained YOLOv8 model for object detection, which has been fine-tuned on a dataset specific to face mask detection. YOLO is a fast and efficient object detection model that works well for real-time applications.

## Dataset

The dataset used in this project from Kaggle, to download it use this [link](https://www.kaggle.com/datasets/andrewmvd/face-mask-detection)

## Packages and frameworks i used

- [cv2](https://docs.opencv.org/4.x/d6/d00/tutorial_py_root.html) For images
- [os](https://docs.python.org/3/library/os.html) For preperaing dirictories
- [xml.etree.ElementTree](https://docs.python.org/3/library/xml.etree.elementtree.html) For prepering xml data
- [ultralytics](https://docs.ultralytics.com/) For YOLOv8 model

