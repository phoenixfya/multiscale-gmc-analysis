# Multiscale GMC Analysis (FIRE-2)

This project investigates how cold gas surface density scales with spatial size around Giant Molecular Clouds (GMCs) in a FIRE-2 galaxy simulation.

## Scientific Question
How does cold gas density vary across spatial scales around GMC environments, and do different GMCs exhibit distinct scaling behavior?

## Approach
This work analyzes two GMC environments identified in a 2D cold gas surface density map. Each region is examined across progressively smaller spatial windows (50, 5, 1, and 0.5 kpc).

For each scale, the following statistics are computed:
- Mean density  
- Median density  
- 90th-percentile density  

Density–scale relations are then compared between GMC environments, and approximate power-law trends of the form  
Σ ∝ R^(-α) are fitted.

## Main Results
- Cold gas surface density increases toward smaller spatial scales in both GMC environments  
- The 90th percentile grows faster than the mean, indicating increasingly dominant dense substructure at small scales  
- The two GMC environments exhibit distinct scaling behavior, suggesting that GMC surroundings are not self-similar and may reflect different dynamical conditions

- ## Key Result: Density Scaling Law

<img width="2065" height="1430" alt="download (4)" src="https://github.com/user-attachments/assets/44463ef6-231a-42b1-b85c-5075c5f29a29" />
<img width="4359" height="1733" alt="download (2)" src="https://github.com/user-attachments/assets/c6de1704-6b27-4b9e-bd32-08d3beaed9d2" />
<img width="4359" height="1733" alt="download (3)" src="https://github.com/user-attachments/assets/3328797f-128c-4597-bf9a-16e1c235f89e" />

Cold gas surface density follows an approximate power-law scaling with spatial scale (Σ ∝ R^(-α)), with different GMC environments exhibiting distinct slopes (α ≈ 0.40 vs 0.61), indicating variation in substructure and density concentration.

## Methods and Tools
- Python  
- NumPy  
- Matplotlib  
- FIRE-2 simulation data  

## Files
- `01_multiscale_gmc_density.ipynb` — main analysis notebook  

## Future Work
This initial analysis focuses on a small number of GMC environments within a single FIRE-2 simulation.

A natural extension of this work is to scale the analysis to a larger statistical sample of GMCs across multiple galaxies, enabling a more robust characterization of density–scale relations and their environmental dependence.

In particular, I am interested in exploring how multiscale gas density structures are influenced by underlying dark matter distributions, including potential connections between halo substructure and the emergence of dense gas regions.

Future work will aim to:
- Quantify scaling exponents (Σ ∝ R^(-α)) across large GMC samples  
- Compare variations across different galactic environments  
- Investigate whether dark matter-driven structure (e.g., subhalos or potential fluctuations) leaves an imprint on cold gas morphology and fragmentation  

This direction connects small-scale baryonic structure (GMCs and star-forming regions) with larger-scale dark matter dynamics, and aims to contribute toward a more unified understanding of structure formation across scales in galaxies, from dark matter halos down to star-forming clouds.

**Author:** Phoenix Harrison  
Astrophysics Undergraduate Researcher, UC Merced  
Interested in galaxy formation, GMC structure, and dark matter
