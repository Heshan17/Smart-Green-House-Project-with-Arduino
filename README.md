Smart Greenhouse Automation System – Full Project Description

This project is a fully automated Smart Greenhouse System built using an ESP32 microcontroller to monitor and control plant-growing conditions for both soil-based and hydroponic cultivation. The system uses multiple sensors, actuators, and an IoT dashboard to ensure optimal plant health with minimal human intervention.

🌱 Key Features

Dual plant-growing methods

Soil-based planting

Hydroponics nutrient solution system

📡 Sensors Used

Soil Moisture Sensor – Measures soil hydration levels and triggers irrigation automatically.

TDS Sensor – Monitors nutrient concentration in the hydroponics system.

DHT22 Sensor – Reads temperature and humidity inside the greenhouse.

Water Level Sensor – Tracks tank water level and controls the auto-refill system.

Water Temperature Sensor – Ensures hydroponic nutrient solution stays within safe temperature limits.

⚙️ Automated Controls

Automatic Irrigation System
Waters soil plants when soil moisture drops below the threshold.

Hydroponics Pump Control
Maintains correct nutrient circulation based on TDS and water temperature.

Tank Auto-Refill Control
Automatically refills the water tank when the water level gets too low.

Scheduled Pump Operations
RTC-based scheduled watering (e.g., every 10 minutes if required).

🔐 Security System

3×4 Keypad + Solenoid Lock
Greenhouse door is password-protected for controlled access.
Users enter a numeric password to unlock the solenoid lock.

📱 IoT Integration (Blynk App)

The project is fully integrated with the Blynk IoT platform, enabling:

Real-time monitoring of all sensor values

Manual pump controls

Alerts/notifications

Visualization dashboards

Remote interaction with the system

🔌 Hardware Used

ESP32 Development Board

Soil Moisture Sensor

DHT22 Temperature & Humidity Sensor

TDS Sensor

Ultrasonic/Float Water Level Sensor

Water Temperature Sensor (DS18B20)

Relay Modules

Solenoid Lock

3×4 Matrix Keypad

Water Pumps (Soil + Hydroponics)

Power Supply and wiring

🎯 Project Goals

Automate plant growth with minimal human involvement

Monitor greenhouse environment in real-time

Improve water usage efficiency

Protect the greenhouse with a smart locking system

Implement both soil and hydroponic methods in a single system

Ensure easy control and monitoring via IoT
