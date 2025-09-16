🚙 Rover Based Courier Delivery Vehicle 📌 Project Overview

This project is a line-following autonomous rover designed for courier delivery applications. It uses IR sensors to detect paths and control the movement of the vehicle via a motor driver circuit. The rover can move forward, turn left, turn right, or stop based on sensor input, making it suitable for automating courier or material transport in restricted areas such as campuses, hospitals, warehouses, and offices.

🛠 Features

🚦 Line Following System – Uses left and right IR sensors to detect black/white paths.

⚡ Autonomous Navigation – Automatically adjusts direction and speed.

🔔 Courier Delivery Use Case – Can be adapted for delivering parcels in controlled zones.

🔋 Low Power & Cost Effective – Works with simple Arduino-based hardware.

🔧 Hardware Requirements

Arduino Uno / Nano

IR Sensors (Left & Right)

Motor Driver (L293D or L298N)

DC Motors with Wheels

Power Supply (Battery)

Chassis (4-wheel recommended)

💻 Software Requirements

Arduino IDE

Required Libraries: None (uses built-in functions)

📜 Circuit Pin Connections Component Arduino Pin Left Sensor (LS) D2 Right Sensor (RS) D3 Left Motor (LM1, LM2) D4, D5 Right Motor (RM1, RM2) D6, D7 🚀 How It Works

Both sensors LOW → Rover moves Forward.

Left LOW, Right HIGH → Rover turns Right.

Left HIGH, Right LOW → Rover turns Left.

Both sensors HIGH → Rover Stops. 📌 Future Enhancements

📡 Add wireless communication (Wi-Fi / Bluetooth) for tracking.

📦 Add load compartment for courier packages.

🔄 Implement obstacle detection (Ultrasonic Sensor).

🤖 Integrate with IoT for smart courier management.
