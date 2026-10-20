# Anomaly Detection of Time Series Data: KNN vs LOF vs EWMA

Honours research by Patel Mohamed Suhail (supervisor: Montaz Ali). Compares K-Nearest Neighbour, Local Outlier Factor and Exponentially Weighted Moving Average for anomaly detection on four Numenta Anomaly Benchmark (NAB) series using sliding windows.

## Run
```
pip install -r requirements.txt
jupyter notebook anomaly_detection.ipynb
```
Run all cells; `results/` and `figures/` are regenerated. Data: `nab_data/` (NAB, AGPL-3.0, https://github.com/numenta/NAB).
