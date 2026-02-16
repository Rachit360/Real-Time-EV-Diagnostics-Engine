# Real-Time EV Diagnostics & Telemetry Engine

A Python-based real-time simulation platform that models core EV telemetry and diagnostic behavior inspired by modern Battery Management Systems (BMS) and ECU architectures.

Designed to demonstrate how vehicle performance data can be generated, visualized, logged, and analyzed before integration with embedded hardware.

---

## Engineering Focus

- Real-time telemetry simulation (60 Hz loop)
- EV-relevant monitoring logic (RPM, voltage, temperature)
- Multithreaded execution (UI + engine separation)
- Structured data logging for diagnostics
- Live performance visualization

---

## Tech Stack

- Python 3
- Tkinter (GUI dashboard)
- Matplotlib (real-time plotting)
- Threading (concurrent engine loop)
- CSV logging (persistent telemetry storage)

---

## Core Features

- Physics-based acceleration & braking model
- RPM–speed relationship modeling
- Battery voltage & thermal tracking
- Live graph updates (Speed & RPM)
- Telemetry logging every 2 seconds
- Modular and extensible architecture

---

## Architecture Flow

Simulation Engine → Sensor Layer → Logger → Visualization

---

## Run

pip install matplotlib  
python main.py

---

## Logged Parameters

- Timestamp
- RPM
- Speed (km/h)
- Temperature (°C)
- Fuel Level (%)
- Battery Voltage (V)

---

## Planned Extensions

- State of Charge (SoC) modeling
- Thermal derating logic
- Fault detection & alerts
- REST API exposure (FastAPI)
- Cloud telemetry dashboard
- Containerization (Docker)

---

## Purpose

This project demonstrates system-level automotive thinking, real-time concurrent programming, and telemetry-driven diagnostics aligned with EV architecture principles.
