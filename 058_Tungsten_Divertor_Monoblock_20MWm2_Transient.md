# 托卡马克钨偏滤器单块构件：>20MW/m²瞬时热斑、循环热疲劳裂纹防控
# Tokamak Tungsten Divertor Monoblock: >20MW/m² Transient Heat Flux & Thermal Fatigue Control

> **Author**: [yangjianbin888]
> **Date**: 2026-06-23
> **Series**: 03-Fusion-Hardcore-Solutions / No. 058
> **Keywords**: Tungsten Divertor, Monoblock, Transient Heat Load, Thermal Fatigue, Crack Initiation, CFETR

---

## 1. Problem Statement

The divertor is the "exhaust vent" of the tokamak, bearing the brunt of particle and energy exhaust.
Unlike the first wall, the divertor faces **extreme transient heat fluxes** that conventional cooling cannot handle.

- **Transient Heat Flux**: >20 MW/m² (ELMs, Edge Localized Modes)
- **Steady-State Load**: 10–15 MW/m² (during flat-top)
- **Critical Failure Mode**: Surface melting, crack initiation, and monoblock detachment due to cyclic fatigue.

ITER-style monoblocks are marginal; CFETR/DEMO requires a fundamental redesign.

---

## 2. Key Design Parameters (Reference Values)

| Parameter | Value | Note |
|---|---|---|
| Component Type | Tungsten Monoblock | Single piece construction |
| Peak Transient q" | **20–30 MW/m²** | ELM strike point |
| Pulse Duration | 0.1–1 ms | Typical ELM duration |
| Surface Temp Limit | <2000°C | Below W melting (3422°C) but above recrystallization |
| Bonding Interface | W / Cu interlayer / CuCrZr pipe | Active cooling |
| Fatigue Cycles | >10,000 cycles | Full power operation lifetime |

---

## 3. Transient Heat Spot Management (>20 MW/m²)

### 3.1 Surface Micro-Texturing (Ripple Structure)
Smooth surfaces concentrate heat into "hot spots".
- **Design**: Machine micro-ripples or castellated structures on the W surface.
- **Effect**: Disperses the incident angle of particles, reducing peak energy density by spreading the load.

### 3.2 Advanced Cooling Geometry
Standard straight pipes fail at >20 MW/m².
- **Swirl Tape Inserts**: Insert twisted tapes inside cooling tubes to induce turbulent flow (swirl flow).
- **Impinging Jet Cooling**: Direct high-speed coolant jets onto the backside of the W block for maximum heat removal.

### 3.3 Thermal Inertia Buffering
- **Concept**: Increase the thickness of the tungsten armor locally at strike points.
- **Mechanism**: Use the high heat capacity of W to absorb the transient pulse before the heat reaches the cooling channel.

---

## 4. Cyclic Thermal Fatigue & Crack Prevention

### 4.1 Interfacial Stress Mitigation
The mismatch in thermal expansion (CTE) between W (4.5×10⁻⁶/K) and CuCrZr (17×10⁻⁶/K) causes delamination.
- **Solution**: Introduce a **Gradient Interlayer** (e.g., W-Cu, CuCrZr).
- **Target**: Keep interfacial stress < 150 MPa during 10,000 cycles.

### 4.2 Crack Arrest Mechanisms
Cracks inevitably initiate at the surface.
- **Material**: Use **Potassium-doped Tungsten (W-K)**.
- **Mechanism**: Potassium bubbles pin grain boundaries and act as "crack arresters," preventing small cracks from propagating through the bulk.

### 4.3 Residual Stress Relief
- **Manufacturing**: Post-bonding heat treatment to relieve residual stresses from HIP (Hot Isostatic Pressing).
- **Operation**: Limit surface temperature swings to avoid exceeding the yield strength of the bonding layer.

---

## 5. Erosion and Melting Control

### 5.1 ELM Pacing
- **Active Control**: Use RMP (Resonant Magnetic Perturbation) coils to break large ELMs into smaller, more frequent "grassy" ELMs, reducing peak flux.

### 5.2 Armor Thickness Optimization
- **Calculation**: Balance between thermal inertia (thicker is better) and thermal stress (thinner is better).
- **Optimal Range**: Typically 10–20 mm for CFETR divertor monoblocks.

---

## 6. Verification & Testing

- **Laser Facility**: Use high-power lasers to simulate 20–30 MW/m² transient pulses.
- **ELM Simulator**: Electron beam testing with millisecond pulsing.
- **Post-Mortem**: Ultrasonic testing (UT) to detect delamination and crack depth after cycling.

---

## 7. Expected Outcome

- Divertor survives >10,000 ELM cycles without structural failure.
- No surface melting during transient events.
- Maintains cooling efficiency throughout reactor lifetime.

---
*This addresses the "thermal exhaust" bottleneck, which is the primary limiting factor for long-pulse fusion.*
