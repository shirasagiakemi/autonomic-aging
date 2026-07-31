# autonomic-aging
Analysis code for age-separated maxima in HRV DFA scaling exponents (α1, α2) and the composite CHI index. Includes primary cohort analysis (PhysioNet Autonomic Aging DB), external cohort validation (Fantasia, NSR-RR), and companion transcriptomic analyses (GSE262619, OEP001041).
# ECSoC Autonomic Aging Analysis

Analysis code accompanying:
>Okabe, H. (2026). Age-Separated Maxima of Short- and Long-Range Heart Rate
Dynamics: A Decade-Scale Offset Between α1 and α2 in a Single Cross-Sectional
Cohort [Preprint]. Zenodo. https://doi.org/10.5281/zenodo.21712528
>  

## Contents

| Notebook | Corresponds to | Data source |
|---|---|---|
| `01_hrv_main/ECSoC_AutonomicAging_v8_step15_extended.ipynb` | Sections 3.1–3.3, 3.5 | PhysioNet Autonomic Aging DB, Fantasia, NSR-RR |
| `02_gse262619_discovery/GSE262619_immune_aging_analysis_v2.ipynb` | Section 3.4 (discovery cohort) | GEO GSE262619 |
| `03_oep001041_companion/OEP001041_Age40to70_DE_GSEA_v11.ipynb` | Section 3.4 (companion cohort, incl. NLR_proxy sensitivity) | NODE accession OEP001041 |

## Environment

Notebooks were written for Google Colab. Paths under `/content/drive/MyDrive/...`
should be adjusted to your local data location.

## Data availability

Raw data are not redistributed in this repository. See original sources:
- PhysioNet Autonomic Aging DB: [https://physionet.org/content/autonomic-aging-cardiovascular/]
- Fantasia / NSR-RR (PhysioNet): [https://physionet.org/content/fantasia/]
- GSE262619 (GEO): [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE262619 ]
- - OEP001041 (NODE): https://www.biosino.org/node/project/detail/OEP001041
  Processed count/FPKM data are publicly available; raw individual-level
  sequencing data require ethics-committee-approved access.
  Primary source: Xia et al., Nat Metab (2020). Also used as an external
  validation cohort in Gao, Li & Cai, J Gerontol A (2025), glaf054.
## License

Code: MIT License (see LICENSE). Data usage is governed by each original
repository's terms, not by this license.
