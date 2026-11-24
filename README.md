# BUG-E EV Powertrain, Charging Circuit & CAN Display Simulations

Simulation models and firmware verification setups developed for Team BUG-E (SAEINDIA eBAJA).

## Repository Contents

1. **Complete EV Powertrain Simulation (`POWERTRAIN.slx`)**
   - Full vehicle powertrain modeling in MATLAB/Simulink.
   - Includes block diagrams and subsystem breakdowns (`PowerTrain Main.png`).

2. **Battery Charging Circuit Simulation (`Charger_Sim.slx`)**
   - Standalone simulation of the EV battery charging topology in MATLAB/Simulink.
   - Includes circuit documentation (`Charging_circuit.pdf`, `Battery Charging Ckt.png`).

3. **CAN Bus Cockpit Display Verification (`proteus_sim.pdsprj`)**
   - Hardware/firmware simulation in Proteus using an Arduino to validate CAN frame parsing and TFT display rendering logic prior to live vehicle integration.

## Tools Used
* MATLAB & Simulink
* Proteus Design Suite
* Arduino IDE
