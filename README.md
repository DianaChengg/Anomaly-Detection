# Bloomberg Industry Program: Anomaly Detection in Stock Returns

## Project Overview
Detecting anomalies in large datasets is a challenging problem with numerous applications in finance. If a stock is flagged as having anomalous returns, it could simply be due to recent news, or it could indicate hidden risks that need to be considered. Machine learning models are traditionally effective at finding patterns by aggregating weak signals over large datasets, making them well-suited for anomaly detection in stock returns.

## Goals
The primary objectives of this project are:
1. **Model Development:** Build and evaluate anomaly detection models of increasing complexity to detect anomalies in stock returns.
2. **Qualitative Analysis:** Apply these models to analyze the types of anomalies they detect and those they miss.
3. **Visualization Interface:** Develop an interactive and compelling interface to visualize model outputs for enhanced interpretability and decision-making.


## Methodologies
The project employs a range of anomaly detection techniques, including but not limited to:

- **DBSCAN (Density-Based Spatial Clustering of Applications with Noise):** Identifies anomalies as points in low-density regions.
- **Isolation Forest:** Leverages the isolation principle to detect anomalies efficiently.
- **Autoencoders:** Uses deep learning to reconstruct input data and detect anomalies based on reconstruction errors.
- **LSTM (Long Short-Term Memory):** Captures temporal dependencies in stock return data for anomaly detection.
- **Statistical Models:** Traditional approaches such as Z-scores and moving averages.

## Data Sources
The dataset consists of 10 years of daily stock return data from the Russell 2000 index, including external factors such as VIX (volatility index) and news sentiment analysis.



