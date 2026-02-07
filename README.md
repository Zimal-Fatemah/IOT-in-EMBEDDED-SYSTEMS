# IOT-in-EMBEDDED-SYSTEMS
# IoT in Embedded Systems

A collection of IoT and embedded systems projects built with ESP32/ESP8266, covering sensor integration, wireless communication protocols, and real-world applications.

## 📁 Projects Overview

### Core IoT Projects

#### **Blind Stick**
Smart assistive device for visually impaired individuals using ultrasonic sensors for obstacle detection.
- Ultrasonic distance measurement
- Alert system (buzzer/vibration)
- Real-time obstacle avoidance

#### **DHT Sensor Integration**
Temperature and humidity monitoring system using DHT11/DHT22 sensors.
- Real-time environmental monitoring
- Data logging capabilities
- Serial output for debugging

#### **WiFi Connectivity**
ESP32/ESP8266 WiFi setup and network communication examples.
- Access Point (AP) mode
- Station (STA) mode
- HTTP server implementation
- Network scanning

### Communication Protocols

#### **Blynk IoT Platform**
Mobile app-controlled IoT device integration using the Blynk platform.
- Remote device control via smartphone
- Real-time sensor data visualization
- Virtual pins configuration
- Cloud-based monitoring

#### **MQTT Broker**
Message Queue Telemetry Transport implementation for lightweight IoT communication.
- Publisher/Subscriber architecture
- Topic-based messaging
- QoS levels implementation
- Connection management

#### **Two Publishers (Twopub)**
Multi-device MQTT communication with two publishing nodes.
- Simultaneous data publishing
- Message synchronization
- Topic hierarchy

#### **Node-RED Integration**
Visual programming for IoT workflow automation.
- Flow-based development
- Dashboard creation
- API integration
- Data processing pipelines

#### **HTML Web Interface**
Custom web-based control panel for IoT devices.
- ESP32 web server
- AJAX for real-time updates
- Responsive design
- Device control interface

### Weekly Lab Assignments

- **Week 4**: Basic sensor interfacing and GPIO control
- **Week 5**: Serial communication and data transmission
- **Week 6**: Advanced networking and protocol implementation
- **Assignment 1 (1252)**: Comprehensive IoT system integration

## 🛠️ Tech Stack

- **Microcontrollers**: ESP32, ESP8266
- **Programming Language**: C++ (Arduino framework)
- **Platforms**: 
  - Arduino IDE
  - PlatformIO
  - Blynk IoT
  - Node-RED
- **Protocols**: 
  - WiFi (802.11)
  - MQTT
  - HTTP/HTTPS
- **Sensors**: 
  - DHT11/DHT22 (Temperature & Humidity)
  - Ultrasonic (HC-SR04)
  - Various GPIO devices

## 🚀 Getting Started

### Prerequisites

1. **Arduino IDE** (version 1.8.x or higher) or **PlatformIO**
2. **ESP32/ESP8266 Board Package** installed
3. Required libraries:
   ```
   - WiFi.h / ESP8266WiFi.h
   - PubSubClient (for MQTT)
   - DHT sensor library
   - Blynk library
   ```

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Zimal-Fatemah/IOT-in-EMBEDDED-SYSTEMS.git
   cd IOT-in-EMBEDDED-SYSTEMS
   ```

2. Install required libraries via Arduino Library Manager:
   - Open Arduino IDE
   - Go to Sketch → Include Library → Manage Libraries
   - Search and install: `DHT sensor library`, `PubSubClient`, `Blynk`

3. Configure WiFi credentials in each project:
   ```cpp
   const char* ssid = "YOUR_WIFI_SSID";
   const char* password = "YOUR_WIFI_PASSWORD";
   ```

4. For MQTT projects, configure broker details:
   ```cpp
   const char* mqtt_server = "YOUR_MQTT_BROKER_IP";
   const int mqtt_port = 1883;
   ```

5. For Blynk projects, add your authentication token:
   ```cpp
   char auth[] = "YOUR_BLYNK_AUTH_TOKEN";
   ```

### Running a Project

1. Open the desired `.ino` file in Arduino IDE
2. Select the correct board: `Tools → Board → ESP32/ESP8266`
3. Select the appropriate port: `Tools → Port`
4. Click **Upload** (→ button)
5. Open Serial Monitor (`Ctrl+Shift+M`) to view output

## 📊 Project Structure

```
IOT-in-EMBEDDED-SYSTEMS/
├── 1252 Assignment 1/    # Comprehensive assignment project
├── Blind Stick/          # Assistive technology project
├── Blynk/               # Blynk IoT integration
├── dht/                 # DHT sensor examples
├── Html/                # Web interface projects
├── MQTTBroker/          # MQTT implementation
├── Node/                # Node-RED flows
├── Twopub/              # Multi-publisher MQTT
├── Week4/               # Lab 4 exercises
├── Week5/               # Lab 5 exercises
├── Week6/               # Lab 6 exercises
└── Wifi/                # WiFi configuration examples
```

## 🔧 Hardware Requirements

Depending on the project, you may need:

- ESP32 or ESP8266 development board
- DHT11/DHT22 temperature & humidity sensor
- HC-SR04 ultrasonic sensor
- LEDs and resistors
- Buzzer or vibration motor
- Breadboard and jumper wires
- Power supply (USB or external)

## 📡 Supported Communication Protocols

- **WiFi**: Local network connectivity and internet access
- **MQTT**: Lightweight pub/sub messaging for IoT
- **HTTP/HTTPS**: RESTful API and web server
- **Serial**: UART communication for debugging

## 🎯 Use Cases

- **Environmental Monitoring**: Temperature and humidity tracking
- **Assistive Technology**: Blind stick for accessibility
- **Remote Control**: Mobile app-based device management
- **Home Automation**: Sensor-driven automation systems
- **Data Logging**: Cloud-based sensor data storage
- **Real-time Monitoring**: Dashboard visualization

## 📖 Learning Outcomes

This repository demonstrates:

- Embedded C/C++ programming for microcontrollers
- Sensor interfacing and data acquisition
- Wireless communication protocol implementation
- IoT cloud platform integration
- Web development for embedded systems
- MQTT messaging architecture
- Real-time data visualization
- Hardware-software integration

## 🤝 Contributing

Contributions are welcome! If you'd like to add new projects or improve existing ones:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-project`)
3. Commit your changes (`git commit -m 'Add new IoT project'`)
4. Push to the branch (`git push origin feature/new-project`)
5. Open a Pull Request

## 📝 License

This project is open source and available under the [MIT License](LICENSE).

## 📧 Contact

**Zimal Fatemah**
- GitHub: [@Zimal-Fatemah](https://github.com/Zimal-Fatemah)

## 🙏 Acknowledgments

- ESP32/ESP8266 community for excellent documentation
- Arduino ecosystem for accessible IoT development
- Open-source library contributors
- Course instructors and lab coordinators

---

**⭐ If you find this repository helpful, please consider giving it a star!**
