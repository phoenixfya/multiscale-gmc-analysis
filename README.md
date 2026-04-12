# Multiscale GMC Analysis (FIRE-2)

This project analyzes the multiscale structure of cold gas around Giant Molecular Clouds (GMCs) in FIRE-2 galaxy simulations.

## What this does
- Identifies GMC environments in a cold gas surface density map
- Computes mean, median, and 90th percentile density across spatial scales
- Visualizes how structure changes from galactic (~50 kpc) to cloud (~0.5 kpc) scales

## Key Results
- Density increases as spatial scale decreases, consistent with hierarchical gas structure
- The 90th percentile grows faster than the mean → indicates clumpy substructure
- Different GMC environments show distinct scaling behavior

## Files
- `01_multiscale_gmc_density.ipynb` — main analysis notebook

## Tools Used
- Python (NumPy, Matplotlib)
- FIRE-2 simulation data

## Next Steps
- Extend to larger GMC samples
- Compare across galaxy types
- Connect to star formation efficiency

---

**Author:** Phoenix Harrison  
Astrophysics @ UC Merced
