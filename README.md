# Smart-Parking-System-Project

This project implements a real-time Smart Parking System using IoT technology. The system monitors parking availability, automates gate control, and provides remote status updates using a Blynk cloud server.

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

