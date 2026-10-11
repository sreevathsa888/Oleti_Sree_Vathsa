# Exploratory Data Analysis (EDA) Course Project - 23BDS0143

## Student Information

* **Name:** Oleti Sree Vathsa
* **Register Number:** 23BDS0143
* **Course:** B.Tech Computer Science and Engineering (Data Science)
* **Institution:** Vellore Institute of Technology (VIT), Vellore

---

## Project Description

This repository contains the **Phase 1, Phase 2, and Phase 3 Exploratory Data Analysis (EDA)** course project completed using **Google Colab** and **Python**.

The project demonstrates data preprocessing, statistical analysis, data cleaning, transformation, visualization, and clustering techniques on the **Males.csv** dataset.

---

## Dataset

* **Dataset Name:** Males.csv
* **Dataset Source:** https://raw.githubusercontent.com/salemprakash/EDA/main/Data/Males.csv

---

## Objectives

### Phase 1

* ✔ Loading the dataset
* ✔ Dataset information and structure
* ✔ Basic statistical analysis
* ✔ Missing value detection
* ✔ Handling missing values
* ✔ Data cleaning
* ✔ Data transformation using Label Encoding
* ✔ Correlation analysis
* ✔ Univariate Analysis
* ✔ Bivariate Analysis
* ✔ Multivariate Analysis

### Phase 2

* ✔ 1D Statistical Analysis
* ✔ 2D Statistical Analysis
* ✔ 3D Statistical Analysis
* ✔ K-Means Clustering
* ✔ Hierarchical Clustering

### Phase 3

* ✔ Principal Component Analysis (PCA)
* ✔ Standardization of selected numerical features
* ✔ Explained variance and cumulative explained variance
* ✔ Scree plot and cumulative variance plot
* ✔ Principal component loadings
* ✔ PC1 vs PC2 visualization
* ✔ Number of components required to retain at least 90% variance

---

## Phase 2 Analysis

### 1D Statistical Analysis

The following statistical measures and visualizations were performed:

* Mean
* Median
* Mode
* Variance
* Standard Deviation
* Minimum and Maximum
* Quartiles
* Skewness
* Kurtosis
* Histograms with KDE
* Box Plots
* Distribution Analysis

### 2D Statistical Analysis

Relationships between two variables were explored using:

* Correlation Matrix
* Scatter Plots
* Regression Analysis
* Schooling vs Wage
* Experience vs Wage
* Year vs Wage
* Union Status vs Wage
* Experience Groups vs Wage
* Categorical vs Numerical Comparisons

### 3D Statistical Analysis

Three-variable relationships were visualized using:

* Experience vs Wage vs Year
* Schooling vs Experience vs Wage
* Year vs Schooling vs Wage
* 3D multivariate scatter visualizations

### K-Means Clustering

K-Means clustering was performed using:

* Schooling
* Experience
* Wage

The following steps were performed:

1. Feature selection
2. Feature standardization
3. Elbow Method
4. Silhouette Score Analysis
5. K-Means clustering
6. 2D cluster visualization
7. 3D cluster visualization
8. Cluster profiling

### Hierarchical Clustering

Agglomerative hierarchical clustering was performed using **Ward linkage**.

The analysis includes:

* Data standardization
* Linkage matrix
* Dendrogram
* Agglomerative clustering
* 2D cluster visualization
* 3D cluster visualization
* Silhouette Score evaluation

---

## Phase 3 Analysis - Principal Component Analysis (PCA)

PCA is performed on the existing cleaned `df` using the numerical features `year`, `school`, `exper`, and `wage`. Identifier columns and label-encoded categorical columns are excluded from the PCA feature set. The selected features are standardized before PCA so that differences in scale do not dominate the result.

The analysis includes:

* StandardScaler preprocessing
* Principal component transformation
* Explained variance ratio for each component
* Cumulative explained variance and the 90% threshold
* Scree plot
* Cumulative explained variance plot
* Principal component loadings table
* PC1 vs PC2 scatter plot

### Phase 3 Visualizations

* PCA Scree Plot
* Cumulative Explained Variance Plot
* PC1 vs PC2 Scatter Plot

---

## Libraries Used

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Scikit-learn
* SciPy

---

## Visualizations

### Phase 1

#### Univariate Analysis

* Histogram with KDE, Mean and Median
* Box Plot
* Count Plot

#### Bivariate Analysis

* Scatter Plot with Regression Line
* Bar Plot
* Box Plot

#### Multivariate Analysis

* Pair Plot
* Correlation Heatmap
* Scatter Matrix

### Phase 2

#### 1D Analysis

* Distribution Histograms
* KDE Plots
* Box Plots
* Skewness Visualization

#### 2D Analysis

* Correlation Heatmap
* Scatter Plots
* Regression Plot
* Box Plots
* Group Comparisons
* Experience Group Analysis

#### 3D Analysis

* 3D Scatter Plots
* Multivariate 3D Visualizations

#### Clustering

* K-Means Elbow Plot
* K-Means Silhouette Plot
* K-Means 2D Clusters
* K-Means 3D Clusters
* Hierarchical Dendrogram
* Hierarchical 2D Clusters
* Hierarchical 3D Clusters

---

## Repository Structure

```text
├── README.md
└── EDA_Course_Project_23BDS0143_Males_Dataset_Phase3_PCA.ipynb
```

---

## How to Run

1. Open the notebook in **Google Colab**.
2. Run the notebook cells sequentially.
3. Execute the Phase 1, Phase 2, and Phase 3 analysis.
4. Review the generated statistical results and visualizations.
5. Save the updated notebook to the **same GitHub repository**.

---

## Results

The project provides a complete Exploratory Data Analysis workflow covering:

* Dataset understanding and preprocessing
* Missing value treatment
* Duplicate checking and removal
* Categorical feature encoding
* 1D statistical analysis
* 2D relationship analysis
* 3D multivariate visualization
* K-Means clustering
* Hierarchical clustering
* Cluster evaluation using silhouette scores
* PCA-based dimensionality reduction
* Explained variance and component loading analysis

The Phase 2 extension provides additional statistical and clustering analysis of relationships among **schooling, experience, wage, and other attributes** in the dataset. Phase 3 applies PCA to standardized `year`, `school`, `exper`, and `wage` features to summarize variance and visualize observations in principal-component space.

---

## GitHub Repository

**Repository:** https://github.com/sreevathsa888/Oleti_Sree_Vathsa

---

## Author

**Oleti Sree Vathsa**

Register Number: **23BDS0143**

Vellore Institute of Technology (VIT), Vellore
