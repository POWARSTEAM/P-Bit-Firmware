# 🌱 POWAR STEAM – P-Bit Firmware & Dashboard

**P-Bit** is an educational microcontroller developed by [POWAR STEAM SL](https://www.powarsteam.es), designed to teach students about sustainability, climate change, and environmental sensing using hands-on STEAM tools.

This repository contains:

* 🔧 The **firmware** for the P-Bit: sensor readings, BLE communication, and TFT screen display.
* 🧪 A **web-based dashboard**: interactive and kid-friendly interface to visualize live data via Web Bluetooth.

---

## 🧠 What is the P-Bit?

The P-Bit is a compact environmental data logger equipped with:

* 🌡️ Air temperature and humidity sensors (DHT11 / DS18B20)
* ☀️ Light sensor (LDR)
* 🔊 Sound sensor (analog audio)
* 🌱 Soil temperature and humidity probes
* 🎛️ TFT display + rotary encoder for on-device navigation
* 💡 RGB LED + buzzer for feedback
* 📶 BLE connectivity to send sensor data to a web-based platform

It’s designed to be **used in classrooms** by K-12 students to run experiments, collect real-world data, and explore how environmental factors impact ecosystems and sustainability challenges.

---

## 📁 Repository Structure

```
/firmware/
  P-Bit.ino
  /lib/               # Sensor libraries and hardware interfaces

/webapp/
  index.html
  scripts.js
  style.css

/legacy/
  firmware-pbit-v1.2.bin       # Current firmware binary (to flash)
  pbit_base.ino                # Arduino IDE / PlatformIO base code
  voltage_sensor_test.ino      # Experimental code for voltage sensor
  tds_sensor_display.ino       # Experimental code for TDS sensor with enhanced screen UI

/assets/
  logo.png
  diagrams/
  screenshots/

LICENSE.md
README.md
```

---

## 🚀 Getting Started

*(To be completed as the project progresses and files are integrated)*

---

## 📡 Data Format

Sensor data is sent via BLE in the following JSON structure:

```json
{
  "device": "PBIT",
  "air_temp": 31.5,
  "air_hum": 55.0,
  "light": 1234,
  "noise": 302,
  "soil_temp": 29.1,
  "soil_hum": 78
}
```

---

## 🎓 Educational Use

This project is released for **educational and non-commercial use only**. Teachers, students, and institutions are encouraged to:

* Use it in classroom settings
* Explore sensor-based experiments
* Modify or expand upon it (with attribution)

See [`LICENSE.md`](./LICENSE.md) for full terms of use.

---

## 🤝 Collaborators & Acknowledgments

This project may include contributions from academic partners, student developers, and STEAM education advocates.

If you'd like to collaborate, contact us at **[pablo@powarsteam.com](mailto:pablo@powarsteam.com)**.

---

## 🔐 License

This project is licensed under:

> **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0)**

No commercial use is allowed. For licensing opportunities or commercial collaborations, contact us directly.

See [`LICENSE.md`](./LICENSE.md) for full details.

---

## 🧑‍💼 About POWAR STEAM

POWAR STEAM SL is a social-impact edtech company based in Barcelona, Spain. We design and manufacture tangible tools that help children **understand how the natural world works** – and how they can become **environmental changemakers**.

Visit us at: 🌍 [www.powarsteam.es](https://www.powarsteam.es)
