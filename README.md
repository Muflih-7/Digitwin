\# DigitTwin — Industrial Digital Twin Platform



!\[Platform](https://img.shields.io/badge/Platform-Digital%20Twin-3b82f6?style=flat-square)

!\[Status](https://img.shields.io/badge/Status-Live-10b981?style=flat-square)

!\[WebGL](https://img.shields.io/badge/3D-WebGL-f59e0b?style=flat-square)

!\[ML](https://img.shields.io/badge/ML-Predictive%20Maintenance-14b8a6?style=flat-square)



A full-stack industrial digital twin platform built as part of a final year Mechanical Engineering project. DigitTwin provides real-time factory monitoring, predictive maintenance, 3D visualisation and engineering simulation through a unified web interface — with no frameworks, no dependencies, just HTML, CSS and vanilla JavaScript.



\---



\## Live Demo



\*\*DigitTwin Dashboard\*\* → deployed via Render  

Login: `admin` / `admin123` \&nbsp;·\&nbsp; or use Guest Observer



\---



\## Linked Platforms



DigitTwin acts as the central hub connecting four live engineering platforms:



| Platform | Description | Link |

|---|---|---|

| \*\*Smart Factory\*\* | Real-time IoT monitoring of 26 machines across 3 production zones | \[factoryonline-production.up.railway.app](https://factoryonline-production.up.railway.app/) |

| \*\*Predictive Maintenance\*\* | ML-based failure prediction and Remaining Useful Life estimation | \[predictivemaintenance-91fu.onrender.com](https://predictivemaintenance-91fu.onrender.com/) |

| \*\*MECHSIM\*\* | Mechanical engineering simulation — FEA, gear design, material selection | \[mechsim.onrender.com](https://mechsim.onrender.com/) |

| \*\*OptimalPrint\*\* | Print job scheduling and production optimisation | \[optimalprint.onrender.com](https://optimalprint.onrender.com/) |



\---



\## Features



\### 3D Digital Twin

\- Real-time interactive 3D factory floor rendered entirely in raw WebGL (no Three.js)

\- Full orbit camera — drag to rotate, scroll to zoom, shift+drag to pan

\- View modes: Perspective, Top, Front, Side

\- Detailed factory geometry: CNC machines, robot arms, conveyor belts, hydraulic presses, paint booths, structural columns, ceiling trusses, safety barriers

\- Per-machine status indicators (green / amber / red) matching live sensor data

\- Right panel shows live telemetry: temperature, vibration, RPM, load, health score, RUL, bearing wear

\- Direct links to Predictive Maintenance and Smart Factory from selected machine panel



\### Dashboard

\- Live KPI cards: OEE, active machines, average RUL, critical alerts

\- Mini 3D factory preview with auto-rotation

\- Real-time alert feed with severity classification

\- Platform cards linking to all 4 external platforms



\### Sensor Network

\- 48 sensor nodes displayed across Zone A, B and C

\- Sensor types: temperature, vibration, pressure, current, RPM, flow, humidity, voltage, CO2, noise

\- Live status: Online / Degraded / Offline with progress bars



\### Live Alerts

\- Full alert table with filter by: All, Critical, Warning, Resolved, Info

\- Severity badges, zone, timestamp and status for every alert



\### Analytics

\- OEE by zone bar chart

\- 14-day machine utilisation sparkline

\- Zone performance breakdown table: availability, performance, quality



\### Historical Data

\- 4 trend sparkline charts: OEE, utilisation, alert frequency, MTBF

\- 30-day daily summary log with export button



\### Fault Analysis

\- Top fault types ranked by frequency

\- 5×5 fault frequency matrix (machine × fault type)

\- Root cause analysis with corrective action recommendations

\- Zone fault distribution

\- ML prediction accuracy by fault category



\### Maintenance Management

\- Open work orders with RUL progress bars

\- ML failure predictions from Predictive Maintenance platform

\- Recently resolved work orders

\- Model performance metrics: accuracy, false positive rate, confidence



\### Configuration

\- 5-section settings panel: General, Alert Thresholds, Connections, Display, Security

\- Live toggle switches, dropdowns and input fields



\### Reports

\- 6 report types: OEE, Maintenance, ML Model, Sensor Health, Fault Analysis, Energy

\- Download simulation with toast notifications

\- Recent downloads log



\---



\## Tech Stack



| Layer | Technology |

|---|---|

| Frontend | HTML5, CSS3, Vanilla JavaScript |

| 3D Rendering | Raw WebGL (GLSL shaders, custom matrix math) |

| Fonts | Inter, IBM Plex Mono (Google Fonts) |

| Deployment | GitHub + Render (Static Site) |

| ML Backend | Python, Isolation Forest, LSTM (separate repo) |

| IoT Backend | Node.js, MQTT, Railway (separate repo) |



No npm. No build step. No frameworks. Open `index.html` and it runs.



\---



\## Project Structure

