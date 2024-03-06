# Automatic Number Plate Recognition (ANPR) with Easy OCR and OpenCV

This project implements Automatic Number Plate Recognition (ANPR) using Easy OCR and OpenCV in Python. ANPR is a system used to automatically recognize and read vehicle license plates. 

## Overview

The implementation of ANPR is divided into several small steps:

1. **Install and Import Dependencies**: Installation of required libraries and importing necessary modules.
2. **Reading an Image**: Reading an image to be used for testing the ANPR system.
3. **Apply Filter and Find Edges For Localization**: Filtering to remove noise and edge detection to find edges within the image.
4. **Find the Contours and Apply Mask**: Finding contours and applying a mask to isolate the number plate region.
5. **Use Easy OCR to Read Text**: Employing Easy OCR to extract text from the number plate region.
6. **Render Results**: Overlaying the extracted text on the original image.


