# STEP DETECTION AND AUTOMATIC BRAKE INTERLOCK SYSTEM

## 🚍 Project Overview

The Step Detection and Automatic Brake Interlock System is a safety system designed for buses to prevent the vehicle from moving while a passenger is boarding or leaving through the steps.

The system uses IR sensors to detect passengers near the bus steps. An Arduino UNO processes the sensor signals and controls a servo-based braking mechanism. When a passenger is detected on the steps, the system activates the brake interlock and prevents the bus motor from operating.

## 🎯 Objectives

- Detect passengers on the bus steps automatically.
- Prevent the bus from moving while a passenger is boarding or leaving.
- Automatically activate the brake mechanism.
- Provide LED and buzzer warnings.
- Improve passenger safety.
- Develop a low-cost prototype using easily available components.

## ⚙️ Main Components

| Component | Quantity |
|---|---:|
| Arduino UNO | 1 |
| IR Obstacle Sensor | 2 |
| L298N Motor Driver | 1 |
| Servo Motor (SG90) | 1 |
| DC Geared Motor | 1 |
| 12V Battery | 1 |
| LED & Buzzer | 1 set |
| Switches | 2 |
| Wheels | 4 |
| Wires & Breadboard | 1 set |

## 🔄 Working Principle

1. A passenger approaches the bus step.
2. The step IR sensor detects the passenger.
3. The Arduino receives the sensor signal.
4. The LED and buzzer provide a warning.
5. The servo motor operates the brake mechanism.
6. The motor is stopped/interlocked.
7. When the passenger clears the step area, the sensor resets.
8. The brake is released and the bus can move.

## 🧠 Control System

**IR Sensors → Arduino UNO → Motor Driver / Servo Motor → Brake & Motor
