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
# 🎯 Project Objective
The primary objective of this project is to demonstrate how TinyML can enable real-time, offline voice control on embedded hardware without relying on cloud services or internet connectivity. This approach is ideal for applications in:
1.Smart home devices
2.Industrial automation
3.Assistive technologies
4.Wearables
5.IoT devices
# 💡 Project Features
✅ Real-time keyword spotting using deep learning
✅ Lightweight TensorFlow Lite model optimized for embedded devices
✅ Offline — no cloud required
✅ Recognizes 5 keywords + background noise
✅ Portable and power-efficient
# 🧰 Tools & Technologies
* TensorFlow 2.x / TensorFlow Lite
* Python 3.x
* librosa (audio feature extraction)
* Google Speech Commands Dataset V2
* Google Colab (for training)
* Embedded boards (for deployment)
# 🚀 PROJECT PLAN — OFFLINE KEYWORD SPOTTING
# Step 1: Setup & Data
Install Python, TensorFlow, librosa
Download Google Speech Commands Dataset
Pick 5 keywords: "Start", "Stop", "Left", "Right", "Help"
# Step 2: Preprocessing
Convert audio to 16kHz, mono
Extract MFCC or Spectrogram features
# Step 3: Model Training
Build small CNN using TensorFlow/Keras
Train model on 5 keywords + background noise
# Step 4: Model Conversion
Convert to TensorFlow Lite model (.tflite)
# Step 5: Testing
Test model on laptop (simulate embedded)
# Step 6: Deployment (optional)
Deploy on ESP32 / Raspberry Pi
Test real-time audio detection

