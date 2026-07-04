# G+1 Commercial Building

<img width="30%" alt="image" src="https://github.com/user-attachments/assets/709043e8-b714-48b9-9005-52c105b67f17" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/52e0d7f8-c3f6-4133-9910-caabbabdd254" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/ab0edfc1-4ab0-4155-8729-33ea84b80a95" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/daabc4f3-a00f-42e7-9174-d418d117b00b" />
<img width="30%" alt="image" src="https://github.com/user-attachments/assets/5712f900-c32a-494f-9a1e-75a82f5f57ac" />

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
  -  dead load: `3.0 kN/m²`
  - Floor finish + ceiling plaster: `1.5 kN/m²`
- Roof 
  - live load: `3.0 kN/m²`
  - Roof finish + ceiling plaster: `1.0 kN/m²`

### Seismic Load
- Directions: `EQ X+`, `EQ X-`, `EQ Y+`, `EQ Y-` 
- Response reduction factor (R): `3` 
  >Reduces design forces by relying on the structure's ductility to absorb energy without collapsing.
- Importance factor (I): `1.2` 
   >Increases the design earthquake force for critical facilities



### Wind Load
- Wind speed Vp :47 ms-1

### Mass Source
- Specified load patterns
Dead: 1
wall loads: 1 
Live: 0.25
staircase: 0.5

- Select all > Assign >Shell > Diapharam
- Assigned new Load pattern> Stiarcase load: Live :4 on staircase floor
- Assigned new Load pattern> Lift and watertank load: Super dead :10 on lift floor
- Select all Floor > Assign >Shell > Floor auto mech > mesh by 2 by 2

### Load Combination
- Add defeult design combination: Concrete frame design(Editable)


  



