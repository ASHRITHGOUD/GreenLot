# GreenLot

Greenlot is a smart irrigation system that uses IoT sensors and automation to monitor soil moisture, temperature, humidity, gas, and light levels, controlling water pumps efficiently. It integrates with Firebase and a web dashboard for real-time monitoring, control, and multilingual user support.

#GREENLOT
# 🌿 GREENLOT — Smart Agriculture & Irrigation System

**GREENLOT** is a full-stack smart agriculture system designed to empower farmers with intelligent field monitoring, real-time decision-making, and multilingual accessibility. By combining IoT sensors, Firebase integration, and a beautifully crafted web interface, GREENLOT makes modern farming more accessible, efficient, and automated.

> _To deploy this project locally or on a server:_ https://greenlot.onrender.com/index.html

---

## 🔍 Project Overview

GREENLOT helps farmers manage their fields intelligently through:
- 🌾 **Crop recommendations** based on automatic **location & season detection** for new farmers.
- 📈 Real-time **sensor data monitoring**.
- 💧 Automatic and manual **irrigation control**.
- 🔥 Hazard detection (gas/fire) with **buzzer alerts**.
- 🌐 Multilingual web interface with **Telugu, English, Hindi** support.
- 📲 OTP-based secure login for farmers.
- 📰 Live agriculture **news updates** for awareness.

---

## 📸 Interface Highlights

> The HTML design of this project is carefully structured and visually enhanced for user-friendliness. Multiple web pages like `control`, `about`, `crop suggestion`, `readings`, and more have been beautifully styled using custom CSS for a smooth, professional farmer experience.

---

## ⚙️ System Architecture

```plaintext
ESP32 + Sensors ---> Firebase (Realtime DB) ---> Web App
         ^                                          |
         |------------------------------------------|
                Controls sent back to ESP32
