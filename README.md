# Homogenized-model-simplified-circuit

The model is firstly solved at the “open circuit mode” to find the OCP. In “scan mode”, the scan starts from the OCP, and increases/ decreases at a small increment (e.g. 0.5 mV) to alter the homogenized area-averaged rebar electrode potential, until it reaches to a given scan range bounds (e.g. OCP-300 mV or OCP+ 300 mV). The simulated potentiodynamic scan procedure was coded up in Python; the group of equations in both “open circuit model” and “scan mode” were numerically solved with iterative optimization algorithm from Scipy in Python ecosystem. To optimize the convergence during solving, solutions from the previous scan step were used as initial guesses for the next scan step. 

