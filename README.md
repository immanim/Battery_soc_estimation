EV Battery State of Charge (SOC) Estimation using MATLAB Simulink

Project Overview

This project demonstrates the estimation of Battery State of Charge (SOC) for an Electric Vehicle battery using MATLAB Simulink.

State of Charge (SOC) indicates the remaining capacity of a battery as a percentage of its total capacity. Accurate SOC estimation is very important for Battery Management Systems (BMS) used in electric vehicles.

This simulation model shows how SOC decreases when the battery discharges over time.

Objectives

- To model a basic battery discharge system in Simulink
- To estimate battery SOC using integrator-based modelling
- To visualize the SOC variation during battery discharge

Tools Used

- MATLAB
- Simulink

System Model

The Simulink model includes the following components:

- Battery model
- Current input representing load consumption
- Integrator block for SOC calculation
- Mathematical blocks for SOC estimation
- Scope block to visualize the SOC output

Simulation Output

During simulation, the battery State of Charge gradually decreases as the battery supplies current to the load.

Example SOC behavior:

100% → 90% → 80% → 70%

This demonstrates how the battery discharges over time.

Project Files

battery_soc_simulation.slx – Simulink model file
model.png – Screenshot of the Simulink model
soc_graph.png – Simulation output showing SOC graph
README.md – Project documentation

Applications

This project is relevant for:

- Electric Vehicle Battery Management Systems
- Energy storage system analysis
- EV powertrain simulation studies
- Battery performance monitoring

Future Improvements

Possible future enhancements include:

- Implementing Kalman Filter based SOC estimation
- Adding temperature effects to the battery model
- Real-time SOC monitoring using sensors
- Integrating the model with a full EV powertrain simulation

Author

IMMANUVEL M
interested in Electric Vehicle Powertrain Systems and MATLAB Simulations.
