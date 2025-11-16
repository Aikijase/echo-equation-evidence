
# Echo Equation Evidence Bundle v1
Zenodo DOI: 10.5281/zenodo.17570715

This archive contains the full set of reproducibility materials used in the
paper **“A Resonant Medium Framework for Cosmology: Finite Memory Dynamics and the Echo Equation.”**  
It provides the exact scripts, compressed inputs, configuration files, and
figure-generation resources required to reproduce all results presented in the
manuscript.

---

## Contents

### `scripts/`
Analysis scripts used to generate predictions, stability checks, and derived
quantities. Includes:
- `magnet_echo_v9.py`
- `spectrum_solver_phase8.py`
- likelihood and guard-metric tools
- auxiliary analysis functions

These scripts were used to produce the BAO, SN, and CMB-lensing model
predictions and guard values discussed in the manuscript.

### `notebooks/`
Jupyter notebooks used to generate all figures in the paper. Each notebook
produces one or more plots appearing in the manuscript and uses the data and
configuration files stored in this bundle.

### `data/`
Compressed-likelihood inputs and observational summaries used for the analysis:
- BAO compressed distances  
- Binned supernova luminosity distances  
- Planck 2018 CMB lensing inputs  
- Supporting numeric arrays for growth and stability tests

These are the exact files used in all computations.

### `configs/`
Parameter files and guard-metric configurations defining the stability,
frequency, and damping settings for Echo Equation runs. These ensure full
reproducibility of all reported results.

### `figs/`
Source data used by the notebooks to generate Figures 1–3 in the manuscript.
Includes numeric arrays and intermediate results needed to reconstruct each
plot exactly.

---

## How to Reproduce Results

1. Install Python 3.9+ with standard scientific libraries  
   (`numpy`, `scipy`, `matplotlib`, `json`, etc.).
2. Run any script in `scripts/` to reproduce the numerical predictions.
3. Open the notebooks in `notebooks/` to regenerate the manuscript figures.
4. All configuration and input files are already included; paths are relative.

Each figure and result in the paper can be reproduced using only the contents
of this archive.

---

## License
This bundle is released under the **Creative Commons Attribution–NonCommercial–
NoDerivatives 4.0 International License (CC BY-NC-ND 4.0)**.  
See `LICENSE.txt` for full terms.

You may download and share this archive for verification, academic review, or
reproduction of results. You may not modify, redistribute, or use the material
for commercial purposes without written permission from the copyright holder.

---

## Version History

### v1.0 (Initial Release)
- First public release of all reproducibility materials for the Echo Equation
  analysis.
- Includes analysis scripts, figure-generation notebooks, configuration files,
  compressed-likelihood inputs, and source data for all manuscript figures.
- Structured for full reproducibility and transparency.

See `CHANGELOG.md` for full details.

---

For questions or clarifications, please refer to the manuscript or contact the
corresponding author.
