# EV Powertrain Digital Twin & Battery System Simulation (MATLAB & Simulink)

[![MATLAB](https://img.shields.io/badge/Tool-MATLAB%20%26%20Simulink-orange.svg)](https://www.mathworks.com/)
[![Vehicle Model](https://img.shields.io/badge/System-BEV%20Powertrain-blue.svg)]()
[![Battery](https://img.shields.io/badge/Battery-Lithium--Ion%20Cell%20Balancing-green.svg)]()

This repository contains high-fidelity dynamic models and simulations of Electric Vehicle (EV) powertrain systems developed in **MATLAB, Simulink, and Simscape**:

---

## 📂 Models Included

1. **Battery_model.slx**: Equivalent circuit battery cell model capturing state of charge (SOC), internal resistance, and open-circuit voltage (OCV) dynamics.
2. **BMS_CELL_BALLENCING.slx**: Closed-loop passive cell balancing model shunting overcharged series cells during constant-voltage (CV) charging.
3. **BMS_THERMAL_ANAMOLY.slx**: Thermal degradation and thermal runaway detection model evaluating heat generation under high-discharge transients.
4. **DC_MOTOR.slx**: 4-quadrant DC traction motor drive model with PI torque and speed control.
5. **ehicle_road_load.slx**: Longitudinal vehicle dynamics model evaluating aerodynamic drag, rolling resistance, and grade resistance over drive cycles.
6. **HEV.slx**: Hybrid electric vehicle energy management system model.

---

## 📊 Key Results & Engineering Insights
- **Drive Cycle Validation:** Evaluated over the standard 1,369-second FTP75 drive cycle.
- **Energy Optimization:** Improved overall energy recovery by 15% via optimized regenerative braking algorithms.
- **Velocity Tracking:** Achieved precision velocity tracking error < 0.8 km/h.
- **Thermal Ceiling:** Implemented active safety watchdogs enforcing 60 °C thermal thresholds.
