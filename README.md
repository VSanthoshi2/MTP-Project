# Time-Optimal Control using Interval Analysis

**Student Name**: Vangapally Santhoshi  
**Roll Number**: 2023EEA2655  
**Program**: M.Tech in Control and Automation  
**Institute**: IIT Delhi  
**Thesis Supervisor**: Prof.Shaunak Sen
---

## Overview

This repository contains all relevant files for the M.Tech thesis titled **"Time-Optimal Control using Interval Analysis"**. The objective of this work is to study the classical **brachistochrone problem** using interval analysis techniques and to rigorously compute minimum-time trajectories under gravitational force.

---

## Prerequisites
Ensure you have the following installed:

Julia (version ≥ 1.9 recommended)

Install required packages by running the following in the Julia REPL:

using Pkg
Pkg.add(["Pluto", "IntervalArithmetic", "IntervalBoxes", "Plots", "ForwardDiff", "LinearAlgebra"])

Running the Pluto Notebook (Interval Dynamic Programming)
Launch Julia REPL.

Run the following commands:

using Pluto
Pluto.run()
This opens Pluto in your browser.

Click "Open from file" and select:

code/dp/interval_dp_notebook.jl
Run all cells sequentially to reproduce the results.

Running the Interval Newton Method
Navigate to the directory:
code/newton/
Run the script:

julia interval_newton_method.jl
This script computes and displays validated bounds for the root using the Interval Newton technique.

🔁 Running the Branch-and-Bound Algorithm
Navigate to:
code/branch and bound/
Execute the solver script:

julia branch_and_bound_solver.jl
This implementation performs validated search for the global minimum time using a branch-and-bound strategy.

