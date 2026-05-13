# PSHA Continuous GMPE Uncertainty – Reproducibility Package (2026)

Reproducibility package for a sampling-based framework for continuous propagation of GMPE uncertainty in Probabilistic Seismic Hazard Analysis (PSHA).

---

## 📄 Associated paper
**Continuous Propagation of Ground Motion Model Uncertainty in Probabilistic Seismic Hazard Analysis**  
João M. C. Estêvão (2026)

(submitted to a peer-reviewed journal)

---

## 🎯 Purpose

This repository provides a reproducibility package enabling:

- Regeneration of the numerical results presented in the paper
- Full sample-level traceability of internal GMPE uncertainty
- Inspection of rupture geometry and ground-motion computations

Outputs include:
- Excel datasets  
- Sampling diagnostics  
- Google Earth (KML) visualization of rupture realizations  

---

## ⚙️ Requirements

- Windows (64-bit)
- .NET Framework 4.x (included in most Windows 10/11 systems)
- Microsoft Excel (for data export)
- Google Earth (for KML visualization)

---

## 🧩 Application context

The executable is part of the broader research platform **SeismicTester**, designed for seismic hazard analysis applications.

In this repository, the application is distributed in a **controlled configuration specific to this paper**, ensuring direct consistency with published results.

The initial selection menu is fixed to:

> *Continuous Propagation of Ground Motion Model Uncertainty in Probabilistic Seismic Hazard Analysis*

This ensures a high level of transparency at the computational level.

---

## 📥 Download

👉 [Download from Releases (ZIP)](https://github.com/jmcestevao/psha-gmpe-uncertainty-2026/releases)


**File:** `SeismicTester_v1.0.zip`

---

## ▶️ How to run

1. Download the application from the Releases section  
2. Extract the ZIP file  
3. Keep all files in the same folder  
4. Run `SeismicTester.exe`  
5. Click **START**  
6. Select the desired **Paper case**  

Optional configuration:
- Sampling method  
- Number of samples  
- Output options (Excel, KML)  

Click **START** to execute the analysis.

✅ No external input files required.

---

## 📄 Documentation

👉 [Application overview (PDF)](https://github.com/jmcestevao/psha-gmpe-uncertainty-2026/blob/main/docs/Continuous%20Propagation%20of%20Internal%20GMPE%20Uncertainty_GitHub.pdf)

The document provides:

- Conceptual workflow description  
- Explanation of sampling strategies  
- Validation and diagnostics  
- Interpretation of individual samples via Google Earth  

---

## 📊 Case studies

All paper cases are embedded:

- **Case 1** – One-dimensional validation  
- **Case 2** – Multidimensional finite source (near-field)  
- **Case 3** – Multidimensional finite source (far-field)  

Interaction is fully graphical.

---

## 📈 Outputs

The application automatically generates:

- Exceedance probability curves  
- Relative variation plots  
- Excel files with sampled variables  
- Sampling diagnostics  
- KML files for rupture visualization  

---

## 🔁 Reproducibility

All results from the paper can be reproduced directly.

The workflow ensures:

- Consistency with published case definitions  
- Explicit control of sampling configuration  
- Traceability through all generated outputs  
- Sample-level inspection of rupture geometry and GMPE inputs  

---

## ⚠️ Notes

- Windows (64-bit) only  
- Portable executable (no installation required)  
- Keep `SeismicTester.exe.config` in the same folder  
- Excel required for data export  
- Google Earth required for visualization  
- Source code not included (under development)

---

## 📖 Reference

If you use this repository, please cite:

**Estêvão, J. M. C. (2026)**  
Continuous Propagation of Ground Motion Model Uncertainty in Probabilistic Seismic Hazard Analysis  

---
