# overhead-wire-breakage-detection
ESP32-based overhead wire breakage detection and automatic power cut-off system using a load cell and HX711.

# Overhead Wire Breakage Detection and Automatic Power Cut-Off System

## About the Project
This project detects a reduction in wire tension and triggers an automatic power cut-off to improve electrical safety.

## Objectives
- Monitor wire tension using a load cell.
- Process sensor readings using the HX711 and ESP32.
- Activate a relay when the tension falls below a set threshold.
- Indicate the system status using LEDs.

## Components Used
- ESP32
- Load Cell
- HX711 Amplifier Module
- Relay Module
- Logic Convertor
- Red and Green LEDs
- Push Button
- Regulated 5V Power Supply

## Working Principle
1. The load cell measures the applied tension.
2. The HX711 amplifies and digitizes the sensor signal.
3. The ESP32 compares the measured value with a predefined threshold.
4. When a low-tension condition is detected, the controller triggers the relay and status indicators.

## Technologies
- ESP32 | Sensors | Electrical Safety

## Project Status
- A complete Prototype 

## Author
Tanishka V.  
B.Tech Electrical and Electronics Engineering
