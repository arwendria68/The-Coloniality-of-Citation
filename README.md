# The-Coloniality-of-Citation

This repository contains open data and reproducible code for analyzing citation inequality and the Matthew Effect in academic publishing.

## 📁 Project Structure

- `data/processed/`  
  Cleaned dataset: `processed_publications_for_mertonian_analysis.csv`
- `notebooks/`  
  Jupyter Notebooks for analysis:
  - `academic_inequality_analysis.ipynb`
  - `matthew_effect_temporal_analysis.ipynb`
- `output/figures/`  
  Generated visualizations (e.g., Lorenz curves, trend plots)
- `output/tables/`  
  Exported results (CSV and Excel files)

## 📚 Data Source & Ethical Use

- Data were extracted from **Scopus** and **Web of Science**, two widely used academic databases.
- The dataset includes only **publicly available bibliographic metadata**:  
  author names, journal titles, publication years, and citation counts.
- **No personal, sensitive, or confidential information** is included.
- This repository is shared for **non-commercial academic research and educational purposes only**.
- If you use this data or code in your work, please:
  - Cite the associated publication (if available)
  - Acknowledge the author: Arwen Dria Dahlan
  - Contact the author for collaborative or derivative uses: arwendriadahlan@uinib.ac.id

## ▶️ How to Run the Analysis

### Prerequisites
- Python 3.8 or higher
- Basic familiarity with Jupyter Notebook

### Steps
1. **Clone this repository**:
   ```bash
   git clone https://github.com/arwendria68/The-Coloniality-of-Citation.git
   cd The-Colonity-of-Citation
## Install required packages:
- pip install -r requirements.txt

## Launch Jupyter:
- jupyter lab

## Open and run a notebook:
- In Jupyter, navigate to notebooks/
- Open either analysis notebook
- Select "Run All" from the menu (or run cells sequentially)
         
## All outputs (figures and tables) will be saved automatically to the output/ folder. 
