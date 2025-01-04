🌱 SMART PLANT WATERING SYSTEM 🌱


📝 Problem Statement

In today's fast-paced world, many individuals struggle to keep their plants hydrated due to busy schedules, 
leading to plant neglect and unnecessary water wastage. To address this issue, an automated plant watering system has been developed. 
This system monitors soil moisture levels and delivers water efficiently, ensuring healthy plant growth while conserving water.

💧 Issue: Busy schedules = neglected plants + wasted water.
✨ Solution: A smart system to monitor soil moisture and water plants efficiently, ensuring healthy growth 🌿 while saving water.




🚀 How It Works
1️⃣ 📡 Sensor: Detects soil moisture.
2️⃣ 🧠 NodeMCU: Processes data and connects to Wi-Fi (Blynk 2.0).
3️⃣ 💦 Water Pump: Activates automatically when soil is dry.
4️⃣ 📱 Control: Monitor and manage via app/web dashboard.


🛠️ How to Make It
Step 1: Connect the Components

🖥️ Connect NodeMCU to the soil moisture sensor.
⚡ Use a relay module to link the water pump to the circuit.
📟 Attach the LCD display (via I2C module) to show data.
🔋 Power everything with a 9V battery or USB.
Step 2: Code the System

Install the Arduino IDE.
Add libraries for NodeMCU and Blynk.
Write the program to read soil moisture, control the pump, and send data to the Blynk app.
Step 3: Set Up the Blynk App

Download the Blynk 2.0 app.
Create a project and link it to your NodeMCU via Wi-Fi.
Add widgets (e.g., a button for manual pump control and a moisture level display).
Step 4: Test & Deploy

Place the moisture sensor in the soil.
Test the pump by drying/wetting the soil.
Fine-tune thresholds for optimal plant care.


🔧 Components
🖥️ NodeMCU ESP8266: IoT controller.
🌡️ Soil Moisture Sensor: Reads moisture level.
⚡ Relay Module: Controls water pump.
💧 Mini Water Pump & Pipe: Supplies water.
📟 LCD Display: Shows status.
🔋 9V Battery: Power source.
💡 Features
✅ Real-time monitoring 🌐
✅ App-based control 📱
✅ Saves water 💧
✅ Ensures healthy plants 🌿

✨ Conclusion
The Smart Plant Watering System makes plant care effortless 🌟. With IoT-enabled automation and efficient water usage, it’s the perfect companion for plant lovers! 💚
The Smart Plant Watering System is a reliable solution for plant care, providing an automated way to monitor and water plants. 
By leveraging sensors, a NodeMCU microcontroller, and the Blynk 2.0 platform, users can ensure the health and longevity of their plants, even when they're away. 
This technology not only simplifies plant care but also promotes sustainable water usage, making it a practical and eco-friendly innovation for plant enthusiasts.
