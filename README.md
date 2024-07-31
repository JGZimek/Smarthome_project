# Smart Home System

## Project Overview
This project is a smart home system using Raspberry Pi Zero and ESP32 devices. The system includes a web application, an MQTT broker, and various sensors and actuators.

## Documentation
- [Project Overview](docs/project-overview.md)
- [Hardware](docs/hardware/)
- [System Architecture](docs/system-architecture/)
- [Software Design](docs/software-design/)
- [Implementation Plan](docs/implementation-plan.md)
- [Testing](docs/testing/)
- [Usage Instructions](docs/usage-instructions.md)

## Repositories
This repository uses submodules for different components:

- [ESP32-1 Environment Sensors](submodules/esp32-1-environment)
- [ESP32-2 Security Sensors](submodules/esp32-2-security)
- [ESP32-3 Control and Actuation](submodules/esp32-3-control-actuation)
- [ESP32-4 Energy Management](submodules/esp32-4-energy-management)
- [Raspberry Pi Zero](submodules/raspberry-pi)
- [Frontend Application](submodules/frontend)
- [Backend Application](submodules/backend)

## Getting Started
1. Clone the main repository with submodules:

```bash
   git clone --recurse-submodules https://github.com/JGZimek/smarthome_project.git
```
