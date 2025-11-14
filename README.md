![Project Banner](Assets/banner.png)

# 🚗 DIY Robotic Car Using Custom Motor Driver

This project is a fully working **DIY robotic car** built using a **custom-designed motor driver**, breadboard prototype electronics, relays, Li-ion battery pack, and a microcontroller for speed and direction control.

The car is completely hand-assembled and tested on a breadboard, making it a great learning project for embedded systems and motor control.

---

## 📸 Project Photo

<p align="center">
  <img src="Assets/Car_photo.jpg" alt="Robotic Car" style="width:100%; max-width:800px; height:auto;">
</p>

<p align="center"><strong>Figure 1 — Prototype robotic car with custom motor driver and Li-ion battery pack.</strong></p>

---

## 📷 Photo Gallery

### 🖥️ Serial Bluetooth Terminal Output

<p align="center">
  <img src="Assets/Serial_Bluetooth_Terminal.jpg" alt="Serial Bluetooth Terminal" style="width:100%; max-width:700px; height:auto;">
</p>

<p align="center"><strong>Figure 2 — Serial Bluetooth Terminal showing real-time command logs (LEFT, RIGHT, REVERSE, STOP).</strong></p>

---

### 📐 Circuit Diagram (Hand-drawn)

<p align="center">
  <img src="Assets/Circuit_Diagram_1.jpg" alt="Circuit Diagram 1" style="width:100%; max-width:800px; height:auto;">
</p>

<p align="center"><strong>Figure 3 — Complete circuit diagram including relays, motor driver, and ESP32 connections.</strong></p>

---

### 📐 DPDT / SPDT Motor Switching Diagram

<p align="center">
  <img src="Assets/Circuit_Diagram_2.jpg" alt="Circuit Diagram 2" style="width:100%; max-width:800px; height:auto;">
</p>

<p align="center"><strong>Figure 4 — DPDT motor direction switching diagram (implemented using two SPDT relays).</strong></p>

---

### 🔬 Inverter Output Waveform (Oscilloscope)

<p align="center">
  <img src="Assets/Inverter_Output_Waveform.jpg" alt="Inverter Output Waveform" style="width:100%; max-width:800px; height:auto;">
</p>

<p align="center"><strong>Figure 5 — Oscilloscope waveform showing custom driver switching pattern.</strong></p>

---

## 🔧 Features

- Custom MOSFET-based motor driver  
- Dual-motor control (forward & reverse)  
- Relay switching and protection  
- Li-ion battery pack for portable power  
- ESP32/Arduino microcontroller control  
- Breadboard prototype wiring  
- PWM-based motor speed control  
- Compact lightweight chassis  
- Expandable for sensors (ultrasonic, IR, Bluetooth)  

---

## 🧩 Hardware Used

- 2× DC gear motors with wheels  
- Custom motor driver (homemade)  
- ESP32 / Arduino (depending on your build)  
- Breadboards  
- Jumper wires  
- Relays  
- Li-ion batteries  
- Battery holder and connectors  
- Switches, diodes, resistors, capacitors  

---

## ⚙️ How It Works

1. The microcontroller sends **PWM signals** to the custom motor driver.  
2. The driver controls the motors for **forward**, **reverse**, or **stop**.  
3. Relays (optional) handle switching and protection.  
4. Li-ion batteries provide portable power to the entire system.  
5. All wiring is mounted on a lightweight chassis to form the robot.  

---

## 📄 License

This project is released under the **MIT License**.

---

