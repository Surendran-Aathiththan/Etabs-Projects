# ETABS Projects

Structural models analysed and designed in **ETABS** (with one slab model exported to **SAFE**). The projects cover reinforced-concrete buildings, a steel truss bridge and basic beam analysis. Each folder holds the ETABS model (`.EDB`), and most include design notes and result plots.

## Projects

| Project | Description | Highlights |
|---|---|---|
| [G+1 Commercial Building](G%2B1%20Commerial%20Building) | RC frame building designed to Indian Standard (IS) provisions | Grid and columns drafted in AutoCAD and imported as DXF · M25 concrete, HYSD500 rebar · wall, floor, roof, seismic (R = 3, I = 1.2) and wind (47 m/s) loads · concrete frame design check, with failing beams and columns resized (B200×500 → B300×500, C200×600 → C300×600) · storey displacement check |
| [Simple G+2 Building](Simple%20G%2B2%20Building) | Three-storey RC frame | M25 / HYSD415 · B250×300 beams, C300×300 columns · fixed supports · 14 kN/m wall load, 2.0 kN/m² LL, 1.5 kN/m² SDL · 1.4DL + 1.6LL combination |
| [Steel Truss Bridge](Steel%20Truss%20Bridge) | Steel truss bridge model | Axial force, bending moment, shear force and shell stress diagrams |
| [Simply Supported Beam](Simply%20Supported%20Beam) | Single-span beam verification model | Bending moment (3-3) and shear force (2-2) diagrams |
| [Safe](Safe) | Slab/foundation model exported from ETABS to SAFE 2016 | SAFE model files |
| [Udemy 01](Udemy%2001) | Course model with design notes | M20 concrete properties, preliminary sizing rules for beams, columns and slabs |
| [ETABS Structural Modeling](ETABS%20Structural%20Modeling), [Ebats Youtube building 1](Ebats%20Youtube%20building%201), [Ebats Youtube square building](Ebats%20Youtube%20square%20building) | Practice building models | Modelling workflow practice |

## Skills demonstrated

- Defining materials, frame sections, supports and diaphragms
- Calculating and assigning wall, floor, roof, seismic and wind loads
- Creating load patterns, mass sources and load combinations
- Running concrete frame design checks and revising failing members
- Reading force diagrams and storey response plots

## Opening the files

Open the `.EDB` files in **ETABS** (2016 or later recommended). Analysis results are not stored in the repository, so run the analysis after opening a model.
