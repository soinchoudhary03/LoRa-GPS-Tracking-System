
# LoRa-Based GPS Tracking System

## Project Overview

A motion-triggered GPS tracking system developed using an FMD microcontroller, BMA400 accelerometer, GPS module, and LoRa communication.

The system detects motion, acquires GPS information, and transmits tracking data wirelessly through LoRa.

## Technologies Used

- Programming: Embedded C
- Microcontroller: FMD MCU
- Motion Sensor: BMA400
- Positioning: GPS
- Wireless Communication: LoRa
- Interfaces: UART, I2C, SPI
- External Storage: SPI Flash

## System Architecture

1. BMA400 detects motion using an interrupt.
2. The MCU wakes up from low-power mode.
3. GPS data is acquired through UART.
4. GPS messages are buffered and processed.
5. Tracking packets are transmitted through LoRa.
6. ACK/NACK handling manages communication reliability.
7. Tracking data is stored in external SPI Flash.

## Key Features

- Motion-triggered tracking
- GPS data acquisition
- Wireless LoRa communication
- ACK/NACK-based communication handling
- Retransmission up to 5 attempts
- 200 ms ACK timeout
- External SPI Flash data storage
- Low-power operation

## My Contribution

During my embedded systems internship, I worked on:

- Transmitter and receiver firmware development.
- BMA400 I2C interrupt integration.
- GPS data acquisition through UART.
- GPS message buffering and packet formation.
- LoRa data transmission.
- ACK/NACK handling and retransmission logic.
- External SPI Flash integration.

## Applications

- Asset tracking
- Remote monitoring
- Location tracking systems
- Low-power IoT applications

## Project Status

Firmware development experience gained during a 6-month embedded systems internship at Orient Softpro.

---

**Developer:** Mohd Soin  
**Role:** Embedded Firmware Engineer
