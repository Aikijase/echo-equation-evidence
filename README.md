# Echo Equation Evidence Bundle — Minimal Referee Pack (v1.1)

Zenodo DOI: 10.5281/zenodo.17622475  
Associated manuscript: *A Resonant Medium Framework for Cosmology: Finite-Memory Dynamics and the Echo Equation.*

This archive provides the **minimal, referee-oriented evidence pack** for the Echo Equation analysis.  
It is designed to make it easy to:

- inspect which quantitative checks support each main figure,  
- verify that guard metrics were computed and passed,  
- confirm that the plotted results correspond to well-defined inputs and scripts.

This bundle is intentionally **small**. It is **not** a full reproducibility package.  
The complete code, data, and analysis pipeline are available through:

- **Main project repository:** `<your GitHub URL>`  
- **Full Zenodo deposition:** `10.5281/zenodo.17622475`

---

## Contents of This Bundle

- `README.md` — high-level description (this file).  
- `README_EVIDENCE.md` — detailed usage of the evidence bundle.  
- `EVIDENCE_INDEX.csv` — machine-readable index of all included artifacts.  
- `EVIDENCE_LOCK.SHA256` — SHA-256 lockfile for the indexed files.

### Figure provenance
- `phase20_fit/fig1_fit_comparison_provenance.json`  
- `phase8_spectrum/fig2_spectral_density_provenance.json`  
- `phase21_guardbands/fig3_lensing_residuals_provenance.json`

### Guard metrics
- `phase21_guardbands/guard_metrics_summary.csv`

All paths, descriptions, and hashes are mirrored in `EVIDENCE_INDEX.csv`.

---

## Scope of This Bundle

This bundle contains only:

- provenance,
- guard metrics,
- minimal numerical context,
- locked hashes.

It does **not** contain:

- full analysis scripts,  
- synthetic tests,  
- compressed-likelihood files,  
- notebooks,  
- configuration files,  
- or raw observational datasets.

These are deliberately kept in the **primary GitHub repository** and **full Zenodo archive**, not duplicated here.

This keeps the evidence bundle compact, hash-stable, and referee-friendly.

---

## License

This evidence bundle is released under the  
**Creative Commons Attribution–NonCommercial–NoDerivatives 4.0 International License (CC BY-NC-ND 4.0).**

See `LICENSE.txt` for full terms.

---

## Version History

### v1.1 — Minimal referee pack cleanup (2025-11-21)
- Rewrote README files to reflect that this is a **minimal evidence bundle**.  
- Updated DOI and descriptions for clarity.  
- Added structured changelog.

### v1.0 — Initial release (2025-11-10)
- First public release of provenance and guardband information.  
- Included evidence index + SHA-256 lockfile.  
- Provided stubs for figure provenance (now being completed).

---

For questions or clarifications, contact:  
**theexperimentalistlab@outlook.com**
