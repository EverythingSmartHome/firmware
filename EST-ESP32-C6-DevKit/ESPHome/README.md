# EST-ESP32-C6-DevKit
These are some ESPHome example configurations for the EST-ESP32-C6-DevKit, an [ESP32-C6 based DevKit](https://shop.everythingsmart.io/products/est-esp32-c6-devkit-esp32-c6-development-kit)

Please note, at the time of writing, ESPHome web flasher doesn't support flashing the ESP32-C6 over cable (it doesn't recognise the ESP32-C6 as a board) - you need to compile the firmware in ESPHome and chose the manual download option, then flash the board using esptool.py. Once the initial firmware is loaded, ESPHome web flasher is able to flash over WiFi/OTA.

* [est-esp32-c6-all-gpios](est-esp32-c6-all-gpios.yaml) - a simple example all of the GPIO's configured as outputs (switches) and inputs (binary sensors)
