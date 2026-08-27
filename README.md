# IoT Smart Blinds with Siri Integration

## 🛠️ Tech Stack

* **Microcontroller:** ESP32 (Seeed Studio XIAO ESP32-S3 / standard ESP32)
* **Motor & Driver:** NEMA17 Stepper Motor, L298N Motor Driver Module
* **Firmware:** C++ (Arduino IDE / ESP-IDF)
* **Integration:** Apple Shortcuts, RESTful HTTP API

## 📸 Gallery
<div display="flex">
    <img src="media/smart-blinds/open-close.gif" width=33%>
    <img src="media/smart-blinds/top.png" width=33%>
    <img src="media/smart-blinds/bottom.png" width=33%>
</div>

## 🚀 Design Process

* Engineered a custom IoT control board pairing an ESP32 microcontroller with an L298N motor driver module to actuate the window blinds.
* Fabricated a custom 3D-printed adapter to securely couple a NEMA17 stepper motor directly to the blinds operating shaft.
* Programmed the ESP32 in C++ using the Arduino IDE, implementing a lightweight RESTful HTTP API to handle remote control commands.
* Configured Apple Shortcuts to trigger HTTP endpoints via any Apple device, enabling seamless voice control through Siri.
