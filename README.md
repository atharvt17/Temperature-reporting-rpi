# Weather-reporting-rpi

This is a Raspberry Pi-based weather monitoring system that reads temperature and humidity values from a DHT11 sensor and reports them to Adafruit IO. It also includes an optional feature to send notifications via IFTTT when the temperature exceeds a threshold.

## Prerequisites

To run this project, you will need:

- Raspberry Pi
- DHT11 temperature and humidity sensor
- Python 3 installed on Raspberry Pi
- Adafruit_DHT library
- Adafruit_IO library
- Adafruit IO account
- IFTTT account (optional, for notifications)

## Hardware Setup

1. Connect the DHT11 sensor to the Raspberry Pi's GPIO pin. Make sure to note down the pin number you used.

## Software Setup

1. Install the required libraries:

   ```bash
   pip install Adafruit_DHT Adafruit_IO
