# Color Identification in Images

![image](https://user-images.githubusercontent.com/93007427/165224772-1423731a-0fce-4586-883c-8c5de3eee5dd.png)


In this project, we identify the colors present in an image using OpenCV and Python. We will create a Python script that identifies the color of the different objects present in the input image.

## Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

## Prerequisites
You need to have Python and OpenCV installed on your system to run this project.

## Installing
Follow the below steps to get started:

1. Clone the repository to your local machine.

2. Open the terminal and navigate to the project directory.

3. Run the following command to install the required libraries:
```
pip install -r requirements.txt
```

4. Once the installation is complete, you can run the project using the following command:
```
python color_detection.py -i <image_path>
```

5. Replace `<image_path>` with the path to the input image.

## Approach
We use OpenCV to read the input image and convert it into the HSV color space. We then define a dictionary of colors with their lower and upper ranges in the HSV color space. For each color in the dictionary, we create a mask by thresholding the image with the lower and upper ranges of the color. We then apply the mask to the original image and extract the objects with that color. Finally, we display the output image with the identified colors.

## Dataset
The dataset used for this project is not publicly available. We use our own images to demonstrate the color identification process.

## Output
The output of the project is an image with the different objects highlighted in their respective colors. The output image is saved in the project directory with the name `output.jpg`.
