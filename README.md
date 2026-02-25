# 🌆 Smart Street Light & Smart Traffic Management System (IoT Project)

![IoT](https://img.shields.io/badge/Domain-IoT-blue)
![SmartCity](https://img.shields.io/badge/Project-SmartCity-green)
![Security](https://img.shields.io/badge/Security-TLS-red)
![ESP32](https://img.shields.io/badge/Platform-ESP32-orange)

## 📋 Project Overview

A comprehensive IoT-based intelligent system that automates street lighting and dynamically controls traffic management using real-time sensor data, MQTT communication, and cloud integration with security-first approach.

## 🎯 Key Features

- **Smart Street Lighting**: Automatic brightness control based on ambient light and motion detection
- **Adaptive Traffic Management**: Dynamic signal timing based on vehicle density
- **Cloud Integration**: Real-time MQTT-based communication and monitoring
- **Security**: TLS encryption, device authentication, and threat detection
- **Energy Efficient**: Optimized power consumption and intelligent automation
- **Scalable**: Modular architecture for easy expansion

## 🏗️ System Architecture

The system consists of four main layers:

1. **Hardware Layer** - Sensors and actuators (ESP32, LDR, IR sensors)
2. **Firmware Layer** - IoT device logic and control algorithms
3. **Cloud Layer** - MQTT broker, dashboard, and data logging
4. **Security Layer** - TLS encryption, authentication, threat detection

## 📁 Repository Structure

```
Smart-City-IoT-Street-Light-Traffic-System
├── README.md
├── docs/
│   ├── problem_statement.md
│   ├── objectives.md
│   ├── literature_review.md
│   ├── literature_gap.md
│   ├── proposed_system.md
│   ├── challenges.md
│   └── ethical_considerations.md
├── architecture/
│   ├── block_diagram.png
│   ├── layered_architecture.png
│   ├── data_flow_diagram.png
│   └── secure_architecture.png
├── hardware/
│   ├── components_list.md
│   ├── pin_configuration.md
│   ├── street_light_circuit.png
│   └── traffic_system_circuit.png
├── firmware/
│   ├── street_light/
│   │   └── street_light.ino
│   └── traffic_management/
│       └── traffic_control.ino
├── cloud/
│   ├── mqtt_configuration.md
│   └── dashboard_setup.md
├── security/
│   ├── threat_model.md
│   ├── attack_simulation.md
│   └── recovery_strategy.md
├── simulation/
│   ├── tinkercad_link.txt
│   └── screenshots/
└── images/
    ├── system_overview.png
    ├── street_light_demo.jpg
    └── traffic_demo.jpg
```

## 🚀 Getting Started

### Hardware Requirements
- ESP32 Microcontroller
- LDR Sensor
- IR Sensors
- Ultrasonic Sensor
- Traffic Signal LEDs (Red, Yellow, Green)
- Power Supply

### Prerequisites
- Arduino IDE with ESP32 support
- MQTT Broker (HiveMQ, Mosquitto, or Azure IoT Hub)
- Basic knowledge of IoT and embedded systems

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/RishvinReddy/Smart-City-IoT-Street-Light-Traffic-System.git
   cd Smart-City-IoT-Street-Light-Traffic-System
   ```

2. **Configure Hardware**
   - Review `hardware/components_list.md` for required components
   - Follow pin configuration in `hardware/pin_configuration.md`

3. **Upload Firmware**
   - Open `firmware/street_light/street_light.ino` in Arduino IDE
   - Configure WiFi and MQTT credentials
   - Upload to ESP32

4. **Cloud Setup**
   - Configure MQTT broker (see `cloud/mqtt_configuration.md`)
   - Set up dashboard (see `cloud/dashboard_setup.md`)

## 🔐 Security

This project implements industry-standard security measures:
- TLS/SSL encryption for MQTT communication
- Device authentication and authorization
- Threat modeling and attack simulation
- Recovery strategies for security incidents

See `security/` directory for detailed security documentation.

## 📊 System Architecture

### Smart Street Light Module
- LDR for day/night detection
- Motion sensor for intensity control
- Energy optimization logic

### Smart Traffic Module
- IR sensors for vehicle density
- Adaptive traffic timing
- Emergency override

### Cloud Layer
- MQTT communication
- Real-time dashboard
- Data logging

## 📚 Documentation

Complete documentation is available in the `docs/` directory:
- [Problem Statement](docs/problem_statement.md)
- [Objectives](docs/objectives.md)
- [Literature Review](docs/literature_review.md)
- [Literature Gap](docs/literature_gap.md)
- [Proposed System](docs/proposed_system.md)
- [Challenges](docs/challenges.md)
- [Ethical Considerations](docs/ethical_considerations.md)

## 🛠️ Technologies Used

- **Platform**: ESP32 Microcontroller
- **Protocol**: MQTT with TLS
- **Cloud**: Azure IoT Hub / HiveMQ
- **Programming**: Arduino C++
- **Sensors**: LDR, IR Sensors, Ultrasonic Sensor

## 🔬 Testing & Simulation

- Tinkercad simulation available
- Attack simulation scenarios documented
- Unit and integration testing procedures

## 📈 Project Status

**Current Phase**: Development & Documentation

## 🤝 Contributing

Contributions are welcome! Please follow standard GitHub workflow:
1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## 📝 License

This project is open source and available under the MIT License.

## 👤 Author

**Rishvin Reddy**
- GitHub: [@RishvinReddy](https://github.com/RishvinReddy)

## 📧 Contact & Support

For questions or support, please open an issue on GitHub.

## 🙏 Acknowledgments

- IoT and Smart City research community
- MQTT protocol developers
- Open-source security tools and libraries

---

**Last Updated**: 2026-02-25 18:19:37