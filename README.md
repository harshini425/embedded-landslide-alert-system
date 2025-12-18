Embedded Landslide & Thunder Detection System
Overview

This project is a simulation-based embedded system designed on Wokwi using ESP32. It detects early signs of landslides and thunder (storm) conditions using environmental sensors and sends timely alerts based on threshold logic.

Objective

To build a low-cost embedded system that monitors landslide-related parameters and thunder occurrences, providing alerts for potential hazards.

System Components (Simulated)

ESP32 Development Board (simulated on Wokwi)

Soil Moisture Sensor

Vibration Sensor

Sound/Thunder detection logic (simulated)

Buzzer / Alert Module

(Optional) IoT platform for alerts

Working Principle

The ESP32 reads sensor data (soil moisture, vibration, audio input for thunder). When sensor values cross pre-defined thresholds (indicating heavy rain, vibration, or thunder), the system marks a risk event and triggers an alert output.

Tools Used

Arduino IDE (with ESP32 support)

Wokwi Simulator

Embedded C / Arduino framework

Project Status

Simulation is completed using Wokwi. Hardware implementation with real sensors is planned for future work.

Future Improvements

Integrate real thunder detection hardware

Add GNSS for location tagging during alerts

Use low-power modes for battery operation

Cloud integration for remote monitoring
## 🔗 Project Simulation Link

- **Wokwi Simulation**: https://wokwi.com/projects/450599241020176385
## 🧪 Simulation Results

Simulation screenshots are available in the [`simulation`](./simulation) folder.

