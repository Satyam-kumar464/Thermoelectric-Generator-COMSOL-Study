# Results and Analysis

## 1. Overview

The initial results were obtained from the COMSOL stationary study and the H/L parametric analysis.

The main purpose of the analysis is to investigate how the H/L ratio affects the thermal behavior and electrical power output of the thermoelectric module.

---

## 2. Power vs H/L

The output power was evaluated for different values of the H/L ratio.

The results show that the output power initially increases with increasing H/L and reaches a maximum region. At higher H/L values, the output power begins to decrease.

![Power vs H/L](Results/Power_vs_HL..png)

### Observation

The current simulation indicates that the output power is dependent on the thermoelectric leg geometry.

An optimum region can be observed in the investigated H/L range. The exact optimum H/L value will be determined after completing the detailed numerical analysis and verification.

---

## 3. Logarithmic Power Plot

A logarithmic representation of the power results was also generated to examine the variation of power over the investigated H/L range.

![Logarithmic Power Plot](Results/Power_Log_Plot.png)

The logarithmic representation provides an alternative way to visualize the variation in output power across the parametric range.

---

## 4. Effective Temperature

The effective temperature was evaluated for different H/L values.

![Effective Temperature](Results/Effective_Temperature.png)

The results show an increasing trend in effective temperature with increasing H/L.

The effective temperature approaches approximately **47 °C** in the current simulation range.

Further analysis will be carried out to understand the relationship between the geometric ratio and the thermal response.

---

## 5. Temperature vs H/L

The temperature response of different regions of the thermoelectric module was investigated as a function of H/L.

![Temperature vs H/L](Results/Temperature_vs_HL.png)

The results show different temperature trends for the investigated regions.

One temperature response increases toward approximately **47 °C**, while another remains around **23 °C**. A third response decreases toward approximately **0 °C** over the investigated range.

These variations represent the different thermal conditions experienced by different regions of the thermoelectric module.

---

## 6. Preliminary Findings

The current simulation results indicate the following:

- The H/L ratio has a significant influence on output power.
- Output power initially increases as H/L increases.
- A maximum-power region is observed within the investigated range.
- Effective temperature increases with H/L.
- Different regions of the module exhibit different temperature responses.
- The geometry of the thermoelectric legs affects the thermal and electrical behavior of the module.

These findings are considered **preliminary** because mesh independence, convergence, and detailed validation are still being performed.

---

## 7. Mesh Verification

Mesh independence is an important part of the numerical analysis.

A mesh-convergence study will be performed using progressively refined meshes.

The following quantities will be compared:

- Maximum temperature
- Minimum temperature
- Output voltage
- Output current
- Output power

The final mesh will be selected by considering both numerical stability and computational cost.

---

## 8. Comparison with Reference Study

The present COMSOL model was developed with reference to published research on Bi₂Te₂.₇₀Se₀.₃₀ thermoelectric modules and COMSOL-based thermoelectric simulations.

The comparison will consider:

- Material selection
- Module geometry
- Boundary conditions
- Thermoelectric properties
- Temperature distribution
- Electrical response
- Output power
- Influence of geometric parameters

The present work is an independent numerical study and is not intended to reproduce the reference study exactly.

Differences between the present and reference results may occur due to differences in geometry, boundary conditions, material properties, load conditions, mesh, and simulation settings.

---

## 9. Current Limitations

The current study is still under development.

The main limitations at the present stage are:

- Mesh independence has not yet been fully established.
- The exact optimum H/L ratio has not yet been finalized.
- Detailed electrical characterization is still being developed.
- Complete comparison with the reference study remains to be performed.
- Thermoelectric efficiency analysis has not yet been finalized.
- The final COMSOL model is still under development.

---

## 10. Future Analysis

The following analyses are planned:

- [ ] Mesh-convergence study
- [ ] Detailed temperature distribution
- [ ] Electric potential distribution
- [ ] Current density distribution
- [ ] Heat flux distribution
- [ ] Voltage-current characteristics
- [ ] Power-load relationship
- [ ] Thermoelectric efficiency
- [ ] Comparison with reference results
- [ ] Final optimization of H/L ratio

---

## 11. Conclusion

The initial COMSOL simulations indicate that the geometry of the thermoelectric module has a significant influence on its thermal and electrical response.

The H/L parametric study provides a basis for investigating the relationship between thermoelectric geometry and output power.

Further mesh verification, convergence analysis, and comparison with reference results will be performed before the final conclusions are established.
