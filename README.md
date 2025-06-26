# 🚁 Arduino-Powered Quadcopter Drone

A custom-built quadcopter drone developed using Arduino and off-the-shelf components. This project explores the fundamentals of drone hardware, control systems, and flight dynamics — from frame construction to electronic speed control and flight stabilization.

---

## 🛠️ Project Overview

The drone follows the classic quadcopter structure, consisting of four brushless motors arranged in an X configuration. The frame was redesigned multiple times: originally made of carbon fiber (lightweight but fragile), it was later replaced with a more durable plastic frame to enhance resilience.

Each motor is paired with a **30A ESC** (Electronic Speed Controller) which controls motor speed and direction. The motors are brushless, allowing for high-frequency rotation and efficient upward thrust generation.

<p align="center">
  <img src="https://github.com/user-attachments/assets/30fa63ad-2df1-43e7-81f0-fbddbbbed016" width="700"/>
</p>
---

## 🧠 Flight Controller & Sensors

At the heart of the system is a **Crius SE v2.5** flight controller, which receives input from several essential onboard sensors:

- 📍 Magnetometer  
- 📈 Accelerometer  
- 🔄 Gyroscope  
- ⬆️ Barometer  

These PID control enable the drone to maintain stability and respond accurately to external stimuli and control commands.

---

## 🎮 Remote Control

The drone is operated via a radio transmitter that sends real-time signals to a receiver mounted on the drone. This receiver is directly connected to the flight controller, which interprets the input to adjust motor speeds and orientation.

---

## 💻 Programming

The flight logic is programmed using **Arduino**. Due to its complexity, the code is based on community-developed open-source firmware readily available online. It handles motor synchronization, sensor reading, and stabilization logic.

---

## 📸 Media

### 🔧 Current Drone Setup
<h4>This is the motherboard</h4>
<p align="center">
  <img src="https://github.com/user-attachments/assets/305dd2e3-cd88-4123-9569-f0b6b5110a08" width="500"/>
</p>

<h4>This is the view of the ESC (bottom)</h4>
<p align="center">
  <img src="https://github.com/user-attachments/assets/b353d311-c86f-4c61-a8b5-9d1275b237b8" width="500"/>
</p>

### 📹 Video Demo

<p align="center">
  <a href="https://youtu.be/2c25TwiUodc" target="_blank">
    <img src="https://img.youtube.com/vi/2c25TwiUodc/hqdefault.jpg" alt="Watch the video" width="600">
  </a>
</p>

Watch the drone in action — fully airborne and stabilized!

- ✅ Real-world tested with successful take-off and maneuvering

