# Face Mask Detection

![t4](https://user-images.githubusercontent.com/93007427/165225026-2321a551-9a1d-4af9-b226-d6b2aa81ffbe.jpg)

This project is aimed to detect whether a person is wearing a face mask or not in real-time using Computer Vision and Deep Learning techniques.

## Introduction
As the COVID-19 pandemic swept across the world, wearing a face mask became one of the most effective ways to stop the spread of the virus. However, not everyone follows this guideline, which can lead to an increase in the number of cases. Therefore, developing a system that can detect whether people are wearing masks or not can be a helpful tool for public safety.

The goal of this project is to build a real-time face mask detection system that can detect whether a person is wearing a mask or not. The system is built using Convolutional Neural Networks (CNN) to identify whether a person in a video stream is wearing a face mask or not.

## Dataset
The dataset used for this project is publicly available and was collected by Prajna Bhandary. It contains images of people with and without masks. The dataset contains a total of 1376 images, out of which 690 images contain people wearing masks, and the other 686 images contain people without masks. The dataset has been split into training and testing sets, with 80% of the data used for training and the remaining 20% used for testing.

## Technologies
1. Python 3.8

2. OpenCV

3. TensorFlow

4. Keras

5. NumPy


## Methodology
The face mask detection system consists of three steps: face detection, face extraction, and mask detection. First, the system detects the faces in the video stream using the Haar Cascade Classifier. Second, the detected faces are extracted from the video stream and passed through a pre-trained CNN to identify whether the person is wearing a mask or not. The pre-trained CNN used in this project is based on the MobileNetV2 architecture. Finally, the system overlays a bounding box and label over the detected faces to indicate whether the person is wearing a mask or not.

## Results
The face mask detection system was able to successfully identify whether a person is wearing a mask or not with an accuracy of 99.07% on the test set. The system was able to detect faces in real-time and accurately classify them as either wearing a mask or not. 
