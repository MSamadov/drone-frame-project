# Drone Frame Design (Fusion 360)

## Overview
This project presents the design and analysis of a quadcopter drone frame developed in Fusion 360. The goal was to create a lightweight yet structurally efficient frame capable of withstanding operational loads while maintaining stability and symmetry.

## Design Features
- Symmetrical quadcopter layout for balanced flight performance  
- Integrated motor protection rings  
- Lightweight structure (~6.35 g)  
- Clean, minimal geometry for efficient manufacturing  

## Material
- Aluminum 6061  
  - Widely used in aerospace applications  
  - Good strength-to-weight ratio  
  - High corrosion resistance  

## Simulation & Analysis
A static structural analysis was performed under applied loading conditions:

- Applied force: 15 N  
- Boundary conditions: Fixed supports at mounting regions  
- Objective: Evaluate stress distribution and deformation  

### Results (Summary)
- Structure remains within safe stress limits  
- Minimal deformation under load  
- Stress concentrated near arm joints and motor mounts  

## Tools Used
- Autodesk Fusion 360 (Design & Simulation)

## Project Structure
- `design_files/` → CAD model (.f3d)  
- `images/` → Rendered views  
- `simulation/` → Analysis results  

## Future Improvements
- Topology optimization for further weight reduction  
- Material comparison (Carbon Fiber vs Aluminum)  
- Dynamic load and vibration analysis  
- Manufacturing considerations (3D printing / CNC)

## Author
Samadov Mirjahon
