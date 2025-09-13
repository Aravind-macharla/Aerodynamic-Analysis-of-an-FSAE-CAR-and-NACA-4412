✈︎ Aerodynamic Simulation Project
📌 Overview

This project conducts an in-depth CFD analysis of the NACA 4412 airfoil and a Formula SAE (FSAE) race car to evaluate and optimize their aerodynamic performance.
The work encompasses geometry generation, mesh creation, simulation setup, and detailed analysis of airflow characteristics, lift, drag, and stall behavior.
The outcomes provide valuable insights for aerospace ✈️ and automotive 🚗 aerodynamic design.

🎯 Objectives

🔹 Analyze aerodynamic performance of the NACA 4412 airfoil, including lift, drag, and pressure distribution across a range of angles of attack.

🔹 Examine stall phenomena and investigate the influence of Reynolds number on aerodynamic behavior.

🔹 Prepare and simplify complex FSAE car geometry to ensure mesh quality and CFD readiness.

🔹 Set up robust CFD simulations for the FSAE car incorporating turbulence modeling and rotating components.

🔹 Extract quantitative 📊 and qualitative 🔍 aerodynamic data to inform design improvements.

🌀 NACA 4412 Airfoil Analysis

✨ Geometry: 4% maximum camber at 40% chord, 12% maximum thickness.

📐 Geometry generated using NACA equations → refined for smoothness.

🕸️ Meshing: structured/unstructured grid with refinement near leading/trailing edges.

⚙️ Simulation: incompressible viscous flow, turbulence models (k-ε or k-ω SST).

🌬️ Boundary conditions: uniform velocity inlet, pressure outlet, no-slip walls.

📈 Parameters: α = -5° → +20°, recording Cl, Cd, Cl/Cd, Cp.

Key Findings:

⬆️ Lift rises linearly until stall, then decreases due to separation.

🏁 Drag remains low at small α, increases sharply post-stall.

📊 Cl/Cd ratio peaks at moderate α → optimal efficiency.

🔻 Cp plots: suction peaks at leading edge, trailing edge separation post-stall.

⚡ Higher Reynolds numbers delay stall → improve lift.

✅ Results validate NACA theory → useful for aerodynamic optimization.

🚗 FSAE Car Aerodynamic Analysis

🛠️ Geometry simplified → minor features (fillets, bolts) removed to cut computational cost.

🔧 CAD repaired: gaps closed, overlaps fixed, watertight model ensured.

🕸️ Meshing in ANSYS Fluent: refinement near wings, suspension, wake zones.

🪶 Boundary layers set for accurate near-wall turbulence (proper y+).

🔷 Mesh type: mix of tetrahedral, hexahedral, polyhedral → refined for accuracy.

Simulation Setup:

🌬️ Inlet velocity: 35 mph

🔄 Rotating wheels modeled using MRF zones

🌪️ Turbulence model: GEKO for complex flows

📊 Solver controls tuned for stability + convergence

Post-Processing:

⚖️ Force evaluation: lift, drag

🌊 Flow visualization: streamlines, contours, vectors, vortex structures

🌀 Identified wake regions and separation points

🚀 Guided iterative design → improved stability + efficiency

🛠️ Usage Instructions

📐 Generate/import geometry as per specifications.

🕸️ Create mesh → refine in critical aerodynamic areas, add boundary layers.

⚙️ Configure solver settings, turbulence models, and boundary conditions.

▶️ Run CFD simulations → extract Cl, Cd, Cp, and Cl/Cd.

🔍 Post-process → visualize flow fields, forces, wake structures.

🚀 Apply insights → optimize airfoil or vehicle design.

🌍 Applications

✈️ Aircraft wing design (light aircraft, UAVs, drones).

🌪️ Wind turbine blades → efficiency improvements.

🚗 FSAE race car optimization → improved stability + reduced drag.

🦽 Mobility systems → balance & lift applications.

📂 ANSYS Simulation Files

Due to file size, the ANSYS CFD/FEA simulation files are not stored in this repository.
You can download them directly from the following Google Drive link:
