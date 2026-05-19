# Comparative Molecular Dynamics Analysis of CYP51–Ligand Systems

## Overview

This repository contains the complete comparative molecular dynamics (MD) analysis workflow for evaluating the interaction stability of:

- Farnesol–CYP51–HEME complex
- Voriconazole–CYP51–HEME complex

The simulations and analyses were performed using GROMACS and post-processed using Python/Google Colab workflows.

The repository includes:

- Processed MD trajectories
- Extracted analysis CSV files
- Comparative visualization scripts
- Statistical summaries
- Publication-quality plots

---

# Systems Analyzed

| System | Description |
|---|---|
| Farnesol | Experimental phytocompound |
| Voriconazole | Reference antifungal drug |

Both ligands were analyzed against fungal CYP51 containing the HEME prosthetic group.

---

# MD Simulation Platform

| Parameter | Value |
|---|---|
| Software | GROMACS 2024.3 |
| Force Field | AMBER-based conversion |
| Simulation Length | 200 ns |
| Water Model | TIP3P |
| Ensemble | NPT |
| Temperature | 300 K |
| Pressure | 1 atm |

---

# Repository Structure

```text
MD_CORRECTED_COLAB_EXPORT/
│
├── Farnesol/
│   ├── RMSD/
│   ├── RMSF/
│   ├── RGYR/
│   ├── DISTANCE/
│   ├── SASA/
│   ├── CONTACTS/
│   └── farnesol_cluster_size_100ps.csv
│
├── Voriconazole/
│   ├── RMSD/
│   ├── RMSF/
│   ├── RGYR/
│   ├── DISTANCE/
│   ├── SASA/
│   ├── CONTACTS/
│   └── vor_cluster_size.csv
