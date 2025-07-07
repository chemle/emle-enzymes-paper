# EMLE Enzymes Paper

Supporting data for [**"Simulating enzyme catalysis with electrostatically embedded machine learning potentials"**](https://chemrxiv.org/engage/chemrxiv/article-details/6862db73c1cb1ecda054fdb9).

---

## Directory Structure

### `figures/`
Contains raw data and Jupyter notebooks for all figures presented in the publication.

### `models/`
ML models trained. Includes:

- `AbyU_MACE.tgz`: MACE model for AbyU system
- `ChoM_DeePMD.tgz`: DeePMD model for ChoM system
- `ChoM_EMLE.tgz`: EMLE model for ChoM system

### `systems/`
Simulation files for each system. Includes:

- `parm7`: AMBER topology file  
- `ncrst`: relaxed structure  
- `in`: example `sander` input file for Umbrella Sampling  
- `restr`: example restraint file with Umbrella Sampling bias

---
