# Rocket Nozzle Performance Reconstruction from CAD Geometry

## Overview

This project reconstructs the internal flow field and performance of a CAD-designed converging-diverging rocket nozzle using classical compressible flow theory and numerical methods.

Rather than performing CFD simulations, the nozzle geometry was measured directly from a FreeCAD model and analyzed using one-dimensional isentropic flow equations.

The objective was to bridge CAD design and aerospace propulsion analysis by estimating nozzle performance from geometry alone.

---

## Features

- CAD-based geometry extraction
- Numerical Area-Mach solver
- Mach number reconstruction
- Temperature distribution analysis
- Pressure distribution analysis
- Density distribution analysis
- Velocity distribution analysis
- Mass flow rate estimation
- Thrust estimation

---

## Methodology

The nozzle was discretized into multiple axial sections.

For each section:

1. Local area was calculated
2. Area ratio (A/A*) was determined
3. Mach number was solved numerically
4. Temperature, pressure, density and velocity were computed

The analysis assumes:

- Steady flow
- One-dimensional flow
- Isentropic expansion
- Ideal gas behavior
- Constant specific heat ratio

---

## Results

### Geometry

| Parameter | Value |
|------------|---------|
| Chamber Diameter | 536 mm |
| Throat Diameter | 260 mm |
| Exit Diameter | 460 mm |

### Performance

| Parameter | Value |
|------------|---------|
| Expansion Ratio | 3.106 |
| Exit Mach Number | 2.674 |
| Exit Velocity | 1883 m/s |
| Exit Temperature | 1234 K |
| Mass Flow Rate | 39.48 kg/s |
| Estimated Thrust | 64.95 kN |

---

## Generated Outputs

- Mach number distribution
- Temperature profile
- Pressure profile
- Density profile
- Velocity profile

---

## Future Improvements

- Import full nozzle contour directly from CAD
- Shock-wave modelling
- Variable gas properties
- Real combustion-product modelling
- CFD validation
- Flow visualization
- Nozzle optimization studies

---

## Tools Used

- FreeCAD
- Python
- NumPy
- SciPy
- Matplotlib

---

## Author

Arisha Singhvi

Aerospace engineering and propulsion projects focused on combining CAD design, numerical methods, and engineering analysis.
