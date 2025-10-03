# House Prices Analysis

**Short description:** Exploratory analysis and modeling of house prices. Includes data cleaning, visualizations, and baseline models.

## Contents
- `data/` — dataset (if small) or link to dataset
- `notebooks/` — Jupyter notebooks (EDA, modeling)
- `scripts/` — reusable scripts
- `results/` — plots, model outputs

## How to run
### Option A — Run in Google Colab
Open the notebook in Colab (File → Open notebook → GitHub → paste this repo URL) or click the Colab badge if present.

### Option B — Run locally
```bash
git clone https://github.com/<your-username>/House-prices-analysis.git
cd House-prices-analysis
python -m venv venv
source venv/bin/activate   # or venv\Scripts\activate on Windows
pip install -r requirements.txt
jupyter notebook
