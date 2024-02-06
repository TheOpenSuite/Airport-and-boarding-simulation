# Airport-and-boarding-simulation
The aim is to simulate a an airport system environment. The simulation involves the generation, delay, and processing of passengers, considering several factors like business and economy class, overweight luggage, a random activity and various service counters. 

## Overview:

This simulation project models an airport passenger system to analyze queue dynamics, waiting times, and system performance.

## Compilation and Execution:

1. **Required Environment:**
   - Ensure you have [MATLAB](https://www.mathworks.com/products/matlab.html) installed on your system.

2. **Run the Simulation:**
   - Open MATLAB and navigate to the project directory.
   - Open the main simulation file: `Airport.m`.
   - Adjust simulation parameters if needed.
   - Run the script in MATLAB.

3. **Interpreting Results:**
   - Simulation results and key statistics will be displayed in the MATLAB console.
   - Check the console for average waiting times, time in the system, and other performance metrics.

## Simulation Parameters (Editable in `Airport.m`):

- Number of Simulations
- Simulation Length (in minutes)
- Number of Airlines
- Number of Counters (M/M/C model)
- Number of Passengers
- Passenger Generation Rate
- Business Class Fraction
- Counter Service Rate
- Overweight Counter Service Rate
- Airplane Capacities
- Delay Parameters
- ...

## Notes:

- This simulation is built using MATLAB. Ensure the necessary MATLAB licenses.
- Adjust simulation parameters based on your specific requirements.
- There may be some issues with some parameters and how the chi-square was used but couldn't be properly fixed due to time contraints.

