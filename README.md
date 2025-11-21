# Echo Equation Evidence Bundle — Minimal Referee Pack (v1.1)

Zenodo DOI: 10.5281/zenodo.17622475  
Associated manuscript: *A Resonant Medium Framework for Cosmology: Finite-Memory Dynamics and the Echo Equation.*

This archive provides the **minimal, referee-oriented evidence pack** for the Echo Equation analysis. It is designed to make it easy to:

- Inspect which quantitative checks underpin the main figures.  
- Verify that key guard metrics were computed and passed.  
- Cross-check that the figure assets used in the paper correspond to well-defined inputs and scripts.

This bundle is intentionally **small**. It does **not** contain all analysis scripts, likelihood files, or raw survey products.

For full code and data, please refer to:

- Main code + analysis repository: `<GitHub URL for the Echo Equation project>`  
- Full Zenodo deposition with complete scripts and inputs: `10.5281/zenodo.17622475`  

---

## Contents of this bundle

- `README.md` — high-level description (this file).  
- `README_EVIDENCE.md` — how to use the evidence bundle.  
- `EVIDENCE_INDEX.csv` — machine-readable index of included artifacts.  
- `EVIDENCE_LOCK.SHA256` — SHA-256 lockfile for the contents listed in `EVIDENCE_INDEX.csv`.  
- `phase20_fit/fig1_fit_comparison_provenance.json` — provenance for Figure 1 (fit comparison).  
- `phase8_spectrum/fig2_spectral_density_provenance.json` — provenance for Figure 2 (operator spectral density).  
- `phase21_guardbands/fig3_lensing_residuals_provenance.json` — provenance for Figure 3 (CMB lensing residuals).  
- `phase21_guardbands/guard_metrics_summary.csv` — numerical summary of guardband checks supporting Figure 3.

All paths and descriptions are mirrored in `EVIDENCE_INDEX.csv`.

---

## How this relates to the full project

The full Echo Equation project includes:

- Phase-by-phase analysis scripts.  
- Compressed likelihood inputs (BAO, SN, CMB lensing, etc.).  
- Additional diagnostic and stability figures.

Those materials live in the main repository and the full Zenodo record.  

This minimal bundle is scoped specifically for **peer review**: it exposes the provenance and guard metrics behind the primary figures in a way that is easy to inspect, hash, and archive.

---

## Versioning

- **v1.0** — Initial public release of the minimal evidence bundle.  
- **v1.1** — Updated README files; clarified scope as a minimal referee pack; aligned DOI with `10.5281/zenodo.17622475`.

See `CHANGELOG.md` for a more detailed change log.
