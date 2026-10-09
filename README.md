# Chem Trace

A chemical byproduct detection and telemetry system engineered to monitor hazardous gases in laboratory and industrial environments. The system utilizes MQ-135 and MQ-2 gas sensor arrays coupled with real-time signal processing to achieve 95.57% detection accuracy.

[![License: MIT](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Hardware](https://img.shields.io/badge/Hardware-Arduino%20%2F%20MQ%20Sensors-red)](#)
[![Accuracy](https://img.shields.io/badge/Accuracy-95.57%25-green)](#)

---

## Overview

Chem Trace monitors volatile chemical reactions and provides automated concentration tracking for hazardous byproducts.

### Target Reactions & Sensor Profiling

1. **Ammonia ($NH_3$) Detection (MQ-135 Sensor)**
   $$\text{NH}_4\text{Cl}_{(s)} + \text{NaOH}_{(aq)} \rightarrow \text{NH}_{3(g)} + \text{H}_2\text{O}_{(aq)} + \text{NaCl}_{(s)}$$
   Tracks gas concentration rise over sequential reaction trials.

2. **Hydrogen ($H_2$) Generation (MQ-2 Sensor)**
   $$2\text{Al}_{(s)} + 2\text{NaOH}_{(s)} + 6\text{H}_2\text{O} \rightarrow 3\text{H}_{2(g)} + 2\text{NaAl(OH)}_4$$
   Demonstrates linear sensor response profiles across varying reactant mass.

---

## Key Performance Metrics

- **Detection Accuracy**: 95.57% across benchmarked trials.
- **Response Latency**: ~0.5s per measurement cycle.
- **Sensor Array**: MQ-135 (Air Quality / Ammonia) and MQ-2 (Combustible Gas / Hydrogen).

---

## Project Structure

```
Chem-Trace/
├── index.html                  # Interactive results portal and telemetry visualizer
├── README.md                   # System documentation and reaction data
```

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/Adel-333/Chem--Trace.git
   cd Chem--Trace
   ```

2. Open `index.html` in any web browser to view the interactive reaction dashboards, sensor curves, and theoretical vs. measured numerical validation.

---

## License

This project is licensed under the MIT License.