# The-Coloniality-of-Citation

This repository contains open data and reproducible code for analyzing citation inequality and the Matthew Effect in academic publishing.

## 📁 Project Structure

- **`data/processed/`**  
  Cleaned dataset: `processed_publications_for_mertonian_analysis.csv`

- **`notebooks/`**  
  Jupyter Notebooks for analysis:
  - `academic_inequality_analysis.ipynb`
  - `matthew_effect_temporal_analysis.ipynb`
  - `north_south_citation_inequality.ipynb`
  - `run_all.ipynb` → **Reproduces all tables and figures in one click**

- **`scripts/nvivo_exports/`**  
  Qualitative outputs from NVivo:
  - `coding_frequencies.csv`
  - `thematic_summary_table.csv`
  - `word_freq_global_north.csv`
  - `word_freq_global_south.csv`

- **`output/figures/`**  
  Generated visualizations (e.g., Lorenz curves, trend plots, boxplots)

- **`output/tables/`**  
  Exported results (CSV and Excel files)

## 📚 Data Source & Ethical Use

- Data were extracted from Scopus and Web of Science, two widely used academic databases.
- The dataset includes only publicly available bibliographic metadata:  
  author names, journal titles, publication years, and citation counts.
- No personal, sensitive, or confidential information is included.
- This repository is shared for **non-commercial academic research and educational purposes only**.

### 📝 Ethical Considerations and Reproducibility
Ethical protocols include anonymization of all journal and organizational identifiers in the qualitative component to protect institutional reputations and enable candid analysis. No human subjects were directly involved; however, the study adheres to principles of epistemic justice by centering marginalized perspectives and critiquing structures of exclusion. To ensure full reproducibility and adherence to FAIR principles, all analytical scripts (Python/R/NVivo), cleaned datasets, codebooks, and a `run_all.ipynb` notebook reproducing every table and figure are publicly available in this repository:  
[https://github.com/arwendria68/The-Coloniality-of-Citation](https://github.com/arwendria68/The-Coloniality-of-Citation).  
This repository invites replication, validation, and scholarly extension by the global research community.

## ▶️ How to Run the Analysis

### Prerequisites
- Python 3.8 or higher
- Basic familiarity with Jupyter Notebook

### Steps
1. Clone this repository:
   ```bash
   git clone https://github.com/arwendria68/The-Coloniality-of-Citation.git
   cd The-Coloniality-of-Citation
   
## Install required packages:
- pip install -r requirements.txt

## Launch Jupyter:
- jupyter lab

## Open and run a notebook:
- In Jupyter, navigate to notebooks/
- Open either analysis notebook
- Select "Run All" from the menu (or run cells sequentially)
         
## All outputs (figures and tables) will be saved automatically to the output/ folder. 
