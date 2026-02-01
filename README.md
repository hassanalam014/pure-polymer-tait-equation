# 📘 Pure Polymer Tait Equation

A Python project for fitting and analyzing the **Tait equation of state** for pure polymers using experimental pressure–volume–temperature (PVT) data.

The Tait equation is widely used in polymer science to model how **specific volume** of a polymer changes with **temperature and pressure** — a key property in polymer processing, materials design, and thermodynamic analysis.

---

## 📌 Overview

This repository contains Python scripts that:

- Load and visualize experimental polymer density/PVT data
- Fit the **Tait equation of state** to that data
- Generate plots and results for further analysis

📂 Files include:
- `fit_Tait_Eq.py` — core script to fit Tait equation
- `loadExperimentalData.py` — data loader utility
- `fit_density.py` — density fitting helper
- `plot_densities_Group.py` and `P4D_plot_densities_PS.py` — plotting utilities
- `all_p_params.py` — parameter extraction & summary

---

## 🧠 What is the Tait Equation?

The **Tait equation** is an empirical P‑V‑T model that describes how the specific volume of a polymer changes with temperature and pressure. It is particularly useful due to its simplicity and good fit to polymer data.

The general form used in polymer science relates specific volume at given conditions to zero‑pressure volume and parameters fit to experimental data.

---

## 🚀 Getting Started

### 🔧 Requirements

Make sure you have:

- Python 3.6+
- `numpy`, `matplotlib`, `scipy`, `pandas` (or similar scientific stack)

Install dependencies using:

```bash
pip install -r requirements.txt
