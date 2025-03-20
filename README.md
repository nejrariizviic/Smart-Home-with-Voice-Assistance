# Smart Home with Voice Assistance

## Table of Contents
- [Project Overview](#project-overview)
- [Required Tools](#required-tools)
- [Installation and Setup](#installation-and-setup)
- [Key System Features](#key-system-features)
- [Future Improvements](#future-improvements)

## Project Overview

The Smart Home with Voice Assistance is an embedded system that enables users to control home appliances using voice commands. The system is built using Arduino Mega 2560, various sensors, and an Android application for Bluetooth-based voice interaction. It provides a smart automation solution for monitoring and managing household devices efficiently.

## Required Tools

To set up and run the project, ensure you have the following software installed:

- Arduino IDE – for writing and uploading code to the microcontroller.

- Proteus 8 Professional – for circuit simulation and testing.

- Arduino Voice Control App – Android application for voice command processing.

## Installation and Setup

1. Download and Configuration

   - Download the project zip file and extract it.

   - Install Arduino IDE and Proteus 8 Professional if they are not already installed.

2. Working with Arduino IDE

- Open the file smart_home_code.ino in Arduino IDE.

- Select Arduino Mega 2560 from the Tools > Board menu.

- Click Verify to compile the code.

- Copy the hex file path from the output window.

3. Working with Proteus

- Open the project in Proteus.

- Paste the previously copied hex file path into the Arduino Mega component in Proteus.

- Load the hexadecimal paths for the PIR sensor, water sensor, and gas sensor from the Libraries directory.

4. Voice Control via Android App

- Download the Arduino Voice Control application on your Android device.

- Connect your phone to the system using a Bluetooth connection.

- Open the app and pair it with the system.

5. Running the Simulation

- Start the simulation in Proteus and test voice commands.

- Observe system responses and automated functionalities.

- Adjust and fine-tune the system for optimal performance.

## Key System Features

- Voice-Controlled Automation – Enables interaction through voice commands.

- Motion Sensor (PIR) – Turns on lights when motion is detected.

- Water Sensor – Detects water leaks and triggers alerts.

- Gas Sensor – Identifies gas presence and activates an alarm.

- Bluetooth Communication – Connects the system to an Android app.

## Future Improvements

- Wi-Fi Integration – Allowing remote control via the internet.

- Advanced AI Voice Recognition – Expanding command processing capabilities.

- IoT Cloud Integration – Real-time monitoring and analytics.


