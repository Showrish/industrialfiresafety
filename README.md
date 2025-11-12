# Industrial Fire Safety System

### Live Monitoring Dashboard: [https://industrialfiresafety123.web.app/](https://industrialfiresafety123.web.app/)

## Overview
The **Industrial Fire Safety System** is an IoT-based solution designed to improve fire safety and security in industrial environments. Through real-time monitoring, automatic response mechanisms, and an interactive online dashboard, the system ensures early hazard detection and quick preventive actions to protect personnel and property.

---

## Features

- **Real-Time Hazard Monitoring:** Monitors smoke, gas, flame, temperature, and motion data on a live [dashboard](https://industrialfiresafety123.web.app/).  
- **Automatic Safety Response:** Activates servo-controlled ventilation systems or extinguisher doors based on hazard detection.  
- **Instant Alerts:** Buzzer and LED provide immediate audible and visual warnings for fire or unauthorized movement.  
- **Data Logging:** Integrated with Firebase for real-time data updates and historical trend analysis.

---

## Project Structure

| Directory | Description |
|------------|--------------|
| **/code** | Contains ESP32 Arduino source code. |
| **/website** | Website files for visualization and monitoring. |
| **/firebase** | Firebase configuration and credentials. |
| **/docs** | Documentation, system architecture, and design diagrams. |

---

## Components Used

### Hardware Components
- **ESP32 Microcontroller:** Main controller for processing and communication.  
- **Sensors:**  
  - MQ05 Gas Sensor – detects flammable gases.  
  - Flame Sensor – detects fire or flame presence.  
  - PIR Motion Sensor – identifies unauthorized entry.  
  - DHT11 Sensor – measures temperature and humidity.  
  - Ultrasonic Sensors – used for proximity and hazard detection.  
- **Servo Motors:** Operate ventilation or extinguisher doors.  
- **Alert Systems:** Include buzzer and LEDs for hazard alerts.

### Software Components
- **Arduino IDE:** Used for programming and uploading code to the ESP32.  
- **Firebase:** Backend used for real-time data storage and synchronization.  
- **Website:** Built using HTML, CSS, and JavaScript, hosted on Firebase for live monitoring.

---

## System Architecture
The system integrates multiple sensors connected to an ESP32 microcontroller. Sensor readings are continuously sent to **Firebase**, where they are displayed on a real-time web dashboard. This allows users to remotely monitor industrial safety parameters and view system alerts through [industrialfiresafety123.web.app](https://industrialfiresafety123.web.app/).

---

## Getting Started

### 1. Hardware Setup
- Connect ESP32 with all required sensors as shown in the circuit diagram.  
- Connect servo motors to represent ventilation or extinguisher systems.  
- Attach buzzer and LEDs for alert mechanisms.

### 2. Software Setup
- Install **Arduino IDE** and necessary libraries (ESP32, Firebase).  
- Configure Firebase credentials in the source code.  
- Clone the repository and upload the code to the ESP32 board.

### 3. Web Hosting on Firebase
- Deploy website files to Firebase Hosting for live monitoring.  
- Set Firebase credentials in the frontend configuration.

### 4. Running the System
- Power the ESP32 and start the system.  
- Access the dashboard: [https://industrialfiresafety123.web.app/](https://industrialfiresafety123.web.app/)  
  to monitor real-time data and alerts.

---

## Usage

1. **Real-Time Monitoring:**  
   View sensor readings (gas, flame, temperature, motion) directly on the web interface.  

2. **Automatic Response:**  
   When a hazard is detected, the system activates alarms, LEDs, and servo motors automatically.  

3. **Data Logging:**  
   Firebase stores all readings, enabling users to review historical data for safety analysis.

---

## Future Enhancements

- Development of a mobile application for remote monitoring.  
- Integration of SMS or email alert notifications.  
- Use of predictive analytics on historical data to anticipate hazards.  

---

## Contributors

This project was collaboratively developed by:
- **Showrish** – VU21CSEN0600005  
- **Suhash** – VU21CSEN0600011  
- **Dhanush** – VU21CSEN0600121  

---

