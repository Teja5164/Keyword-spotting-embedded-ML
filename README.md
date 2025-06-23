# Keyword-spotting-embedded-ML

🚀 PROJECT PLAN — OFFLINE KEYWORD SPOTTING
Step 1: Setup & Data

Install Python, TensorFlow, librosa

Download Google Speech Commands Dataset

Pick 5 keywords: "Start", "Stop", "Left", "Right", "Help"

Step 2: Preprocessing

Convert audio to 16kHz, mono

Extract MFCC or Spectrogram features

Step 3: Model Training

Build small CNN using TensorFlow/Keras

Train model on 5 keywords + background noise

Step 4: Model Conversion

Convert to TensorFlow Lite model (.tflite)

Step 5: Testing

Test model on laptop (simulate embedded)

Step 6: Deployment (optional)

Deploy on ESP32 / Raspberry Pi

Test real-time audio detection
