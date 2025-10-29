# Helmholtz-field-decomposition
Calculates the axial and radial components of the magnetic field produced by Helmholtz coils using the Biot–Savart law and elliptic integrals. Includes functions for total field computation and Cartesian conversion.
This Python project computes and visualizes the **axial** and **radial** components of the magnetic field produced by a pair of **Helmholtz coils** using the **Biot–Savart law** and **complete elliptic integrals**.  
It also includes a visualization module that plots the **magnetic field distribution** in the **XY** and **YZ** planes, showing both field strength and direction.

---

## Features

- Calculates **axial** and **radial** magnetic field components at any spatial point.  
- Computes **total field components** (from both coils) in a Helmholtz configuration.  
- Converts the field into **Cartesian components** (`Bx`, `By`, `Bz`).  
- Generates **density maps and stream plots** for magnetic field visualization in the XY- and YZ-planes.  
- Uses **SciPy elliptic integrals** for high-precision computation.

---

## Parameters

| Symbol | Description | Units |
|:------:|:-------------|:------|
| `i` | Current through the coil | A |
| `a` | Coil radius | m |
| `n` | Number of turns per coil | — |
| `x, y, z` | Spatial coordinates | m |
| `uo` | Magnetic permeability constant (scaled by `n`) | H/m |
| `circle_radius` | Visualization marker for coil radius | m |
