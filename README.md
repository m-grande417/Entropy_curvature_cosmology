<img width="1800" height="1800" alt="0D89EE47-560A-4112-A2CF-50EA5831EE6B" src="https://github.com/user-attachments/assets/768092bd-dca2-49f1-a0b8-e27ca676046f" />
# Entropy_curvature_cosmology
Thermodynamic field–driven cosmology replacing ΛCDM expansion with an entropy–curvature law, predicting testable large-scale structure, BAO, and CMB signatures.
# Entropy–Curvature Cosmology (ECC)

## Quickstart
```bash
python -m venv .venv && source .venv/bin/activate
pip install -r requirements.txt
python examples/run_pde_2d.py --steps 100 --out fig_entropy_field.png
# Entropy Curvature Cosmology (ECC)

**Author:** Melanie Grande  
**Latest Version:** Illustrated & Interleaved Edition  
**License:** CC BY-NC 4.0  

---

## 📜 Overview
**Entropy Curvature Cosmology (ECC)** is a unified thermodynamic and topological framework for understanding large-scale cosmic expansion, structure formation, and anisotropy—without invoking dark energy or inflation.  

ECC proposes that:
- A **temperature-modulated entropy field** directly sources curvature.
- A **single scaling law** can match multiple cosmological observations:
  - Type Ia supernova distances (Pantheon+, RMSE ≈ 0.19 mag)  
  - CMB spectral tilt (n_s ≈ 0.963)  
  - Baryon Acoustic Oscillation (BAO) scale offset (~110 Mpc)  
  - Isotropic birefringence (β ≈ 0.30° ± 0.11°)  

The model also predicts **testable near-term phenomena** such as cold-spot activation, void lensing, and high-z distance modulus drift.

---

## 📊 Key Results

| Observable           | ECC Prediction                        | Observations Match |
|----------------------|---------------------------------------|--------------------|
| SN Ia Distances      | RMSE ≈ 0.19 mag                        | ✅                  |
| CMB Spectral Tilt    | n_s ≈ 0.963                            | ✅                  |
| BAO Scale            | ~110 Mpc (systematic under-reach)      | ⚠️ Falsifiable      |
| Birefringence        | β ≈ 0.30° ± 0.11°                      | ✅                  |
| Weak Lensing         | ±7% of DES amplitude; void lensing     | ✅                  |

---

## 📂 Repository Structure

---

## 🖼 Flagship Figures

| Figure | Description | Thumbnail |
|--------|-------------|-----------|
| **1** | Supernova Luminosity–Redshift — Fits Pantheon+ without dark energy. | ![Fig 1](figures/fig1.jpg) |
| **2** | BAO-like Rings — Thermally damped entropy waves (~90 Mpc). | ![Fig 2](figures/fig2.jpg) |
| **3** | Weak Lensing — From entropy curvature gradients; predicts void lensing. | ![Fig 3](figures/fig3.jpg) |
| **4** | Early Entropy Growth — Aligned with CMB cold spots. | ![Fig 4](figures/fig4.jpg) |
| **5** | Polarization Rotation — From filament chirality; matches Planck birefringence. | ![Fig 5](figures/fig5.jpg) |

---

## 📚 How to Use

1. **Read the theory** in `ECC_Illustrated_Interleaved.pdf` for the full model and inline figures.
2. **Use the predictions** to compare against observational data from:
   - **Euclid**
   - **JWST**
   - **LSST**
3. **Extend the model**:
   - Adapt the PDE framework to include additional cosmological parameters.
   - Test falsifiable predictions with new observational datasets.

---

## 🔬 Methods Summary
- Finite-difference PDE evolution with periodic boundaries.
- Entropy scaling: \( T \propto (1+z) \) → \( \alpha(z) \propto (1+z)^m \).
- Observables derived from \( H(z) \), ∇²E, and polarization effects.

---

## 📌 Citation

If you use ECC in your research, please cite:

> Grande, M. (2025). *Entropy Curvature Cosmology: A Unified Thermodynamic and Topological Framework*. Illustrated Interleaved Edition.

---

## 📜 License
This work is licensed under a Creative Commons Attribution-NonCommercial 4.0 International License.

---
<img width="3510" height="2490" alt="image" src="https://github.com/user-attachments/assets/1e6962ae-05ca-45d8-a61f-3f5a1cf50da3" />
