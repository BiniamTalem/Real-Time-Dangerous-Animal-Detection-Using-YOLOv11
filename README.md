# Real-Time Dangerous Animal Detection Using YOLOv11

This project presents a **real-time dangerous animal detection system**
designed to improve public safety in environments such as parks,
recreational areas, and other high-traffic public spaces.

Using **YOLOv11 deep learning models**, **big data processing with PySpark**,
and **advanced data augmentation techniques**, the system detects
dangerous animals from surveillance camera images and enables
early warning mechanisms to reduce risk to humans.

---
## Pipeline Overview

Data collection, preprocessing, filtering, and augmentation were performed
in the notebooks located in the `notebooks/` directory.

The main YOLOv11 training and detection pipeline is implemented in
`dangerous_animal_detection_yolov11.ipynb`.

---

## 📓 Notebooks Structure

- `dangerous_animal_detection_yolov11.ipynb` – Main YOLOv11 training and real-time detection pipeline
- `notebooks/` – Supporting notebooks for data collection, preprocessing, PySpark-based filtering, and data augmentation

---
## 🚨 Problem Statement
As urban areas expand and human activity increasingly overlaps with wildlife habitats,
dangerous animals such as **snakes, scorpions, lions, and other predators**
pose potential threats to public safety.

Traditional monitoring systems are often reactive and inefficient.
This project addresses the need for a **fast, accurate, and automated
real-time detection system** capable of operating in public environments.

---

## 🧠 Solution Overview
- Real-time object detection using **YOLOv11**
- Custom-labeled multi-class dangerous animal dataset
- Big data image processing with **PySpark**
- Advanced data augmentation to improve model robustness
- Scalable pipeline suitable for camera-based surveillance systems

---

## 📊 Dataset
- Custom image dataset containing dangerous animals:
  - Snake
  - Wild Boar
  - Lion
  - Leopard
  - Fox
  - Hyena
  - Elephant
  - Wild Dog
- Dataset includes real and augmented images
- Images labeled using **YOLO format**

---

## 🛠️ Technologies & Tools
- **Python**
- **YOLOv11 (Ultralytics)**
- PyTorch
- OpenCV
- PySpark
- Label Studio
- NumPy, Pandas
- Jupyter Notebook

---

## 🔄 Methodology

### Data Preparation
- Image collection from multiple sources
- Manual annotation using Label Studio
- Image preprocessing and resizing
- Data augmentation:
  - Rotation
  - Blurring
  - Brightness & contrast adjustment
  - Motion blur
- Big data image processing using PySpark

---

### Model Training
- YOLOv11 object detection model
- Multi-class detection of dangerous animals
- Training on augmented and real-world data
- Evaluation using detection accuracy and inference speed

---

### Real-Time Detection
- Optimized inference for camera-based input
- Capable of detecting animals in real-time frames
- Designed for integration with surveillance and alert systems

---

## 📈 Key Outcomes
- High detection accuracy for multiple dangerous animal classes
- Robust performance under different lighting and motion conditions
- Scalable architecture suitable for real-time public safety systems
- Demonstrates effective integration of **deep learning and big data**

---

## 🎓 Context
Originally developed as part of an **MSc in Data Analytics**.
This repository contains a **cleaned and refactored version**
prepared for professional portfolio presentation.

---

## 🚀 Future Improvements
- Audio-based warning system integration
- Edge deployment (Jetson / Raspberry Pi)
- Video stream optimization
- Expansion to additional animal classes

---
