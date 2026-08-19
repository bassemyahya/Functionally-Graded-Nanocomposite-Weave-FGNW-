# Functionally Graded Nanocomposite Weave (FGNW)
### Advanced Propulsion Cowlings & Relativistic Spacecraft Shielding Architecture

[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.22007080.svg)](https://doi.org/10.5281/zenodo.22007080)
[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-lightgrey.svg)](https://creativecommons.org/licenses/by/4.0/)

---

## 📌 Overview
This repository contains the numerical verification codes, 3D interactive multiphysics simulator, and structural mesh models for the **Functionally Graded Nanocomposite Weave (FGNW)** framework authored by **Basem Yehia**.

The material system establishes an atomic interphase gradient transitioning from an ultra-inert crystalline Iridium outer barrier into an auxetic 3D hexagonal MWCNT/BNNT core to eliminate interfacial shear delamination and endure extreme space environments (20°C to 2400°C).

---

## 🔬 Official Publication & Citing
If you reference this work or utilize the simulation suites, please cite the published technical whitepaper:

> **Yehia, B. (2026).** *Functionally Graded Nanocomposite Weave (FGNW) for Sub-Light Propulsion & Relativistic Shielding Systems*. Zenodo. [https://doi.org/10.5281/zenodo.22007080](https://doi.org/10.5281/zenodo.22007080)

---

## 🚀 Repository Contents
* `fgnw_multiphysics_simulator.py`: Comprehensive Python multiphysics and chemical kinetics evaluation engine.
* `FGNW_Interactive_3D_Multiphysics_Bilingual.html`: WebGL / Three.js real-time interactive 3D stress & thermal simulator (Bilingual English/Arabic).
* `fgnw_hexagonal_monolith_mesh.obj`: 3D CAD mesh file for the hexagonal honeycomb monolithic structure.

---

## 💻 Running the 3D Interactive Simulator
You can directly open `FGNW_Interactive_3D_Multiphysics_Bilingual.html` in any modern web browser or run the Python simulation script:

```bash
python fgnw_multiphysics_simulator.py
