# Object Detection Lab 4
Name: Jiten Bharga  
ID: 202301466 

This project implements R-CNN, Fast R-CNN, Faster R-CNN, and YOLO for object detection.

## Task 1: IoU Explanation
IoU measures overlap between predicted and ground truth bounding boxes.
Formula: Intersection / Union

It is used to evaluate detection accuracy.

## Task 2: Selective Search
Selective Search generates region proposals for object detection.
It reduces the number of regions compared to sliding window.

## Task 3: R-CNN
R-CNN processes each region separately, making it computationally expensive.

## Task 4: Fast R-CNN
Fast R-CNN improves speed by using a shared feature map and ROI pooling.

## Task 5: Faster R-CNN
Faster R-CNN introduces Region Proposal Network (RPN) to generate proposals efficiently.

## Task 6: Non-Maximum Suppression
NMS removes overlapping bounding boxes and keeps the most confident ones.

## Task 7: YOLO
YOLO is a single-stage detector that predicts bounding boxes and class probabilities simultaneously.

## Comparison Analysis
YOLO is fastest, while R-CNN is slowest due to per-region processing.

# Object Detection Lab 4

## Student Details
Name: YOUR NAME  
ID: YOUR ID  

## Description
This project implements multiple object detection algorithms:

- IoU calculation
- Selective Search
- R-CNN
- Fast R-CNN
- Faster R-CNN
- Non-Maximum Suppression (NMS)
- YOLOv8 Training

## Dataset
Custom dataset containing images and XML annotations (Pascal VOC format).

## Requirements.txt
- torch
- torchvision
- opencv-contrib-python
- ultralytics
- matplotlib
- numpy

## Results
- R-CNN: Slowest
- Fast R-CNN: Improved speed
- Faster R-CNN: Efficient proposal generation
- YOLO: Fastest

## Execution
Run the notebook in Google Colab with GPU enabled.

## Repository Structure
- notebook.ipynb → complete implementation
- data.yaml → YOLO config
- sample_outputs → results and graphs
