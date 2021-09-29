<h1 align = "center">🌟LILYGO T-OI-PLUS🌟</h1>

## **English | [中文](./README_CN.MD)**

## New version
**The new version has fixed the glitch that caused crystal burrs to start wifi and ble reset**

<h3 align = "left">Quick start:</h3>

1. Install the current upstream Arduino IDE at the 1.8 level or later. The current version is at the [Arduino website](http://www.arduino.cc/en/main/software).
2. Start Arduino and open Preferences window. In additional board manager add url: https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json .separating them with commas.
3. Select Tools -> Board -> ESP32C3 Dev Module
4. If you do not have a driver installed, you need to install it (Window:ch341ser2.exe, MAC:ch34x_mac_driver_v1.6.zip)
5. Need to install the following dependencies
     - [Adafruit_NeoPixel](https://github.com/adafruit/Adafruit_NeoPixel)

<h3 align = "left">Product 📷:</h3>

|  Product  |                            Product  Link                            |
| :-------: | :-----------------------------------------------------------------: |
| T-OI-PLUS | [AliExpress](https://www.aliexpress.com/item/1005003348936965.html) |

## Pinout
New version

![](image/new_TOI_Plus.png)

![](image/TOI_Plus.jpg)

## known issues
[Using IDF wifi needs to be put TX power is limited to 12, it will operate normally](https://github.com/espressif/esp-idf/issues/7082)

