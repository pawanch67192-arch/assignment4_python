# Weather Data Visualizer - Pawan Chauhan

**Course:** Programming for Problem Solving using Python  
**Assignment:** Data Analysis and Visualization with Real-World Weather Data

## Dataset
- Source: (add dataset source & citation here, e.g., Kaggle / IMD / local station)
- File(s): `data/raw/<raw_file>.csv`
- Columns used: date, temperature_max, temperature_min, rainfall, humidity, wind_speed (adjust to your dataset)

## Tools & Libraries
- Python 3.8+
- pandas, numpy, matplotlib, seaborn (optional), jupyter

## What’s included
- `notebooks/weather_analysis.ipynb` — full notebook with cleaning, analysis, and plotting
- `data/clean/weather_clean.csv` — cleaned dataset
- `outputs/plots/` — saved plot PNGs
- `REPORT.md` — summary & interpretation

## How to run
1. Create virtual env: `python -m venv venv && source venv/bin/activate`
2. Install: `pip install -r requirements.txt`
3. Open notebook: `jupyter notebook notebooks/weather_analysis.ipynb`
4. Or run script: `python scripts/weather_analysis.py --input data/raw/<file>.csv`

## Results summary
(Add 3–5 bullet insights here after you run the notebook)
