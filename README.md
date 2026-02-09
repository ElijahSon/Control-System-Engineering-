# Satellite Station-Keeping Simulator (DSAS) — LQR Control (MATLAB/Simulink)

This project implements a satellite station-keeping / relative motion simulator used in the context of a DSAS engineering study. The goal is to maintain a satellite at an autonomous “hold position” (near an equilibrium point) using state-space modeling and LQR feedback control, with simulation performed in Simulink.

├── prgBE_DSAS.m
│   Main MATLAB script:
│   - Builds the state-space model
│   - Designs LQR controllers
│   - Runs simulations and plots results
│
├── initialisation_a_distribuer.m
│   Loads orbital parameters, constants, initial conditions,
│   and simulation settings
│
├── simulik_DSAS_validation.slx
│   Simulink model for open-loop and standard LQR validation
│
├── sch_2.slx
│   Simulink model implementing the augmented LQR controller
│   with perturbation effects
│
├── README.md
    Project documentation

