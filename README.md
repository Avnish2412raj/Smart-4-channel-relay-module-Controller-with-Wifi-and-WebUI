# ESP8266 Relay Control Web Server

This project allows you to control 4 relays connected to an ESP8266 via a Wi-Fi hotspot and a web interface.

## Features
- ESP8266 SoftAP mode (no internet required)
- Responsive HTML interface
- Control 4 relays (ON/OFF)
- Modern UI with dark theme
- Works offline via hotspot (captive portal style)

## Hardware Required
- ESP8266 (NodeMCU or Wemos D1 Mini)
- 4-channel relay module
- Power supply
- Jumper wires

## Installation
1. Open `relay_control.ino` in Arduino IDE.
2. Install required libraries:
   - `ESP8266WiFi`
   - `DNSServer`
   - `EEPROM`
3. Select correct board and port.
4. Upload the code.

## Usage
- ESP creates a Wi-Fi network (default: `ESP01`, password: `12345678`).
- Connect your phone/laptop to it.
- Open browser and go to `192.168.4.1`
- Control the relays from the web interface.

## License
MIT License - Free to use for personal or commercial purposes.
