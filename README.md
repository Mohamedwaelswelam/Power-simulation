# Power-simulation

This repository contains the MATLAB implementation of a steady-state AC power flow simulation for a 15-bus power system using the MATPOWER toolbox.

## Overview

The simulation computes bus voltages, power injections, and branch flows based on given load and generation data. It uses Newton-Raphson-based AC power flow algorithms provided by MATPOWER to analyse system performance under different load and generation scenarios.

## Features

- 15-bus power network simulation
- Full AC power flow analysis using MATPOWER
- Load and generation defined per bus
- Branch power and reactive flow monitoring
- Supports integrated studies with gas systems

## Requirements

- MATLAB (R2020a or later recommended)
- MATPOWER (version 7.1 or compatible)

## How to Run

1. Clone or download the repository.
2. Open MATLAB and set the working directory to the project folder.
3. Ensure MATPOWER is installed and added to the MATLAB path.
4. Run the simulation script (e.g., `runpf.m` depending on your file names).

## File Structure

- `case15nbr.m` — MATPOWER case file representing the 15-bus network

## Author

Mohamed Wael Swelam  
University of Manchester – Final Year Project

## License

This project is for academic use and demonstration purposes.

