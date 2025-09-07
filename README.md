PID vs MPC Steering Control Simulation

This project compares two control strategies for autonomous vehicle trajectory tracking:

PID Controller: Reactive, simple, works okay on straight roads, oscillates on curves.
MPC (Model Predictive Control): Predictive, anticipates path, smoother steering, better for curves.

 Features:-
(i) Simulates three scenarios: initial offset, initial heading error, curved road.
(ii) Plots trajectories and steering inputs for each controller.
(iii) Written in Python using `numpy`, `matplotlib`, and optionally `cvxpy` for optimization.

TO RUN:-
1. Clone the repository:  
   `git clone https://github.com/Kanikashri19/lane-simulation.git`
   
2. Open the notebook in JupyterLab and run all cells.

GitHub:-
[View Project](https://github.com/Kanikashri19/lane-simulation)
