# 🎯 YOLOv8 Object Detection Lab

> **Lab Assignment** — Deep Learning & Computer Vision | 2025–26

---

## 🏫 Institute & Course Details

* **Institute:** MIT Academy of Engineering, Alandi
* **Department:** Electronics & Telecommunication (E&TC)
* **Course:** Deep Learning / Computer Vision / AI Lab
* **Course Code:** 2311332L
* **Semester:** VI
* **Academic Year:** 2025–26

---

## 👥 Group Details

| Member                   | Roll No      | GitHub                                                 |
| ------------------------ | ------------ | ------------------------------------------------------ |
| Heena Janbandhu (Leader) | 202301070032 | [@Heena-janbandhu](https://github.com/Heena-janbandhu) |
| Sakshi Patil             | 202301070173 | [@Sakshi2004-29](https://github.com/Sakshi2004-29)     |

---

## 🧑‍🏫 Faculty Details

* **Faculty Name:** Dr. Diptee Ghusse
* **Designation:** Assistant Professor

---

## 📋 About This Project

This project implements **object detection**, **instance segmentation**, and **image classification** using **YOLOv8 (Ultralytics)**. The goal is to evaluate multi-task learning performance and understand how different computer vision tasks behave under a unified architecture.

We also explore a **real-world application in Smart Surveillance**, where the model is used for detecting people and monitoring security scenarios in real time.

---

## 🔧 Setup

```bash
pip install ultralytics roboflow supervision matplotlib seaborn pandas
```

---

## 🚀 Run

1. Open `YOLOv8_Object_Detection_Lab.ipynb` in Google Colab
2. Run all cells sequentially
3. Train models and evaluate results
4. View predictions and generated outputs

---

## 📊 Results

| Task           | Model       | mAP@50 | mAP@50-95 |
| -------------- | ----------- | ------ | --------- |
| Detection      | YOLOv8n     | 0.985  | 0.683     |
| Segmentation   | YOLOv8n-seg | 0.90   | 0.65      |
| Classification | YOLOv8n-cls | N/A    | N/A       |

**Key Insight:**

* Detection achieved very high accuracy (mAP@50 = 0.985)
* Segmentation performed slightly lower due to pixel-level complexity
* Classification showed strong performance in simpler tasks

---

## 🌍 Real-World Application: Smart Surveillance System

### 🔹 Problem Statement

Traditional CCTV systems require constant human monitoring, which is inefficient and prone to errors. There is a need for an automated system that can detect suspicious activities and provide real-time alerts.

### 🔹 Solution using YOLOv8

YOLOv8 enables real-time detection of people and objects in surveillance footage. It can identify unusual activity and trigger alerts, improving security and reducing manual effort.

### 🔹 Features

* Real-time person detection
* Automated monitoring
* Scalable for smart cities and campuses
* Edge deployment support

---

## 📁 File Structure

```
.
├── YOLOv8_Object_Detection_Lab.ipynb   # Main notebook
├── README.md
├── requirements.txt
└── results/
    ├── detection_output.png
    ├── segmentation_output.png
    ├── classification_top5.png
    └── training_curves.png
```

---

## 📦 Deployment

* **Edge Devices:** Raspberry Pi / Jetson Nano
* **Cloud:** Model monitoring and storage
* **Dashboard:** Web or mobile interface for alerts

---

## 📜 Undertaking

We hereby declare that this project is our original work and has been completed as part of the academic requirement. All resources and references have been appropriately acknowledged.

---

## 🔗 GitHub Repository

👉 https://github.com/Heena-janbandhu/yolov8-object-detection-lab.git

---

## 📅 Submission Details

* **Lab Date:** 19/03/2026
* **Submission Date:** 25/03/2026

---
