# ETABS Practice Building Models: Irregular Residential Frame and 5-Storey Frame

Two ETABS 22 models built while following online tutorials: an irregular-grid residential RC building with a plinth level, stairs and a retaining wall (`Aa.EDB`), and a regular 5-storey RC frame with IS 1893 seismic and IS 875 wind load patterns (`Ytub.EDB`).

**Status:** 🟡 Practice models. Geometry and loads assigned; no design results recorded.

## Model 1: `Aa.EDB`, irregular residential building

| Item | Value (from `Aa.$et`) |
|---|---|
| Grid | 14 × 5 irregular grid lines, about 19.0 m × 13.5 m |
| Levels | Base → plinth (0.45 m) → 4 storeys at 3.0 m |
| Beams | B240x500 (M25; defined 240 × 450 mm), plinth beams PB300x450 |
| Columns | C240x400 (M30) |
| Slabs | 140 mm floor slabs, 250 mm stair slabs, 120 mm sunshades, 200 mm slabs |
| Walls | 200 mm retaining wall (membrane) |
| Stiffness modifiers | Beams I = 0.35I<sub>g</sub>, columns I = 0.70I<sub>g</sub>, torsion 0.01 |
| Loads | Masonry 12 kN/m on beams · additional dead 1.5 kN/m² (5.0 kN/m² on some panels) · live 5.0 / 2.0 kN/m² |
| Supports | Pinned (translations restrained), 27 points |
| Design code | IS 456:2000 |

## Model 2: `Ytub.EDB`, 5-storey RC frame

| Item | Value (from `Ytub.$et`) |
|---|---|
| Grid | 6 × 3 grid lines, 17 m × 7 m, 18 columns |
| Storeys | 5 at 3.0 m |
| Members | Beams 350 × 350 mm, columns 450 × 450 mm (M30) |
| Slab | 150 mm |
| Loads | Wall loads 3.06 and 5.06 kN/m · dead 3.75 kN/m² · live 2.5 kN/m² |
| Seismic | IS 1893:2016, Z = 0.36, I = 1.0, R = 5, soil type II |
| Wind | IS 875:2015, V<sub>b</sub> = 44 m/s, C<sub>p</sub> 0.8 / 0.5 |
| Supports | Fixed |
| Design code | IS 456:2000 |

## Skills shown

- Irregular grids, plinth levels, stair and sunshade slabs, retaining walls
- Cracked-section stiffness modifiers for beams and columns
- Defining IS 1893 and IS 875 auto-lateral load patterns

## Files

| File | Description |
|---|---|
| `Aa.EDB` | Irregular residential building model |
| `Ytub.EDB` | 5-storey frame model |

Open in ETABS 22 or later and run the analysis (results are not stored in the repository).
