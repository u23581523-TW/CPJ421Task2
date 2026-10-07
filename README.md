# CPJ421 – Biomethanol Reactor Design and Analysis

This repository contains the Python computational models developed for the CPJ421 final-year engineering design project. The models were developed to simulate, analyse, optimise and assess the operability of the methanol synthesis reactor and associated process.

The code is implemented primarily using Python and Jupyter Notebooks.

## Repository Contents

### `U23581523_Base_model.ipynb`

Contains the main process and reactor model used for the methanol synthesis system. The model includes the process calculations required to simulate the reactor and downstream separation, including material balances, thermodynamic calculations, reactor behaviour and pressure drop.

### `U23581523_Closed_loop.ipynb`

Contains the closed-loop process model. This extends the base model to incorporate recycle and process convergence, allowing the overall process behaviour to be evaluated under steady-state operating conditions.

### `U23581523_Dist_analysis.ipynb`

Contains the disturbance analysis used to investigate the response of the reactor and process to changes in key operating variables. The analysis considers disturbances such as reactor inlet temperature, pressure, flow rate and feed composition, and is used to identify important process variables for control and safety.

### `U23581523_Optimisation.ipynb`

Contains the reactor design and economic optimisation calculations. Reactor design variables are varied to investigate their effect on the total annualised cost and process performance, allowing an appropriate reactor configuration to be selected.

### `U23581523_Sens_analysis.ipynb`

Contains the sensitivity analyses performed on key reactor and process parameters. These analyses are used to assess the effect of design variables on reactor performance and to support the selection and justification of the final design.

## Model Structure

The computational work can broadly be divided into the following stages:

1. **Base model** – development and validation of the reactor and process model.
2. **Closed-loop model** – incorporation of process recycle and convergence.
3. **Disturbance analysis** – assessment of process response to operating disturbances.
4. **Optimisation** – evaluation of reactor design variables against the economic objective.
5. **Sensitivity analysis** – investigation of the influence of selected parameters on the final design.

## Purpose

The notebooks provide the complete computational implementation supporting the reactor design, optimisation and process analysis presented in the CPJ421 engineering design report.

The repository is provided to allow the underlying calculations and methodology to be inspected in full.
