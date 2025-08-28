# bank-telemarketing-classification
Classification analysis of UCI Bank Marketing dataset — Machine Learning with Scikit-Learn, Pandas, NumPy, Matplotlib.

## Team & Contributions
- Viktor Trilar
- Oleksandr Yakovlev
- **Zoi Theofilakou — Step 1: Data exploration, preprocessing, visualizations & interpretation**  
  (EDA: histograms, boxplots, correlation matrix, target correlations; observations and insights.)
  
## Repo Structure
- `data/` → dataset CSVs + citation
- `notebooks/` → Jupyter notebooks (analysis)
- `reports/` → HTML reports (exported notebooks)
- `src/` → helper scripts (optional)
- `models/` → saved ML models (optional)

## Results (Step 1: EDA)
- Explored dataset distributions (histograms, boxplots).
- Identified skewed features and outliers.
- Correlation analysis highlighted **duration**, **previous contacts**, and **poutcome** as strong predictors.

## Quickstart
```bash
git clone https://github.com/zoi-theofilakou/bank-telemarketing-classification.git
cd bank-telemarketing-classification
python -m venv .venv && source .venv/bin/activate  # Windows: .venv\Scripts\Activate
pip install -r requirements.txt
jupyter lab

## Dataset
UCI Bank Marketing dataset (Moro et al., 2014).  
See `data/README.md` for full citation.

See `data/README.md` for dataset source and citation.

  


