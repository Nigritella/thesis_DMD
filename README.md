# thesis_DMD

- config.ini: this file contains the parameter values needed to run the simulation 1D;
- Jarrah's_paper_reproduction.ipynb: reproduce the simulation with the parameters from the reference paper, using the Runge-Kutta 4 method built into SciPy;
- Euler_1cell.ipynb: it contains an explicit implementation of the Euler method to reproduce the results from the reference paper;
- discretized_1D.ipynb: actual simulation of the 1D model with added diffusion. It contains all the functions needed to obtain parameters from the config.ini file, run the simulation, save the results, and print them;
- output_1D: this directory contains the results of various simulations, including variations in dt, the diffusion coefficient, initial conditions, and boundary conditions;



