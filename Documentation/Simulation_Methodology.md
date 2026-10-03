# Simulation Methodology

## 1. Simulation Approach

The thermoelectric module is analyzed using the finite element method in COMSOL Multiphysics.

A coupled thermal–electrical model is used to investigate the behavior of the thermoelectric material under the applied operating conditions.

The simulation workflow consists of:

1. Geometry creation
2. Material assignment
3. Physics selection
4. Boundary condition definition
5. Mesh generation
6. Stationary solution
7. Parametric study
8. Results extraction
9. Performance analysis

---

## 2. Thermoelectric Principle

Thermoelectric generators operate by converting a temperature difference into electrical energy.

When a temperature gradient is established across a thermoelectric material, a voltage develops due to the Seebeck effect.

The generated voltage can be represented conceptually as:

V = S × ΔT

where:

- **V** = generated voltage
- **S** = Seebeck coefficient
- **ΔT** = temperature difference

The actual COMSOL model solves the coupled thermal and electrical equations using the material properties defined for the thermoelectric material.

---

## 3. Coupled Thermal–Electrical Analysis

The model simultaneously considers:

- Temperature distribution
- Heat transfer
- Electric potential
- Current density
- Thermoelectric coupling

The temperature field influences the electrical response through the thermoelectric material properties.

Similarly, the electrical field is coupled with the thermal field through thermoelectric effects.

---

## 4. Mesh Generation

A finite-element mesh is generated for the complete 3D geometry.

The mesh discretizes the geometry into smaller elements over which COMSOL solves the governing equations.

Mesh refinement is particularly important in regions where:

- Temperature gradients are high
- Electrical potential changes rapidly
- Different materials are connected
- Thermoelectric elements are relatively small

The current model uses a finite-element mesh generated within COMSOL Multiphysics.

A mesh-independence study will be performed during the later stage of the project.

---

## 5. Stationary Study

A stationary study is used to calculate the steady-state solution.

The stationary study provides the following types of information:

- Temperature distribution
- Electric potential distribution
- Current density
- Heat transfer
- Electrical power

The solution is evaluated after the coupled thermal and electrical equations converge.

---

## 6. H/L Parametric Study

The main parametric investigation is based on the H/L ratio.

Where:

**H** = thermoelectric leg height

**L** = characteristic thermoelectric leg length

The H/L ratio is changed over a defined range while the remaining simulation conditions are maintained according to the model setup.

For each H/L value, the resulting thermoelectric response is evaluated.

---

## 7. Quantities Investigated

The following quantities are investigated during the study:

### Temperature

Temperature distribution is evaluated throughout the thermoelectric module.

### Effective Temperature

Effective temperature is monitored as a function of the H/L ratio.

### Electrical Response

The electrical response of the module is investigated using the electric potential and current-related quantities.

### Output Power

Electrical power is evaluated to investigate the influence of the H/L ratio on thermoelectric performance.

---

## 8. Power Evaluation

The electrical output power is one of the main performance parameters of the study.

For a resistive load, electrical power can generally be expressed as:

P = V² / R

or

P = I²R

where:

- **P** = electrical power
- **V** = voltage
- **I** = current
- **R** = load resistance

The power values obtained from the COMSOL model are used to study the relationship between output power and H/L ratio.

---

## 9. Parametric Study Workflow

```text
Select H/L Value
       ↓
Update Geometry
       ↓
Generate/Update Mesh
       ↓
Solve Stationary Model
       ↓
Extract Temperature
       ↓
Extract Electrical Response
       ↓
Calculate/Extract Power
       ↓
Repeat for Next H/L
       ↓
Plot Results
