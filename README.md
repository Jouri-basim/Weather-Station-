# Weather Station Project

## Overview

This project is designed to create a weather station that collects and displays real-time weather data, including temperature, humidity, and atmospheric pressure. It serves as an efficient, low-cost solution suitable for personal or educational use.

## Features

- **Real-Time Data Display**: Continuously shows updated weather data.
- **Accurate Measurements**: Utilizes reliable sensors for precise readings.
- **User Notifications**: Alerts users about critical weather conditions.
- **User-Friendly Interface**: Simple interface for easy operation.

## Components Used

- **Microcontroller**: Arduino Uno
- **Temperature and Humidity Sensor**: DHT11
- **Barometric Pressure Sensor**: BMP180
- **Display Unit**: 16x2 Character LCD
- **Connecting Wires**: Jumper Wires
- **Power Supply**: USB Power Source
- **Breadboard**: For building and testing circuits

  ## Hardware and Software Requirements

### Hardware Requirements

| Component                        | Specifications                       |
|----------------------------------|-------------------------------------|
| **Microcontroller**              | Arduino Uno                         |
| **Temperature and Humidity Sensor** | DHT11 Sensor                     |
| **Barometric Pressure Sensor**   | BMP180 Sensor                       |
| **Display Unit**                 | 16x2 Character LCD                 |
| **Breadboard**                   | For building and testing circuits   |
| **Connecting Wires**             | Jumper Wires                        |
| **Power Supply**                 | USB Power Source                    |

### Software Requirements

- **Arduino IDE**: The integrated development environment for programming the Arduino board.
- **Libraries**:
  - `DHT` library for the DHT11 sensor.
  - `Adafruit BMP085 Unified` library for the BMP180 sensor.
  - `LiquidCrystal_I2C` library for the LCD display.

### Installation Instructions

1. Download and install the [Arduino IDE](https://www.arduino.cc/en/software).
2. Install the required libraries through the Library Manager in the Arduino IDE.
3. Clone or download this repository to your local machine.
4. Open the project file in the Arduino IDE and upload the code to your Arduino board.

## Installation and Setup

1. Connect all the components according to the circuit diagram.
2. Install the required libraries in the Arduino IDE.
3. Upload the Arduino code to the board using the Arduino IDE.
4. Power the Arduino with a USB cable.
5. Test the system to ensure it displays the correct weather data.

## How It Works

- The sensors collect weather data.
- The microcontroller processes the data.
- The LCD displays the current weather conditions.
- Alerts are sent for critical weather conditions.

## Usage

- Turn on the system using the power supply.
- Monitor the displayed weather data on the LCD.
- Receive alerts for any critical weather changes.

## Future Improvements

- Adding wireless connectivity (Wi-Fi or Bluetooth) for remote monitoring.
- Implementing data logging for historical data analysis.
- Utilizing more sensitive sensors for better detection.

  ## Applications

The weather station can be used in various environments, including:

- **Homes and Apartments**: 
  - Provides residents with real-time weather updates, helping them make informed decisions about daily activities and home maintenance.
  
- **Offices**: 
  - Enhances workplace comfort by monitoring indoor climate conditions, which can improve employee productivity and well-being.
  
- **Small Warehouses**: 
  - Monitors environmental conditions to ensure that stored goods are kept in optimal conditions, reducing the risk of spoilage or damage.
  
- **Classrooms or Labs**: 
  - Serves as an educational tool for students to learn about meteorology and data collection, while also maintaining a comfortable learning environment.
