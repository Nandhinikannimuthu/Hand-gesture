# Hand Gesture Remote Control using STM32 & NanoEdge AI Studio

This project uses an STM32 microcontroller with NanoEdge AI Studio to detect and classify hand gestures in real time. Based on the recognized gesture, it sends control signals to operate external devices such as fans, lights, or other appliances.

## 🔍 Overview

- **Platform**: STM32 Nucleo Board
- **AI Tool**: NanoEdge AI Studio (Edge Impulse Alternative)
- **Sensors**: MPU6050 (Accelerometer/Gyroscope)
- **Languages**: Embedded C
- **IDE**: STM32CubeIDE

The gesture recognition model is trained using real-world sensor data, embedded directly on the MCU, and does not require any cloud or internet connection for inference.

## 🎯 Features

- Real-time hand gesture recognition
- On-device AI model (no internet/cloud required)
- Low-latency control of output devices
- Expandable gesture classes
- Cost-effective and power-efficient solution

## 🧠 AI Workflow

1. Collect gesture sensor data using STM32 + IMU.
2. Use NanoEdge AI Studio to:
   - Upload and label data
   - Automatically generate & benchmark multiple AI models
   - Export the best model as a C library
3. Integrate the model into STM32CubeIDE project
4. Use output predictions to control GPIO pins or UART devices

## 📦 Project Structure

