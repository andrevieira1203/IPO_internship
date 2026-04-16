# IPO Internship : Bioinformatic Analysis of Molecular Alterations in Prostate Cancer

## Description

This repository contains the work developed during an internship at **IPO (Instituto Português de Oncologia)**, focused on the bioinformatic analysis of **molecular alterations in Normal Adjacent Tissue (NAT)** to tumors in **prostate cancer**.

The main goal is to understand how the apparently normal tissue surrounding a tumor presents molecular alterations distinct from healthy tissue, contributing to a better understanding of tumor progression and the epigenetic/genomic mechanisms associated with prostate cancer.

---

## Repository Structure

```
IPO_internship/
│
├── InitialDatasets/          # Initial datasets used in the analysis
├── AnaliseEstagio.ipynb      # Main notebook with the full bioinformatic analysis
├── data.csv                  # Processed data used in the analyses
└── README.md                 # Project documentation
```

> **Note:** The `TCGA_PRAD_IlluminiSeq` dataset (from The Cancer Genome Atlas — Prostate Adenocarcinoma) was used as an additional data source but was not included in the repository due to its large size.

---

## Data Sources

| Dataset | Source | Description |
|---|---|---|
| InitialDatasets | IPO / local | Initial datasets for the analysis |
| data.csv | Processed | Integrated and cleaned data for analysis |
| TCGA_PRAD_IlluminiSeq | [TCGA](https://www.cancer.gov/tcga) | RNA-seq gene expression data (Illumina) — not included |

---

## Analysis

The main analysis is contained in **`AnaliseEstagio.ipynb`** and includes:

- **Data preprocessing** — cleaning, normalization, and integration of datasets
- **Exploratory Data Analysis (EDA)** — visualization of distributions and patterns in molecular data
- **NAT vs. Tumor comparison** — identification of differential molecular alterations between tumor and normal adjacent tissue
- **Gene expression analysis** — study of differentially expressed genes using RNA-seq data (TCGA PRAD)
- **Bioinformatic visualizations** — heatmaps, volcano plots, and other supporting charts

---

## Technologies & Libraries

- **Python 3**
- **Jupyter Notebook**
- Likely libraries:
  - `pandas`, `numpy` — data manipulation
  - `matplotlib`, `seaborn` — visualization
  - `scipy`, `statsmodels` — statistical analysis
  - `sklearn` — dimensionality reduction (PCA, etc.)

---

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/andrevieira1203/IPO_internship.git
   cd IPO_internship
   ```

2. Install dependencies (virtual environment recommended):
   ```bash
   pip install pandas numpy matplotlib seaborn scipy scikit-learn jupyter
   ```

3. Open the notebook:
   ```bash
   jupyter notebook AnaliseEstagio.ipynb
   ```

> To fully reproduce the analysis, download the `TCGA_PRAD_IlluminiSeq` dataset from the [TCGA portal](https://portal.gdc.cancer.gov/) and place it in the root of the project.

---

## Context

This work was carried out during an internship at **IPO — Instituto Português de Oncologia**, as part of a research line on biomarkers and epigenetic/genomic alterations in prostate cancer. The study of NAT is relevant for understanding the mechanisms of field cancerization and identifying potential therapeutic targets or early diagnostic markers.

---
