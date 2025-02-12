# NovaFusion        
###### V1.0
NovaFusion is a IoT app for Arduino and ESP32.
---------------------------------------------------------------------------------------------------------------------------------------------------------------
NovaFusion is an intelligent macOS IoT application designed to seamlessly control and monitor your connected devices. Whether you're adjusting LED brightness, customizing vibrant NeoPixel lighting, or keeping track of ambient conditions, NovaFusion provides an intuitive and powerful dashboard for your IoT setup.

### 🌟 Features:

✅ LED Controller – Adjust brightness and toggle LEDs on/off with precision.

✅ NeoPixel Control – Customize RGB lighting with full color control.

✅ Ambient Monitor – Track real-time temperature and light intensity for smarter automation.

✅ Wi-Fi Connectivity – Communicates effortlessly with Arduino-compatible boards via Wi-Fi

---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🟠 Get started

Before using NovaFusion, follow these steps to ensure compatibility and a smooth setup:

1️⃣ **Check Compatibility**
Read this entire README file to verify that your laptop and board are compatible with NovaFusion.
If your device is compatible, proceed to the next step.

2️⃣ **Download the NovaFusion App**
Go to the Releases section on GitHub and download the latest version of the NovaFusion app.
After downloading, open the .dmg file and drag NovaFusion.app into the Applications folder.

3️⃣ **Allow NovaFusion to Run (Mac Users Only)**
Since NovaFusion is not signed by an identified Apple developer, macOS will block it by default. To allow it:
Open System Settings → Privacy & Security.
Scroll to the bottom and find the message:
***"NovaFusion was blocked from use because it is not from an identified developer."
Click Open Anyway to allow the app to run.***

4️⃣ **Upload Code to Your Board**
Download the Arduino or ESP32 code package from the Downloads section below.
Open Arduino IDE and upload the code to your board.

5️⃣ **Follow the Setup Guide**
Download the setup guide text file from the Downloads section.
This file contains step-by-step instructions for setting up your IoT project and hardware components.


---------------------------------------------------------------------------------------------------------------------------------------------------------------

## ⚠️ IMPORTANT (Please read this before proceeding to the next step) ⚠️
If you're using an Arduino board, especially the Arduino Uno R4 WiFi, make sure to use a 1KΩ resistor or higher when connecting an LED diode.

Using a lower resistance resistor ****(e.g., 470Ω or less)**** may exceed the board’s safe current limits, potentially ****damaging the I/O pin or the microcontroller itself.****

Why is this important?

The ****Arduino Uno R4 WiFi**** can ****safely provide up to 8mA per GPIO pin.****
****A typical LED can draw 16mA - 20mA****, which is ****more than double the safe limit if no proper resistor is used.****
Using a ****higher resistor value (e.g., 1KΩ or more) reduces the current and increases your board’s lifespan.****
******This precaution is recommended for all Arduino & ESP32 boards to prevent damage and ensure long-term stability.*******

## ⚠️ ********Disclaimer: We are not responsible for any damages to your board or components. By following this guide, you acknowledge that improper wiring or resistor selection may cause damage, and you take full responsibility for your hardware.⚠️********

---------------------------------------------------------------------------------------------------------------------------------------------------------------
### 🔴 Libraries required for the arduino code

For your code to work you need to download these libraries:
#### Arduino
1. WiFiS3
2. Adafruit Neopixel
3. DHT
#### ESP32
1. WiFi
2. Adafruit Neopixel
3. DHT

---------------------------------------------------------------------------------------------------------------------------------------------------------------

### 🟡 Supported Boards:
#### Arduino (Download Arduino Package for Arduino)
1. Arduino Uno R4 WiFi
2. Arduino MKR WiFi 1010
#### ESP32 (Download ESP32 Package for ESP32)
1. ESP32-WROOM-32
2. ESP32-WROVER
3. ESP32-S3
4. ESP32-C3
5. ESP32-Mini
6. ESP32-DevKit V1

_______________________________________________________________________________________________________________________________________________________________

### 🔵 Mac Compatibility
#### MacOS
NovaFusion requires **MacOS 13.0(Ventura) or later**.
#### Processor
NovaFusion requires a **Intel** or a **Apple Silicon Chip** 

--------------------------------------------------------------------------------------------------------------------------------------------------------------
#### NovaFusion is the perfect companion for makers, home automation enthusiasts, and developers looking for an all-in-one IoT control solution! Stay Tuned for latest updates!!
