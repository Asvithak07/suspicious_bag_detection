# 🎒 Suspicious Bag Detection System

A Computer Vision-based security surveillance system that detects unattended or suspicious bags in CCTV footage using YOLOv5 object detection.

The application processes both images and videos, automatically identifying suspicious objects and highlighting them for security monitoring purposes. The system is deployed using Flask and supports real-time detection workflows.

---

## 📌 Overview

Public places such as airports, railway stations, shopping malls, and transportation hubs face security risks from unattended luggage and suspicious objects.

Manual surveillance can be challenging due to the large number of cameras and continuous monitoring requirements.

This project leverages Deep Learning and Computer Vision to automatically detect suspicious bags in CCTV footage, helping security personnel respond more quickly to potential threats.

---

## 🚀 Features

* Suspicious bag detection in CCTV footage
* YOLOv5-based object detection
* Image upload and analysis
* Video upload and analysis
* Bounding box visualization
* Flask-based web application
* Docker support
* CI/CD workflow integration

---

## 🎯 Objectives

* Detect unattended bags from surveillance footage
* Improve security monitoring efficiency
* Reduce manual surveillance workload
* Enable automated threat identification
* Support real-time monitoring environments

---

## 🛠️ Technology Stack

### Programming Language

* Python

### Deep Learning

* PyTorch
* YOLOv5

### Computer Vision

* OpenCV
* Pillow (PIL)

### Web Framework

* Flask

### Deployment

* Docker

### Automation

* GitHub Actions

---

## ⚙️ Project Workflow

1. Upload image or video
2. Preprocess input data
3. Load trained YOLOv5 model
4. Detect suspicious bags
5. Draw bounding boxes
6. Generate processed output
7. Display detection results through Flask application

---

## 🧠 Deep Learning Approach

### YOLOv5 Object Detection

The project uses YOLOv5 (You Only Look Once Version 5), a state-of-the-art real-time object detection model.

Key advantages:

* High detection speed
* Real-time processing capability
* Accurate object localization
* Efficient video analysis

### Detection Pipeline

* Input Image/Video
* Feature Extraction
* Object Detection
* Bounding Box Generation
* Result Visualization

---

## 📂 Project Structure

```text
suspicious_bag_detection/
│
├── .github/
│   └── workflows/
│
├── templates/
│
├── static/
│   ├── uploads/
│   └── processed/
│
├── Dockerfile
├── app.py
├── best.pt
├── requirements.txt
└── README.md
```

---

## ▶️ Installation

### Clone Repository

```bash
git clone https://github.com/Asvithak07/suspicious_bag_detection.git
cd suspicious_bag_detection
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Run Application

```bash
python app.py
```

Open the application in your browser:

```text
http://127.0.0.1:5000
```

---


## 🎥 Supported Inputs

### Images

* JPG
* JPEG
* PNG

### Videos

* MP4
* AVI

---

## 🌍 Real-World Applications

* Airport Security
* Railway Station Surveillance
* Smart City Monitoring
* Public Event Security
* Transportation Hubs
* CCTV-Based Threat Detection

---

## 🚀 Future Improvements

* Real-time CCTV stream integration
* Multi-camera surveillance support
* Alert notification system
* Person-object tracking
* Cloud deployment
* Mobile monitoring dashboard

---

## 👩‍💻 Author

**Asvithaa K**

Computer Vision & Machine Learning Enthusiast

---

## ⭐ Support

If you found this project useful, consider giving it a star on GitHub.
