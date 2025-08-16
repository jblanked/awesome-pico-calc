# Getting Started with PicoCalc 
Welcome to the PicoCalc Getting Started guide! This document will help you set up your PicoCalc device.

## What is PicoCalc?
PicoCalc is a versatile handheld device based on the Raspberry Pi Pico and is designed for various applications, including programming, gaming, and media playback. It features a powerful microcontroller and supports multiple programming languages and SDKs. Read more about it here: https://www.clockworkpi.com/picocalc

## Updating The STM32
This is critical to ensure your PicoCalc runs smoothly. Follow these steps to update the STM32 firmware.

Here's a video guide for visual assistance: [YouTube Video](https://www.youtube.com/watch?v=zD3XbYQG6cM&pp=ygUIamJsYW5rZWQ%3D).

### Steps to Update STM32
1. Open the back of the PicoCalc carefully
2. Turn on switch 1 (SW107) (just below the SD-card)
3. Connect USB-C to the Computer
4. Hold power button to turn on PicoCalc
5. Start STM32CubeProgrammer (https://www.st.com/en/development-tools/stm32cubeprog.html) on the computer
6. Select `UART` (light blue drop-down at the top right)
7. Press “Connect” (green button at the top right)
8. Press tab `Open file` and select `PicoCalc_BIOS_v1.4.bin` (Download from https://github.com/clockworkpi/PicoCalc/tree/master/Bin)
9. Press “Download” button

## Flashing New Firmware
Custom firmware can enhance the functionality of your PicoCalc. You can flash new firmware to add features or update existing ones.

Here's a video guide for visual assistance: [YouTube Video](https://www.youtube.com/watch?v=O-EXSRHOsfQ&pp=ygUIamJsYW5rZWQ%3D).
Sure! Here's the clean version:

---

### Steps to Flash New Firmware

1. **Download** the firmware file you want to flash.

2. **Put your PicoCalc into bootloader mode:**

   * Connect the micro-USB cable to your computer.
   * While holding down the **BOOTSEL** button on the Raspberry Pi Pico inside your PicoCalc, connect the other end of the cable to your **Raspberry Pi Pico**.

     > 💡 *Beginner Tip:* You don’t need to open the back of the PicoCalc to reach the BOOTSEL button. Use something small and non-metallic—like a wooden toothpick—to press the button through the hole on the back.

3. **Wait for your computer to recognize** the PicoCalc as a mass storage device (it will appear like a USB drive).

4. **Copy** the firmware file to the root directory of the PicoCalc (just drag and drop the file into the drive).

5. **Eject** the PicoCalc from your computer safely, then unplug and power it on to restart with the new firmware.

---
