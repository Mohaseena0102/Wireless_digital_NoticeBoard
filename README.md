# Wireless Digital Notice Board
### AIM: The main aim of this project is to replace traditional physical notice boards with a dynamic, remotely updatable digital display. The project utilizes the LPC2148 microcontroller, interfacing with a dot matrix LED display to show messages such as announcements, alerts, or notices. The system operates wirelessly via Bluetooth communication, allowing users to update the displayed content from a mobile device.

## Block diagram: 



<img width="724" height="450" alt="Screenshot 2025-09-05 221950" src="https://github.com/user-attachments/assets/c2dedc23-3bd8-40e0-8fa6-71cc32de1d06" />

## HARDWRAE REQUIREMENTS
* LPC2148
* 4 - 8x8 DOT MATRIX DISPLAYS
* 74HC573 (LATCH)
* 74HC164 (SHIFT REGISTER)
* AT24C256 (EEPROM)
* HC-05 BLUETOOTH MODULE
* DB-9 CABLE/USB-UART CONVERTER

## SOFTWARE REQUIREMENTS
* KEIL C Compiler
* PROGRAMMING IN EMBEDDED C
* Flash Magic
## Features
1. #### Dynamic Digital Display:The system uses a dot matrix LED display to show messages, announcements, and notices.
2. Wireless Updation: The display can be updated remotely using Bluetooth communication from a mobile device.
3. Microcontroller-based: The project utilizes the LPC2148 microcontroller for processing and controlling the display.
4. Multiple Display Support: The system can support multiple 8x8 dot matrix displays (4 in this case).
5. Data Storage: The system uses an EEPROM (AT24C256) for storing data.
6. User-friendly Interface: The system allows users to update the displayed content wirelessly using a mobile device.

