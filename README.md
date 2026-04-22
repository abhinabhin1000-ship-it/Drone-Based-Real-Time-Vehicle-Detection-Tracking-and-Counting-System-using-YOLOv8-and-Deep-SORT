# Drone-Based-Real-Time-Vehicle-Detection-Tracking-and-Counting-System-using-YOLOv8-and-Deep-SORT
Real-time vehicle detection, tracking, and counting system using YOLOv8 and Deep SORT on drone footage, designed for smart traffic monitoring and UAV-based surveillance applications.


#  Drone-Based Real-Time Vehicle Detection, Tracking, and Counting System

This project implements a real-time vehicle detection, tracking, and counting system using deep learning and computer vision techniques on aerial (drone) footage.

---

## 🔍 Features
- Detects vehicles (cars, buses, bikes) using YOLOv8
- Tracks objects with unique IDs using Deep SORT
- Counts vehicles using line-crossing logic
- Works on drone/aerial video data

---

##  Tech Stack
- Python
- YOLOv8 (Ultralytics)
- Deep SORT
- OpenCV

---

##  Applications
- Smart Traffic Monitoring
- Drone Surveillance
- Intelligent Transportation Systems

---

## How It Works
1. Video input is processed frame-by-frame
2. YOLOv8 detects vehicles
3. Deep SORT assigns unique IDs for tracking
4. Vehicles are counted when crossing a defined line

---

##  Sample Output
![Output 1](output1.png)
![Output 2](output2.png)

---


## 🛠️ Installation

```bash
pip install ultralytics opencv-python deep-sort-realtime
