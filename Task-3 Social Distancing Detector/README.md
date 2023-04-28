# Social Distancing Detector

![t3](https://user-images.githubusercontent.com/93007427/165225080-35211a70-eb00-4320-b0cc-12a7858d1cbe.jpg)

In the wake of COVID-19 pandemic, social distancing has become an important measure to prevent the spread of the virus. This project aims to build a social distancing detector using OpenCV, TensorFlow and Deep Learning that can monitor whether people are maintaining a safe distance from each other or not.



## Problem Statement
The problem statement is to build a social distancing detector that can:

1. Detect the people in the video frame.

2. Calculate the distance between each pair of people.

3. Determine whether the distance between two people is safe or not.

4. Draw bounding boxes around people who violate social distancing norms.


## Dataset
We can use any video file to test the social distancing detector, or we can also use a webcam to live stream the video. There is no specific dataset required for this project.


## Solution Approach
The social distancing detector can be built in the following steps:

1. Load the video file or use the webcam to live stream the video.

2. Apply object detection to detect people in each frame of the video.

3. Calculate the pairwise distances between all people detected in each frame.

4. Based on the distance, determine whether people are maintaining a safe distance or not.

5. Draw bounding boxes around people who violate social distancing norms.

6. The model for object detection can be trained using any of the popular deep learning frameworks like TensorFlow, Keras or PyTorch. We can use a pre-trained model like YOLO or SSD to detect people in each frame of the video. The distance between each pair of people can be calculated using Euclidean distance or Manhattan distance.


## Tools and Libraries
The following tools and libraries can be used to build the social distancing detector:

1. OpenCV: for reading and processing the video frames.

2. TensorFlow: for object detection and distance calculation.

3. NumPy: for numerical computation and array manipulation.

4. Matplotlib: for plotting the images and results.


## Conclusion
The social distancing detector can be a useful tool in monitoring social distancing in public places and events. It can help to prevent the spread of COVID-19 and other contagious diseases by alerting people who are not maintaining a safe distance. The model can be further improved by incorporating other factors like face mask detection, crowd density and temperature measurement.
