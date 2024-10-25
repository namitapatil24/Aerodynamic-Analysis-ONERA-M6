# Computational Aerodynamic Analysis of ONERA M6 Wing at Transonic Conditions

**Thesis for MSc in Aerospace Dynamics, Cranfield University**  
*Author:* Namita Patil

*Supervisor:* Dr. Zeeshan Rana and Prof. Simon Prince

---

## 📖 Overview

This project presents a computational aerodynamic analysis of the ONERA M6 wing, a widely studied model for validating computational fluid dynamics (CFD) in transonic flow regimes. The study compares CFD simulations with experimental wind tunnel data to assess the accuracy of numerical models in capturing flow characteristics like shock waves, flow separation, and pressure distributions at various Mach numbers and angles of attack.

### 🏆 Key Objectives

1. **Validate** CFD simulations with ONERA M6 wind tunnel data.
2. **Analyze** pressure coefficients (Cp) and flow patterns across the wing at transonic speeds.
3. **Compare** the performance of turbulence models: Spalart-Allmaras (SA) and k-omega SST.
4. **Evaluate** CFD results for Reynolds-Averaged Navier-Stokes (RANS) and Delayed Detached Eddy Simulation (DDES) methods.

---

## ✈️ Background

The **ONERA M6 Wing** is a standard test case in aerodynamic research, particularly for transonic flows where shock waves and boundary layer interactions are complex. This project leverages the wing’s design as a benchmark for CFD validation, focusing on Mach numbers of **0.7, 0.83, and 0.9** and angles of attack of **0, 3, and 6 degrees**. 

**Key Research Questions:**
- How accurately do RANS models predict transonic flow characteristics?
- What limitations arise in simulating flow separation at higher angles of attack?
- How does turbulence model choice impact results at different Mach numbers?

---

## 🔍 Methodology

1. **Geometry and Meshing**  
   The ONERA M6 wing was modeled in **CATIA V5** and meshed using **ICEM CFD**, with boundary layer refinements to capture flow characteristics accurately.

2. **Simulation Setup**  
   - **Software:** ANSYS Fluent
   - **Models:** Spalart-Allmaras (SA) and k-omega SST turbulence models
   - **Solvers:** Steady-state RANS for initial validation; DDES was used to assess higher fidelity but faced time constraints.

3. **Validation Metrics**  
   The pressure coefficient (Cp) was computed at seven sections along the wing and compared with wind tunnel results. Special attention was paid to flow separation and shock location across different Mach and angle conditions.

---

## 📊 Findings and Analysis

- **RANS Models Performance:** Achieved close alignment with wind tunnel data at lower Mach numbers and angles of attack. RANS models demonstrated limitations in capturing shock and separation regions accurately at higher Mach and angle settings.
  
- **Turbulence Models Comparison:**  
   - **Spalart-Allmaras (SA):** Best suited for lower angles of attack, provided reasonable accuracy for pressure distributions.
   - **k-omega SST:** Offered improved predictions in regions of separated flow but was still limited in high Mach number cases.

- **DDES Analysis:** DDES was only partially utilized due to computational time constraints. However, it shows potential for capturing detailed flow structures in separated regions if implemented with a smaller timestep.

---

## 🛠️ Tools and Technologies

- **Geometry & Meshing:** CATIA V5, ICEM CFD
- **CFD Simulation:** ANSYS Fluent
- **Turbulence Models:** Spalart-Allmaras (SA), k-omega SST
- **Solution Techniques:** RANS (steady-state), DDES (time-dependent)

---

## 📌 Key Contributions

1. **Methodology for CFD Validation** using a benchmark geometry and experimental data for transonic conditions.
2. **Recommendations for Future Work:** A smaller timestep and further DDES analysis are suggested for capturing detailed flow structures at high Mach numbers and angles of attack.

---

## 🧪 Data and Results

### Pressure Coefficient (Cp) Plots
Comparisons of Cp across seven sections along the wing, showing CFD versus wind tunnel data. Detailed plots can be found in the [results folder](./results) of this repository.


---

## 📝 Future Scope

Future studies can:
- Implement **finer timestep DDES** to better capture shock-induced separation.
- Explore **higher fidelity turbulence models** to refine flow separation and shock predictions.

---

## 📫 Contact

For inquiries or further information on this project, please feel free to connect:

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-blue?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/namita-rajendra-patil/) [![Email](https://img.shields.io/badge/-Gmail-red?style=flat&logo=gmail&logoColor=white)](mailto:namitapatil1995@gmail.com)

---

*This project was submitted as part of the MSc in Aerospace Dynamics at Cranfield University.*

---

