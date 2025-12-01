# Numerical Modeling of QCL and Kerr Frequency Combs

**Author:** Haozheng  
**Topic:** Computational Physics / Nonlinear Optics  
**Status:** 🚧 *Active Development (Code Refactoring & Uploading)*

---

## 📄 Overview
This repository serves as the supplementary portfolio for my independent research on the numerical modeling of optical frequency combs. It focuses on two distinct formation mechanisms: **Quantum Cascade Laser (QCL) combs** (Frequency Modulated) and **Kerr microresonator combs** (Amplitude Modulated).

Currently, the **Technical Note** detailing the theoretical derivations and simulation results is available for review. The source code (Python/Julia solvers) and reproduction scripts are currently being cleaned up and documented for public release. They are scheduled to be fully uploaded by **early January 2026**.


### Abstract
This study investigates the numerical modeling of quantum cascade laser (QCL) combs and Kerr combs. It bridges the gap between mean-field theories and numerical implementation, specifically:
* **Kerr Combs:** Implementing the **Lugiato-Lefever Equation (LLE)** to reproduce the evolution of Dissipative Kerr Solitons (DKS), tracing the path from chaotic modulation instability to stable soliton formation.
* **QCL Combs:** Utilizing the **Extendon Nonlinear Schrödinger Equation (NLSE)** to model the frequency-modulated (FM) nature of QCL combs and analyzing spectral locking under RF modulation.

---

## 🔜 Upcoming Content (Roadmap)
The following resources are being prepared for upload to this repository:

1.  **LLE Solver (Python/PyCORe):**
    * Implementation of the split-step Fourier method for solving the dimensionless LLE.
    * Scripts to reproduce the "Turing Pattern" to "Soliton" transitions (referencing Fig. 7 & Fig. 8 in the Note).
    
2.  **QCL Dynamics Solver:**
    * Numerical solution of the Extendon NLSE for FM comb generation.
    * RF-modulation injection locking simulations.

3.  **Visualization Tools:**
    * Scripts for generating 2D spectral density maps and instantaneous frequency profiles.

---

## 📊 Preview of Results
*(Excerpts from the Technical Note)*

> **Dissipative Kerr Soliton Formation:**
> The simulation captures the critical transition where the chaotic intracavity field converges into a stable dissipative Kerr soliton (DKS) within the red-detuned region.
> *See Technical Note Section 3.3 for full discussion.*

> **RF-Modulated QCL Spectra:**
> Analysis of the power spectrum density map under different modulation detunings, revealing the conditions for stable, broadband operation.
> *See Technical Note Section 2.3.*

---

## Contact
If you have questions regarding the methodology or code availability prior to the full upload, please feel free to contact me via email included in my application materials.
