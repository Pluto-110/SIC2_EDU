The board works with the ESP-IDF extension and PlatformIO extension of VSCode. 

For the PlatformIO extension, use the board Espressif ESP32 Dev Module. platformio.ini looks like the following

; PlatformIO Project Configuration File
;
;   Build options: build flags, source filter
;   Upload options: custom upload port, speed and extra flags
;   Library options: dependencies, extra library storages
;   Advanced options: extra scripting
;
; Please visit documentation for the other options and examples
; https://docs.platformio.org/page/projectconf.html

[env:esp32dev]
platform = espressif32
board = esp32dev
framework = arduino

