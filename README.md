# ETABS Projects

Reinforced-concrete building and steel structure models analysed and designed in **ETABS** (versions 22–23), with one slab model exported to **SAFE**. Each project folder has its own README describing the model, loads, results and current status.

## Featured project

### [G+1 Commercial Building](G%2B1%20Commerial%20Building): RC frame designed to IS 456 / IS 1893 / IS 875

- Grid and column layout drafted in AutoCAD and imported into ETABS as a DXF
- M25 concrete, HYSD500 reinforcement, 150 mm one-way and two-way slabs, rigid diaphragms
- Wall loads calculated from wall thickness × unit weight × height (10, 5 and 4 kN/m)
- Seismic loads (IS 1893, I = 1.2, R = 3) and wind loads (IS 875, V<sub>b</sub> = 47 m/s) in four directions
- Concrete frame design check: failing members resized from B200×500 → B300×500 and C200×600 → C300×600
- Storey displacement check, plus documented review notes on the model

## All projects

| Project | What it covers | Status |
|---|---|---|
| [G+1 Commercial Building](G%2B1%20Commerial%20Building) | RC frame, gravity + seismic + wind loads, concrete frame design check to IS 456 | ✅ Complete |
| [Simple G+2 Building](Simple%20G%2B2%20Building) | 3 × 4 bay RC frame (12 m × 16 m), wall load calculation, 1.4DL + 1.6LL (BS 8110) | ✅ Model complete · gravity only |
| [Steel Truss Bridge](Steel%20Truss%20Bridge) | Steel frame with deck slabs; axial, shear, moment and shell-stress results | 🟡 Practice model |
| [Simply Supported Beam](Simply%20Supported%20Beam) | Bending-moment and shear-force diagrams | 🟡 Practice model |
| [Safe](Safe) | Slab model exported from ETABS to SAFE 2016 with Eurocode-style combinations (1.35DL + 1.5LL, DL + 0.3LL ± EQ) | 🟡 Model only |
| [Udemy 01](Udemy%2001) | Course model with notes on M20 properties and preliminary sizing of beams, columns and slabs | 🟡 Learning model |
| [ETABS Structural Modeling](ETABS%20Structural%20Modeling), [Ebats Youtube building 1](Ebats%20Youtube%20building%201), [Ebats Youtube square building](Ebats%20Youtube%20square%20building) | Tutorial-based practice building models | 🟡 Practice models |

## Skills demonstrated

- Defining materials, frame and slab sections, supports, diaphragms and auto-meshing
- Calculating and assigning wall, floor, roof, staircase, lift/tank, seismic and wind loads
- Setting up mass sources, load patterns and load combinations
- Running concrete frame design checks and revising failing members
- Reading force diagrams, shell stress contours and storey response plots
- Transferring models between AutoCAD (DXF), ETABS and SAFE

## Repository layout

```
Etabs Projects/
├── G+1 Commerial Building/   # featured RC building (EDB, e2k export, DXF, readme)
├── Simple G+2 Building/      # RC frame (EDB, e2k export, readme)
├── Steel Truss Bridge/       # steel model + result images
├── Simply Supported Beam/    # beam model + result images
├── Safe/                     # SAFE slab model
├── Udemy 01/                 # course model + notes
└── ...                       # other practice models
```

## Opening the files

Open the `.EDB` files in **ETABS 22 or later**. Analysis output files are not stored in the repository (see `.gitignore`), so run the analysis after opening a model. The `.e2k` files are plain-text exports that can be read without ETABS.
