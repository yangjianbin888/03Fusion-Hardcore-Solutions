# Nb₃Sn CICC Superconducting Magnet for Tokamak – 13T High Field Stress Management & Quench Fast Protection

> **Author**: [yangjianbin888]
> **Date**: 2026-06-23
> **License**: CC BY-SA 4.0 (open for engineering use with attribution)
> **Keywords**: Nb3Sn, CICC, Tokamak, 13T, Stress Management, Quench Protection, Fusion Magnet

---

## 1. Problem Statement

A 13T-class toroidal field (TF) magnet using Nb₃Sn Cable-in-Conduit Conductor (CICC) faces two critical failure modes:
- **High-field electromagnetic stress** → brittle Nb₃Sn fracture (strain limit ≈0.2–0.3%)
- **Quench event** → localized Joule heating, hotspot >300K if not protected within <100ms

ITER (~11.8T) is marginal; CFETR/DEMO (>13T) requires explicit multi-field co-design.

---

## 2. Key Design Parameters (Reference Values)

| Parameter | Value | Note |
|---|---|---|
| Central Field B₀ | 13.0–13.2 T | @4.5K |
| Operating Current I_op | 40 kA | Margin >20% over I_c |
| Coil Inductance L | ~180 H | TF coil |
| Stored Energy | ~144 MJ | ½LI² |
| Nb₃Sn Critical Strain ε_c | 0.20% (virgin) → 0.50%+ (Ti-doped) | A15 phase |
| CICC Strand Dia | 0.82 mm | 486-filament, internal-Sn |
| Jacket Material | 316LN SS (N-bearing) | σ₀.₂≈600MPa @4.5K |
| Coolant | Supercritical He @4.5K, 0.6MPa | |
| Quench Propagation Velocity Vq | 10–50 m/s | Nb₃Sn CICC |
| Max Allowable Terminal Voltage | ≤4.5 kV | insulation limit |
| Target Detection+Action Time | <100 ms | FBG+voltage hybrid |

---

## 3. High-Field Stress Management (Mechanical)

### 3.1 Strain-Sensitive Jc Model (Summers-type)
