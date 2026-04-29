# Health Expenditure in Australia: Classification & Clustering 🏥📊

This project applies **data mining techniques** to analyze healthcare expenditure in Australia. Using **R**, the study combines supervised learning (classification) and unsupervised learning (clustering) to uncover spending patterns and provide evidence-based insights for policy optimization.

## 📊 Dataset
- Source: [Australian Government Open Data Portal](https://data.gov.au/search?q=health+expenditure)
- Publisher: Australian Institute of Health and Welfare
- Attributes:
  - `financial_year` – reporting year
  - `state` – region of expenditure
  - `area_of_expenditure` – healthcare sector (e.g., hospitals, pharmaceuticals)
  - `broad_source_of_funding` – government vs. non-government
  - `detailed_source_of_funding` – granular funding source
  - `real_expenditure_millions` – expenditure amount

## ⚙️ Methodology
1. **Data Cleaning & Preparation**
   - Missing value imputation
   - Data type conversion
   - Normalization & scaling
2. **Classification (Supervised Learning)**
   - Decision Tree
   - Random Forest
   - K-Nearest Neighbors (KNN)
   - Evaluation: Accuracy, Precision, Recall, F1-score, ROC-AUC
3. **Clustering (Unsupervised Learning)**
   - K-Means (Elbow method for optimal clusters)
   - DBSCAN
   - Gaussian Mixture Models (GMM)
   - Evaluation: Silhouette score, inertia
4. **Visualization**
   - Time-series plots
   - Bar charts by state
   - Correlation heatmaps
   - Cluster visualizations

## 🚀 Results
- **Random Forest** was the best-performing classification model.
- **K-Means clustering** grouped similar private hospitals by expenditure trends.
- Clear patterns emerged in government vs. non-government funding sources.
- Evidence-based insights can support **policy optimization** in Sri Lanka’s public health sector.

## 🛠️ Tech Stack
- R, RStudio
- Libraries: `ggplot2`, `dplyr`, `randomForest`, `class`, `factoextra`, `Mclust`, `dbscan`


---

✨ *This project demonstrates how classification and clustering can uncover healthcare expenditure patterns for better resource allocation.*
