# 🏗️ Blueprint Computer Vision Pipeline

This project implements a complete computer vision pipeline tailored for blueprint documents, construction site photos, and technical diagrams. It processes images, runs object detection models (such as YOLOv8), and exposes results through a RESTful API using FastAPI.

---

## ✅ Features

- 📷 **Image preprocessing**: resizing, grayscale conversion, histogram equalization
- 🤖 **Object detection** with modern models (YOLOv8 by Ultralytics)
- 🧪 **Postprocessing**: extract class labels, bounding boxes, and confidence scores in structured JSON
- 🔌 **REST API** to send images and receive detection results
- 🧱 **Modular design**, easy to extend with segmentation, OCR, or PDF parsing

---

## 📁 Project Structure
