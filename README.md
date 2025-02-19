# RADAR-made-with-arduino-
![IMG_4887](https://github.com/user-attachments/assets/f9f9e44a-6a78-4ef8-a6ee-f7067589009b)


# 🚀 Arduino Radar System  

## 📌 Project Overview  
This project is an **Arduino-based radar system** that uses **ultrasonic sensors** to measure the speed of objects. When an object passes through two ultrasonic sensors placed at a fixed distance apart, the system calculates its speed and displays it on an **I2C LCD screen**.  

## 🛠 Components Used  
- **Arduino Uno**  
- **HC-SR04 Ultrasonic Sensors (x2)**  
- **I2C LCD Display (16x2)**  
- **Connecting Wires & Breadboard**  

## ⚡ How It Works  
1. **Distance Measurement**: Each ultrasonic sensor detects objects by emitting sound waves and calculating the echo time.  
2. **Speed Calculation**: When an object crosses the first sensor, a timer starts. When it crosses the second sensor, the time is recorded, and speed is calculated using:  
   \[
   \text{Speed} = \frac{\text{Distance between sensors}}{\text{Time taken}} \times 3.6
   \]
   (to convert m/s to km/h).  
3. **LCD Display**: The speed is displayed on the LCD in real time.  
4. **Reset Mechanism**: After displaying the speed, the system resets for the next measurement.  

## 📷 Demo  


https://github.com/user-attachments/assets/e669238a-3cd6-4bbb-89c5-006e7943b316



## 🔌 Wiring Diagram  
![Screenshot 2025-02-19 184438](https://github.com/user-attachments/assets/72e48e2d-3357-4c2b-be34-a84f22662940)

## 🚀 Installation & Usage  
1. **Connect the components** as per the wiring diagram.  
2. **Upload the `radar_code.ino`** file to your Arduino.  
3. **Power on the system**, and it will be ready to measure speeds. 
