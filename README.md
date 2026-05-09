<div align="center">

# 👋 Hi, I'm Vladyslav Hirchuk

### Embedded Systems Engineer — I ship firmware and hardware from breadboard to production

📍 Olsztyn, Poland &nbsp;·&nbsp; 📫 [hirchukv@gmail.com](mailto:hirchukv@gmail.com)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/YOUR_LINKEDIN)
[![Portfolio](https://img.shields.io/badge/Portfolio-000000?style=for-the-badge&logo=vercel&logoColor=white)](https://YOUR_PORTFOLIO_URL)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/YOUR_GITHUB)

</div>

---

## 🧭 About Me

Embedded engineer with commercial end-to-end experience — I've designed the PCB, written the firmware, debugged the hardware, and handed off working products to real clients.

- 🚁 Shipped a **tilt-compensated drone fuel sensor** — 2-layer KiCad PCB, FreeRTOS on ESP32-C3, CAN 2.0B, OTA updates, ±3% accuracy — in a single contract cycle
- 🤖 Hands-on with **ROS2, LiDAR/IMU SLAM** on ARM64 edge compute
- 🌐 Contributed to a full-stack **DJI drone fleet platform** used in active field operations
- 🎓 Studying Computer Engineering at Lviv Polytechnic (expected May 2026)
- 🔭 Currently looking for a team where I can keep building real things

---

## 🛠️ Technical Skills

**Core Languages & Firmware**

![C](https://img.shields.io/badge/C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=flat-square&logo=gnu-bash&logoColor=white)

**Embedded Platforms & RTOS**

![FreeRTOS](https://img.shields.io/badge/FreeRTOS-006DAD?style=flat-square)
![ESP-IDF](https://img.shields.io/badge/ESP--IDF_(ESP32--C3)-E7352C?style=flat-square&logo=espressif&logoColor=white)
![Arduino](https://img.shields.io/badge/Arduino_(AVR)-00979D?style=flat-square&logo=arduino&logoColor=white)
![ARM64](https://img.shields.io/badge/ARM64_Linux-0091BD?style=flat-square&logo=arm&logoColor=white)

**Communication Protocols**

![CAN Bus](https://img.shields.io/badge/CAN_2.0B-grey?style=flat-square)
![I2C](https://img.shields.io/badge/I2C-grey?style=flat-square)
![SPI](https://img.shields.io/badge/SPI-grey?style=flat-square)
![UART](https://img.shields.io/badge/UART-grey?style=flat-square)
![MQTT](https://img.shields.io/badge/MQTT-660066?style=flat-square&logo=eclipsemosquitto&logoColor=white)
![NRF24L01](https://img.shields.io/badge/NRF24L01-grey?style=flat-square)

**Hardware & Tools**

![KiCad](https://img.shields.io/badge/KiCad-314CB0?style=flat-square&logo=kicad&logoColor=white)
![Oscilloscope](https://img.shields.io/badge/Oscilloscope-grey?style=flat-square)
![Logic Analyser](https://img.shields.io/badge/Logic_Analyser-grey?style=flat-square)
![3D Printing](https://img.shields.io/badge/3D_Printing-grey?style=flat-square)
![SMD Soldering](https://img.shields.io/badge/SMD%2FTHT_Soldering-grey?style=flat-square)

**Robotics & Sensors**

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white)
![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white)
![MediaPipe](https://img.shields.io/badge/MediaPipe-0097A7?style=flat-square)
![SLAM](https://img.shields.io/badge/SLAM_(DLIO,_LIO--SAM)-grey?style=flat-square)
![LiDAR](https://img.shields.io/badge/LiDAR_(Hesai,_Seyond)-grey?style=flat-square)

**Tooling & DevOps**

![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
![GitLab](https://img.shields.io/badge/GitLab-FC6D26?style=flat-square&logo=gitlab&logoColor=white)

---

## 🚀 Featured Projects

### 🛢️ Drone Fuel Tank Sensor
> `C/C++` `ESP-IDF` `FreeRTOS` `CAN 2.0B` `KiCad` `ESP32-C3`

Full product cycle — capacitive sensing (FDC1004) + tilt compensation (MPU-6050), 2-layer 40×30 mm PCB, 4-task FreeRTOS firmware, CAN 2.0B bus, OTA updates, NVS calibration. Delivered to client with user manual. **No board respins.**

---

### 🗺️ LiDAR + IMU SLAM on ARM64
> `ROS2` `DLIO` `LIO-SAM` `ARM64` `Orange Pi 5 Plus`

3D LiDAR + 9-DOF IMU on ARM64 edge compute. Recorded 9.5 GB rosbag at 250 Hz / 10 Hz. Real-time DLIO odometry with `.pcd` export and voxel downsampling. Solved timestamp drift with `message_filters` + `chrony`.

---

### 🤖 Robotic Hand Prototype ⭐ 6
> `Arduino` `C++` `NRF24L01` `Flex Sensors` `Servos` `3D Printing`

5-finger wireless prosthetic hand — flex sensor glove → NRF24L01 radio → servo actuation with real-time gesture mirroring. Fully open-source: firmware, schematics, and 3D files.

---

### 🕶️ AI Glasses Clone (Ray-Ban inspired)
> `Python` `OpenCV` `Vosk` `MediaPipe`

Voice-controlled camera HUD with offline speech recognition, real-time face + hand detection, and video recording pipeline.

---

### 🎲 Digital Dice — Hardware
> `KiCad` `555 Timer` `7-Segment Display`

Electronic dice circuit: 555 timer oscillator + 7-segment display, button-triggered random 1–6. Complete KiCad schematic and PCB.

---

### 💻 WinAPI System Monitor
> `C++` `Win32 API`

Native Win32 app for real-time CPU, memory, and process monitoring — zero third-party frameworks, direct system calls only.

---

## 📊 GitHub Stats

<div align="center">

![Vladyslav's GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_GITHUB_USERNAME&show_icons=true&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff&icon_color=58a6ff)

![GitHub Streak](https://github-readme-streak-stats.herokuapp.com/?user=YOUR_GITHUB_USERNAME&theme=dark&hide_border=true&background=0d1117&ring=58a6ff&fire=58a6ff&currStreakLabel=58a6ff)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_GITHUB_USERNAME&layout=compact&theme=dark&hide_border=true&bg_color=0d1117&title_color=58a6ff)

</div>

---

## 🏆 GitHub Trophies

<div align="center">

![Trophies](https://github-profile-trophy.vercel.app/?username=YOUR_GITHUB_USERNAME&theme=darkhub&no-frame=true&column=7)

</div>

---

## 📜 Certifications & Achievements

- 🏅 **C++ Proficiency** — College of DuPage
- 🏅 **Python Proficiency** — College of DuPage
- 🔒 **Computer Security Fundamentals** — uCertify
- 🌐 **TOEFL iBT B2 English** — ETS
- 🏆 **ICPC Certificate of Achievement** — Southwest Ukraine Regional 2021
- 🎓 **Community College Initiative Scholarship** — U.S. Department of State

---

<div align="center">

![Visitor Badge](https://visitor-badge.laobi.icu/badge?page_id=YOUR_GITHUB_USERNAME.YOUR_GITHUB_USERNAME)

*"I ship firmware and hardware from breadboard to production."*

</div>
