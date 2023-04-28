# Optical Character Recognition (OCR)

![image](https://user-images.githubusercontent.com/93007427/165224684-0dd27ca5-120f-4a8f-a162-bb2202c0ee35.png)

This project is a part of the Graduate Rotational Internship Program (GRIP) by The Sparks Foundation. The objective of this task is to perform Optical Character Recognition (OCR) on an image containing English text and to extract the text from the image using Tesseract OCR engine.

## Technologies Used
1. Python 3

2. OpenCV

3. Tesseract OCR Engine


## Installation
1. Clone this repository using `git clone https://github.com/footcricket05/TSF-GRIP-IoT-ComputerVision.git`

2. Install the required libraries using `pip install -r requirements.txt`

3. Download and install Tesseract OCR Engine from https://github.com/UB-Mannheim/tesseract/wiki


## Usage
Place the image containing English text in the `input` directory.
Run the `ocr.py` file using `python ocr.py`.
The extracted text will be displayed on the console and also saved in a text file named `output.txt` in the `output` directory.


## Example
The example.jpg file in the input directory can be used to test the OCR.
Run the `ocr.py` file using python ocr.py.
The extracted text will be displayed on the console and also saved in a text file named `output.txt` in the output directory.


## Note
This project works best with high-resolution images.
The output may not be accurate for images with low resolution or images containing noisy text.


## References
Tesseract OCR Engine: https://github.com/tesseract-ocr/tesseract
OpenCV: https://opencv.org/


## License
This project is licensed under the MIT License - see the LICENSE.md file for details.
