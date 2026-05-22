<h1 align="center">Panel de Control IoT — Control de Dispositivos y Monitoreo de Sensores en Tiempo Real</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Angular-17-DD0031?logo=angular&logoColor=white" alt="Angular">
  <img src="https://img.shields.io/badge/TypeScript-5.2-3178C6?logo=typescript&logoColor=white" alt="TypeScript">
  <img src="https://img.shields.io/badge/Chart.js-4.4-FF6384?logo=chartdotjs&logoColor=white" alt="Chart.js">
  <img src="https://img.shields.io/badge/Licencia-GPL_v3-0298c3?logo=gnu&logoColor=white" alt="GPL v3">
  <img src="https://img.shields.io/badge/Estado-Active-2ea44f" alt="Active">
</p>

<p align="center">
  <em>Interfaz web para controlar LEDs, servomotores y monitorear sensores de temperatura y humedad DHT11 en tiempo real.</em>
</p>

<p align="center">
  <a href="README.md">🇬🇧 English</a> · <a href="README.es.md">🇪🇸 Español</a>
</p>

---

## Acerca del Panel de Control IoT

Panel de control IoT en tiempo real que permite la gestión remota de componentes electrónicos conectados a un microcontrolador compatible con Arduino. Los usuarios pueden encender y apagar LEDs, ajustar la posición de un servomotor y visualizar datos de temperatura y humedad de un sensor DHT11 a través de una interfaz web intuitiva.

### Ecosistema

| Componente | Repositorio | Stack |
|-----------|-----------|-------|
| Frontend | [chrisssp/iot-sensors](https://github.com/chrisssp/iot-sensors) | Angular 17, TypeScript, Chart.js |
| API Backend | [chrisssp/iot-sensors-api](https://github.com/chrisssp/iot-sensors-api) | Spring Boot 3, Java 17, MongoDB |

## Funcionalidades

- Encender y apagar LEDs Rojo, Verde y Azul
- Ajustar el ángulo del servomotor (0–180°)
- Visualizar lecturas en tiempo real del sensor DHT11
- Gráficos de línea con Chart.js para datos históricos
- Interfaz responsive con tema oscuro

## Inicio rápido

### Requisitos previos

- Node.js 18+
- Angular CLI 17+
- Microcontrolador compatible con Arduino con componentes conectados

### Instalación

```bash
git clone https://github.com/chrisssp/iot-sensors.git
cd iot-sensors
npm install
ng serve
```

La aplicación corre en `http://localhost:4200` y espera la API en `http://localhost:8080`.

## Contribuciones

Lee [CONTRIBUTING.md](CONTRIBUTING.md) para conocer las convenciones de ramas, commits y PRs.

## Licencia

Este proyecto está bajo la licencia GPL v3 — ver [LICENSE](LICENSE) para más detalles.

---

<p align="center">
  <sub>Hecho con ❤️ · 2026</sub>
</p>
