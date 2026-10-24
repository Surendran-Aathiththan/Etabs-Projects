# 5-Storey RC Frame with Eurocode Seismic Loading (ETABS)

A regular reinforced-concrete frame modelled in ETABS 22 using Eurocode materials, Eurocode 8 seismic loads and Eurocode 2 design settings. This model was also exported to SAFE (see [../Safe](../Safe)).

**Status:** 🟡 Practice model. Geometry, loads, seismic patterns and combinations defined; no design results recorded.

| Item | Value (from `Youtuve.$et`) |
|---|---|
| Grid | 3 × 3 bays at 4.0 m (12 m × 12 m), 16 columns |
| Storeys | Ground storey 2.0 m, four upper storeys at 3.6 m |
| Beams | 450 × 450 mm, C30/37 |
| Columns | 500 × 600 mm, C30/37 |
| Slab | 125 mm thin shell |
| Loads | Wall load 12 kN/m on beams · floor finish 1.5 kN/m² · live 2.0 kN/m² |
| Seismic | Eurocode 8 (EN 1998-1:2004), a<sub>g</sub> = 0.4g, type 1 spectrum, ground type B, q = 2, 5 % eccentricity |
| Combinations | 1.35G · 1.35G + 1.5Q · G + 0.3Q ± E · G ± E |
| Supports | Fixed |
| Design code | Eurocode 2-2004 |

## Files

| File | Description |
|---|---|
| `Youtuve.EDB` | ETABS model |

Open in ETABS 22 or later and run the analysis (results are not stored in the repository).
