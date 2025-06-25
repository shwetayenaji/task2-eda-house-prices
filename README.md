# 🏠 Task 2: Exploratory Data Analysis (EDA) – House Prices Dataset

## 📌 Objective

The goal of this task is to explore and understand the structure, relationships, and distribution of the data using statistical summaries and visualizations. This analysis helps in identifying important features, patterns, outliers, and trends that influence house prices.

---

## 🗂 Dataset

- **Dataset Name:** House Prices - Advanced Regression Techniques  
- **Source:** [Kaggle Link](https://www.kaggle.com/datasets/camnugent/house-prices-advanced-regression-techniques)  
- **File Used:** `train.csv`  

---

## 📊 Exploratory Steps Performed

1. **Dataset Overview**
   - Displayed data types, null counts, and basic structure.
   - Calculated summary statistics (mean, median, std, etc.)

2. **Missing Value Analysis**
   - Visualized missing values using a heatmap.
   - Noted that features like `PoolQC`, `Fence`, `Alley`, etc. have high missingness.

3. **Univariate Analysis**
   - Plotted histograms of key numeric features to examine their distribution.
   - Used boxplots to detect outliers in `SalePrice` and other numeric columns.

4. **Correlation Analysis**
   - Created a correlation heatmap to identify highly correlated features.
   - Found that `OverallQual`, `GrLivArea`, and `GarageCars` are strongly correlated with `SalePrice`.

5. **Multivariate Analysis**
   - Plotted pairplots for the top correlated features.
   - Observed clear trends and positive relationships with price.

6. **Categorical Insights**
   - Analyzed the impact of `Neighborhood`, `GarageType`, and `HouseStyle` on `SalePrice` using boxplots.

---

## 🔍 Key Insights & Inferences

- **OverallQual** is the strongest predictor of `SalePrice`.
- Larger homes (`GrLivArea`, `TotalBsmtSF`) tend to be more expensive.
- **Neighborhood** greatly affects price, indicating the value of location.
- Skewed features like `SalePrice`, `LotArea` may require log transformation.
- Outliers exist in features like `GrLivArea` and `SalePrice`.

---

## 🛠 Tools Used

- Python
- Pandas, NumPy
- Seaborn, Matplotlib

---

## 📁 Files in This Repo

| File Name                | Description                                  |
|--------------------------|----------------------------------------------|
| `train.csv`              | Original dataset from Kaggle                 |
| `eda_house_prices.ipynb` | Notebook containing EDA code and visuals     |
| `README.md`              | This project summary and explanation         |

---

## 👩‍💻 Author

**Shweta Yenaji**  


