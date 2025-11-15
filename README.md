# Clustering Techniques Project

This project explores various **clustering algorithms** applied to a structured dataset to compare performance, evaluate cluster quality, and analyze results. The workflow includes exploratory data analysis (EDA), feature engineering, dimensionality reduction, and implementation of multiple clustering algorithms with comprehensive evaluation metrics.


## Visuals & Demo

* **Project Image:** [Watch Demo](assets/image.mp4)  
* **Project Documentation:** ![Documentation](assets/documentation.png)  


---

## **📊 About the Dataset**
The dataset used in this project is sourced from Kaggle: [Customer Segmentation Dataset](https://www.kaggle.com/datasets/vjchoudhary7/customer-segmentation-tutorial-in-python). It contains both numerical and categorical features suitable for unsupervised learning. The dataset was preprocessed to handle missing values, scale numerical features, and prepare it for clustering.

Key features include:
- Customer demographic and transactional information
- Numerical attributes suitable for distance-based clustering
- Categorical features encoded for algorithm compatibility

---

## **📄 Project Structure**
```

Clustering-Techniques/
├── Clustering_Techniques.ipynb      # Full EDA and clustering workflow
├── README.md                        # Project documentation
├── images/                           # Visualizations of clusters and metrics
└── requirements.txt                  # Dependencies

```

---

## **🔬 Project Workflow**

### 1️⃣ Exploratory Data Analysis (EDA)
- Inspect dataset, rename columns, check for missing values
- Univariate, bivariate, and multivariate analysis
- Visualizations including histograms, scatter plots, and boxplots
- Correlation heatmaps and descriptive statistics

### 2️⃣ Feature Engineering
- **Dimensionality Reduction:** Applied PCA to reduce feature space for better visualization and clustering performance
- **Feature Scaling:** Standardized numerical features to ensure algorithm compatibility

### 3️⃣ Clustering Techniques
- **Helper Methods for Optimal Cluster Identification:**
  - KElbow Method
  - Silhouette Score
  - Davies-Bouldin (DB) Score
  - Calinski-Harabasz (CH) Score
- **Implemented Algorithms:**
  - **KMeans & KMeans with PCA**
  - **Hierarchical Clustering**
  - **DBSCAN**
  - **Affinity Propagation**
  - **Mean Shift**
  - **OPTICS**

### 4️⃣ Model Evaluation
- Performance metrics (Silhouette, DB, CH Scores) used to compare algorithms
- Visual comparison via scatter plots of clusters
- Statistical analysis of clusters (mean, standard deviation, quartiles)

---

## **💡 Key Insights**
- PCA reduced dimensionality effectively while preserving cluster structures
- **KMeans and Hierarchical Clustering:** Best for well-separated, spherical clusters
- **DBSCAN and OPTICS:** Excelled in detecting clusters with noise and varying densities
- **Affinity Propagation:** Automatically determined number of clusters, offering flexibility
- Statistical analysis of clusters provided deeper insights into the internal structure of each cluster
- Using multiple evaluation metrics ensured robust comparison across algorithms

---

## **📌 Summary**
This project demonstrates how different clustering techniques can provide varied insights depending on the dataset structure. Key takeaways:
- Visual and statistical evaluation is crucial for understanding cluster quality
- Different algorithms suit different types of data: density-based, hierarchical, or centroid-based
- Combining dimensionality reduction, multiple clustering techniques, and performance metrics ensures comprehensive analysis and interpretable results

---

## **👤 Author**
**Emmanuel Odedele**  
Machine Learning | AI | Data Science
```