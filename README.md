# Toll-Booth-Automation-using-Text-Recognition-from-Images

A project for automating a Toll Booth. Using Tesseract OCR

The idea here is to install camera at toll booths to capture an image of the registration plate of the car as it passes through a toll gate.

The image is then subjected to the following steps
1. Resized to a standard size for all images
2. Converted to 255 bit greyscale
3. Contour mapping used to highlight text area and blur the rest
4. Conversion to black and white
5. Unwanted noises removed
6. Image Inversed

The final image will contain simple black text upon a white background which can be easily identified by the OCR.
The output from the OCR is passed to the database to lookup the type of vehicle and the subsequent toll fee is applied against the number.

Pre - Requisites

1. Python 
2. OpenCV
3. Ubuntu ImageOps Repo
4. SQLite Support

This project was done on a Raspberry Pi. 

Complete details avaible in the Project Report.