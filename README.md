# Network Traffic Anomaly Detection

![Python](https://img.shields.io/badge/Python-3.7%2B-blue)
![License](https://img.shields.io/badge/License-MIT-green)
![Status](https://img.shields.io/badge/Status-In%20Development-yellow)

A machine learning project for detecting anomalies in network traffic using DBSCAN, Isolation Forest, and Autoencoder techniques.

## Features

- Data preprocessing and exploratory data analysis
- Implementation of three anomaly detection techniques:
  - DBSCAN
  - Isolation Forest
  - Autoencoder
- Visualization of results using PCA
- Performance evaluation with ROC and Precision-Recall curves

## Requirements

- Python
- pandas
- numpy
- scikit-learn
- matplotlib
- seaborn

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Satviksangamkar/Advanced-Anomaly-Detection-in-Network-Traffic-Using-Autoencoders-DBSCAN-and-Isolation-Forest
   cd network-traffic-anomaly-detection
2. Install required packages:
   ```bash
   pip install -r requirements.txt
## Usage

1. Ensure you have the KDD Cup 1999 dataset or your own network traffic dataset in the `data/` directory.

2. Run the Jupyter notebook:
   ```bash
   jupyter notebook notebooks/anomaly_detection.ipynb
   
3. Follow the notebook cells to perform data preprocessing, EDA, and anomaly detection.
## Methodology

The project employs three anomaly detection techniques:

1. **DBSCAN**: Density-based clustering for identifying outliers.
2. **Isolation Forest**: Ensemble method that explicitly isolates anomalies.
3. **Autoencoder**: Neural network approach for detecting anomalies based on reconstruction error.

## Results

- Feature visualizations and correlation analysis
- Performance metrics for each detection method
- PCA visualizations of anomaly detection results
- ROC and Precision-Recall curves
