# Microbiome Machine Learning Classifier

Classify disease status based on human gut microbiome composition using public MetaPhlAn2 abundance data. 
Built with Python tools and focused on clear, reproducible, and interpretable analysis.

---

## Project Goals

- Perform exploratory data analysis (EDA) on microbiome taxonomic abundance tables
- Visualize sample metadata and taxa composition
- Build machine learning models to classify disease status
- Apply dimensionality reduction
- Practice GitHub workflows for bioinformatics

---

## Project Structure
```
├── data/                 # Raw and processed data
├── notebooks/            # Jupyter notebooks (EDA, modeling, etc.)
├── results/              # Output figures, model metrics
├── requirements.txt      # Python dependencies
└── README.md             # Project overview
```
---

## Dataset

- Source: [Kaggle Metagenomics Dataset] (https://www.kaggle.com/datasets/antaresnyc/metagenomics/data)
- Reference: [Pasolli et al., PLOS Computational Biology 2016] (https://doi.org/10.1371/journal.pcbi.1004977)
- Samples: Stool microbiome abundance tables
- Metadata: Age, gender, BMI, disease status

---

## Notebooks

| Notebook | Purpose |
|----------|---------|
| `01_data_cleaning.ipynb` | Load + clean abundance & metadata |
| `02_eda.ipynb`           | Visualize sample distributions, taxa, metadata |
| `03_modeling.ipynb`      | ML pipeline: preprocessing → model training → evaluation |
| `04_umap_pca.ipynb`      | Dimensionality reduction & clustering |

---

## Dependencies

Install required packages:

```bash
pip install -r requirements.txt
