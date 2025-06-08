# HOME-AUTOMATION-WITH-BLUETOOTH #
cription
# API Integration and Data Visualization

## Developer Information
*Name:* A.sudheer kumar reddy 
*Company:* CODTECH IT SOLUTIONS    
*ID:*  :CT08DM1081 
*Domain:* PYTHON PROGRAMMING  
*Duration:* 11th may to 12th Julyh 

---

A solution to control home appliances using a Bluetooth device (an Android smartphone).

This repository consists of source code for an Android app as well as Arduino configuration.

Requirements
Before you begin, ensure you have the following:

Arduino development board
HC-05 or HC-06 Bluetooth module
5V DC / 220V AC relays
Android Bluetooth device
Connecting wires.
Steps to set up Arduino
Complete the following steps to set up Arduino. You can use the Arduino documentation for reference:

Upload the Arduino code in the repository root for the Arduino controller
Connect PIN 11(TX) pin of Arduino to RX pin of HC-05
Connect PIN 10(RX) pin of Arduino to TX pin of HC-05
Connect 5V of Arduino to Vin of HC-05 and Vcc of relays
Connect GND of Arduino to GND of HC-05 and GND of relays
Connect IN of relay to PIN 13 of Arduino board(you are free to use any pin and also multiple pins, just update the arduino code)
Connect 220V AC Line to Pole and Load(appliance) to NO of the relay
Power the Arduino board and you're ready to use. Refer to circuit diagram for setup:
Circuit Diagram
Circuit diagram

How to use
Build and install the app on an Android Bluetooth device.
Turn Bluetooth ON and pair with HC-05 using the default passcode '1234' (Feel free to change this).
Open the app, click on select controller and select the HC-05
Use ON/OFF buttons to control the appliance.
Purpose
Mini Project for Bachelor of Technology, CVR College of Engineering, Hyderabad

Android Application
Features

Send Signals via Bluetooth.
List of Available Devices.
Switch On/Off any devices.
Tools

Shared Preferences
Bluetooth Socket
File
Media Store
URI
License
