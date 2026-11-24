# BUG-E EV Powertrain, Charging Circuit & Telemetry Simulations

Simulation models and electrical schematics developed for **Team BUG-E** (SAEINDIA eBAJA).

## Repository Contents

1. **Complete EV Powertrain Simulation (`POWERTRAIN.slx`)**
   - Full vehicle powertrain modeling in MATLAB/Simulink, covering battery discharge, motor controller behavior, and drivetrain load.
   - Includes system block diagrams and subsystem views (`PowerTrain Main.png`).

2. **Battery Charging Circuit Simulation (`Charger_Sim.slx`)**
   - Standalone simulation of the EV battery charging topology in MATLAB/Simulink to analyze voltage/current regulation and charging stability.
   - Includes circuit schematics and documentation (`Charging_circuit.pdf`, `Battery Charging Ckt.png`).

3. **Cockpit Telemetry Display Simulation (`proteus_sim.pdsprj`)**
   - Proteus simulation setup using an Arduino to test and verify cockpit TFT display rendering and UI behavior with simulated vehicle parameters.

4. **ESP32 CAN Bus Circuit Schematic (`<your-can-schematic-filename>.pdf`)**
   - Initial hardware schematic design for the ESP32-based CAN bus interface circuit used for vehicle telemetry integration.

## Tools Used
* MATLAB & Simulink
* Proteus Design Suite
* Arduino IDE
* EasyEDA
