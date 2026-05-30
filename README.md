# Decomposition-of-curves-into-peaks
Automated computational model for the decomposition and parameter extraction of thermoluminescence curves (Temperature range: 70 K — 320 K)

<img width="1315" height="1629" alt="изображение" src="https://github.com/user-attachments/assets/a1a69df0-8338-46f5-8873-53dee1295d6c" />


The model, implemented in Python, integrates all stages of data processing – from baseline correction and multi-Gaussian peak fitting to the calculation of physically meaningful parameters such as activation energy (Ea), number of monomer units (N), and segment length (l) – into a single, streamlined pipeline. Training on a reference set of forty manually processed curves using K-means clustering enabled the model to learn characteristic peak parameters for six relaxation transitions (γ₁, γ₂, β₁, β₂, α₁, α₂).

Note: initially the main usage meant the processing of plasma-induced thermoluminescence curves from ultra-high molecular weight polyethylene (UHMWPE) reactor powders

To use the code, download it first. The step-by-step instructions will be inside the file.
