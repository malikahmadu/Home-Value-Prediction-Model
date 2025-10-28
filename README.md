# 🏠 Home Value Prediction Model

A data science project that uses Python and machine learning to predict housing prices based on key property features. The project explores data cleaning, visualization, and model evaluation using real-world housing data.

## 🧰 Tech Stack
- **Python**
- **Pandas**, **NumPy**
- **scikit-learn**
- **Matplotlib**, **Seaborn**
- **Jupyter Notebook**

## ⚙️ Features
- Loads and cleans housing data from `home_dataset.csv`
- Performs exploratory data analysis (EDA) to identify key predictors of home prices
- Builds and trains a **Linear Regression** model using scikit-learn
- Evaluates model accuracy with metrics like MAE, MSE, and R²
- Visualizes correlations, feature importance, and residual trends

## 🚀 How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/malikahmadu/HomeValuePrediction.git
   cd HomeValuePrediction

## Install Dependecies
pip install pandas numpy scikit-learn matplotlib seaborn jupyter

## Example Output
| Feature     | Coefficient |
| ----------- | ----------- |
| LotArea     | 0.0045      |
| OverallQual | 21000.32    |
| GrLivArea   | 85.76       |
