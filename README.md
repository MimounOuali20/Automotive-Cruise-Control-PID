# Automotive Cruise Control System with PID

## Project Overview
This project presents a high-fidelity MATLAB/Simulink simulation of a vehicle cruise control. 
It uses a PID controller to track a variable speed profile while compensating for road grade disturbances and aerodynamic drag .

## Features
- **PID Controller**: Tuned for zero steady-state error.
- **Physical Modeling**: Includes 1200kg mass, rolling resistance, and aero drag .
- **Environment**: Variable road grade (incline) disturbances .
- **Visualization**: Professional plots and 2D animation script .

## How to Run
1. Run `01_init_parameters.m` to load vehicle data.
2. Open and run `Professional_Cruise_Control_PID.slx`.
3. Run `02_plot_results.m` to generate analysis graphs.

## Results
![Speed Tracking](./results/01_speed_tracking_result.png)
