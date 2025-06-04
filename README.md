# Network-Anomaly-Detection-on-UNSW-NB15

This repository contains **` Network-Anomaly-Detection.ipynb`**, a step-by-step Jupyter notebook
that detects network attacks in the **UNSW-NB15** dataset.

### Key points
- Keeps only numeric features and handles missing values.  
- Standardizes the data with **StandardScaler**.  
- Applies **DBSCAN** clustering and **Isolation Forest** to spot anomalies  
  (label 1 = attack, label 0 = normal).  
- Visualises clusters with **PCA** (2-D scatter).  
- Tests several `eps` values for DBSCAN; best recall ≈ 0.27 at `eps=1.3`.
