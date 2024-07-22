# Smart Glow - Automatic Street Lights System

Smart Glow is an IoT-based street lights control system using NodeMCU ESP8266. It allows users to control street lights automatically or manually through an Android application.

## Features
- **Automatic Mode**: Intelligent street light control based on ambient light and human presence.
- **Manual Mode**: Manual control of LEDs via the Android app.
- **Real-time Status Display**: 
  - Mode status (Automatic/Manual)
  - Day/Night status based on LDR readings
  - LED status based on PIR sensor and user control
- **Firebase Integration**: Data logging using Google Firebase Realtime Database.

## Hardware Setup
- **LDR**: Connect to analog pin A0 for light sensing.
- **PIR Sensor**: Connect to digital pin D2 for human presence detection.
- **LED**: Connect to digital pin D1 for street lighting.
  ![Reference circuit](SmartGlow-mini-project/Reference circuit.png)

## Software Setup
1. **Arduino Code**: Upload the `SmartGlow.ino` file to your NodeMCU ESP8266.
2. **Android App**: Use the provided Android app for manual control and real-time status display.
3. **Firebase**: Configure your Firebase Realtime Database using the provided `firebase_config.json`.

## Directory Structure
- `AndroidApp/`: Source code for the Android application.
- `ESP8266_Code/`: Arduino code and necessary libraries.
- `Hardware_Schematics/`: Hardware schematics and components list.
- `Firebase/`: Firebase configuration file.

## Getting Started
1. Clone this repository.
2. Follow the hardware setup instructions.
3. Upload the Arduino code to your NodeMCU ESP8266.
4. Install the Android app on your smartphone.
5. Configure Firebase using the provided `firebase_config.json`.
