# LUNEVIA

**Lunar Navigation, Exploration, Verification & Intelligent Autonomy**

LUNEVIA is a browser-based lunar rover mission simulation. It demonstrates how a rover might plan routes, assess terrain, manage energy, respond to simulated faults, and operate autonomously when communications are unavailable.

> **Simulation only.** This project does not control a real rover or use live mission data. Terrain, sensor readings, and mission results are simulated.

## Run locally

No build step or package installation is required.

1. Open the HTML file directly in a modern browser, or open it in Visual Studio Code and run it with a local server extension.
2. Select **START MISSION** or **EXPLORE SYSTEM**.
3. Use **START DEMO** to run the guided scenario.

Google Fonts are loaded from an external service, so they may not appear without an internet connection.

## Features

- Interactive lunar terrain map with selectable data layers
- Simulated rover telemetry and configurable capability limits
- Route planning with terrain and return-energy checks
- Mission objectives, targets, and waypoint assignment
- Simulated sensor, communication, and environmental events
- AI copilot, mission log, black box, and replay tools
- Guided tour and rover camera visualization

## Project structure

```text
.
├── LUNEVIA — Lunar Navigation, Exploration, Verification & Intelligent Autonomy (2).html
└── README.md
```

## Data and storage

The simulation generates its terrain, readings, and mission events in the browser. Mission black-box entries may be saved in browser `localStorage`; they are not uploaded to a server.

## License

No license is specified. Add a `LICENSE` file before redistributing the project if you want to grant others permission to use or modify it.
