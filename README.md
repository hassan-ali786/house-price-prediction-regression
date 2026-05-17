# House Price Prediction using Regression

A machine learning project that predicts house prices using real-world real estate data and regression techniques.  
The project analyzes property features and builds predictive models to estimate housing prices accurately using the California Housing Dataset.

---

## Project Overview

This project predicts housing prices based on property features:

- Explore and preprocess housing data  
- Visualize price distribution and feature relationships  
- Build regression models to predict median house value  
- Evaluate model performance using RMSE and R² score  

**Objectives:**  

- Understand regression techniques on real-world data  
- Compare Linear Regression vs Polynomial Regression  
- Interpret feature importance through model coefficients  

---

## Dataset Information

- **Source:** California Housing Dataset (scikit-learn)  
- **Type:** Real-world housing data  
- **Target Variable:** Median House Value  
- **Features Include:**  
  - Median Income  
  - House Age  
  - Average Rooms  
  - Average Bedrooms  
  - Population  
  - Latitude & Longitude  

---

## Project Workflow

1. Data Loading & Exploration  
2. Data Cleaning & Outlier Handling (IQR Method)  
3. Price Distribution Visualization  
4. Feature Selection  
5. Model Building  
   - Linear Regression  
   - Polynomial Regression (Degree = 2)  
6. Model Evaluation using RMSE & R² Score  
7. Interpretation of Regression Coefficients  

---

## Models Used

- **Linear Regression**  
- **Polynomial Regression (Degree = 2)**  

---

## Evaluation Metrics

- **RMSE (Root Mean Squared Error)** – Measures prediction error  
- **R² Score (Coefficient of Determination)** – Measures variance explained by the model  

---

## Project Structure

```bash
house-price-prediction-regression/
├── notebooks/
│   └── house_price_prediction_regression.ipynb
├── requirements.txt
├── README.md
```

---

## Tools & Technology Stack

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)  
![Pandas](https://img.shields.io/badge/Pandas-150458?style=flat&logo=pandas&logoColor=white)  
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat&logo=numpy&logoColor=white)  
![Matplotlib](https://img.shields.io/badge/Matplotlib-007D9C?style=flat&logo=matplotlib&logoColor=white)  
![Scikit-learn](https://img.shields.io/badge/Scikit--learn-F7931E?style=flat&logo=scikit-learn&logoColor=white)  
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat&logo=jupyter&logoColor=white)  

---

## How to Run

1. Clone the repository:

```bash
git clone https://github.com/hassan-ali786/house-price-prediction-regression.git
cd house-price-prediction-regression
```

2. Install dependencies:

```bash
pip install -r requirements.txt
```

3. Open the notebook:

```bash
jupyter notebook notebooks/House_Price_Prediction_Regression.ipynb
```

4. Run all cells to reproduce analysis and model predictions.  

---

## Key Learnings

- Handling real-world datasets and outliers  
- Understanding regression behavior and assumptions  
- Comparing linear vs polynomial regression models  
- Interpreting feature importance using regression coefficients  

---

## Future Improvements

- Add Decision Tree & Random Forest regression models  
- Hyperparameter tuning for better accuracy  
- Deploy as a web app using Streamlit  
- Feature engineering for improved predictive performance  

---

## Author

**Hassan Ali**  
Data Scientist | Machine Learning Engineer  

GitHub: https://github.com/hassan-ali786  

---

⭐ Feel free to fork this repository and explore further improvements!
