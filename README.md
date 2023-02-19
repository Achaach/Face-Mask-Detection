# Face-Mask-Detection
## Overview
The aim of this project is to develop a system that can detect whether people are wearing masks or not using computer vision and machine learning techniques. The system will use a camera or a video feed to capture images of people's faces and determine if they are wearing masks or not. The objective is to help organizations and governments enforce mask-wearing protocols in public spaces, reduce the spread of COVID-19, and protect public health.
### Introduction to SSD:
Single Shot Multibox Detector (SSD) is an object detection algorithm that uses a deep convolutional neural network (CNN) to identify objects in an image. It was introduced in a 2016 paper by Liu et al. The key innovation of SSD is its ability to perform object detection in real-time while achieving high accuracy.
One advantage of SSD is that it can handle objects of different sizes and aspect ratios by generating default bounding boxes at multiple scales and aspect ratios. Additionally, SSD is an end-to-end system that can be trained on a large dataset using a simple loss function that combines classification and localization losses.

Overall, SSD is a powerful object detection algorithm that has been widely adopted in computer vision applications such as autonomous driving, surveillance, and robotics.

## Methodology
The system will use machine learning algorithm and SSD which is achieved by using multiple boxes or filters with different sizes, and aspect ratio for object detection, to analyze the images and detect whether people are wearing masks or not. 

The model will be trained on the labeled dataset, and the accuracy of the model will be evaluated using the test dataset.

## Data
Face Mask Detection Dataset: https://www.kaggle.com/datasets/wobotintelligence/face-mask-detection-dataset

Caffe Face Detector (OpenCV Pre-trained Model): https://www.kaggle.com/datasets/sambitmukherjee/caffe-face-detector-opencv-pretrained-model

## Steps
1. Extract the face data for training.
2. Train the classifier to classify faces into mask or non-mask labels.
3. Detect Faces in testing data using SSD Face Detector.
4. By using the trained classifier, classify the detected faces.


## Results
The system will be able to accurately detect whether people are wearing medical masks or not. 
### Accuracy:
![accuracy](https://user-images.githubusercontent.com/90078254/219982310-6aa11a31-57de-4d29-ab7f-4e51561883f7.png)
### Loss:
![loss](https://user-images.githubusercontent.com/90078254/219982315-8af9d3e1-fbdb-43c3-9e18-bcf105b2b143.png)

### Visulization
<img width="765" alt="Screen Shot 2023-02-19 at 6 46 46 PM" src="https://user-images.githubusercontent.com/90078254/219982783-3db141e0-3722-4885-88ac-8a81c879a227.png">
Note that for time saving, here we took our epochs as 20. For higher accuracy, we can make the epochs to be larger.
