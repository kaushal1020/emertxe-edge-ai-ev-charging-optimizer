# Edge AI Based Smart EV Charging Station Optimizer

**Emertxe IoT Internship 2026 — Individual Project**

## Project Overview

The Edge AI Based Smart EV Charging Station Optimizer is an IoT-based project developed as part of the Emertxe IoT Internship 2026.

The project focuses on monitoring and optimizing electric vehicle charging across three charging bays. It uses ESP32 controllers, Edge AI, MQTT communication, and the ThingsBoard platform to monitor charging parameters, estimate charging demand, and support intelligent charging decisions.

The system combines local processing on the ESP32 with cloud-based monitoring and visualization through ThingsBoard.

## Project Objectives

- Monitor voltage, current, temperature, and power-related parameters across three charging bays.
- Use Edge AI to estimate EV arrival probability and charging duration.
- Optimize charging decisions according to charging demand and station load.
- Support charging decisions such as ALLOW, THROTTLE, and DEFER.
- Send telemetry to ThingsBoard using MQTT.
- Provide real-time monitoring, historical data visualization, and alarms through a dashboard.
- Support remote monitoring and control of the charging system.

## Key Features

- **Three Charging Bays:** Monitors three EV charging bays.
- **ESP32-Based Monitoring:** Collects charging and sensor data.
- **Edge AI:** Estimates EV arrival probability and expected charging duration.
- **Smart Load Optimization:** Adjusts charging decisions based on station conditions.
- **Charging Decisions:** Supports ALLOW, THROTTLE, and DEFER decisions.
- **MQTT Communication:** Transfers telemetry between the ESP32 devices and ThingsBoard.
- **ThingsBoard Dashboard:** Displays charging data and station status.
- **Alarm Monitoring:** Supports alerts for configured abnormal conditions.
- **Remote Control:** Supports dashboard-based control where configured.

## Technologies Used

| Technology | Purpose |
|---|---|
| ESP32 | Embedded processing and device control |
| C/C++ | ESP32 firmware development |
| Edge AI | Local prediction and charging optimization |
| MQTT | Communication between devices and the platform |
| ThingsBoard | Telemetry visualization, dashboards, and alarms |
| Wokwi | Hardware simulation and testing |
| Python | AI model development and supporting analysis |
| PlatformIO / Arduino IDE | Firmware development and uploading |

## System Architecture

The system follows an IoT-based architecture in which the ESP32 handles local monitoring and Edge AI processing, while ThingsBoard provides cloud-based visualization and monitoring.

### Data Flow

1. **Sensors and Inputs:** Collect or simulate charging parameters and bay status.
2. **ESP32 Controller:** Reads inputs and processes charging-related data.
3. **Edge AI and Optimization:** Estimates charging demand and helps determine charging decisions.
4. **Wi-Fi and MQTT:** Transmits telemetry to ThingsBoard.
5. **ThingsBoard Dashboard:** Displays bay status, charging parameters, station-level information, and configured alarms.

### Architecture Diagram

Sensors / Inputs  
↓  
ESP32 Controller  
↓  
Edge AI + Smart Load Optimization  
↓  
Wi-Fi + MQTT  
↓  
ThingsBoard Dashboard

*Note: The architecture description should reflect the actual implementation and whether testing was performed in simulation or on physical hardware.*

## Project Information

- **Project Title:** Edge AI Based Smart EV Charging Station Optimizer
- **Project Type:** Individual IoT Internship Project
- **Internship:** Emertxe IoT Internship 2026
- **Internship Period:** 10 August 2026 – 16 September 2026
- **Author:** Kaushal Kumar
- **Department:** Electronics and Communication Engineering (ECE)
- **Institution:** Madan Mohan Malaviya University of Technology (MMMUT)

## Future Improvements

- Improve the accuracy of charging demand predictions.
- Enhance station-level load optimization.
- Add more detailed historical analysis.
- Expand monitoring and testing under different simulated charging conditions.

## Project Status

The project documentation and implementation details will be updated as the repository is organized and verified.

## License

No license has been specified for this repository yet.
