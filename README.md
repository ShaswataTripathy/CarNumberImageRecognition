# CarNumberImageRecognition
Python script that can be used for recognizing number plates in traffic stop cameras, along with image enhancement capabilities. This script uses OpenCV for image processing, Tesseract OCR for text recognition, and includes functions for enhancing images.

Instructions to Run the Code
Install Required Libraries: Make sure you have the necessary libraries installed. You can install them using pip:

 copy
bash

pip install opencv-python pytesseract numpy
Download Tesseract: Install Tesseract OCR from here. Set the Tesseract executable path in the script where indicated.

Haarcascade XML File: Download the Haar cascade for number plate detection (e.g., haarcascade_russian_plate_number.xml) and place it in the same directory as your script. You can find it here.

Run the Script: Update the image_path variable in the script with the path to your test image, then run:

 copy
bash

python traffic_stop_camera.py
Note:
This implementation includes basic image enhancement techniques like histogram equalization and adaptive thresholding to improve OCR accuracy.
Depending on the quality of the input images, further tuning of the image preprocessing steps may be required for optimal performance.
