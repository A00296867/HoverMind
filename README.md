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


phase 4: 
The drone uses facial recognition technology to identify and approach a person in need, delivering a payload to the target. The system is designed to be fully automated, with the drone controlling flight and facial recognition independently.

Features
Facial Recognition: The drone is equipped with facial recognition technology to detect and identify a specific person.
Autonomous Flight: The drone can fly upwards, search for the target face, and automatically navigate toward the identified individual.
Payload Delivery: Once the target is identified, the drone drops a payload at the person’s location.
Hardware
Drone: Chubory A68 Brushless Drone
Arduino: Used for interfacing with the drone's joystick to automate flight control
Joystick: Reverse-engineered to interface with the Arduino for flight control
Current Progress
Joystick Integration: The team is currently investigating and reverse-engineering the joystick to reconnect it with the Arduino for automated control of the drone.
Facial Recognition: The facial recognition system is being tested and integrated with the drone’s flight control.
Installation and Setup
Hardware Requirements:

Chubory A68 Brushless Drone
Arduino (e.g., Arduino Uno or Mega)
Joystick module (for reverse-engineering)
Camera module for facial recognition
Payload (e.g., a small kit or package)
Software Requirements:

Arduino IDE (for programming the Arduino)
Facial recognition software (e.g., OpenCV or a similar library)
Additional libraries for drone control (depending on the drone’s system)
Setup Instructions:

Install the Arduino IDE and the necessary libraries for drone control and facial recognition.
Connect the joystick to the Arduino and reverse-engineer the connection to enable automated flight control.
Integrate the facial recognition system to control the drone’s navigation.
Future Improvements
Enhance the facial recognition system for better accuracy.
Optimize the drone’s flight capabilities for more precise movements.
Implement additional payload features (e.g., different types of rescue kits).


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

# Basic architecture of the drone
![Image](https://github.com/user-attachments/assets/55910279-b5f2-4f1e-aa9f-420208281d9d)

# Simple Quadcopter Data Flow Diagram with Single Radio Controller

![Image](https://github.com/user-attachments/assets/2ed07bf8-0395-49fd-9b5b-824709bce290)

# YMFC_Schematic

![Image](https://github.com/user-attachments/assets/f2ece7d7-cca2-470e-a858-cf4e85fdd1ad)

# Way to control drone using smartphone

https://youtu.be/eDDdNAw7GqQ?si=brWKFNLE81Xn3_XE


