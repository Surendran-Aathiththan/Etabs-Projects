# G+1 Commercial Building

<img width="30%" alt="image" src="https://github.com/user-attachments/assets/709043e8-b714-48b9-9005-52c105b67f17" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/52e0d7f8-c3f6-4133-9910-caabbabdd254" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/ab0edfc1-4ab0-4155-8729-33ea84b80a95" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/daabc4f3-a00f-42e7-9174-d418d117b00b" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/5712f900-c32a-494f-9a1e-75a82f5f57ac" />
<img width="30%" src="https://github.com/user-attachments/assets/6604efc2-ed02-4685-b8da-a694c55a8fae" />

<br><br><br>

Created the centerline and columns in AutoCAD and exported the model as a DXF file.

> Ensure all four sides of each column are joined before exporting.

- Used IS code


## Materials
- **Concrete:** M25
- **Rebar:** HYSD500

## Frame Sections
- **Columns:** C200 × 600 mm
- **Beams:** B200 × 500 mm

## Load Calculations

### Wall Load
- Exterior wall: `0.2 × 20 × 2.5 = 10 kN/m`
- Interior wall: `0.1 × 20 × 2.5 = 5 kN/m`
- Parapet wall: `0.1 × 20 × 2.0 = 4 kN/m`
- Assigned as a distributed frame load

### Floor Loads
- Ground & 1st floor
  # G+1 Commercial Building

  <p align="center">
    <img width="30%" alt="plan" src="https://github.com/user-attachments/assets/709043e8-b714-48b9-9005-52c105b67f17" />
    <img width="30%" alt="elevation" src="https://github.com/user-attachments/assets/52e0d7f8-c3f6-4133-9910-caabbabdd254" />
    <img width="30%" alt="section" src="https://github.com/user-attachments/assets/ab0edfc1-4ab0-4155-8729-33ea84b80a95" />
    <img width="30%" alt="details" src="https://github.com/user-attachments/assets/daabc4f3-a00f-42e7-9174-d418d117b00b" />
    <img width="30%" alt="model" src="https://github.com/user-attachments/assets/5712f900-c32a-494f-9a1e-75a82f5f57ac" />
    <img width="30%" alt="mesh" src="https://github.com/user-attachments/assets/6604efc2-ed02-4685-b8da-a694c55a8fae" />
  </p>

  Created the centerline and columns in AutoCAD and exported the model as a DXF file.

  > Ensure all four sides of each column are joined before exporting.

  **Design code:** Indian Standard (IS) provisions

  ## Materials
  - **Concrete:** M25
  - **Rebar:** HYSD500

  ## Frame Sections
  - **Columns:** C200 × 600 mm
  - **Beams:** B200 × 500 mm

  ## Load Calculations

  ### Wall Load
  - Exterior wall: `0.2 × 20 × 2.5 = 10 kN/m`
  - Interior wall: `0.1 × 20 × 2.5 = 5 kN/m`
  - Parapet wall: `0.1 × 20 × 2.0 = 4 kN/m`
  - Assigned as a distributed frame load

 ### Floor Loads
  - Ground & 1st floor
  -  dead load: `3.0 kN/m²`
  - Floor finish + ceiling plaster: `1.5 kN/m²` 
  - Roof live load: `3.0 kN/m²`
  - Roof finish + ceiling plaster: `1.0 kN/m²`

  ### Seismic Load
  - Directions: `EQ X+`, `EQ X-`, `EQ Y+`, `EQ Y-`
  - Response reduction factor (R): `3` — reduces design forces using ductility considerations
  - Importance factor (I): `1.2` — increases seismic forces for important structures

  ### Wind Load
  - Basic wind speed: $V_p = 47   \mathrm{m/s}$

  ### Mass / Load Sources
  - Load patterns used:
    - Dead: `1.0`
    - Wall loads: `1.0`
    - Live: `0.25`
    - Staircase: `0.5`

  - Assignments and notes:
    - Select all elements → Assign → Shell → Diaphragm
    - Staircase load: assign a Live pattern on staircase floor (as required)
    - Lift and water tank: assign a Super Dead pattern (e.g. 10 kN) on lift floor
    - Mesh floor shells: Auto mesh, suggested 2×2 elements

  ### Load Combinations
  - Add defaut load combinations
  - Add new combo DL+LL and DL+LL+1.5 
    - Dead
    - Live
    - Wall Load
    - Staircase
    - Roof Live

  ## Analysis & Design
  - Run: Design → Concrete Frame Design → Design Check
  - For lateral displacement checks: Display → Story Responce Plots

  