# Vietnamese-ID-Card-Information-Extraction-System
An AI-powered system for detecting and extracting structured information from Vietnamese ID cards using Computer Vision and Optical Character Recognition (OCR).

This project demonstrates a complete pipeline from image preprocessing to text extraction, designed for automation, scalability, and easy integration into real-world applications.

---

## 🚀 Project Overview

Manual data entry from identity documents is time-consuming and prone to human error. This project aims to automate the process by:

* Detecting Vietnamese ID cards from images
* Extracting important personal information automatically
* Converting visual data into structured digital output
* Providing a modular AI pipeline for future improvements

Typical use cases:

* Identity verification systems
* Digital onboarding workflows
* Document processing automation
* Smart data entry solutions

---

## Key Features

* Automatic ID card detection
* Image preprocessing for improved recognition accuracy
* Uses VietOCR to read fields such as ID, name, DOB, address.
* Structured JSON output
* Modular and extensible architecture
* Easy integration into other systems

---

## Technologies Used

* Python
* OpenCV, Pillow
* Yolo
* Numpy
* VietOCR

---

## Getting started
### 1. Clone the repo
```sh
git clone https://github.com/anhchuc094/Vietnamese-ID-Card-Information-Extraction-System.git
cd Vietnamese-ID-Card-Information-Extraction-System
```
### 2. Create virtual env
```sh
python -m venv venv
source venv/bin/activate
```
OR using conda
```sh
conda create -n Vid_card_ocr python=3.10 --y
conda activate Vid_card_ocr
conda install pip          
```
## 3. Install dependencies
```sh
pip install -r requirements.txt
```

## 4. Run pipeline
```sh
python pipeline_v2.py
```
Output directory will be display in resulst/
