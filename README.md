# SentriMat: IoT-Enabled Package Security System

**SentriMat** is a privacy-first, camera-free security solution designed to mitigate porch piracy through **Dynamic Force-Signature Analysis**. By utilizing a high-frequency sensor matrix, the system distinguishes between authorized deliveries, environmental noise, and unauthorized theft.

---

## 🚀 Features

* [cite_start]**Impact Force Fingerprinting:** Samples contact force at high frequencies during the first 500ms to identify package material and density[cite: 13, 101, 157].
* [cite_start]**Spatial Center of Pressure (CoP) Tracking:** Monitors for package tilting or sliding using a multi-channel sensor matrix before removal[cite: 115, 155, 162].
* [cite_start]**Privacy-First Design:** Full security monitoring without the use of intrusive cameras or optical sensors[cite: 120, 171].
* [cite_start]**Automated Data Logging:** Generates time-stamped CSV files for detailed trend analysis and security audits, facilitating easy integration with tools like Microsoft Excel[cite: 15, 31, 37, 70].
* [cite_start]**Dual-Factor Verification:** Requires a physical "Footprint Signature" and a digital handshake for authorized retrieval, ensured by precise real-time clock timestamping[cite: 14, 25, 82, 108].

---

## 🛠️ Hardware Requirements

| Component | Specification | Purpose |
| :--- | :--- | :--- |
| **Microcontroller** | ESP32 / Arduino Board | [cite_start]System control and integration [cite: 14, 180] |
| **Sensors** | 9x Temperature / 3x DHT11 / FSR Matrix | [cite_start]Comprehensive environmental and load monitoring [cite: 13, 116] |
| **RTC Module** | DS3231 RTC Module | [cite_start]Precise timestamping for data integrity [cite: 14, 108] |
| **Storage** | SD Card Module (CSV Format) | [cite_start]Long-term data storage and accessibility [cite: 15, 29, 146] |
| **User Interface** | 16x2 LCD Display | [cite_start]Real-time data visualization and monitoring [cite: 14, 111, 193] |
| **Alert System** | Piezoelectric Buzzer | [cite_start]Immediate detection of anomalies and alerts [cite: 130, 131] |

---

## ⚙️ How It Works (The SVA Algorithm)

1. [cite_start]**State 0: Idle Monitoring** – Continuous monitoring of environmental and load parameters[cite: 190].
2. [cite_start]**State 1: Impact Handshake** – Detects high-speed force spikes to verify delivery events through unique time threads[cite: 159, 184].
3. [cite_start]**State 2: Secured State** – Monitors the Center of Pressure (CoP) stability using calibrated digital sensors[cite: 182, 183].
4. **State 3: Retrieval Verification** – Checks for authorized access patterns. [cite_start]If weight loss occurs without a verified sequence, a theft alarm is triggered[cite: 172, 213].

---

## 📈 Future Scope

* [cite_start]**IoT Framework Integration:** Incorporating protocols like MQTT or HTTP for remote monitoring over the internet[cite: 201, 203].
* [cite_start]**Advanced Data Analytics:** Integrating machine learning algorithms for predictive insights and anomaly detection[cite: 211, 212].
* [cite_start]**Diverse Sensor Support:** Expanding to include air quality, light intensity, and sound level monitoring[cite: 206].
* [cite_start]**Cloud Integration:** Centralized data storage and management for accessibility from anywhere[cite: 204].

---

## 📄 License & Intellectual Property

[cite_start]This project is part of an **Invention Disclosure** developed at **Manipal University Jaipur**[cite: 1, 3]. 

[cite_start]**Applicants/Inventors:** Vedica Saini, Rishav Dubey, Anupam Dubey[cite: 3, 5].

Unauthorized reproduction for commercial purposes is prohibited.
