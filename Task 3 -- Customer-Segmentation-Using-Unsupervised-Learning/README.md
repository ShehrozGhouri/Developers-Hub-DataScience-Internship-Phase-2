# Task 3: Customer Segmentation Using Unsupervised Learning

## 📌 Objective
Cluster a retail establishment's clientele based on their annual income and spending metrics to discover natural personas and propose tailored, data-driven marketing frameworks.

## 📊 Dataset
* **Source:** Mall Customers Dataset
* **Core Dimensions:** 200 records, 5 structural columns (`CustomerID`, `Gender`, `Age`, `AnnualIncome`, `SpendingScore`).

## 🛠️ Implementation Workflow
1. **Exploratory Data Analysis (EDA):** Evaluated value distributions for continuous age features and mapped spending scores across genders.
2. **Disparity Feature Scaling:** Implemented `StandardScaler` transformations to eliminate variable scale variations before calculating distance measurements.
3. **Optimal K Selection:** Calculated the Within-Cluster Sum of Squares (WCSS) across alternative configurations (K=1 to 10) to identify the optimal elbow convergence point at **K=5**.
4. **Dimensionality Reduction:** Compressed the 3D feature profile down to flat coordinates using Principal Component Analysis (PCA) for straightforward 2D visualization.
5. **Strategic Action Plans:** Grouped structural coordinates to define five customer personas:
   * *Loyal Senior Mid-Spenders* (Baseline Volume Pillar)
   * *Elite Spenders* (High-Value Premium Focus)
   * *Young Impulsive Buyers* (High Consumption / Low Income)
   * *Young Pragmatic Shoppers* (Value-Driven Bundles)
   * *Affluent Strategic Savers* (High Income / Defensive Spending)

## 📁 Repository Artifacts Inside This Folder
* `Mall_Customers.csv` - Raw client baseline dataset.
* `eda_distributions.png` - Continuous feature histograms.
* `elbow_curve.png` - WCSS elbow selection plot.
* `customer_clusters.png` - 2D cluster visualization via PCA.
* `mall_customers_segmented.csv` - Final dataset complete with cluster assignments.
* `kmeans_customer_model.pkl` - Trained, production-ready clustering model artifact.
* `customer_scaler.pkl` - Serialized StandardScaler instance for upcoming inference data.

## 🚀 Key Skills Demonstrated
* Unsupervised Clustering Frameworks (K-Means)
* Linear Dimensionality Reduction (PCA)
* Behavioral Persona Profiling & Business Action Design
