# autonomic-aging
Analysis code for age-separated maxima in HRV DFA scaling exponents (α1, α2) and the composite CHI index. Includes primary cohort analysis (PhysioNet Autonomic Aging DB), external cohort validation (Fantasia, NSR-RR), and companion transcriptomic analyses (GSE262619, OEP001041).
# ECSoC Autonomic Aging Analysis

Analysis code accompanying:
> Okabe, H. (2026). Age-Separated Maxima of CHI, α1, α2 in Heart Rate
> Variability DFA Scaling Exponents. [preprint DOI to be added]

## Contents

| Notebook | Corresponds to | Data source |
|---|---|---|
| `01_hrv_main/ECSoC_AutonomicAging_v8_step15_extended.ipynb` | Sections 3.1–3.3, 3.5 | PhysioNet Autonomic Aging DB, Fantasia, NSR-RR |
| `02_gse262619_discovery/GSE262619_immune_aging_analysis_v2.ipynb` | Section 3.4 (discovery cohort) | GEO GSE262619 |
| `03_oep001041_companion/OEP001041_Age40to70_DE_GSEA_v11.ipynb` | Section 3.4 (companion cohort, incl. NLR_proxy sensitivity) | NGDC OEP001041 |

## Environment

Notebooks were written for Google Colab. Paths under `/content/drive/MyDrive/...`
should be adjusted to your local data location.

## Data availability

Raw data are not redistributed in this repository. See original sources:
- PhysioNet Autonomic Aging DB: [link]
- Fantasia / NSR-RR (PhysioNet): [link]
- GSE262619 (GEO): [link]
- OEP001041 (NGDC): [link] — access may require application; see NGDC data use policy.

## License

Code: MIT License (see LICENSE). Data usage is governed by each original
repository's terms, not by this license.
