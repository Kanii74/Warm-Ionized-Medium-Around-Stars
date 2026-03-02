# Warm Ionized Medium Around Stars

This project estimates the size of H II regions (Strömgren spheres) around main-sequence stars of spectral type O, B, A, F, G, K, and M.

Using blackbody radiation theory and photoionization physics, the hydrogen ionizing photon flux and resulting H II region sizes are calculated.

---

## Overview

The work includes:

1. Synthetic Planck curves for different stellar spectral types  
2. Calculation of hydrogen ionizing photon flux  
3. Estimation of Strömgren radius  
4. A histogram comparison of H II region sizes  
5. Physical interpretation of the results  

---

## 1. Planck Curves

The Planck function used:

Bν(ν, T) = (2hν³ / c²) * 1 / (exp(hν / kT) − 1)

- Frequency plotted in Hz  
- Planck function plotted in J s⁻¹ m⁻² sr⁻¹ Hz⁻¹  
- Log scale used for clarity  
- 1 Rydberg frequency marked with a dashed vertical line  

This shows how hotter stars emit significantly more high-frequency radiation.

---

## 2. Hydrogen Ionizing Photon Flux

The ionizing photon flux (Q) is calculated by integrating the spectrum above the hydrogen ionization threshold (1 Rydberg).

This determines how many ionizing photons are emitted per second by each spectral type.

---

## 3. Strömgren Radius

The H II region size is calculated using:

RS = [ (3Q) / (4π αH n²) ]^(1/3)

Where:

- Q = ionizing photon flux  
- αH = recombination coefficient  
- n = hydrogen number density  

The result is converted to parsecs.

---

## Results Summary

- O and B type stars produce the largest H II regions.
- Later type stars (A–M) produce significantly smaller ionized regions.
- The size difference spans many orders of magnitude.

---

## Physical Interpretation

- Massive O and B stars emit strong ultraviolet radiation.
- This radiation ionizes the surrounding interstellar medium.
- Bright warm ionized medium (WIM) indicates recent or ongoing massive star formation.
- Typical WIM temperatures range between ~6000 K and 12000 K.

