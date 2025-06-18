# Charlotte Housing Market Modeling

This project explores how environmental and structural housing features impact **home sale prices** and **home ownership status** in Charlotte, NC. It was completed as part of DTSC 2302 and involved both regression and classification modeling using real-world neighborhood-level data.

## 📊 Project Goals

1. **Regression**: Predict *Home Sale Prices* using predictors like:
   - Housing Age
   - Housing Size
   - Residential New Construction
   - Housing Density
   - Home Ownership Rates

2. **Classification**: Predict *Home Ownership Status* (Good vs. Poor) using:
   - Housing Age
   - Housing Size
   - Housing Density
   - Residential New Construction
   - Home Sale Prices

## 🧠 Methodology

### 🔹 Regression Models
- **Linear Regression**: Initial models included 5 predictors, but many were insignificant. A refined model using just *Housing Age* and *Housing Size* explained 15–16% of variability.
- **Regression Tree**: Used to visualize splits based on size and age. Provided intuitive rules but limited depth due to data.
- **Generalized Additive Model (GAM)**: Outperformed others with an R² of 32.4%, capturing non-linear effects of housing size.

### 🔹 Classification Models
- Tested multiple algorithms: **LDA**, **QDA**, **KNN**, **Decision Tree**, **Linear SVM**, **RBF SVM**
- **LDA** was the best model:
  - **Accuracy**: 77.11%
  - **Cross-validation score**: 76.05%

## 🧪 Tools Used
- Python (Pandas, Scikit-learn, Statsmodels)
- R (for GAM and visualizations)
- Jupyter Notebook / PDF Report

