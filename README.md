# Iris Dataset - Exploratory Data Analysis (EDA)

## Project Overview
This project involves a detailed exploratory data analysis (EDA) of the Iris dataset. The Iris dataset is a well-known dataset for pattern recognition, containing information about the sepal and petal dimensions of three Iris species: Setosa, Versicolor, and Virginica.

### Key Objectives
1. Analyze the dataset structure and identify patterns or trends.
2. Perform univariate and multivariate analysis to explore relationships between features.
3. Use visualizations and summary insights to highlight key findings.

---

## Tasks & Analysis

### 1. Data Inspection
- Checked for missing values, duplicates, and data types.
- Examined dataset dimensions and unique class labels.

### 2. Univariate Analysis
- Plotted histograms and boxplots for sepal and petal dimensions.
- Identified skewness and outliers for each feature.

### 3. Multivariate Analysis
- Created pair plots to analyze relationships between features.
- Explored feature variation across the three Iris species using boxplots.

### 4. Correlation Analysis
- Computed a correlation matrix to identify relationships between features.
- Found that **petal length** and **petal width** were highly correlated.

---

## Tools Used
- **Python**: `pandas`, `matplotlib`, `seaborn`
- **Jupyter Notebook**: For analysis and visualization.

---

## Summary Insights
1. **Distinctive Features**: Petal dimensions (length and width) are the most useful for classifying Iris species.
2. **Class Separation**:
   - **Setosa** is the easiest to classify, as it is distinct in all pair plots.
   - **Versicolor** and **Virginica** overlap more, making them harder to separate.
3. **Correlations**:
   - Petal length and petal width show the strongest positive correlation.

---

## Repository Structure

---

## How to Use
1. Clone the repository:
   ```bash
   git clone https://github.com/<your-username>/iris-eda.git
