---
layout: default
title: "Codes and Databases"
permalink: "/codes/"
---

# Codes and Databases

This page gathers the training datasets, benchmarks, and model of my publications.

---

## 🧠 Machine Learning Potentials

### 🔹 AIQM2 / Δ-learning datasets

**Dataset:** CO₂ on water clusters  
**Description:** Configurations sampled from ab initio MD and optimized at MP2/TZ level for benchmarking Δ-learning corrections to AIQM2.  
**Zenodo DOI:** [10.5281/zenodo.XXXXXXX](https://doi.org/10.5281/zenodo.XXXXXXX)  

**Files included:**  
- `co2_water_clusters.xyz` (training geometries)  
- `co2_water_energies.csv` (reference energies, ΔE wrt AIQM2)  
- `split_indices.json` (train/validation/test indices)

---

### 🔹 H₂O–CO₂ potential (ML extension)

**Dataset:** Combined dataset of CO₂ adsorption and diffusion on amorphous water ice surfaces.  
**Zenodo DOI:** [10.5281/zenodo.YYYYYYY](https://doi.org/10.5281/zenodo.YYYYYYY)

**Content overview:**  
| File | Description |
|------|--------------|
| `train_set.xyz` | Training configurations |
| `test_set.xyz` | Independent validation |
| `forces.csv` | Reference gradients (CCSD(T)/TZ) |

---

### 🔹 Transfer learning examples

**Model:** SchNet + Q (charged species adaptation)  
**Zenodo DOI:** [10.5281/zenodo.ZZZZZZZ](https://doi.org/10.5281/zenodo.ZZZZZZZ)  

> Includes model weights, normalization parameters, and test scripts for use with i-PI and ASE.

---

## 📦 Repository Links

| Resource | Description | Link |
|-----------|--------------|------|
| 🧩 GitHub — Model Training | Python scripts and workflows for Δ-learning setup | [github.com/username/aiqm2-delta](https://github.com/username/aiqm2-delta) |
| 🧬 GitHub — Utilities | Scripts for sampling and dataset preparation | [github.com/username/ice-tools](https://github.com/username/ice-tools) |

---

## 📘 Citation
If you use any of these datasets, please cite the corresponding Zenodo DOI and the associated publication
