# License Plate Detection and Recognition using OpenCV & EasyOCR

## Overview
This project implements an automated License Plate Recognition (LPR) system using OpenCV for image processing and EasyOCR for text extraction. The system processes vehicle images to detect and recognize license plate numbers.

## Features
- Image preprocessing (grayscale conversion, noise reduction, edge detection)
- Contour detection to locate license plates
- OCR-based text extraction using EasyOCR
- Visualization of intermediate processing steps

## Installation
To run this project, install the required dependencies:
```bash
pip install opencv-python numpy matplotlib imutils easyocr
```


## Usage
 1. Place the image of a vehicle with a visible license plate in the working directory.
 2. Run the main notebook `main_notebook.ipynb`.
 3. The detected license plate text will be displayed as output.
 
 ## Steps in the Pipeline
 1. **Image Preprocessing:** Convert to grayscale and apply noise reduction.
 2. **Edge Detection:** Identify the edges using the Canny algorithm.
 3. **Contour Detection:** Extract the rectangular region containing the license plate.
 4. **OCR Processing:** Use EasyOCR to extract text from the detected plate.




 ## Example Output
 An example of a detected license plate and recognized text:
