# yolo-ocr-vehicle-display
A practical YOLO + OCR workflow for extracting vehicle display information from images.
# YOLO + OCR: Extracting Vehicle Display Information from Images

A practical Computer Vision workflow combining YOLO, OpenCV, ROI extraction, and Tesseract OCR to extract information from a vehicle instrument-cluster image.

## Overview

This project demonstrates how different Computer Vision techniques can be combined to build an end-to-end image recognition workflow.

The workflow includes:

- YOLO object detection
- OpenCV image processing
- Region of Interest (ROI) extraction
- Image preprocessing
- Grayscale conversion and thresholding
- Tesseract OCR
- Text extraction from vehicle display regions

## Workflow

Image
↓
YOLO Detection
↓
Detected Region
↓
Crop
↓
ROI Extraction
↓
Image Preprocessing
↓
Tesseract OCR
↓
Extracted Information

## Example Application

The notebook demonstrates extraction of information such as:

- Ambient temperature
- Time

from a vehicle instrument-cluster image.

## Technologies Used

- Python
- NumPy
- OpenCV
- Ultralytics YOLO
- Tesseract OCR
- PyTesseract
- Jupyter Notebook

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd yolo-ocr-vehicle-display
