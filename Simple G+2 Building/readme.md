# G+2 Building

<img width="50%" alt="image" src="https://github.com/user-attachments/assets/f4ecfc2f-df4d-4d0a-991d-6a2b9e627dfc" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/16eb5e6c-e211-419a-ab1a-e0db73b6a29d" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/91341f4f-4aa6-46cc-8feb-6126260c7ff4" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/17890af7-ed70-47a3-a9d4-844a111ebf0b" />
<img width="20%" alt="image" src="https://github.com/user-attachments/assets/6cc84d7c-039c-4c97-a035-70562c8c6e2e" />
<img width="60%" alt="image" src="https://github.com/user-attachments/assets/311cfc22-91e0-4f29-bf57-63f15a89e361" />
<img width="60%" alt="image" src="https://github.com/user-attachments/assets/673c1a0a-0d46-4af0-9244-fe488bf264d5" />

<br><br><br>

## Material Properties

Added the following materials:

- **Concrete:** M25
- **Reinforcement Steel:** HYSD415

## Frame Sections

Defined the following frame sections:

- **Beam:** B250 × 300 mm
- **Column:** C300 × 300 mm

## Boundary Conditions

- Assigned **Fixed Restraints** to all column base supports.

## Load Calculations

### Wall Load

- Unit weight of brick masonry = **19 kN/m³**
- Wall thickness = **240 mm**
- Wall height = **3.0 m**

{Wall Load} = 19 x 0.24 x 3 = 14 {kN/m}


**Wall Load = 14 kN/m**
Applied them on all beams

### Slab Loads

- **Live Load (LL):** 2.0 kN/m²
- **Floor Finish (SDL):** 1.5 kN/m²

## Load Combination

Defined the following load combination:

- **1.4DL + 1.6LL**

## Analysis

- ✔ Checked the analytical model.
- ✔ Verified geometry and connectivity.
- ✔ Ran structural analysis successfully.
