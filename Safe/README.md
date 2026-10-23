# SAFE Slab Model

A slab model exported from the ETABS practice model `ETABS Structural Modeling/Youtuve.EDB` to **SAFE** for slab analysis.

**Status:** 🟡 Model exported and set up; no slab design results recorded yet.

| Item | Value (from `Youtuve.F2K`) |
|---|---|
| Grid | 3 × 3 bays at 4.0 m (12 m × 12 m) |
| Load cases | Dead, Live, EQ X (3 parts), EQ Y |
| Combinations | 1.35DL · 1.35DL + 1.5LL · DL + 0.3LL ± EQ |

## Files

| File | Description |
|---|---|
| `Youtuve_V2016.FDB` | SAFE 2016 model |
| `Youtuve.F2K` | Text export from ETABS (loads and combinations) |
| `Youtuve_V2016.xsdm` | SAFE model data |

Open `Youtuve_V2016.FDB` in SAFE 2016 or later.
