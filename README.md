# Supersonic-Nozzle-Design-and-Simulation

##  What is a Supersonic Nozzle?

A **supersonic nozzle**, or **converging-diverging (C-D) nozzle**, is a device used to accelerate gases to supersonic speeds by taking advantage of compressible flow behavior. These nozzles are crucial in aerospace propulsion, wind tunnel design, and high-speed fluid delivery systems.

This project focuses on designing and simulating a 2D axisymmetric supersonic nozzle using **ANSYS Fluent**, with the goal of identifying the most efficient design capable of achieving **maximum exit velocity** under given stagnation and outlet pressure conditions. Future plans include **manufacturing the optimized nozzle using additive manufacturing** techniques.

---

##  Objectives

- Design an initial nozzle geometry analytically using isentropic relations.
- Set up and run 2D compressible flow simulations in ANSYS Fluent.
- Analyze and optimize the nozzle shape to maximize outlet velocity.
- Refine the nozzle using the **Method of Characteristics** to improve expansion flow quality.
- Prepare for future integration of additive manufacturing once the simulation results are finalized.

---

##  Initial Nozzle Design

- **Total Length:** 20 mm  
- **Throat Diameter:** 1 mm (length: 1 mm)  
- **Converging Section:** 10 mm long  
- **Diverging Section:** 5 mm long  
- **Profile:** Linear profile (to be improved using characteristic equations)  

---

##  CFD Simulation Details

- **Software:** ANSYS Fluent  
- **Type:** 2D Axisymmetric, Steady-State, Compressible  
- **Solver:** Density-based  
- **Gas Model:** Ideal gas  
- **Boundary Conditions:**
  - Inlet: Stagnation pressure and temperature
  - Outlet: Static pressure
- **Discretization:** Second-order upwind for pressure, density, and momentum

---

##  Optimization Approach

- Track key outputs:
  - Mach number at outlet
  - Velocity contours
  - Shock formation and flow separation
- Compare results for different nozzle angles and lengths
- Implement **characteristic method** in future versions to smoothen expansion fans and eliminate oblique shocks

---

##  Current Status

 - CFD simulation is ongoing  
 - Geometry optimization is in progress  
 - Manufacturing phase yet to begin (pending simulation results)

---

##  Future Work

- Complete refinement of nozzle geometry using analytical and numerical techniques
- Validate with experimental or reference data (if available)
- Begin **additive manufacturing planning** based on the optimized design
- Investigate performance under varying operating conditions (if extended)





