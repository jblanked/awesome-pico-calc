# Getting Started with Pico Calc 
Welcome to the Pico Calc Getting Started guide! This document will help you set up your Pico Calc device.

## What is Pico Calc?
Pico Calc is a versatile handheld device based on the Raspberry Pi Pico and is designed for various applications, including programming, gaming, and media playback. It features a powerful microcontroller and supports multiple programming languages and SDKs. Read more about it here: https://www.clockworkpi.com/picocalc

## Updating The STM322
This is critical to ensure your Pico Calc runs smoothly. Follow these steps to update the STM322 firmware.

Here's a video guide for visual assistance: [YouTube Video](https://www.youtube.com/watch?v=zD3XbYQG6cM&pp=ygUIamJsYW5rZWQ%3D).

### Steps to Update STM322
1. Open the back of the PicoCalc carefully
2. Turn on switch 1 (SW107) (just below the SD-card)
3. Connect USB-C to the Computer
4. Hold power button to turn on PicoCalc
5. Start STM32CubeProgrammer (https://www.st.com/en/development-tools/stm32cubeprog.html) on the computer
6. Select “UART” (light blue drop-down at the top right)
7. Press “Connect” (green button at the top right)
8. Press tab “Open file” and select “PicoCalc_BIOS_v1.2.bin” (https://github.com/clockworkpi/PicoCalc/tree/master)
9. Press “Download” button

## Flashing New Firmware
Custom firmware can enhance the functionality of your Pico Calc. You can flash new firmware to add features or update existing ones.

Here's a video guide for visual assistance: [YouTube Video](https://www.youtube.com/watch?v=O-EXSRHOsfQ&pp=ygUIamJsYW5rZWQ%3D).

### Steps to Flash New Firmware
1. Download the firmware file you want to flash.
2. Put your Pico Calc into bootloader mode by holding down the BOOTSEL button while connecting it to the USB port.
3. Your computer should recognize the Pico Calc as a mass storage device.
4. Copy the firmware file to the root directory of the Pico Calc.
5. Eject the Pico Calc from your computer and restart it.
