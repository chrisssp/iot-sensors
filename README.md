<h1 align="center">IoT Control Panel — Real-Time Device Control and Sensor Monitoring</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-17-DD0031?logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/TypeScript-5.2-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Chart.js-4.4-FF6384?logo=chartdotjs&logoColor=white" alt="Chart.js">
  <img src="https://img.shields.io/badge/License-GPL_v3-0298c3?logo=gnu&logoColor=white" alt="GPL v3">
  <img src="https://img.shields.io/badge/Status-Active-2ea44f" alt="Active">
</p>

<p align="center">
  <em>Web interface for controlling LEDs, servo motors, and monitoring DHT11 temperature and humidity sensors in real time.</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## About IoT Control Panel

A real-time IoT control panel that enables remote management of electronic components connected to an Arduino-compatible microcontroller. Users can toggle LEDs, adjust servo motor position, and visualize temperature and humidity data from a DHT11 sensor through an intuitive web interface.

### Ecosystem

| Component | Repository | Stack |
|-----------|-----------|-------|
| Frontend | [chrisssp/iot-sensors](https://github.com/chrisssp/iot-sensors) | Angular 17, TypeScript, Chart.js |
| Backend API | [chrisssp/iot-sensors-api](https://github.com/chrisssp/iot-sensors-api) | Spring Boot 3, Java 17, MongoDB |

## Features

- Toggle Red, Green, and Blue LEDs on and off
- Adjust servo motor angle (0–180°)
- View real-time DHT11 temperature and humidity readings
- Historical data visualization with Chart.js line graphs
- Dark-themed responsive UI

## Quick Start

### Prerequisites

- Node.js 18+
- Angular CLI 17+
- Arduino-compatible microcontroller with connected components

### Setup

```bash
git clone https://github.com/chrisssp/iot-sensors.git
cd iot-sensors
npm install
ng serve
```

The application runs on `http://localhost:4200` and expects the API at `http://localhost:8080`.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for branch naming, commit conventions, and PR workflow.

## License

This project is licensed under the GPL v3 — see the [LICENSE](LICENSE) file for details.

---

<p align="center">
  <sub>Built with ❤️ · 2026</sub>
</p>
