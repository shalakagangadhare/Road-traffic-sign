# Road-traffic-sign

# 🚦 Road Traffic Signs - Bounding Box Predictions

## 📘 Project Title: Traffic Light Sign Detection and Classification using Deep Learning

---

## 🎯 Objective

Develop a deep learning-based system that can:
- Detect traffic light signs in street images or videos
- Localize them with bounding boxes
- Classify their color state: **Red**, **Yellow**, or **Green**

This is essential for:
- Autonomous vehicles
- Smart city traffic systems
- Traffic law enforcement

---

## 📌 Key Features

✅ Detect traffic lights in real-world urban scenarios  
✅ Classify the state of each detected light: **Red**, **Yellow**, or **Green**  
✅ Draw bounding boxes around detected lights  
✅ Robust to diverse lighting and weather conditions

---

## 📊 Dataset Details (Example)

- **Total Images**: 1000+
- **Content**: Streets and intersections with visible traffic lights
- **Annotations**:
  - `Class`: Red / Yellow / Green
  - `Bounding Box`: Coordinates (xmin, ymin, xmax, ymax)
  - **Format**: XML (Pascal VOC format)

---

## 🔄 Workflow

### 1. Data Preprocessing
- Resize and normalize images
- Apply data augmentation:
  - Horizontal flip
  - Brightness/contrast adjustment
  - Random crop

### 2. Model Training
- Loss function: Combined classification + bounding box regression
- Model architecture: CNN / YOLO / SSD (customizable)
- Framework: TensorFlow / PyTorch

### 3. Prediction & Inference
- **Input**: Raw street image
- **Output**: Bounding boxes with classified traffic light states

---

## ✅ Applications

- 🚗 Autonomous Vehicles
- 📉 Traffic Flow Monitoring
- 🚦 Smart Signal Automation
- 🛡️ Accident Prevention Systems
- 🚶‍♂️ Pedestrian Safety Technologies



