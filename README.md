# 🚗 Vehicle Detection with YOLO11

This project demonstrates real-time **vehicle detection** using a custom YOLO-based model, referred to as **YOLO11** (built on top of YOLOv8). The model is trained on a vehicle detection dataset to accurately identify cars and other vehicles in images and video streams.

[![Kaggle](https://img.shields.io/badge/Kaggle-Notebook-blue?logo=kaggle)](https://www.kaggle.com/code/amirhoseinmousavian/vehicle-detection-yolo11)

---

## 📁 Project Structure

- `vehicle-detection-yolo11.ipynb`: The full Jupyter notebook with:
  - Data preprocessing
  - YOLO training pipeline
  - Evaluation metrics
  - Visualization of predictions
- `runs/detect/`: Model predictions (images with bounding boxes)
- `best.pt`: Trained YOLO11 model weights

---

## 🧠 Model Summary

- **Architecture**: YOLO11 (Ultralytics)
- **Backbone**: Custom-trained on vehicle dataset
- **Task**: Object detection
- **Classes**: Vehicles (cars, buses, etc.)

---

## 📊 Evaluation

| Metric        | Value  |
|---------------|--------|
| Precision     | ~0.98  |
| Recall        | ~0.97  |
| mAP@0.5       | ~0.96  |
| Inference FPS | Real-time |

*Note: Actual values may vary depending on dataset splits.*

---

## 🚀 Getting Started

### 1. Clone the repo
```bash
git clone https://github.com/your-username/vehicle-detection-yolo11.git
cd vehicle-detection-yolo11

📦 Dataset

The dataset includes images of vehicles with bounding box annotations.

You can download or explore it via [Kaggle](https://www.kaggle.com/datasets/alkanerturan/vehicledetection)
    
