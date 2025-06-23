# Keyword-spotting-embedded-ML


This project implements a complete offline Keyword Spotting (KWS) system that can recognize specific spoken keywords in real-time on embedded devices with limited compute power. The goal is to build a small, efficient, and low-power machine learning model that listens to audio streams and detects predefined keywords such as:
"start"
"stop"
"left"
"right"
"help"
The model is trained on the Google Speech Commands Dataset V2, preprocessed using MFCC (Mel Frequency Cepstral Coefficients) feature extraction, and optimized using TensorFlow Lite for deployment on embedded platforms such as:
ESP32
Raspberry Pi
STM32 microcontrollers
PC / Laptop (for testing & simulation)
## 🎯 Project Objective
The primary objective of this project is to demonstrate how TinyML can enable real-time, offline voice control on embedded hardware without relying on cloud services or internet connectivity. This approach is ideal for applications in:
1.Smart home devices
2.Industrial automation
3.Assistive technologies
4.Wearables
5.IoT devices
## Project Features
✅ Real-time keyword spotting using deep learning
✅ Lightweight TensorFlow Lite model optimized for embedded devices
✅ Offline — no cloud required
✅ Recognizes 5 keywords + background noise
✅ Portable and power-efficient
## Tools & Technologies
* TensorFlow 2.x / TensorFlow Lite
* Python 3.x
* librosa (audio feature extraction)
* Google Speech Commands Dataset V2
* Google Colab (for training)
* Embedded boards (for deployment)
## PROJECT PLAN — OFFLINE KEYWORD SPOTTING
## Step 1: Setup & Data
Install Python, TensorFlow, librosa
Download Google Speech Commands Dataset
Pick 5 keywords: "Start", "Stop", "Left", "Right", "Help"
## Step 2: Preprocessing
Convert audio to 16kHz, mono
Extract MFCC or Spectrogram features
## Step 3: Model Training
Build small CNN using TensorFlow/Keras
Train model on 5 keywords + background noise
## Step 4: Model Conversion
Convert to TensorFlow Lite model (.tflite)
## Step 5: Testing
Test model on laptop (simulate embedded)
## Step 6: Deployment (optional)
Deploy on ESP32 / Raspberry Pi
*Test real-time audio detection

##  Conclusion
This project showcases how TinyML and embedded keyword spotting can enable real-time, offline voice-controlled interfaces on low-power hardware. By using lightweight neural networks and optimized TensorFlow Lite models, we can deploy smart audio recognition on microcontrollers without the need for cloud services — ensuring privacy, responsiveness, and energy efficiency.

This approach opens the door for creating intelligent IoT devices, industrial automation systems, and smart consumer products that can interpret voice commands even in constrained environments. The project also serves as an excellent example of applying embedded machine learning techniques in practical, real-world scenarios.

## Future Work
1.Add more keywords and increase vocabulary
2.Improve model accuracy using advanced architectures (e.g., depthwise separable CNNs)
3.Implement wake-word + full command pipeline (multi-stage detection)
4.Add support for continuous streaming audio (real-time inference)
5.Deploy on ultra-low power microcontrollers (e.g., STM32, Cortex-M)
6.Add second-stage NLP pipeline for more advanced voice interaction
7.Optimize model using quantization for smaller memory footprint
8.Benchmark model latency and performance on various hardware
9.Integrate with hardware actions (LED, motor control, home automation)
