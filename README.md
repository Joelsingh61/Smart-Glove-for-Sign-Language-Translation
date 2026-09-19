# 🧤 Smart Glove — ASL to English Translation

> A wearable, sensor-based smart glove that recognizes American Sign Language (ASL) hand gestures and converts them into readable English letters and words in real time.

---

##  Overview

The **Smart Glove** is a wearable assistive-technology system designed to bridge communication between **American Sign Language (ASL) users** and people who do not understand sign language.

The glove captures hand and finger movements using multiple sensors connected to an **ESP32 microcontroller**. The acquired sensor data is processed and analyzed using **sensor fusion and machine learning** techniques to recognize different ASL gestures.

Recognized gestures are converted into corresponding **English letters**, which are then sequentially combined to form **readable words**.

### 🔄 System Pipeline

```text
Hand Gesture
     ↓
Flex Sensors + IMU
     ↓
ESP32 Data Acquisition
     ↓
Sensor Fusion
     ↓
Feature Extraction
     ↓
Machine Learning Model
     ↓
ASL Gesture Classification
     ↓
English Letter
     ↓
Letter Sequencing
     ↓
Readable Word
