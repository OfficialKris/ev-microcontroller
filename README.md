# EV Microcontroller

## Description

The EV Microcontroller is a small, portable, self-contained
processing unit that is capable of reading in sensor data
and outputing that data to a CAN bus. It is meant to be a
robust alternative to a similar unit made of an arduino and 
compatable shields.

## Features

* Low power, shock resistant
* CAN connectivity
* 5 12-bit analog pins
* 10 digital pins
* Micropython support
* RP2040 microprocessor
* Onboard power distribution (3V3, 5V, 12V)
* USB-C port (flash/debug/power/data)
* MicroSD CAN backup
* M2 grounded mounting holes (with vibration dampining)
* Board thermistor
* 9 axis gyroscope
* Highly embedded and compact (30mm x 40mm)
* Electrical protections (overcurrent, undervoltage, etc.)
* Waterproof enclosure
* Other features when paired with other devices (display, etc.)

## Parts

| Type | Part | Description |
|------|------|-------------|
| MCU |RP2040| Microcontroller |
| Power |TCKE805NL,RF| eFuse |
| Power |MAX77540AAWV+| Dual Voltage Regulator |
| Power |FPF3042UCX| Power Source Switch |
| Memory |GD25Q40CEIGR| Flash |
| Memory |MEM2051-00-195-00-A| MicroSD connector |
| Peripherals |TJA1441BTK/0Z| CAN Transceiver |
| Peripherals |MAX19777AZA+T| ADC |
| Peripherals |MC6470| 9-axis IMU |
| Peripherals |NTCG104QH474JT1| Board thermistor |
| Connectors |USB4105-GF-A| USB C Receptacle |
| Connectors |B20B-PHDSS(LF)(SN)| 20 pin JST Connector |
| Oscillator |DSC1001DI1-020.0000| 20Mhz oscillator |
