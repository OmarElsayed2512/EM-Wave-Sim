**Electromagnetic Wave Simulation**

## Team Members
- Omar Elsayed (202100597)
- Aser Osama (202101266)
- Saifelden Mohamed (202100432)
- Mahmoud Mohamed (202100678)

## Course Information
**Course:** CIE 327 – Communications and Information Engineering  
**Institution:** Zewail City of Science and Technology  
**Date:** January 8, 2024

## Introduction
This project focuses on the simulation of electromagnetic wave propagation using mathematical derivation and numerical methods. The study includes deriving the electromagnetic wave equations, solving them in one and two dimensions, and implementing these solutions in a MATLAB simulation.

## Derivation of the EM Wave Equation
The electromagnetic wave equations are derived using Maxwell’s equations. The derivation combines Gauss's Law for Electricity and Magnetism, Faraday's Law of Induction, and Ampère’s Law with Maxwell’s Addition.

## PDE Discretization
The one-dimensional electromagnetic wave equation is discretized using a finite difference scheme. This discretized form is then expressed in matrix-vector form for numerical solutions.

## CFL Condition
The Courant-Friedrichs-Lewy (CFL) condition ensures numerical stability. The condition for our simulation is adjusted to \( \text{CFL} = \frac{c \cdot \Delta t}{h} \leq 0.5 \) for two dimensions.

## MATLAB Simulation
### Overview
The MATLAB GUI simulates electromagnetic interference using PDE discretization. The interface includes several panels for setting simulation parameters and visualizing results.

### Panels
1. **Point Charge Properties Panel:** Modify amplitude, frequency, and position of the point charge.
2. **Area Boundary Condition Panel:** Define the shape of the simulation region.
3. **Simulation Properties Panel:** Adjust duration and number of points.
4. **Electric Field Properties Panel:** Set relative permeability and permittivity.
5. **Simulation Type Panel:** Choose the type of simulation (Magnitude of E, Ex, or Ey).

### Running the Simulation
1. Set parameters in each panel.
2. Click "Update Simulation Settings."
3. Choose visualization mode.
4. Optionally, select "Save as Video."
5. Click "Run Simulation."

## Important Code Snippets
- Generation of Ex and Ey fields.
- Calculation of total E field.

## Disclaimer
This program is provided as-is. The user is responsible for any modifications needed for specific use cases.

## References
1. Huang, H. (n.d.). Numerical methods for PDE (two quick examples). Retrieved from Arizona State University: [link](https://www.public.asu.edu/~hhuang38/pde.pdf)

---

This README provides an overview of the project, the mathematical foundation, and instructions for using the MATLAB simulation. For further details, refer to the project documentation and the provided references.
