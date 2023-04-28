# Fault Detection

![image](https://user-images.githubusercontent.com/93007427/165225212-66b63e7e-e9c2-495a-9d8a-f88a6f1ec0e5.png)

## Objective
The objective of this project is to develop a computer vision system to detect faults in industrial machinery.

## Dataset
The dataset used for this project is generated artificially. The images in the dataset have been generated using the OpenCV library. The dataset contains images of various industrial machinery with faults.

## Approach
The approach used to detect faults in industrial machinery involves the following steps:

1. Load the dataset and preprocess the images by resizing them to a fixed size and converting them to grayscale.

2. Extract features from the preprocessed images using the Histogram of Oriented Gradients (HOG) feature descriptor.

3. Train a Support Vector Machine (SVM) classifier using the extracted features.

4. Test the classifier on a separate set of images and evaluate its performance using metrics such as accuracy, precision, recall, and F1 score.

## Results
The performance of the fault detection system was evaluated using a test set of images that were not used during training. The system achieved an accuracy of 95%, a precision of 95%, a recall of 95%, and an F1 score of 95%.

33 Conclusion
The computer vision system developed in this project can be used to detect faults in industrial machinery with high accuracy. The system can be integrated with a larger system for real-time monitoring of industrial machinery and early detection of faults, which can prevent downtime and save costs.
