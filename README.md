# 🦺 Custom YOLOv8 Helmet & Safety Vest Detection

## 📌 Project Overview

This project demonstrates how to fine-tune a pretrained YOLOv8 model on a custom Personal Protective Equipment (PPE) dataset.

The model detects:

* 🪖 Helmet
* 🦺 Vest
* 👤 Head
* 🚶 Person

The project was built as part of a Computer Vision learning journey to understand custom object detection using YOLO.

---

## 🚀 Technologies Used

* Python
* YOLOv8 (Ultralytics)
* OpenCV
* Kaggle Notebook
* PyTorch

---

## 📂 Dataset

Dataset Source:

**Hardhat Vest Dataset V3 (Kaggle)**

Classes:

* Helmet
* Vest
* Head
* Person

---

## ⚙️ Training Process

* Started from pretrained **YOLOv8 Nano (yolov8n.pt)**
* Created a custom `data.yaml`
* Trained on the custom dataset
* Saved the best-performing model (`best.pt`)

---

## 📈 Workflow

Dataset

↓

YOLO Dataset Structure

↓

Create data.yaml

↓

Load Pretrained YOLOv8

↓

Fine-tune on Custom Dataset

↓

Save Best Model

↓

Run Predictions

---

## 📁 Project Files

* `train.ipynb` — Training notebook
* `data.yaml` — Dataset configuration
* `custom_yolo_best.pt` — Trained model (optional)
* `images/` — Sample prediction images
* `results/` — Training outputs

---

## 🎯 Skills Demonstrated

* Object Detection
* Transfer Learning
* Custom Dataset Training
* YOLOv8
* Computer Vision
* Deep Learning
* Model Fine-Tuning

---

## 📚 Future Improvements

* Increase dataset size
* Hyperparameter tuning
* Real-time webcam detection
* Deployment using Streamlit or Flask
* Safety monitoring system for construction sites


