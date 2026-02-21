# 🔫 Real-Time Weapon Detection using YOLOv8

## 📌 Overview
This project presents a real-time weapon detection and alert system built using the YOLOv8 object detection model. The system processes live video streams from a camera or video file and performs frame-wise detection to identify potential weapon objects.

Detected objects are filtered using confidence thresholds and stability checks to reduce false positives. When a high-confidence weapon detection occurs, the system triggers both visual alerts and audible alarms for immediate threat awareness.

---

## 🚀 Features

✅ Real-time video stream processing  
✅ YOLOv8-based object detection  
✅ Confidence-based filtering  
✅ Noise & small-object rejection  
✅ Temporal stability mechanism  
✅ Visual bounding box alerts  
✅ Audible alarm system  
✅ Pop-up warning notifications  

---

## 🧠 Detection Strategy

The system improves reliability using:

- **Detection Confidence Threshold** → Controls object detection sensitivity  
- **Alert Confidence Threshold** → Triggers alarms only for high-confidence threats  
- **Minimum Area Filtering** → Removes small false detections (pens, noise, etc.)  
- **Temporal Stability Check** → Prevents flickering alerts  

---

## 🛠 Technologies Used

- **Python**
- **YOLOv8 (Ultralytics)**
- **OpenCV**
- **Tkinter (GUI Alerts)**
- **Winsound (Alarm System)**
- **Roboflow (Dataset Handling)**

---

## 📷 System Modes

The project supports:

✔ Video file detection  
✔ Live webcam detection  
✔ Alert & alarm-enabled detection  

---
