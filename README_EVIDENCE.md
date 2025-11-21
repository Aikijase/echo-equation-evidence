# Echo Equation — Minimal Evidence Bundle

**Generated:** 2025-11-10T08:21:26Z (UTC)  
Zenodo DOI: 10.5281/zenodo.17622475

This archive contains the **minimal set of artifacts** needed to understand and verify the evidence behind the three primary figures in the Echo Equation manuscript:

1. Figure 1 — Model fit comparison (Echo vs ΛCDM).  
2. Figure 2 — Spectral density of the resonant operator.  
3. Figure 3 — CMB lensing residuals and guardband checks.

---

## Structure

- `phase20_fit/fig1_fit_comparison_provenance.json`  
- `phase8_spectrum/fig2_spectral_density_provenance.json`  
- `phase21_guardbands/fig3_lensing_residuals_provenance.json`  
- `phase21_guardbands/guard_metrics_summary.csv`  
- `EVIDENCE_INDEX.csv` — overview of these files.  
- `EVIDENCE_LOCK.SHA256` — SHA-256 checksums for the indexed artifacts.

---

## How to use this bundle

Each `*_provenance.json` file describes:

- The **inputs** used to generate the corresponding figure (e.g., CSV/NPZ files with model predictions and data).  
- The **code scripts** used to transform those inputs into a plotted figure.  
- The expected **outputs** (e.g., `fig1_fit_comparison.pdf`) and their hashes.  

To verify or regenerate a figure:

1. Open the relevant provenance JSON.  
2. Locate the referenced inputs and scripts in the main Echo Equation repository or full Zenodo deposition.  
3. Follow the “notes” section and associated command line (which we will complete in each JSON) to rerun the plot.

This minimal bundle does **not** duplicate the full code and data. Instead, it provides a stable, hash-locked map of what was used, so that long-term archival and cross-checks remain easy.

---

## Guard metrics

`phase21_guardbands/guard_metrics_summary.csv` summarises a small number of numerical guard checks associated with the lensing and growth analysis (e.g., Δχ² parity, residual bounds, and split stability). These values are discussed in the manuscript and can be recomputed from the underlying scripts and inputs in the full project repository.

---

## Contact

For questions or clarifications, please refer to the manuscript or contact the corresponding author at:

`theexperimentalistlab@outlook.com`
