# qg-plasma
Analysis scripts for CHM equations

## FIle/Folder Structure

- `eigensolvers.py` - Spectral and finite-difference solvers for Rossby wave eigenfunctions
- `config_generator.py` - Generates configuration files for the Poincare maps
- `poincare_map.py` - Functions for generating different Poincare maps, and compute lyapunov exponents
- `run_analysis.py` - Script containing all of the desired analysis
- `dns_input` - Inputs from the DNS
- `poincare_input` - Inputs to the poincare map, generated mostly from config_generator.py
- `sections` - Output sections go here
- `lyapunovs` - Output lyapunov exponents go here
- `plot_scripts` - Scripts for plotting the outputted data
- `qg_dns` - Folder containing DNS (and DNS analysis) scripts
- `scratch` - Scratch scripts to test things with
