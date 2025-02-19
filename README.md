# Smart-Parking-System-Project

The Smart Parking System is an IoT-based project designed to monitor parking slot availability, automate gate control, and display real-time updates using IR sensors, an LCD screen, and a servo motor. When a car approaches, the system checks for available slots and opens the gate if space is available. Once parked, the slot is marked as occupied, and the updated status is displayed on the LCD and sent to a remote monitoring system (Blynk App or Serial Monitor). If the parking is full, the gate remains closed to prevent additional entry. This system improves efficiency, reduces manual supervision, and enhances the parking experience. 🚗✨

**📌 Features**

✅ Real-time Parking Monitoring – Detects available & occupied slots

✅ LCD Display – Shows parking status (Full or Empty: X/Y)

✅ Servo Motor for Gate Control – Opens only when slots are available

✅ LED Indicators – Shows parking space occupancy

✅ Remote Monitoring via Blynk – Check status from anywhere

**🛠 Components Used**

Arduino Uno – Main controller

IR Sensors – Detects cars in parking slots

Servo Motor – Controls gate opening/closing

16x2 LCD Display – Displays available parking slots

LEDs – Indicate occupied/free spaces

WiFi Module (ESP8266 or NodeMCU) – Sends data to Blynk app

Blynk Cloud – Remote parking status monitoring

**🔧 Circuit Connections**

1️⃣ IR Sensors → Connected to Arduino Digital Pins (Detects cars)

2️⃣ Servo Motor → Connected to PWM Pin (Gate opens when slot is free)

3️⃣ LCD Display → Connected to I2C Pins (Shows availability)

4️⃣ LEDs → Connected to Digital Pins (Indicates slot status)

5️⃣ WiFi Module → Connected to Serial Pins (Sends data to Blynk)

