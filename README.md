# AIfES-Net

This repository contains the source code for the **training and inference** of **Feedforward Neural Networks (FNNs)** and **Convolutional Neural Networks (CNNs)** directly on **microcontrollers**, specifically the **ESP32-WROOM-32** and **STM32F401RE**, using the [AIfES](https://www.fraunhofer.de/en/research/lighthouse-projects/aifes.html) (Artificial Intelligence for Embedded Systems) framework.

These neural networks are trained **on-device** to serve as **Intrusion Detection Systems (IDS)**, allowing the microcontrollers to detect anomalies in input data without requiring external computation or cloud-based processing.

> 🔍 **Note**: The **FNN implementation for ESP32** is not included in this repository, as it is part of a separate project. You can find it here: [**gossip-ids-esp32**](https://github.com/gsacrestano/gossip-ids-esp32)

---

## 🧠 Project Overview

- ✅ **On-device training** of FNNs and CNNs using AIfES
- ✅ **Real-time inference** of trained models for IDS tasks
- ✅ Designed for **ESP32-WROOM-32** and **STM32F401RE**
- ✅ All code is **Arduino IDE compatible** with proper board configuration
- ✅ Lightweight, no external training required
- ✅ Focused on embedded cybersecurity use cases

---

## 🛠️ Getting Started

To compile and upload the code, use the **Arduino IDE** with proper board configuration:

### ✅ ESP32-WROOM-32
1. Install the [ESP32 board package](https://docs.espressif.com/projects/arduino-esp32/en/latest/installing.html)
2. Select **ESP32-WROOM-DA Module** in the board manager
3. Install required libraries (AIfES, etc.)
4. Open the `.ino` file 

### ✅ STM32F401RE
1. Install [STM32 Arduino Core](https://github.com/stm32duino/BoardManagerFiles)
2. Select **Nucleo F401RE** in the board manager
3. Install required libraries
4. Open the `.ino` file

---
