# 🌊 Bio-Guard — Water Quality Monitoring System

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-ESP32%20%7C%20Web%20BLE-03A9F4)

An innovative water quality analysis system combining optical sensors, embedded system engineering, and Web Bluetooth telemetry[cite: 12, 13]. Developed at **CEEFMTI João XXIII**.

---

## ⚙️ Key Features

- 🧪 **Contamination Level Analysis:** RGB optical sensing (TCS34725) to detect color shift and contamination indicators[cite: 12, 13].
- 💡 **Turbidity Tracking:** LDR sensor evaluating light intensity and water clarity[cite: 12, 13].
- 📶 **Wireless Telemetry:** Real-time data transmission over Web Bluetooth API (BLE).
- 📊 **Dynamic Diagnosis:** Automated status evaluation (Good, Warning, Critical) based on telemetry thresholds[cite: 13].

---

## 🛠️ Tech Stack

### **Hardware & Sensors**
- ESP32 WROOM-32 (Bluetooth Low Energy)[cite: 12]
- TCS34725 RGB Color Sensor[cite: 12]
- Light Dependent Resistor (LDR) Sensor[cite: 12]
- Optical clarity sensor array[cite: 12]

### **Frontend & Interface**
- Responsive HTML5 & CSS3 with modern gradient UI[cite: 10, 11]
- Vanilla JavaScript (ES6+) with Web Bluetooth API integration[cite: 13]

---

## 🚀 Local Setup

This project uses the **Web Bluetooth API**, which requires an `HTTPS` environment or `localhost`[cite: 13].

```bash
# 1. Clone the repository
git clone [https://github.com/Davy466/Bio-Guard-7.git](https://github.com/Davy466/Bio-Guard-7.git)

# 2. Navigate into the folder
cd Bio-Guard-7

# 3. Start a local server (e.g. via Python)
python -m http.server 8000
