# Smart Bilirubin Detector

## Overview

The Smart Bilirubin Detector is a low-cost, non-invasive system designed to estimate bilirubin levels for early detection of jaundice in newborns and adults. The project combines optical sensing, machine learning, and embedded systems to provide rapid bilirubin assessment without the need for invasive blood sampling.

## Problem Statement

Traditional bilirubin measurement requires blood tests, which can be painful, time-consuming, and expensive. Many healthcare facilities, especially in rural areas, lack access to advanced diagnostic equipment.

This project aims to provide a portable, affordable, and user-friendly alternative for preliminary jaundice screening.

## Features

- Non-invasive bilirubin estimation
- Real-time measurement and analysis
- Machine Learning based prediction model
- Portable and low-cost design
- OLED display for instant results
- Skin tone compensation for improved accuracy
- Suitable for neonatal and adult jaundice screening
- Expandable with Bluetooth connectivity for mobile monitoring

## System Architecture

1. Optical sensors capture reflected light from the skin.
2. Sensor data is processed by the microcontroller.
3. Machine Learning model predicts bilirubin concentration.
4. Results are displayed on the OLED screen.
5. Data can be stored or transmitted for further analysis.

## Technologies Used

### Hardware
- ESP32 Microcontroller
- RGB Color Sensor
- Photodiodes
- OLED Display
- Power Management Circuit

### Software
- Python
- Machine Learning
- PlatformIO
- Embedded C/C++
- Data Processing Algorithms

## Machine Learning Model

The project utilizes a trained machine learning model to estimate bilirubin levels based on sensor readings.

Model Features:
- Sensor value preprocessing
- Feature extraction
- Bilirubin prediction
- Risk classification

## Repository Structure

```text
src/        - Source code
include/    - Header files
lib/        - Libraries
test/       - Test files
README.md   - Project documentation
