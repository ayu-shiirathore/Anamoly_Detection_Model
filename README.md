# Anomaly Detection and Removal

## Project Overview

This project focuses on detecting and removing anomalies from a dataset using multiple anomaly detection techniques. It also evaluates the performance of clustering models on the cleaned data. By leveraging the **PyCaret** library for anomaly detection and **scikit-learn** for clustering, this project aims to identify outliers and assess the effectiveness of various models in anomaly detection and clustering.

The goal is to help users understand the underlying patterns in their data by identifying and handling anomalies effectively, which is crucial for improving data quality and ensuring more accurate predictions in machine learning tasks.

## Key Features

- **Multiple Anomaly Detection Models**: The project uses various anomaly detection models to detect outliers in the dataset, including:
  - **ABOD (Angle-based Outlier Detection)**
  - **Cluster-based Anomaly Detection**
  - **COF (Connectivity-based Outlier Factor)**
  - **Isolation Forest (iForest)**
  - **Histogram-based Outlier Detection**
  - **K-Nearest Neighbors (KNN)**
  - **Local Outlier Factor (LOF)**
  - **Support Vector Machine (SVM)**
  - **Principal Component Analysis (PCA)**
  - **Minimum Covariance Determinant (MCD)**
  - **Subspace Outlier Detection (SOD)**
  - **Smallest Observation Subspaces (SOS)**

- **Clustering on Cleaned Data**: After detecting and removing anomalies, the cleaned data is subjected to clustering using the **KMeans** algorithm. The performance of the clusters is evaluated using the **Silhouette Score**, which measures the quality of the clusters based on their compactness and separation.

- **Model Evaluation**: The project evaluates each anomaly detection model by:
  - Counting the number of detected anomalies
  - Displaying the model's parameters
  - Evaluating the clustering quality using the **Silhouette Score**

- **Easy-to-Follow Workflow**: The project provides a clean and understandable workflow, with results displayed for each model, including anomaly counts, model parameters, and silhouette scores.

## Getting Started

### Prerequisites

To run this project, you'll need to install the following libraries:

- `pycaret`
- `scikit-learn`

You can install them using `pip`:

```bash
pip install pycaret scikit-learn
