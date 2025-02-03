# HoverMind
IOT 1021

# 🚁 Disaster Response & Search and Rescue Drone
📌 Project Overview
This project aims to develop an autonomous search and rescue drone that can assist in disaster relief operations. The drone will be equipped with thermal imaging, GPS, and real-time telemetry to locate survivors and deliver emergency supplies.

Initially, the drone will be controlled using a Bluetooth module (HC-05/HC-06) and a mobile app for short-range testing. If Bluetooth proves unreliable, we will transition to a radio transmitter and receiver system for better range and stability.

🔹 Features & Functionality
✅ Search & Rescue Capabilities
Uses thermal imaging and GPS to locate survivors in disaster zones.
Capable of carrying and delivering emergency supplies to designated locations.

✅ Control System
Phase 1: Bluetooth-based control via a custom mobile app.
Phase 2 (If Needed): Integration of an RC transmitter & receiver for extended range.
Failsafe system to ensure the drone lands safely if communication is lost.

✅ Autonomous Flight & Navigation
MPU6050 IMU for stability and motion tracking.
PID-based motor control for smooth and responsive flight.
Altitude and position monitoring for precise movement.

✅ Live Telemetry & Monitoring
Real-time data transmission for battery status, altitude, and position tracking.
Mobile app interface for easy monitoring and control.

📡 Technology Stack
🛠 Hardware Components
Flight Controller: Arduino-based system
Sensors: MPU6050 IMU, GPS, Thermal Camera (for future integration)
Communication: HC-05/HC-06 Bluetooth module, optional 2.4 GHz RC system
Motors & ESCs: Brushless motors with ESCs for efficient flight
Battery: LiPo battery for power efficiency

💻 Software & Frameworks
Arduino C++ for drone control logic
PID algorithm for flight stability
Mobile App (Android/iOS) for Bluetooth-based control and telemetry
Failsafe mechanism to ensure emergency landing in case of connection loss

🚀 Development Roadmap
Phase 1: Bluetooth-Based Drone Control

✔ Setup Bluetooth module (HC-05/HC-06) and integrate with Arduino.

✔ Develop a simple mobile app for sending throttle, roll, pitch, and yaw commands.

✔ Test motor response to mobile commands and implement failsafe auto-landing.


Phase 2: Flight Stabilization & Autonomous Navigation

✔ Implement PID control for smooth and stable flight.

✔ Integrate altitude monitoring and position tracking.


Phase 3: Advanced Features & Long-Range Communication

✔ Expand control range using RC transmitter & receiver if Bluetooth is insufficient.

✔ Add thermal imaging & GPS tracking for automated rescue missions.


👥 Team Members
Name	Role
Harisanker Sureshkumar Uma	Project Coordinator & Electronics
Devika Vinod	Software Development
Alwin Antony	Testing & QA
Alister Jaison	Software Development
Sanjay Basil	Hardware Integration

📌 How to Get Started

1️⃣ Hardware Setup

Connect the Bluetooth module (HC-05/HC-06) to the flight controller.
Attach motors, ESCs, and power module.
Ensure all connections are secure and tested.

2️⃣ Software Setup

Install Arduino IDE and required libraries.
Upload flight control and Bluetooth communication code to Arduino.
Pair the mobile app with the Bluetooth module.

3️⃣ Testing & Calibration

Verify motor response to app controls.
Tune PID values for stable hovering and movement.
Implement failsafe landing in case of Bluetooth disconnection.
📢 Future Enhancements
🔹 Upgrade to Wi-Fi or 4G/5G control for long-range operation.
🔹 Implement computer vision for intelligent obstacle avoidance.
🔹 Add real-time streaming from thermal camera to detect survivors.

![Image](https://github.com/user-attachments/assets/2ed07bf8-0395-49fd-9b5b-824709bce290)
