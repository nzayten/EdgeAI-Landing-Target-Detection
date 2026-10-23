# Edge AI-Based Real-Time Landing Zone & Target Detection

This repository contains the graduation thesis project focusing on deploying lightweight, quantized deep learning models (YOLOv8n vs. FOMO) on resource-constrained embedded hardware (ESP32-CAM / Raspberry Pi Zero) for autonomous landing target detection.

## Project Objectives
- Train deep learning object detection models on aerial/top-down landing pad datasets.
- Apply post-training quantization (INT8 TFLite) to fit models onto embedded systems.
- Benchmark inference speed (FPS), memory footprint (RAM), and detection accuracy ($mAP_{50}$).
- Provide a C# desktop simulator for real-time telemetry and spatial target visualization.

## Stack & Tools
- **Frameworks:** PyTorch, Ultralytics YOLOv8, TensorFlow Lite, Edge Impulse
- **Hardware:** ESP32-CAM, Raspberry Pi Zero
- **Languages:** Python, C/C++, C# (.NET)
- **Data & Tools:** Roboflow, Google Colab
