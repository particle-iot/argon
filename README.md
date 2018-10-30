# Argon

<div align=center><img src="https://github.com/particle-iot/argon/blob/master/images/argon-top.png" ></div>

### Overview

The Argon is a powerful Wi-Fi enabled development board that can act as either a standalone Wi-Fi endpoint or Wi-Fi enabled gateway for Particle Mesh networks. It is based on the Nordic nRF52840 and has built-in battery charging circuitry so it’s easy to connect a Li-Po and deploy your local network in minutes.

The Argon is great for connecting existing projects to the Particle Device Cloud or as a gateway to connect an entire group of local endpoints.

### Features

 * Espressif ESP32-D0WD 2.4Ghz Wi-Fi coprocessor 
  * On-board 4MB flash for ESP32 
  * 802.11 b/g/n support 
  * 802.11 n (2.4 GHz), up to 150 Mbps
 * Nordic Semiconductor nRF52840 SoC 
  * ARM Cortex-M4F 32-bit processor @ 64MHz 
  * 1MB flash, 256KB RAM 
  * IEEE 802.15.4-2006: 250 Kbps 
  * Bluetooth 5: 2 Mbps, 1 Mbps, 500 Kbps, 125 Kbps 
  * Supports DSP instructions, HW accelerated Floating Point Unit (FPU) calculations 
  * ARM TrustZone CryptoCell-310 Cryptographic and security module 
  * Up to +8 dBm TX power (down to -20 dBm in 4 dB steps) 
  * NFC-A tag
 * On-board additional 2MB SPI flash
 * 20 mixed signal GPIO (6 x Analog, 8 x PWM), UART, I2C, SPI
 * Micro USB 2.0 full speed (12 Mbps)
 * Integrated Li-Po charging and battery connector
 * JTAG (SWD) Connector
 * RGB status LED
 * Reset and Mode buttons
 * On-board PCB antenna
 * u.FL connector for external antenna
 * Meets the Adafruit Feather [specification](https://learn.adafruit.com/adafruit-feather/feather-specification) in dimensions and pinout
 * FCC, CE and IC certified
 * RoHS compliant (lead-free)

### Structure of this repository:
 - /eagle
     + Contains the schematic and PCB files in the Eagle file format
 - /gerbers
     + Contains the manufacturing gerber files for the board
 - /datasheets
     + Contains the relevant datasheets of the components used on the Argon
 - /pdfs
     + Contains schematic files in PDF 

### Hardware datasheet

The complete datasheet for the Argon is available [here.](https://docs.particle.io/datasheets/wi-fi/argon-datasheet/)
