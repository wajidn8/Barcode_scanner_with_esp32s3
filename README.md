# ESP32-S3 USB Barcode Scanner using ESP-IDF

A barcode scanner project built using **ESP32-S3** in **ESP-IDF framework**.  
The scanner is connected through **USB D+ and D- pins**, and decoded barcode data is printed to the **serial monitor**.

## Features
- USB barcode scanner interface
- ESP32-S3 support
- ESP-IDF framework
- Real-time barcode decoding
- Serial monitor output
- Plug and play USB connection

## Hardware Connections
### Barcode Scanner → ESP32-S3
- D+ → GPIO 20
- D- → GPIO 19
- VCC → External 5V
- GND → Common Ground

ESP32-S3 is connected to PC/laptop through USB.

## Steps to Build and Flash
1. Open ESP-IDF
2. Select target board: ESP32-S3
3. Create/open project
4. Build project
5. Flash to ESP32-S3
6. Open serial monitor

## Output
Decoded barcode data is printed in serial monitor.

Example:
```text
Decoded Barcode: 8901234567890
```

## Applications
- Inventory systems
- POS billing machines
- Smart warehouse
- Embedded automation
- Industrial scanners
