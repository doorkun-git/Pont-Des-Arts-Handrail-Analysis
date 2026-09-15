# Pont des Arts Handrail Redesign

MATLAB analysis of a simply supported handrail section based on the Pont des Arts bridge.

## Project Overview

This project evaluates the structural behavior of a proposed handrail cross-section under distributed and concentrated loading. The analysis includes:

- Shear-force diagram
- Bending-moment diagram
- Maximum bending stress
- Maximum shear stress
- Elastic curve
- Maximum beam deflection
- Material and cross-section evaluation

## Tools Used

- MATLAB
- Symbolic Math Toolbox
- Beam mechanics
- Bending and shear stress analysis

## Analysis Assumptions

- Simply supported beam
- Beam length: 2.8 m
- Uniform distributed load: 1300 N/m
- Three concentrated loads: 500 N each
- Elastic modulus: 190 GPa
- Moment of inertia: 216667e-12 m^4
- Linear elastic behavior
- Small-deflection beam theory

## Running the Code

Open `pont_des_arts_analysis.m` in MATLAB and run the script. The program calculates the maximum shear force, bending moment, normal stress, shear stress, and deflection.

## Results

The script generates:

1. Shear-force and bending-moment diagrams
2. An elastic-curve plot
3. Command-window results for maximum stresses and deflection

## Note

This is an educational beam-analysis model based on simplified loading and support assumptions. It is not a complete structural design or safety certification.
