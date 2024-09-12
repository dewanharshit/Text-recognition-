OCR Text Detection Using OpenCV and EasyOCR
This project demonstrates how to detect and annotate text in images using OpenCV, EasyOCR, and matplotlib in Python.

Description-
The script reads an image from the specified path, detects text using EasyOCR, and draws bounding boxes around detected text with the associated confidence score. It then visualizes the results using matplotlib.

Dependencies-
To run this script, the following Python libraries need to be installed:

opencv-python: for reading images and drawing bounding boxes
easyocr: for optical character recognition (OCR)
matplotlib: for displaying the output image
numpy: for array manipulation (required by OpenCV)
You can install the required libraries using the following command:
pip install opencv-python easyocr matplotlib numpy

Usage-
Replace the image_path variable with the path to your image file.

The script processes the image by:

Reading the image using cv2.imread().
Using EasyOCR's Reader class to detect text.
Iterating through the detected text and drawing bounding boxes with the recognized text.
A confidence threshold is used to filter out low-confidence text detections.

The annotated image is displayed using matplotlib.
