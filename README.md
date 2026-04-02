# Automatic Number Plate Recognition (ANPR)

## Overview

This project implements an Automatic Number Plate Recognition (ANPR) system that allows users to upload an image and automatically detect and extract the vehicle's license plate number.

The system uses YOLOv8 for license plate detection, OpenCV for image processing, and EasyOCR/Tesseract for text extraction.

---

## Workflow

1. Upload an input image
2. Detect license plate using YOLOv8
3. Crop the detected region using OpenCV
4. Apply OCR to extract text
5. Display the detected number plate

---

## Tech Stack

* YOLOv8 (Ultralytics) – Object Detection
* OpenCV – Image Processing
* EasyOCR / Tesseract – Optical Character Recognition
* Python – Programming Language
* Roboflow – Dataset Management

---

## Dataset

* Source: Roboflow
* Project: License Plate Detector
* Format: YOLOv8

---

## Installation

```bash
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
pip install -r requirements.txt
```

---

## Usage

```bash
python main.py
```

Make sure to:

* Place your test image in the project folder
* Update the image path in the script

---

## Features

* Detects number plates in images
* Supports multiple vehicles in one image
* Uses OCR for automatic text extraction
* Simple and modular pipeline

---

## Notes

* Ensure your YOLO model (best.pt) is available in the project directory
* Image preprocessing improves OCR accuracy

---

## Future Improvements

* Real-time detection using webcam
* Web interface for image upload
* Model optimization for higher accuracy
* Deployment as a web application

---

## Author

Susmitha VG

---

## Acknowledgements

Ultralytics YOLOv8
OpenCV
EasyOCR
Roboflow
