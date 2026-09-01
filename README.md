# Dual-Axis Light-Tracking Solar Panel

## Overview

The **Dual-Axis Light-Tracking Solar Panel** is a smart solar-energy system designed to maximize power generation by automatically adjusting the orientation of a solar panel according to the direction of maximum sunlight.

Developed under the **Robotics Club**, this project uses light sensors and motorized movement to keep the solar panel optimally aligned with the sun throughout the day.

## Project Principle

The system works on the principle of keeping the **solar panel surface as perpendicular as possible to incoming sunlight**. This allows the panel to receive maximum solar radiation and improve energy generation.

## How It Works

The system consists of **four Light Dependent Resistors (LDRs)** placed around the solar panel to detect differences in light intensity.

### 1. Light Sensing

Four LDR sensors measure the intensity of sunlight at different positions around the panel.

### 2. Data Processing

The variation in LDR readings is analyzed by the controller to determine the direction in which the panel should move.

### 3. Movement Adjustment

Motors adjust the panel's orientation based on the difference in light intensity between the sensors.

### 4. Dual-Axis Tracking

The mechanism allows the solar panel to move along **two axes**, enabling it to track the sun's changing position throughout the day and across different seasons.

## Key Features

* **Dual-axis solar tracking**
* **Four-LDR light sensing system**
* Automatic panel orientation
* Real-time adjustment according to sunlight
* Improved solar energy collection
* Simple and efficient mechanical design
* Suitable for experimental and educational applications

## Why It Matters

### Enhanced Efficiency

Keeping the panel aligned with the strongest sunlight can increase the amount of solar energy received compared with a fixed panel orientation.

### Adaptability

The dual-axis mechanism can accommodate changes in the sun's position throughout the day and across seasons.

### User-Friendly Design

The system provides automatic tracking without requiring continuous manual adjustment.

## Limitations

* **Higher Initial Cost:** Sensors, motors, and additional mechanical components increase the overall setup cost.
* **Regular Maintenance:** Moving mechanical components require periodic inspection and maintenance.
* **Energy Consumption:** The tracking mechanism itself consumes a small amount of electrical energy.
* **Weather Dependency:** Tracking provides less benefit when sunlight is weak or heavily diffused by clouds.

## System Workflow

```text
Sunlight
   ↓
Four LDR Sensors
   ↓
Light Intensity Comparison
   ↓
Controller
   ↓
Motor Control
   ↓
Dual-Axis Movement
   ↓
Optimal Solar Panel Orientation
   ↓
Maximum Sunlight Exposure
```

## Project Structure

```text
Dual-Axis-Light-Tracking-Solar-Panel/
│
├── CAD/
│   ├── Mechanical Components/
│   └── Assembly/
│
├── Electronics/
│   └── Circuit and Wiring/
│
├── Code/
│   └── Solar Tracker Code/
│
├── Images/
│   └── Project Photos/
│
├── BOM/
│   └── Bill of Materials/
│
└── README.md
```

## Applications

This project can be used for:

* Solar-energy experiments
* Engineering and robotics projects
* Educational demonstrations
* Renewable-energy research
* Automated solar-panel systems

## Future Improvements

* Integration of **IoT-based monitoring**
* Real-time power generation monitoring
* Automatic fault detection
* Weather-based tracking optimization
* Improved mechanical stability
* Low-power motor-control algorithms

## Conclusion

The **Dual-Axis Light-Tracking Solar Panel** demonstrates how sensors, electronics, mechanical systems, and automation can be combined to improve solar-energy utilization. By continuously adjusting the panel toward the strongest available sunlight, the system provides an efficient and practical approach to automated solar tracking.

---

### Developed Under

**Robotics Club**
**Dual-Axis Light-Tracking Solar Panel Project**
