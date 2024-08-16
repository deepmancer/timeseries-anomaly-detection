# 📈 Time Series Classic Anomaly Detection

<p align="center">
  <img src="https://img.shields.io/badge/scikitlearn-F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white" alt="scikit-learn">
  <img src="https://img.shields.io/badge/Python-3.6+-3776AB.svg?style=for-the-badge&logo=Python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/Jupyter-Notebook-F37626.svg?style=for-the-badge&logo=Jupyter&logoColor=white" alt="Jupyter">
</p>

---

## 📖 Overview

This repository provides an in-depth exploration of time series anomaly detection techniques, utilizing classic machine learning models. The project is implemented in a Jupyter Notebook, which offers an interactive environment to experiment with and understand the methods used for detecting anomalies in time series data.

---

## 📝 Project Description

Time series anomaly detection is a critical task in various domains, from finance to IoT, where identifying unexpected behavior in data is essential for decision-making and security. This project explores classic anomaly detection techniques tailored for time series data, including methods like:

- **Z-Score Analysis**: Detects anomalies based on statistical deviation.
- **Rolling Statistics**: Uses moving averages and standard deviations to flag anomalies.
- **Isolation Forest**: A tree-based model that isolates anomalies in high-dimensional data.
- **Local Outlier Factor (LOF)**: Identifies anomalies based on the local density of data points.
- **Autoencoders**: Neural networks trained to reconstruct input data, with anomalies detected as poorly reconstructed instances.

### Key Features:

- **Step-by-Step Implementation**: Each method is implemented from scratch, with explanations provided for the underlying concepts.
- **Interactive Exploration**: The Jupyter Notebook format allows for interactive experimentation, making it easy to adjust parameters and observe the effects on anomaly detection.
- **Visualizations**: Detailed plots and graphs are included to visualize the data and highlight detected anomalies.

---

## 🛠️ Prerequisites

Ensure that you have the following dependencies installed to run the Jupyter Notebook:

- **Python 3.6+**
- **Jupyter Notebook**
- **Pandas**
- **NumPy**
- **Scikit-learn**
- **Matplotlib**
- **Seaborn**

You can install the required libraries via pip:

```bash
pip install jupyter pandas numpy scikit-learn matplotlib seaborn
```
