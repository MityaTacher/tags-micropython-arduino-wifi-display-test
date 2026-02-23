# MicroPython Arduino WiFi Display Test

Simple testing utility for ESP32/ESP8266 boards with SSD1306 OLED displays. 
Designed for rapid prototyping of WiFi signal strength visualization.

## Hardware Requirements
* ESP32-WROOM-32 or NodeMCU (ESP8266)
* I2C OLED Display (SSD1306 128x64)
* MicroPython Firmware v1.19.1+

## Quick Start
1. Flash your device with MicroPython.
2. Upload `main.py` and `display_utils.py` to the board.
3. Configure `wifi_config.py` with your credentials.
