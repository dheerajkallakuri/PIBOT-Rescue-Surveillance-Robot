# PiBot: Rescue Surveillance Robot

## Video Demonstration

For a visual demonstration of this project, please refer to the video linked below:

[Project Video Demonstration](https://youtu.be/otnKntRg7Aw)

[![Project Video Demonstration](https://img.youtube.com/vi/otnKntRg7Aw/0.jpg)](https://www.youtube.com/watch?v=otnKntRg7Aw)


## Overview

PiBot is a cost-effective prototype designed for Search and Rescue (SAR) operations in urban disaster scenarios such as fire hazards, gas explosions, and building collapses. PiBot can operate in hazardous conditions, providing real-time data and live streaming to assist rescue teams in locating and assessing victims and dangers. It leverages minimal technology to keep costs low while ensuring effective communication and control.

## Features

- **Real-time Data Transmission:** Provides sensor readings for harmful gases, temperature, and obstacle detection.
- **Live Streaming:** Camera feed with pan-tilt mechanism for comprehensive site analysis.
- **Remote Operation:** Can be controlled over the same network or remotely via Team Viewer and DNS server.
- **Interactive GUI:** Web-based interface for controlling the bot and viewing data streams.

## Specifications

- **Processor:** Raspberry Pi
- **Camera:** Mounted on a pan-tilt mechanism
- **Sensors:** Gas sensors, temperature sensors, obstacle detection sensors
- **Motors:** Controlled via motor drivers
- **Communication:** Operates on the same network using IP address or remotely using Team Viewer

## System Architecture

### Hardware Components

- **Raspberry Pi:** Central processing unit for the bot.
- **Camera:** Provides live streaming with a pan-tilt mechanism.
- **Sensors:** Measure harmful gases, temperature, and obstacle distance.
- **Motors and Motor Drivers:** Control the movement of the bot.
- **Power Supply:** Batteries to power the bot.

### Software Components

- **Operating System:** Raspbian (Linux-based OS for Raspberry Pi)
- **Programming Languages:** Python, Embedded C, JavaScript
- **Web Server:** Lighttpd for hosting the interactive GUI
- **Control Libraries:** WiringPi for GPIO control
- **Communication Protocols:** NODE.js for sensor data server

### Input and Output

- **Input:** Commands from the interactive GUI or keyboard inputs.
- **Output:** Sensor readings, live camera feed, motor control signals.

## Modes of Operation

1. **Same Network Mode:**
   - The controller and bot are on the same network.
   - Access the bot via the IP address using a web browser.
   
2. **Remote Network Mode:**
   - The controller operates the bot from a different network.
   - Utilizes Team Viewer and DNS server for remote access.

## Getting Started

### Prerequisites

- **Hardware:** Raspberry Pi, Camera, Sensors, Motors, Motor Drivers, Batteries
- **Software:** Raspbian OS, Python, NODE.js, WiringPi, Lighttpd

### Installation

1. **Set Up Raspberry Pi:**
   - Install Raspbian OS on an SD card.
   - Boot Raspberry Pi and complete the initial setup.

2. **Install Required Libraries:**
   - Install WiringPi for GPIO control.
   - Set up Lighttpd web server.
   - Install necessary Python libraries for sensor interfacing and motor control.
   - Install NODE.js and configure the sensor data server.

3. **Clone the Repository:**
   - Clone this project repository onto your Raspberry Pi.

### Running the Project

1. **Start Web Server:**
   - Launch Lighttpd to host the interactive GUI.

2. **Run Sensor and Motor Control Scripts:**
   - Start the NODE.js server for sensor data.
   - Execute Python scripts for motor and pan-tilt control.

3. **Access the GUI:**
   - Open a web browser and enter the Raspberry Pi’s IP address (same network mode) or connect via Team Viewer (remote network mode).

4. **Operate PiBot:**
   - Use the interactive GUI or keyboard inputs to control the bot and monitor real-time data and live feed.

## Potential Challenges

- **Lag in Detection and Response:** Potential delay due to processing overhead.
- **CPU Overloading:** High processing requirements may overload the CPU.
- **Battery Life:** Ensure sufficient power supply for prolonged operations.
- **Calibration of Sensors:** Accurate calibration is required for reliable data.
- **Camera Angle:** Proper positioning is crucial for effective site analysis.

## Conclusion

PiBot offers a practical and affordable solution for SAR operations, providing critical real-time data and live streaming to assist rescue teams. Its minimal technology approach ensures cost-effectiveness without compromising essential functionalities.

## Links

- ![Presentation Preview](Presentation.pdf)
- ![Report Preview](Report.pdf)
