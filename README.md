# Human Activity Recognition Using Smartphones – Unsupervised Learning & Feature Selection

**Author:** Alex Gurung  
**Course:** ARI510  

This repository contains the analysis of the [Human Activity Recognition Using Smartphones Dataset](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones), applying unsupervised learning techniques, feature selection, and supervised classification.

---


> **Note:** The dataset and virtual environment folders are **not included** in this repository. You can download the dataset from the [UCI HAR Dataset page](https://archive.ics.uci.edu/ml/datasets/human+activity+recognition+using+smartphones).

---

## 📊 Dataset

- Contains **561 features** extracted from smartphone sensor data.  
- **7,352 training samples** and **2,947 test samples**.  
- Six activity types: `WALKING`, `WALKING_UPSTAIRS`, `WALKING_DOWNSTAIRS`, `SITTING`, `STANDING`, `LAYING`.

---

## 🧠 Methods

1. **Unsupervised Learning**
   - **Principal Component Analysis (PCA)** – dimensionality reduction and visualization.
   - **Clustering Algorithms**
     - **K-Means**
     - **DBSCAN**

2. **Feature Selection**
   - Selected important features to improve model performance.
   
3. **Supervised Classification**
   - Models evaluated based on selected features and performance metrics.

---

## 📌 How to Run

1. Clone this repository:

git clone https://github.com/alexgurung/Human-Activity-Recognition-Unsupervised-Feature-Selection.git
cd Human-Activity-Recognition-Unsupervised-Feature-Selection

Download the dataset from UCI HAR Dataset
 and place it locally (optional if you want to re-run analysis).

Install Python dependencies (if not already installed):

pip install pandas numpy matplotlib scikit-learn seaborn


Open and run har_analysis.ipynb in Jupyter Notebook.

📈 Visualizations

Activity distributions, clustering results, PCA projections, silhouette scores, and feature importance plots are included as .png files.

📄 Report

See Report.pdf for detailed methodology, results, and analysis.
