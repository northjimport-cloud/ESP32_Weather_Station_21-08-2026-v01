## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.. All rights reserved, [northjim] 2026
# ESP32_Weather_Station_21-08-2026-v01
ESP32-based weather station using MicroPython. Reads temperature &amp; humidity from DHT22, displays live data on 128x64 OLED, and sends readings over WiFi. Includes custom KiCad PCB with USB-C, AMS1117-3.3V regulator, power/reset switches, and TX/RX status LEDs.
#details
ESP32 Weather Station with OLED & WiFi
A compact IoT sensor node built around the ESP32-WROOM-32. It reads temperature & humidity from a DHT22 sensor, displays real-time data on a 128×64 OLED screen, and syncs readings over WiFi using MicroPython.
🔧 Hardware
ESP32-WROOM-32 (WiFi + Bluetooth)
DHT22 — Temperature & Humidity Sensor
0.96" I2C OLED (SSD1306)
AMS1117-3.3 — Voltage Regulator
USB-C — Power & Programming
Custom KiCad PCB with power/reset switches and TX/RX status LEDs
💻 Software
MicroPython firmware
Reads sensor data every 2 seconds
Displays live readings on OLED
Sends data to a remote server / MQTT / ThingSpeak (configurable)
📡 WiFi Features
Station mode (connects to home WiFi)
Optional AP mode for direct configuration
HTTP POST / MQTT publish for cloud logging
