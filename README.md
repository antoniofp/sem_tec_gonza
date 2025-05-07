# OCR Image Processing with EasyOCR

This project processes images of license plates to extract text using OpenCV and EasyOCR. The script applies various image processing techniques to enhance the images before performing Optical Character Recognition (OCR).

## Features

- Removes green text from images.
- Resizes and preprocesses images using grayscale conversion, blurring, and adaptive thresholding.
- Detects edges and applies morphological operations to clean up noise.
- Uses EasyOCR to recognize text from processed images.
- Saves processed images and recognized text.

## Requirements

- Python 3.8+
- Required Python libraries:
  - `opencv-python`
  - `numpy`
  - `matplotlib`
  - `easyocr`

