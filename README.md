The repository contains the notebooks developed for the study of a mathematical model of muscle regeneration proposed in 2014 in the paper by Jarrah et al., "A mathematical model of skeletal muscle disease and immune response in the mdx mouse." Each directory focuses on a specific aspect of the analysis; typically, each folder is associated with a notebook and a configuration file.

- paper_reproduction contains notebooks that reproduce the results of the paper using the explicit Euler and Runge-Kutta methods, along with example outputs.

- damage_term_and_mass_conservation includes a notebook that evaluates the impact of the time-dependent term over the course of the system’s evolution. It also compares the autonomous and non-autonomous systems, both as defined in the paper and by replacing the equation for regenerating fibres with the mass conservation equation.

- stationary_time is used to calculate the convergence time through a direct comparison between the autonomous and non-autonomous systems. The output files are saved in subdirectories named after the variable whose initial value has been modified in each case.

- fixed_points_research contains the file for fixed-point analysis in the case of the system with default initial conditions (to be refined).

- convergence_from_different_ic contains code for sampling initial conditions within a predefined volume in the phase space and assessing whether the system's evolution from these conditions converges or not. Some output files are saved in the folder.

- fixed_point_trend is used to study the behaviour of the steady state when varying the initial condition of a single variable at a time. This directory also includes the results of some simulations.

- stability_analysis contains two subdirectories: one for the study of the linear stability of fixed points and another for visualising heat maps related to system divergence (to be completed).

- model_with_diffusion implements a new version of the model, introducing a spatial component and one-dimensional diffusion. The long-term effect of diffusion on different cells can be studied to determine how it influences the steady state.

- effect_of_diffusion_in_different_cells uses the diffusion model to visualise the evolution in different cells along the row. Output files are saved for several examples with varying boundary conditions and different file lengths.
