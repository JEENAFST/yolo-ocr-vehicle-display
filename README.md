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
2. Install Python dependencies
pip install numpy opencv-python ultralytics pytesseract matplotlib pillow
3. Install Tesseract OCR

Tesseract OCR must also be installed separately on your system.

After installation, make sure Tesseract is available in your system PATH.

4. Open the notebook
jupyter notebook

Open:

YOLO_OCR_Vehicle_Display_Information.ipynb

Important Note

The YOLO model used in this demonstration is YOLOv8n.

The notebook uses YOLO to detect the larger relevant image region. The individual text fields are then extracted using ROI coordinates, followed by image preprocessing and Tesseract OCR.

For production applications, ROI coordinates and object-detection models should be adapted to the specific camera, display layout, and target application.

Learning Objectives

This notebook is intended as a hands-on learning resource for exploring:

Object detection
Image preprocessing
OCR
Region-based image analysis
Computer Vision pipelines
Automotive and Edge AI applications
Author

Jeena George
Embedded Systems | Modern C++ | Embedded Linux | Edge AI
Future Shock Technologies

License

This project is shared for educational and learning purposes.
