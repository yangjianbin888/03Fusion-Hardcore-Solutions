# Tokamak Tungsten First Wall: >10MW/m² Steady-State Heat Load & Sputter Erosion Suppression

> **Author**: [华夏之光永存]
> **Date**: 2026-06-23
> **Series**: 03-Fusion-Hardcore-Solutions / No. 057
> **Keywords**: Tungsten First Wall, Plasma Facing Components (PFC), Heat Load, Sputter Erosion, CFETR, DEMO

---

## 1. Problem Statement

The first wall (FW) and divertor are the only physical barriers between the 100-million-degree plasma and the vacuum vessel. 
For CFETR/DEMO-class devices, the FW must withstand:

- **Steady-State Heat Flux**: >10 MW/m² (normal operation)
- **Transient Heat Loads**: ELMs and disruptions can spike >100 MW/m²
- **Particle Bombardment**: High-energy neutrons and fuel ions causing sputtering and surface modification.

Current ITER-grade tungsten monoblocks show severe limitations under these conditions: surface cracking, melting, and excessive erosion.

---

## 2. Key Design Parameters (Reference Values)

| Parameter | Value | Note |
|---|---|---|
| Material | Pure Tungsten (W) / W-La₂O₃ alloy | High melting point (3422°C) |
| Surface Heat Flux (Steady) | **10–15 MW/m²** | CFETR/DEMO requirement |
| Neutron Wall Loading | **1–2 MW/m²** | 14 MeV neutrons |
| Surface Temperature Limit | <1200°C | To avoid recrystallization embrittlement |
| Sputtering Yield (Y) | <10⁻⁴ atoms/ion | Critical for low contamination |
| Cooling Channel | Water / He | Sub-surface cooling |
| Coolant Pressure Drop | <0.5 MPa | System constraint |

---

## 3. Thermal Management Strategy (10–15 MW/m²)

### 3.1 Ultra-High Conductivity Composite
Pure tungsten has poor thermal conductivity at high temperatures. 
- **Solution**: Develop **W-Cu graded composites**.
- **Structure**: W surface (plasma side) → W-Cu transition layer → CuCrZr substrate (coolant side).
- **Benefit**: Avoids sharp thermal expansion mismatch, prevents delamination.

### 3.2 Micro-channel Hypervapotron Cooling
Traditional macro-channels cannot handle >10 MW/m².
- **Design**: Integrate **micro-hypervapotron channels** directly behind the plasma-facing surface.
- **Mechanism**: Utilize subcooled boiling and liquid film evaporation to drastically enhance heat transfer coefficients (HTC > 1 MW/m²K).

### 3.3 Surface Topology Optimization
Flat surfaces concentrate heat. 
- **Approach**: Optimize the FW surface with **3D micro-rippled structures** (similar to shark skin or riblets).
- **Effect**: Increases effective radiating area by 20–30%, reducing peak heat flux density.

---

## 4. Sputter Erosion Suppression

### 4.1 Low-Z Coating Barrier
Tungsten sputtering releases high-Z impurities (W atoms) into the plasma, causing radiative collapse.
- **Strategy**: Deposit a thin (<10 µm) **Beryllium (Be) or Boron Carbide (B₄C) coating** on the W surface.
- **Function**: Be/B acts as a sacrificial layer, absorbing ion bombardment while keeping W confined.

### 4.2 Magnetic Shielding of Impurities
- **Concept**: Use local **error field correction coils** near the FW to steer escaping W ions back into the divertor region, preventing them from reaching the core plasma.

### 4.3 Helium Ash Removal
Helium ash accumulation on the FW surface insulates heat.
- **Requirement**: Ensure surface roughness (Ra) < 1 µm to facilitate helium bubble release via thermal desorption.

---

## 5. Structural Integrity & Lifetime

### 5.1 Thermal Fatigue Resistance
Cyclic 10 MW/m² loads cause crack initiation.
- **Material Choice**: Use **W-Re alloys** or **W-K doped** materials. Potassium bubbles pin dislocations and suppress crack propagation.

### 5.2 Neutron Irradiation Embrittlement
14 MeV neutrons create voids and transmutation products (Re, Os).
- **Target**: Maintain **DBTT (Ductile-Brittle Transition Temperature)** below 200°C even after 15 dpa (displacements per atom).

---

## 6. Verification & Testing

- **Electron Beam Facility**: Test mock-ups under 10–15 MW/m² steady-state loading (e.g., JUDITH, GLADIS).
- **Plasma Exposure**: Validate in existing tokamaks (EAST, DIII-D) for erosion rates.
- **Post-Mortem Analysis**: Focus on surface cracking depth and W re-deposition layers.

---

## 7. Expected Outcome

- Stable operation of CFETR/DEMO first wall under full power.
- Sputter erosion rate reduced to <1 mm/year.
- Lifetime extended to >5 full-power years without replacement.

---
*This solution targets the "thermal wall" bottleneck preventing steady-state fusion.*
