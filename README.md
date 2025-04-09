

## 🧠 About YOLOv8, TensorRT, and Streamlit

### 🧩 What is YOLOv8?

[YOLOv8](https://github.com/ultralytics/ultralytics) is the latest object detection model in the YOLO (You Only Look Once) series, developed by **Ultralytics**. It is designed for **real-time performance** and supports multiple tasks including:

- 🎯 Object detection
- 🧠 Classification
- 📏 Segmentation
- 🕺 Pose estimation

YOLOv8 is built with **PyTorch** and is easy to use, train, and deploy. It also supports exporting to multiple formats like **ONNX**, **TensorRT**, and **CoreML**.

---

### ⚡ What is TensorRT?

**TensorRT** is a high-performance deep learning inference SDK developed by **NVIDIA**, used to accelerate model performance on **NVIDIA GPUs**.

**Key Benefits:**
- 🚀 Super fast inference
- 📉 Lower latency and memory footprint
- ✅ Support for FP16 and INT8 precision
- 🔁 Layer fusion and optimized execution plans

TensorRT is ideal for deploying YOLOv8 models on devices like **Jetson Nano**, **Xavier**, and **NVIDIA RTX/GeForce cards**.

---

### 🖥️ What is Streamlit?

[Streamlit](https://streamlit.io/) is an open-source Python framework for building interactive web apps for data science and machine learning projects.

**Why use Streamlit in this project?**
- ⚡ Fast to build, easy to run
- 🎥 Can display real-time webcam feeds
- 🧪 Great for prototyping and demos
- 🌐 Runs entirely in the browser

---

## 🤖 YOLOv8 + TensorRT + Streamlit = Ultimate Real-Time Detection

This project combines the power of:
- **YOLOv8** for accurate object detection
- **TensorRT** for GPU-accelerated inference
- **Streamlit** for a live web interface with webcam support

Together, they create a fast, interactive app capable of detecting objects in real time directly from your webcam!

---

## 🛠️ How to Export and Optimize Your Model

### ✅ Step 1: Export YOLOv8 to ONNX
```bash
yolo export model=yolov8n.pt format=onnx
