# MQTT Topics Documentation for Smart Home Project

## Overview

This document outlines the MQTT topics used in the Smart Home project. MQTT (Message Queuing Telemetry Transport) is a lightweight messaging protocol that allows IoT devices to communicate with each other. In this project, MQTT is used to facilitate communication between the Raspberry Pi Zero, ESP32 devices, and the web application.

## MQTT Topics Structure

Below is the structure of the MQTT topics used in this project, visualized as a hierarchical diagram.

```mermaid
graph LR
    A[Smarthome] --> B[Environment Sensors]
    A --> C[Security System]
    A --> D[Control and Actuation]
    A --> E[Energy Management]

    B --> B1[temperature]
    B --> B2[humidity]
    B --> B3[status]

    C --> C1[light]
    C --> C2[motion]
    C --> C3[status]

    D --> D1[door]
    D --> D2[window]
    D --> D3[status]

    E --> E1[smoke]
    E --> E2[gas]
    E --> E3[status]

    B1 --> F[smarthome/environment-sensors/temperature]
    B2 --> G[smarthome/environment-sensors/humidity]
    B3 --> H[smarthome/environment-sensors/status]

    C1 --> I[smarthome/security-system/light]
    C2 --> J[smarthome/security-system/motion]
    C3 --> K[smarthome/security-system/status]

    D1 --> L[smarthome/control-actuation/door]
    D2 --> M[smarthome/control-actuation/window]
    D3 --> N[smarthome/control-actuation/status]

    E1 --> O[smarthome/energy-management/smoke]
    E2 --> P[smarthome/energy-management/gas]
    E3 --> Q[smarthome/energy-management/status]
```
