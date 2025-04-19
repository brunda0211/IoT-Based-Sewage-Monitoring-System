# IoT-Based-Sewage-Monitoring-System
IoT-based sewage monitoring system using C++ on NodeMCU with ultrasonic sensors and Blynk. Detects blockages and overflows in real time, sending alerts to authorities. Reduces manual intervention and supports smart city infrastructure.

## ⚙️ Key Components

- **NodeMCU (ESP8266)**: For data collection and Wi-Fi transmission.
- **Ultrasonic Sensor**: Detects water level in manholes.
- **Blynk Application**: For real-time monitoring and alerts via mobile.
- **Arduino IDE**: For writing and uploading code to NodeMCU.
- **Breadboard & Jumper Wires**: For circuit prototyping.

## 🧠 How It Works

1. The ultrasonic sensor continuously monitors the water level inside a manhole.
2. The NodeMCU reads the sensor data and transmits it via Wi-Fi.
3. The Blynk app receives this data and displays real-time information on the user’s smartphone.
4. Alerts are triggered if water levels exceed a predefined threshold.

## 🛠 Features

- Live water level monitoring from anywhere.
- Early warning system for sewage overflows.
- Minimal hardware cost and low power consumption.
- Reduces the need for hazardous manual inspections.

## 🏗 Installation

1. Assemble the hardware components on a breadboard.
2. Upload the code to the NodeMCU using Arduino IDE.
3. Configure the Blynk app with the provided authentication token.
4. Place the assembled device in a sewage inspection manhole.
5. Monitor real-time values on the Blynk dashboard.

## 📱 Blynk Dashboard Features

- Real-time water level gauge.
- Push notifications for overflow alert.
- SuperChart for historical data tracking.
- ## 💻 Programming Language

## This project uses **C++** through the **Arduino IDE** to program the NodeMCU (ESP8266) microcontroller. The code handles:

- Reading sensor data (ultrasonic water level measurements)
- Interfacing with the Blynk IoT platform
- Sending data over Wi-Fi
- Triggering alerts when thresholds are exceeded

C++ is ideal for embedded systems like this due to its low-level hardware control and high performance.


## 📊 Real-World Impact

- Addresses manual scavenging issues.
- Minimizes urban flooding and sewage mixing incidents.
- Contributes to smart city initiatives.
