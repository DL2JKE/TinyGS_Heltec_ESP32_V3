# Source / Purpose

This is a fork of [TinGS](https://github.com/G4lile0/tinyGS).

In branch 'heltec_V3' support for [Heltec ESP32 LoRa Wifi](https://heltec.org/project/wifi-lora-32-v3/) has been added

# Changes

Changes (after fixing the problem between keyboard and chair):
- Switched to Espressif 6.3.0 toolkit/platform (to support ESP32s3 chips)
- Added the 433-510MHz and 863-870MHz boards to the configuration.

# Hints

- In contrast to RadioLib recommendation (error code -707), the XTAL must be provided with voltage (hence 1.6f in board configuration).
- The board's WiFi receiver easily goes into saturation (needs a distance of appx 4m to the WiFi-AP; learned the hard way).

# License

This program is licensed under GPL-3.0
