# Exploratory Data Analysis (EDA) Course Project - 23BDS0143

## Student Information

- **Name:** Oleti Sree Vathsa
- **Register Number:** 23BDS0143
- **Course:** B.Tech Computer Science and Engineering (Data Science)
- **Institution:** Vellore Institute of Technology (VIT), Vellore

---

## Project Description

This repository contains the **Phase 1, Phase 2, and Phase 3** course work completed using **Google Colab and Python** on the **Males.csv** dataset. The project covers exploratory data analysis, statistical analysis, clustering, dimensionality reduction, and Simple Linear Regression.

---

## Dataset

- **Dataset:** `Males.csv`
- **Source:** https://raw.githubusercontent.com/salemprakash/EDA/main/Data/Males.csv

The dataset contains variables such as year, schooling, experience, wage, union status, industry, occupation, and residence.

---

## Project Objectives

### Phase 1 — Exploratory Data Analysis

- Load and inspect the dataset
- Review dataset structure and descriptive statistics
- Identify and handle missing values
- Check and remove duplicate records
- Transform categorical variables using label encoding
- Perform correlation analysis
- Conduct univariate, bivariate, and multivariate analysis

### Phase 2 — Statistical Analysis and Clustering

- 1D statistical analysis
- 2D statistical analysis
- 3D statistical analysis
- K-Means clustering
- Hierarchical clustering

### Phase 3 — PCA and Simple Linear Regression

**Principal Component Analysis (PCA)**
- Select numerical features and standardize them
- Transform features into principal components
- Calculate explained variance and cumulative explained variance
- Identify the number of components needed to retain at least 90% variance
- Examine principal component loadings

**Simple Linear Regression (SLR)**
- Select one numerical independent variable (`exper`) and one numerical dependent variable (`wage`)
- Calculate Pearson correlation
- Split the data into training and testing sets
- Fit a Simple Linear Regression model
- Calculate and interpret the intercept, slope, and regression equation
- Predict wage values for test observations and new experience values
- Evaluate predictions using MAE, MSE, RMSE, and R-squared
- Perform statistical inference using coefficient estimates, standard errors, t-statistics, p-values, confidence intervals, and the overall F-test
- Calculate and interpret residuals
- Examine residuals against fitted values
- Assess residual distribution using a histogram and Q-Q plot
- Check regression assumptions using diagnostic tests, including Shapiro-Wilk, Breusch-Pagan, and Durbin-Watson

---

## Phase 1 Analysis

Phase 1 focuses on understanding the dataset and its variables. It includes dataset inspection, descriptive statistics, data cleaning, categorical encoding, correlation analysis, and univariate, bivariate, and multivariate exploration.

### Visualizations

- Histograms and density plots
- Box plots
- Count plots
- Scatter plots with regression lines
- Pair plots
- Correlation heatmaps
- Scatter matrices

---

## Phase 2 Analysis

### 1D Statistical Analysis

- Mean, median, and mode
- Variance and standard deviation
- Minimum, maximum, and quartiles
- Skewness and kurtosis
- Distribution analysis

### 2D Statistical Analysis

- Correlation analysis
- Relationships such as schooling vs wage, experience vs wage, and year vs wage
- Union status vs wage
- Experience groups vs wage
- Categorical and numerical comparisons

### 3D Statistical Analysis

- Experience vs wage vs year
- Schooling vs experience vs wage
- Year vs schooling vs wage
- Three-variable visualizations

### K-Means Clustering

The clustering analysis uses selected numerical features, including schooling, experience, and wage. It includes feature standardization, the elbow method, silhouette score analysis, clustering, visualization, and cluster profiling.

### Hierarchical Clustering

Agglomerative hierarchical clustering with Ward linkage includes data standardization, a linkage matrix, a dendrogram, cluster assignment, visualization, and silhouette score evaluation.

---

## Phase 3 Analysis

### Principal Component Analysis (PCA)

PCA is applied to selected numerical features (`year`, `school`, `exper`, and `wage`). The features are standardized before PCA so that differences in scale do not dominate the analysis.

The analysis includes:
- StandardScaler preprocessing
- Principal component transformation
- Explained variance ratio and cumulative explained variance
- Identifying the number of components required to retain at least 90% variance
- Principal component loadings
- PCA visualizations, including the scree plot, cumulative variance plot, and PC1 vs PC2 plot

### Simple Linear Regression (SLR)

SLR models the linear relationship between **experience (`exper`)** and **wage (`wage`)**. Experience is the independent variable, and wage is the dependent variable.

The SLR workflow includes:
1. Selecting the independent and dependent variables
2. Calculating the Pearson correlation coefficient
3. Splitting the data into training and testing sets
4. Training a `LinearRegression` model
5. Calculating the intercept and slope and writing the regression equation
6. Predicting wage values for the test set and new experience values
7. Evaluating the model with MAE, MSE, RMSE, and R-squared
8. Obtaining a statistical model summary using `statsmodels`
9. Testing slope significance using a p-value
10. Calculating 95% confidence intervals
11. Calculating residuals and plotting residuals against fitted values
12. Examining the residual distribution using a histogram and Q-Q plot
13. Checking residual normality, constant variance, and possible first-order autocorrelation using diagnostic tests

The training-set statistical summary and residual diagnostics are used to examine the fitted model, while the test set is used to assess predictive performance on held-out observations. Diagnostic tests are interpreted as evidence about assumptions rather than as automatic proof that an assumption is satisfied.

---

## Libraries Used

- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn
- Statsmodels
- SciPy

---

## Repository Structure

```text
├── README.md
└── EDA_Course_Project_23BDS0143_Males_Dataset.ipynb
```

---

## How to Run

1. Open the notebook in Google Colab.
2. Run the cells sequentially.
3. Execute the Phase 1, Phase 2, and Phase 3 sections as required.
4. Review the generated statistics, model outputs, and visualizations.
5. Save the updated notebook and README in the GitHub repository.

---

## Results

The project demonstrates a complete workflow covering exploratory data analysis, data preprocessing, statistical analysis, clustering, dimensionality reduction using PCA, and predictive modeling using Simple Linear Regression.

The SLR component estimates the relationship between experience and wage, evaluates prediction errors on held-out data, and uses coefficient inference and residual diagnostics to examine model fit and assumptions.

---

## GitHub Repository

**Repository:** https://github.com/sreevathsa888/Oleti_Sree_Vathsa

---

## Author

**Oleti Sree Vathsa**  
Register Number: **23BDS0143**  
Vellore Institute of Technology (VIT), Vellore
