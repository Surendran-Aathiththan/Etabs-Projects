# 5-Storey Square RC Building (ETABS)

A regular 5-storey reinforced-concrete frame on a 4 × 4 bay square grid, with IS 1893 seismic and IS 875 wind load patterns. Built in ETABS 22 while following an online tutorial.

**Status:** 🟡 Practice model. Geometry, loads and lateral load patterns defined; no design results recorded.

| Item | Value (from `square building.$et`) |
|---|---|
| Grid | 4 × 4 bays at 4.0 m (16 m × 16 m), 25 columns |
| Storeys | Ground storey 4.0 m, four upper storeys at 3.0 m (16 m total) |
| Beams | 300 × 460 mm, M25 |
| Columns | 460 × 460 mm, M25 |
| Slab | 125 mm thin shell, M25 |
| Loads | Wall load 24.3 kN/m on beams · floor finish 2.0 kN/m² · live 5.0 kN/m² |
| Seismic | IS 1893:2016, Z = 0.36 (zone V), I = 1.5, R = 5, soil type II |
| Wind | IS 875:2015, V<sub>b</sub> = 55 m/s, terrain category 4, k<sub>1</sub> = 1.08, k<sub>3</sub> = 1.36 |
| Supports | Fixed, rigid diaphragm D1 |
| Design code | IS 456:2000 |

## Files

| File | Description |
|---|---|
| `square building.EDB` | ETABS model |

Open in ETABS 22 or later and run the analysis (results are not stored in the repository).
