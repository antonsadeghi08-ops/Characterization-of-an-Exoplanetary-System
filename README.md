# Characterization-of-an-Exoplanetary-System
# Characterization of an Exoplanetary System

> **Hobby / Final Project**  
> A personal, educational project created as part of **Rymdforskarskolan 2025**.  
> This is **not intended for professional research**.

---

## Overview

This Python script implements a **mathematical model** to estimate the physical parameters of exoplanets and their host stars.  

It calculates:

- **Stellar parameters:** distance, absolute magnitude, luminosity, radius, mass, and density  
- **Planetary parameters:** mass, radius, volume, density, and effective temperature  
- **Orbital parameters:** semi-major axis, orbital speed  

All formulas are derived from **lectures in astronomy and astrophysics at Rymdforskarskolan 2025**.  

> **Assumptions:**  
> - Two-body system (star + planet)  
> - Perfectly circular orbits  
> - Simplified physics; results are approximate

---

Packages:

> - numpy – numerical calculations
> - uncertainties – automatic error propagation
> - matplotlib – optional, used if plotting is added

 ## Run the script:

python Felmarginaler.py

The script prints calculations to the console, including propagated uncertainties:

> - Distances, magnitudes, and luminosities
> - Stellar and planetary radii and masses
> - Orbital velocities and semi-major axes
> - Planetary and stellar densities
> - Estimated effective planetary temperature
> - Example Output
> - Avstånd: 187.34 [pc]
> - Absolut magnitud: 7.2 +/- 0.02
> - Luminositet: 1.2e26 [W]
> - Stjärnradie: 5.1e8 [m]
> - Stjärnmassa: 1.9e30 kg (0.95 M_sun)
> - Planetmassa: 1.2e27 kg
> - Planetär radie: 7.1e7 [m]
> - Planetär densitet: 1300 [kg/m3]
> - Halva storaxeln: 1.5e11 [m] (1.0 AU)
> - Planetens radialhastighet: 30000 [m/s]
> - Effektiv planettemperatur: 290 K
> - Disclaimer

 ## Note
Educational purposes only – final project for Rymdforskarskolan 2025
Simplified assumptions (circular orbits, 2-body system)
Not suitable for scientific publication or exoplanet research

 ## Author

Final project at Rymdforskarskolan 2025 – a hobby exploration of exoplanetary system modeling in Python.
