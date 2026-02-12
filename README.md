# Digital Drainage Mapping and Maintenance Prediction

![GitHub License](https://img.shields.io/badge/license-Patent--Pending-orange)
![Hardware](https://img.shields.io/badge/Hardware-Arduino--Uno-blue)
![IoT](https://img.shields.io/badge/IoT-Flood--Monitoring-green)

## 📌 Overview
Urban flooding is a critical infrastructure challenge often caused by the reactive maintenance of blocked drainage systems. This project introduces a **low-cost IoT solution** that identifies potential flooding by monitoring real-time water levels within drainage pipes and road-prone areas.



The system utilizes **ultrasonic sensors** to measure the distance between the sensor and the water surface. By digitizing these levels and mapping them onto an interactive interface, the system can classify the risk of overflow—allowing municipal bodies to intervene before flooding occurs.

## 🚀 Key Features
* **Real-Time Level Sensing:** Uses ultrasonic pulses to provide high-precision water height measurements.
* **Predictive Intelligence:** Categorizes water levels into **Normal**, **Warning**, and **Critical** states based on depth thresholds.
* **Digital Twin Capability:** Designed to bridge physical infrastructure with a digital representation for city-wide real-time monitoring.
* **Visual Alert System:** Integrated LED indicators (Green, Yellow, Red) for immediate on-site status assessment.

## 🔬 System Architecture
The project follows a modular architecture designed for scalability:

1.  **Sensing Layer:** An ultrasonic transducer (HC-SR04) measures the distance to the water surface.
2.  **Processing Layer:** An Arduino Uno calculates the water level height and compares it against pre-calibrated safety models.
3.  **Visualization Layer:** Data is logged and processed for digital mapping and predictive alerting on a GIS-integrated platform.



## 📋 Components List
* **Microcontroller:** Arduino Uno
* **Sensor:** Ultrasonic Distance Sensor (HC-SR04)
* **Indicators:** 3 x LEDs (Green, Yellow, Red)
* **Resistors:** 3 x 220 Ohm (for LED protection)
* **Simulation Rig:** PVC pipe assembly and controlled water flow source.
* **Software:** Google Colab (Python) & Arduino IDE.

## 🧪 Methodology
The system was validated through a controlled experimental environment to ensure accuracy and reliability in varied urban scenarios:

* **Baseline Calibration:** Established the empty-pipe distance to serve as the zero-level reference, accounting for sensor offset and internal pipe diameter.
* **Level Simulation:** Introduced water at various heights within a test rig to simulate different flow capacities (25%, 50%, 75%, and 100%) and verify sensor linear accuracy.

* **Threshold Logic:** Developed a logic-based algorithm to trigger real-time alerts as the water level approaches the pipe ceiling, categorized into Normal, Warning, and Critical states.
* **Digital Integration:** Created a data-driven model suitable for real-time digital drainage mapping, allowing for seamless integration into GIS-based monitoring platforms.


## 📂 Repository Structure
```text
├── digital_drainage_mapping_and_maintenance_prediction.ipynb  # Primary Project Code & Analysis
├── README.md                                                  # Project Documentation
└── assets/                                                    # Circuit diagrams and experimental setup photos
```
---

## ⚖️ Intellectual Property & Patenting
**Notice:** This project is currently under development for **patenting**. The documentation and code provided in this repository serve as a proof-of-concept. Specific proprietary algorithms, high-resolution calibration datasets, and custom hardware designs are intentionally withheld to protect intellectual property rights.

---

## 👤 Author
**S Aaron Rohan Raj**
*Student | Internet of Things & Urban Infrastructure*
