# 🛡️ Air Defense Mechanism using Radar System

## 🔍 Overview
This project simulates an air defense system using a radar-like mechanism. Built using **Arduino**, **ultrasonic sensors**, and the **Processing IDE**, it detects objects within a defined range and direction, visualizes them in real-time, and triggers automatic defense responses like alarms and movement.

## 🎯 Features
- Radar-style object detection using HC-SR04 ultrasonic sensor  
- Servo motor rotates sensor to scan the environment  
- Real-time visualization with radar sweep via Processing IDE  
- Audio-visual alert system (buzzer + LED) on object detection  
- Distance and angle calculation  
- Automated response simulation (mimicking target tracking)

## 🛠️ Technologies Used
- Arduino UNO  
- HC-SR04 Ultrasonic Sensor  
- Servo Motor  
- Buzzer & LED  
- Processing IDE (Java-based visualization)  
- C/C++ for Arduino sketch  

## 🧠 How It Works
1. The ultrasonic sensor mounted on a servo rotates to scan the area.  
2. Detected objects within a threshold range are visualized on a radar UI using Processing.  
3. When an object is within a critical distance, the buzzer and LED are triggered.  
4. The system simulates a defense response, ideal for smart surveillance or early warning systems.

## 📄 Publication
This project was published in the **International Journal of Information Technology and Computer Engineering** for its innovative approach to simulating radar-based defense systems using IoT components.

## 📸 Demo
_<img width="1468" height="915" alt="Screenshot 2025-05-16 153256" src="https://github.com/user-attachments/assets/3b827ba8-e195-4dc2-9c97-3baef580778b" />

## 📌 Getting Started
1. Connect HC-SR04 to Arduino with servo motor.  
2. Upload the `radar_defense.ino` sketch to Arduino.  
3. Open the `radar_visual.pde` in Processing IDE.  
4. Run both Arduino and Processing simultaneously to see the radar in action.

## 🤖 Future Enhancements
- Integrate camera or ML model for object classification  
- Wireless data transmission (e.g., using ESP8266)  
- GUI controls for angle, range, or alert settings  

## 🔗 License
This project is open-source for educational purposes. Feel free to modify and enhance it.

