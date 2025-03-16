# 🏡 House Price Prediction using Machine Learning

## 📌 Project Overview
This project predicts house prices using machine learning models based on the **California Housing Dataset**. It includes data preprocessing, model training, evaluation, and prediction.

## 📂 Dataset Information
- **Dataset Name:** California Housing Prices
- **Source:** [Kaggle - California Housing Prices](https://www.kaggle.com/datasets/camnugent/california-housing-prices)
- **Format:** CSV
- **Features:**
  - `longitude`, `latitude` (Location coordinates)
  - `housing_median_age` (Age of housing units)
  - `total_rooms`, `total_bedrooms` (Total rooms and bedrooms)
  - `population`, `households` (Total population and households)
  - `median_income` (Median income in the area)
  - `ocean_proximity` (Categorical - distance to ocean)
  - `median_house_value` (Target variable)

## 🚀 Tech Stack
- **Python** (Pandas, NumPy, Matplotlib, Seaborn, Scikit-Learn, XGBoost)
- **Machine Learning Models:**
  - Linear Regression
  - Random Forest Regressor
  - XGBoost Regressor
- **Google Colab** (for training & evaluation)


```

## 🎯 How to Use
1. **Run the Python script or Jupyter Notebook**.
2. The script will:
   - Load and clean the dataset
   - Train **Linear Regression, Random Forest, and XGBoost**
   - Evaluate model performance (MSE, RMSE, R² score)
3. **Enter custom house details** to predict prices.
4. **View model accuracy** and compare different models.

## 📊 Model Performance
| Model               | MAE       | MSE          | RMSE       | R² Score |
|---------------------|-----------|--------------|------------|----------|
| Linear Regression  | 51,810.48  | 5.05B        | 71,133.17  | 0.614    |
| Random Forest      | 32,093.65  | 2.49B        | 49,880.46  | 0.810    |
| XGBoost           | 32,790.55  | 2.43B        | 49,300.77  | 0.815    |

✅ **Best Model:** **XGBoost (R² = 0.815)**

## 📂 Repository Structure
```
📦 house-price-prediction
├── 📜 README.md
├── 📜 requirements.txt
├── 📜 house_price_prediction.py
├── 📂 data
│   ├── housing.csv
├── 📂 notebooks
│   ├── House_Price_Prediction.ipynb
```

## 🔮 Future Improvements
- **Hyperparameter tuning** for better accuracy
- **Feature Engineering** (handling categorical variables, creating new features)
- **Deployment** using Flask or Streamlit for a user-friendly interface

## 📜 License
This project is licensed under the **MIT License**.

## 👨‍💻 Author
**SATYA VARDHAN**  


