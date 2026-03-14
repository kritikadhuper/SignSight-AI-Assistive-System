# SignSight (Work in Progress)

SignSight is an AI-powered assistive vision system designed to improve accessibility for visually and speech-impaired users. The system uses computer vision and machine learning to interpret visual information from a camera and convert it into speech.

The application integrates Indian Sign Language recognition, OCR text reading, object detection, and proximity alerts to help users understand their surroundings in real time.

---

## Project Status

⚠️ This project is currently under development as part of an academic research project.

---

## Features

### Indian Sign Language Recognition
Detects hand gestures using MediaPipe hand landmark detection and a machine learning classifier to translate Indian Sign Language gestures into speech.

### OCR Text Reader
Uses OCR to detect printed text from the camera and convert it into spoken audio.

### Scene Description
Uses YOLOv8 object detection to identify objects in the environment and describe them to the user.

### Proximity Detection
Estimates the distance of objects and warns the user when objects are too close to the camera.

### Real-Time Speech Feedback
Provides audio output describing detected objects and surroundings.

---

## Technologies Used

- Python  
- YOLOv8 (Object Detection)  
- OpenCV  
- MediaPipe (Hand Tracking)  
- EasyOCR (Text Recognition)  
- Machine Learning  

---

## Project Architecture

Camera Input  
↓  
Object Detection (YOLOv8)  
↓  
Distance Estimation  
↓  
Scene Description  
↓  
Text-to-Speech Output  

Additional Modules:

- Sign Language Recognition  
- OCR Text Reader  

---

## Installation
Clone the repository

git clone https://github.com/kritikadhuper/SignSight.git

Install dependencies

pip install -r requirements.txt

Run the application

python app.py
