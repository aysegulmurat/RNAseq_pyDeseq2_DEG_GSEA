# GSE217195 – MOLM-13 Bulk RNA-seq Analysis

This repository contains a **reproducible and literature-aligned exploratory transcriptomics analysis** based on the public GEO dataset **GSE217195**, focusing on the human acute myeloid leukemia (AML) cell line **MOLM-13**.

The project is prepared directly for **GitHub sharing**, with clear scope definition, transparent assumptions, and explicit limitations.

---

## 📂 Dataset

* **GEO accession:** GSE217195
* **Repository:** NCBI Gene Expression Omnibus (GEO)
* **Link:** [https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE217195](https://www.ncbi.nlm.nih.gov/geo/query/acc.cgi?acc=GSE217195)
* **Organism:** *Homo sapiens*
* **Cell line:** MOLM-13 (acute myeloid leukemia)

Raw data are accessed from GEO and are **not redistributed** in this repository.

---

## 🎯 Project Scope

This project aims to:

* Inspect and preprocess expression data from GSE217195
* Apply appropriate filtering and normalization steps
* Perform exploratory data analysis (EDA)
* Visualize global expression patterns across samples

The analysis is **exploratory and hypothesis-generating**. No clinical or causal claims are made.

---

## 🧪 Analysis Workflow

The analysis follows commonly accepted bulk RNA-seq best practices:

1. Data loading and metadata inspection
2. Filtering of low-expressed genes
3. Normalization and transformation (method explicitly stated in the notebook)
4. Exploratory analyses

   * Principal Component Analysis (PCA)
   * Sample-level visualization
5. Optional differential expression analysis **only if group definitions are available in GEO metadata**

All steps, parameters, and assumptions are documented in the notebook.

---

## 📊 Methodological Principles

* No artificial sample groupings are introduced
* PCA is used strictly for exploratory visualization
* Results are interpreted at the level of **patterns and trends**, not statistical causality
* Thresholds and preprocessing decisions are explicitly stated

These choices align with recommendations in current transcriptomics literature.

---

## 📁 Repository Structure

```
├── GSE217195_molm13_project.ipynb   # Main analysis notebook
├── README.md                       # Project documentation
└── data/                           # (Optional) processed input files
```

---

## 🔁 Reproducibility

* Single, self-contained Jupyter Notebook
* Fixed random seeds where applicable
* Fully transparent preprocessing and analysis steps

This repository is designed for **direct reproducibility and reuse**.

---

## ⚠️ Limitations

* Analysis is restricted to a single AML cell line (MOLM-13)
* Biological interpretation is limited by the original experimental design
* No external validation dataset is included

---

## 📚 Citation

If you use this dataset, please cite the original GEO submission:

> GEO Accession: GSE217195, NCBI Gene Expression Omnibus

---

## 👤 Author

Aysegul Murat

---

## 📝 License

This repository is shared for **academic and educational purposes**. Please consult GEO data usage policies before reuse.
