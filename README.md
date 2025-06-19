# 🌫️ Air Quality Monitoring System

This project involves creating a real-time air quality monitoring system using a gas sensor (MQ-135) and a Raspberry Pi. The system collects sensor data, analyzes air quality, and displays results.

---

## 📌 Project Details

- **Duration:** 8 hours  
- **Complexity:** Medium  
- **Portfolio Worthy:** ✅ Yes

---

## 🎯 Learning Outcomes

- Interfacing gas sensors with microcontrollers
- Real-time environmental data monitoring
- Data visualization techniques
- Basics of air quality indexes (AQI)

---

## 📚 Pre-requisites

- Basic Python programming
- Familiarity with gas sensors (MQ-135)
- Understanding of Raspberry Pi GPIO and analog-to-digital conversion
- Data plotting (optional: matplotlib)

---

## 🧰 Required Components

- MQ-135 gas sensor
- Raspberry Pi (any model)
- MCP3008 ADC (for analog-to-digital conversion)
- Breadboard and jumper wires
- Power supply (5V)
- Optional: OLED Display or cloud logging

---

## 🛠️ Setup Instructions

1. Connect the **MQ-135** sensor to **MCP3008 ADC**
2. Connect the **MCP3008** to **Raspberry Pi SPI interface**
3. Install Python libraries (`gpiozero`, `spidev`, `matplotlib`)
4. Run the code below to monitor and display real-time air quality

---

## 💻 How to Run

```bash
sudo pip3 install gpiozero spidev matplotlib
python3 air_quality_monitor.py
