# Thermoelectric Generator Analysis Using COMSOL Multiphysics

## Overview

This project presents a numerical study of a thermoelectric generator using COMSOL Multiphysics.

The objective is to investigate the coupled thermal and electrical behavior of the thermoelectric system and study the influence of the H/L parameter on temperature and power output.

The model is being developed as a parametric multiphysics simulation, with the current work focused on obtaining and analyzing the thermal and power characteristics of the system.

---

## Project Status

 **Status: In Progress**

The COMSOL model has been developed and the initial parametric study has been completed.

### Completed so far

- Thermoelectric geometry development
- Material assignment
- Thermal and electrical physics setup
- Boundary condition definition
- Mesh generation
- Stationary study setup
- Parametric study with varying H/L
- Power calculation
- Effective temperature analysis
- Temperature response analysis

### Planned work

- Identify the exact optimum H/L ratio
- Perform mesh/convergence verification
- Analyze temperature distribution
- Analyze electric potential distribution
- Analyze current density
- Analyze heat flux
- Calculate thermoelectric performance parameters
- Compare numerical results with the reference study
- Finalize conclusions

---

## Software Used

- COMSOL Multiphysics
- Microsoft Excel / spreadsheet analysis for post-processing
- GitHub for project documentation and version control

---

## Model Description

The thermoelectric system is modeled using coupled thermal and electrical physics in COMSOL Multiphysics.

The study investigates the effect of the dimensionless geometric parameter:

\[
H/L
\]

on the thermal response and electrical power output of the thermoelectric system.

---

## Physics

The model uses coupled multiphysics behavior involving:

- Heat Transfer
- Electric Currents
- Thermoelectric Effect

The stationary study is used to evaluate the steady-state response of the system.

---

## Parametric Study

A parametric sweep was performed by varying the H/L parameter over a wide range.

The calculated output power was evaluated using the electrical response of the thermoelectric system.

The current results show that the output power increases initially, reaches a maximum at an intermediate H/L value, and subsequently decreases as H/L increases further.

This behavior indicates the presence of an optimum geometric condition for maximum power output.

---

## Current Results

### 1. Power vs H/L

The power curve shows a maximum output power of approximately 0.018–0.019 W within the investigated H/L range.

![Power vs H/L](Results/Power_vs_HL.png)

---

### 2. Logarithmic Power Analysis

A logarithmic representation of the power relationship with H/L was also generated to examine the behavior over the wide parameter range.

![Logarithmic Power Plot](Results/Power_Log_Plot.png)

---

### 3. Effective Temperature

The effective temperature increases rapidly at lower H/L values and gradually approaches a nearly constant value at higher H/L.

![Effective Temperature](Results/Effective_Temperature.png)

---

### 4. Temperature vs H/L

The temperature response demonstrates significant variation with H/L. The higher-temperature region increases while the lower-temperature region decreases as H/L increases.

![Temperature vs H/L](Results/Temperature_vs_HL.png)

---

## Preliminary Observations

The current numerical results indicate:

1. Output power is strongly dependent on H/L.
2. An intermediate H/L region produces the maximum calculated power.
3. Effective temperature increases with H/L and eventually approaches a plateau.
4. The temperature response changes significantly across the investigated H/L range.
5. Further analysis is required before determining the final optimum configuration.

---

## Future Work

The next stage of the project will focus on:

- Extracting exact numerical values from COMSOL
- Determining the optimum H/L ratio
- Checking mesh independence
- Studying temperature distribution
- Studying electric potential distribution
- Studying current density
- Studying heat flux
- Evaluating voltage, current and power
- Comparing results with the reference study
- Performing final validation
- Preparing the final engineering conclusions

---

## Project Workflow

```text
Geometry
   ↓
Material Properties
   ↓
Physics Setup
   ↓
Boundary Conditions
   ↓
Mesh
   ↓
Stationary Study
   ↓
Parametric Sweep
   ↓
H/L Variation
   ↓
Temperature Analysis
   ↓
Electrical Analysis
   ↓
Power Calculation
   ↓
Optimization
   ↓
Validation
   ↓
Final Conclusions
