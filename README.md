# 🚰 RF-Based Automatic Water Tank Control System

> An award-winning wireless water level monitoring and automatic pump control system developed using RF communication, discrete electronic components, and relay-based switching.

<p align="center">
  <img src="Images\project_model.png" alt="Project Image" width="700">
</p>

---

## 📖 Overview

The **RF-Based Automatic Water Tank Control System** is a hardware project designed to automatically monitor the water level of an overhead tank and control the water pump wirelessly using RF communication.

The system eliminates the need for manual pump operation by automatically switching the motor **ON** when the water level becomes low and **OFF** when the tank is full, preventing water overflow, dry running, and unnecessary power consumption.

Unlike many modern implementations based on microcontrollers, this project was built primarily using **discrete electronic components**, demonstrating practical circuit design and hardware implementation skills.

---

## 🏆 Achievement

🥉 **2nd Runner-Up (3rd Place)**

**Technovision 2K23 Hardware Project Competition**

This project was recognized for its innovative approach to wireless and automatic pump control.

---

# ✨ Features

- 📡 Wireless control using RF communication
- 🚰 Automatic water pump ON/OFF control
- ⚡ Relay-based motor switching
- 📶 RF Transmitter and Receiver communication
- 🔋 Low-cost hardware implementation
- 🛠 Built using discrete electronic components
- 🔒 Reliable automatic operation
- 💧 Prevents water overflow
- 🔥 Protects the motor from unnecessary operation

---

# ⚙️ Working Principle

The system consists of two sections:

## 1️⃣ Water Tank Unit (Transmitter)

- Water level sensors detect different water levels.
- The sensor information is transmitted wirelessly using an RF Transmitter module.

## 2️⃣ Pump Control Unit (Receiver)

- The RF Receiver receives the transmitted water level information.
- Based on the received signal:
  - Pump turns **ON** when the water level is low.
  - Pump turns **OFF** when the tank reaches the predefined maximum level.
- A relay is used to safely control the water pump.

The complete operation is performed automatically without requiring manual intervention.

---

# 🛠 Hardware Used

- BC547 NPN Transistors
- RF Transmitter Module
- RF Receiver Module
- Relay Module
- Water Pump
- lithium ion Batterys
- LEDs
- Resistors
- Capacitors
- Diodes
- Connecting Wires
- PCB / General Purpose Board

---

# 🧠 Skills Demonstrated

- Electronics Circuit Design
- RF Communication
- Relay Control
- Hardware Debugging
- Wireless Monitoring
- PCB Design Concepts
- Analog & Digital Electronics
- System Integration
- Problem Solving

---

# 🎥 Demonstration Video

[YouTube](https://youtu.be/zw9lHeaTPAo?si=mIalCZn4R1ZrWdTB)

---

# 📄 Circuit Diagram

<p align="center">
  <img src="PCB Tank Unit\schematic_kicad.jpg" alt="Circuit Diagram - Tank Unit" width="800">
</p>

<p align="center">
  <img src="PCB Pump Unit\receiver_schematic_drawing_03.jpg" alt="Circuit Diagram - Pump Unit" width="800">
</p>

---

# PCB 3D View

<p align="center">
  <img src="PCB Tank Unit\pcb_3D_view_with_components.jpg" alt="PCB 3D - Tank Unit" width="800">
</p>

<p align="center">
  <img src="PCB Pump Unit\receiver_3d_07.jpg" alt="PCB 3D - Pump Unit" width="800">
</p>

---

# PCB Routing

<p align="center">
  <img src="PCB Tank Unit\pcb_layout_tank_unit.jpg" alt="PCB Routing - Tank Unit" width="800">
</p>

<p align="center">
  <img src="PCB Pump Unit\receiver_pcb_copper05.jpg" alt="PCB Routing - Pump Unit" width="800">
</p>

For more pictures visit PCB directories....

---


# 🚀 Future Improvements

- ESP32 / STM32 based implementation
- Solar Pannel Integration
- IoT Dashboard
- Wi-Fi Connectivity
- Mobile Application
- MQTT Integration
- Cloud Monitoring
- Water Consumption Analytics
- Mobile Notifications
- PCB Miniaturization

---

# 💡 Applications

- Residential Buildings
- Apartments
- Schools
- Hostels
- Commercial Buildings
- Industrial Water Storage
- Farms
- Smart Water Management

---

# 🏅 Competition Recognition

This project received the **2nd Runner-Up (3rd Place)** award at the **Technovision 2K23 Hardware Project Competition**, recognizing its practical implementation and engineering design.

---

# 👨‍💻 Author

**Sourik Choudhury**

B.Tech – Electronics & Communication Engineering

- 💼 [LinkedIn](https://www.linkedin.com/in/sourik-choudhury-332b72248/)
- 💻 [GitHub](https://github.com/sourikchoudhury)

---

# 📜 License

This project is licensed under the MIT License.

---

## ⭐ If you found this project interesting, consider giving it a Star!